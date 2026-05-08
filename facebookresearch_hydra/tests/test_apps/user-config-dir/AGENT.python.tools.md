# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/tests/test_apps/user-config-dir/my_app.py

Prompts

```
['run the Hydra app my_app that prints the resolved config as YAML', 'run the Hydra app my_app with command-line config overrides like db.driver=sqlite', 'review the hydra.main decorator configuration with version_base, config_path, and config_name', 'summarize how OmegaConf.to_yaml converts a DictConfig object into a YAML string', 'refactor my_app to write the config YAML output to a file instead of printing']
```

Usage

```
{'run_hydra_app': 'run the Hydra app my_app that prints the resolved config as YAML', 'run_hydra_app_with_override': 'run the Hydra app my_app with command-line config overrides like db.driver=sqlite', 'review_hydra_main_decorator': 'review the hydra.main decorator configuration with version_base, config_path, and config_name', 'summarize_omegaconf_to_yaml': 'summarize how OmegaConf.to_yaml converts a DictConfig object into a YAML string', 'refactor_my_app_config_output': 'refactor my_app to write the config YAML output to a file instead of printing'}
```

