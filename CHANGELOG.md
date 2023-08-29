# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 3.9.0 [Unreleased]

### Added 

- Add CMake option `USE_DEFAULT_INSTALL_PATH`.
- Add API to manage Atlas Search Indexes.
- Automatically download C driver dependency if not provided.

### Changed
- Do not build tests as part of `all` target. Configure with `BUILD_TESTING=ON` to build tests.