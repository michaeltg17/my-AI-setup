# my-ai-setup

My AI setup — configs, prompts, and workflows I use across all my projects.

## Model — Strata

Serves `Qwen3.8-Flash-Next-IQ3_S` as an OpenAI-compatible API on the local network.

Windows:
- Download or clone [Niko1221/Strata](https://github.com/Niko1221/Strata)
- Double-click `START-HERE.bat`
- Accept the recommended model and settings
- When it's ready, open `http://127.0.0.1:8080`
- Update later with `UPDATE.bat` · v0.2.17

API endpoint: `http://192.168.1.100:9931/v1`

## Agent — OpenCode

Uses [`opencode.json`](opencode.json) from this repo: local provider pointing at the Strata endpoint, `model: local/Qwen3.8-Flash-Next-IQ3_S`.

## Web search — SearXNG (opt-in per repo)

The built-in OpenCode websearch is disabled (`websearch: false`); search goes through the SearXNG MCP server included in `opencode.json`.

This config is **project-level, not global** — drop `opencode.json` into a repo to opt in to the whole setup; repos without one are unaffected.
