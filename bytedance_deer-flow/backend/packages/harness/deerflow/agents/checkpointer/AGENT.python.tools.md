# Agent Python Tools

- repo: bytedance/deer-flow
- repo_uri: https://github.com/bytedance/deer-flow

## File: bytedance_deer-flow/backend/packages/harness/deerflow/agents/checkpointer/provider.py

Prompts

```
['build a sync checkpointer singleton that persists agent state using SQLite or PostgreSQL backend', 'create a sync context manager that yields a checkpointer with deterministic cleanup on exit', 'reset the global sync checkpointer singleton, closing backend connections and clearing the cached instance', 'test the sync checkpointer factory with memory, SQLite, and PostgreSQL backend configurations', 'run a LangGraph graph invocation with a configured checkpointer for thread state persistence']
```

Usage

```
{'build_checkpointer_singleton': 'build a sync checkpointer singleton that persists agent state using SQLite or PostgreSQL backend', 'create_checkpointer_context': 'create a sync context manager that yields a checkpointer with deterministic cleanup on exit', 'reset_checkpointer_singleton': 'reset the global sync checkpointer singleton, closing backend connections and clearing the cached instance', 'test_checkpointer_backend': 'test the sync checkpointer factory with memory, SQLite, and PostgreSQL backend configurations', 'run_checkpointer_with_graph': 'run a LangGraph graph invocation with a configured checkpointer for thread state persistence'}
```

