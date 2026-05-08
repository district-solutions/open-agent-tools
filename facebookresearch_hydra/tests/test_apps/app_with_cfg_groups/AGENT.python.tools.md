# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/tests/test_apps/app_with_cfg_groups/my_app.py

Prompts

```
['run the Hydra app my_app that returns the resolved DictConfig from conf/config', 'run the Hydra app my_app with a config group override via command-line arguments', 'test that the Hydra app my_app correctly resolves and returns the merged config', 'review the my_app function decorated with @hydra.main using config_path conf and config_name config', 'refactor the my_app Hydra entry point to process the DictConfig instead of returning it directly', 'run the hydra app that prints the selected optimizer choice from config group runtime options', 'run the my_app function with a specific optimizer config group choice via hydra cli', 'test the hydra runtime choices feature by running the app with different optimizer options', 'summarize how hydra resolves runtime config group choices using the hydra runtime choices interpolation']
```

Usage

```
{'run_hydra_app': 'run the Hydra app my_app that returns the resolved DictConfig from conf/config', 'run_hydra_app_with_cfg_group': 'run the Hydra app my_app with a config group override via command-line arguments', 'test_hydra_config_resolution': 'test that the Hydra app my_app correctly resolves and returns the merged config', 'review_hydra_main_decorator': 'review the my_app function decorated with @hydra.main using config_path conf and config_name config', 'refactor_hydra_app': 'refactor the my_app Hydra entry point to process the DictConfig instead of returning it directly'}
```

## File: facebookresearch_hydra/tests/test_apps/app_with_cfg_groups/my_app_with_runtime_choices_print.py

Prompts

```
['run the Hydra app my_app that returns the resolved DictConfig from conf/config', 'run the Hydra app my_app with a config group override via command-line arguments', 'test that the Hydra app my_app correctly resolves and returns the merged config', 'review the my_app function decorated with @hydra.main using config_path conf and config_name config', 'refactor the my_app Hydra entry point to process the DictConfig instead of returning it directly', 'run the hydra app that prints the selected optimizer choice from config group runtime options', 'run the my_app function with a specific optimizer config group choice via hydra cli', 'test the hydra runtime choices feature by running the app with different optimizer options', 'summarize how hydra resolves runtime config group choices using the hydra runtime choices interpolation']
```

Usage

```
{'run_hydra_app_with_runtime_choices': 'run the hydra app that prints the selected optimizer choice from config group runtime options', 'run_my_app_with_optimizer': 'run the my_app function with a specific optimizer config group choice via hydra cli', 'test_hydra_runtime_choices': 'test the hydra runtime choices feature by running the app with different optimizer options', 'review_hydra_main_decorator': 'review the hydra main decorator usage with config_path and config_name for runtime option selection', 'summarize_hydra_config_resolution': 'summarize how hydra resolves runtime config group choices using the hydra runtime choices interpolation'}
```

