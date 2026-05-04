# Agent Python Tools

- repo: google-deepmind/gemma
- repo_uri: https://github.com/google-deepmind/gemma

## File: google-deepmind_gemma/gemma/gm/tools/_file_explorer.py

Prompts

```
['read the contents of a file at a given absolute path using the cat method', 'list all entries in a directory at a given path using the ls method', 'explore the file system by reading files or listing directories with FileExplorer', 'handle a missing file gracefully by returning a not found message with cat', 'handle an os error when trying to read a directory as text with cat', 'create a OneShotToolManager instance with a list of Tool objects to orchestrate tool usage', 'parse model output and execute the referenced tool via maybe_execute_tool on a OneShotToolManager', 'generate a system prompt string from a OneShotToolManager that lists all available tools and their formats', 'format a Tool object into a readable instruction string with description, call format, and example', 'replace the current list of registered tools on a ToolManagerBase instance with new ones', 'create an McpToolHandler instance with an MCP client to manage MCP tools', 'list all available MCP tools by calling the _tools method on McpToolHandler', 'call an MCP tool by name with optional arguments using the _call_tool method', 'activate the McpToolHandler as a context manager to enter and exit the MCP client session', 'get the fastmcp.Client instance from the McpToolHandler client cached property']
```

Usage

```
{'read_file_with_cat': 'read the contents of a file at a given absolute path using the cat method', 'list_directory_with_ls': 'list all entries in a directory at a given path using the ls method', 'explore_file_system': 'explore the file system by reading files or listing directories with FileExplorer', 'handle_missing_file': 'handle a missing file gracefully by returning a not found message with cat', 'handle_directory_read_error': 'handle an os error when trying to read a directory as text with cat'}
```

## File: google-deepmind_gemma/gemma/gm/tools/_manager.py

Prompts

```
['read the contents of a file at a given absolute path using the cat method', 'list all entries in a directory at a given path using the ls method', 'explore the file system by reading files or listing directories with FileExplorer', 'handle a missing file gracefully by returning a not found message with cat', 'handle an os error when trying to read a directory as text with cat', 'create a OneShotToolManager instance with a list of Tool objects to orchestrate tool usage', 'parse model output and execute the referenced tool via maybe_execute_tool on a OneShotToolManager', 'generate a system prompt string from a OneShotToolManager that lists all available tools and their formats', 'format a Tool object into a readable instruction string with description, call format, and example', 'replace the current list of registered tools on a ToolManagerBase instance with new ones', 'create an McpToolHandler instance with an MCP client to manage MCP tools', 'list all available MCP tools by calling the _tools method on McpToolHandler', 'call an MCP tool by name with optional arguments using the _call_tool method', 'activate the McpToolHandler as a context manager to enter and exit the MCP client session', 'get the fastmcp.Client instance from the McpToolHandler client cached property']
```

Usage

```
{'create_oneshot_tool_manager': 'create a OneShotToolManager instance with a list of Tool objects to orchestrate tool usage', 'execute_tool_from_model_output': 'parse model output and execute the referenced tool via maybe_execute_tool on a OneShotToolManager', 'generate_system_prompt_for_tools': 'generate a system prompt string from a OneShotToolManager that lists all available tools and their formats', 'format_tool_instructions': 'format a Tool object into a readable instruction string with description, call format, and example', 'update_registered_tools': 'replace the current list of registered tools on a ToolManagerBase instance with new ones'}
```

## File: google-deepmind_gemma/gemma/gm/tools/_mcp_manager.py

Prompts

```
['read the contents of a file at a given absolute path using the cat method', 'list all entries in a directory at a given path using the ls method', 'explore the file system by reading files or listing directories with FileExplorer', 'handle a missing file gracefully by returning a not found message with cat', 'handle an os error when trying to read a directory as text with cat', 'create a OneShotToolManager instance with a list of Tool objects to orchestrate tool usage', 'parse model output and execute the referenced tool via maybe_execute_tool on a OneShotToolManager', 'generate a system prompt string from a OneShotToolManager that lists all available tools and their formats', 'format a Tool object into a readable instruction string with description, call format, and example', 'replace the current list of registered tools on a ToolManagerBase instance with new ones', 'create an McpToolHandler instance with an MCP client to manage MCP tools', 'list all available MCP tools by calling the _tools method on McpToolHandler', 'call an MCP tool by name with optional arguments using the _call_tool method', 'activate the McpToolHandler as a context manager to enter and exit the MCP client session', 'get the fastmcp.Client instance from the McpToolHandler client cached property']
```

Usage

```
{'create_mcp_tool_handler': 'create an McpToolHandler instance with an MCP client to manage MCP tools', 'list_mcp_tools': 'list all available MCP tools by calling the _tools method on McpToolHandler', 'call_mcp_tool': 'call an MCP tool by name with optional arguments using the _call_tool method', 'activate_mcp_handler': 'activate the McpToolHandler as a context manager to enter and exit the MCP client session', 'get_mcp_client': 'get the fastmcp.Client instance from the McpToolHandler client cached property'}
```

