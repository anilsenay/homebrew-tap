# Homebrew tap for Octomux

```sh
brew install --cask anilsenay/tap/octomux
```

[Octomux](https://github.com/anilsenay/octomux) is a terminal multiplexer and coding agent manager for macOS
(14 or later, Apple Silicon). The cask installs the same signed and notarized build as the DMG on the
[releases page](https://github.com/anilsenay/octomux/releases).

Octomux updates itself, so `brew upgrade` skips it unless you pass `--greedy`.

To remove Octomux with its data, background service and running sessions:

```sh
brew uninstall --zap --cask octomux
```

The Octomux release script updates this cask. Report issues in the
[Octomux repository](https://github.com/anilsenay/octomux/issues).
