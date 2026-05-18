# Agent Python Tools

- repo: facebookresearch/meta-agents-research-environments
- repo_uri: https://github.com/facebookresearch/meta-agents-research-environments

## File: facebookresearch_meta-agents-research-environments/gaia2-cli/containers/openclaw/gaia2_adapter.py

Prompts

```
['run the gaia2 adapter HTTP server and OpenClaw WebSocket client bridge', 'send a user message to the OpenClaw gateway via chat.send RPC', 'connect to the OpenClaw gateway WebSocket with token authentication and auto-reconnect', 'post a system event to the OpenClaw wake hook to trigger a heartbeat', 'buffer and broadcast agent responses then write AUI events for terminal states', 'generate an OpenClaw runtime config from environment variables and write config files to a home directory', 'resolve provider configuration from environment variables for anthropic, openai, google, openrouter, or openai-compat providers', 'build the OpenClaw gateway and agent configuration dictionary from a resolved provider setup', 'build an OpenAI-completions provider config dict with custom base URL, model, and context window settings', 'write OpenClaw runtime JSON config files and markdown identity files to the target home directory', 'test the _message_text function to extract text from string, dict, or content-array message shapes', 'test the _is_tool_message function to detect messages containing tool_calls, toolUses, or tool_use content', 'test the _handle_chat_event function to forward final and error events while ignoring non-terminal ones', 'test the on_backend_response function to buffer responses and emit AUI turn-boundary events for final and error states', 'test the write_aui_event function to append AgentUserInterface events to events.jsonl with optional simulated time', 'run the openclaw_config CLI to write runtime files and emit shell exports', 'build a custom provider config dict for OpenAI, Anthropic, Google, or OpenRouter', 'test that generate_setup resolves the correct provider, model, and shell exports']
```

Usage

```
{'run_main': 'run the gaia2 adapter HTTP server and OpenClaw WebSocket client bridge', 'send_message': 'send a user message to the OpenClaw gateway via chat.send RPC', 'backend_connect': 'connect to the OpenClaw gateway WebSocket with token authentication and auto-reconnect', 'send_wake_hook': 'post a system event to the OpenClaw wake hook to trigger a heartbeat', 'on_backend_response': 'buffer and broadcast agent responses then write AUI events for terminal states'}
```

## File: facebookresearch_meta-agents-research-environments/gaia2-cli/containers/openclaw/openclaw_config.py

Prompts

```
['run the gaia2 adapter HTTP server and OpenClaw WebSocket client bridge', 'send a user message to the OpenClaw gateway via chat.send RPC', 'connect to the OpenClaw gateway WebSocket with token authentication and auto-reconnect', 'post a system event to the OpenClaw wake hook to trigger a heartbeat', 'buffer and broadcast agent responses then write AUI events for terminal states', 'generate an OpenClaw runtime config from environment variables and write config files to a home directory', 'resolve provider configuration from environment variables for anthropic, openai, google, openrouter, or openai-compat providers', 'build the OpenClaw gateway and agent configuration dictionary from a resolved provider setup', 'build an OpenAI-completions provider config dict with custom base URL, model, and context window settings', 'write OpenClaw runtime JSON config files and markdown identity files to the target home directory', 'test the _message_text function to extract text from string, dict, or content-array message shapes', 'test the _is_tool_message function to detect messages containing tool_calls, toolUses, or tool_use content', 'test the _handle_chat_event function to forward final and error events while ignoring non-terminal ones', 'test the on_backend_response function to buffer responses and emit AUI turn-boundary events for final and error states', 'test the write_aui_event function to append AgentUserInterface events to events.jsonl with optional simulated time', 'run the openclaw_config CLI to write runtime files and emit shell exports', 'build a custom provider config dict for OpenAI, Anthropic, Google, or OpenRouter', 'test that generate_setup resolves the correct provider, model, and shell exports']
```

Usage

```
{'generate_openclaw_setup': 'generate an OpenClaw runtime config from environment variables and write config files to a home directory', 'resolve_provider_setup': 'resolve provider configuration from environment variables for anthropic, openai, google, openrouter, or openai-compat providers', 'build_openclaw_config': 'build the OpenClaw gateway and agent configuration dictionary from a resolved provider setup', 'build_openai_completions_provider': 'build an OpenAI-completions provider config dict with custom base URL, model, and context window settings', 'write_runtime_files': 'write OpenClaw runtime JSON config files and markdown identity files to the target home directory'}
```

## File: facebookresearch_meta-agents-research-environments/gaia2-cli/containers/openclaw/test_gaia2_adapter.py

Prompts

```
['run the gaia2 adapter HTTP server and OpenClaw WebSocket client bridge', 'send a user message to the OpenClaw gateway via chat.send RPC', 'connect to the OpenClaw gateway WebSocket with token authentication and auto-reconnect', 'post a system event to the OpenClaw wake hook to trigger a heartbeat', 'buffer and broadcast agent responses then write AUI events for terminal states', 'generate an OpenClaw runtime config from environment variables and write config files to a home directory', 'resolve provider configuration from environment variables for anthropic, openai, google, openrouter, or openai-compat providers', 'build the OpenClaw gateway and agent configuration dictionary from a resolved provider setup', 'build an OpenAI-completions provider config dict with custom base URL, model, and context window settings', 'write OpenClaw runtime JSON config files and markdown identity files to the target home directory', 'test the _message_text function to extract text from string, dict, or content-array message shapes', 'test the _is_tool_message function to detect messages containing tool_calls, toolUses, or tool_use content', 'test the _handle_chat_event function to forward final and error events while ignoring non-terminal ones', 'test the on_backend_response function to buffer responses and emit AUI turn-boundary events for final and error states', 'test the write_aui_event function to append AgentUserInterface events to events.jsonl with optional simulated time', 'run the openclaw_config CLI to write runtime files and emit shell exports', 'build a custom provider config dict for OpenAI, Anthropic, Google, or OpenRouter', 'test that generate_setup resolves the correct provider, model, and shell exports']
```

Usage

```
{'test_message_text_extraction': 'test the _message_text function to extract text from string, dict, or content-array message shapes', 'test_tool_message_detection': 'test the _is_tool_message function to detect messages containing tool_calls, toolUses, or tool_use content', 'test_handle_chat_event': 'test the _handle_chat_event function to forward final and error events while ignoring non-terminal ones', 'test_backend_response_handling': 'test the on_backend_response function to buffer responses and emit AUI turn-boundary events for final and error states', 'test_write_aui_event': 'test the write_aui_event function to append AgentUserInterface events to events.jsonl with optional simulated time'}
```

## File: facebookresearch_meta-agents-research-environments/gaia2-cli/containers/openclaw/test_openclaw_config.py

Prompts

```
['run the gaia2 adapter HTTP server and OpenClaw WebSocket client bridge', 'send a user message to the OpenClaw gateway via chat.send RPC', 'connect to the OpenClaw gateway WebSocket with token authentication and auto-reconnect', 'post a system event to the OpenClaw wake hook to trigger a heartbeat', 'buffer and broadcast agent responses then write AUI events for terminal states', 'generate an OpenClaw runtime config from environment variables and write config files to a home directory', 'resolve provider configuration from environment variables for anthropic, openai, google, openrouter, or openai-compat providers', 'build the OpenClaw gateway and agent configuration dictionary from a resolved provider setup', 'build an OpenAI-completions provider config dict with custom base URL, model, and context window settings', 'write OpenClaw runtime JSON config files and markdown identity files to the target home directory', 'test the _message_text function to extract text from string, dict, or content-array message shapes', 'test the _is_tool_message function to detect messages containing tool_calls, toolUses, or tool_use content', 'test the _handle_chat_event function to forward final and error events while ignoring non-terminal ones', 'test the on_backend_response function to buffer responses and emit AUI turn-boundary events for final and error states', 'test the write_aui_event function to append AgentUserInterface events to events.jsonl with optional simulated time', 'run the openclaw_config CLI to write runtime files and emit shell exports', 'build a custom provider config dict for OpenAI, Anthropic, Google, or OpenRouter', 'test that generate_setup resolves the correct provider, model, and shell exports']
```

Usage

```
{'generate_openclaw_setup': 'generate OpenClaw runtime config from environment variables for a given LLM provider', 'run_openclaw_cli': 'run the openclaw_config CLI to write runtime files and emit shell exports', 'build_provider_config': 'build a custom provider config dict for OpenAI, Anthropic, Google, or OpenRouter', 'test_provider_resolution': 'test that generate_setup resolves the correct provider, model, and shell exports', 'write_runtime_files': 'write OpenClaw JSON config, auth profiles, and markdown files to a home directory'}
```

