# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/tests/tui_gateway/test_make_agent_provider.py

Prompts

```
['test the _make_agent function forwards provider, base_url, api_key, and api_mode from resolve_runtime_provider to AIAgent', 'test the server._ok and server._err methods produce valid JSON-RPC 2.0 response envelopes', 'test the server.write_json method writes JSON to stdout and handles broken pipe errors gracefully', 'test the server._emit method sends JSON-RPC event notifications with or without payload', 'test the server._block method and _pending/_answers mechanism for blocking prompt round-trips', 'test the server.handle_request method for command.dispatch with queue, steer, retry, and skill commands', 'test the render_message function to render formatted text with column width fallback behavior', 'test the render_diff function to render diff output with rich module fallback to None', 'test the make_stream_renderer function to create a StreamingRenderer instance with column width', 'test render_message fallback behavior when format_response raises TypeError then succeeds', 'test render_message returns None when format_response raises a generic exception']
```

Usage

```
{'test_make_agent_passes_resolved_provider': 'test the _make_agent function forwards provider, base_url, api_key, and api_mode from resolve_runtime_provider to AIAgent'}
```

## File: NousResearch_hermes-agent/tests/tui_gateway/test_protocol.py

Prompts

```
['test the _make_agent function forwards provider, base_url, api_key, and api_mode from resolve_runtime_provider to AIAgent', 'test the server._ok and server._err methods produce valid JSON-RPC 2.0 response envelopes', 'test the server.write_json method writes JSON to stdout and handles broken pipe errors gracefully', 'test the server._emit method sends JSON-RPC event notifications with or without payload', 'test the server._block method and _pending/_answers mechanism for blocking prompt round-trips', 'test the server.handle_request method for command.dispatch with queue, steer, retry, and skill commands', 'test the render_message function to render formatted text with column width fallback behavior', 'test the render_diff function to render diff output with rich module fallback to None', 'test the make_stream_renderer function to create a StreamingRenderer instance with column width', 'test render_message fallback behavior when format_response raises TypeError then succeeds', 'test render_message returns None when format_response raises a generic exception']
```

Usage

```
{'test_jsonrpc_envelope': 'test the server._ok and server._err methods produce valid JSON-RPC 2.0 response envelopes', 'test_write_json': 'test the server.write_json method writes JSON to stdout and handles broken pipe errors gracefully', 'test_emit_event': 'test the server._emit method sends JSON-RPC event notifications with or without payload', 'test_block_respond': 'test the server._block method and _pending/_answers mechanism for blocking prompt round-trips', 'test_command_dispatch': 'test the server.handle_request method for command.dispatch with queue, steer, retry, and skill commands'}
```

## File: NousResearch_hermes-agent/tests/tui_gateway/test_render.py

Prompts

```
['test the _make_agent function forwards provider, base_url, api_key, and api_mode from resolve_runtime_provider to AIAgent', 'test the server._ok and server._err methods produce valid JSON-RPC 2.0 response envelopes', 'test the server.write_json method writes JSON to stdout and handles broken pipe errors gracefully', 'test the server._emit method sends JSON-RPC event notifications with or without payload', 'test the server._block method and _pending/_answers mechanism for blocking prompt round-trips', 'test the server.handle_request method for command.dispatch with queue, steer, retry, and skill commands', 'test the render_message function to render formatted text with column width fallback behavior', 'test the render_diff function to render diff output with rich module fallback to None', 'test the make_stream_renderer function to create a StreamingRenderer instance with column width', 'test render_message fallback behavior when format_response raises TypeError then succeeds', 'test render_message returns None when format_response raises a generic exception']
```

Usage

```
{'test_render_message': 'test the render_message function to render formatted text with column width fallback behavior', 'test_render_diff': 'test the render_diff function to render diff output with rich module fallback to None', 'test_make_stream_renderer': 'test the make_stream_renderer function to create a StreamingRenderer instance with column width', 'test_render_message_type_error_fallback': 'test render_message fallback behavior when format_response raises TypeError then succeeds', 'test_render_message_exception_returns_none': 'test render_message returns None when format_response raises a generic exception'}
```

