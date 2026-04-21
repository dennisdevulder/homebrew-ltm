# homebrew-ltm

Homebrew tap for [`ltm`](https://github.com/dennisdevulder/ltm) — portable understanding for AI work sessions.

## Install

Once the first release is tagged:

```bash
brew tap dennisdevulder/ltm
brew install ltm
```

Until then, build from source:

```bash
git clone https://github.com/dennisdevulder/ltm
cd ltm
go build -o ltm ./cmd/ltm
```

## Why this tap exists

Reserves `dennisdevulder/ltm` as the install path and prevents anyone else from squatting the formula name `ltm` in an adversarial third-party tap.

The formula will ship here as soon as a `v0.1.0` release exists on the main repo.
