# Changelog

## 1.4.7

**Bug Fixes**
- Fixed MCP tool responses failing with some AI providers

## 1.4.6

**Bug Fixes**
- Fixed "Failed to get tools" error when using MCP server
- Fixed MCP server failing to start due to missing dependency
- Fixed environment variables not being passed to MCP server
- Fixed `ha-mcp test` command hanging

## 1.4.0

**New: Home Assistant LSP (Language Server)**

Intelligent editing assistance for your YAML configuration files:

- **Autocomplete** - Entity IDs, services, areas, devices, Jinja2 functions
- **Hover Info** - See entity states, service docs, and template previews
- **Diagnostics** - Warnings for unknown entities/services, missing includes
- **Go-to-Definition** - Ctrl+click on `!include` or `!secret` to jump to files

The LSP connects to your Home Assistant instance to provide live suggestions from your actual entities and services.

| Option | Default | Description |
|--------|---------|-------------|
| `lsp_enabled` | `true` | Enable the Home Assistant LSP server |

## 1.3.0

**MCP Server Improvements**
- Added safety annotations to tools (destructive actions require confirmation)
- Tools now return links to related resources for exploration
- Updated to latest MCP SDK

## 1.2.0

**New: Enhanced MCP Server**

Major expansion of MCP capabilities for AI assistants:

| Category | What's New |
|----------|-----------|
| **Tools** | 19 total - added history, logbook, calendars, diagnostics, anomaly detection |
| **Resources** | Browsable data for automations, scripts, scenes, areas, and more |
| **Prompts** | 6 guided workflows for troubleshooting, automation creation, energy audit |

**Intelligence Features**
- Anomaly detection (low batteries, unusual readings, doors left open)
- Semantic search for entities by natural language
- Automation suggestions based on your setup

## 1.1.0

**Changes**
- Switched to Debian base image (fixes startup issues)
- OpenCode now auto-starts when opening the add-on
- Exit OpenCode to access bash shell

## 1.0.5

**Changes**
- Improved terminal colors and readability

## 1.0.0

**Initial Release**

- OpenCode AI coding agent for Home Assistant
- Web terminal with ingress support
- Access to your configuration directory
- `ha-logs` command for viewing system logs
- MCP server for AI assistant integration (experimental)
- `ha-mcp` command to manage MCP integration
- Support for 75+ AI providers
