# Rust APDS9960 Digital Proximity, Ambient Light, RGB and Gesture Sensor Driver

[![crates.io](https://img.shields.io/crates/v/apds9960.svg)](https://crates.io/crates/apds9960)
[![Docs](https://docs.rs/apds9960/badge.svg)](https://docs.rs/apds9960)
[![Build Status](https://travis-ci.org/eldruin/apds9960-rs.svg?branch=master)](https://travis-ci.org/eldruin/apds9960-rs)
[![Coverage Status](https://coveralls.io/repos/github/eldruin/apds9960-rs/badge.svg?branch=master)](https://coveralls.io/github/eldruin/apds9960-rs?branch=master)
![Maintenance Intention](https://img.shields.io/badge/maintenance-actively--developed-brightgreen.svg)

This is a platform agnostic Rust driver for the APDS9960 digital proximity, ambient light, RGB
and gesture sensor, based on the [`embedded-hal`] traits.

[`embedded-hal`]: https://github.com/rust-embedded/embedded-hal

This driver allows you to:
- TODO

## The device

The APDS-9960 device features advanced gesture detection, proximity detection, digital ambient
light sense (ALS) and color sense (RGBC).

The communication is done through an I2C bidirectional bus.

Datasheet:
- [APDS9960](https://docs.broadcom.com/docs/AV02-4191EN)

## Usage example

Please find additional examples in this repository: [apds9960-examples]

[apds9960-examples]: https://github.com/eldruin/apds9960-examples

```rust
// TODO. See documentation.
```

## License

Licensed under either of

 * Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or
   http://www.apache.org/licenses/LICENSE-2.0)
 * MIT license ([LICENSE-MIT](LICENSE-MIT) or
   http://opensource.org/licenses/MIT) at your option.

### Contributing

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall
be dual licensed as above, without any additional terms or conditions.
