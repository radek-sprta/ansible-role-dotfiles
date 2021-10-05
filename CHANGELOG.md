# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [2.2.0] - 2021-10-05

### Added

- Enable cloning dotfiles non-recursively.

## [2.1.0] - 2021-08-31

### Added

- Add tmux to default files to symlink.

## [2.0.0] - 2021-01-16

### Added

- Support dotfile repositories where files do not start with a dot.
- Enable force clone of dotfiles repository.

### Changed

- Show filename while looping over tasks.
- Update default repository, dotfiles folder and linked files.

### Fixed

- Set permissions in a way that does not break directories.

## [1.2.1] - 2019-11-07

### Changed

- Update dotfiles\_files default to use zshrc instead of bash\_profile.

## [1.2.0] - 2018-04-23

### Fixed

- always\_run is deprecated in Ansible 2.4.

## [1.1.0] - 2016-06-14

### Added

- Added support for git accept\_hostkey parameter.

## 1.0.0 - 2015-01-03

### Fixed

- Exit correctly on errors when testing for a symlink.

[1.1.0]: https://gitlab.com/radek-sprta/ansible-role-dotfiles/compare/1.0.0...1.1.0
[1.2.0]: https://gitlab.com/radek-sprta/ansible-role-dotfiles/compare/1.1.0...1.2.0
[1.2.1]: https://gitlab.com/radek-sprta/ansible-role-dotfiles/compare/1.2.0...1.2.1
[2.0.0]: https://gitlab.com/radek-sprta/ansible-role-dotfiles/compare/1.2.1...2.0.0
[2.1.0]: https://gitlab.com/radek-sprta/ansible-role-dotfiles/compare/2.0.0...2.1.0
[2.2.0]: https://gitlab.com/radek-sprta/ansible-role-dotfiles/compare/2.1.0...2.2.0
