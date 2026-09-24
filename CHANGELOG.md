# Changelog

All notable changes are documented here.
Format follows keepachangelog.com, versions are semver-ish.

## [0.2.8] - 2026-06-01

### Fixed
- config values were ignored when flags were present
- wrong exit code on partial failures

### Changed
- faster directory walking, fewer syscalls

## [0.1.0] - 2026-05-09

### Added
- sentence-transformers when available, tf-idf fallback
