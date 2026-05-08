# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/labgraph/websockets/ws_client/api_message_constructor.py

Prompts

```
['build a python module that constructs a serialized StartStreamRequest JSON message for a given target and stream ID', 'build a python module that constructs a serialized EndStreamRequest JSON message for a given stream ID', 'create a StartStreamRequest JSON message that includes an optional app_id for the specified data stream', 'test the get_start_stream_request function to verify it returns valid JSON with the correct target and stream ID', 'test the get_end_stream_request function to verify it returns valid JSON with the correct stream ID', 'create a WSPollerConfig with app_id, ip, port, and api_version fields for websocket polling', 'connect a WSPollerNode to a websocket server using the configured ip and port', 'start streaming data from a websocket connection by sending a start stream message', 'receive the next message from the websocket connection synchronously or asynchronously', 'run the ws_publisher async generator to continuously poll and yield WSMessage objects from websocket', 'create a STREAMWSPollerConfig with streams list, optional stream_ids, ip, port, and api_version fields', 'setup a STREAMWSPollerNode that validates streams and stream_ids match and auto-generates UUIDs if needed', 'start websocket streams on a STREAMWSPollerNode by sending start stream requests for each configured stream', 'end websocket streams on a STREAMWSPollerNode by sending end stream requests for each configured stream', "get the stream_id for a given stream_name from a STREAMWSPollerNode's streams mapping"]
```

Usage

```
{'build_start_stream_request': 'build a python module that constructs a serialized StartStreamRequest JSON message for a given target and stream ID', 'build_end_stream_request': 'build a python module that constructs a serialized EndStreamRequest JSON message for a given stream ID', 'create_start_stream_with_app_id': 'create a StartStreamRequest JSON message that includes an optional app_id for the specified data stream', 'test_get_start_stream_request': 'test the get_start_stream_request function to verify it returns valid JSON with the correct target and stream ID', 'test_get_end_stream_request': 'test the get_end_stream_request function to verify it returns valid JSON with the correct stream ID'}
```

## File: facebookresearch_labgraph/labgraph/websockets/ws_client/ws_poller_node.py

Prompts

```
['build a python module that constructs a serialized StartStreamRequest JSON message for a given target and stream ID', 'build a python module that constructs a serialized EndStreamRequest JSON message for a given stream ID', 'create a StartStreamRequest JSON message that includes an optional app_id for the specified data stream', 'test the get_start_stream_request function to verify it returns valid JSON with the correct target and stream ID', 'test the get_end_stream_request function to verify it returns valid JSON with the correct stream ID', 'create a WSPollerConfig with app_id, ip, port, and api_version fields for websocket polling', 'connect a WSPollerNode to a websocket server using the configured ip and port', 'start streaming data from a websocket connection by sending a start stream message', 'receive the next message from the websocket connection synchronously or asynchronously', 'run the ws_publisher async generator to continuously poll and yield WSMessage objects from websocket', 'create a STREAMWSPollerConfig with streams list, optional stream_ids, ip, port, and api_version fields', 'setup a STREAMWSPollerNode that validates streams and stream_ids match and auto-generates UUIDs if needed', 'start websocket streams on a STREAMWSPollerNode by sending start stream requests for each configured stream', 'end websocket streams on a STREAMWSPollerNode by sending end stream requests for each configured stream', "get the stream_id for a given stream_name from a STREAMWSPollerNode's streams mapping"]
```

Usage

```
{'create_WSPollerConfig': 'create a WSPollerConfig with app_id, ip, port, and api_version fields for websocket polling', 'connect_WSPollerNode': 'connect a WSPollerNode to a websocket server using the configured ip and port', 'start_streaming_WSPollerNode': 'start streaming data from a websocket connection by sending a start stream message', 'recv_WSPollerNode': 'receive the next message from the websocket connection synchronously or asynchronously', 'ws_publisher_WSPollerNode': 'run the ws_publisher async generator to continuously poll and yield WSMessage objects from websocket'}
```

## File: facebookresearch_labgraph/labgraph/websockets/ws_client/ws_poller_stream_node.py

Prompts

```
['build a python module that constructs a serialized StartStreamRequest JSON message for a given target and stream ID', 'build a python module that constructs a serialized EndStreamRequest JSON message for a given stream ID', 'create a StartStreamRequest JSON message that includes an optional app_id for the specified data stream', 'test the get_start_stream_request function to verify it returns valid JSON with the correct target and stream ID', 'test the get_end_stream_request function to verify it returns valid JSON with the correct stream ID', 'create a WSPollerConfig with app_id, ip, port, and api_version fields for websocket polling', 'connect a WSPollerNode to a websocket server using the configured ip and port', 'start streaming data from a websocket connection by sending a start stream message', 'receive the next message from the websocket connection synchronously or asynchronously', 'run the ws_publisher async generator to continuously poll and yield WSMessage objects from websocket', 'create a STREAMWSPollerConfig with streams list, optional stream_ids, ip, port, and api_version fields', 'setup a STREAMWSPollerNode that validates streams and stream_ids match and auto-generates UUIDs if needed', 'start websocket streams on a STREAMWSPollerNode by sending start stream requests for each configured stream', 'end websocket streams on a STREAMWSPollerNode by sending end stream requests for each configured stream', "get the stream_id for a given stream_name from a STREAMWSPollerNode's streams mapping"]
```

Usage

```
{'create_STREAMWSPollerConfig': 'create a STREAMWSPollerConfig with streams list, optional stream_ids, ip, port, and api_version fields', 'setup_STREAMWSPollerNode': 'setup a STREAMWSPollerNode that validates streams and stream_ids match and auto-generates UUIDs if needed', 'start_streams_STREAMWSPollerNode': 'start websocket streams on a STREAMWSPollerNode by sending start stream requests for each configured stream', 'end_streams_STREAMWSPollerNode': 'end websocket streams on a STREAMWSPollerNode by sending end stream requests for each configured stream', 'get_stream_id_STREAMWSPollerNode': "get the stream_id for a given stream_name from a STREAMWSPollerNode's streams mapping"}
```

