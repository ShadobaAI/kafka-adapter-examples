# Repository Agent Instructions

## Workspace Instructions

Read the required [workspace instructions](../../AGENTS.md) before working in this repository. The fixed `KAFKA_PROJECTS_ROOT` layout is required. If the shared file is missing, report a workspace-layout error and stop. The repository-specific rules below supplement and override the shared rules when they conflict.

## Repository Scope

This repository contains a development-only 1C extension with Kafka Adapter API examples and integration scenarios. It is not a production deployment artifact. Start with [README.md](README.md). Preserve original Russian 1C identifiers.

## Repository-Specific Rules

- Use only the EDT-MCP instance named `kfk-edt` for current-state queries, navigation, platform documentation, diagnostics, and every 1C change under `src/**`.
- Prefix new repository-owned 1C metadata objects with `кфк_т_`.
- Run the relevant adapter scenarios when the changed example is covered and the environment is available.
