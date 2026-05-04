# Agent Python Tools

- repo: google-deepmind/actionengine
- repo_uri: https://github.com/google-deepmind/actionengine

## File: google-deepmind_actionengine/py_tests/test_action_basics.py

Prompts

```
['create an ActionSchema with name, inputs, outputs, and description for an echo action', 'run an async echo action that reads input chunks and writes them to output', 'build an ActionRegistry and register an echo action with its schema and handler', 'test an echo action by sending input, consuming output, and asserting the result matches', 'run an action in the background using run_in_background and wait for completion', 'test that buffer_wire_messages context manager coalesces multiple sends into a single WireMessage', 'test that force_flush sends buffered messages mid-context before the buffer closes', 'test that half_close inside a buffering context flushes all buffered messages at once', 'test setting and getting headers on WireMessage objects including string and binary values', 'create a WebRTC server with a custom connection handler and configurable port']
```

Usage

```
{'create_action_schema': 'create an ActionSchema with name, inputs, outputs, and description for an echo action', 'run_echo_action': 'run an async echo action that reads input chunks and writes them to output', 'make_action_registry': 'build an ActionRegistry and register an echo action with its schema and handler', 'test_action_runs': 'test an echo action by sending input, consuming output, and asserting the result matches', 'run_action_in_background': 'run an action in the background using run_in_background and wait for completion'}
```

## File: google-deepmind_actionengine/py_tests/test_wire_message_buffering_behaviour.py

Prompts

```
['create an ActionSchema with name, inputs, outputs, and description for an echo action', 'run an async echo action that reads input chunks and writes them to output', 'build an ActionRegistry and register an echo action with its schema and handler', 'test an echo action by sending input, consuming output, and asserting the result matches', 'run an action in the background using run_in_background and wait for completion', 'test that buffer_wire_messages context manager coalesces multiple sends into a single WireMessage', 'test that force_flush sends buffered messages mid-context before the buffer closes', 'test that half_close inside a buffering context flushes all buffered messages at once', 'test setting and getting headers on WireMessage objects including string and binary values', 'create a WebRTC server with a custom connection handler and configurable port']
```

Usage

```
{'test_buffer_wire_messages': 'test that buffer_wire_messages context manager coalesces multiple sends into a single WireMessage', 'test_force_flush_buffered_messages': 'test that force_flush sends buffered messages mid-context before the buffer closes', 'test_half_close_with_buffering': 'test that half_close inside a buffering context flushes all buffered messages at once', 'test_wire_message_headers': 'test setting and getting headers on WireMessage objects including string and binary values', 'create_webrtc_server_with_handler': 'create a WebRTC server with a custom connection handler and configurable port'}
```

