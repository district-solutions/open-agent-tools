# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/labgraph/websockets/ws_server/session/session.py

Prompts

```
['send samples to all active streams matching a given stream name via the Session websocket', 'add an ApiStreamDesc to the Session so it receives sample messages for its stream name', 'remove an ApiStreamDesc from the Session and clean up its batch number tracking', 'get all ApiStreamDesc objects registered in the Session that match a given stream name', 'check whether a given stream name has any active streams registered in the Session', 'create a new WebSocket session with an IP, port, and enums object and return its session ID', 'retrieve a WebSocket session object by its session ID from the session manager', 'get the current number of active WebSocket sessions managed by the session manager', "stop all active WebSocket sessions and clear the session manager's session list", 'generate the next unique session ID using an incrementing counter', 'run the WSServer process method to handle incoming websocket connections and stream requests', 'create a WSServer instance with enums and configurable timeout and sleep pause settings', 'start a websocket stream connection by sending a start stream request message to the client', 'end a websocket stream connection by sending an end stream request message to the client', 'check if a named stream is currently active in the WSServer streams dictionary', 'create a WebSocketSession with an ip, port, session_id, and enums object', 'start a WebSocketSession to launch a websocket server on the configured ip and port', 'stop a running WebSocketSession by halting the event loop and joining the thread', 'write data to connected websocket clients via the async write method on WebSocketSession', 'review the WebSocketSession class and its start, stop, and write methods']
```

Usage

```
{'send_samples_to_streams': 'send samples to all active streams matching a given stream name via the Session websocket', 'add_stream_to_session': 'add an ApiStreamDesc to the Session so it receives sample messages for its stream name', 'remove_stream_from_session': 'remove an ApiStreamDesc from the Session and clean up its batch number tracking', 'get_streams_by_name': 'get all ApiStreamDesc objects registered in the Session that match a given stream name', 'check_stream_name_active': 'check whether a given stream name has any active streams registered in the Session'}
```

## File: facebookresearch_labgraph/labgraph/websockets/ws_server/session/session_manager.py

Prompts

```
['send samples to all active streams matching a given stream name via the Session websocket', 'add an ApiStreamDesc to the Session so it receives sample messages for its stream name', 'remove an ApiStreamDesc from the Session and clean up its batch number tracking', 'get all ApiStreamDesc objects registered in the Session that match a given stream name', 'check whether a given stream name has any active streams registered in the Session', 'create a new WebSocket session with an IP, port, and enums object and return its session ID', 'retrieve a WebSocket session object by its session ID from the session manager', 'get the current number of active WebSocket sessions managed by the session manager', "stop all active WebSocket sessions and clear the session manager's session list", 'generate the next unique session ID using an incrementing counter', 'run the WSServer process method to handle incoming websocket connections and stream requests', 'create a WSServer instance with enums and configurable timeout and sleep pause settings', 'start a websocket stream connection by sending a start stream request message to the client', 'end a websocket stream connection by sending an end stream request message to the client', 'check if a named stream is currently active in the WSServer streams dictionary', 'create a WebSocketSession with an ip, port, session_id, and enums object', 'start a WebSocketSession to launch a websocket server on the configured ip and port', 'stop a running WebSocketSession by halting the event loop and joining the thread', 'write data to connected websocket clients via the async write method on WebSocketSession', 'review the WebSocketSession class and its start, stop, and write methods']
```

Usage

```
{'add_websocket_session': 'create a new WebSocket session with an IP, port, and enums object and return its session ID', 'get_session': 'retrieve a WebSocket session object by its session ID from the session manager', 'num_sessions': 'get the current number of active WebSocket sessions managed by the session manager', 'clear_sessions': "stop all active WebSocket sessions and clear the session manager's session list", 'get_session_id': 'generate the next unique session ID using an incrementing counter'}
```

## File: facebookresearch_labgraph/labgraph/websockets/ws_server/session/ws_server.py

Prompts

```
['send samples to all active streams matching a given stream name via the Session websocket', 'add an ApiStreamDesc to the Session so it receives sample messages for its stream name', 'remove an ApiStreamDesc from the Session and clean up its batch number tracking', 'get all ApiStreamDesc objects registered in the Session that match a given stream name', 'check whether a given stream name has any active streams registered in the Session', 'create a new WebSocket session with an IP, port, and enums object and return its session ID', 'retrieve a WebSocket session object by its session ID from the session manager', 'get the current number of active WebSocket sessions managed by the session manager', "stop all active WebSocket sessions and clear the session manager's session list", 'generate the next unique session ID using an incrementing counter', 'run the WSServer process method to handle incoming websocket connections and stream requests', 'create a WSServer instance with enums and configurable timeout and sleep pause settings', 'start a websocket stream connection by sending a start stream request message to the client', 'end a websocket stream connection by sending an end stream request message to the client', 'check if a named stream is currently active in the WSServer streams dictionary', 'create a WebSocketSession with an ip, port, session_id, and enums object', 'start a WebSocketSession to launch a websocket server on the configured ip and port', 'stop a running WebSocketSession by halting the event loop and joining the thread', 'write data to connected websocket clients via the async write method on WebSocketSession', 'review the WebSocketSession class and its start, stop, and write methods']
```

Usage

```
{'run_ws_server_process': 'run the WSServer process method to handle incoming websocket connections and stream requests', 'create_ws_server_instance': 'create a WSServer instance with enums and configurable timeout and sleep pause settings', 'start_ws_stream_connection': 'start a websocket stream connection by sending a start stream request message to the client', 'end_ws_stream_connection': 'end a websocket stream connection by sending an end stream request message to the client', 'check_ws_stream_active': 'check if a named stream is currently active in the WSServer streams dictionary'}
```

## File: facebookresearch_labgraph/labgraph/websockets/ws_server/session/ws_session.py

Prompts

```
['send samples to all active streams matching a given stream name via the Session websocket', 'add an ApiStreamDesc to the Session so it receives sample messages for its stream name', 'remove an ApiStreamDesc from the Session and clean up its batch number tracking', 'get all ApiStreamDesc objects registered in the Session that match a given stream name', 'check whether a given stream name has any active streams registered in the Session', 'create a new WebSocket session with an IP, port, and enums object and return its session ID', 'retrieve a WebSocket session object by its session ID from the session manager', 'get the current number of active WebSocket sessions managed by the session manager', "stop all active WebSocket sessions and clear the session manager's session list", 'generate the next unique session ID using an incrementing counter', 'run the WSServer process method to handle incoming websocket connections and stream requests', 'create a WSServer instance with enums and configurable timeout and sleep pause settings', 'start a websocket stream connection by sending a start stream request message to the client', 'end a websocket stream connection by sending an end stream request message to the client', 'check if a named stream is currently active in the WSServer streams dictionary', 'create a WebSocketSession with an ip, port, session_id, and enums object', 'start a WebSocketSession to launch a websocket server on the configured ip and port', 'stop a running WebSocketSession by halting the event loop and joining the thread', 'write data to connected websocket clients via the async write method on WebSocketSession', 'review the WebSocketSession class and its start, stop, and write methods']
```

Usage

```
{'create_websocket_session': 'create a WebSocketSession with an ip, port, session_id, and enums object', 'start_websocket_session': 'start a WebSocketSession to launch a websocket server on the configured ip and port', 'stop_websocket_session': 'stop a running WebSocketSession by halting the event loop and joining the thread', 'write_websocket_data': 'write data to connected websocket clients via the async write method on WebSocketSession', 'review_websocket_session_class': 'review the WebSocketSession class and its start, stop, and write methods'}
```

