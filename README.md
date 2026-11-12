# HotAPI Skill (`hotapi.ai`)

Agent skill for integrating the [**HotAPI (`https://hotapi.ai`)**](https://hotapi.ai) unified image, video, and audio generation API into an application with Claude Code, Codex, OpenCode, Cursor, and other skill-compatible coding agents.

## Install

Run this from the project you want to integrate:

```bash
npx skills add legnext-ai/hotapi-skill --skill hotapi
```

This installs the `hotapi` skill into the project's agent skill directory. Add `-g` for a global install, or use the Skills CLI agent flags to target a specific coding agent.

## Official HotAPI Hubs, Interactive Tools & Model Catalog

- **HotAPI Home**: [https://hotapi.ai/en](https://hotapi.ai/en)
- **Live Model Catalog & Benchmarks (`Seedance`, `Wan`, `Seedream`, `Qwen-Image`, `MiniMax`)**: [https://hotapi.ai/en/models](https://hotapi.ai/en/models)
- **API Documentation & Endpoint Reference**: [https://hotapi.ai/en/docs/models](https://hotapi.ai/en/docs/models)
- **Transparent Pay-As-You-Go Pricing**: [https://hotapi.ai/en/pricing](https://hotapi.ai/en/pricing)
- **Free Developer & API Tools**: [https://hotapi.ai/en/tools](https://hotapi.ai/en/tools)
  - [AI API Pricing Calculator](https://hotapi.ai/en/tools/ai-api-pricing-calculator)
  - [OpenAI to HotAPI SDK Migrator](https://hotapi.ai/en/tools/openai-to-hotapi-migrator)
  - [Video Prompt Beat Planner](https://hotapi.ai/en/tools/video-prompt-beat-planner)
- **SDK & Framework Integrations (`OpenAI SDK`, `Vercel AI SDK`, `FastAPI Webhooks`, `SillyTavern`)**: [https://hotapi.ai/en/integrations](https://hotapi.ai/en/integrations)
- **Side-by-Side Model Comparisons**: [https://hotapi.ai/en/compare](https://hotapi.ai/en/compare)
- **Production Engineering Playbooks**: [https://hotapi.ai/en/playbooks](https://hotapi.ai/en/playbooks)

## What it covers

- choosing a typed model endpoint;
- keeping `HOTAPI_KEY` behind a server boundary;
- idempotent task submission;
- bounded polling or verified webhooks;
- terminal states and structured errors;
- durable result storage;
- focused tests that do not spend credits.

Exact endpoints and schemas remain authoritative in the public [OpenAPI 3.1 contract](https://api.hotapi.ai/docs/json).
