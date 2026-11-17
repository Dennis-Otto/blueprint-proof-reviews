# Blueprint proof reviews

[![CI](https://github.com/Dennis-Otto/blueprint-proof-reviews/actions/workflows/ci.yml/badge.svg)](https://github.com/Dennis-Otto/blueprint-proof-reviews/actions/workflows/ci.yml)
[![CodeQL](https://github.com/Dennis-Otto/blueprint-proof-reviews/actions/workflows/codeql.yml/badge.svg)](https://github.com/Dennis-Otto/blueprint-proof-reviews/actions/workflows/codeql.yml)
[![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/Dennis-Otto/blueprint-proof-reviews/badge)](https://scorecard.dev/viewer/?uri=github.com/Dennis-Otto/blueprint-proof-reviews)
[![REUSE](https://api.reuse.software/badge/github.com/Dennis-Otto/blueprint-proof-reviews)](https://api.reuse.software/info/github.com/Dennis-Otto/blueprint-proof-reviews)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue)](LICENSE)

A throwaway repository for the live test of the settings as code of Repo Blueprint.

## Installation

Describe here how to use the project.

## Development

Every change goes through a pull request whose title follows [Conventional Commits](https://www.conventionalcommits.org/), with commits that are signed off (`git commit -s`) and signed (`git commit -S`). The checks of the CI run locally with

```sh
bash scripts/check.sh
```

[CONTRIBUTING.md](CONTRIBUTING.md) explains the set-up and the rules.

## Releases

The release bot keeps a pull request for the next release open, with the version and the changelog from the merged pull requests. Merging it publishes the release, with its SBOM and a signed provenance; [CHANGELOG.md](CHANGELOG.md) lists every change.

## Support and security

Questions and problems: see [SUPPORT.md](SUPPORT.md). Report vulnerabilities privately, as [SECURITY.md](SECURITY.md) describes.

## License

MIT; see [LICENSE](LICENSE). Every file names its license in the machine-readable form of [REUSE](https://reuse.software).
