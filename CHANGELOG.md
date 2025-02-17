# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) and this
project adheres to [Semantic Versioning](http://semver.org/).

### [1.3.1](https://www.github.com/terraform-google-modules/terraform-google-memorystore/compare/v1.3.0...v1.3.1) (2020-12-22)


### Bug Fixes

* Remove interpolation-only expressions ([#32](https://www.github.com/terraform-google-modules/terraform-google-memorystore/issues/32)) ([f4896f6](https://www.github.com/terraform-google-modules/terraform-google-memorystore/commit/f4896f6b339e98c93937ea71397683847525677d))

## [1.3.0](https://www.github.com/terraform-google-modules/terraform-google-memorystore/compare/v1.2.0...v1.3.0) (2020-08-14)


### Features

* Addition of redis_configs parameter, allowing additional configuration for Redis ([#27](https://www.github.com/terraform-google-modules/terraform-google-memorystore/issues/27)) ([250861a](https://www.github.com/terraform-google-modules/terraform-google-memorystore/commit/250861ae46a4a4e1a431d51162879f234d7daa1f))


### Bug Fixes

* correct logic for setting memcache display name ([#24](https://www.github.com/terraform-google-modules/terraform-google-memorystore/issues/24)) ([97f84ad](https://www.github.com/terraform-google-modules/terraform-google-memorystore/commit/97f84ad6fb50ea56394be660fa0fc82e2acb3bbe))

## [1.2.0](https://www.github.com/terraform-google-modules/terraform-google-memorystore/compare/v1.1.0...v1.2.0) (2020-07-28)


### Features

* Added submodule for cloud memorystore (memcache) ([#22](https://www.github.com/terraform-google-modules/terraform-google-memorystore/issues/22)) ([6067568](https://www.github.com/terraform-google-modules/terraform-google-memorystore/commit/606756829c01d3b15b583debd1e156911f09ae36))

## [1.1.0](https://www.github.com/terraform-google-modules/terraform-google-memorystore/compare/v1.0.0...v1.1.0) (2020-06-11)


### Features

* add missing input, var.connect_mode ([#18](https://www.github.com/terraform-google-modules/terraform-google-memorystore/issues/18)) ([d3c44dd](https://www.github.com/terraform-google-modules/terraform-google-memorystore/commit/d3c44dd217fccb813b84ab2b69566ccb36fb44f8))

## [1.0.0] - 2019-09-24

### Changed
 - Supported version of Terraform is 0.12. [#10]

## [0.1.0] - 2019-01-17

### Added
- Initial module release with basic functionality.

[Unreleased]: https://github.com/terraform-google-modules/terraform-google-memorystore/compare/1.0.0...HEAD
[1.0.0]: https://github.com/terraform-google-modules/terraform-google-memorystore/compare/0.1.0...1.0.0
[0.1.0]: https://github.com/terraform-google-modules/terraform-google-memorystore/releases/tag/0.1.0

[#10]: https://github.com/terraform-google-modules/terraform-google-memorystore/pull/10
