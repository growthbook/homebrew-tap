# GrowthBook Homebrew Tap

Homebrew tap for GrowthBook command-line tools.

```sh
brew install growthbook/tap/growthbook
```

## What's in here

| Cask | Description |
| --- | --- |
| `growthbook` | [GrowthBook CLI](https://github.com/growthbook/cli) — manage feature flags, experiments, metrics, and more from your terminal |

## How it works

Casks in this repo are generated and pushed automatically by
[GoReleaser](https://goreleaser.com) from the
[`growthbook/cli`](https://github.com/growthbook/cli) release workflow on each
**stable** release (prereleases never touch this tap). Don't edit cask files by
hand — changes belong in `.goreleaser.yaml` in the source repo.
