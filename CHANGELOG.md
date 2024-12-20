# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [v3.1.0 Unreleased]

### Added

- A new `~K{}` sigil for shortening keyword list definitions.

### Changed

- **BREAKING**: Fixed a longstanding "bug" where the `~m{}` sigil did not return string keys for key renames.

### Removed

- Trademark sign previously shown after the project description in version
  0.3.0

## [v3.0.0]

### Added

- Renamed project from `ShorterMaps` to `TinyMaps`
- Add `:logger` to `extra_applications`

### Changed

### Removed

- Remvoed `espec` dependency for testing to enable Elixir 1.16 support.
