# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/chat_service/services/websocket/agents.py

Prompts

```
['create a WebsocketAgent instance with opt, manager, receiver_id, and task_id parameters', 'send a message to a websocket agent using the observe method with text or payload', 'queue an incoming websocket message into the agent using the put_data method', 'send a base64 encoded image through the observe method using a payload dict with type and data keys', 'send a message with quick replies by including a quick_replies list in the act dict', 'run the websocket chat service by executing the run module with a config file path', 'create a ParlaiParser with websocket arguments and parse command line options', 'start the WebsocketManager task and handle graceful shutdown on exceptions', 'parse a configuration file and merge world options into the parser options', 'review the websocket runner entry point that manages the WebsocketManager lifecycle', 'create a MessageSocketHandler subclass to handle incoming WebSocket connections with a custom message callback', 'open a new WebSocket connection that auto-assigns a UUID and registers the socket in the subs dictionary', 'handle an incoming WebSocket message by parsing JSON text and payload and invoking the message callback', 'close a WebSocket connection and remove its socket ID from the subs subscriber dictionary', 'generate a random UUID string using the get_rand_id function for socket identification', 'run a WebsocketManager to manage agent interactions over websockets using given setup options', 'start the WebsocketManager task to begin handling websocket connections on a specified port', 'send a text message with optional quick replies to a specific agent socket via websocket', 'send a payload like base64 encoded image data to a specific agent socket via websocket', 'shutdown the WebsocketManager to stop the tornado application and expire all conversations']
```

Usage

```
{'create_websocket_agent': 'create a WebsocketAgent instance with opt, manager, receiver_id, and task_id parameters', 'send_message_via_observe': 'send a message to a websocket agent using the observe method with text or payload', 'queue_incoming_message': 'queue an incoming websocket message into the agent using the put_data method', 'send_image_payload': 'send a base64 encoded image through the observe method using a payload dict with type and data keys', 'send_quick_replies': 'send a message with quick replies by including a quick_replies list in the act dict'}
```

## File: facebookresearch_parlai/parlai/chat_service/services/websocket/run.py

Prompts

```
['create a WebsocketAgent instance with opt, manager, receiver_id, and task_id parameters', 'send a message to a websocket agent using the observe method with text or payload', 'queue an incoming websocket message into the agent using the put_data method', 'send a base64 encoded image through the observe method using a payload dict with type and data keys', 'send a message with quick replies by including a quick_replies list in the act dict', 'run the websocket chat service by executing the run module with a config file path', 'create a ParlaiParser with websocket arguments and parse command line options', 'start the WebsocketManager task and handle graceful shutdown on exceptions', 'parse a configuration file and merge world options into the parser options', 'review the websocket runner entry point that manages the WebsocketManager lifecycle', 'create a MessageSocketHandler subclass to handle incoming WebSocket connections with a custom message callback', 'open a new WebSocket connection that auto-assigns a UUID and registers the socket in the subs dictionary', 'handle an incoming WebSocket message by parsing JSON text and payload and invoking the message callback', 'close a WebSocket connection and remove its socket ID from the subs subscriber dictionary', 'generate a random UUID string using the get_rand_id function for socket identification', 'run a WebsocketManager to manage agent interactions over websockets using given setup options', 'start the WebsocketManager task to begin handling websocket connections on a specified port', 'send a text message with optional quick replies to a specific agent socket via websocket', 'send a payload like base64 encoded image data to a specific agent socket via websocket', 'shutdown the WebsocketManager to stop the tornado application and expire all conversations']
```

Usage

```
{'run_websocket_service': 'run the websocket chat service by executing the run module with a config file path', 'setup_websocket_args': 'create a ParlaiParser with websocket arguments and parse command line options', 'start_websocket_manager': 'start the WebsocketManager task and handle graceful shutdown on exceptions', 'load_websocket_config': 'parse a configuration file and merge world options into the parser options', 'review_websocket_runner': 'review the websocket runner entry point that manages the WebsocketManager lifecycle'}
```

## File: facebookresearch_parlai/parlai/chat_service/services/websocket/sockets.py

Prompts

```
['create a WebsocketAgent instance with opt, manager, receiver_id, and task_id parameters', 'send a message to a websocket agent using the observe method with text or payload', 'queue an incoming websocket message into the agent using the put_data method', 'send a base64 encoded image through the observe method using a payload dict with type and data keys', 'send a message with quick replies by including a quick_replies list in the act dict', 'run the websocket chat service by executing the run module with a config file path', 'create a ParlaiParser with websocket arguments and parse command line options', 'start the WebsocketManager task and handle graceful shutdown on exceptions', 'parse a configuration file and merge world options into the parser options', 'review the websocket runner entry point that manages the WebsocketManager lifecycle', 'create a MessageSocketHandler subclass to handle incoming WebSocket connections with a custom message callback', 'open a new WebSocket connection that auto-assigns a UUID and registers the socket in the subs dictionary', 'handle an incoming WebSocket message by parsing JSON text and payload and invoking the message callback', 'close a WebSocket connection and remove its socket ID from the subs subscriber dictionary', 'generate a random UUID string using the get_rand_id function for socket identification', 'run a WebsocketManager to manage agent interactions over websockets using given setup options', 'start the WebsocketManager task to begin handling websocket connections on a specified port', 'send a text message with optional quick replies to a specific agent socket via websocket', 'send a payload like base64 encoded image data to a specific agent socket via websocket', 'shutdown the WebsocketManager to stop the tornado application and expire all conversations']
```

Usage

```
{'create_websocket_handler': 'create a MessageSocketHandler subclass to handle incoming WebSocket connections with a custom message callback', 'open_websocket_connection': 'open a new WebSocket connection that auto-assigns a UUID and registers the socket in the subs dictionary', 'handle_websocket_message': 'handle an incoming WebSocket message by parsing JSON text and payload and invoking the message callback', 'close_websocket_connection': 'close a WebSocket connection and remove its socket ID from the subs subscriber dictionary', 'generate_random_uuid': 'generate a random UUID string using the get_rand_id function for socket identification'}
```

## File: facebookresearch_parlai/parlai/chat_service/services/websocket/websocket_manager.py

Prompts

```
['create a WebsocketAgent instance with opt, manager, receiver_id, and task_id parameters', 'send a message to a websocket agent using the observe method with text or payload', 'queue an incoming websocket message into the agent using the put_data method', 'send a base64 encoded image through the observe method using a payload dict with type and data keys', 'send a message with quick replies by including a quick_replies list in the act dict', 'run the websocket chat service by executing the run module with a config file path', 'create a ParlaiParser with websocket arguments and parse command line options', 'start the WebsocketManager task and handle graceful shutdown on exceptions', 'parse a configuration file and merge world options into the parser options', 'review the websocket runner entry point that manages the WebsocketManager lifecycle', 'create a MessageSocketHandler subclass to handle incoming WebSocket connections with a custom message callback', 'open a new WebSocket connection that auto-assigns a UUID and registers the socket in the subs dictionary', 'handle an incoming WebSocket message by parsing JSON text and payload and invoking the message callback', 'close a WebSocket connection and remove its socket ID from the subs subscriber dictionary', 'generate a random UUID string using the get_rand_id function for socket identification', 'run a WebsocketManager to manage agent interactions over websockets using given setup options', 'start the WebsocketManager task to begin handling websocket connections on a specified port', 'send a text message with optional quick replies to a specific agent socket via websocket', 'send a payload like base64 encoded image data to a specific agent socket via websocket', 'shutdown the WebsocketManager to stop the tornado application and expire all conversations']
```

Usage

```
{'run_websocket_manager': 'run a WebsocketManager to manage agent interactions over websockets using given setup options', 'start_websocket_task': 'start the WebsocketManager task to begin handling websocket connections on a specified port', 'observe_message_to_socket': 'send a text message with optional quick replies to a specific agent socket via websocket', 'observe_payload_to_socket': 'send a payload like base64 encoded image data to a specific agent socket via websocket', 'shutdown_websocket_manager': 'shutdown the WebsocketManager to stop the tornado application and expire all conversations'}
```

