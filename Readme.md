# Autorandr-rs

This projects hosts a few binaries:

* [*autorandrd*(1)](man/autorandrd.1.scd) A daemon that automatically configures attached monitors based on EDIDs.
  It accepts a mapping through a TOML Config file, format here: [*autorandrd*(5)](man/autorandrd.5.scd).
* [*randr-edid*(1)](man/randr-edid.1.scd) A tiny utility for printing the EDIDs of attached monitors

## Commands

### Rust

`cargo build`: Build project

`cargo run -- <ARGS>`: Run executable, with provided `<ARGS>`, like `-h` for help and a list of other available CLI arguments.

## Configuration

[An example of TOML file](https://github.com/theotherjimmy/dotfiles/blob/b4cff23bdd25f05c4eb77c9297f9f08fd6ee5d15/monitors.toml)

~~dededddede~~
