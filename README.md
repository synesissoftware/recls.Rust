# recls.Rust <!-- omit in toc -->

**re**cursive **ls**, for **Rust**.

![Language](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
[![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)
![MSRV](https://img.shields.io/badge/MSRV-1.74-lightgrey)
[![CI](https://github.com/synesissoftware/recls.Rust/actions/workflows/ci.yml/badge.svg)](https://github.com/synesissoftware/recls.Rust/actions/workflows/ci.yml)


## Table of Contents <!-- omit in toc -->

- [Introduction](#introduction)
- [Installation](#installation)
- [Components](#components)
  - [Supported API](#supported-api)
  - [Features](#features)
- [Examples](#examples)
- [Project Information](#project-information)
  - [Where to get help](#where-to-get-help)
  - [Contribution guidelines](#contribution-guidelines)
  - [Dependencies](#dependencies)
    - [Efferent (fan-out)](#efferent-fan-out)
      - [Runtime Dependencies](#runtime-dependencies)
      - [Build Dependencies](#build-dependencies)
      - [Development Dependencies](#development-dependencies)
    - [Afferent (fan-in)](#afferent-fan-in)
  - [Related projects](#related-projects)
  - [License](#license)


## Introduction

**recls.Rust** is currently an unpublished scaffold. Recursive filesystem
search is not implemented, and no supported public API currently exists. The
repository reserves the Rust identity for a future recursive-search library.


## Installation

The package is intentionally unpublished with `publish = false`. It is not
currently available as a supported crates.io dependency, and no installation
procedure should be inferred from this scaffold.

This library repository retains **Cargo.lock** so local and CI validation can
use reproducible dependency resolution.
The existing formatting configuration retains nightly-only options, so
**scripts/fmt** selects the pinned `nightly-2026-08-08` formatter.


## Components

### Supported API

No supported public API is currently defined. Path traversal, filesystem
search, filtering, and result types remain future implementation work.


### Features

No supported public features are currently defined.


## Examples

No examples are currently applicable because there is no supported public API.
An **EXAMPLES.md** file will be added when a genuine API example exists.


## Project Information

### Where to get help

Use the [recls.Rust issue tracker](https://github.com/synesissoftware/recls.Rust/issues)
for questions about the scaffold and future project work.


### Contribution guidelines

Contributions should remain limited to scaffold, documentation, and packaging
work until a separate implementation task establishes a supported recursive-
search API. Do not add placeholder traversal, filtering, result types,
behavioural tests, or examples as part of boilerplate work.


### Dependencies

#### Efferent (fan-out)

The manifest retains the intended dependency direction for future work:

##### Runtime Dependencies

* [**base-traits**](https://github.com/synesissoftware/base-traits) is reserved
  for future shared trait support;
* [**fastparse**](https://github.com/synesissoftware/FastParse.Rust) is reserved
  for future parsing support;
* [**libpath**](https://github.com/synesissoftware/libpath.Rust) is reserved
  for future path handling support.

These dependencies are not used by a supported API because none currently
exists.


##### Build Dependencies

None.


##### Development Dependencies

* [**criterion**](https://github.com/criterion-rs/criterion.rs) is reserved
  for future performance work;
* [**test_help-rs**](https://github.com/synesissoftware/test_help-rs) is reserved
  for future test support.


#### Afferent (fan-in)

No downstream consumers are currently recorded.


### Related projects

The future path-search implementation is expected to build on the related
**fastparse** and **libpath.Rust** projects. No supported Rust consumer is
currently recorded.


### License

**recls.Rust** is released under the 3-clause BSD license. See
[LICENSE](./LICENSE) for details.


<!-- ########################### end of file ########################### -->
