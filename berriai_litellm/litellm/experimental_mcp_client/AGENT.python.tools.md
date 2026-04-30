# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/experimental_mcp_client/client.py

Prompts

```
['call an MCP tool on a connected server with arguments and optional progress callback', 'list available tools from an MCP server using SSE, HTTP, or stdio transport', 'list available prompts from an MCP server', 'fetch resource contents from an MCP server by URL', 'authenticate MCP requests with AWS SigV4 using access keys, secret keys, or assumed roles', 'convert an MCP tool to an OpenAI ChatCompletionToolParam for function calling', 'load all available MCP tools from a session and optionally convert them to OpenAI format', 'call an MCP tool by name with arguments using a client session and return the result', 'convert an OpenAI ChatCompletionMessageToolCall to an MCP CallToolRequestParams', 'invoke an OpenAI tool call through the MCP client session and return the MCP tool result']
```

Usage

```
{'call_tool_MCPClient': 'call an MCP tool on a connected server with arguments and optional progress callback', 'list_tools_MCPClient': 'list available tools from an MCP server using SSE, HTTP, or stdio transport', 'list_prompts_MCPClient': 'list available prompts from an MCP server', 'read_resource_MCPClient': 'fetch resource contents from an MCP server by URL', 'authenticate_MCPSigV4Auth': 'authenticate MCP requests with AWS SigV4 using access keys, secret keys, or assumed roles'}
```

## File: berriai_litellm/litellm/experimental_mcp_client/tools.py

Prompts

```
['call an MCP tool on a connected server with arguments and optional progress callback', 'list available tools from an MCP server using SSE, HTTP, or stdio transport', 'list available prompts from an MCP server', 'fetch resource contents from an MCP server by URL', 'authenticate MCP requests with AWS SigV4 using access keys, secret keys, or assumed roles', 'convert an MCP tool to an OpenAI ChatCompletionToolParam for function calling', 'load all available MCP tools from a session and optionally convert them to OpenAI format', 'call an MCP tool by name with arguments using a client session and return the result', 'convert an OpenAI ChatCompletionMessageToolCall to an MCP CallToolRequestParams', 'invoke an OpenAI tool call through the MCP client session and return the MCP tool result']
```

Usage

```
{'build_transform_mcp_tool_to_openai_tool': 'convert an MCP tool to an OpenAI ChatCompletionToolParam for function calling', 'create_load_mcp_tools': 'load all available MCP tools from a session and optionally convert them to OpenAI format', 'run_call_mcp_tool': 'call an MCP tool by name with arguments using a client session and return the result', 'transform_openai_tool_call_request_to_mcp_tool_call_request': 'convert an OpenAI ChatCompletionMessageToolCall to an MCP CallToolRequestParams', 'call_openai_tool': 'invoke an OpenAI tool call through the MCP client session and return the MCP tool result'}
```

