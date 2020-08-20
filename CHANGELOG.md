1.0.7 / 2020-08-20
------------------

- Added Safari canvas GC workaround,  https://github.com/nodeca/pica/issues/199.


1.0.6 / 2020-07-31
------------------

- Fix: jpeg plugin should create canvas via `pica`.


1.0.5 / 2020-07-26
------------------

- Added `.use()` method.
- Check output blob type before transfer EXIF header.


1.0.4 / 2020-07-14
------------------

- Fixed public method names. Should be `.toCanvas()` and `.toBlob()`, as in doc.
  Old names are left as aliases until 2.0 and will be removed. 


1.0.3 / 2020-07-11
------------------

- Create canvas via pica helper.
- Rearrange utilities to simplify modifications.


1.0.2 / 2020-07-11
------------------

- Added `pica` options support (`alpha`, `unsharpAmount`, `unsharpRadius`,
  `unsharpThreshold`, `cancelToken`).
- `pica` version bump.


1.0.1 / 2020-06-25
------------------

- Added `pica` to module exports.


1.0.0 / 2020-06-25
------------------

- First release.
