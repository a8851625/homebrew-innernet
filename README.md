# homebrew-innernet

Homebrew tap for [innernet](https://github.com/a8851625/innernet) — private
networks over WireGuard, with subnet routing and a web admin UI.

```sh
brew tap a8851625/innernet
brew install innernet
```

Installs prebuilt binaries from GitHub Releases; no Rust toolchain required.

## Updating

The formula pins version and per-architecture checksums. After a release,
update the two `url`/`sha256` pairs from the release's `SHA256SUMS`.

## Uninstall

```sh
brew uninstall innernet
```
