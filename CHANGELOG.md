# Change log

All notable changes to the project will be documented in this file. This project adheres to [Semantic Versioning](http://semver.org).

## [1.0.2](https://github.com/launchdarkly/go-ntlm-proxy-auth/compare/1.0.1...v1.0.2) (2025-03-27)


### Bug Fixes

* Bump go-ntlmssp to v1.0.2 ([#5](https://github.com/launchdarkly/go-ntlm-proxy-auth/issues/5)) ([ff06e14](https://github.com/launchdarkly/go-ntlm-proxy-auth/commit/ff06e140234fec58bbf6369a1d528c8f08de1516))

## [1.0.1] - 2020-06-11
### Added:
- Added `go.mod` file so this package can now be consumed as a module. Since the major version is still `1` and it does not have any module-only dependencies, it can still be used by non-module projects as well.

## [1.0.0] - 2019-07-16
Initial release of this fork. The only change from the upstream code is that its dependency on `github.com/Azure/go-ntlmssp` has been replaced with `github.com/launchdarkly/go-ntlmssp`(https://github.com/launchdarkly/go-ntlmssp).
