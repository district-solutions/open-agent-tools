# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/examples/advanced/package_overrides/simple.py

Prompts

```
['run the hydra app that prints the resolved config as YAML to stdout', 'run the my_app function to print the OmegaConf config as YAML', 'review the hydra.main decorator configuration with version_base, config_path, and config_name', 'review the my_app function that accepts a DictConfig and prints it as YAML', 'summarize the hydra app that uses OmegaConf.to_yaml to print the config', 'run the Hydra app that composes two database configs under separate package names and prints the result as YAML', 'run the my_app function to print the composed Hydra DictConfig as YAML output', 'review the OmegaConf.to_yaml call that serializes the DictConfig to a YAML string', 'refactor the two_packages config to override source or destination database defaults at runtime']
```

Usage

```
{'run_hydra_app': 'run the hydra app that prints the resolved config as YAML to stdout', 'run_my_app': 'run the my_app function to print the OmegaConf config as YAML', 'review_hydra_main_decorator': 'review the hydra.main decorator configuration with version_base, config_path, and config_name', 'review_my_app': 'review the my_app function that accepts a DictConfig and prints it as YAML', 'summarize_hydra_app': 'summarize the hydra app that uses OmegaConf.to_yaml to print the config'}
```

## File: facebookresearch_hydra/examples/advanced/package_overrides/two_packages.py

Prompts

```
['run the hydra app that prints the resolved config as YAML to stdout', 'run the my_app function to print the OmegaConf config as YAML', 'review the hydra.main decorator configuration with version_base, config_path, and config_name', 'review the my_app function that accepts a DictConfig and prints it as YAML', 'summarize the hydra app that uses OmegaConf.to_yaml to print the config', 'run the Hydra app that composes two database configs under separate package names and prints the result as YAML', 'run the my_app function to print the composed Hydra DictConfig as YAML output', 'review the OmegaConf.to_yaml call that serializes the DictConfig to a YAML string', 'refactor the two_packages config to override source or destination database defaults at runtime']
```

Usage

```
{'run_hydra_package_override_app': 'run the Hydra app that composes two database configs under separate package names and prints the result as YAML', 'run_my_app_with_cfg': 'run the my_app function to print the composed Hydra DictConfig as YAML output', 'review_hydra_main_decorator': 'review the hydra.main decorator usage with version_base, config_path, and config_name parameters', 'review_omegaconf_to_yaml': 'review the OmegaConf.to_yaml call that serializes the DictConfig to a YAML string', 'refactor_two_packages_config': 'refactor the two_packages config to override source or destination database defaults at runtime'}
```

