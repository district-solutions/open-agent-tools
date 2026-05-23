# Agent Python Tools

- repo: facebookresearch/recipes
- repo_uri: https://github.com/facebookresearch/recipes

## File: facebookresearch_recipes/torchrecipes/launcher/run.py

Prompts

```
['run a PyTorch Lightning train app using hydra config and the CONFIG_MODULE environment variable', 'run a BaseTrainApp in train, test, predict, or prod mode based on the MODE environment variable', 'fetch the current operating mode from the MODE environment variable and return a Mode enum', 'instantiate a BaseTrainApp from a hydra TrainAppConf config using hydra.utils.instantiate', 'run a BaseTrainApp in prod mode that trains the model and then runs tests']
```

Usage

```
{'run_train_app_with_hydra': 'run a PyTorch Lightning train app using hydra config and the CONFIG_MODULE environment variable', 'run_in_certain_mode': 'run a BaseTrainApp in train, test, predict, or prod mode based on the MODE environment variable', 'get_mode_from_env': 'fetch the current operating mode from the MODE environment variable and return a Mode enum', 'instantiate_train_app_from_cfg': 'instantiate a BaseTrainApp from a hydra TrainAppConf config using hydra.utils.instantiate', 'run_train_and_test': 'run a BaseTrainApp in prod mode that trains the model and then runs tests'}
```

