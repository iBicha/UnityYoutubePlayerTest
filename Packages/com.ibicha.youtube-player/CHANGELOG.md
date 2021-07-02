# Changelog
All notable changes to this package will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
- A CHANGELOG.md file.
- Schema to allow downloading only needed fields
  - For playing a video, only the `url` field is requested.
  - For downloading a video, only `title`, `_filename` , `ext` and `url` fields are requeted.


### Fixed 
- `JsonSerializationException` on IL2CPP by adding a default .ctor to model files