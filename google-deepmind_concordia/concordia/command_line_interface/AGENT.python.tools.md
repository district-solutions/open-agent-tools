# Agent Python Tools

- repo: google-deepmind/concordia
- repo_uri: https://github.com/google-deepmind/concordia

## File: google-deepmind_concordia/concordia/command_line_interface/concordia_log.py

Prompts

```
['run concordia-log overview on a simulation log JSON file to see steps, entities, and entry types', "run concordia-log actions on a simulation log to show an entity's actions across all steps", 'run concordia-log context to show full action context including observations and prompt for an entity at a step', 'run concordia-log search on a simulation log to find entries matching a keyword query', 'run concordia-log dump to output inflated de-duplicated JSON for piping to jq or grep', 'run concordia log overview to get total steps and entities from a simulation log file', 'run concordia log entities to list all entity names in a simulation log file', 'run concordia log actions to retrieve all actions for a specific entity across simulation steps', 'run concordia log search to find log entries matching a keyword across all entities and steps', 'run concordia log dump to export raw log entries filtered by step or entity name']
```

Usage

```
{'run_concordia_log_overview': 'run concordia-log overview on a simulation log JSON file to see steps, entities, and entry types', 'run_concordia_log_actions': "run concordia-log actions on a simulation log to show an entity's actions across all steps", 'run_concordia_log_context': 'run concordia-log context to show full action context including observations and prompt for an entity at a step', 'run_concordia_log_search': 'run concordia-log search on a simulation log to find entries matching a keyword query', 'run_concordia_log_dump': 'run concordia-log dump to output inflated de-duplicated JSON for piping to jq or grep'}
```

## File: google-deepmind_concordia/concordia/command_line_interface/concordia_log_test.py

Prompts

```
['run concordia-log overview on a simulation log JSON file to see steps, entities, and entry types', "run concordia-log actions on a simulation log to show an entity's actions across all steps", 'run concordia-log context to show full action context including observations and prompt for an entity at a step', 'run concordia-log search on a simulation log to find entries matching a keyword query', 'run concordia-log dump to output inflated de-duplicated JSON for piping to jq or grep', 'run concordia log overview to get total steps and entities from a simulation log file', 'run concordia log entities to list all entity names in a simulation log file', 'run concordia log actions to retrieve all actions for a specific entity across simulation steps', 'run concordia log search to find log entries matching a keyword across all entities and steps', 'run concordia log dump to export raw log entries filtered by step or entity name']
```

Usage

```
{'overview_simulation_log': 'run concordia log overview to get total steps and entities from a simulation log file', 'list_entities': 'run concordia log entities to list all entity names in a simulation log file', 'get_entity_actions': 'run concordia log actions to retrieve all actions for a specific entity across simulation steps', 'search_log_entries': 'run concordia log search to find log entries matching a keyword across all entities and steps', 'dump_filtered_entries': 'run concordia log dump to export raw log entries filtered by step or entity name'}
```

