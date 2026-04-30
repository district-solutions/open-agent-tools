# Agent Python Tools

- repo: bytedance/deer-flow
- repo_uri: https://github.com/bytedance/deer-flow

## File: bytedance_deer-flow/backend/packages/harness/deerflow/runtime/store/_sqlite_utils.py

Prompts

```
['build a function that resolves SQLite connection strings, returning :memory: and file: URIs unchanged while resolving plain paths to absolute strings', 'create a function that creates parent directories for SQLite filesystem paths, skipping in-memory and file: URI databases', 'create a global sync Store singleton that persists across calls using get_store()', 'test the get_store singleton function for lazy initialization and caching behavior', 'refactor the get_store singleton to support configurable backend selection from environment variables', 'review the store_context context manager for deterministic cleanup in CLI scripts and tests', 'summarize the _sync_store_cm factory function that creates memory, sqlite, or postgres store backends']
```

Usage

```
{'build_resolve_sqlite_conn_str': 'build a function that resolves SQLite connection strings, returning :memory: and file: URIs unchanged while resolving plain paths to absolute strings', 'create_ensure_sqlite_parent_dir': 'create a function that creates parent directories for SQLite filesystem paths, skipping in-memory and file: URI databases'}
```

## File: bytedance_deer-flow/backend/packages/harness/deerflow/runtime/store/provider.py

Prompts

```
['build a function that resolves SQLite connection strings, returning :memory: and file: URIs unchanged while resolving plain paths to absolute strings', 'create a function that creates parent directories for SQLite filesystem paths, skipping in-memory and file: URI databases', 'create a global sync Store singleton that persists across calls using get_store()', 'test the get_store singleton function for lazy initialization and caching behavior', 'refactor the get_store singleton to support configurable backend selection from environment variables', 'review the store_context context manager for deterministic cleanup in CLI scripts and tests', 'summarize the _sync_store_cm factory function that creates memory, sqlite, or postgres store backends']
```

Usage

```
{'create_store_singleton': 'create a global sync Store singleton that persists across calls using get_store()', 'test_store_singleton': 'test the get_store singleton function for lazy initialization and caching behavior', 'refactor_store_singleton': 'refactor the get_store singleton to support configurable backend selection from environment variables', 'review_store_context': 'review the store_context context manager for deterministic cleanup in CLI scripts and tests', 'summarize_sync_store_factory': 'summarize the _sync_store_cm factory function that creates memory, sqlite, or postgres store backends'}
```

