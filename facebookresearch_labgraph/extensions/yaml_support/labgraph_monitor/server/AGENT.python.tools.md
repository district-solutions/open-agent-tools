# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/extensions/yaml_support/labgraph_monitor/server/lg_monitor_server.py

Prompts

```
['run a websocket server graph that streams a labgraph topology to connected clients', 'review the WSSenderNode inner class that wires a Serializer and WSAPIServerNode together', 'create a WSAPIServerConfig with app_id, ip, port, api_version, and sample_rate settings', 'configure a SerializerConfig with serialized graph data, sample rate, stream name, and stream id', 'summarize the run_topology function that creates and runs a labgraph WebSocket monitoring server', 'create a SerializerConfig with data, sample_rate, stream_name, and stream_id fields for labgraph node configuration', 'create a DataState class with four optional dictionary slots for storing serialized message data', 'build a Serializer labgraph Node that subscribes to four RandomMessage topics and publishes WSStreamMessage outputs', 'review the Serializer get_grouping method that matches subscriber topics with their upstream grouping keys', 'test the Serializer async source publisher that yields WSStreamMessage samples at a configurable sample rate']
```

Usage

```
{'run_topology': 'run a websocket server graph that streams a labgraph topology to connected clients', 'review_WSSenderNode': 'review the WSSenderNode inner class that wires a Serializer and WSAPIServerNode together', 'create_WSAPIServerConfig': 'create a WSAPIServerConfig with app_id, ip, port, api_version, and sample_rate settings', 'configure_SerializerConfig': 'configure a SerializerConfig with serialized graph data, sample rate, stream name, and stream id', 'summarize_run_topology': 'summarize the run_topology function that creates and runs a labgraph WebSocket monitoring server'}
```

## File: facebookresearch_labgraph/extensions/yaml_support/labgraph_monitor/server/serializer_node.py

Prompts

```
['run a websocket server graph that streams a labgraph topology to connected clients', 'review the WSSenderNode inner class that wires a Serializer and WSAPIServerNode together', 'create a WSAPIServerConfig with app_id, ip, port, api_version, and sample_rate settings', 'configure a SerializerConfig with serialized graph data, sample rate, stream name, and stream id', 'summarize the run_topology function that creates and runs a labgraph WebSocket monitoring server', 'create a SerializerConfig with data, sample_rate, stream_name, and stream_id fields for labgraph node configuration', 'create a DataState class with four optional dictionary slots for storing serialized message data', 'build a Serializer labgraph Node that subscribes to four RandomMessage topics and publishes WSStreamMessage outputs', 'review the Serializer get_grouping method that matches subscriber topics with their upstream grouping keys', 'test the Serializer async source publisher that yields WSStreamMessage samples at a configurable sample rate']
```

Usage

```
{'create_serializer_config': 'create a SerializerConfig with data, sample_rate, stream_name, and stream_id fields for labgraph node configuration', 'create_data_state': 'create a DataState class with four optional dictionary slots for storing serialized message data', 'build_serializer_node': 'build a Serializer labgraph Node that subscribes to four RandomMessage topics and publishes WSStreamMessage outputs', 'review_get_grouping': 'review the Serializer get_grouping method that matches subscriber topics with their upstream grouping keys', 'test_source_publisher': 'test the Serializer async source publisher that yields WSStreamMessage samples at a configurable sample rate'}
```

