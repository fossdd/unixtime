# unixtime 

[![Rust](https://github.com/schoenenberg/unixtime/actions/workflows/rust.yml/badge.svg)](https://github.com/schoenenberg/unixtime/actions/workflows/rust.yml)

A small utility to print the current unix-time on STDOUT.

## Motivation

Sometimes I need the current unix-time for interacting with APIs and other stuff. But I never remember the correct command for it (it's `date +%s`). I mostly end up googling the current unix-time..

Late at night, I quickly built this tool. Maybe someone is having the same issue.

## Installation

Installation requires the Rust-Toolchain. Then install it by executing:
```bash
cargo install unixtime
```
