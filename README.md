# circleci-test

## Description

### `TL;DR`

A Project to try out circleci before writing ecology backend for it

### More

**TODO**: Write a proper description

## Building the lot

``` shell
bin/ci.common
```

## Building the projects

Each project can be built with the command:

``` shell
./mafia build
```

The first time you ever run it on your system it might take a while, as it will build and install
[`haskell-mafia/mafia`](https://github.com/haskell-mafia/mafia) on your system.

## Running the tests

``` shell
./mafia test
```
