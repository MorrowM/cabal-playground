# Cabal-Playground

Quickly set up a temporary [cabal](https://cabal.readthedocs.io/) project for playing around with a package.

## Usage

```
cabal-playground [PKG1 PKG2 PKG3 ...]
```

For example:

```
cabal-playground text containers lens
```

## Installation

Make the `cabal-playground` script executable with `chmod +x cabal-playground` and place it anywhere on your `$PATH`. Optionally install [`cabal-fmt`](https://github.com/phadej/cabal-fmt).

## Acknowledgements

Inspired by [this blog post](https://www.greyblake.com/blog/2021-03-12-rust-playground-at-your-fingertips/) by Sergey Potapov.
