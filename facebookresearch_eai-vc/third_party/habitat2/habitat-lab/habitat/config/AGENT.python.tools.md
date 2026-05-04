# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-lab/habitat/config/default.py

Prompts

```
['load a habitat config from a yaml file with optional overrides using get_config', 'resolve a relative config path to an absolute path using get_full_config_path', 'resolve a relative habitat config path to an absolute path using get_full_habitat_config_path', "get an agent's config node from a simulator config using get_agent_config", 'review the get_config function to understand how it composes habitat configs from yaml and overrides', 'register a Hydra plugin by calling register_hydra_plugin with the HabitatConfigPlugin class before invoking hydra.main', 'configure a Habitat task by setting task type, reward measure, success measure, and actions in TaskConfig', 'configure simulator sensors like RGB, depth, or semantic by defining entries in AgentConfig sim_sensors dict', 'configure task measurements such as SPL, success, or top-down map by adding entries to TaskConfig measurements dict', 'configure task lab sensors like GPS, compass, or pointgoal by adding entries to TaskConfig lab_sensors dict', 'use the read_write context manager to temporarily allow modifications to a readonly OmegaConf config object', 'modify an OmegaConf config object by using read_write to disable readonly and struct flags temporarily', 'patch an OmegaConf Container config within a context block that restores original flags on exit', 'review the read_write context manager function that toggles OmegaConf readonly and struct flags for safe config mutation', 'refactor the read_write context manager to replace OmegaConf flag toggling with native Hydra config mutation support']
```

Usage

```
{'get_config': 'load a habitat config from a yaml file with optional overrides using get_config', 'get_full_config_path': 'resolve a relative config path to an absolute path using get_full_config_path', 'get_full_habitat_config_path': 'resolve a relative habitat config path to an absolute path using get_full_habitat_config_path', 'get_agent_config': "get an agent's config node from a simulator config using get_agent_config", 'review_get_config': 'review the get_config function to understand how it composes habitat configs from yaml and overrides'}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-lab/habitat/config/default_structured_configs.py

Prompts

```
['load a habitat config from a yaml file with optional overrides using get_config', 'resolve a relative config path to an absolute path using get_full_config_path', 'resolve a relative habitat config path to an absolute path using get_full_habitat_config_path', "get an agent's config node from a simulator config using get_agent_config", 'review the get_config function to understand how it composes habitat configs from yaml and overrides', 'register a Hydra plugin by calling register_hydra_plugin with the HabitatConfigPlugin class before invoking hydra.main', 'configure a Habitat task by setting task type, reward measure, success measure, and actions in TaskConfig', 'configure simulator sensors like RGB, depth, or semantic by defining entries in AgentConfig sim_sensors dict', 'configure task measurements such as SPL, success, or top-down map by adding entries to TaskConfig measurements dict', 'configure task lab sensors like GPS, compass, or pointgoal by adding entries to TaskConfig lab_sensors dict', 'use the read_write context manager to temporarily allow modifications to a readonly OmegaConf config object', 'modify an OmegaConf config object by using read_write to disable readonly and struct flags temporarily', 'patch an OmegaConf Container config within a context block that restores original flags on exit', 'review the read_write context manager function that toggles OmegaConf readonly and struct flags for safe config mutation', 'refactor the read_write context manager to replace OmegaConf flag toggling with native Hydra config mutation support']
```

Usage

```
{'register_hydra_plugin': 'register a Hydra plugin by calling register_hydra_plugin with the HabitatConfigPlugin class before invoking hydra.main', 'configure_habitat_task': 'configure a Habitat task by setting task type, reward measure, success measure, and actions in TaskConfig', 'configure_simulator_sensors': 'configure simulator sensors like RGB, depth, or semantic by defining entries in AgentConfig sim_sensors dict', 'configure_task_measurements': 'configure task measurements such as SPL, success, or top-down map by adding entries to TaskConfig measurements dict', 'configure_task_lab_sensors': 'configure task lab sensors like GPS, compass, or pointgoal by adding entries to TaskConfig lab_sensors dict'}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-lab/habitat/config/read_write.py

Prompts

```
['load a habitat config from a yaml file with optional overrides using get_config', 'resolve a relative config path to an absolute path using get_full_config_path', 'resolve a relative habitat config path to an absolute path using get_full_habitat_config_path', "get an agent's config node from a simulator config using get_agent_config", 'review the get_config function to understand how it composes habitat configs from yaml and overrides', 'register a Hydra plugin by calling register_hydra_plugin with the HabitatConfigPlugin class before invoking hydra.main', 'configure a Habitat task by setting task type, reward measure, success measure, and actions in TaskConfig', 'configure simulator sensors like RGB, depth, or semantic by defining entries in AgentConfig sim_sensors dict', 'configure task measurements such as SPL, success, or top-down map by adding entries to TaskConfig measurements dict', 'configure task lab sensors like GPS, compass, or pointgoal by adding entries to TaskConfig lab_sensors dict', 'use the read_write context manager to temporarily allow modifications to a readonly OmegaConf config object', 'modify an OmegaConf config object by using read_write to disable readonly and struct flags temporarily', 'patch an OmegaConf Container config within a context block that restores original flags on exit', 'review the read_write context manager function that toggles OmegaConf readonly and struct flags for safe config mutation', 'refactor the read_write context manager to replace OmegaConf flag toggling with native Hydra config mutation support']
```

Usage

```
{'use_read_write_context_manager': 'use the read_write context manager to temporarily allow modifications to a readonly OmegaConf config object', 'modify_omegaconf_config': 'modify an OmegaConf config object by using read_write to disable readonly and struct flags temporarily', 'patch_config_in_context': 'patch an OmegaConf Container config within a context block that restores original flags on exit', 'review_read_write_function': 'review the read_write context manager function that toggles OmegaConf readonly and struct flags for safe config mutation', 'refactor_read_write_for_hydra': 'refactor the read_write context manager to replace OmegaConf flag toggling with native Hydra config mutation support'}
```

