# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/plugins/hydra_nevergrad_sweeper/tests/test_nevergrad_sweeper_plugin.py

Prompts

```
["test that the NevergradSweeper plugin is discoverable by Hydra's Plugins system", 'test creating nevergrad parameters from config dictionaries with choice, log, and scalar bounds', 'test parsing nevergrad parameters from Hydra override strings like choice, interval, and range', 'test launching Hydra sweep jobs using the nevergrad sweeper with a small budget', 'test running a Hydra app with nevergrad optimization via command-line overrides for batch size and learning rate']
```

Usage

```
{'test_nevergrad_sweeper_discovery': "test that the NevergradSweeper plugin is discoverable by Hydra's Plugins system", 'test_create_nevergrad_param_from_config': 'test creating nevergrad parameters from config dictionaries with choice, log, and scalar bounds', 'test_create_nevergrad_param_from_override': 'test parsing nevergrad parameters from Hydra override strings like choice, interval, and range', 'test_launched_jobs_sweep': 'test launching Hydra sweep jobs using the nevergrad sweeper with a small budget', 'test_nevergrad_example_app': 'test running a Hydra app with nevergrad optimization via command-line overrides for batch size and learning rate'}
```

