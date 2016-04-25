#Change Log
This project adheres to [Semantic Versioning](http://semver.org/).

This CHANGELOG follows the format listed at [Keep A Changelog](http://keepachangelog.com/)

## [Unreleased]
- nothing

## [1.0.1] - 2016-04-25
### Changed
- Fix NoMethodError: undefined method > for nil:NilClass in bin/check-graphite.rb[279]

## [1.0.0] - 2016-01-20
### Changed
- Use the whole client name as hostname for graphite measurement

## [0.0.7] - 2015-09-29
### Added
- add -r option (Reverse the warning/crit scale (if value is less than instead of greater than)) to check-graphite-stats.rb

### Changed
- The short command line option for 'Add an auth token to the HTTP request' is now -A, -a clashed with the proxy support
- Set socket's SSL mode only if using HTTPS

## [0.0.6] - 2015-08-27
### Added
- check on number of hosts
- -auth param allows authentication by bearer token

## [0.0.5] - 2015-08-05
### Changed
- general cleanup

## [0.0.4] - 2015-07-14
### Changed
- updated sensu-plugin gem to 1.2.0

## [0.0.3] - 2015-06-16
### Fixed
- removed outdated dependency on openssl

## [0.0.2] - 2015-06-02
### Fixed
- added binstubs
### Changed
- removed cruft from /lib

## 0.0.1 - 2015-04-30
### Added
- initial release

[Unreleased]: https://github.com/sensu-plugins/sensu-plugins-graphite/compare/1.0.0...HEAD
[1.0.0]: https://github.com/sensu-plugins/sensu-plugins-graphite/compare/0.0.7...1.0.0
[0.0.7]: https://github.com/sensu-plugins/sensu-plugins-graphite/compare/0.0.6...0.0.7
[0.0.6]: https://github.com/sensu-plugins/sensu-plugins-graphite/compare/0.0.5...0.0.6
[0.0.5]: https://github.com/sensu-plugins/sensu-plugins-graphite/compare/0.0.4...0.0.5
[0.0.4]: https://github.com/sensu-plugins/sensu-plugins-graphite/compare/0.0.3...0.0.4
[0.0.3]: https://github.com/sensu-plugins/sensu-plugins-graphite/compare/0.0.2...0.0.3
[0.0.2]: https://github.com/sensu-plugins/sensu-plugins-graphite/compare/0.0.1...0.0.2
