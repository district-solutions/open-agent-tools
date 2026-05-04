# Agent Python Tools

- repo: google-deepmind/concordia
- repo_uri: https://github.com/google-deepmind/concordia

## File: google-deepmind_concordia/concordia/agents/entity_agent.py

Prompts

```
['create an EntityAgent with an acting component and optional context components', 'run the act method on an EntityAgent to produce an action attempt through its lifecycle', 'run the observe method on an EntityAgent to process an observation through its lifecycle', 'get the serialized state dictionary of an EntityAgent including all component states', 'set the state of an EntityAgent by restoring act and context component states', 'create an EntityAgentWithLogging instance with an act component and optional context components and measurements', 'get the latest log datum from all available measurement channels as a dictionary', 'retrieve all measurement channels and their full log history from the agent', 'register a per-thread capture key mapping thread ID to entity name for async log isolation', 'remove the per-thread capture key for a given thread ID when the entity loop exits']
```

Usage

```
{'create_entity_agent': 'create an EntityAgent with an acting component and optional context components', 'run_entity_agent_act': 'run the act method on an EntityAgent to produce an action attempt through its lifecycle', 'run_entity_agent_observe': 'run the observe method on an EntityAgent to process an observation through its lifecycle', 'get_entity_agent_state': 'get the serialized state dictionary of an EntityAgent including all component states', 'set_entity_agent_state': 'set the state of an EntityAgent by restoring act and context component states'}
```

## File: google-deepmind_concordia/concordia/agents/entity_agent_with_logging.py

Prompts

```
['create an EntityAgent with an acting component and optional context components', 'run the act method on an EntityAgent to produce an action attempt through its lifecycle', 'run the observe method on an EntityAgent to process an observation through its lifecycle', 'get the serialized state dictionary of an EntityAgent including all component states', 'set the state of an EntityAgent by restoring act and context component states', 'create an EntityAgentWithLogging instance with an act component and optional context components and measurements', 'get the latest log datum from all available measurement channels as a dictionary', 'retrieve all measurement channels and their full log history from the agent', 'register a per-thread capture key mapping thread ID to entity name for async log isolation', 'remove the per-thread capture key for a given thread ID when the entity loop exits']
```

Usage

```
{'create_entity_agent_with_logging': 'create an EntityAgentWithLogging instance with an act component and optional context components and measurements', 'get_last_log': 'get the latest log datum from all available measurement channels as a dictionary', 'get_all_logs': 'retrieve all measurement channels and their full log history from the agent', 'set_capture_key_for_thread': 'register a per-thread capture key mapping thread ID to entity name for async log isolation', 'clear_capture_key_for_thread': 'remove the per-thread capture key for a given thread ID when the entity loop exits'}
```

