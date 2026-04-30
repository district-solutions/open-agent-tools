# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/integrations/websearch_interception/handler.py

Prompts

```
['create a WebSearchInterceptionLogger instance with specified enabled providers and search tool name', 'initialize WebSearchInterceptionLogger from litellm_settings and callback_specific_params proxy config dictionaries', 'run agentic loop that intercepts web search tool calls and executes litellm.asearch() for each query', 'short-circuit web search-only requests by executing search directly and returning synthetic Anthropic response', 'convert native web search tools to LiteLLM standard format before API request', 'build the standard LiteLLM web search tool definition in Anthropic format', 'build the LiteLLM web search tool definition in OpenAI function format', 'test the strict web search tool checker for Chat Completions API', 'test the web search tool detector for native and LiteLLM standard formats', 'review the standard web search tool definition used for interception', 'transform a model response to detect and extract WebSearch tool_use or tool_calls blocks', 'transform search results into Anthropic or OpenAI assistant and user/tool messages for the agentic loop', 'format a SearchResponse into plain text with title, URL, and snippet for each result', 'detect WebSearch tool_use blocks from a non-streaming Anthropic-style response', 'detect WebSearch tool_calls from an OpenAI-style response with function calls']
```

Usage

```
{'create_websearch_interception_logger': 'create a WebSearchInterceptionLogger instance with specified enabled providers and search tool name', 'initialize_from_proxy_config': 'initialize WebSearchInterceptionLogger from litellm_settings and callback_specific_params proxy config dictionaries', 'run_agentic_loop_websearch': 'run agentic loop that intercepts web search tool calls and executes litellm.asearch() for each query', 'short_circuit_search': 'short-circuit web search-only requests by executing search directly and returning synthetic Anthropic response', 'convert_native_websearch_tools': 'convert native web search tools to LiteLLM standard format before API request'}
```

## File: berriai_litellm/litellm/integrations/websearch_interception/tools.py

Prompts

```
['create a WebSearchInterceptionLogger instance with specified enabled providers and search tool name', 'initialize WebSearchInterceptionLogger from litellm_settings and callback_specific_params proxy config dictionaries', 'run agentic loop that intercepts web search tool calls and executes litellm.asearch() for each query', 'short-circuit web search-only requests by executing search directly and returning synthetic Anthropic response', 'convert native web search tools to LiteLLM standard format before API request', 'build the standard LiteLLM web search tool definition in Anthropic format', 'build the LiteLLM web search tool definition in OpenAI function format', 'test the strict web search tool checker for Chat Completions API', 'test the web search tool detector for native and LiteLLM standard formats', 'review the standard web search tool definition used for interception', 'transform a model response to detect and extract WebSearch tool_use or tool_calls blocks', 'transform search results into Anthropic or OpenAI assistant and user/tool messages for the agentic loop', 'format a SearchResponse into plain text with title, URL, and snippet for each result', 'detect WebSearch tool_use blocks from a non-streaming Anthropic-style response', 'detect WebSearch tool_calls from an OpenAI-style response with function calls']
```

Usage

```
{'build_get_litellm_web_search_tool': 'build the standard LiteLLM web search tool definition in Anthropic format', 'build_get_litellm_web_search_tool_openai': 'build the LiteLLM web search tool definition in OpenAI function format', 'test_is_web_search_tool_chat_completion': 'test the strict web search tool checker for Chat Completions API', 'test_is_web_search_tool': 'test the web search tool detector for native and LiteLLM standard formats', 'review_get_litellm_web_search_tool': 'review the standard web search tool definition used for interception'}
```

## File: berriai_litellm/litellm/integrations/websearch_interception/transformation.py

Prompts

```
['create a WebSearchInterceptionLogger instance with specified enabled providers and search tool name', 'initialize WebSearchInterceptionLogger from litellm_settings and callback_specific_params proxy config dictionaries', 'run agentic loop that intercepts web search tool calls and executes litellm.asearch() for each query', 'short-circuit web search-only requests by executing search directly and returning synthetic Anthropic response', 'convert native web search tools to LiteLLM standard format before API request', 'build the standard LiteLLM web search tool definition in Anthropic format', 'build the LiteLLM web search tool definition in OpenAI function format', 'test the strict web search tool checker for Chat Completions API', 'test the web search tool detector for native and LiteLLM standard formats', 'review the standard web search tool definition used for interception', 'transform a model response to detect and extract WebSearch tool_use or tool_calls blocks', 'transform search results into Anthropic or OpenAI assistant and user/tool messages for the agentic loop', 'format a SearchResponse into plain text with title, URL, and snippet for each result', 'detect WebSearch tool_use blocks from a non-streaming Anthropic-style response', 'detect WebSearch tool_calls from an OpenAI-style response with function calls']
```

Usage

```
{'transform_request_detect_websearch': 'transform a model response to detect and extract WebSearch tool_use or tool_calls blocks', 'transform_response_build_messages': 'transform search results into Anthropic or OpenAI assistant and user/tool messages for the agentic loop', 'format_search_response_text': 'format a SearchResponse into plain text with title, URL, and snippet for each result', 'detect_from_non_streaming_response': 'detect WebSearch tool_use blocks from a non-streaming Anthropic-style response', 'detect_from_openai_response': 'detect WebSearch tool_calls from an OpenAI-style response with function calls'}
```

