> *This is a **VERY** hacky solution to a problem where it produced a weird compiler error. Please use the original template if [this issue](https://github.com/Rahix/avr-hal-template/issues/30) has been resolved. Only use this template if it hasn't or if you like `clippy` to be added in the [`rust-toolchain.toml`](./rust-toolchain.toml)*

`avr-hal-template`
==================
[`cargo-generate`] template for jumpstarting projects on common AVR
microcontroller boards.  This template supports the following hardware at this
time:

 - Arduino Leonardo
 - Arduino Mega 2560
 - Arduino Mega 1280
 - Arduino Nano
 - Arduino Nano New Bootloader (Manufactured after January 2018)
 - Arduino Uno
 - SparkFun ProMicro
 - SpartFun ProMini 3.3V
 - SpartFun ProMini 5v
 - Adafruit Trinket
 - Adafruit Trinket Pro

## Usage
If you don't have them already, install [`cargo-generate`] and [`ravedude`]:

```bash
cargo install cargo-generate
cargo install ravedude
```

Then instantiate this template:

```bash
cargo generate --git https://github.com/Kiwifuit/avr-hal-template.git
```

You will be prompted to select your board - do so and you're ready to roll!
Everything is prepared so you should be able to just

```bash
cargo run
```

and see a blinky flashed to your board!

[`cargo-generate`]: https://github.com/cargo-generate/cargo-generate
[`ravedude`]: https://github.com/Rahix/avr-hal/tree/next/ravedude

## License
Licensed under either of

 - Apache License, Version 2.0
   ([LICENSE-APACHE](LICENSE-APACHE) or <http://www.apache.org/licenses/LICENSE-2.0>)
 - MIT license
   ([LICENSE-MIT](LICENSE-MIT) or <http://opensource.org/licenses/MIT>)

at your option.

## Contribution
Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall
be dual licensed as above, without any additional terms or conditions.
