# jira-confluence-automation

Jira/Confluence automation toolkit built with AI assistance.

## Overview

This repository is the starting point for a toolkit that automates Jira and Confluence workflows using AI assistants connected through the Model Context Protocol (MCP). At the moment it contains the Module 13 (MCP) training deliverables; the toolkit itself is still to come.

## Contents

| Path | Description |
| --- | --- |
| `module-13-report.md` | Module 13 completion report: MCP configuration, configured servers, and tool test outputs |
| `notes/mcp-test.md` | Scratch note created via the MCP filesystem server |

## MCP servers

The workspace uses three MCP servers:

- **echo-windows**: a custom PowerShell echo server used to verify MCP connectivity.
- **filesystem**: `@modelcontextprotocol/server-filesystem`, scoped to the `work/` directory.
- **memory**: `@modelcontextprotocol/server-memory`, a knowledge-graph store.

See `module-13-report.md` for the full configuration and the recorded tool test outputs.

## Status

Work in progress.
