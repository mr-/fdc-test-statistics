# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

## [0.8.0] - 2016-02-14
### Added
- expand meta/projects call with details
- add call to fetch subproject and language coverage
- unit and integration tests
- add h2 in memory db for tests
- coverage diff can now go back arbitrary days (../coverage/diff/<project-name>/days/<day-to-go-back>)
### Changed
- refactoring the whole db layer

## [0.7.1] - 2016-01-23
### Added
- line and covered diff data in /statistics/coverage/diff
- changelog

##[0.7.0] - 2016-01-21
### Added
- REST-API for coverage diff (/statistics/coverage/diff/<project-name>)