# Agent Python Tools

- repo: facebookresearch/spdl
- repo_uri: https://github.com/facebookresearch/spdl

## File: facebookresearch_spdl/tools/autoresearch/utils/workflow/adapter.py

Prompts

```
['build an AutoresearchAdapter instance with workdir, config, state, and platform to orchestrate experiment workflows', 'run an experiment by calling make_coro on a WorkSpec and awaiting the resulting coroutine for a WorkResult', 'load initial or checkpointed WorkSpecs from the store and save scheduler state with checkpoint', 'analyze a completed experiment result and plan follow-up child experiments using on_result', 'resolve the correct parent HypothesisNode for a child experiment based on goto commit or baseline', 'create an _AutoresearchStore instance with a workdir path and state dictionary to manage workflow persistence', 'load queued and running work specs from engine/checkpoint.json to resume an interrupted autoresearch workflow', 'save the current scheduler state with queued specs, running specs, and status to checkpoint.json and monitoring views', 'update a WorkSpec with new node data and persist the changes to all engine monitoring files', 'write text to a file atomically using a temp file and rename to prevent partial writes']
```

Usage

```
{'build_autoresearch_adapter': 'build an AutoresearchAdapter instance with workdir, config, state, and platform to orchestrate experiment workflows', 'run_experiment_coroutine': 'run an experiment by calling make_coro on a WorkSpec and awaiting the resulting coroutine for a WorkResult', 'load_and_checkpoint_specs': 'load initial or checkpointed WorkSpecs from the store and save scheduler state with checkpoint', 'analyze_and_plan_followups': 'analyze a completed experiment result and plan follow-up child experiments using on_result', 'resolve_parent_node': 'resolve the correct parent HypothesisNode for a child experiment based on goto commit or baseline'}
```

## File: facebookresearch_spdl/tools/autoresearch/utils/workflow/store.py

Prompts

```
['build an AutoresearchAdapter instance with workdir, config, state, and platform to orchestrate experiment workflows', 'run an experiment by calling make_coro on a WorkSpec and awaiting the resulting coroutine for a WorkResult', 'load initial or checkpointed WorkSpecs from the store and save scheduler state with checkpoint', 'analyze a completed experiment result and plan follow-up child experiments using on_result', 'resolve the correct parent HypothesisNode for a child experiment based on goto commit or baseline', 'create an _AutoresearchStore instance with a workdir path and state dictionary to manage workflow persistence', 'load queued and running work specs from engine/checkpoint.json to resume an interrupted autoresearch workflow', 'save the current scheduler state with queued specs, running specs, and status to checkpoint.json and monitoring views', 'update a WorkSpec with new node data and persist the changes to all engine monitoring files', 'write text to a file atomically using a temp file and rename to prevent partial writes']
```

Usage

```
{'create_autoresearch_store': 'create an _AutoresearchStore instance with a workdir path and state dictionary to manage workflow persistence', 'load_checkpoint_specs': 'load queued and running work specs from engine/checkpoint.json to resume an interrupted autoresearch workflow', 'save_scheduler_state': 'save the current scheduler state with queued specs, running specs, and status to checkpoint.json and monitoring views', 'update_workspec_node': 'update a WorkSpec with new node data and persist the changes to all engine monitoring files', 'write_text_atomic': 'write text to a file atomically using a temp file and rename to prevent partial writes'}
```

