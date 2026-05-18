# Agent Python Tools

- repo: facebookresearch/meta-agents-research-environments
- repo_uri: https://github.com/facebookresearch/meta-agents-research-environments

## File: facebookresearch_meta-agents-research-environments/are/simulation/scenarios/scenario_imported_from_json/benchmark_scenario.py

Prompts

```
['build a dictionary mapping each event ID to its turn index using BFS traversal on scenario events', 'build turn trigger events with condition checks to modify the scenario event graph for multi-turn scenarios', 'build a validation function wrapper that validates scenario turns in online or offline mode', 'initialize multi-turn scenario turns by building event-to-turn mapping, turn triggers, and validation functions', 'create a BenchmarkScenarioImportedFromJson instance to import and manage multi-turn scenarios from JSON files', 'create app instances from serialized metadata with optional skip or keep filters', 'build the events flow from serialized events data in a ScenarioImportedFromJson instance', 'initialize and populate scenario apps from serialized app metadata with a sandbox directory', 'run and validate a ScenarioImportedFromJson scenario instance via the CLI entry point', 'create a ScenarioImportedFromJson instance with serialized events and apps for JSON import', 'preprocess a benchmark scenario by running oracle mode, setting up judges, and initializing turns', 'extract placeholder events from a scenario and return PlaceholderMetadata objects with conflict flags', 'preprocess a scenario for execution without oracle mode by adding dummy turn triggers and execution metadata', 'preprocess a scenario using a ScenarioRunnerConfig to set up judge configuration and validation mode', 'load a JSON scenario string, import it, and preprocess it using a ScenarioRunnerConfig']
```

Usage

```
{'build_event_id_to_turn_idx': 'build a dictionary mapping each event ID to its turn index using BFS traversal on scenario events', 'build_turn_trigger': 'build turn trigger events with condition checks to modify the scenario event graph for multi-turn scenarios', 'build_validation_fn': 'build a validation function wrapper that validates scenario turns in online or offline mode', 'initialize_turns': 'initialize multi-turn scenario turns by building event-to-turn mapping, turn triggers, and validation functions', 'create_BenchmarkScenarioImportedFromJson': 'create a BenchmarkScenarioImportedFromJson instance to import and manage multi-turn scenarios from JSON files'}
```

## File: facebookresearch_meta-agents-research-environments/are/simulation/scenarios/scenario_imported_from_json/scenario.py

Prompts

```
['build a dictionary mapping each event ID to its turn index using BFS traversal on scenario events', 'build turn trigger events with condition checks to modify the scenario event graph for multi-turn scenarios', 'build a validation function wrapper that validates scenario turns in online or offline mode', 'initialize multi-turn scenario turns by building event-to-turn mapping, turn triggers, and validation functions', 'create a BenchmarkScenarioImportedFromJson instance to import and manage multi-turn scenarios from JSON files', 'create app instances from serialized metadata with optional skip or keep filters', 'build the events flow from serialized events data in a ScenarioImportedFromJson instance', 'initialize and populate scenario apps from serialized app metadata with a sandbox directory', 'run and validate a ScenarioImportedFromJson scenario instance via the CLI entry point', 'create a ScenarioImportedFromJson instance with serialized events and apps for JSON import', 'preprocess a benchmark scenario by running oracle mode, setting up judges, and initializing turns', 'extract placeholder events from a scenario and return PlaceholderMetadata objects with conflict flags', 'preprocess a scenario for execution without oracle mode by adding dummy turn triggers and execution metadata', 'preprocess a scenario using a ScenarioRunnerConfig to set up judge configuration and validation mode', 'load a JSON scenario string, import it, and preprocess it using a ScenarioRunnerConfig']
```

Usage

```
{'get_apps_from_metadata': 'create app instances from serialized metadata with optional skip or keep filters', 'build_events_flow': 'build the events flow from serialized events data in a ScenarioImportedFromJson instance', 'init_and_populate_apps': 'initialize and populate scenario apps from serialized app metadata with a sandbox directory', 'run_scenario_imported_from_json': 'run and validate a ScenarioImportedFromJson scenario instance via the CLI entry point', 'create_scenario_imported_from_json': 'create a ScenarioImportedFromJson instance with serialized events and apps for JSON import'}
```

## File: facebookresearch_meta-agents-research-environments/are/simulation/scenarios/scenario_imported_from_json/utils.py

Prompts

```
['build a dictionary mapping each event ID to its turn index using BFS traversal on scenario events', 'build turn trigger events with condition checks to modify the scenario event graph for multi-turn scenarios', 'build a validation function wrapper that validates scenario turns in online or offline mode', 'initialize multi-turn scenario turns by building event-to-turn mapping, turn triggers, and validation functions', 'create a BenchmarkScenarioImportedFromJson instance to import and manage multi-turn scenarios from JSON files', 'create app instances from serialized metadata with optional skip or keep filters', 'build the events flow from serialized events data in a ScenarioImportedFromJson instance', 'initialize and populate scenario apps from serialized app metadata with a sandbox directory', 'run and validate a ScenarioImportedFromJson scenario instance via the CLI entry point', 'create a ScenarioImportedFromJson instance with serialized events and apps for JSON import', 'preprocess a benchmark scenario by running oracle mode, setting up judges, and initializing turns', 'extract placeholder events from a scenario and return PlaceholderMetadata objects with conflict flags', 'preprocess a scenario for execution without oracle mode by adding dummy turn triggers and execution metadata', 'preprocess a scenario using a ScenarioRunnerConfig to set up judge configuration and validation mode', 'load a JSON scenario string, import it, and preprocess it using a ScenarioRunnerConfig']
```

Usage

```
{'preprocess_scenario': 'preprocess a benchmark scenario by running oracle mode, setting up judges, and initializing turns', 'extract_placeholders': 'extract placeholder events from a scenario and return PlaceholderMetadata objects with conflict flags', 'preprocess_scenario_for_execution_without_oracle': 'preprocess a scenario for execution without oracle mode by adding dummy turn triggers and execution metadata', 'preprocess_scenario_from_config': 'preprocess a scenario using a ScenarioRunnerConfig to set up judge configuration and validation mode', 'load_and_preprocess_scenario_str': 'load a JSON scenario string, import it, and preprocess it using a ScenarioRunnerConfig'}
```

