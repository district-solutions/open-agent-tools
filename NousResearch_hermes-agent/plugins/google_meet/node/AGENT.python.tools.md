# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/plugins/google_meet/node/cli.py

Prompts

```
['run a node server on this machine listening on a specified host and port', 'list all approved remote nodes registered in the node registry', 'approve and register a remote node with its name, url, and token', 'remove a previously registered node from the node registry by name', 'ping a registered node by name and return its status as json', 'start a google meet bot to join a meeting and transcribe the conversation', 'send text through the meet bot to speak during an active meeting session', 'fetch the meeting transcript with an optional limit on the number of recent messages', 'stop the running google meet bot and end the active meeting session', 'check the current status of the google meet bot or ping it for health', 'build a python request envelope with type token and payload for the google meet node rpc protocol', 'create a success response envelope with a request id and payload dict for the rpc protocol', 'create an error envelope with a request id and error message string for the rpc protocol', 'encode a message envelope dict into a compact JSON string using the protocol encode function', 'decode a raw JSON string into a validated message envelope dict using the protocol decode function', 'add a new remote meet node with a name, websocket url, and auth token to the NodeRegistry', 'get a specific node entry by name from the NodeRegistry file-backed JSON store', 'remove a named node from the NodeRegistry and return True if it existed', 'list all registered remote meet nodes sorted alphabetically by name from the NodeRegistry', 'resolve a chrome_node name to its url and token or auto-resolve when exactly one node is registered', 'run a NodeServer WebSocket server on host 0.0.0.0 port 18789 to handle meet bot RPC requests', 'generate and persist a 32 character hex auth token for the NodeServer using ensure_token', 'handle a start_bot RPC request that starts a Google Meet bot with a given URL and guest name', 'handle a transcript RPC request to retrieve the meeting transcript with optional last N lines', 'handle a say RPC request to enqueue text into the active meeting say queue JSONL file']
```

Usage

```
{'run_node_server': 'run a node server on this machine listening on a specified host and port', 'list_registered_nodes': 'list all approved remote nodes registered in the node registry', 'approve_remote_node': 'approve and register a remote node with its name, url, and token', 'remove_registered_node': 'remove a previously registered node from the node registry by name', 'ping_registered_node': 'ping a registered node by name and return its status as json'}
```

## File: NousResearch_hermes-agent/plugins/google_meet/node/client.py

Prompts

```
['run a node server on this machine listening on a specified host and port', 'list all approved remote nodes registered in the node registry', 'approve and register a remote node with its name, url, and token', 'remove a previously registered node from the node registry by name', 'ping a registered node by name and return its status as json', 'start a google meet bot to join a meeting and transcribe the conversation', 'send text through the meet bot to speak during an active meeting session', 'fetch the meeting transcript with an optional limit on the number of recent messages', 'stop the running google meet bot and end the active meeting session', 'check the current status of the google meet bot or ping it for health', 'build a python request envelope with type token and payload for the google meet node rpc protocol', 'create a success response envelope with a request id and payload dict for the rpc protocol', 'create an error envelope with a request id and error message string for the rpc protocol', 'encode a message envelope dict into a compact JSON string using the protocol encode function', 'decode a raw JSON string into a validated message envelope dict using the protocol decode function', 'add a new remote meet node with a name, websocket url, and auth token to the NodeRegistry', 'get a specific node entry by name from the NodeRegistry file-backed JSON store', 'remove a named node from the NodeRegistry and return True if it existed', 'list all registered remote meet nodes sorted alphabetically by name from the NodeRegistry', 'resolve a chrome_node name to its url and token or auto-resolve when exactly one node is registered', 'run a NodeServer WebSocket server on host 0.0.0.0 port 18789 to handle meet bot RPC requests', 'generate and persist a 32 character hex auth token for the NodeServer using ensure_token', 'handle a start_bot RPC request that starts a Google Meet bot with a given URL and guest name', 'handle a transcript RPC request to retrieve the meeting transcript with optional last N lines', 'handle a say RPC request to enqueue text into the active meeting say queue JSONL file']
```

Usage

```
{'start_google_meet_bot': 'start a google meet bot to join a meeting and transcribe the conversation', 'send_text_through_meet_bot': 'send text through the meet bot to speak during an active meeting session', 'fetch_meeting_transcript': 'fetch the meeting transcript with an optional limit on the number of recent messages', 'stop_meet_bot': 'stop the running google meet bot and end the active meeting session', 'check_meet_bot_status': 'check the current status of the google meet bot or ping it for health'}
```

## File: NousResearch_hermes-agent/plugins/google_meet/node/protocol.py

Prompts

```
['run a node server on this machine listening on a specified host and port', 'list all approved remote nodes registered in the node registry', 'approve and register a remote node with its name, url, and token', 'remove a previously registered node from the node registry by name', 'ping a registered node by name and return its status as json', 'start a google meet bot to join a meeting and transcribe the conversation', 'send text through the meet bot to speak during an active meeting session', 'fetch the meeting transcript with an optional limit on the number of recent messages', 'stop the running google meet bot and end the active meeting session', 'check the current status of the google meet bot or ping it for health', 'build a python request envelope with type token and payload for the google meet node rpc protocol', 'create a success response envelope with a request id and payload dict for the rpc protocol', 'create an error envelope with a request id and error message string for the rpc protocol', 'encode a message envelope dict into a compact JSON string using the protocol encode function', 'decode a raw JSON string into a validated message envelope dict using the protocol decode function', 'add a new remote meet node with a name, websocket url, and auth token to the NodeRegistry', 'get a specific node entry by name from the NodeRegistry file-backed JSON store', 'remove a named node from the NodeRegistry and return True if it existed', 'list all registered remote meet nodes sorted alphabetically by name from the NodeRegistry', 'resolve a chrome_node name to its url and token or auto-resolve when exactly one node is registered', 'run a NodeServer WebSocket server on host 0.0.0.0 port 18789 to handle meet bot RPC requests', 'generate and persist a 32 character hex auth token for the NodeServer using ensure_token', 'handle a start_bot RPC request that starts a Google Meet bot with a given URL and guest name', 'handle a transcript RPC request to retrieve the meeting transcript with optional last N lines', 'handle a say RPC request to enqueue text into the active meeting say queue JSONL file']
```

Usage

```
{'build_make_request': 'build a python request envelope with type token and payload for the google meet node rpc protocol', 'create_make_response': 'create a success response envelope with a request id and payload dict for the rpc protocol', 'create_make_error': 'create an error envelope with a request id and error message string for the rpc protocol', 'encode_message': 'encode a message envelope dict into a compact JSON string using the protocol encode function', 'decode_message': 'decode a raw JSON string into a validated message envelope dict using the protocol decode function'}
```

## File: NousResearch_hermes-agent/plugins/google_meet/node/registry.py

Prompts

```
['run a node server on this machine listening on a specified host and port', 'list all approved remote nodes registered in the node registry', 'approve and register a remote node with its name, url, and token', 'remove a previously registered node from the node registry by name', 'ping a registered node by name and return its status as json', 'start a google meet bot to join a meeting and transcribe the conversation', 'send text through the meet bot to speak during an active meeting session', 'fetch the meeting transcript with an optional limit on the number of recent messages', 'stop the running google meet bot and end the active meeting session', 'check the current status of the google meet bot or ping it for health', 'build a python request envelope with type token and payload for the google meet node rpc protocol', 'create a success response envelope with a request id and payload dict for the rpc protocol', 'create an error envelope with a request id and error message string for the rpc protocol', 'encode a message envelope dict into a compact JSON string using the protocol encode function', 'decode a raw JSON string into a validated message envelope dict using the protocol decode function', 'add a new remote meet node with a name, websocket url, and auth token to the NodeRegistry', 'get a specific node entry by name from the NodeRegistry file-backed JSON store', 'remove a named node from the NodeRegistry and return True if it existed', 'list all registered remote meet nodes sorted alphabetically by name from the NodeRegistry', 'resolve a chrome_node name to its url and token or auto-resolve when exactly one node is registered', 'run a NodeServer WebSocket server on host 0.0.0.0 port 18789 to handle meet bot RPC requests', 'generate and persist a 32 character hex auth token for the NodeServer using ensure_token', 'handle a start_bot RPC request that starts a Google Meet bot with a given URL and guest name', 'handle a transcript RPC request to retrieve the meeting transcript with optional last N lines', 'handle a say RPC request to enqueue text into the active meeting say queue JSONL file']
```

Usage

```
{'add_node_to_registry': 'add a new remote meet node with a name, websocket url, and auth token to the NodeRegistry', 'get_node_from_registry': 'get a specific node entry by name from the NodeRegistry file-backed JSON store', 'remove_node_from_registry': 'remove a named node from the NodeRegistry and return True if it existed', 'list_all_nodes': 'list all registered remote meet nodes sorted alphabetically by name from the NodeRegistry', 'resolve_chrome_node': 'resolve a chrome_node name to its url and token or auto-resolve when exactly one node is registered'}
```

## File: NousResearch_hermes-agent/plugins/google_meet/node/server.py

Prompts

```
['run a node server on this machine listening on a specified host and port', 'list all approved remote nodes registered in the node registry', 'approve and register a remote node with its name, url, and token', 'remove a previously registered node from the node registry by name', 'ping a registered node by name and return its status as json', 'start a google meet bot to join a meeting and transcribe the conversation', 'send text through the meet bot to speak during an active meeting session', 'fetch the meeting transcript with an optional limit on the number of recent messages', 'stop the running google meet bot and end the active meeting session', 'check the current status of the google meet bot or ping it for health', 'build a python request envelope with type token and payload for the google meet node rpc protocol', 'create a success response envelope with a request id and payload dict for the rpc protocol', 'create an error envelope with a request id and error message string for the rpc protocol', 'encode a message envelope dict into a compact JSON string using the protocol encode function', 'decode a raw JSON string into a validated message envelope dict using the protocol decode function', 'add a new remote meet node with a name, websocket url, and auth token to the NodeRegistry', 'get a specific node entry by name from the NodeRegistry file-backed JSON store', 'remove a named node from the NodeRegistry and return True if it existed', 'list all registered remote meet nodes sorted alphabetically by name from the NodeRegistry', 'resolve a chrome_node name to its url and token or auto-resolve when exactly one node is registered', 'run a NodeServer WebSocket server on host 0.0.0.0 port 18789 to handle meet bot RPC requests', 'generate and persist a 32 character hex auth token for the NodeServer using ensure_token', 'handle a start_bot RPC request that starts a Google Meet bot with a given URL and guest name', 'handle a transcript RPC request to retrieve the meeting transcript with optional last N lines', 'handle a say RPC request to enqueue text into the active meeting say queue JSONL file']
```

Usage

```
{'run_nodeserver_websocket': 'run a NodeServer WebSocket server on host 0.0.0.0 port 18789 to handle meet bot RPC requests', 'generate_auth_token': 'generate and persist a 32 character hex auth token for the NodeServer using ensure_token', 'handle_start_bot_request': 'handle a start_bot RPC request that starts a Google Meet bot with a given URL and guest name', 'handle_transcript_request': 'handle a transcript RPC request to retrieve the meeting transcript with optional last N lines', 'handle_say_request': 'handle a say RPC request to enqueue text into the active meeting say queue JSONL file'}
```

