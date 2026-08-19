# Instalação detalhada

SEFAZ PR: Guia de IPVA é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_sefaz_pr_guia_ipva`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_sefaz_pr_guia_ipva` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_sefaz_pr_guia_ipva` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_sefaz_pr_guia_ipva` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.sefaz_pr_guia_ipva` (ou `servers.sefaz_pr_guia_ipva` no VS Code) do config do cliente e reinicie.
