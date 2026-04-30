# Agent Python Tools

- repo: bytedance/deer-flow
- repo_uri: https://github.com/bytedance/deer-flow

## File: bytedance_deer-flow/backend/scripts/migrate_user_isolation.py

Prompts

```
['run the migration script with --dry-run to preview thread and memory moves without changes', 'run the migration script to move legacy thread dirs and memory into per-user layout', 'move legacy thread directories into per-user layout using a thread owner map from the database', 'move legacy global memory.json file into a per-user memory layout for a specified user', 'query the threads_meta table to build a thread_id to user_id ownership mapping from the SQLite database']
```

Usage

```
{'run_migration_dry': 'run the migration script with --dry-run to preview thread and memory moves without changes', 'run_migration_full': 'run the migration script to move legacy thread dirs and memory into per-user layout', 'migrate_thread_dirs': 'move legacy thread directories into per-user layout using a thread owner map from the database', 'migrate_memory': 'move legacy global memory.json file into a per-user memory layout for a specified user', 'build_owner_map': 'query the threads_meta table to build a thread_id to user_id ownership mapping from the SQLite database'}
```

