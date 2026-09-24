---
name: zell-getting-started
description: First-run setup for the Zell plugin. Use when the user installs Zell, asks how to connect, or needs to authorize the Zell MCP connector.
---

# Getting started with Zell

Zell turns real sales calls into daily coaching: morning reviews for reps and clear priorities for managers.

## Connect

1. Confirm the Zell MCP connector is installed (`https://api.getzell.com/mcp`).
2. Start OAuth and have the user sign in to Zell in the browser.
3. After connect succeeds, confirm with a short workspace check (for example list recent coaching priorities or calls) using Zell tools—never invent data.
4. Ask whether they are a **manager** or a **rep**, then offer the matching next step:
   - Manager → coaching priorities (`zell-coaching-priorities`)
   - Rep → morning review (`zell-morning-review`)

## Rules

- Do not ask for an API key; Zell uses OAuth.
- If auth fails, point them at https://docs.getzell.com/guides/mcp-integration and retry OAuth.
- Stay inside Zell tools and docs; do not invent coaching scores or call summaries.
