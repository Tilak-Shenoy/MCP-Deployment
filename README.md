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
