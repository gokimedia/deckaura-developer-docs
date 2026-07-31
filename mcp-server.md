# MCP server

The Deckaura Tarot MCP server exposes the card database and reading helpers to MCP-compatible clients.

## Install

```bash
npm install -g @deckaura/tarot-mcp-server
```

## Client configuration

```json
{
  "mcpServers": {
    "deckaura-tarot": {
      "command": "npx",
      "args": ["-y", "@deckaura/tarot-mcp-server"]
    }
  }
}
```

## Tools

- `get_card_meaning`
- `draw_random_card`
- `three_card_spread`
- `yes_no_reading`
- `list_all_cards`

Source code and issues are available in the [Deckaura Tarot MCP repository](https://github.com/gokimedia/tarot-mcp-server). Full interpretations remain available on [Deckaura](https://deckaura.com/blogs/guide/tarot-card-meanings).

