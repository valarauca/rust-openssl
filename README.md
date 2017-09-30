# rust-openssl

This is a [fork of sfackler's work](https://github.com/sfackler/rust-openssl).

[Documentation](https://docs.rs/openssl).

## Warning

This crate only supports the `v1.1.0` of OpenSSL

## Building

Building will result in a `PIC` OpenSSL binary **ALWAYS** being linked in your application.

Tools that are required

* `rustc` (stable)
* `cargo`
* `git`
* `gcc` (openssl needs this)
* `perl` (v5.5 or greater, openssl needs this)
* `binutils` (v2.2 or greater, openssl needs this)
* `make` (idk version restrictions)

### Linux

Linux is the only supported OS

SorryNotSorry

### Contribution

Unless you explicitly state otherwise, any contribution intentionally
submitted for inclusion in the work by you, as defined in the Apache-2.0
license, shall be dual licensed under the terms of both the Apache License,
Version 2.0 and the MIT license without any additional terms or conditions.
