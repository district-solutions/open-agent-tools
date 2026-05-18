# Agent Python Tools

- repo: facebookresearch/meta-agents-research-environments
- repo_uri: https://github.com/facebookresearch/meta-agents-research-environments

## File: facebookresearch_meta-agents-research-environments/are/simulation/tests/scenarios/scenario_imported_from_json/benchmark_scenario_utils_test.py

Prompts

```
['preprocess a benchmark scenario by adding SystemApp, setting duration, running oracle mode, and initializing turns with judge validation', 'check if a JSON event dictionary is an OracleEvent by inspecting its class_name field', 'create a PlaceholderMetadata object from a placeholder event and its parent OracleEvent with turn index mapping', 'detect whether the same tool is invoked by another agent event within the same turn of a scenario', 'extract all placeholder references from scenario events and return PlaceholderMetadata objects with a same-tool conflict flag', 'extract execution metadata including placeholders and placeholder conflict flags from a benchmark scenario', 'preprocess a benchmark scenario for non-oracle execution by adding dummy turn triggers and extracting execution metadata', 'import a JSON scenario string, preprocess it for non-oracle execution, and export the result back to a JSON string']
```

Usage

```
{'preprocess_scenario': 'preprocess a benchmark scenario by adding SystemApp, setting duration, running oracle mode, and initializing turns with judge validation', 'is_oracle_event': 'check if a JSON event dictionary is an OracleEvent by inspecting its class_name field', 'create_placeholder': 'create a PlaceholderMetadata object from a placeholder event and its parent OracleEvent with turn index mapping', 'flag_same_tool_used_in_same_turn': 'detect whether the same tool is invoked by another agent event within the same turn of a scenario', 'extract_placeholders': 'extract all placeholder references from scenario events and return PlaceholderMetadata objects with a same-tool conflict flag', 'extract_execution_metadata': 'extract execution metadata including placeholders and placeholder conflict flags from a benchmark scenario', 'preprocess_scenario_for_execution_without_oracle': 'preprocess a benchmark scenario for non-oracle execution by adding dummy turn triggers and extracting execution metadata', 'preprocess_scenario_str_for_execution_without_oracle': 'import a JSON scenario string, preprocess it for non-oracle execution, and export the result back to a JSON string'}
```

