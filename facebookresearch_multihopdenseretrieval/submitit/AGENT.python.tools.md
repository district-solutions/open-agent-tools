# Agent Python Tools

- repo: facebookresearch/multihopdenseretrieval
- repo_uri: https://github.com/facebookresearch/multihop_dense_retrieval

## File: facebookresearch_multihopdenseretrieval/submitit/submitit_train.py

Prompts

```
['run a hyperparameter grid search that submits multiple training jobs via submitit and collects results', 'run the grid_parameters function to yield all combinations of parameters from a given grid dictionary', 'create a unique init file with a UUID name in the shared folder for distributed training', 'get the shared folder path used for storing experiment checkpoints and job outputs', 'review the grid_search function that launches training jobs with different hyperparameter configurations using submitit', 'run get_init_file to create a unique UUID-named init file in the shared folder for distributed training', 'run get_shared_folder to return the shared checkpoint path for multi-hop QA experiments', 'run the main entry point to parse training args and launch a grid search sweep']
```

Usage

```
{'run_grid_search': 'run a hyperparameter grid search that submits multiple training jobs via submitit and collects results', 'run_grid_parameters': 'run the grid_parameters function to yield all combinations of parameters from a given grid dictionary', 'create_init_file': 'create a unique init file with a UUID name in the shared folder for distributed training', 'get_shared_folder': 'get the shared folder path used for storing experiment checkpoints and job outputs', 'review_grid_search': 'review the grid_search function that launches training jobs with different hyperparameter configurations using submitit'}
```

## File: facebookresearch_multihopdenseretrieval/submitit/submitit_train_qa.py

Prompts

```
['run a hyperparameter grid search that submits multiple training jobs via submitit and collects results', 'run the grid_parameters function to yield all combinations of parameters from a given grid dictionary', 'create a unique init file with a UUID name in the shared folder for distributed training', 'get the shared folder path used for storing experiment checkpoints and job outputs', 'review the grid_search function that launches training jobs with different hyperparameter configurations using submitit', 'run get_init_file to create a unique UUID-named init file in the shared folder for distributed training', 'run get_shared_folder to return the shared checkpoint path for multi-hop QA experiments', 'run the main entry point to parse training args and launch a grid search sweep']
```

Usage

```
{'run_grid_search': 'run a hyperparameter grid search for QA training jobs using submitit on a SLURM cluster', 'run_grid_parameters': 'run the grid_parameters function to yield all combinations of parameters in a given grid dict', 'run_get_init_file': 'run get_init_file to create a unique UUID-named init file in the shared folder for distributed training', 'run_get_shared_folder': 'run get_shared_folder to return the shared checkpoint path for multi-hop QA experiments', 'run_main': 'run the main entry point to parse training args and launch a grid search sweep'}
```

