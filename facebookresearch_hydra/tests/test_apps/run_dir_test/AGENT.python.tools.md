# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/tests/test_apps/run_dir_test/my_app.py

Prompts

```
['run a Hydra-decorated app that validates run directory consistency before and after a sleep', "test that Hydra's run directory path remains stable across time using get_original_cwd and HydraConfig", 'review the hydra.main decorator usage with version_base set to None for a simple app', 'summarize how HydraConfig.get().run.dir provides the current run directory path', 'refactor the Hydra app to replace time.sleep with a configurable wait duration']
```

Usage

```
{'run_hydra_app': 'run a Hydra-decorated app that validates run directory consistency before and after a sleep', 'test_hydra_run_dir': "test that Hydra's run directory path remains stable across time using get_original_cwd and HydraConfig", 'review_hydra_main_decorator': 'review the hydra.main decorator usage with version_base set to None for a simple app', 'summarize_hydraconfig_run_dir': 'summarize how HydraConfig.get().run.dir provides the current run directory path', 'refactor_hydra_app_sleep': 'refactor the Hydra app to replace time.sleep with a configurable wait duration'}
```

