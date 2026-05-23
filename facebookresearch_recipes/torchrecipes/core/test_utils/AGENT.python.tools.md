# Agent Python Tools

- repo: facebookresearch/recipes
- repo_uri: https://github.com/facebookresearch/recipes

## File: facebookresearch_recipes/torchrecipes/core/test_utils/conf_utils.py

Prompts

```
['convert a dataclass object to a dictionary using conf_asdict instead of dataclasses.asdict', 'use conf_asdict to convert a dataclass to a dict and remove the Hydra _target_ field', 'test the conf_asdict function with a dataclass that contains a _target_ field', 'review the conf_asdict function to understand how it strips Hydra specific fields from dataclasses', 'refactor conf_asdict to also remove additional Hydra specific fields beyond _target_', 'create a mock trainer params wrapper that disables logger and checkpointing for unit tests', 'test a BaseTrainApp subclass by inheriting from BaseTrainAppTestCase and using mock_trainer_params', 'create a BaseTrainApp instance from a Hydra config module and config name with optional overrides', 'assert a TrainOutput is not None and has no tensorboard log directory set', 'refactor get_mock_init_trainer_params to add custom default overrides for fast_dev_run or checkpointing']
```

Usage

```
{'conf_asdict_convert_dataclass': 'convert a dataclass object to a dictionary using conf_asdict instead of dataclasses.asdict', 'conf_asdict_remove_hydra_target': 'use conf_asdict to convert a dataclass to a dict and remove the Hydra _target_ field', 'test_conf_asdict': 'test the conf_asdict function with a dataclass that contains a _target_ field', 'review_conf_asdict': 'review the conf_asdict function to understand how it strips Hydra specific fields from dataclasses', 'refactor_conf_asdict': 'refactor conf_asdict to also remove additional Hydra specific fields beyond _target_'}
```

## File: facebookresearch_recipes/torchrecipes/core/test_utils/test_base.py

Prompts

```
['convert a dataclass object to a dictionary using conf_asdict instead of dataclasses.asdict', 'use conf_asdict to convert a dataclass to a dict and remove the Hydra _target_ field', 'test the conf_asdict function with a dataclass that contains a _target_ field', 'review the conf_asdict function to understand how it strips Hydra specific fields from dataclasses', 'refactor conf_asdict to also remove additional Hydra specific fields beyond _target_', 'create a mock trainer params wrapper that disables logger and checkpointing for unit tests', 'test a BaseTrainApp subclass by inheriting from BaseTrainAppTestCase and using mock_trainer_params', 'create a BaseTrainApp instance from a Hydra config module and config name with optional overrides', 'assert a TrainOutput is not None and has no tensorboard log directory set', 'refactor get_mock_init_trainer_params to add custom default overrides for fast_dev_run or checkpointing']
```

Usage

```
{'create_mock_trainer_params': 'create a mock trainer params wrapper that disables logger and checkpointing for unit tests', 'test_BaseTrainAppTestCase': 'test a BaseTrainApp subclass by inheriting from BaseTrainAppTestCase and using mock_trainer_params', 'create_app_from_hydra': 'create a BaseTrainApp instance from a Hydra config module and config name with optional overrides', 'assert_train_output': 'assert a TrainOutput is not None and has no tensorboard log directory set', 'refactor_get_mock_init_trainer_params': 'refactor get_mock_init_trainer_params to add custom default overrides for fast_dev_run or checkpointing'}
```

