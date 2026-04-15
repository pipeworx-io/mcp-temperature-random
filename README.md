# mcp-temperature-random

temperature-random MCP — wraps StupidAPIs (requires X-API-Key)

Part of the [Pipeworx](https://pipeworx.io) open MCP gateway.

## Tools

| Tool | Description |
|------|-------------|
| `temperature_random_generate` | Fetches current temperature from 10 cities worldwide, sums them, returns last two digits. Rigorous methodology. |

## Quick Start

Add to your MCP client config:

```json
{
  "mcpServers": {
    "temperature-random": {
      "url": "https://gateway.pipeworx.io/temperature-random/mcp"
    }
  }
}
```

Or use the CLI:

```bash
npx pipeworx use temperature-random
```

## License

MIT
