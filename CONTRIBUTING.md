# Contributing

This repository is a **read-only mirror**. Its contents are generated from
[`rhesis-ai/rhesis`](https://github.com/rhesis-ai/rhesis) and refreshed on every change to `skills/rhesis/` there.

Direct pushes to `main` are blocked — only the sync bot can write here, and any content that
did land out of band would be reverted by the next sync.

## Where to make changes

All paths below are in [`rhesis-ai/rhesis`](https://github.com/rhesis-ai/rhesis).

| Change | Where |
|---|---|
| Skill instructions, references, MCP guidance | `skills/rhesis/` |
| Plugin manifests, README banner, this file | `scripts/skill/build_mirror.py` |
| Bug reports, feature requests | [Open an issue](https://github.com/rhesis-ai/rhesis/issues) |

## Local development

Clone the source repo and point your agent at `skills/rhesis/` directly — no need to wait
for a sync.
