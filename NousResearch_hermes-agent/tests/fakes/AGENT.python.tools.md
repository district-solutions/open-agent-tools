# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/tests/fakes/fake_ha_server.py

Prompts

```
['test the FakeHAServer class as an async context manager that mimics a Home Assistant server', "test pushing state_changed events into the fake server's WebSocket event queue", 'test GET /api/states returns a list of sample entity states with auth', 'test POST /api/services/{domain}/{service} records and simulates service calls', 'test POST /api/services/persistent_notification/create captures notifications']
```

Usage

```
{'test_fake_ha_server': 'test the FakeHAServer class as an async context manager that mimics a Home Assistant server', 'test_push_event': "test pushing state_changed events into the fake server's WebSocket event queue", 'test_get_entity_states': 'test GET /api/states returns a list of sample entity states with auth', 'test_call_service': 'test POST /api/services/{domain}/{service} records and simulates service calls', 'test_handle_notification': 'test POST /api/services/persistent_notification/create captures notifications'}
```

