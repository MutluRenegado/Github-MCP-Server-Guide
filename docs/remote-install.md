# Remote GitHub MCP Server Setup

## ✅ Prerequisites

- Compatible MCP host (VS Code ≥ 1.101, Claude Desktop, Cursor, etc.)
- OAuth or GitHub Personal Access Token (PAT)

## 🔧 VS Code Example

### OAuth (minimal):

```json
{
  "servers": {
    "github": {
      "type": "http",
      "url": "https://api.githubcopilot.com/mcp/"
    }
  }
}
