# MCP Gateway Registry Desk

Hosted MCP for AI SDK MCP gateway registry.

MCP Gateway Registry Desk is a paid remote MCP endpoint for AI SDK MCP gateway registry. It exposes structured JSON tools, a public server card, token-based access, usage receipts, and audit-ready workflow evidence for AI agents and coding teams.

## Public Endpoints

- Website: https://mcpgatewaydesk.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605r25
- MCP endpoint: https://mcpgatewaydesk.clauxel.com/mcp
- Server card: https://mcpgatewaydesk.clauxel.com/.well-known/mcp/server-card.json
- Registry name: `com.clauxel.mcpgatewaydesk/mcpgatewaydesk-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `list_team_tools`
- `route_tool_call`
- `read_permission_state`
- `export_gateway_log`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://mcpgatewaydesk.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605r25
- Pricing: https://mcpgatewaydesk.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605r25#pricing
- Server card: https://mcpgatewaydesk.clauxel.com/.well-known/mcp/server-card.json
- MCP endpoint: https://mcpgatewaydesk.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
