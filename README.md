# KYMA Frequency MCP

A public, remote Model Context Protocol (MCP) server for searching the KYMA369 frequency library and opening selected sets in the free KYMA app.

> **Wellness information only.** This server is designed for holistic wellness exploration. It does not diagnose, treat, cure, or prevent medical conditions; users should seek qualified medical advice for health concerns.

## Connect

**Remote Streamable HTTP endpoint**

```text
https://eaqistzhmblvuxndwfbn.supabase.co/functions/v1/freq-mcp
```

No credentials are required.

### Generic MCP client configuration

```json
{
  "mcpServers": {
    "kyma-frequencies": {
      "url": "https://eaqistzhmblvuxndwfbn.supabase.co/functions/v1/freq-mcp"
    }
  }
}
```

## Tools

| Tool | What it does |
|---|---|
| `search_frequencies` | Search public frequency sets by keyword, Hz, title, or wellness intent. |
| `get_frequency` | Fetch a set by UUID or exact title and receive a KYMA app play link. |
| `list_popular` | Browse popular/high-priority public catalog sets. |
| `get_play_link` | Create a tracked deep link into the free KYMA player. |
| `about_kyma` | Get a concise overview of KYMA369 and its app/hardware. |
| `search_content` | Search KYMA369 educational content and wellness guides. |
| `list_healing_guides` | Browse wellness-oriented guide pages. |
| `get_hz_page` | Retrieve a canonical KYMA frequency encyclopedia URL. |
| `compare_frequencies` | Retrieve a KYMA frequency-comparison page. |
| `headphones_or_pemf` | Check whether a Hz value can be played as audio or needs PEMF equipment. |

## Links

- **MCP documentation:** https://kyma369.com/mcp
- **Server card:** https://kyma369.com/.well-known/mcp/server-card.json
- **Browse the public library:** https://kyma369.com/library
- **Open the free app:** https://kyma369.com/onboarding

## Validation

The endpoint has been verified with an MCP `initialize` request (Streamable HTTP) and its public tool list.
