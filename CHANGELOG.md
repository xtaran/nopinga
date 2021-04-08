Changelog of nopinga
====================

All notable changes to this project will be documented in this file.

The format is based on [Keep a
Changelog](https://keepachangelog.com/en/1.0.0/), and this project
adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

[Unreleased]
------------

### Added

* Error handling wrt. to non-resolving hosts
* Add support for CNAME records
* Pass each resolved IP address only once to `noping`, even if some
  were resolved multiple times.

### Bug Fixes

* Grammar fixes in README and package

### Changed

* Refactored DNS resolving code to sport less code duplication and
  make it easier to maintain.

## [1.0.0] - 2021-03-28

Initial release.

[Unreleased]: https://github.com/xtaran/nopinga/compare/1.0.0...HEAD
[1.0.0]: https://github.com/xtaran/nopinga/releases/tag/1.0.0
