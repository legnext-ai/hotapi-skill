# HotAPI Skill

Agent skill for integrating the [HotAPI](https://hotapi.ai) image, video, and audio generation API into an application with Claude Code, Codex, Cursor, and other skill-compatible coding agents.

## Install

Run this from the project you want to integrate:

```bash
npx skills add legnext-ai/hotapi-skill --skill hotapi
```

This installs the `hotapi` skill into the project's agent skill directory. Add `-g` for a global install, or use the Skills CLI agent flags to target a specific coding agent.

## What it covers

- choosing a typed model endpoint;
- keeping `HOTAPI_KEY` behind a server boundary;
- idempotent task submission;
- bounded polling or verified webhooks;
- terminal states and structured errors;
- durable result storage;
- focused tests that do not spend credits.

Exact endpoints and schemas remain authoritative in the public [OpenAPI 3.1 contract](https://api.hotapi.ai/docs/json).
