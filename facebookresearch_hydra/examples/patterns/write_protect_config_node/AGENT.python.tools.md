# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/examples/patterns/write_protect_config_node/frozen.py

Prompts

```
['run the hydra app that prints a frozen SerialPort config with baud_rate, data_bits, and stop_bits', 'create a frozen dataclass like SerialPort to write-protect a Hydra config node with immutable fields', 'register a dataclass config node in Hydra using ConfigStore.instance().store with a name and node', 'review the frozen dataclass pattern for write-protecting Hydra config nodes to prevent runtime mutation', 'refactor a mutable Hydra config dataclass to use frozen=True to prevent accidental config changes']
```

Usage

```
{'run_hydra_frozen_config_app': 'run the hydra app that prints a frozen SerialPort config with baud_rate, data_bits, and stop_bits', 'create_frozen_dataclass_config': 'create a frozen dataclass like SerialPort to write-protect a Hydra config node with immutable fields', 'register_config_with_configstore': 'register a dataclass config node in Hydra using ConfigStore.instance().store with a name and node', 'review_frozen_config_pattern': 'review the frozen dataclass pattern for write-protecting Hydra config nodes to prevent runtime mutation', 'refactor_config_to_frozen': 'refactor a mutable Hydra config dataclass to use frozen=True to prevent accidental config changes'}
```

