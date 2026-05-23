# Agent Python Tools

- repo: facebookresearch/salina
- repo_uri: https://github.com/facebookresearch/salina

## File: facebookresearch_salina/salina_cl/core.py

Prompts

```
['create a Task instance with an env agent config dict and task id for RL training', 'build a Framework model with a seed and params dict to train and evaluate on tasks', 'train a Framework on a Task by calling train() with a logger to log metrics', 'evaluate a Framework on a list of test Tasks and return avg reward metrics', 'create a CRLAgent subclass with set_task and add_regularizer methods for continual RL', 'create a WandbLogger instance to initialize wandb tracking for a project with configurable tags and verbosity', 'save hyperparameters to wandb config by calling save_hps on a WandbLogger instance', 'log scalar metrics to wandb using add_scalar with a name, value, and iteration number', 'log HTML content to wandb by calling add_html on a WandbLogger instance', 'recursively convert a DictConfig or nested dict to a plain Python dict using _to_dict']
```

Usage

```
{'create_Task': 'create a Task instance with an env agent config dict and task id for RL training', 'build_Framework': 'build a Framework model with a seed and params dict to train and evaluate on tasks', 'train_Framework': 'train a Framework on a Task by calling train() with a logger to log metrics', 'evaluate_Framework': 'evaluate a Framework on a list of test Tasks and return avg reward metrics', 'create_CRLAgent': 'create a CRLAgent subclass with set_task and add_regularizer methods for continual RL'}
```

## File: facebookresearch_salina/salina_cl/logger.py

Prompts

```
['create a Task instance with an env agent config dict and task id for RL training', 'build a Framework model with a seed and params dict to train and evaluate on tasks', 'train a Framework on a Task by calling train() with a logger to log metrics', 'evaluate a Framework on a list of test Tasks and return avg reward metrics', 'create a CRLAgent subclass with set_task and add_regularizer methods for continual RL', 'create a WandbLogger instance to initialize wandb tracking for a project with configurable tags and verbosity', 'save hyperparameters to wandb config by calling save_hps on a WandbLogger instance', 'log scalar metrics to wandb using add_scalar with a name, value, and iteration number', 'log HTML content to wandb by calling add_html on a WandbLogger instance', 'recursively convert a DictConfig or nested dict to a plain Python dict using _to_dict']
```

Usage

```
{'create_wandb_logger': 'create a WandbLogger instance to initialize wandb tracking for a project with configurable tags and verbosity', 'save_hyperparameters': 'save hyperparameters to wandb config by calling save_hps on a WandbLogger instance', 'log_scalar_values': 'log scalar metrics to wandb using add_scalar with a name, value, and iteration number', 'log_html_content': 'log HTML content to wandb by calling add_html on a WandbLogger instance', 'convert_to_dict': 'recursively convert a DictConfig or nested dict to a plain Python dict using _to_dict'}
```

