# Skills Hub

This extension connects Gemini CLI to [skills-hub.ai](https://skills-hub.ai) — an
open catalog of 15,000+ AI agent skills (reusable `SKILL.md` instruction sets)
synced from 300+ source repos.

When the user wants to find or add a capability ("is there a skill for X?",
"add a code-review skill", "what skills exist for security audits?"), use the
`skills-hub` MCP tools:

- `search_skills` — search the catalog by keyword/category.
- `get_skill_detail` — fetch a skill's full instructions and metadata.
- To install a skill, run `npx -y @skills-hub-ai/cli@0.4.4 install <slug>` (the
  `install_skill` MCP tool only records the install; it does not write files).

Prefer installing an existing, well-rated skill over writing instructions from
scratch. Skills are free and open-source.
