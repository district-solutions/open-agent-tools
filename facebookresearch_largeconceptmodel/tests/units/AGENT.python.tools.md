# Agent Python Tools

- repo: facebookresearch/largeconceptmodel
- repo_uri: https://github.com/facebookresearch/large_concept_model

## File: facebookresearch_largeconceptmodel/tests/units/conftest.py

Prompts

```
['create a PyArrow table with 1000 rows containing cat, id, seq, and text columns', 'mock the distributed process group init to return a FakeGang for unit testing', 'mock the gang getter to return a FakeGang instead of a real distributed gang', 'apply monkeypatches to disable logging, env setup, and MKL threading in LCM unit tests', 'create DataLoadingConfig and ParquetDatasetConfig fixtures for testing LCM dataset loading pipelines', 'test the training recipes to ensure they are synced with trainer signatures and configs', 'find and yield evaluation recipe config file stems from the recipes/eval/lcm directory', 'run the test_train_recipes function with a specific recipe name like pretrain/two_tower', 'review the KEY_TRAINING_RECIPES list of pretrain and finetune recipe config names', 'refactor test_train_recipes to handle additional error types or recipe configurations']
```

Usage

```
{'create_simple_table': 'create a PyArrow table with 1000 rows containing cat, id, seq, and text columns', 'mock_init_process_group': 'mock the distributed process group init to return a FakeGang for unit testing', 'mock_get_gang': 'mock the gang getter to return a FakeGang instead of a real distributed gang', 'setup_patches_fixture': 'apply monkeypatches to disable logging, env setup, and MKL threading in LCM unit tests', 'create_simple_data_config': 'create DataLoadingConfig and ParquetDatasetConfig fixtures for testing LCM dataset loading pipelines'}
```

## File: facebookresearch_largeconceptmodel/tests/units/test_recipes.py

Prompts

```
['create a PyArrow table with 1000 rows containing cat, id, seq, and text columns', 'mock the distributed process group init to return a FakeGang for unit testing', 'mock the gang getter to return a FakeGang instead of a real distributed gang', 'apply monkeypatches to disable logging, env setup, and MKL threading in LCM unit tests', 'create DataLoadingConfig and ParquetDatasetConfig fixtures for testing LCM dataset loading pipelines', 'test the training recipes to ensure they are synced with trainer signatures and configs', 'find and yield evaluation recipe config file stems from the recipes/eval/lcm directory', 'run the test_train_recipes function with a specific recipe name like pretrain/two_tower', 'review the KEY_TRAINING_RECIPES list of pretrain and finetune recipe config names', 'refactor test_train_recipes to handle additional error types or recipe configurations']
```

Usage

```
{'test_train_recipes': 'test the training recipes to ensure they are synced with trainer signatures and configs', 'find_eval_recipes': 'find and yield evaluation recipe config file stems from the recipes/eval/lcm directory', 'run_test_train_recipes_with_param': 'run the test_train_recipes function with a specific recipe name like pretrain/two_tower', 'review_KEY_TRAINING_RECIPES': 'review the KEY_TRAINING_RECIPES list of pretrain and finetune recipe config names', 'refactor_test_train_recipes': 'refactor test_train_recipes to handle additional error types or recipe configurations'}
```

