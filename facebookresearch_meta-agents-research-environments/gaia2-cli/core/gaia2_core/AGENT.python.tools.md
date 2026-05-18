# Agent Python Tools

- repo: facebookresearch/meta-agents-research-environments
- repo_uri: https://github.com/facebookresearch/meta-agents-research-environments

## File: facebookresearch_meta-agents-research-environments/gaia2-cli/core/gaia2_core/loader.py

Prompts

```
['build a python module that loads a Gaia2 scenario JSON file and parses events, apps, and metadata using ScenarioLoader', 'create a function that converts Gaia2 JSON args list with name, value, and value_type into a flat dictionary', 'extract oracle events, causal graphs, tasks, and user details per turn from a parsed Gaia2 scenario for the judge', 'extract user first name, last name, and address from the contacts app initial state in a Gaia2 scenario JSON', 'perform a BFS-based topological sort on a directed graph mapping event IDs to their parent dependency IDs', 'generate an HTML trace viewer page from a single Gaia2 ExportedTrace JSON file', 'generate HTML trace viewer pages for all Gaia2 trace JSON files in a directory', 'start an HTTP server to serve Gaia2 trace viewer pages with live regeneration', 'load and parse a Gaia2 ExportedTrace JSON file with deserialized world logs', 'generate an index HTML page summarizing multiple Gaia2 traces with pass/fail stats', 'resolve double-brace placeholders in args dict using completed events return values', 'create an EventAction model with app_name, class_name, function_name, args, and operation_type fields', 'create a CompletedEvent model with event_id, event_type, event_time, action, and return_value', 'create an OracleEvent model with event_id, event_type, action, args, resolved_args, and return_value', 'create a JudgmentResult model with success boolean, agent to oracle event ID mapping, and failure_reason']
```

Usage

```
{'build_scenario_loader': 'build a python module that loads a Gaia2 scenario JSON file and parses events, apps, and metadata using ScenarioLoader', 'parse_args_gaia2': 'create a function that converts Gaia2 JSON args list with name, value, and value_type into a flat dictionary', 'extract_oracle_data': 'extract oracle events, causal graphs, tasks, and user details per turn from a parsed Gaia2 scenario for the judge', 'extract_user_details': 'extract user first name, last name, and address from the contacts app initial state in a Gaia2 scenario JSON', 'topological_sort_events': 'perform a BFS-based topological sort on a directed graph mapping event IDs to their parent dependency IDs'}
```

## File: facebookresearch_meta-agents-research-environments/gaia2-cli/core/gaia2_core/trace_viewer.py

Prompts

```
['build a python module that loads a Gaia2 scenario JSON file and parses events, apps, and metadata using ScenarioLoader', 'create a function that converts Gaia2 JSON args list with name, value, and value_type into a flat dictionary', 'extract oracle events, causal graphs, tasks, and user details per turn from a parsed Gaia2 scenario for the judge', 'extract user first name, last name, and address from the contacts app initial state in a Gaia2 scenario JSON', 'perform a BFS-based topological sort on a directed graph mapping event IDs to their parent dependency IDs', 'generate an HTML trace viewer page from a single Gaia2 ExportedTrace JSON file', 'generate HTML trace viewer pages for all Gaia2 trace JSON files in a directory', 'start an HTTP server to serve Gaia2 trace viewer pages with live regeneration', 'load and parse a Gaia2 ExportedTrace JSON file with deserialized world logs', 'generate an index HTML page summarizing multiple Gaia2 traces with pass/fail stats', 'resolve double-brace placeholders in args dict using completed events return values', 'create an EventAction model with app_name, class_name, function_name, args, and operation_type fields', 'create a CompletedEvent model with event_id, event_type, event_time, action, and return_value', 'create an OracleEvent model with event_id, event_type, action, args, resolved_args, and return_value', 'create a JudgmentResult model with success boolean, agent to oracle event ID mapping, and failure_reason']
```

Usage

```
{'view_single_trace': 'generate an HTML trace viewer page from a single Gaia2 ExportedTrace JSON file', 'view_trace_directory': 'generate HTML trace viewer pages for all Gaia2 trace JSON files in a directory', 'serve_traces': 'start an HTTP server to serve Gaia2 trace viewer pages with live regeneration', 'load_trace_json': 'load and parse a Gaia2 ExportedTrace JSON file with deserialized world logs', 'generate_index_page': 'generate an index HTML page summarizing multiple Gaia2 traces with pass/fail stats'}
```

## File: facebookresearch_meta-agents-research-environments/gaia2-cli/core/gaia2_core/types.py

Prompts

```
['build a python module that loads a Gaia2 scenario JSON file and parses events, apps, and metadata using ScenarioLoader', 'create a function that converts Gaia2 JSON args list with name, value, and value_type into a flat dictionary', 'extract oracle events, causal graphs, tasks, and user details per turn from a parsed Gaia2 scenario for the judge', 'extract user first name, last name, and address from the contacts app initial state in a Gaia2 scenario JSON', 'perform a BFS-based topological sort on a directed graph mapping event IDs to their parent dependency IDs', 'generate an HTML trace viewer page from a single Gaia2 ExportedTrace JSON file', 'generate HTML trace viewer pages for all Gaia2 trace JSON files in a directory', 'start an HTTP server to serve Gaia2 trace viewer pages with live regeneration', 'load and parse a Gaia2 ExportedTrace JSON file with deserialized world logs', 'generate an index HTML page summarizing multiple Gaia2 traces with pass/fail stats', 'resolve double-brace placeholders in args dict using completed events return values', 'create an EventAction model with app_name, class_name, function_name, args, and operation_type fields', 'create a CompletedEvent model with event_id, event_type, event_time, action, and return_value', 'create an OracleEvent model with event_id, event_type, action, args, resolved_args, and return_value', 'create a JudgmentResult model with success boolean, agent to oracle event ID mapping, and failure_reason']
```

Usage

```
{'resolve_placeholders': 'resolve double-brace placeholders in args dict using completed events return values', 'create_event_action': 'create an EventAction model with app_name, class_name, function_name, args, and operation_type fields', 'create_completed_event': 'create a CompletedEvent model with event_id, event_type, event_time, action, and return_value', 'create_oracle_event': 'create an OracleEvent model with event_id, event_type, action, args, resolved_args, and return_value', 'create_judgment_result': 'create a JudgmentResult model with success boolean, agent to oracle event ID mapping, and failure_reason'}
```

