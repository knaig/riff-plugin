# riff-plugin

Claude Code marketplace for [Riff MCP](https://github.com/knaig/riff), a free, bring-your-own-LLM architecture whiteboard. `draw_repo` statically crawls a repo and opens a local, clickable canvas; `explain_box` cites every claim.

## Install

Claude Code:

```
/plugin marketplace add knaig/riff-plugin
/plugin install riff-mcp
```

Cursor, VS Code, or any MCP client:

```
npx -y riff-mcp mcp
```

Then set your own AI key once:

```
npx riff-mcp setup
```

Source, issues, and docs live in [knaig/riff](https://github.com/knaig/riff).
