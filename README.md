# Awesome MCP UI

A curated list of awesome resources, libraries, tools, tutorials, and community links for **MCP UI** – the UI SDK for the Model Context Protocol (MCP) that enables rich interactive interfaces for AI tools.

---

## 📚 Official Resources

- **GitHub Repository** – The source code and all releases.
  - https://github.com/MCP-UI-Org/mcp-ui
- **Documentation Site** – Guides, API reference, and walkthroughs.
  - https://mcpui.dev/
- **Package Indexes**
  - **npm** – `@mcp-ui/client` and `@mcp-ui/server` 
    - https://www.npmjs.com/package/@mcp-ui/client
    - https://www.npmjs.com/package/@mcp-ui/server
  - **Ruby Gem** – `mcp_ui_server`
    - https://rubygems.org/gems/mcp_ui_server
  - **Python PyPI** – `mcp-ui-server`
    - https://pypi.org/project/mcp-ui-server/

---

## 🚀 Getting Started & Guides

- **Introduction** – Overview of MCP UI and the MCP Apps standard.
  - https://mcpui.dev/guide/introduction
- **Installation** – Quick start for TypeScript, Ruby, and Python.
  - https://mcpui.dev/guide/installation
- **Walkthroughs** – Step‑by‑step guides for each language.
  - TypeScript server walkthrough: https://mcpui.dev/guide/server/typescript/walkthrough
  - Ruby server walkthrough: https://mcpui.dev/guide/server/ruby/walkthrough
  - Python server walkthrough: https://mcpui.dev/guide/server/python/walkthrough
- **Client Guide** – Rendering UI resources in hosts.
  - https://mcpui.dev/guide/client/overview

---

## 🛠️ SDKs & Libraries

| Language | Package | Description |
|----------|---------|-------------|
| TypeScript / JavaScript | `@mcp-ui/client` | Client‑side rendering components (`AppRenderer`, `UIResourceRenderer`). |
| TypeScript / JavaScript | `@mcp-ui/server` | Server‑side helpers to create UI resources (`createUIResource`). |
| Ruby | `mcp_ui_server` | Ruby wrapper for creating UI resources on the server. |
| Python | `mcp-ui-server` | Python wrapper for creating UI resources on the server. |

---

## 📂 Example Projects & Demos

### Server‑side Examples

- **Full‑featured TypeScript server** – Demonstrates registration of tools and UI resources.
  - https://github.com/MCP-UI-Org/mcp-ui/tree/main/examples/server
- **TypeScript server demo** – Minimal example for quick testing.
  - https://github.com/MCP-UI-Org/mcp-ui/tree/main/examples/typescript-server-demo
- **Ruby server demo** – Bare‑bones Ruby implementation.
  - https://github.com/MCP-UI-Org/mcp-ui/tree/main/examples/ruby-server-demo
- **Python server demo** – Simple Python server.
  - https://github.com/MCP-UI-Org/mcp-ui/tree/main/examples/python-server-demo
- **Remote‑DOM & Web‑Component demos** – Showcase advanced UI resources.
  - https://github.com/MCP-UI-Org/mcp-ui/tree/main/examples/remote-dom-demo
  - https://github.com/MCP-UI-Org/mcp-ui/tree/main/examples/wc-demo

### Client‑side Examples

- **Goose** – Open‑source AI agent that supports `mcp-ui`.
  - https://github.com/block/goose
- **LibreChat** – ChatGPT‑style UI with `mcp-ui` support.
  - https://github.com/danny-avila/LibreChat
- **UI Inspector** – Local tool for inspecting UI resources on an MCP server.
  - https://github.com/idosal/ui-inspector
- **MCP‑UI Chat** – Interactive chat built with the client SDK.
  - https://github.com/idosal/scira-mcp-ui-chat (hosted demo: https://scira-mcp-chat-git-main-idosals-projects.vercel.app/)

---

## 🤝 Community & Support

- **Discord** – Real‑time chat with the maintainers and community.
  - https://discord.gg/CEAG4KW7ZH
- **GitHub Discussions** – Ask questions, share ideas, and discuss road‑map.
  - https://github.com/MCP-UI-Org/mcp-ui/discussions
- **Issues** – Bug reports and feature requests.
  - https://github.com/MCP-UI-Org/mcp-ui/issues
- **Contributing** – Guidelines for contributing code, documentation, or examples.
  - https://github.com/MCP-UI-Org/mcp-ui/blob/main/.github/CONTRIBUTING.md

---

## 📦 Packages (as of today)

| Package | Latest Version | npm / PyPI / Gem |
|---------|----------------|-----------------|
| `@mcp-ui/client` | v7.1.0 (May 1 2026) | https://www.npmjs.com/package/@mcp-ui/client |
| `@mcp-ui/server` | v7.1.0 (May 1 2026) | https://www.npmjs.com/package/@mcp-ui/server |
| `mcp_ui_server` (Ruby) | 0.9.3 | https://rubygems.org/gems/mcp_ui_server |
| `mcp-ui-server` (Python) | 0.9.3 | https://pypi.org/project/mcp-ui-server/ |

---

## 🗺️ Roadmap & Future Work

- Online playground
- Expanded UI Action API
- Full Web‑Component support
- Additional language SDKs
- Generative UI capabilities

*See the full roadmap in the repository’s `README` under **Roadmap**.*

---

## 📄 License

MCP UI is released under the **Apache‑2.0 License**. See the LICENSE file in the main repository.

---

*This list is automatically curated from the official MCP‑UI repository and its documentation site as of today. Contributions are welcome – feel free to open a PR to add new resources!*
