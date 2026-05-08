# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/projects/habitat_ovmm/utils/config_utils.py

Prompts

```
['get a habitat config object from a yaml file path with optional overrides', 'load an OmegaConf configuration from a yaml file path and set it to readonly', 'merge habitat and environment configs removing third person sensors if visualization is disabled', 'merge environment and baseline configs into a readonly agent configuration DictConfig', 'review the config_utils module functions for merging habitat environment and agent configurations', 'create a HabitatOpenVocabManipEnv instance from a DictConfig for the OVMM task', 'create a habitat environment from config and wrap it into HabitatOpenVocabManipEnv', 'build an open vocabulary manipulation environment using habitat config and dataset', 'review the create_ovmm_env_fn function that creates OVMM environments from config', 'summarize the env_utils module that provides OVMM environment creation utilities', 'aggregate episode metrics DataFrame computing mean, min, max, and count for each metric column', 'compute stage-wise success rates and summary statistics from an aggregated metrics DataFrame', 'compute summary statistics including overall success and partial success from episode metrics DataFrame', 'review the aggregate_metrics function to understand how it drops string columns and computes aggregations', 'refactor the compute_stats function to support additional custom metric keys beyond phase success']
```

Usage

```
{'get_habitat_config': 'get a habitat config object from a yaml file path with optional overrides', 'get_omega_config': 'load an OmegaConf configuration from a yaml file path and set it to readonly', 'create_env_config': 'merge habitat and environment configs removing third person sensors if visualization is disabled', 'create_agent_config': 'merge environment and baseline configs into a readonly agent configuration DictConfig', 'review_config_utils': 'review the config_utils module functions for merging habitat environment and agent configurations'}
```

## File: facebookresearch_home-robot/projects/habitat_ovmm/utils/env_utils.py

Prompts

```
['get a habitat config object from a yaml file path with optional overrides', 'load an OmegaConf configuration from a yaml file path and set it to readonly', 'merge habitat and environment configs removing third person sensors if visualization is disabled', 'merge environment and baseline configs into a readonly agent configuration DictConfig', 'review the config_utils module functions for merging habitat environment and agent configurations', 'create a HabitatOpenVocabManipEnv instance from a DictConfig for the OVMM task', 'create a habitat environment from config and wrap it into HabitatOpenVocabManipEnv', 'build an open vocabulary manipulation environment using habitat config and dataset', 'review the create_ovmm_env_fn function that creates OVMM environments from config', 'summarize the env_utils module that provides OVMM environment creation utilities', 'aggregate episode metrics DataFrame computing mean, min, max, and count for each metric column', 'compute stage-wise success rates and summary statistics from an aggregated metrics DataFrame', 'compute summary statistics including overall success and partial success from episode metrics DataFrame', 'review the aggregate_metrics function to understand how it drops string columns and computes aggregations', 'refactor the compute_stats function to support additional custom metric keys beyond phase success']
```

Usage

```
{'create_ovmm_env': 'create a HabitatOpenVocabManipEnv instance from a DictConfig for the OVMM task', 'create_habitat_env_from_config': 'create a habitat environment from config and wrap it into HabitatOpenVocabManipEnv', 'build_ovmm_environment': 'build an open vocabulary manipulation environment using habitat config and dataset', 'review_create_ovmm_env_fn': 'review the create_ovmm_env_fn function that creates OVMM environments from config', 'summarize_env_utils': 'summarize the env_utils module that provides OVMM environment creation utilities'}
```

## File: facebookresearch_home-robot/projects/habitat_ovmm/utils/metrics_utils.py

Prompts

```
['get a habitat config object from a yaml file path with optional overrides', 'load an OmegaConf configuration from a yaml file path and set it to readonly', 'merge habitat and environment configs removing third person sensors if visualization is disabled', 'merge environment and baseline configs into a readonly agent configuration DictConfig', 'review the config_utils module functions for merging habitat environment and agent configurations', 'create a HabitatOpenVocabManipEnv instance from a DictConfig for the OVMM task', 'create a habitat environment from config and wrap it into HabitatOpenVocabManipEnv', 'build an open vocabulary manipulation environment using habitat config and dataset', 'review the create_ovmm_env_fn function that creates OVMM environments from config', 'summarize the env_utils module that provides OVMM environment creation utilities', 'aggregate episode metrics DataFrame computing mean, min, max, and count for each metric column', 'compute stage-wise success rates and summary statistics from an aggregated metrics DataFrame', 'compute summary statistics including overall success and partial success from episode metrics DataFrame', 'review the aggregate_metrics function to understand how it drops string columns and computes aggregations', 'refactor the compute_stats function to support additional custom metric keys beyond phase success']
```

Usage

```
{'aggregate_episode_metrics': 'aggregate episode metrics DataFrame computing mean, min, max, and count for each metric column', 'compute_stage_wise_stats': 'compute stage-wise success rates and summary statistics from an aggregated metrics DataFrame', 'get_stats_from_episode_metrics': 'compute summary statistics including overall success and partial success from episode metrics DataFrame', 'review_aggregate_metrics': 'review the aggregate_metrics function to understand how it drops string columns and computes aggregations', 'refactor_compute_stats': 'refactor the compute_stats function to support additional custom metric keys beyond phase success'}
```

