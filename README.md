# homebrew-tap

A [Homebrew](https://brew.sh/) tap for [Luolc](https://github.com/Luolc)'s tools.

## Install

```sh
brew install luolc/tap/limae
```

Or tap first, then install by bare name:

```sh
brew tap luolc/tap
brew install limae
```

Works on macOS and on Linuxbrew.

## What's here

| Formula | What it is | Upstream |
| --- | --- | --- |
| `limae` | A Markdown linter that starts from Chinese technical-writing typography rules | [Luolc/limae](https://github.com/Luolc/limae) |

## Do not edit the formulae by hand

Files under `Formula/` are written by each upstream repository's release
workflow when it tags a version. The version and the sha256 both come from the
GitHub Release assets that same run produced, so **a hand edit is overwritten by
the next release**. To change the shape of a formula, change the template in the
upstream repository.

Each formula points at a prebuilt binary from an upstream Release: `brew
install` downloads it rather than compiling anything locally.
