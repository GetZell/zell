# Zell

Official Agent Plugin for [Zell](https://www.getzell.com): sales coaching from real calls.

Connects Cursor, Grok Bot, and other Agent Plugins clients to your Zell workspace through the remote MCP server at `https://api.getzell.com/mcp`. Authentication is OAuth; no API key is required.

## What you get

- **MCP connector** — live tools against your Zell workspace after OAuth
- **Skills** — guided workflows for managers (who to coach next), reps (morning review), and call-linked drills

## Install

1. Install this plugin from the Cursor / Grok Bot marketplace (or load it locally while developing).
2. Complete the OAuth prompt and sign in to Zell.
3. Ask the agent to pull coaching priorities, a morning review, or call coaching moments.

## Local development (Cursor IDE)

```bash
ln -s "$(pwd)" ~/.cursor/plugins/local/zell
```

Reload Cursor, then connect Zell when prompted.

## Docs

- Product: https://www.getzell.com
- MCP setup guide: https://docs.getzell.com/guides/mcp-integration
- Docs index: https://docs.getzell.com

## Publish

Public Git repo → submit at https://cursor.com/marketplace/publish  
Do **not** open a PR on `github.com/xai-org/plugin-marketplace` (that catalog is for Grok Build, not Grok Bot).

## License

MIT
