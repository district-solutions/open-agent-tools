# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/chat_service/core/agents.py

Prompts

```
['create a subclass of ChatServiceAgent implementing observe and put_data abstract methods', 'send a payload with quick replies and persona id through the message manager', 'queue an action by id into the message queue only if it has not been seen', 'repeatedly poll the message queue for a new act message with an optional timeout', 'retrieve and set the agent stored data from the manager using the agent id', 'create a subclass of ChatServiceManager that implements abstract methods for a new messaging platform', 'manage AgentState to track active agents, task assignments, and pool membership for a chat service user', 'start the task matching loop that pairs agents from the pool into conversation worlds', 'launch an overworld conversation for a new agent and handle onboarding before task assignment', 'handle incoming messages by routing them to the correct agent and launching overworlds for first-time users', 'create a ChatServiceMessageSocket instance with a server URL, port, and message callback function', 'setup websocket open, error, disconnect, and message handlers for a chat service socket', 'send a world_alive registration message to the passthrough server via the socket', 'safely send data over the websocket with automatic retry and connection state checks', 'ensure the websocket connection is safely closed even if already disconnected', 'launch a task world with agents and return the future object for async execution', 'shutdown the ChatServiceWorldRunner and all active task worlds gracefully', 'run a world until episode completion and return the last parley output and world data', 'check if the ChatServiceWorldRunner has finished its async module initialization']
```

Usage

```
{'create_chat_service_agent_subclass': 'create a subclass of ChatServiceAgent implementing observe and put_data abstract methods', 'send_payload_through_manager': 'send a payload with quick replies and persona id through the message manager', 'queue_action_with_deduplication': 'queue an action by id into the message queue only if it has not been seen', 'retrieve_message_blocking_with_timeout': 'repeatedly poll the message queue for a new act message with an optional timeout', 'load_agent_stored_data': 'retrieve and set the agent stored data from the manager using the agent id'}
```

## File: facebookresearch_parlai/parlai/chat_service/core/chat_service_manager.py

Prompts

```
['create a subclass of ChatServiceAgent implementing observe and put_data abstract methods', 'send a payload with quick replies and persona id through the message manager', 'queue an action by id into the message queue only if it has not been seen', 'repeatedly poll the message queue for a new act message with an optional timeout', 'retrieve and set the agent stored data from the manager using the agent id', 'create a subclass of ChatServiceManager that implements abstract methods for a new messaging platform', 'manage AgentState to track active agents, task assignments, and pool membership for a chat service user', 'start the task matching loop that pairs agents from the pool into conversation worlds', 'launch an overworld conversation for a new agent and handle onboarding before task assignment', 'handle incoming messages by routing them to the correct agent and launching overworlds for first-time users', 'create a ChatServiceMessageSocket instance with a server URL, port, and message callback function', 'setup websocket open, error, disconnect, and message handlers for a chat service socket', 'send a world_alive registration message to the passthrough server via the socket', 'safely send data over the websocket with automatic retry and connection state checks', 'ensure the websocket connection is safely closed even if already disconnected', 'launch a task world with agents and return the future object for async execution', 'shutdown the ChatServiceWorldRunner and all active task worlds gracefully', 'run a world until episode completion and return the last parley output and world data', 'check if the ChatServiceWorldRunner has finished its async module initialization']
```

Usage

```
{'create_chat_service_manager_subclass': 'create a subclass of ChatServiceManager that implements abstract methods for a new messaging platform', 'manage_agent_state': 'manage AgentState to track active agents, task assignments, and pool membership for a chat service user', 'start_task_matching': 'start the task matching loop that pairs agents from the pool into conversation worlds', 'launch_overworld': 'launch an overworld conversation for a new agent and handle onboarding before task assignment', 'handle_incoming_message': 'handle incoming messages by routing them to the correct agent and launching overworlds for first-time users'}
```

## File: facebookresearch_parlai/parlai/chat_service/core/socket.py

Prompts

```
['create a subclass of ChatServiceAgent implementing observe and put_data abstract methods', 'send a payload with quick replies and persona id through the message manager', 'queue an action by id into the message queue only if it has not been seen', 'repeatedly poll the message queue for a new act message with an optional timeout', 'retrieve and set the agent stored data from the manager using the agent id', 'create a subclass of ChatServiceManager that implements abstract methods for a new messaging platform', 'manage AgentState to track active agents, task assignments, and pool membership for a chat service user', 'start the task matching loop that pairs agents from the pool into conversation worlds', 'launch an overworld conversation for a new agent and handle onboarding before task assignment', 'handle incoming messages by routing them to the correct agent and launching overworlds for first-time users', 'create a ChatServiceMessageSocket instance with a server URL, port, and message callback function', 'setup websocket open, error, disconnect, and message handlers for a chat service socket', 'send a world_alive registration message to the passthrough server via the socket', 'safely send data over the websocket with automatic retry and connection state checks', 'ensure the websocket connection is safely closed even if already disconnected', 'launch a task world with agents and return the future object for async execution', 'shutdown the ChatServiceWorldRunner and all active task worlds gracefully', 'run a world until episode completion and return the last parley output and world data', 'check if the ChatServiceWorldRunner has finished its async module initialization']
```

Usage

```
{'create_chat_service_message_socket': 'create a ChatServiceMessageSocket instance with a server URL, port, and message callback function', 'setup_websocket_handlers': 'setup websocket open, error, disconnect, and message handlers for a chat service socket', 'send_world_alive_message': 'send a world_alive registration message to the passthrough server via the socket', 'safe_send_data': 'safely send data over the websocket with automatic retry and connection state checks', 'ensure_socket_closed': 'ensure the websocket connection is safely closed even if already disconnected'}
```

## File: facebookresearch_parlai/parlai/chat_service/core/world_runner.py

Prompts

```
['create a subclass of ChatServiceAgent implementing observe and put_data abstract methods', 'send a payload with quick replies and persona id through the message manager', 'queue an action by id into the message queue only if it has not been seen', 'repeatedly poll the message queue for a new act message with an optional timeout', 'retrieve and set the agent stored data from the manager using the agent id', 'create a subclass of ChatServiceManager that implements abstract methods for a new messaging platform', 'manage AgentState to track active agents, task assignments, and pool membership for a chat service user', 'start the task matching loop that pairs agents from the pool into conversation worlds', 'launch an overworld conversation for a new agent and handle onboarding before task assignment', 'handle incoming messages by routing them to the correct agent and launching overworlds for first-time users', 'create a ChatServiceMessageSocket instance with a server URL, port, and message callback function', 'setup websocket open, error, disconnect, and message handlers for a chat service socket', 'send a world_alive registration message to the passthrough server via the socket', 'safely send data over the websocket with automatic retry and connection state checks', 'ensure the websocket connection is safely closed even if already disconnected', 'launch a task world with agents and return the future object for async execution', 'shutdown the ChatServiceWorldRunner and all active task worlds gracefully', 'run a world until episode completion and return the last parley output and world data', 'check if the ChatServiceWorldRunner has finished its async module initialization']
```

Usage

```
{'launch_task_world': 'launch a task world with agents and return the future object for async execution', 'launch_overworld': 'launch an overworld with onboarding map and agent to handle agent routing and onboarding', 'shutdown_world_runner': 'shutdown the ChatServiceWorldRunner and all active task worlds gracefully', 'run_world': 'run a world until episode completion and return the last parley output and world data', 'check_initialization': 'check if the ChatServiceWorldRunner has finished its async module initialization'}
```

