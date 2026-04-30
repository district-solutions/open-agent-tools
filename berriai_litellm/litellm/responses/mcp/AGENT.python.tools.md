# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/responses/mcp/mcp_streaming_iterator.py

Prompts

```
['create MCP discovery events from pre-processed tools with in_progress, completed, and output_item.done events', 'create MCP call events with in_progress, arguments_delta, arguments_done, and completed or failed events for a tool call', 'create an MCP streaming iterator that handles initial LLM response streaming, MCP discovery, tool execution, and follow-up response', 'generate tool execution events and execute tool calls from a collected LLM response with auto-execution support', 'create a follow-up response iterator by sending tool results back to the LLM for continued processing']
```

Usage

```
{'create_mcp_list_tools_events': 'create MCP discovery events from pre-processed tools with in_progress, completed, and output_item.done events', 'create_mcp_call_events': 'create MCP call events with in_progress, arguments_delta, arguments_done, and completed or failed events for a tool call', 'create_MCPEnhancedStreamingIterator': 'create an MCP streaming iterator that handles initial LLM response streaming, MCP discovery, tool execution, and follow-up response', 'create_generate_tool_execution_events': 'generate tool execution events and execute tool calls from a collected LLM response with auto-execution support', 'create_follow_up_iterator': 'create a follow-up response iterator by sending tool results back to the LLM for continued processing'}
```

