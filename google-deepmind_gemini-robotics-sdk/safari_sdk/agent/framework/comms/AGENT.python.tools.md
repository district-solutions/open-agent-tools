# Agent Python Tools

- repo: google-deepmind/gemini-robotics-sdk
- repo_uri: https://github.com/google-deepmind/gemini-robotics-sdk

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/agent/framework/comms/external_controller.py

Prompts

```
['run a FastAPI server to externally control the EAR agent framework via HTTP endpoints', 'execute a long-horizon task by sending a task instruction to the agent via the execute_lh_task endpoint', 'stream the EAR framework status at 1Hz to monitor agent health and long-horizon task progress', 'stream events of specified types from the event bus as an SSE feed to the client', 'publish an event to the agent framework event bus via a POST request with type, source, data, and metadata', 'create an EventBusLogHandler instance that publishes log messages to an event bus with a configurable minimum log level', 'set the asyncio event loop on an EventBusLogHandler so it can publish log events asynchronously', 'emit a log record as a SYSTEM_LOG event to the event bus with level, message, module, function name, and line number', 'configure the minimum logging level for an EventBusLogHandler to filter which messages get published to the event bus', 'handle errors during log emission by delegating to the standard logging handler error mechanism']
```

Usage

```
{'run_external_controller_server': 'run a FastAPI server to externally control the EAR agent framework via HTTP endpoints', 'execute_long_horizon_task': 'execute a long-horizon task by sending a task instruction to the agent via the execute_lh_task endpoint', 'stream_framework_status': 'stream the EAR framework status at 1Hz to monitor agent health and long-horizon task progress', 'stream_events': 'stream events of specified types from the event bus as an SSE feed to the client', 'publish_event': 'publish an event to the agent framework event bus via a POST request with type, source, data, and metadata'}
```

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/agent/framework/comms/log_handler.py

Prompts

```
['run a FastAPI server to externally control the EAR agent framework via HTTP endpoints', 'execute a long-horizon task by sending a task instruction to the agent via the execute_lh_task endpoint', 'stream the EAR framework status at 1Hz to monitor agent health and long-horizon task progress', 'stream events of specified types from the event bus as an SSE feed to the client', 'publish an event to the agent framework event bus via a POST request with type, source, data, and metadata', 'create an EventBusLogHandler instance that publishes log messages to an event bus with a configurable minimum log level', 'set the asyncio event loop on an EventBusLogHandler so it can publish log events asynchronously', 'emit a log record as a SYSTEM_LOG event to the event bus with level, message, module, function name, and line number', 'configure the minimum logging level for an EventBusLogHandler to filter which messages get published to the event bus', 'handle errors during log emission by delegating to the standard logging handler error mechanism']
```

Usage

```
{'create_event_bus_log_handler': 'create an EventBusLogHandler instance that publishes log messages to an event bus with a configurable minimum log level', 'set_loop_on_handler': 'set the asyncio event loop on an EventBusLogHandler so it can publish log events asynchronously', 'emit_log_record': 'emit a log record as a SYSTEM_LOG event to the event bus with level, message, module, function name, and line number', 'configure_min_log_level': 'configure the minimum logging level for an EventBusLogHandler to filter which messages get published to the event bus', 'handle_emit_errors': 'handle errors during log emission by delegating to the standard logging handler error mechanism'}
```

