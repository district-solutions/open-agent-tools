# Agent Python Tools

- repo: bytedance/deer-flow
- repo_uri: https://github.com/bytedance/deer-flow

## File: bytedance_deer-flow/backend/packages/harness/deerflow/mcp/cache.py

Prompts

```
['initialize MCP tools and cache them with config file modification tracking', 'get cached MCP tools with lazy initialization and stale cache detection', 'reset the MCP tools cache for testing or reloading tools', 'get the modification time of the extensions config file for cache invalidation', 'check if the MCP tools cache is stale due to config file changes', 'build MCP server parameters for a stdio transport server with command and environment variables', 'build MCP server parameters for an SSE transport server with URL and authentication headers', 'build a dictionary of all enabled MCP server configurations from ExtensionsConfig', 'build MCP server parameters and validate required fields for command or URL based on transport type', 'build MCP server configurations and skip servers that fail to configure with error logging', 'build an OAuth tool interceptor that injects Authorization headers into MCP server requests', 'create an OAuth token manager that acquires, caches, and refreshes tokens for MCP servers', 'test the OAuthTokenManager.get_authorization_header method for token caching and refresh', 'get initial OAuth Authorization headers for all enabled MCP server connections', 'review the OAuthTokenManager class and its token acquisition, caching, and refresh logic', 'build MCP tools from enabled servers using langchain-mcp-adapters MultiServerMCPClient', 'create a synchronous wrapper for an asynchronous MCP tool coroutine to support sync invocation', 'test the get_mcp_tools function to load and return all tools from configured MCP servers', 'review the _make_sync_tool_wrapper function for correct nested event loop handling', 'summarize the get_mcp_tools async function that loads MCP tools with OAuth headers and sync wrappers']
```

Usage

```
{'initialize_mcp_tools': 'initialize MCP tools and cache them with config file modification tracking', 'get_cached_mcp_tools': 'get cached MCP tools with lazy initialization and stale cache detection', 'reset_mcp_tools_cache': 'reset the MCP tools cache for testing or reloading tools', 'get_config_mtime': 'get the modification time of the extensions config file for cache invalidation', 'is_cache_stale': 'check if the MCP tools cache is stale due to config file changes'}
```

## File: bytedance_deer-flow/backend/packages/harness/deerflow/mcp/client.py

Prompts

```
['initialize MCP tools and cache them with config file modification tracking', 'get cached MCP tools with lazy initialization and stale cache detection', 'reset the MCP tools cache for testing or reloading tools', 'get the modification time of the extensions config file for cache invalidation', 'check if the MCP tools cache is stale due to config file changes', 'build MCP server parameters for a stdio transport server with command and environment variables', 'build MCP server parameters for an SSE transport server with URL and authentication headers', 'build a dictionary of all enabled MCP server configurations from ExtensionsConfig', 'build MCP server parameters and validate required fields for command or URL based on transport type', 'build MCP server configurations and skip servers that fail to configure with error logging', 'build an OAuth tool interceptor that injects Authorization headers into MCP server requests', 'create an OAuth token manager that acquires, caches, and refreshes tokens for MCP servers', 'test the OAuthTokenManager.get_authorization_header method for token caching and refresh', 'get initial OAuth Authorization headers for all enabled MCP server connections', 'review the OAuthTokenManager class and its token acquisition, caching, and refresh logic', 'build MCP tools from enabled servers using langchain-mcp-adapters MultiServerMCPClient', 'create a synchronous wrapper for an asynchronous MCP tool coroutine to support sync invocation', 'test the get_mcp_tools function to load and return all tools from configured MCP servers', 'review the _make_sync_tool_wrapper function for correct nested event loop handling', 'summarize the get_mcp_tools async function that loads MCP tools with OAuth headers and sync wrappers']
```

Usage

```
{'build_server_params_stdio': 'build MCP server parameters for a stdio transport server with command and environment variables', 'build_server_params_sse': 'build MCP server parameters for an SSE transport server with URL and authentication headers', 'build_servers_config': 'build a dictionary of all enabled MCP server configurations from ExtensionsConfig', 'build_server_params_validate': 'build MCP server parameters and validate required fields for command or URL based on transport type', 'build_servers_config_skip_failed': 'build MCP server configurations and skip servers that fail to configure with error logging'}
```

## File: bytedance_deer-flow/backend/packages/harness/deerflow/mcp/oauth.py

Prompts

```
['initialize MCP tools and cache them with config file modification tracking', 'get cached MCP tools with lazy initialization and stale cache detection', 'reset the MCP tools cache for testing or reloading tools', 'get the modification time of the extensions config file for cache invalidation', 'check if the MCP tools cache is stale due to config file changes', 'build MCP server parameters for a stdio transport server with command and environment variables', 'build MCP server parameters for an SSE transport server with URL and authentication headers', 'build a dictionary of all enabled MCP server configurations from ExtensionsConfig', 'build MCP server parameters and validate required fields for command or URL based on transport type', 'build MCP server configurations and skip servers that fail to configure with error logging', 'build an OAuth tool interceptor that injects Authorization headers into MCP server requests', 'create an OAuth token manager that acquires, caches, and refreshes tokens for MCP servers', 'test the OAuthTokenManager.get_authorization_header method for token caching and refresh', 'get initial OAuth Authorization headers for all enabled MCP server connections', 'review the OAuthTokenManager class and its token acquisition, caching, and refresh logic', 'build MCP tools from enabled servers using langchain-mcp-adapters MultiServerMCPClient', 'create a synchronous wrapper for an asynchronous MCP tool coroutine to support sync invocation', 'test the get_mcp_tools function to load and return all tools from configured MCP servers', 'review the _make_sync_tool_wrapper function for correct nested event loop handling', 'summarize the get_mcp_tools async function that loads MCP tools with OAuth headers and sync wrappers']
```

Usage

```
{'build_oauth_tool_interceptor': 'build an OAuth tool interceptor that injects Authorization headers into MCP server requests', 'create_oauth_token_manager': 'create an OAuth token manager that acquires, caches, and refreshes tokens for MCP servers', 'test_get_authorization_header': 'test the OAuthTokenManager.get_authorization_header method for token caching and refresh', 'get_initial_oauth_headers': 'get initial OAuth Authorization headers for all enabled MCP server connections', 'review_oauth_token_manager': 'review the OAuthTokenManager class and its token acquisition, caching, and refresh logic'}
```

## File: bytedance_deer-flow/backend/packages/harness/deerflow/mcp/tools.py

Prompts

```
['initialize MCP tools and cache them with config file modification tracking', 'get cached MCP tools with lazy initialization and stale cache detection', 'reset the MCP tools cache for testing or reloading tools', 'get the modification time of the extensions config file for cache invalidation', 'check if the MCP tools cache is stale due to config file changes', 'build MCP server parameters for a stdio transport server with command and environment variables', 'build MCP server parameters for an SSE transport server with URL and authentication headers', 'build a dictionary of all enabled MCP server configurations from ExtensionsConfig', 'build MCP server parameters and validate required fields for command or URL based on transport type', 'build MCP server configurations and skip servers that fail to configure with error logging', 'build an OAuth tool interceptor that injects Authorization headers into MCP server requests', 'create an OAuth token manager that acquires, caches, and refreshes tokens for MCP servers', 'test the OAuthTokenManager.get_authorization_header method for token caching and refresh', 'get initial OAuth Authorization headers for all enabled MCP server connections', 'review the OAuthTokenManager class and its token acquisition, caching, and refresh logic', 'build MCP tools from enabled servers using langchain-mcp-adapters MultiServerMCPClient', 'create a synchronous wrapper for an asynchronous MCP tool coroutine to support sync invocation', 'test the get_mcp_tools function to load and return all tools from configured MCP servers', 'review the _make_sync_tool_wrapper function for correct nested event loop handling', 'summarize the get_mcp_tools async function that loads MCP tools with OAuth headers and sync wrappers']
```

Usage

```
{'build_mcp_tools': 'build MCP tools from enabled servers using langchain-mcp-adapters MultiServerMCPClient', 'create_sync_tool_wrapper': 'create a synchronous wrapper for an asynchronous MCP tool coroutine to support sync invocation', 'test_get_mcp_tools': 'test the get_mcp_tools function to load and return all tools from configured MCP servers', 'review_sync_tool_wrapper': 'review the _make_sync_tool_wrapper function for correct nested event loop handling', 'summarize_get_mcp_tools': 'summarize the get_mcp_tools async function that loads MCP tools with OAuth headers and sync wrappers'}
```

