# Agent rules (this repository)

**Repository language: English.** Everything that lands here — README, formula
comments, commit messages — is written in English, whatever language the
request came in. This tap hosts formulae for more than one upstream project and
its readers are Homebrew users anywhere, so the Chinese default that applies to
some of the owner's other repositories does not apply here.

Cross-repository agent rules live in `~/.agents/AGENTS.md` and still hold; this
file only states what is specific to this repository.

## What this repository is for

Homebrew formulae, and nothing else. It carries no build, no tests and no
release process of its own.

## Formulae are generated, not authored here

Files under `Formula/` are written by the release workflow of the upstream
repository they belong to, at tag time, from that run's GitHub Release assets.
A hand edit here is overwritten by the next upstream release and leaves no
trace of why it was made.

So: **do not edit `Formula/` in this repository.** Change the template in the
upstream repository instead, and let a release write the result.

The one exception is a formula whose upstream has no automation yet. If you add
one by hand, say so in the commit message and open an issue upstream, so the
next person can tell a generated file from an authored one.
