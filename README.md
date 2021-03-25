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

### Dependencies

Install `cabal-edit` using [cabal](https://cabal.readthedocs.io/):

```
cabal install cabal-edit
```

Make sure that `$HOME/.cabal/bin/` is in your `$PATH`.

### Install

Make the `cabal-playground` script executable with `chmod +x cabal-playground` and place it anywhere on your `$PATH`. Make sure `$EDITOR` is configured to your favorite text editor that can handle opening directories.

## Acknowledgements

Inspired by [this blog post](https://www.greyblake.com/blog/2021-03-12-rust-playground-at-your-fingertips/) by Sergey Potapov.
