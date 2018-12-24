# Cargo-image

[![Crates.io](https://img.shields.io/crates/v/cargo-image.svg)](https://crates.io/crates/cargo-image)
![maintenance-as-is](https://img.shields.io/badge/maintenance-as--is-yellow.svg)

An alternative to [`bootimage`](https://crates.io/crates/bootimage) that doesn't call `cargo-xbuild`.

Intended to be used with [`cargo-sysroot`](https://crates.io/crates/cargo-sysroot),
this tool will create an image bootable in QEMU for you, using the [`bootloader`](https://crates.io/crates/bootloader) crate.

## Prerequisite

* A nightly compiler.

## FAQ

* Q: What about `bootimage`?
* A: 🤷. It didn't work for my needs, so I wrote my own.

## License

Licensed under either of

* Apache License, Version 2.0
   ([LICENSE-APACHE](LICENSE-APACHE) or <http://www.apache.org/licenses/LICENSE-2.0>)
* MIT license
   ([LICENSE-MIT](LICENSE-MIT) or <http://opensource.org/licenses/MIT>)

at your option.

## Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.