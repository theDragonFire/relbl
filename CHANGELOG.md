# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2020-05-09
### Added
* README.md
  * Contains documentation on how to use `relbl`

### Fixed
* Program doesn't print out the `Result` containing all the files it matched

## [0.1.0] - 2020-05-08
### Added
* Basic functionality
	* Search in current directory for all files that match a regex
	* Rename files that match the regex with by a given pattern
	* Pattern can include `${n}` to match the nth reference group
	* Argument `--target-dir` or `-t` can pass a target directory to the program

[Unreleased]: https://github.com/theDragonFire/relbl/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/theDragonFire/relbl/releases/tag/v1.0.0
[0.1.0]: https://github.com/theDragonFire/relbl/releases/tag/v0.1.0