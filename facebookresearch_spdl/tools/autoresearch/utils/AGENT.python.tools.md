# Agent Python Tools

- repo: facebookresearch/spdl
- repo_uri: https://github.com/facebookresearch/spdl

## File: facebookresearch_spdl/tools/autoresearch/utils/log.py

Prompts

```
['setup logging to write DEBUG logs to a file and INFO logs to stderr', 'setup logging with a file handler that appends to workdir/logs/autoresearch.log', 'setup logging with a stream handler that outputs INFO level messages to stderr', 'setup logging once using the idempotent guard that skips reconfiguration on repeated calls', 'setup logging that automatically creates the logs directory under the given workdir path', 'run work specs with bounded async concurrency using AsyncWorkEngine and a custom adapter', 'create a WorkSpec with an id, priority, kind, and payload dictionary for scheduling', 'deserialize a WorkSpec from a dictionary using the from_dict class method', 'serialize a WorkSpec to a dictionary using the to_dict instance method', 'implement the WorkAdapter protocol with load, checkpoint, make_coro, and on_result methods', "read the experiment state from a workdir's state.json file and return a normalized dict", "write a normalized experiment state dict to a workdir's state.json file", "read the experiment config from a workdir's config.json file and return a normalized dict", 'append a row dict to the master_table.tsv file in the given workdir', 'normalize a config dict by setting default values for stopping criteria, platform, and agent', 'create a Claude or Codex supervisor agent instance by name using the factory function', 'resolve an available supervisor agent automatically by checking Claude and Codex in order', 'check if the Claude CLI command is available on the system path', 'build a Claude CLI command list with a system prompt and optional user request', 'build a Codex CLI command list with a combined system prompt and user request', 'create a FailureRecord with kind, phase, and message then serialize it to a dictionary', 'deserialize a dictionary back into a FailureRecord using the from_dict class method', 'create a HypothesisNode with node_id and name then serialize it to a dictionary', 'deserialize a dictionary back into a HypothesisNode using the from_dict class method', 'raise an AutoresearchError with a FailureRecord to signal an expected workflow failure']
```

Usage

```
{'setup_logging_configure': 'setup logging to write DEBUG logs to a file and INFO logs to stderr', 'setup_logging_file_handler': 'setup logging with a file handler that appends to workdir/logs/autoresearch.log', 'setup_logging_stream_handler': 'setup logging with a stream handler that outputs INFO level messages to stderr', 'setup_logging_idempotent': 'setup logging once using the idempotent guard that skips reconfiguration on repeated calls', 'setup_logging_log_dir': 'setup logging that automatically creates the logs directory under the given workdir path'}
```

## File: facebookresearch_spdl/tools/autoresearch/utils/runner.py

Prompts

```
['setup logging to write DEBUG logs to a file and INFO logs to stderr', 'setup logging with a file handler that appends to workdir/logs/autoresearch.log', 'setup logging with a stream handler that outputs INFO level messages to stderr', 'setup logging once using the idempotent guard that skips reconfiguration on repeated calls', 'setup logging that automatically creates the logs directory under the given workdir path', 'run work specs with bounded async concurrency using AsyncWorkEngine and a custom adapter', 'create a WorkSpec with an id, priority, kind, and payload dictionary for scheduling', 'deserialize a WorkSpec from a dictionary using the from_dict class method', 'serialize a WorkSpec to a dictionary using the to_dict instance method', 'implement the WorkAdapter protocol with load, checkpoint, make_coro, and on_result methods', "read the experiment state from a workdir's state.json file and return a normalized dict", "write a normalized experiment state dict to a workdir's state.json file", "read the experiment config from a workdir's config.json file and return a normalized dict", 'append a row dict to the master_table.tsv file in the given workdir', 'normalize a config dict by setting default values for stopping criteria, platform, and agent', 'create a Claude or Codex supervisor agent instance by name using the factory function', 'resolve an available supervisor agent automatically by checking Claude and Codex in order', 'check if the Claude CLI command is available on the system path', 'build a Claude CLI command list with a system prompt and optional user request', 'build a Codex CLI command list with a combined system prompt and user request', 'create a FailureRecord with kind, phase, and message then serialize it to a dictionary', 'deserialize a dictionary back into a FailureRecord using the from_dict class method', 'create a HypothesisNode with node_id and name then serialize it to a dictionary', 'deserialize a dictionary back into a HypothesisNode using the from_dict class method', 'raise an AutoresearchError with a FailureRecord to signal an expected workflow failure']
```

Usage

```
{'run_async_work_engine': 'run work specs with bounded async concurrency using AsyncWorkEngine and a custom adapter', 'create_work_spec': 'create a WorkSpec with an id, priority, kind, and payload dictionary for scheduling', 'deserialize_work_spec': 'deserialize a WorkSpec from a dictionary using the from_dict class method', 'serialize_work_spec': 'serialize a WorkSpec to a dictionary using the to_dict instance method', 'implement_work_adapter': 'implement the WorkAdapter protocol with load, checkpoint, make_coro, and on_result methods'}
```

## File: facebookresearch_spdl/tools/autoresearch/utils/state.py

Prompts

```
['setup logging to write DEBUG logs to a file and INFO logs to stderr', 'setup logging with a file handler that appends to workdir/logs/autoresearch.log', 'setup logging with a stream handler that outputs INFO level messages to stderr', 'setup logging once using the idempotent guard that skips reconfiguration on repeated calls', 'setup logging that automatically creates the logs directory under the given workdir path', 'run work specs with bounded async concurrency using AsyncWorkEngine and a custom adapter', 'create a WorkSpec with an id, priority, kind, and payload dictionary for scheduling', 'deserialize a WorkSpec from a dictionary using the from_dict class method', 'serialize a WorkSpec to a dictionary using the to_dict instance method', 'implement the WorkAdapter protocol with load, checkpoint, make_coro, and on_result methods', "read the experiment state from a workdir's state.json file and return a normalized dict", "write a normalized experiment state dict to a workdir's state.json file", "read the experiment config from a workdir's config.json file and return a normalized dict", 'append a row dict to the master_table.tsv file in the given workdir', 'normalize a config dict by setting default values for stopping criteria, platform, and agent', 'create a Claude or Codex supervisor agent instance by name using the factory function', 'resolve an available supervisor agent automatically by checking Claude and Codex in order', 'check if the Claude CLI command is available on the system path', 'build a Claude CLI command list with a system prompt and optional user request', 'build a Codex CLI command list with a combined system prompt and user request', 'create a FailureRecord with kind, phase, and message then serialize it to a dictionary', 'deserialize a dictionary back into a FailureRecord using the from_dict class method', 'create a HypothesisNode with node_id and name then serialize it to a dictionary', 'deserialize a dictionary back into a HypothesisNode using the from_dict class method', 'raise an AutoresearchError with a FailureRecord to signal an expected workflow failure']
```

Usage

```
{'read_state': "read the experiment state from a workdir's state.json file and return a normalized dict", 'write_state': "write a normalized experiment state dict to a workdir's state.json file", 'read_config': "read the experiment config from a workdir's config.json file and return a normalized dict", 'append_master_row': 'append a row dict to the master_table.tsv file in the given workdir', 'normalize_config': 'normalize a config dict by setting default values for stopping criteria, platform, and agent'}
```

## File: facebookresearch_spdl/tools/autoresearch/utils/supervisor.py

Prompts

```
['setup logging to write DEBUG logs to a file and INFO logs to stderr', 'setup logging with a file handler that appends to workdir/logs/autoresearch.log', 'setup logging with a stream handler that outputs INFO level messages to stderr', 'setup logging once using the idempotent guard that skips reconfiguration on repeated calls', 'setup logging that automatically creates the logs directory under the given workdir path', 'run work specs with bounded async concurrency using AsyncWorkEngine and a custom adapter', 'create a WorkSpec with an id, priority, kind, and payload dictionary for scheduling', 'deserialize a WorkSpec from a dictionary using the from_dict class method', 'serialize a WorkSpec to a dictionary using the to_dict instance method', 'implement the WorkAdapter protocol with load, checkpoint, make_coro, and on_result methods', "read the experiment state from a workdir's state.json file and return a normalized dict", "write a normalized experiment state dict to a workdir's state.json file", "read the experiment config from a workdir's config.json file and return a normalized dict", 'append a row dict to the master_table.tsv file in the given workdir', 'normalize a config dict by setting default values for stopping criteria, platform, and agent', 'create a Claude or Codex supervisor agent instance by name using the factory function', 'resolve an available supervisor agent automatically by checking Claude and Codex in order', 'check if the Claude CLI command is available on the system path', 'build a Claude CLI command list with a system prompt and optional user request', 'build a Codex CLI command list with a combined system prompt and user request', 'create a FailureRecord with kind, phase, and message then serialize it to a dictionary', 'deserialize a dictionary back into a FailureRecord using the from_dict class method', 'create a HypothesisNode with node_id and name then serialize it to a dictionary', 'deserialize a dictionary back into a HypothesisNode using the from_dict class method', 'raise an AutoresearchError with a FailureRecord to signal an expected workflow failure']
```

Usage

```
{'create_supervisor_agent': 'create a Claude or Codex supervisor agent instance by name using the factory function', 'resolve_supervisor_agent_auto': 'resolve an available supervisor agent automatically by checking Claude and Codex in order', 'check_claude_availability': 'check if the Claude CLI command is available on the system path', 'build_claude_command': 'build a Claude CLI command list with a system prompt and optional user request', 'build_codex_command': 'build a Codex CLI command list with a combined system prompt and user request'}
```

## File: facebookresearch_spdl/tools/autoresearch/utils/types.py

Prompts

```
['setup logging to write DEBUG logs to a file and INFO logs to stderr', 'setup logging with a file handler that appends to workdir/logs/autoresearch.log', 'setup logging with a stream handler that outputs INFO level messages to stderr', 'setup logging once using the idempotent guard that skips reconfiguration on repeated calls', 'setup logging that automatically creates the logs directory under the given workdir path', 'run work specs with bounded async concurrency using AsyncWorkEngine and a custom adapter', 'create a WorkSpec with an id, priority, kind, and payload dictionary for scheduling', 'deserialize a WorkSpec from a dictionary using the from_dict class method', 'serialize a WorkSpec to a dictionary using the to_dict instance method', 'implement the WorkAdapter protocol with load, checkpoint, make_coro, and on_result methods', "read the experiment state from a workdir's state.json file and return a normalized dict", "write a normalized experiment state dict to a workdir's state.json file", "read the experiment config from a workdir's config.json file and return a normalized dict", 'append a row dict to the master_table.tsv file in the given workdir', 'normalize a config dict by setting default values for stopping criteria, platform, and agent', 'create a Claude or Codex supervisor agent instance by name using the factory function', 'resolve an available supervisor agent automatically by checking Claude and Codex in order', 'check if the Claude CLI command is available on the system path', 'build a Claude CLI command list with a system prompt and optional user request', 'build a Codex CLI command list with a combined system prompt and user request', 'create a FailureRecord with kind, phase, and message then serialize it to a dictionary', 'deserialize a dictionary back into a FailureRecord using the from_dict class method', 'create a HypothesisNode with node_id and name then serialize it to a dictionary', 'deserialize a dictionary back into a HypothesisNode using the from_dict class method', 'raise an AutoresearchError with a FailureRecord to signal an expected workflow failure']
```

Usage

```
{'create_failure_record': 'create a FailureRecord with kind, phase, and message then serialize it to a dictionary', 'deserialize_failure_record': 'deserialize a dictionary back into a FailureRecord using the from_dict class method', 'create_hypothesis_node': 'create a HypothesisNode with node_id and name then serialize it to a dictionary', 'deserialize_hypothesis_node': 'deserialize a dictionary back into a HypothesisNode using the from_dict class method', 'raise_autoresearch_error': 'raise an AutoresearchError with a FailureRecord to signal an expected workflow failure'}
```

