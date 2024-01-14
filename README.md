# OxyWeb

Web server in rust with zero dependencies/crates

It uses TCP/IP directly

## Building

To build a docker image, run
```bash
scripts/build.sh
```
and it should generate an image called `oxyweb:latest`.

## Build/Run locally

Just use `cargo run` to run and `cargo build` to build

## Configuration

It runs at port 8080 by default, can be configured by the `PORT` environment variable
