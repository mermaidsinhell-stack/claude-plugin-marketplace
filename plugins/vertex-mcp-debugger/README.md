# Vertex MCP Debugger

Debug and troubleshoot Google Vertex AI, Gemini API, and MCP server integration issues.

## Features

- **Authentication Diagnostics**: gcloud ADC, service accounts, API keys
- **Vertex AI Troubleshooting**: 401/403 errors, quota limits, API enablement
- **Model Version Verification**: Fetches current Gemini, Imagen, Veo, embedding models
- **SDK Migration Guidance**: Migrate from deprecated `vertexai.generative_models` to `google.genai`
- **MCP Server Debugging**: Configuration, logs, connectivity issues
- **Visual UI Debugging**: Screenshots, console monitoring, performance analysis (via VUDA)
- **Multi-Agent Orchestration**: Invokes specialized agents for complex issues

## Agent

### vertex-debugger

Triggers when you mention:
- Vertex AI authentication issues
- Gemini API errors
- MCP server problems
- Model version questions
- SDK deprecation warnings

## MCP Servers

### VUDA (Visual UI Debug Agent)

Auto-installed via npx. Provides 30 Playwright-based tools for:
- Screenshots and visual analysis
- DOM inspection
- Console monitoring
- Performance analysis
- API endpoint testing

## Prerequisites

- gcloud CLI installed and configured
- Google Cloud project with Vertex AI API enabled
- Node.js 18+ (for VUDA MCP)

## Quick Start

1. Enable the plugin in Claude Code
2. Ask about Vertex AI issues - the agent triggers automatically
3. Agent will diagnose auth, API, and MCP configuration

## Authoritative Documentation

The agent fetches current information from:
- https://docs.cloud.google.com/vertex-ai/generative-ai/docs/learn/model-versions
- https://docs.cloud.google.com/gemini/docs
- https://googleapis.github.io/python-genai/
- https://docs.cloud.google.com/vertex-ai/generative-ai/docs/sdks/overview

## License

MIT
