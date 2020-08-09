# CHANGELOG for ssh_authorized_keys

All notable changes to the [`ssh_authorized_keys`](https://supermarket.chef.io/cookbooks/ssh_authorized_keys) Chef cookbook will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
- ...

## [1.0.0] - 2020-08-09
[![Build Status](https://img.shields.io/travis/zuazo/ssh_authorized_keys-cookbook/1.0.0.svg?style=flat)](https://travis-ci.org/zuazo/ssh_authorized_keys-cookbook)

### Added
- Chef 16 support (issues [#15](https://github.com/zuazo/ssh_authorized_keys-cookbook/pull/15) and [#16](https://github.com/zuazo/ssh_authorized_keys-cookbook/pull/16), thanks [Benjamin M. Hughes](https://github.com/bmhughes) and [Corey Hemminger](https://github.com/Stromweld)).
- Included Oracle support.

### Removed
- Drop Ruby `< 2.5` support.
- Drop Chef `< 14` support.

### Documentation Changes
- README: Fix broken badges

## [0.4.0] - 2017-06-12
[![Build Status](https://img.shields.io/travis/zuazo/ssh_authorized_keys-cookbook/0.4.0.svg?style=flat)](https://travis-ci.org/zuazo/ssh_authorized_keys-cookbook)

### Added
- Adding ability to disable assert ([issue #6](https://github.com/zuazo/ssh_authorized_keys-cookbook/pull/6), thanks [Anthony Caiafa](https://github.com/acaiafa)).
- Allowing direct key injection ([issue #7](https://github.com/zuazo/ssh_authorized_keys-cookbook/pull/7), thanks [Anthony Caiafa](https://github.com/acaiafa)).
- Add AIX as supported platform ([issue #8](https://github.com/zuazo/ssh_authorized_keys-cookbook/issues/8), thanks [Mike Veltman](https://github.com/MVNW)).
- metadata: Add `chef_version`.

### Removed
- Drop Ruby `< 2.3` support.
- Drop Chef `< 12` support.

### Documentation Changes
- README:
  - Add documentation badge.
  - Fix Parameters table.
- Add GitHub templates.
- CHANGELOG: Follow "Keep a CHANGELOG".

## [0.3.0] - 2015-08-14
[![Build Status](https://img.shields.io/travis/zuazo/ssh_authorized_keys-cookbook/0.3.0.svg?style=flat)](https://travis-ci.org/zuazo/ssh_authorized_keys-cookbook)

### Fixed
- Use *gid* from `Etc.getpwnam` (issue [#3](https://github.com/zuazo/ssh_authorized_keys-cookbook/pull/3), thanks [Ong Ming Yang](https://github.com/ongmingyang)).
- Recursively create *.ssh* directory if it does not exist (issue [#4](https://github.com/zuazo/ssh_authorized_keys-cookbook/pull/4), thanks [Ong Ming Yang](https://github.com/ongmingyang)).
- Update chef links to use *chef.io* domain.
- Update contact information and links after migration.

## [0.2.0] - 2015-05-27
[![Build Status](https://img.shields.io/travis/zuazo/ssh_authorized_keys-cookbook/0.2.0.svg?style=flat)](https://travis-ci.org/zuazo/ssh_authorized_keys-cookbook)

### Added
- Add openSUSE as supported platform.

### Fixed
- Sort keys always in the same order ([issue #2](https://github.com/zuazo/ssh_authorized_keys-cookbook/issues/2), thanks to [Chris Burroughs](https://github.com/cburroughs) for the idea).

## 0.1.0 - 2015-01-11
[![Build Status](https://img.shields.io/travis/zuazo/ssh_authorized_keys-cookbook/0.1.0.svg?style=flat)](https://travis-ci.org/zuazo/ssh_authorized_keys-cookbook)

- Initial release of `ssh_authorized_keys`.

[Unreleased]: https://github.com/zuazo/ssh_authorized_keys-cookbook/compare/1.0.0...HEAD
[1.0.0]: https://github.com/zuazo/ssh_authorized_keys-cookbook/compare/0.4.0...1.0.0
[0.4.0]: https://github.com/zuazo/ssh_authorized_keys-cookbook/compare/0.3.0...0.4.0
[0.3.0]: https://github.com/zuazo/ssh_authorized_keys-cookbook/compare/0.2.0...0.3.0
[0.2.0]: https://github.com/zuazo/ssh_authorized_keys-cookbook/compare/0.1.0...0.2.0
