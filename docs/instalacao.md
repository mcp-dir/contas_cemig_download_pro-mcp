# Instalação detalhada

Cemig: Download de Contas para Profissionais é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_contas_cemig_download_pro`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_contas_cemig_download_pro` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_contas_cemig_download_pro` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_contas_cemig_download_pro` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.contas_cemig_download_pro` (ou `servers.contas_cemig_download_pro` no VS Code) do config do cliente e reinicie.
