# Agent Python Tools

- repo: facebookresearch/meta-agents-research-environments
- repo_uri: https://github.com/facebookresearch/meta-agents-research-environments

## File: facebookresearch_meta-agents-research-environments/are/simulation/scenarios/config.py

Prompts

```
['create a HuggingFaceConfig instance to set dataset upload and original dataset metadata fields', 'create a ScenarioRunnerConfig instance to configure model, agent, endpoint, and scenario execution parameters', 'create a MultiScenarioRunnerConfig instance to configure concurrent scenario execution with executor type and caching', 'run get_config_hash on a ScenarioRunnerConfig to generate an MD5 hash of execution-affecting parameters', 'review the ScenarioRunnerConfig class fields to understand model, agent, and agent2agent configuration options', 'register all built-in scenarios with the provided ScenarioRegistry instance by discovering and importing scenario modules', 'discover scenario modules in proper Python packages using pkgutil.iter_modules and import them into the registry', 'discover scenario modules using os.walk as a fallback method to find Python files in non-package directories', 'import a scenario module by its fully qualified name using importlib and track it to avoid duplicates', 'skip utility modules test modules and modules starting with underscore during scenario discovery', 'create a Scenario instance to define simulation events, apps, and task flows for agent research environments', 'add an event to the Scenario DAG with predecessor dependencies, event type, and timing validation', 'edit an existing event in the Scenario DAG by updating its function, parameters, and predecessor links', 'validate the Scenario state after execution by checking environment state and final validation checks', 'process a list of events in topological order and add them to the Scenario with proper dependencies', 'create a ScenarioValidationResult dataclass instance with success, exception, rationale, and duration fields', 'add a ScenarioValidationResult to a MultiScenarioValidationResult by scenario_id and optional run_number', 'convert a MultiScenarioValidationResult to a polars DataFrame with optional extra columns', 'calculate the success rate percentage from a MultiScenarioValidationResult counts', 'generate a detailed text description of MultiScenarioValidationResult with model info and stats']
```

Usage

```
{'create_HuggingFaceConfig': 'create a HuggingFaceConfig instance to set dataset upload and original dataset metadata fields', 'create_ScenarioRunnerConfig': 'create a ScenarioRunnerConfig instance to configure model, agent, endpoint, and scenario execution parameters', 'create_MultiScenarioRunnerConfig': 'create a MultiScenarioRunnerConfig instance to configure concurrent scenario execution with executor type and caching', 'run_get_config_hash': 'run get_config_hash on a ScenarioRunnerConfig to generate an MD5 hash of execution-affecting parameters', 'review_ScenarioRunnerConfig_fields': 'review the ScenarioRunnerConfig class fields to understand model, agent, and agent2agent configuration options'}
```

## File: facebookresearch_meta-agents-research-environments/are/simulation/scenarios/registration.py

Prompts

```
['create a HuggingFaceConfig instance to set dataset upload and original dataset metadata fields', 'create a ScenarioRunnerConfig instance to configure model, agent, endpoint, and scenario execution parameters', 'create a MultiScenarioRunnerConfig instance to configure concurrent scenario execution with executor type and caching', 'run get_config_hash on a ScenarioRunnerConfig to generate an MD5 hash of execution-affecting parameters', 'review the ScenarioRunnerConfig class fields to understand model, agent, and agent2agent configuration options', 'register all built-in scenarios with the provided ScenarioRegistry instance by discovering and importing scenario modules', 'discover scenario modules in proper Python packages using pkgutil.iter_modules and import them into the registry', 'discover scenario modules using os.walk as a fallback method to find Python files in non-package directories', 'import a scenario module by its fully qualified name using importlib and track it to avoid duplicates', 'skip utility modules test modules and modules starting with underscore during scenario discovery', 'create a Scenario instance to define simulation events, apps, and task flows for agent research environments', 'add an event to the Scenario DAG with predecessor dependencies, event type, and timing validation', 'edit an existing event in the Scenario DAG by updating its function, parameters, and predecessor links', 'validate the Scenario state after execution by checking environment state and final validation checks', 'process a list of events in topological order and add them to the Scenario with proper dependencies', 'create a ScenarioValidationResult dataclass instance with success, exception, rationale, and duration fields', 'add a ScenarioValidationResult to a MultiScenarioValidationResult by scenario_id and optional run_number', 'convert a MultiScenarioValidationResult to a polars DataFrame with optional extra columns', 'calculate the success rate percentage from a MultiScenarioValidationResult counts', 'generate a detailed text description of MultiScenarioValidationResult with model info and stats']
```

Usage

```
{'register_builtin_scenarios': 'register all built-in scenarios with the provided ScenarioRegistry instance by discovering and importing scenario modules', 'discover_with_pkgutil': 'discover scenario modules in proper Python packages using pkgutil.iter_modules and import them into the registry', 'discover_with_os_walk': 'discover scenario modules using os.walk as a fallback method to find Python files in non-package directories', 'import_scenario_module': 'import a scenario module by its fully qualified name using importlib and track it to avoid duplicates', 'skip_scenario_modules': 'skip utility modules test modules and modules starting with underscore during scenario discovery'}
```

## File: facebookresearch_meta-agents-research-environments/are/simulation/scenarios/scenario.py

Prompts

```
['create a HuggingFaceConfig instance to set dataset upload and original dataset metadata fields', 'create a ScenarioRunnerConfig instance to configure model, agent, endpoint, and scenario execution parameters', 'create a MultiScenarioRunnerConfig instance to configure concurrent scenario execution with executor type and caching', 'run get_config_hash on a ScenarioRunnerConfig to generate an MD5 hash of execution-affecting parameters', 'review the ScenarioRunnerConfig class fields to understand model, agent, and agent2agent configuration options', 'register all built-in scenarios with the provided ScenarioRegistry instance by discovering and importing scenario modules', 'discover scenario modules in proper Python packages using pkgutil.iter_modules and import them into the registry', 'discover scenario modules using os.walk as a fallback method to find Python files in non-package directories', 'import a scenario module by its fully qualified name using importlib and track it to avoid duplicates', 'skip utility modules test modules and modules starting with underscore during scenario discovery', 'create a Scenario instance to define simulation events, apps, and task flows for agent research environments', 'add an event to the Scenario DAG with predecessor dependencies, event type, and timing validation', 'edit an existing event in the Scenario DAG by updating its function, parameters, and predecessor links', 'validate the Scenario state after execution by checking environment state and final validation checks', 'process a list of events in topological order and add them to the Scenario with proper dependencies', 'create a ScenarioValidationResult dataclass instance with success, exception, rationale, and duration fields', 'add a ScenarioValidationResult to a MultiScenarioValidationResult by scenario_id and optional run_number', 'convert a MultiScenarioValidationResult to a polars DataFrame with optional extra columns', 'calculate the success rate percentage from a MultiScenarioValidationResult counts', 'generate a detailed text description of MultiScenarioValidationResult with model info and stats']
```

Usage

```
{'create_scenario': 'create a Scenario instance to define simulation events, apps, and task flows for agent research environments', 'add_event_to_scenario': 'add an event to the Scenario DAG with predecessor dependencies, event type, and timing validation', 'edit_event_in_scenario': 'edit an existing event in the Scenario DAG by updating its function, parameters, and predecessor links', 'validate_scenario': 'validate the Scenario state after execution by checking environment state and final validation checks', 'process_events_into_scenario': 'process a list of events in topological order and add them to the Scenario with proper dependencies'}
```

## File: facebookresearch_meta-agents-research-environments/are/simulation/scenarios/validation_result.py

Prompts

```
['create a HuggingFaceConfig instance to set dataset upload and original dataset metadata fields', 'create a ScenarioRunnerConfig instance to configure model, agent, endpoint, and scenario execution parameters', 'create a MultiScenarioRunnerConfig instance to configure concurrent scenario execution with executor type and caching', 'run get_config_hash on a ScenarioRunnerConfig to generate an MD5 hash of execution-affecting parameters', 'review the ScenarioRunnerConfig class fields to understand model, agent, and agent2agent configuration options', 'register all built-in scenarios with the provided ScenarioRegistry instance by discovering and importing scenario modules', 'discover scenario modules in proper Python packages using pkgutil.iter_modules and import them into the registry', 'discover scenario modules using os.walk as a fallback method to find Python files in non-package directories', 'import a scenario module by its fully qualified name using importlib and track it to avoid duplicates', 'skip utility modules test modules and modules starting with underscore during scenario discovery', 'create a Scenario instance to define simulation events, apps, and task flows for agent research environments', 'add an event to the Scenario DAG with predecessor dependencies, event type, and timing validation', 'edit an existing event in the Scenario DAG by updating its function, parameters, and predecessor links', 'validate the Scenario state after execution by checking environment state and final validation checks', 'process a list of events in topological order and add them to the Scenario with proper dependencies', 'create a ScenarioValidationResult dataclass instance with success, exception, rationale, and duration fields', 'add a ScenarioValidationResult to a MultiScenarioValidationResult by scenario_id and optional run_number', 'convert a MultiScenarioValidationResult to a polars DataFrame with optional extra columns', 'calculate the success rate percentage from a MultiScenarioValidationResult counts', 'generate a detailed text description of MultiScenarioValidationResult with model info and stats']
```

Usage

```
{'create_ScenarioValidationResult': 'create a ScenarioValidationResult dataclass instance with success, exception, rationale, and duration fields', 'add_result_MultiScenarioValidationResult': 'add a ScenarioValidationResult to a MultiScenarioValidationResult by scenario_id and optional run_number', 'to_polars_MultiScenarioValidationResult': 'convert a MultiScenarioValidationResult to a polars DataFrame with optional extra columns', 'success_rate_MultiScenarioValidationResult': 'calculate the success rate percentage from a MultiScenarioValidationResult counts', 'description_MultiScenarioValidationResult': 'generate a detailed text description of MultiScenarioValidationResult with model info and stats'}
```

