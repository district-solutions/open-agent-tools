# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/examples/patterns/configuring_experiments/my_app.py

Prompts

```
['run the Hydra app my_app to print the resolved configuration as YAML', 'run my_app with experiment=nglite to override server to nginx and db to sqlite', 'run my_app with experiment=aplite to override db to sqlite and set server port to 8080', 'review the Hydra config groups for db, server, and experiment in the conf directory', 'summarize how OmegaConf.to_yaml prints the resolved DictConfig as YAML output']
```

Usage

```
{'run_hydra_app': 'run the Hydra app my_app to print the resolved configuration as YAML', 'run_experiment_config': 'run my_app with experiment=nglite to override server to nginx and db to sqlite', 'run_experiment_aplite': 'run my_app with experiment=aplite to override db to sqlite and set server port to 8080', 'review_hydra_config_groups': 'review the Hydra config groups for db, server, and experiment in the conf directory', 'summarize_omegaconf_yaml': 'summarize how OmegaConf.to_yaml prints the resolved DictConfig as YAML output'}
```

