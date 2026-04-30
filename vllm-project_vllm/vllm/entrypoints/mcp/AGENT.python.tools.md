# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/entrypoints/mcp/tool.py

Prompts

```
['test the validate_gpt_oss_install function checks gpt_oss package version requirement', 'create a HarmonyBrowserTool instance for web browsing via EXA_API_KEY and SimpleBrowserTool', 'run the HarmonyBrowserTool.get_result method to process the last message from a conversation context', 'create a HarmonyPythonTool instance for executing Python code in a Docker sandbox', 'test the HarmonyPythonTool.validate method by running a print hello world snippet', 'create an MCPToolServer instance and add tool servers via SSE URLs', 'list available tools from an MCP server by connecting via SSE', 'trim MCP JSON Schema into Harmony-compatible format by removing title and null types', 'post-process MCP tool descriptions to filter and adapt schemas for Harmony', 'create a DemoToolServer with browser and python tools for local testing']
```

Usage

```
{'test_validate_gpt_oss_install': 'test the validate_gpt_oss_install function checks gpt_oss package version requirement', 'create_HarmonyBrowserTool': 'create a HarmonyBrowserTool instance for web browsing via EXA_API_KEY and SimpleBrowserTool', 'run_HarmonyBrowserTool_get_result': 'run the HarmonyBrowserTool.get_result method to process the last message from a conversation context', 'create_HarmonyPythonTool': 'create a HarmonyPythonTool instance for executing Python code in a Docker sandbox', 'test_HarmonyPythonTool_validate': 'test the HarmonyPythonTool.validate method by running a print hello world snippet'}
```

## File: vllm-project_vllm/vllm/entrypoints/mcp/tool_server.py

Prompts

```
['test the validate_gpt_oss_install function checks gpt_oss package version requirement', 'create a HarmonyBrowserTool instance for web browsing via EXA_API_KEY and SimpleBrowserTool', 'run the HarmonyBrowserTool.get_result method to process the last message from a conversation context', 'create a HarmonyPythonTool instance for executing Python code in a Docker sandbox', 'test the HarmonyPythonTool.validate method by running a print hello world snippet', 'create an MCPToolServer instance and add tool servers via SSE URLs', 'list available tools from an MCP server by connecting via SSE', 'trim MCP JSON Schema into Harmony-compatible format by removing title and null types', 'post-process MCP tool descriptions to filter and adapt schemas for Harmony', 'create a DemoToolServer with browser and python tools for local testing']
```

Usage

```
{'create_MCPToolServer': 'create an MCPToolServer instance and add tool servers via SSE URLs', 'list_server_and_tools': 'list available tools from an MCP server by connecting via SSE', 'trim_schema': 'trim MCP JSON Schema into Harmony-compatible format by removing title and null types', 'post_process_tools_description': 'post-process MCP tool descriptions to filter and adapt schemas for Harmony', 'create_DemoToolServer': 'create a DemoToolServer with browser and python tools for local testing'}
```

