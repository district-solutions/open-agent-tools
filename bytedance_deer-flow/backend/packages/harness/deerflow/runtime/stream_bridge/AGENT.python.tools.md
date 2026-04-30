# Agent Python Tools

- repo: bytedance/deer-flow
- repo_uri: https://github.com/bytedance/deer-flow

## File: bytedance_deer-flow/backend/packages/harness/deerflow/runtime/stream_bridge/base.py

Prompts

```
['create a frozen dataclass StreamEvent with id, event name, and JSON-serialisable data payload', 'build an async method that publishes a single event to a run_id on a StreamBridge implementation', 'test the StreamBridge subscribe method that yields an async iterator of StreamEvents for a run_id', 'refactor the StreamBridge cleanup method to release resources for a run_id with an optional drain delay', 'summarize the StreamBridge close method that releases backend resources with a default no-op implementation']
```

Usage

```
{'create_stream_event': 'create a frozen dataclass StreamEvent with id, event name, and JSON-serialisable data payload', 'build_stream_bridge_publish': 'build an async method that publishes a single event to a run_id on a StreamBridge implementation', 'test_stream_bridge_subscribe': 'test the StreamBridge subscribe method that yields an async iterator of StreamEvents for a run_id', 'refactor_stream_bridge_cleanup': 'refactor the StreamBridge cleanup method to release resources for a run_id with an optional drain delay', 'summarize_stream_bridge_close': 'summarize the StreamBridge close method that releases backend resources with a default no-op implementation'}
```

