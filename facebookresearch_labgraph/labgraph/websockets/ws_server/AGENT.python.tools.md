# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/labgraph/websockets/ws_server/ws_api_node_server.py

Prompts

```
['create a WSAPIServerConfig with app_id, ip, port, api_version, and optional num_messages for termination', 'build a WSAPIServerNode WebSocket API server node that subscribes to WSStreamMessage topics and forwards samples', 'test the create_batch_samples method to generate a list of sample data with timestamps for a given batch size', 'review the termination_background async method that polls and raises NormalTermination after receiving num_messages messages', 'refactor the ws_server_publisher subscriber method to handle WSStreamMessage routing, sample batching, and connection error recovery', 'run the WSServerNode main_loop to start a WebSocket server session and poll until shutdown', 'create a WSServerConfig with app_id, ip, port, api_version, and enums fields for WebSocket server setup', 'setup a WSServerNode by initializing ip, port, app_id, api_version, enums, stream, and shutdown from config', 'cleanup a WSServerNode by setting the shutdown flag to true to stop the main loop', 'review the WSServerNode class and its main_loop, setup, and cleanup lifecycle methods']
```

Usage

```
{'create_WSAPIServerConfig': 'create a WSAPIServerConfig with app_id, ip, port, api_version, and optional num_messages for termination', 'build_WSAPIServerNode': 'build a WSAPIServerNode WebSocket API server node that subscribes to WSStreamMessage topics and forwards samples', 'test_create_batch_samples': 'test the create_batch_samples method to generate a list of sample data with timestamps for a given batch size', 'review_termination_background': 'review the termination_background async method that polls and raises NormalTermination after receiving num_messages messages', 'refactor_ws_server_publisher': 'refactor the ws_server_publisher subscriber method to handle WSStreamMessage routing, sample batching, and connection error recovery'}
```

## File: facebookresearch_labgraph/labgraph/websockets/ws_server/ws_node_server.py

Prompts

```
['create a WSAPIServerConfig with app_id, ip, port, api_version, and optional num_messages for termination', 'build a WSAPIServerNode WebSocket API server node that subscribes to WSStreamMessage topics and forwards samples', 'test the create_batch_samples method to generate a list of sample data with timestamps for a given batch size', 'review the termination_background async method that polls and raises NormalTermination after receiving num_messages messages', 'refactor the ws_server_publisher subscriber method to handle WSStreamMessage routing, sample batching, and connection error recovery', 'run the WSServerNode main_loop to start a WebSocket server session and poll until shutdown', 'create a WSServerConfig with app_id, ip, port, api_version, and enums fields for WebSocket server setup', 'setup a WSServerNode by initializing ip, port, app_id, api_version, enums, stream, and shutdown from config', 'cleanup a WSServerNode by setting the shutdown flag to true to stop the main loop', 'review the WSServerNode class and its main_loop, setup, and cleanup lifecycle methods']
```

Usage

```
{'run_WSServerNode_main_loop': 'run the WSServerNode main_loop to start a WebSocket server session and poll until shutdown', 'create_WSServerConfig': 'create a WSServerConfig with app_id, ip, port, api_version, and enums fields for WebSocket server setup', 'setup_WSServerNode': 'setup a WSServerNode by initializing ip, port, app_id, api_version, enums, stream, and shutdown from config', 'cleanup_WSServerNode': 'cleanup a WSServerNode by setting the shutdown flag to true to stop the main loop', 'review_WSServerNode_class': 'review the WSServerNode class and its main_loop, setup, and cleanup lifecycle methods'}
```

