# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/tests/test_apps/sweep_complex_defaults/my_app.py

Prompts

```
['run the hydra app my_app that prints the resolved config as YAML', 'run the hydra app with sweep mode to iterate over multiple config combinations', 'review the my_app function that uses OmegaConf.to_yaml to print the Hydra config', 'refactor the hydra.main decorator to change the config_path or config_name values', 'test the my_app function by running it with different Hydra config overrides via CLI']
```

Usage

```
{'run_hydra_app': 'run the hydra app my_app that prints the resolved config as YAML', 'run_hydra_sweep': 'run the hydra app with sweep mode to iterate over multiple config combinations', 'review_hydra_config_printing': 'review the my_app function that uses OmegaConf.to_yaml to print the Hydra config', 'refactor_hydra_main_decorator': 'refactor the hydra.main decorator to change the config_path or config_name values', 'test_hydra_app_config': 'test the my_app function by running it with different Hydra config overrides via CLI'}
```

