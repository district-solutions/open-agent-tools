# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/labgraph/websockets/ws_server/api/api_request.py

Prompts

```
['parse a JSON websocket message into an APIRequest object with request id, stream id, and app id', 'validate that a JSON message contains the required api version and api request fields', 'update a base stream message with the request id and stream id from an APIRequest', 'check if an APIRequest stream name matches the LABGRAPH_MONITOR stream type', 'check if an APIRequest is a start stream or end stream request type', 'build a LabGraph WS API start stream request message with a stream ID and request ID', 'build a LabGraph WS API error message for a non-existent stream with a request ID', 'build a LabGraph WS API end stream request message with a stream ID and request ID', 'build a sample data message from a numpy array and produced timestamp for streaming', 'review the ws_api_message_constructor module and its functions for building LabGraph WebSocket API messages']
```

Usage

```
{'parse_api_request': 'parse a JSON websocket message into an APIRequest object with request id, stream id, and app id', 'validate_json_message': 'validate that a JSON message contains the required api version and api request fields', 'update_stream_request': 'update a base stream message with the request id and stream id from an APIRequest', 'check_labgraph_monitor': 'check if an APIRequest stream name matches the LABGRAPH_MONITOR stream type', 'check_request_type': 'check if an APIRequest is a start stream or end stream request type'}
```

## File: facebookresearch_labgraph/labgraph/websockets/ws_server/api/ws_api_message_constructor.py

Prompts

```
['parse a JSON websocket message into an APIRequest object with request id, stream id, and app id', 'validate that a JSON message contains the required api version and api request fields', 'update a base stream message with the request id and stream id from an APIRequest', 'check if an APIRequest stream name matches the LABGRAPH_MONITOR stream type', 'check if an APIRequest is a start stream or end stream request type', 'build a LabGraph WS API start stream request message with a stream ID and request ID', 'build a LabGraph WS API error message for a non-existent stream with a request ID', 'build a LabGraph WS API end stream request message with a stream ID and request ID', 'build a sample data message from a numpy array and produced timestamp for streaming', 'review the ws_api_message_constructor module and its functions for building LabGraph WebSocket API messages']
```

Usage

```
{'build_start_stream_request': 'build a LabGraph WS API start stream request message with a stream ID and request ID', 'build_start_stream_error': 'build a LabGraph WS API error message for a non-existent stream with a request ID', 'build_end_stream_request': 'build a LabGraph WS API end stream request message with a stream ID and request ID', 'build_sample_data_message': 'build a sample data message from a numpy array and produced timestamp for streaming', 'review_ws_api_message_constructor': 'review the ws_api_message_constructor module and its functions for building LabGraph WebSocket API messages'}
```

