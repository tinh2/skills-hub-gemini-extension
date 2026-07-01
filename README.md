# Skills Hub — Gemini CLI extension

Search and install **6,500+ AI agent skills** from
[skills-hub.ai](https://skills-hub.ai) without leaving Gemini CLI.

Skills are reusable `SKILL.md` instruction sets (the open Agent Skills standard)
synced from 140+ source repos — code review, testing, security, deployment,
docs, and much more, across engineering and non-engineering domains.

## Install

```bash
gemini extensions install https://github.com/tinh2/skills-hub-gemini-extension
```

Or find it in the Gemini CLI extensions gallery.

## What you get

The extension connects Gemini CLI to the Skills Hub MCP server
(`https://api.skills-hub.ai/mcp`), exposing these tools:

| Tool               | Does                                         |
| ------------------ | -------------------------------------------- |
| `search_skills`    | Search the catalog by keyword / category     |
| `get_skill_detail` | Fetch a skill's full instructions + metadata |
| `install_skill`    | Install a skill locally                      |

Plus convenience commands:

- `/search <query>` — search the catalog
- `/install <slug>` — install a skill by slug

## Example

```
/search security audit
/install owasp-top-10
```

## Links

- Catalog: https://skills-hub.ai
- MCP server & CLI: https://github.com/tinh2/skills-hub
- Browse by tool: https://skills-hub.ai/for-every-tool

---

MIT licensed. Not affiliated with Google.
