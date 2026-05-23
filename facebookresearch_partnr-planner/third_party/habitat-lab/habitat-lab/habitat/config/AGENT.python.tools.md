# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-lab/habitat/config/default.py

Prompts

```
['get a Habitat config object from a YAML file path with optional overrides', 'get the absolute path to a YAML config file relative to a configs directory', 'get the absolute path to a Habitat YAML config file relative to the default config directory', "get an agent's config node from a simulator config by agent index", 'patch a Habitat DictConfig by inferring missing keys and setting it to readonly', 'review the HabitatConfig dataclass to understand the top-level configuration schema for Habitat environments', 'review the TaskConfig dataclass to understand task definitions including reward, success, and action configurations', 'review the SimulatorConfig dataclass to understand simulator settings like scene, agents, and rendering options', 'review the ArmActionConfig dataclass to understand robot arm action parameters for rearrangement tasks', 'review the register_hydra_plugin function to understand how to register the HabitatConfigPlugin with Hydra before using hydra.main', 'use the read_write context manager to temporarily modify a readonly OmegaConf configuration object', 'modify an OmegaConf config by wrapping changes in the read_write context manager', 'toggle readonly and struct flags on an OmegaConf config using the read_write context', 'review the read_write context manager that safely enables temporary writes to OmegaConf configs', 'summarize the read_write function that temporarily disables readonly and struct flags on OmegaConf']
```

Usage

```
{'get_config': 'get a Habitat config object from a YAML file path with optional overrides', 'get_full_config_path': 'get the absolute path to a YAML config file relative to a configs directory', 'get_full_habitat_config_path': 'get the absolute path to a Habitat YAML config file relative to the default config directory', 'get_agent_config': "get an agent's config node from a simulator config by agent index", 'patch_config': 'patch a Habitat DictConfig by inferring missing keys and setting it to readonly'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-lab/habitat/config/default_structured_configs.py

Prompts

```
['get a Habitat config object from a YAML file path with optional overrides', 'get the absolute path to a YAML config file relative to a configs directory', 'get the absolute path to a Habitat YAML config file relative to the default config directory', "get an agent's config node from a simulator config by agent index", 'patch a Habitat DictConfig by inferring missing keys and setting it to readonly', 'review the HabitatConfig dataclass to understand the top-level configuration schema for Habitat environments', 'review the TaskConfig dataclass to understand task definitions including reward, success, and action configurations', 'review the SimulatorConfig dataclass to understand simulator settings like scene, agents, and rendering options', 'review the ArmActionConfig dataclass to understand robot arm action parameters for rearrangement tasks', 'review the register_hydra_plugin function to understand how to register the HabitatConfigPlugin with Hydra before using hydra.main', 'use the read_write context manager to temporarily modify a readonly OmegaConf configuration object', 'modify an OmegaConf config by wrapping changes in the read_write context manager', 'toggle readonly and struct flags on an OmegaConf config using the read_write context', 'review the read_write context manager that safely enables temporary writes to OmegaConf configs', 'summarize the read_write function that temporarily disables readonly and struct flags on OmegaConf']
```

Usage

```
{'review_HabitatConfig': 'review the HabitatConfig dataclass to understand the top-level configuration schema for Habitat environments', 'review_TaskConfig': 'review the TaskConfig dataclass to understand task definitions including reward, success, and action configurations', 'review_SimulatorConfig': 'review the SimulatorConfig dataclass to understand simulator settings like scene, agents, and rendering options', 'review_ArmActionConfig': 'review the ArmActionConfig dataclass to understand robot arm action parameters for rearrangement tasks', 'review_register_hydra_plugin': 'review the register_hydra_plugin function to understand how to register the HabitatConfigPlugin with Hydra before using hydra.main'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-lab/habitat/config/read_write.py

Prompts

```
['get a Habitat config object from a YAML file path with optional overrides', 'get the absolute path to a YAML config file relative to a configs directory', 'get the absolute path to a Habitat YAML config file relative to the default config directory', "get an agent's config node from a simulator config by agent index", 'patch a Habitat DictConfig by inferring missing keys and setting it to readonly', 'review the HabitatConfig dataclass to understand the top-level configuration schema for Habitat environments', 'review the TaskConfig dataclass to understand task definitions including reward, success, and action configurations', 'review the SimulatorConfig dataclass to understand simulator settings like scene, agents, and rendering options', 'review the ArmActionConfig dataclass to understand robot arm action parameters for rearrangement tasks', 'review the register_hydra_plugin function to understand how to register the HabitatConfigPlugin with Hydra before using hydra.main', 'use the read_write context manager to temporarily modify a readonly OmegaConf configuration object', 'modify an OmegaConf config by wrapping changes in the read_write context manager', 'toggle readonly and struct flags on an OmegaConf config using the read_write context', 'review the read_write context manager that safely enables temporary writes to OmegaConf configs', 'summarize the read_write function that temporarily disables readonly and struct flags on OmegaConf']
```

Usage

```
{'use_read_write_context': 'use the read_write context manager to temporarily modify a readonly OmegaConf configuration object', 'modify_omegaconf_config': 'modify an OmegaConf config by wrapping changes in the read_write context manager', 'toggle_readonly_config': 'toggle readonly and struct flags on an OmegaConf config using the read_write context', 'review_read_write_function': 'review the read_write context manager that safely enables temporary writes to OmegaConf configs', 'summarize_read_write': 'summarize the read_write function that temporarily disables readonly and struct flags on OmegaConf'}
```

