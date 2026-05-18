# Agent Python Tools

- repo: facebookresearch/meta-agents-research-environments
- repo_uri: https://github.com/facebookresearch/meta-agents-research-environments

## File: facebookresearch_meta-agents-research-environments/gaia2-cli/containers/hermes/gaia2_adapter.py

Prompts

```
['send a user message to the Hermes worker via the Unix socket bridge', 'check if the Hermes worker is connected and ready to receive messages', 'get health information including backend type, model, and active run ID', 'start the Unix socket server and wait for the Hermes worker to connect', 'buffer a worker response and emit a turn boundary event when the state is final or error', 'test the on_backend_response function to verify final state responses buffer and emit turn boundaries', 'test the on_backend_response function to verify error state responses write turn boundary events', 'test the backend_connect and send_message functions to verify Unix socket worker communication', 'test the send_message function to verify that a second message interrupts an active run', 'test the is_connected function to verify worker connection status after backend_connect', 'test the hermes worker trace logging by running pytest on test_hermes_worker.py with verbose output', 'install trace logging on a FakeAgent instance to record LLM call requests and responses to a JSONL trace file', 'resolve the base URL for an API provider like openai by checking the BASE_URL environment variable', 'normalize a chat completions request by adding reasoning_effort or translating extra_body reasoning fields', "patch an agent's API call method to automatically inject reasoning_effort into every request", 'patch an agent class to normalize whitespace in tool call IDs, call IDs, and response item IDs', 'disable streaming on a Hermes agent by redirecting streaming calls to the non-streaming API path']
```

Usage

```
{'send_message_to_hermes_worker': 'send a user message to the Hermes worker via the Unix socket bridge', 'check_hermes_worker_connection': 'check if the Hermes worker is connected and ready to receive messages', 'get_adapter_health_info': 'get health information including backend type, model, and active run ID', 'connect_hermes_worker_backend': 'start the Unix socket server and wait for the Hermes worker to connect', 'buffer_worker_response': 'buffer a worker response and emit a turn boundary event when the state is final or error'}
```

## File: facebookresearch_meta-agents-research-environments/gaia2-cli/containers/hermes/test_gaia2_adapter.py

Prompts

```
['send a user message to the Hermes worker via the Unix socket bridge', 'check if the Hermes worker is connected and ready to receive messages', 'get health information including backend type, model, and active run ID', 'start the Unix socket server and wait for the Hermes worker to connect', 'buffer a worker response and emit a turn boundary event when the state is final or error', 'test the on_backend_response function to verify final state responses buffer and emit turn boundaries', 'test the on_backend_response function to verify error state responses write turn boundary events', 'test the backend_connect and send_message functions to verify Unix socket worker communication', 'test the send_message function to verify that a second message interrupts an active run', 'test the is_connected function to verify worker connection status after backend_connect', 'test the hermes worker trace logging by running pytest on test_hermes_worker.py with verbose output', 'install trace logging on a FakeAgent instance to record LLM call requests and responses to a JSONL trace file', 'resolve the base URL for an API provider like openai by checking the BASE_URL environment variable', 'normalize a chat completions request by adding reasoning_effort or translating extra_body reasoning fields', "patch an agent's API call method to automatically inject reasoning_effort into every request", 'patch an agent class to normalize whitespace in tool call IDs, call IDs, and response item IDs', 'disable streaming on a Hermes agent by redirecting streaming calls to the non-streaming API path']
```

Usage

```
{'test_backend_response_final': 'test the on_backend_response function to verify final state responses buffer and emit turn boundaries', 'test_backend_response_error': 'test the on_backend_response function to verify error state responses write turn boundary events', 'test_worker_bridge_connect_and_send': 'test the backend_connect and send_message functions to verify Unix socket worker communication', 'test_worker_bridge_interrupt': 'test the send_message function to verify that a second message interrupts an active run', 'test_adapter_is_connected': 'test the is_connected function to verify worker connection status after backend_connect'}
```

## File: facebookresearch_meta-agents-research-environments/gaia2-cli/containers/hermes/test_hermes_worker.py

Prompts

```
['send a user message to the Hermes worker via the Unix socket bridge', 'check if the Hermes worker is connected and ready to receive messages', 'get health information including backend type, model, and active run ID', 'start the Unix socket server and wait for the Hermes worker to connect', 'buffer a worker response and emit a turn boundary event when the state is final or error', 'test the on_backend_response function to verify final state responses buffer and emit turn boundaries', 'test the on_backend_response function to verify error state responses write turn boundary events', 'test the backend_connect and send_message functions to verify Unix socket worker communication', 'test the send_message function to verify that a second message interrupts an active run', 'test the is_connected function to verify worker connection status after backend_connect', 'test the hermes worker trace logging by running pytest on test_hermes_worker.py with verbose output', 'install trace logging on a FakeAgent instance to record LLM call requests and responses to a JSONL trace file', 'resolve the base URL for an API provider like openai by checking the BASE_URL environment variable', 'normalize a chat completions request by adding reasoning_effort or translating extra_body reasoning fields', "patch an agent's API call method to automatically inject reasoning_effort into every request", 'patch an agent class to normalize whitespace in tool call IDs, call IDs, and response item IDs', 'disable streaming on a Hermes agent by redirecting streaming calls to the non-streaming API path']
```

Usage

```
{'test_hermes_trace_logging': 'test the hermes worker trace logging by running pytest on test_hermes_worker.py with verbose output', 'install_trace_logging': 'install trace logging on a FakeAgent instance to record LLM call requests and responses to a JSONL trace file', 'resolve_base_url': 'resolve the base URL for an API provider like openai by checking the BASE_URL environment variable', 'normalize_chat_reasoning_request': 'normalize a chat completions request by adding reasoning_effort or translating extra_body reasoning fields', 'patch_chat_reasoning_effort': "patch an agent's API call method to automatically inject reasoning_effort into every request", 'patch_hermes_tool_call_ids': 'patch an agent class to normalize whitespace in tool call IDs, call IDs, and response item IDs', 'disable_hermes_streaming_for_gaia2': 'disable streaming on a Hermes agent by redirecting streaming calls to the non-streaming API path'}
```

