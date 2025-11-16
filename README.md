# Installation

## Deployment

Add the following configuration to your configuration file:
(settings -> developer -> Edit config) in Claude Desktop

```json
"Deployment": {
    "command": "uvx",
    "args": [
        "--from",
        "git+https://github.com/Tilak-Shenoy/MCP-Deploymet.git",
        "mcp-server"
    ]
}
```

Usage — add two numbers


For streamable HTTP use the following config

Host the code in azure/AWS and use that as `<your-url>`
```json
"remote-example": {
      "command": "npx",
      "args": [
        "mcp-remote",
        "<your-url>/mcp",
        "--allow-http"
      ]
    }
```