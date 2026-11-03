# shelf

A plugin marketplace for Claude Code, Claude Desktop and Cowork.
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

Updates: `/plugin update commonplace` in Claude Code; the Plugins tab in
Desktop.

## Plugins

| plugin | what it is | source |
|---|---|---|
| `commonplace` | A cited markdown research wiki and second brain that Claude maintains while it works, with a bundled tool (Linux, macOS, Windows) that verifies citations, links and structure | [hannesloots/commonplace](https://github.com/hannesloots/commonplace) |
