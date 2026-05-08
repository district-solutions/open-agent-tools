# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/tests/test_apps/app_with_runtime_config_error/my_app.py

Prompts

```
['run the hydra main decorated my_app function that calls foo with a DictConfig', 'test that assigning to a non-existent config key raises a runtime config error', 'review the foo function that attempts to assign cfg.foo which does not exist in the config', 'refactor the foo function to safely handle missing config keys before assignment', 'summarize how hydra.main is used with version_base, config_path, and config_name parameters']
```

Usage

```
{'run_hydra_app': 'run the hydra main decorated my_app function that calls foo with a DictConfig', 'test_runtime_config_error': 'test that assigning to a non-existent config key raises a runtime config error', 'review_foo_function': 'review the foo function that attempts to assign cfg.foo which does not exist in the config', 'refactor_foo_function': 'refactor the foo function to safely handle missing config keys before assignment', 'summarize_hydra_main_usage': 'summarize how hydra.main is used with version_base, config_path, and config_name parameters'}
```

