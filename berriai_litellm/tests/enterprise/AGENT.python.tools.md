# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/tests/enterprise/conftest.py

Prompts

```
['create a pytest session-scoped fixture that provides an asyncio event loop for enterprise tests', 'create a pytest autouse fixture that reloads litellm and flushes the LLM client cache before each test', 'reload the litellm proxy server module during test setup to prevent callback chaining between tests', 'flush the in-memory LLM clients cache before each test function runs', 'reorder pytest collection so custom_logger tests run before other enterprise tests']
```

Usage

```
{'setup_event_loop_fixture': 'create a pytest session-scoped fixture that provides an asyncio event loop for enterprise tests', 'setup_and_teardown_fixture': 'create a pytest autouse fixture that reloads litellm and flushes the LLM client cache before each test', 'reload_litellm_proxy_server': 'reload the litellm proxy server module during test setup to prevent callback chaining between tests', 'flush_llm_clients_cache': 'flush the in-memory LLM clients cache before each test function runs', 'reorder_pytest_collection': 'reorder pytest collection so custom_logger tests run before other enterprise tests'}
```

