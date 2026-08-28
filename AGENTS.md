# Repository Agent Instructions

Apply the required [workspace instructions](../../AGENTS.md). The rules below are this repository's delta and override shared rules on conflict.

## Repository Scope

This repository contains a development-only 1C extension with Kafka Adapter API examples and integration scenarios; it is not a production deployment artifact. Preserve Russian 1C identifiers.

## Repository-Specific Rules

- Use `kfk-edt` on port `8765` for authoritative live state, platform documentation, diagnostics, and every persistent 1C mutation.
- Use the canonical `kfk-examples` alias only for supplementary read-only code-index analysis of this checkout.
- Prefix new repository-owned 1C metadata objects with `кфк_т_`.
- Run relevant adapter scenarios when they cover the change and the environment is available.
