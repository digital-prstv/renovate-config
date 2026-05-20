# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- ✨ add rebaseWhen config(pr [#32])
- ✨ add docker datasource to rust package rule(pr [#33])
- ✨ add node support to docker datasource(pr [#34])
- BREAKING: migrate to circleci-toolkit v4.2.1(pr [#39])
- ✨ enable pinning of digests in config(pr [#41])
- ✨ enable Docker digest tracking for ci-rust(pr [#43])
- group rand packages(pr [#58])

### Changed

- 👷 ci(circleci)-downgrade node version in CI configuration(pr [#15])
- 🔧 chore(config)-update customManagers configuration(pr [#16])
- 👷 ci(circleci)-enhance renovate config validation(pr [#17])
- 🔧 chore(renovate)-update renovate configuration(pr [#20])
- 🔧 chore(renovate)-update schedule format(pr [#22])
- 🔧 chore(config)-update circleci toolkit source URL(pr [#23])
- 🔧 chore(config)-update CircleCI toolkit source URL(pr [#24])
- chore-rename CHANGELOG.md to PRLOG.md(pr [#26])
- ♻️ refactor(config)-remove redundant package matching rule(pr [#42])
- 🔧 chore(ci)-update manager file patterns in CI configuration(pr [#46])
- ♻️ refactor(ci)-simplify ciContainerDigest.json structure(pr [#47])
- 🔧 chore(config)-add package to matchPackageNames(pr [#48])
- 🔧 chore(ci)-update manager file patterns in ciContainerDigest(pr [#50])
- 🔧 chore(ci)-update yaml file pattern in container digest(pr [#51])
- 🔧 chore(config)-update test tools group name in package configuration(pr [#53])
- 🔧 chore(config)-add group name for pinned containers(pr [#56])
- 🔧 chore(config)-add opentelemetry package group(pr [#57])

### Fixed

- Configure Renovate(pr [#11])
- deps: update cimg/node docker tag to v24(pr [#18])
- deps: update cimg/node docker tag to v24.6.0(pr [#25])
- deps: update cimg/node docker tag to v24.8.0(pr [#27])
- deps: update dependency toolkit to v2.13.0(pr [#28])
- deps: update dependency toolkit to v2.13.5(pr [#29])
- deps: update cimg/node docker tag to v24.10.0(pr [#30])
- deps: update cimg/node docker tag to v25(pr [#31])
- deps: update cimg/node docker tag to v24.11.1(pr [#35])
- deps: update cimg/node docker tag to v25(pr [#36])
- deps: update dependency toolkit to v3(pr [#38])
- deps: update cimg/node docker tag to v25.4.0(pr [#40])
- 🐛 config: correct file path in matchFileNames(pr [#44])
- 🐛 ci: correct regex pattern in ciContainerDigest.json(pr [#49])
- deps: update dependency toolkit to v4.4.3(pr [#55])
- deps: update cimg/node docker tag to v25.6.1(pr [#54])
- deps: update cimg/node docker tag to v25.8.1(pr [#60])

[#15]: https://github.com/digital-prstv/renovate-config/pull/15
[#16]: https://github.com/digital-prstv/renovate-config/pull/16
[#11]: https://github.com/digital-prstv/renovate-config/pull/11
[#17]: https://github.com/digital-prstv/renovate-config/pull/17
[#18]: https://github.com/digital-prstv/renovate-config/pull/18
[#20]: https://github.com/digital-prstv/renovate-config/pull/20
[#22]: https://github.com/digital-prstv/renovate-config/pull/22
[#23]: https://github.com/digital-prstv/renovate-config/pull/23
[#24]: https://github.com/digital-prstv/renovate-config/pull/24
[#25]: https://github.com/digital-prstv/renovate-config/pull/25
[#26]: https://github.com/digital-prstv/renovate-config/pull/26
[#27]: https://github.com/digital-prstv/renovate-config/pull/27
[#28]: https://github.com/digital-prstv/renovate-config/pull/28
[#29]: https://github.com/digital-prstv/renovate-config/pull/29
[#30]: https://github.com/digital-prstv/renovate-config/pull/30
[#31]: https://github.com/digital-prstv/renovate-config/pull/31
[#32]: https://github.com/digital-prstv/renovate-config/pull/32
[#33]: https://github.com/digital-prstv/renovate-config/pull/33
[#34]: https://github.com/digital-prstv/renovate-config/pull/34
[#35]: https://github.com/digital-prstv/renovate-config/pull/35
[#36]: https://github.com/digital-prstv/renovate-config/pull/36
[#38]: https://github.com/digital-prstv/renovate-config/pull/38
[#39]: https://github.com/digital-prstv/renovate-config/pull/39
[#40]: https://github.com/digital-prstv/renovate-config/pull/40
[#41]: https://github.com/digital-prstv/renovate-config/pull/41
[#42]: https://github.com/digital-prstv/renovate-config/pull/42
[#43]: https://github.com/digital-prstv/renovate-config/pull/43
[#44]: https://github.com/digital-prstv/renovate-config/pull/44
[#46]: https://github.com/digital-prstv/renovate-config/pull/46
[#47]: https://github.com/digital-prstv/renovate-config/pull/47
[#48]: https://github.com/digital-prstv/renovate-config/pull/48
[#49]: https://github.com/digital-prstv/renovate-config/pull/49
[#50]: https://github.com/digital-prstv/renovate-config/pull/50
[#51]: https://github.com/digital-prstv/renovate-config/pull/51
[#53]: https://github.com/digital-prstv/renovate-config/pull/53
[#55]: https://github.com/digital-prstv/renovate-config/pull/55
[#54]: https://github.com/digital-prstv/renovate-config/pull/54
[#56]: https://github.com/digital-prstv/renovate-config/pull/56
[#57]: https://github.com/digital-prstv/renovate-config/pull/57
[#58]: https://github.com/digital-prstv/renovate-config/pull/58
[#60]: https://github.com/digital-prstv/renovate-config/pull/60
