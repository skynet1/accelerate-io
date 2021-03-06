# Change Log

Notable changes to the project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) and the
project adheres to the [Haskell Package Versioning
Policy (PVP)](https://pvp.haskell.org)

## [next]
### Changed
 * Split the different conversion functions into separate modules, rather than
   having a single `Data.Array.Accelerate.IO` export everything.

 * Conversion to/from `ByteString` is now non-copying and fix the type.

## [1.0.0.1] - 2017-10-14
### Fixed
 * `fromIArray` would fail with exception "Error in array index" when the IArray
   indices were not zero-based. This has been fixed.

## [1.0.0.0] - 2017-03-31
  * stable release


[next]:       https://github.com/AccelerateHS/accelerate-io/compare/1.0.0.1...HEAD
[1.0.0.1]:    https://github.com/AccelerateHS/accelerate-io/compare/1.0.0.0...1.0.0.1
[1.0.0.0]:    https://github.com/AccelerateHS/accelerate-io/compare/0.15.1.0...1.0.0.0

