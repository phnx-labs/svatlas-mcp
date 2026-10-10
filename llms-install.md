# Installing Silicon Valley Atlas

Atlas is a hosted remote MCP server; there is nothing to clone, build or run.
Add it to the MCP settings:

```json
{"mcpServers":{"svatlas":{"type":"streamableHttp","url":"https://svatlas.io/mcp"}}}
```

The first tool call opens a browser to sign in with Google (OAuth 2.1 with
dynamic client registration and PKCE). Do not ask the user for an API key;
none exists. Verify the install by calling `search_companies` with a query
such as "AI developer tools".
