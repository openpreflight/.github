## openpreflight

A small CI provider for private repos: one Go binary that is both a
**configurator** (add GitHub Apps and repo bindings in a web UI or over JSON)
and a **worker** (receive webhooks, run install/test/build on the exact commit,
report one Check Run with full logs).

```text
openpreflight
────────────────────
✓ install    8s
✓ test      21s
✓ build     13s

Passed in 42s

View full logs →
```

It is the smallest useful version of GitHub-native CI — a self-hosted Check Runs
runner for teams that want CI on their own server, without Actions and without
learning a pipeline DSL. A binary and a SQLite file on a box you already pay for.

### Repositories

| Repo | What it is |
|---|---|
| [openpreflight](https://github.com/openpreflight/openpreflight) | The Go binary — configurator and worker |
| [docs](https://github.com/openpreflight/docs) | Astro Starlight site → [docs.openpreflight.xyz](https://docs.openpreflight.xyz) |
| [website](https://github.com/openpreflight/website) | Marketing site → [openpreflight.xyz](https://openpreflight.xyz) |
| [.github](https://github.com/openpreflight/.github) | This landing page |

### Links

- **Docs** — [docs.openpreflight.xyz](https://docs.openpreflight.xyz)
- **Quickstart** — [docs.openpreflight.xyz/start/quickstart](https://docs.openpreflight.xyz/start/quickstart/)
- **Why it gates on the check suite** — [ADR 005](https://docs.openpreflight.xyz/adr/005-check-suite-gating/)
- **Security policy** — [SECURITY.md](https://github.com/openpreflight/openpreflight/blob/main/SECURITY.md)

Apache-2.0 licensed.
