# AI Studio Workspace Approval Gate

AI Studio Workspace Approval Gate is a hosted remote MCP for AI Studio Workspace approval gate MCP.

This repository is a public documentation project for AI Studio Workspace Approval Gate. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://aistudioworkspaceapproval.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=aistudioworkspaceapproval_public_docs&utm_content=readme_home
- Pricing: https://aistudioworkspaceapproval.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=aistudioworkspaceapproval_public_docs&utm_content=readme_pricing
- Checkout: https://aistudioworkspaceapproval.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=aistudioworkspaceapproval_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://aistudioworkspaceapproval.clauxel.com/mcp
- Server card: https://aistudioworkspaceapproval.clauxel.com/server-card.json
- Registry name: `com.clauxel.aistudioworkspaceapproval/aistudioworkspaceapproval-mcp`
- Tools: `check_workspace_change`, `approve_model_run`, `estimate_ai_studio_spend`, `issue_workspace_receipt`, `export_workspace_audit`

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
- MCP tool: check_workspace_change
- MCP tool: approve_model_run
- MCP tool: estimate_ai_studio_spend
- MCP tool: issue_workspace_receipt
- MCP tool: export_workspace_audit

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
