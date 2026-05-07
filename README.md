# Running and Debugging the MCP Server

## 1. Run the MCP Server

Start the MCP server using:

```bash
uv run fastmcp run main.py:mcp
```

You should see output similar to:

```text
Starting MCP server 'Demo Server' with transport 'stdio'
```

This means the server is running successfully.

---

## 2. Inspect the MCP Server

Inspect the registered tools and server details:

```bash
uv run fastmcp inspect main.py:mcp
```

This shows:

- Server name
- Registered tools
- MCP version
- FastMCP version

---

## 3. Debug Using MCP Inspector

Launch the MCP Inspector UI for interactive debugging:

```bash
uv run fastmcp dev inspector main.py:mcp
```

This opens a browser-based debugging interface where you can:

- View tools
- Test tool calls
- Inspect requests and responses