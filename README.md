# Local AI Workstation

A modular, local-first AI environment for software development.

## Architecture

| Component | Technology | Purpose |
|---|---|---|
| LLM Runtime | Ollama | Running local language models |
| Agent Runtime | OpenCode | Agents, tools and workflows |
| IDE | VS Code | Code editing and development |
| MCP | Model Context Protocol | External tools and integrations |
| Skills | SKILL.md | Specialized agent instructions |
| Embeddings | Ollama | Semantic representations |
| Vector Database | Qdrant | Semantic search (planned) |
| Infrastructure | Docker | Service isolation |
| Version Control | Git | Configuration management |

## Project Structure

- `agents/` – specialized agent definitions
- `config/` – models, permissions and integrations
- `infrastructure/` – Docker and scripts
- `knowledge/` – indexes and metadata
- `mcp/` – MCP-related configurations
- `repositories/` – local code repositories
- `skills/` – reusable agent instructions
- `docs/` – project documentation

## Principles

- Local-first
- Modular architecture
- Least privilege
- Read-only by default
- Human approval for destructive operations
- Version-controlled configuration
