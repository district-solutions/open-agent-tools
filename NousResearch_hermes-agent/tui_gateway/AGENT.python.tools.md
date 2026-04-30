# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/tui_gateway/event_publisher.py

Prompts

```
['create a WsPublisherTransport instance that connects to a WebSocket URL for publishing events', 'write a dictionary event to the WsPublisherTransport for best-effort WebSocket delivery', 'close the WsPublisherTransport to stop the drain thread and close the WebSocket connection', 'review the WsPublisherTransport _drain method that dequeues and sends JSON strings over the WebSocket', 'refactor the WsPublisherTransport to change the maximum queue size from 256 to a custom value', 'skipped — no argparse CLI entry point', 'create a new AI agent session with a unique session ID and configurable terminal columns', 'submit a text prompt to an active AI agent session for streaming conversation response', 'set configuration values such as model, personality, reasoning effort, verbose mode, and display settings', 'execute a slash command through a persistent HermesCLI subprocess worker for the current session', 'run a shell command with dangerous-command detection, stdout/stderr capture, and 30-second timeout', 'bind a Transport instance to the current context so handlers route writes correctly', 'reset the transport binding to its previous value using the token from bind_transport', 'get the transport currently bound to the active request context via current_transport', 'create a StdioTransport that writes JSON frames to stdout using a stream getter and lock', 'create a TeeTransport that mirrors writes to a primary transport and N secondary transports', 'handle an incoming WebSocket connection by accepting it and dispatching JSON-RPC messages to the server', 'create a WSTransport instance for a WebSocket connection to enable thread-safe message writing', 'write a JSON-RPC dict from a pool worker thread using WSTransport write method with automatic loop marshalling', 'write a JSON-RPC dict from the event loop thread using WSTransport write_async method with await', 'close a WSTransport instance to mark the WebSocket connection as closed and stop further writes']
```

Usage

```
{'create_ws_publisher_transport': 'create a WsPublisherTransport instance that connects to a WebSocket URL for publishing events', 'write_event_to_transport': 'write a dictionary event to the WsPublisherTransport for best-effort WebSocket delivery', 'close_ws_publisher_transport': 'close the WsPublisherTransport to stop the drain thread and close the WebSocket connection', 'review_ws_publisher_drain_loop': 'review the WsPublisherTransport _drain method that dequeues and sends JSON strings over the WebSocket', 'refactor_ws_publisher_queue_size': 'refactor the WsPublisherTransport to change the maximum queue size from 256 to a custom value'}
```

## File: NousResearch_hermes-agent/tui_gateway/render.py

Prompts

```
['create a WsPublisherTransport instance that connects to a WebSocket URL for publishing events', 'write a dictionary event to the WsPublisherTransport for best-effort WebSocket delivery', 'close the WsPublisherTransport to stop the drain thread and close the WebSocket connection', 'review the WsPublisherTransport _drain method that dequeues and sends JSON strings over the WebSocket', 'refactor the WsPublisherTransport to change the maximum queue size from 256 to a custom value', 'skipped — no argparse CLI entry point', 'create a new AI agent session with a unique session ID and configurable terminal columns', 'submit a text prompt to an active AI agent session for streaming conversation response', 'set configuration values such as model, personality, reasoning effort, verbose mode, and display settings', 'execute a slash command through a persistent HermesCLI subprocess worker for the current session', 'run a shell command with dangerous-command detection, stdout/stderr capture, and 30-second timeout', 'bind a Transport instance to the current context so handlers route writes correctly', 'reset the transport binding to its previous value using the token from bind_transport', 'get the transport currently bound to the active request context via current_transport', 'create a StdioTransport that writes JSON frames to stdout using a stream getter and lock', 'create a TeeTransport that mirrors writes to a primary transport and N secondary transports', 'handle an incoming WebSocket connection by accepting it and dispatching JSON-RPC messages to the server', 'create a WSTransport instance for a WebSocket connection to enable thread-safe message writing', 'write a JSON-RPC dict from a pool worker thread using WSTransport write method with automatic loop marshalling', 'write a JSON-RPC dict from the event loop thread using WSTransport write_async method with await', 'close a WSTransport instance to mark the WebSocket connection as closed and stop further writes']
```

Usage

```
{'note': 'skipped — no argparse CLI entry point'}
```

## File: NousResearch_hermes-agent/tui_gateway/server.py

Prompts

```
['create a WsPublisherTransport instance that connects to a WebSocket URL for publishing events', 'write a dictionary event to the WsPublisherTransport for best-effort WebSocket delivery', 'close the WsPublisherTransport to stop the drain thread and close the WebSocket connection', 'review the WsPublisherTransport _drain method that dequeues and sends JSON strings over the WebSocket', 'refactor the WsPublisherTransport to change the maximum queue size from 256 to a custom value', 'skipped — no argparse CLI entry point', 'create a new AI agent session with a unique session ID and configurable terminal columns', 'submit a text prompt to an active AI agent session for streaming conversation response', 'set configuration values such as model, personality, reasoning effort, verbose mode, and display settings', 'execute a slash command through a persistent HermesCLI subprocess worker for the current session', 'run a shell command with dangerous-command detection, stdout/stderr capture, and 30-second timeout', 'bind a Transport instance to the current context so handlers route writes correctly', 'reset the transport binding to its previous value using the token from bind_transport', 'get the transport currently bound to the active request context via current_transport', 'create a StdioTransport that writes JSON frames to stdout using a stream getter and lock', 'create a TeeTransport that mirrors writes to a primary transport and N secondary transports', 'handle an incoming WebSocket connection by accepting it and dispatching JSON-RPC messages to the server', 'create a WSTransport instance for a WebSocket connection to enable thread-safe message writing', 'write a JSON-RPC dict from a pool worker thread using WSTransport write method with automatic loop marshalling', 'write a JSON-RPC dict from the event loop thread using WSTransport write_async method with await', 'close a WSTransport instance to mark the WebSocket connection as closed and stop further writes']
```

Usage

```
{'create_session': 'create a new AI agent session with a unique session ID and configurable terminal columns', 'submit_prompt': 'submit a text prompt to an active AI agent session for streaming conversation response', 'set_config': 'set configuration values such as model, personality, reasoning effort, verbose mode, and display settings', 'exec_slash_command': 'execute a slash command through a persistent HermesCLI subprocess worker for the current session', 'run_shell_command': 'run a shell command with dangerous-command detection, stdout/stderr capture, and 30-second timeout'}
```

## File: NousResearch_hermes-agent/tui_gateway/transport.py

Prompts

```
['create a WsPublisherTransport instance that connects to a WebSocket URL for publishing events', 'write a dictionary event to the WsPublisherTransport for best-effort WebSocket delivery', 'close the WsPublisherTransport to stop the drain thread and close the WebSocket connection', 'review the WsPublisherTransport _drain method that dequeues and sends JSON strings over the WebSocket', 'refactor the WsPublisherTransport to change the maximum queue size from 256 to a custom value', 'skipped — no argparse CLI entry point', 'create a new AI agent session with a unique session ID and configurable terminal columns', 'submit a text prompt to an active AI agent session for streaming conversation response', 'set configuration values such as model, personality, reasoning effort, verbose mode, and display settings', 'execute a slash command through a persistent HermesCLI subprocess worker for the current session', 'run a shell command with dangerous-command detection, stdout/stderr capture, and 30-second timeout', 'bind a Transport instance to the current context so handlers route writes correctly', 'reset the transport binding to its previous value using the token from bind_transport', 'get the transport currently bound to the active request context via current_transport', 'create a StdioTransport that writes JSON frames to stdout using a stream getter and lock', 'create a TeeTransport that mirrors writes to a primary transport and N secondary transports', 'handle an incoming WebSocket connection by accepting it and dispatching JSON-RPC messages to the server', 'create a WSTransport instance for a WebSocket connection to enable thread-safe message writing', 'write a JSON-RPC dict from a pool worker thread using WSTransport write method with automatic loop marshalling', 'write a JSON-RPC dict from the event loop thread using WSTransport write_async method with await', 'close a WSTransport instance to mark the WebSocket connection as closed and stop further writes']
```

Usage

```
{'bind_transport_for_context': 'bind a Transport instance to the current context so handlers route writes correctly', 'reset_transport_binding': 'reset the transport binding to its previous value using the token from bind_transport', 'get_current_transport': 'get the transport currently bound to the active request context via current_transport', 'create_stdio_transport': 'create a StdioTransport that writes JSON frames to stdout using a stream getter and lock', 'create_tee_transport': 'create a TeeTransport that mirrors writes to a primary transport and N secondary transports'}
```

## File: NousResearch_hermes-agent/tui_gateway/ws.py

Prompts

```
['create a WsPublisherTransport instance that connects to a WebSocket URL for publishing events', 'write a dictionary event to the WsPublisherTransport for best-effort WebSocket delivery', 'close the WsPublisherTransport to stop the drain thread and close the WebSocket connection', 'review the WsPublisherTransport _drain method that dequeues and sends JSON strings over the WebSocket', 'refactor the WsPublisherTransport to change the maximum queue size from 256 to a custom value', 'skipped — no argparse CLI entry point', 'create a new AI agent session with a unique session ID and configurable terminal columns', 'submit a text prompt to an active AI agent session for streaming conversation response', 'set configuration values such as model, personality, reasoning effort, verbose mode, and display settings', 'execute a slash command through a persistent HermesCLI subprocess worker for the current session', 'run a shell command with dangerous-command detection, stdout/stderr capture, and 30-second timeout', 'bind a Transport instance to the current context so handlers route writes correctly', 'reset the transport binding to its previous value using the token from bind_transport', 'get the transport currently bound to the active request context via current_transport', 'create a StdioTransport that writes JSON frames to stdout using a stream getter and lock', 'create a TeeTransport that mirrors writes to a primary transport and N secondary transports', 'handle an incoming WebSocket connection by accepting it and dispatching JSON-RPC messages to the server', 'create a WSTransport instance for a WebSocket connection to enable thread-safe message writing', 'write a JSON-RPC dict from a pool worker thread using WSTransport write method with automatic loop marshalling', 'write a JSON-RPC dict from the event loop thread using WSTransport write_async method with await', 'close a WSTransport instance to mark the WebSocket connection as closed and stop further writes']
```

Usage

```
{'handle_websocket_session': 'handle an incoming WebSocket connection by accepting it and dispatching JSON-RPC messages to the server', 'create_ws_transport': 'create a WSTransport instance for a WebSocket connection to enable thread-safe message writing', 'write_json_from_thread': 'write a JSON-RPC dict from a pool worker thread using WSTransport write method with automatic loop marshalling', 'write_json_from_loop': 'write a JSON-RPC dict from the event loop thread using WSTransport write_async method with await', 'close_ws_transport': 'close a WSTransport instance to mark the WebSocket connection as closed and stop further writes'}
```

