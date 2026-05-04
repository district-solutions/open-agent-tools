# Agent Python Tools

- repo: facebookresearch/habitat-lab
- repo_uri: https://github.com/facebookresearch/habitat-lab

## File: facebookresearch_habitat-lab/habitat-lab/habitat/config/default.py

Prompts

```
['load a Habitat config from a YAML file with optional overrides using get_config', 'resolve a relative or absolute YAML config file path to its full absolute path', 'resolve a relative Habitat config file path to its absolute path within the Habitat config directory', "retrieve an agent's configuration from a SimulatorConfig by agent index or default agent", 'validate and patch a Habitat DictConfig to ensure agents_order matches agents keys and set readonly', 'create a HabitatConfig dataclass to configure the environment, simulator, task, and dataset for a Habitat simulation run', 'create a TaskConfig dataclass to define navigation or rearrangement task parameters including sensors, measurements, and actions', 'create a SimulatorConfig dataclass to configure the Habitat simulator with scene, agents, sensors, and physics settings', 'create an ArmActionConfig dataclass to configure robot arm movement, grip controller, and joint parameters for rearrangement tasks', 'register the HabitatConfigPlugin with Hydra so that habitat config schemas are available in the Hydra ConfigStore', 'use the read_write context manager to temporarily modify a read-only OmegaConf configuration object', 'modify a read-only OmegaConf config by wrapping changes in the read_write context manager', 'modify a struct-locked OmegaConf config by using the read_write context to disable struct mode', 'review the read_write context manager that temporarily disables readonly and struct flags on OmegaConf configs', 'test the read_write context manager to ensure readonly and struct flags are restored after exiting']
```

Usage

```
{'get_config': 'load a Habitat config from a YAML file with optional overrides using get_config', 'get_full_config_path': 'resolve a relative or absolute YAML config file path to its full absolute path', 'get_full_habitat_config_path': 'resolve a relative Habitat config file path to its absolute path within the Habitat config directory', 'get_agent_config': "retrieve an agent's configuration from a SimulatorConfig by agent index or default agent", 'patch_config': 'validate and patch a Habitat DictConfig to ensure agents_order matches agents keys and set readonly'}
```

## File: facebookresearch_habitat-lab/habitat-lab/habitat/config/default_structured_configs.py

Prompts

```
['load a Habitat config from a YAML file with optional overrides using get_config', 'resolve a relative or absolute YAML config file path to its full absolute path', 'resolve a relative Habitat config file path to its absolute path within the Habitat config directory', "retrieve an agent's configuration from a SimulatorConfig by agent index or default agent", 'validate and patch a Habitat DictConfig to ensure agents_order matches agents keys and set readonly', 'create a HabitatConfig dataclass to configure the environment, simulator, task, and dataset for a Habitat simulation run', 'create a TaskConfig dataclass to define navigation or rearrangement task parameters including sensors, measurements, and actions', 'create a SimulatorConfig dataclass to configure the Habitat simulator with scene, agents, sensors, and physics settings', 'create an ArmActionConfig dataclass to configure robot arm movement, grip controller, and joint parameters for rearrangement tasks', 'register the HabitatConfigPlugin with Hydra so that habitat config schemas are available in the Hydra ConfigStore', 'use the read_write context manager to temporarily modify a read-only OmegaConf configuration object', 'modify a read-only OmegaConf config by wrapping changes in the read_write context manager', 'modify a struct-locked OmegaConf config by using the read_write context to disable struct mode', 'review the read_write context manager that temporarily disables readonly and struct flags on OmegaConf configs', 'test the read_write context manager to ensure readonly and struct flags are restored after exiting']
```

Usage

```
{'create_HabitatConfig': 'create a HabitatConfig dataclass to configure the environment, simulator, task, and dataset for a Habitat simulation run', 'create_TaskConfig': 'create a TaskConfig dataclass to define navigation or rearrangement task parameters including sensors, measurements, and actions', 'create_SimulatorConfig': 'create a SimulatorConfig dataclass to configure the Habitat simulator with scene, agents, sensors, and physics settings', 'create_ArmActionConfig': 'create an ArmActionConfig dataclass to configure robot arm movement, grip controller, and joint parameters for rearrangement tasks', 'register_hydra_plugin': 'register the HabitatConfigPlugin with Hydra so that habitat config schemas are available in the Hydra ConfigStore'}
```

## File: facebookresearch_habitat-lab/habitat-lab/habitat/config/read_write.py

Prompts

```
['load a Habitat config from a YAML file with optional overrides using get_config', 'resolve a relative or absolute YAML config file path to its full absolute path', 'resolve a relative Habitat config file path to its absolute path within the Habitat config directory', "retrieve an agent's configuration from a SimulatorConfig by agent index or default agent", 'validate and patch a Habitat DictConfig to ensure agents_order matches agents keys and set readonly', 'create a HabitatConfig dataclass to configure the environment, simulator, task, and dataset for a Habitat simulation run', 'create a TaskConfig dataclass to define navigation or rearrangement task parameters including sensors, measurements, and actions', 'create a SimulatorConfig dataclass to configure the Habitat simulator with scene, agents, sensors, and physics settings', 'create an ArmActionConfig dataclass to configure robot arm movement, grip controller, and joint parameters for rearrangement tasks', 'register the HabitatConfigPlugin with Hydra so that habitat config schemas are available in the Hydra ConfigStore', 'use the read_write context manager to temporarily modify a read-only OmegaConf configuration object', 'modify a read-only OmegaConf config by wrapping changes in the read_write context manager', 'modify a struct-locked OmegaConf config by using the read_write context to disable struct mode', 'review the read_write context manager that temporarily disables readonly and struct flags on OmegaConf configs', 'test the read_write context manager to ensure readonly and struct flags are restored after exiting']
```

Usage

```
{'use_read_write_context': 'use the read_write context manager to temporarily modify a read-only OmegaConf configuration object', 'modify_readonly_config': 'modify a read-only OmegaConf config by wrapping changes in the read_write context manager', 'modify_struct_config': 'modify a struct-locked OmegaConf config by using the read_write context to disable struct mode', 'review_read_write': 'review the read_write context manager that temporarily disables readonly and struct flags on OmegaConf configs', 'test_read_write_context': 'test the read_write context manager to ensure readonly and struct flags are restored after exiting'}
```

