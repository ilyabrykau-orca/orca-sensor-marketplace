# Orca Sensor Marketplace

Claude Code plugin marketplace for the Orca Sensor team.

## Available Plugins

### orca-sensor-claude

Codanna/Serena MCP tool routing, native tool enforcement, Serena edit guard, and session analytics.

**Install:**
```bash
# Register marketplace (one-time)
claude plugin marketplace add orca-sensor-marketplace ilyabrykau-orca/orca-sensor-marketplace

# Install plugin
claude plugin install orca-sensor-claude@orca-sensor-marketplace
```

## What it does

- **Blocks native Read/Edit/Write** on code files → routes to Serena MCP
- **Blocks native Grep/Glob** → routes to Codanna MCP
- **Enforces find_referencing_symbols** before any Serena edit
- **Auto-detects Serena project** from cwd (orca, orca-sensor, orca-runtime-sensor)
- **Session analytics** — token usage, tool distribution, cost tracking
- **Skill activation** — keyword matching for codebase-explorer, skill-developer, add-language
