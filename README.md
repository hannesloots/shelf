# shelf

A plugin marketplace for Claude Code, Claude Desktop, Cowork, GitHub Copilot CLI
and OpenAI Codex.
This repository holds built plugins only; each plugin's source lives in its
own repository and its release workflow publishes here.

## Install

**Claude Code**

```
/plugin marketplace add hannesloots/shelf
/plugin install commonplace@shelf
```

**Claude Desktop / Cowork**: Customize → Plugins → "+" next to Personal
plugins → Add marketplace → `hannesloots/shelf`, then Install on the
plugin you want.

**GitHub Copilot CLI**

```
copilot plugin marketplace add hannesloots/shelf
copilot plugin install commonplace@shelf
```

**OpenAI Codex**

```
codex plugin marketplace add hannesloots/shelf
```

then install `commonplace` from the plugin list (`/plugins` in the CLI, or
the Plugins page in the desktop app).

**Any other agent that reads skills and `AGENTS.md`**: copy
`plugins/commonplace/skills/commonplace/` into the agent's skills folder
(for example `~/.agents/skills/commonplace`), or unzip
`commonplace-skill-desktop.zip` from the
[commonplace releases](https://github.com/hannesloots/commonplace/releases)
there.

Updates: `/plugin update commonplace` in Claude Code;
`copilot plugin update commonplace`; `codex plugin marketplace upgrade shelf`;
the Plugins tab in Desktop. Copy the folder again for other agents.

Claude Code and Copilot read `.claude-plugin/marketplace.json`; Codex reads
`.agents/plugins/marketplace.json`. Keep both lists in step.

## Plugins

| plugin | what it is | source |
|---|---|---|
| `commonplace` | A cited markdown research wiki and second brain that your agent maintains while it works, with a bundled tool (Linux, macOS, Windows) that verifies citations, links and structure | [hannesloots/commonplace](https://github.com/hannesloots/commonplace) |
