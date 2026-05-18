# Agent Python Tools

- repo: facebookresearch/meta-agents-research-environments
- repo_uri: https://github.com/facebookresearch/meta-agents-research-environments

## File: facebookresearch_meta-agents-research-environments/gaia2-cli/cli/gaia2_cli/app_registry.py

Prompts

```
['resolve scenario tools from a JSON scenario file to get agent-visible CLI commands and tools to remove', 'get the human-readable description for a Gaia2 app by its canonical name or alias from the registry', 'look up the real CLI binary name for a given Gaia2 app canonical name or alias', 'look up notification formatter lambdas for a given app to format environment event notifications', 'look up the state file name constant for a given Gaia2 app name from the registry', 'load app state from JSON with file locking then save changes atomically', 'log a successful CLI action with args and return value to events.jsonl', 'convert dataclasses, enums, and nested structures into JSON-safe Python dicts', 'resolve a cloud-drive path to a real filesystem path inside the Gaia2 sandbox', 'build a machine-readable schema list from a Click command group for tool discovery']
```

Usage

```
{'resolve_scenario_tools': 'resolve scenario tools from a JSON scenario file to get agent-visible CLI commands and tools to remove', 'get_description_for_app': 'get the human-readable description for a Gaia2 app by its canonical name or alias from the registry', 'lookup_app_to_cli': 'look up the real CLI binary name for a given Gaia2 app canonical name or alias', 'lookup_notification_formatters': 'look up notification formatter lambdas for a given app to format environment event notifications', 'lookup_app_state_name': 'look up the state file name constant for a given Gaia2 app name from the registry'}
```

## File: facebookresearch_meta-agents-research-environments/gaia2-cli/cli/gaia2_cli/shared.py

Prompts

```
['resolve scenario tools from a JSON scenario file to get agent-visible CLI commands and tools to remove', 'get the human-readable description for a Gaia2 app by its canonical name or alias from the registry', 'look up the real CLI binary name for a given Gaia2 app canonical name or alias', 'look up notification formatter lambdas for a given app to format environment event notifications', 'look up the state file name constant for a given Gaia2 app name from the registry', 'load app state from JSON with file locking then save changes atomically', 'log a successful CLI action with args and return value to events.jsonl', 'convert dataclasses, enums, and nested structures into JSON-safe Python dicts', 'resolve a cloud-drive path to a real filesystem path inside the Gaia2 sandbox', 'build a machine-readable schema list from a Click command group for tool discovery']
```

Usage

```
{'load_and_save_app_state': 'load app state from JSON with file locking then save changes atomically', 'log_action_to_events': 'log a successful CLI action with args and return value to events.jsonl', 'make_serializable_data': 'convert dataclasses, enums, and nested structures into JSON-safe Python dicts', 'resolve_sandbox_path': 'resolve a cloud-drive path to a real filesystem path inside the Gaia2 sandbox', 'build_click_schema': 'build a machine-readable schema list from a Click command group for tool discovery'}
```

