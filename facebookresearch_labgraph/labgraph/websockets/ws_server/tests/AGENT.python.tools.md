# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/labgraph/websockets/ws_server/tests/test_server_local.py

Prompts

```
['test the WSAPIServerNode by running a local graph that sends mock stream messages', 'create a MySource node that publishes WSStreamMessage samples to a WebSocket server topic', 'run a LocalRunner with a graph connecting MySource to WSAPIServerNode for local testing', 'configure a WSAPIServerConfig with app_id, ip, port, api_version, and sample_rate settings', 'review the MyWSSenderGraph connections that wire MySource.TOPIC to WSAPIServerNode.topic', 'test the WSAPIServerNode by publishing a WSStreamMessage through the ws_server_publisher', 'create a WSAPIServerConfig with app_id, ip, port, api_version, num_messages, and enums', 'create a WSStreamMessage with samples, stream_name, and stream_id for WebSocket communication', 'run the node ws_server_publisher asynchronously with a WSStreamMessage as an argument', 'use NodeTestHarness to set up and tear down a WSAPIServerNode with a given config']
```

Usage

```
{'test_WSAPIServerNode_local': 'test the WSAPIServerNode by running a local graph that sends mock stream messages', 'create_MySource_node': 'create a MySource node that publishes WSStreamMessage samples to a WebSocket server topic', 'run_LocalRunner_graph': 'run a LocalRunner with a graph connecting MySource to WSAPIServerNode for local testing', 'configure_WSAPIServerConfig': 'configure a WSAPIServerConfig with app_id, ip, port, api_version, and sample_rate settings', 'review_MyWSSenderGraph_connections': 'review the MyWSSenderGraph connections that wire MySource.TOPIC to WSAPIServerNode.topic'}
```

## File: facebookresearch_labgraph/labgraph/websockets/ws_server/tests/test_ws_node_server.py

Prompts

```
['test the WSAPIServerNode by running a local graph that sends mock stream messages', 'create a MySource node that publishes WSStreamMessage samples to a WebSocket server topic', 'run a LocalRunner with a graph connecting MySource to WSAPIServerNode for local testing', 'configure a WSAPIServerConfig with app_id, ip, port, api_version, and sample_rate settings', 'review the MyWSSenderGraph connections that wire MySource.TOPIC to WSAPIServerNode.topic', 'test the WSAPIServerNode by publishing a WSStreamMessage through the ws_server_publisher', 'create a WSAPIServerConfig with app_id, ip, port, api_version, num_messages, and enums', 'create a WSStreamMessage with samples, stream_name, and stream_id for WebSocket communication', 'run the node ws_server_publisher asynchronously with a WSStreamMessage as an argument', 'use NodeTestHarness to set up and tear down a WSAPIServerNode with a given config']
```

Usage

```
{'test_WSAPIServerNode': 'test the WSAPIServerNode by publishing a WSStreamMessage through the ws_server_publisher', 'create_WSAPIServerConfig': 'create a WSAPIServerConfig with app_id, ip, port, api_version, num_messages, and enums', 'create_WSStreamMessage': 'create a WSStreamMessage with samples, stream_name, and stream_id for WebSocket communication', 'run_async_publisher': 'run the node ws_server_publisher asynchronously with a WSStreamMessage as an argument', 'use_NodeTestHarness': 'use NodeTestHarness to set up and tear down a WSAPIServerNode with a given config'}
```

