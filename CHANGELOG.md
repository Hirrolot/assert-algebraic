# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## unreleased

## 0.2.0 - 2021-12-01

### Added

 - Add the root `CMakeLists.txt` to be able to use CMake with [`FetchContent`] or [`add_subdirectory`].

[`FetchContent`]: https://cmake.org/cmake/help/latest/module/FetchContent.html
[`add_subdirectory`]: https://cmake.org/cmake/help/latest/command/add_subdirectory.html

### Changed

 - Make complete C statements out of macros using `do { ... } while (0)` [**BC**].

## 0.1.1 - 2020-01-02

### Added

 - `ASSERT_EQUIVALENCE`.
 - `ASSERT_IRREFLEXIVE`.
 - `ASSERT_ANTISYMMETRIC`.
 - `ASSERT_ASYMMETRIC`.
 - `ASSERT_ANTITRANSITIVE`.
 - `ASSERT_CONNEXIVE`.
 - `ASSERT_SEMICONNEXIVE`.
 - `ASSERT_PREORDER`.
 - `ASSERT_PARTIAL_ORDER`.
 - `ASSERT_STRICT_PARTIAL_ORDER`.
 - `ASSERT_TOTAL_ORDER`.
 - `ASSERT_STRICT_TOTAL_ORDER`.

## 0.1.0- 2020-12-29

### Added

 - This excellent project.
