# Agent Python Tools

- repo: bytedance/deer-flow
- repo_uri: https://github.com/bytedance/deer-flow

## File: bytedance_deer-flow/backend/packages/harness/deerflow/runtime/runs/manager.py

Prompts

```
['create a RunManager instance to manage async runs with thread-based isolation and locking', 'create a new pending run record with thread_id, assistant_id, and multitask_strategy for async task execution', 'cancel an in-flight run by run_id, triggering abort event and task cancellation with interrupt or rollback action', 'check if a thread already has pending or running runs before creating a new one with conflict detection', 'list all runs for a given thread_id ordered newest first with thread-scoped filtering']
```

Usage

```
{'create_run_manager': 'create a RunManager instance to manage async runs with thread-based isolation and locking', 'create_run_record': 'create a new pending run record with thread_id, assistant_id, and multitask_strategy for async task execution', 'cancel_run': 'cancel an in-flight run by run_id, triggering abort event and task cancellation with interrupt or rollback action', 'check_inflight_runs': 'check if a thread already has pending or running runs before creating a new one with conflict detection', 'list_thread_runs': 'list all runs for a given thread_id ordered newest first with thread-scoped filtering'}
```

