# yvett-plugins

Personal collection of Claude Code plugins.

## Installation

```bash
claude plugin add github:mermaidsinhell-stack/claude-plugin-marketplace
```

## Available Plugins

### vertex-mcp-debugger

Debug and troubleshoot Google Vertex AI, Gemini API, and MCP server integration issues.

**Features:**
- Authentication diagnostics (gcloud ADC, service accounts, API keys)
- Vertex AI troubleshooting (401/403 errors, quota limits, API enablement)
- Model version verification for Gemini, Imagen, Veo, embedding models
- SDK migration guidance
- MCP server debugging
- Visual UI debugging via VUDA

**Install:**
```bash
claude plugin install vertex-mcp-debugger@mermaidsinhell-stack/claude-plugin-marketplace
```

## Adding New Plugins

1. Create plugin directory in `plugins/`
2. Add `.claude-plugin/plugin.json` with name and description
3. Add components: `commands/`, `agents/`, `skills/`, `hooks/`
4. Update `marketplace.json` with the new plugin entry

## License

MIT
