# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [2.0.3] - 2016-11-07
### Fixed
- Fix defining associations on `acting_as` model after calling `acting_as`

## [2.0.2] - 2016-11-06
### Fixed
- Call `#touch` on `actable` object when it's called on the `acting_as` object

## [2.0.1] - 2016-10-05
### Added
- Added this changelog
- Added `touch` option to skip touching the `acting_as` object (https://github.com/hzamani/active_record-acts_as/pull/78, thanks to [allenwq](https://github.com/allenwq)!)

## [2.0.0] - 2016-09-14
### Added
- Added support for Rails 5 (https://github.com/hzamani/active_record-acts_as/pull/80, thanks to [nicklandgrebe](https://github.com/nicklandgrebe)!)
- Allow specifying `association_method` parameter (https://github.com/hzamani/active_record-acts_as/pull/72, thanks to [tombowo](https://github.com/tombowo)!)

### Removed
- Dropped support for Ruby < 2.2 and ActiveSupport/ActiveRecord < 4.2

### Fixed
- Fixed `remove_actable` migration helper (https://github.com/hzamani/active_record-acts_as/pull/71, thanks to [nuclearpidgeon](https://github.com/nuclearpidgeon)!)

[Unreleased]: https://github.com/hzamani/active_record-acts_as/compare/v2.0.3...HEAD
[2.0.3]: https://github.com/hzamani/active_record-acts_as/compare/v2.0.2...v2.0.3
[2.0.2]: https://github.com/hzamani/active_record-acts_as/compare/v2.0.1...v2.0.2
[2.0.1]: https://github.com/hzamani/active_record-acts_as/compare/v2.0.0...v2.0.1
[2.0.0]: https://github.com/hzamani/active_record-acts_as/compare/v1.0.8...v2.0.0
[1.0.8]: https://github.com/hzamani/active_record-acts_as/compare/v1.0.7...v1.0.8
[1.0.7]: https://github.com/hzamani/active_record-acts_as/compare/v1.0.6...v1.0.7
[1.0.6]: https://github.com/hzamani/active_record-acts_as/compare/v1.0.5...v1.0.6
[1.0.5]: https://github.com/hzamani/active_record-acts_as/compare/v1.0.4...v1.0.5
[1.0.4]: https://github.com/hzamani/active_record-acts_as/compare/v1.0.3...v1.0.4
[1.0.3]: https://github.com/hzamani/active_record-acts_as/compare/v1.0.2...v1.0.3
[1.0.2]: https://github.com/hzamani/active_record-acts_as/compare/v1.0.1...v1.0.2
[1.0.1]: https://github.com/hzamani/active_record-acts_as/compare/v1.0.0...v1.0.1
[1.0.0]: https://github.com/hzamani/active_record-acts_as/compare/v1.0.0.rc...v1.0.0
[1.0.0.rc]: https://github.com/hzamani/active_record-acts_as/compare/v1.0.0.pre...v1.0.0.rc
