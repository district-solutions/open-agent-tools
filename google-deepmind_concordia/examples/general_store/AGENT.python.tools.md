# Agent Python Tools

- repo: google-deepmind/concordia
- repo_uri: https://github.com/google-deepmind/concordia

## File: google-deepmind_concordia/examples/general_store/run.py

Prompts

```
['run a concordia general store simulation with a specified scenario number and language model', 'set up a language model and sentence transformer embedder for concordia simulations', 'list all available concordia general store scenarios with their names and descriptions', 'run a specific concordia scenario by its number using a provided model and embedder', 'save concordia simulation results to a timestamped JSON file in the output directory', 'create a crime and punishment scenario config with a custom time period in minutes', 'run the crime and punishment simulation with a given model and embedder for a set number of steps', 'run the crime and punishment simulation with separate agent and game master model overrides', 'review the SCENARIO_INFO dict to get the scenario name, description, and entry point functions', 'review the create_scenario function to understand the locations, characters, and game rules for the simulation', 'run a general store simulation scenario with a config, model, and embedder', 'create a simulation config with a premise, instances, and optional extra prefabs', 'get the default prefab palette including entity and game master prefabs', 'review the run_scenario function to understand checkpoint capture and visualization output', 'refactor create_simulation_config to support additional prefab types or custom max steps']
```

Usage

```
{'run_concordia_simulation': 'run a concordia general store simulation with a specified scenario number and language model', 'setup_model_with_embedder': 'set up a language model and sentence transformer embedder for concordia simulations', 'list_available_scenarios': 'list all available concordia general store scenarios with their names and descriptions', 'run_scenario_by_number': 'run a specific concordia scenario by its number using a provided model and embedder', 'save_simulation_results': 'save concordia simulation results to a timestamped JSON file in the output directory'}
```

## File: google-deepmind_concordia/examples/general_store/scenario_00_crime_and_punishment.py

Prompts

```
['run a concordia general store simulation with a specified scenario number and language model', 'set up a language model and sentence transformer embedder for concordia simulations', 'list all available concordia general store scenarios with their names and descriptions', 'run a specific concordia scenario by its number using a provided model and embedder', 'save concordia simulation results to a timestamped JSON file in the output directory', 'create a crime and punishment scenario config with a custom time period in minutes', 'run the crime and punishment simulation with a given model and embedder for a set number of steps', 'run the crime and punishment simulation with separate agent and game master model overrides', 'review the SCENARIO_INFO dict to get the scenario name, description, and entry point functions', 'review the create_scenario function to understand the locations, characters, and game rules for the simulation', 'run a general store simulation scenario with a config, model, and embedder', 'create a simulation config with a premise, instances, and optional extra prefabs', 'get the default prefab palette including entity and game master prefabs', 'review the run_scenario function to understand checkpoint capture and visualization output', 'refactor create_simulation_config to support additional prefab types or custom max steps']
```

Usage

```
{'create_scenario_config': 'create a crime and punishment scenario config with a custom time period in minutes', 'run_simulation': 'run the crime and punishment simulation with a given model and embedder for a set number of steps', 'run_simulation_with_overrides': 'run the crime and punishment simulation with separate agent and game master model overrides', 'review_scenario_info': 'review the SCENARIO_INFO dict to get the scenario name, description, and entry point functions', 'review_create_scenario': 'review the create_scenario function to understand the locations, characters, and game rules for the simulation'}
```

## File: google-deepmind_concordia/examples/general_store/shared.py

Prompts

```
['run a concordia general store simulation with a specified scenario number and language model', 'set up a language model and sentence transformer embedder for concordia simulations', 'list all available concordia general store scenarios with their names and descriptions', 'run a specific concordia scenario by its number using a provided model and embedder', 'save concordia simulation results to a timestamped JSON file in the output directory', 'create a crime and punishment scenario config with a custom time period in minutes', 'run the crime and punishment simulation with a given model and embedder for a set number of steps', 'run the crime and punishment simulation with separate agent and game master model overrides', 'review the SCENARIO_INFO dict to get the scenario name, description, and entry point functions', 'review the create_scenario function to understand the locations, characters, and game rules for the simulation', 'run a general store simulation scenario with a config, model, and embedder', 'create a simulation config with a premise, instances, and optional extra prefabs', 'get the default prefab palette including entity and game master prefabs', 'review the run_scenario function to understand checkpoint capture and visualization output', 'refactor create_simulation_config to support additional prefab types or custom max steps']
```

Usage

```
{'run_simulation_scenario': 'run a general store simulation scenario with a config, model, and embedder', 'create_simulation_config': 'create a simulation config with a premise, instances, and optional extra prefabs', 'get_prefabs': 'get the default prefab palette including entity and game master prefabs', 'review_run_scenario': 'review the run_scenario function to understand checkpoint capture and visualization output', 'refactor_create_simulation_config': 'refactor create_simulation_config to support additional prefab types or custom max steps'}
```

