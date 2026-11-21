# Android Systems & Developer Tools

I've spent over a decade building Android software, with a focus on system stability and how phones connect to in-car systems. This profile collects my public tools and engineering experiments.

**VS Code extensions** · [CSV editing and virtual scrolling](https://github.com/HOLYGITHUBUSER/vscode_csv_reader) · [Markdown and Mermaid preview](https://github.com/HOLYGITHUBUSER/vscode_md_reader) · [YAML tree and source navigation](https://github.com/HOLYGITHUBUSER/vscode_yaml_reader)

## AgentVault · Who sets the spending limit?

[**AgentVault**](https://github.com/HOLYGITHUBUSER/hecthon_monad_hangzhou_20260413) was an entry in the Agentic Payment track at **Monad Blitz Hangzhou V2**. On the Monad testnet, a user authorizes an agent and sets its spending limit. The agent can request payments, but the vault contract enforces the limit. The user can revoke access.

[Smart contracts](https://github.com/HOLYGITHUBUSER/hecthon_monad_hangzhou_20260413/tree/HEAD/contracts-%E5%90%88%E7%BA%A6) · [MCP server](https://github.com/HOLYGITHUBUSER/hecthon_monad_hangzhou_20260413/tree/HEAD/mcp-server-MCP%E6%9C%8D%E5%8A%A1%E5%99%A8)

```mermaid
flowchart LR
  U["User sets a spending limit"] --> V["Vault contract"]
  A["Agent requests payment"] --> V
  V -->|"Authorized and within limit"| P["Execute payment"]
  V -->|"Unauthorized or over limit"| R["Reject request"]
  U -.->|"Can revoke access"| V
```

## Toolbox

- **AI workflows** · [HarnessEngineering](https://github.com/HOLYGITHUBUSER/HarnessEngineering) collects reusable skills, commands, and rules for recurring engineering tasks. Start with the [skills directory](https://github.com/HOLYGITHUBUSER/HarnessEngineering/tree/HEAD/skills).
- **Android / Kotlin** · [PermissionLibX](https://github.com/HOLYGITHUBUSER/PermissionLibX) wraps Android runtime permission requests so screens can focus on what happens after access is granted.
- **Browser extensions** · [Dark Mode Extension](https://github.com/HOLYGITHUBUSER/safari_darkmode_extension) adapts websites for dark mode. The screenshots show the same page before and after.

| Default appearance | Dark mode enabled |
| :---: | :---: |
| ![CSDN in its default theme](https://raw.githubusercontent.com/HOLYGITHUBUSER/safari_darkmode_extension/HEAD/extension-source-%E6%89%A9%E5%B1%95%E6%BA%90%E4%BB%A3%E7%A0%81/tests/screenshots/china-sites/CSDN-before.png) | ![CSDN with dark mode enabled](https://raw.githubusercontent.com/HOLYGITHUBUSER/safari_darkmode_extension/HEAD/extension-source-%E6%89%A9%E5%B1%95%E6%BA%90%E4%BB%A3%E7%A0%81/tests/screenshots/china-sites/CSDN-after.png) |

### Technical focus

**Mobile:** Android, Kotlin, permissions, and system stability.  
**Developer tools:** TypeScript, VS Code extensions, webviews, and virtualized lists.  
**Agent engineering:** Agent Skills, MCP, Solidity, and on-chain authorization.

## GitHub Activity

[![Public repositories](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2FHOLYGITHUBUSER&query=%24.public_repos&label=Public%20repos&logo=github&color=356b59)](https://github.com/HOLYGITHUBUSER?tab=repositories) [![Followers](https://img.shields.io/github/followers/HOLYGITHUBUSER?label=Followers&logo=github&color=466987)](https://github.com/HOLYGITHUBUSER?tab=followers)

[![GitHub contribution calendar for the past year](https://ghchart.rshah.org/39845a/HOLYGITHUBUSER)](https://github.com/HOLYGITHUBUSER#js-contribution-activity)

[View contribution activity on GitHub →](https://github.com/HOLYGITHUBUSER#js-contribution-activity)

**Contact** · For bugs and feature requests, open an issue in the relevant repository. For other public questions, [start here](https://github.com/HOLYGITHUBUSER/HOLYGITHUBUSER/issues/new).
