<div align="center">

<img src="https://openpreflight.xyz/apple-touch-icon.png" alt="openpreflight" width="72" height="72" />

# openpreflight

**A small CI provider for private repos.**

One Go binary · one SQLite file · one Check Run per commit

[Website](https://openpreflight.xyz) · [Docs](https://docs.openpreflight.xyz) · [Quickstart](https://docs.openpreflight.xyz/getting-started/quickstart/) · [Source](https://github.com/openpreflight/openpreflight)

</div>

A small CI provider for private repos. One Go binary, one SQLite file: register a GitHub App, enable your repos, and get one Check Run per commit.

**v2.1.2** is released (7 September 2026). [GitHub Release](https://github.com/openpreflight/openpreflight/releases/tag/v2.1.2) · [Changelog](https://github.com/openpreflight/openpreflight/blob/v2.1.2/CHANGELOG.md)

## Repositories

| Repo | Role |
| --- | --- |
| [**openpreflight**](https://github.com/openpreflight/openpreflight) | Go binary — configurator and worker |
| [**docs**](https://github.com/openpreflight/docs) | Reference docs → [docs.openpreflight.xyz](https://docs.openpreflight.xyz) |
| [**website**](https://github.com/openpreflight/website) | Marketing → [openpreflight.xyz](https://openpreflight.xyz) |
| [**.github**](https://github.com/openpreflight/.github) | This org profile |

## Maintainer

[@trivedi-vatsal](https://github.com/trivedi-vatsal). Security reports go to
**security@openpreflight.xyz** or through
[GitHub Security Advisories](https://github.com/openpreflight/openpreflight/security/advisories/new),
not to a public issue.

## Start here

- [Quickstart](https://docs.openpreflight.xyz/getting-started/quickstart/) — binary, first-boot wizard, GitHub App
- [Pipelines](https://docs.openpreflight.xyz/use/pipelines/) — `.ci.yml`, `runtime:`, defaults
- [ADR 005](https://docs.openpreflight.xyz/reference/decisions/005-check-suite-gating/) — why runs gate on the check suite
- [Security model](https://docs.openpreflight.xyz/reference/security-model/) — HMAC, encryption, trust boundaries
- [llms.txt](https://openpreflight.xyz/llms.txt) — curated index for agents

Apache-2.0 licensed.
