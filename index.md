# MCP Gateway Registry Desk

MCP Gateway Registry Desk is a hosted remote MCP for AI SDK MCP gateway registry.

This repository is a public documentation project for MCP Gateway Registry Desk. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://mcpgatewaydesk.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=mcpgatewaydesk_public_docs&utm_content=readme_home
- Pricing: https://mcpgatewaydesk.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=mcpgatewaydesk_public_docs&utm_content=readme_pricing
- Checkout: https://mcpgatewaydesk.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=mcpgatewaydesk_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://mcpgatewaydesk.clauxel.com/mcp
- Server card: https://mcpgatewaydesk.clauxel.com/server-card.json
- Registry name: `com.clauxel.mcpgatewaydesk/mcpgatewaydesk-mcp`
- Tools: `list_team_tools`, `route_tool_call`, `read_permission_state`, `export_gateway_log`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI product teams, operations leads, workflow owners, and technical evaluators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: list_team_tools
- MCP tool: route_tool_call
- MCP tool: read_permission_state
- MCP tool: export_gateway_log

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
