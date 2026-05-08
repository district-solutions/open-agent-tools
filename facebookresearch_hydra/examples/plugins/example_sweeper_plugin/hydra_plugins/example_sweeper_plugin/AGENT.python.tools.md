# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/examples/plugins/example_sweeper_plugin/hydra_plugins/example_sweeper_plugin/example_sweeper.py

Prompts

```
['create a Hydra sweeper plugin by subclassing Sweeper and implementing setup and sweep methods', 'build a LauncherConfig dataclass with target path and custom parameters for Hydra sweeper registration', 'register a sweeper config with ConfigStore using group hydra/sweeper and a unique name', 'implement sweep logic that parses overrides, computes cartesian product, and launches jobs in batches', 'chunk a list of sweep batches into smaller groups using max_batch_size before launching']
```

Usage

```
{'create_hydra_sweeper_plugin': 'create a Hydra sweeper plugin by subclassing Sweeper and implementing setup and sweep methods', 'build_sweeper_config_dataclass': 'build a LauncherConfig dataclass with target path and custom parameters for Hydra sweeper registration', 'register_sweeper_with_configstore': 'register a sweeper config with ConfigStore using group hydra/sweeper and a unique name', 'implement_sweep_batch_processing': 'implement sweep logic that parses overrides, computes cartesian product, and launches jobs in batches', 'chunk_batches_for_launcher': 'chunk a list of sweep batches into smaller groups using max_batch_size before launching'}
```

