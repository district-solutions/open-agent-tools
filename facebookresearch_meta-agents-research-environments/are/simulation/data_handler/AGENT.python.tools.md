# Agent Python Tools

- repo: facebookresearch/meta-agents-research-environments
- repo_uri: https://github.com/facebookresearch/meta-agents-research-environments

## File: facebookresearch_meta-agents-research-environments/are/simulation/data_handler/exporter.py

Prompts

```
['export simulation environment trace data to a JSON file in hf, lite, or both formats', 'export simulation environment trace data as a JSON string with optional model and agent metadata', 'export a lite JSON trace containing per-agent interaction histories and LLM usage statistics', 'build a conversation history from agent world logs excluding tool calls, rationale, and action types', 'extract LLM token usage and completion duration stats from a list of agent world logs', 'create a JsonScenarioImporter and call import_from_json to parse a JSON trace into a ScenarioImportedFromJson with completed events and agent logs', 'create a JsonScenarioImporter and call import_from_json_to_benchmark to parse a JSON trace into a BenchmarkScenarioImportedFromJson with HuggingFace app fetching', 'call the map_action static method to transform raw action data with app name mappings into a structured action dictionary', 'call the map_event static method to transform raw event JSON with metadata and action into a mapped event dictionary', 'call _fetch_apps_from_huggingface to retrieve missing apps for a scenario from a HuggingFace dataset using ExportedHuggingFaceMetadata', 'create an ExportedTrace with metadata, events, and apps for simulation data export', 'convert a PlaceholderMetadata instance to ExportedPlaceholderMetadata using the from_metadata class method', 'convert an ExecutionMetadata instance to ExportedExecutionMetadata using the from_metadata class method', 'build an ExportedTraceDefinitionMetadata with scenario_id, hints, and augmentation flags for trace definition', 'create an ExportedEvent with class_name, event_type, event_id, and optional action for simulation traces']
```

Usage

```
{'export_simulation_trace_to_json_file': 'export simulation environment trace data to a JSON file in hf, lite, or both formats', 'export_simulation_trace_to_json_string': 'export simulation environment trace data as a JSON string with optional model and agent metadata', 'export_lite_trace_with_llm_stats': 'export a lite JSON trace containing per-agent interaction histories and LLM usage statistics', 'build_history_from_agent_logs': 'build a conversation history from agent world logs excluding tool calls, rationale, and action types', 'extract_llm_usage_stats_from_logs': 'extract LLM token usage and completion duration stats from a list of agent world logs'}
```

## File: facebookresearch_meta-agents-research-environments/are/simulation/data_handler/importer.py

Prompts

```
['export simulation environment trace data to a JSON file in hf, lite, or both formats', 'export simulation environment trace data as a JSON string with optional model and agent metadata', 'export a lite JSON trace containing per-agent interaction histories and LLM usage statistics', 'build a conversation history from agent world logs excluding tool calls, rationale, and action types', 'extract LLM token usage and completion duration stats from a list of agent world logs', 'create a JsonScenarioImporter and call import_from_json to parse a JSON trace into a ScenarioImportedFromJson with completed events and agent logs', 'create a JsonScenarioImporter and call import_from_json_to_benchmark to parse a JSON trace into a BenchmarkScenarioImportedFromJson with HuggingFace app fetching', 'call the map_action static method to transform raw action data with app name mappings into a structured action dictionary', 'call the map_event static method to transform raw event JSON with metadata and action into a mapped event dictionary', 'call _fetch_apps_from_huggingface to retrieve missing apps for a scenario from a HuggingFace dataset using ExportedHuggingFaceMetadata', 'create an ExportedTrace with metadata, events, and apps for simulation data export', 'convert a PlaceholderMetadata instance to ExportedPlaceholderMetadata using the from_metadata class method', 'convert an ExecutionMetadata instance to ExportedExecutionMetadata using the from_metadata class method', 'build an ExportedTraceDefinitionMetadata with scenario_id, hints, and augmentation flags for trace definition', 'create an ExportedEvent with class_name, event_type, event_id, and optional action for simulation traces']
```

Usage

```
{'import_scenario_from_json': 'create a JsonScenarioImporter and call import_from_json to parse a JSON trace into a ScenarioImportedFromJson with completed events and agent logs', 'import_scenario_to_benchmark': 'create a JsonScenarioImporter and call import_from_json_to_benchmark to parse a JSON trace into a BenchmarkScenarioImportedFromJson with HuggingFace app fetching', 'map_action_static': 'call the map_action static method to transform raw action data with app name mappings into a structured action dictionary', 'map_event_static': 'call the map_event static method to transform raw event JSON with metadata and action into a mapped event dictionary', 'fetch_apps_from_huggingface': 'call _fetch_apps_from_huggingface to retrieve missing apps for a scenario from a HuggingFace dataset using ExportedHuggingFaceMetadata'}
```

## File: facebookresearch_meta-agents-research-environments/are/simulation/data_handler/models.py

Prompts

```
['export simulation environment trace data to a JSON file in hf, lite, or both formats', 'export simulation environment trace data as a JSON string with optional model and agent metadata', 'export a lite JSON trace containing per-agent interaction histories and LLM usage statistics', 'build a conversation history from agent world logs excluding tool calls, rationale, and action types', 'extract LLM token usage and completion duration stats from a list of agent world logs', 'create a JsonScenarioImporter and call import_from_json to parse a JSON trace into a ScenarioImportedFromJson with completed events and agent logs', 'create a JsonScenarioImporter and call import_from_json_to_benchmark to parse a JSON trace into a BenchmarkScenarioImportedFromJson with HuggingFace app fetching', 'call the map_action static method to transform raw action data with app name mappings into a structured action dictionary', 'call the map_event static method to transform raw event JSON with metadata and action into a mapped event dictionary', 'call _fetch_apps_from_huggingface to retrieve missing apps for a scenario from a HuggingFace dataset using ExportedHuggingFaceMetadata', 'create an ExportedTrace with metadata, events, and apps for simulation data export', 'convert a PlaceholderMetadata instance to ExportedPlaceholderMetadata using the from_metadata class method', 'convert an ExecutionMetadata instance to ExportedExecutionMetadata using the from_metadata class method', 'build an ExportedTraceDefinitionMetadata with scenario_id, hints, and augmentation flags for trace definition', 'create an ExportedEvent with class_name, event_type, event_id, and optional action for simulation traces']
```

Usage

```
{'create_exported_trace': 'create an ExportedTrace with metadata, events, and apps for simulation data export', 'convert_placeholder_metadata': 'convert a PlaceholderMetadata instance to ExportedPlaceholderMetadata using the from_metadata class method', 'convert_execution_metadata': 'convert an ExecutionMetadata instance to ExportedExecutionMetadata using the from_metadata class method', 'export_trace_definition_metadata': 'build an ExportedTraceDefinitionMetadata with scenario_id, hints, and augmentation flags for trace definition', 'create_exported_event': 'create an ExportedEvent with class_name, event_type, event_id, and optional action for simulation traces'}
```

