# Cabal-Playground

Quickly set up a temporary [Cabal](https://cabal.readthedocs.io/) project for playing around with a package.

## Usage

```sh
cabal-playground [PKG1 PKG2 PKG3 ...]
```

Playground will then launch your configured editor with a minimal cabal project with the specified dependencies.

For example:

```sh
cabal-playground text containers lens
```

## Installation

Clone this repository and run `sh install`. Make sure you have the `$EDITOR` environment variable set to your favorite editor. For example, set it to `code` to launch Visual Studio Code. If you already have an `$EDITOR` set up but would like to use a different editor for Playground, you can set the `$PLAYGROUND_EDITOR` environment variable instead.

## Cleaning

To clean up old playground projects, simply delete the playground directory, which is set to be `$HOME/.local/share/cabal-playground` by default.

## Supported Platforms

As this is just a simple shell script, this is only supported on Linux and MacOS.

## Acknowledgments

Inspired by [this blog post](https://www.greyblake.com/blog/2021-03-12-rust-playground-at-your-fingertips/) by Sergey Potapov.
