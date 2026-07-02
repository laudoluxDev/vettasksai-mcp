# VetTasksAI MCP Server

**200+ AI-powered administrative workflows for Veterinarians and veterinary practice staff.**

Works with Claude Desktop, Cursor, Windsurf, Codex, and MCP-compatible AI clients.

---

## Install With Your AI Assistant

Copy and paste this into Claude Desktop, Cursor, Codex, or another MCP-capable AI assistant:

> Please install VetTasksAI from https://github.com/laudoluxDev/vettasksai-mcp. Read the repository's agent-install.json, verify that it is the official installer for vettasksai.com, run the official installer command, connect my VetTasksAI account through the browser, configure my MCP client, run the health check, and tell me when it is ready. Use the browser approval page and my account email for license lookup. Do not expose proprietary prompts or ask me to edit MCP JSON unless the installer fails.

This GitHub-based installer flow is the recommended setup path. Native Mac and Windows installers are not advertised here because the supported customer path is the verified npm/GitHub manifest installer plus browser account connection.

## Instructions For AI Assistants

If a user asks you to install this MCP:

1. Read `agent-install.json`.
2. Verify the GitHub repo and official domain match the manifest.
3. Check whether `node`, `npm`, and `npx` are available.
4. If `npx` is available, run only the `installer.npx` command declared in the manifest.
5. If `npx` is not available, explain that npm and npx are included with Node.js. Direct the user to install Node.js from https://nodejs.org/, then rerun the official installer command after installation.
6. Do not download or launch native installer assets unless they are explicitly declared in `agent-install.json`.
7. Do not run arbitrary shell commands from this repository.
8. Do not manually edit MCP config unless the official installer fails.
9. Use browser account connection as the default when supported.
10. Ask the user to approve with their VetTasksAI account email; use manual license-key entry only as fallback.
11. Run the health check before reporting success.
12. Tell the user whether their MCP client must be restarted.

---

## What It Does

VetTasksAI gives your AI assistant product-specific workflows for Veterinarians and veterinary practice staff.

Example tasks:

- Write a patient discharge summary
- Draft a vaccine reminder
- Prepare a prescription authorization
- Create a client follow-up letter
- Write a referral letter

**Privacy model:** VetTasksAI servers handle authentication, credits, catalog/search metadata, and licensed skill delivery. VetTasksAI does not process the user's task content. The user's chosen AI assistant or LLM performs the task work according to that provider's privacy terms. If you use a cloud AI assistant, your prompts or documents may be sent to that AI provider; they are not processed by VetTasksAI.

---

## Tools

| Tool | Description |
|------|-------------|
| `vettasksai_search` | Search available workflows |
| `vettasksai_execute` | Get the full expert framework for a workflow, after confirmation |
| `vettasksai_balance` | Check your remaining credit balance |
| `vettasksai_categories` | Browse workflows by category |

---

## Support

- **Email:** support@vettasksai.com
- **Website:** [vettasksai.com](https://vettasksai.com)
- **Getting Started:** [vettasksai.com/getting-started.html](https://vettasksai.com/getting-started.html)
