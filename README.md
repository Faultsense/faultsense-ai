# Faultsense AI — Claude Code Plugin Marketplace

Umbrella [Claude Code plugin marketplace](https://code.claude.com/docs/en/plugin-marketplaces) for Faultsense's AI-agent tools.

## Add this marketplace

```shell
/plugin marketplace add Faultsense/faultsense-ai
```

## Available plugins

| Plugin | Description | Install |
|---|---|---|
| [**faultsense-instrumentation**](https://github.com/Faultsense/faultsense-claude-plugin) | Instrument web apps with Faultsense production assertion monitoring. Teaches your AI coding agent how to add `fs-*` attributes that turn E2E assertions into real-user production checks. | `/plugin install faultsense-instrumentation@faultsense-ai` |

## About this repo

This repo is the catalog — a single `.claude-plugin/marketplace.json` plus this README. It's a **one-way release projection** from the private Faultsense monorepo; every commit corresponds to a release event. Issues and PRs here will not be addressed — please file them upstream.

## What's Faultsense?

Faultsense validates feature correctness in production through declarative HTML attribute assertions — E2E test assertions built into your HTML, running against every real user session. See [faultsense.com](https://faultsense.com) for the full picture.

## License

Individual plugins listed above carry their own licenses (see each plugin repo's `LICENSE`). This marketplace catalog is provided for discovery and install convenience.
