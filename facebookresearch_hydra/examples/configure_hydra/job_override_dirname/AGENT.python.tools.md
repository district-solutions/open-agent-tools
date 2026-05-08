# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/examples/configure_hydra/job_override_dirname/my_app.py

Prompts

```
['run the hydra my_app that prints the current working directory', 'run the hydra my_app with command line config overrides for learning_rate or batch_size', 'run the hydra my_app in multirun mode to sweep over seed values', 'review the hydra job override_dirname config that excludes the seed key from directory names', 'refactor the hydra my_app to add additional config-driven logic beyond printing the working directory']
```

Usage

```
{'run_hydra_app': 'run the hydra my_app that prints the current working directory', 'run_hydra_app_with_override': 'run the hydra my_app with command line config overrides for learning_rate or batch_size', 'run_hydra_multirun': 'run the hydra my_app in multirun mode to sweep over seed values', 'review_hydra_override_dirname_config': 'review the hydra job override_dirname config that excludes the seed key from directory names', 'refactor_hydra_app': 'refactor the hydra my_app to add additional config-driven logic beyond printing the working directory'}
```

