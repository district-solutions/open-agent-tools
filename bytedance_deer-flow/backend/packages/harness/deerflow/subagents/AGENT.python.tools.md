# Agent Python Tools

- repo: bytedance/deer-flow
- repo_uri: https://github.com/bytedance/deer-flow

## File: bytedance_deer-flow/backend/packages/harness/deerflow/subagents/executor.py

Prompts

```
['create a SubagentExecutor with config, tools, and optional sandbox state for running AI subagent tasks', 'run a subagent task synchronously via execute() and return the SubagentResult with status and output', 'start a subagent task asynchronously via execute_async() and return the task ID for later polling', 'cancel a running background subagent task by task ID, signaling cooperative cancellation', 'filter a list of BaseTools using allowed and disallowed name lists for a subagent config', 'get the configuration for a named subagent with config.yaml overrides applied', 'list all available subagent configurations with config.yaml overrides applied', 'get all registered subagent names from the built-in registry', 'get subagent names filtered by sandbox security settings', 'review the subagent registry module and its configuration override logic']
```

Usage

```
{'create_subagent_executor': 'create a SubagentExecutor with config, tools, and optional sandbox state for running AI subagent tasks', 'run_subagent_task_sync': 'run a subagent task synchronously via execute() and return the SubagentResult with status and output', 'run_subagent_task_async': 'start a subagent task asynchronously via execute_async() and return the task ID for later polling', 'cancel_background_task': 'cancel a running background subagent task by task ID, signaling cooperative cancellation', 'filter_tools_for_subagent': 'filter a list of BaseTools using allowed and disallowed name lists for a subagent config'}
```

## File: bytedance_deer-flow/backend/packages/harness/deerflow/subagents/registry.py

Prompts

```
['create a SubagentExecutor with config, tools, and optional sandbox state for running AI subagent tasks', 'run a subagent task synchronously via execute() and return the SubagentResult with status and output', 'start a subagent task asynchronously via execute_async() and return the task ID for later polling', 'cancel a running background subagent task by task ID, signaling cooperative cancellation', 'filter a list of BaseTools using allowed and disallowed name lists for a subagent config', 'get the configuration for a named subagent with config.yaml overrides applied', 'list all available subagent configurations with config.yaml overrides applied', 'get all registered subagent names from the built-in registry', 'get subagent names filtered by sandbox security settings', 'review the subagent registry module and its configuration override logic']
```

Usage

```
{'get_subagent_config': 'get the configuration for a named subagent with config.yaml overrides applied', 'list_subagents': 'list all available subagent configurations with config.yaml overrides applied', 'get_subagent_names': 'get all registered subagent names from the built-in registry', 'get_available_subagent_names': 'get subagent names filtered by sandbox security settings', 'review_registry': 'review the subagent registry module and its configuration override logic'}
```

