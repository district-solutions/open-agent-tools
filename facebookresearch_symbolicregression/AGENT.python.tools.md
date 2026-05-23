# Agent Python Tools

- repo: facebookresearch/symbolicregression
- repo_uri: https://github.com/facebookresearch/symbolicregression

## File: facebookresearch_symbolicregression/evaluate.py

Prompts

```
['run the symbolic regression evaluator on PMMLB datasets with configurable noise and random state', 'run in-domain evaluation on symbolic regression model with beam search and SymPy verification', 'read a CSV or gzipped CSV file and return features, targets, and feature names as numpy arrays', 'evaluate the symbolic regression model on PMMLB regression datasets with optional filtering and noise injection', 'create an Evaluator instance from a Trainer to access model modules and evaluation methods', 'build an argparse parser for symbolic regression function prediction experiments with model and training parameters', 'configure transformer encoder and decoder embedding dimensions, layer counts, and attention heads via parser arguments', 'set beam search decoding parameters including beam size, temperature, length penalty, and early stopping', 'configure evaluation metrics like r2, accuracy thresholds, and complexity for symbolic regression model validation', 'setup multi-GPU multi-node distributed training arguments with SLURM debug, local rank, and master port', 'run multinode symbolic regression training jobs on a Slurm cluster using submitit', 'submit a grid search of hyperparameter combinations as Slurm jobs via submitit AutoExecutor', 'create a Trainer class that wraps training args and handles GPU setup and checkpointing', 'setup GPU rank, world size, and job directory from submitit JobEnvironment in Trainer', 'checkpoint the Trainer and requeue it as a DelayedSubmission for fault tolerance']
```

Usage

```
{'run_symbolic_regression_evaluation': 'run the symbolic regression evaluator on PMMLB datasets with configurable noise and random state', 'run_in_domain_evaluation': 'run in-domain evaluation on symbolic regression model with beam search and SymPy verification', 'read_csv_dataset': 'read a CSV or gzipped CSV file and return features, targets, and feature names as numpy arrays', 'evaluate_pmlb_datasets': 'evaluate the symbolic regression model on PMMLB regression datasets with optional filtering and noise injection', 'create_evaluator_instance': 'create an Evaluator instance from a Trainer to access model modules and evaluation methods'}
```

## File: facebookresearch_symbolicregression/parsers.py

Prompts

```
['run the symbolic regression evaluator on PMMLB datasets with configurable noise and random state', 'run in-domain evaluation on symbolic regression model with beam search and SymPy verification', 'read a CSV or gzipped CSV file and return features, targets, and feature names as numpy arrays', 'evaluate the symbolic regression model on PMMLB regression datasets with optional filtering and noise injection', 'create an Evaluator instance from a Trainer to access model modules and evaluation methods', 'build an argparse parser for symbolic regression function prediction experiments with model and training parameters', 'configure transformer encoder and decoder embedding dimensions, layer counts, and attention heads via parser arguments', 'set beam search decoding parameters including beam size, temperature, length penalty, and early stopping', 'configure evaluation metrics like r2, accuracy thresholds, and complexity for symbolic regression model validation', 'setup multi-GPU multi-node distributed training arguments with SLURM debug, local rank, and master port', 'run multinode symbolic regression training jobs on a Slurm cluster using submitit', 'submit a grid search of hyperparameter combinations as Slurm jobs via submitit AutoExecutor', 'create a Trainer class that wraps training args and handles GPU setup and checkpointing', 'setup GPU rank, world size, and job directory from submitit JobEnvironment in Trainer', 'checkpoint the Trainer and requeue it as a DelayedSubmission for fault tolerance']
```

Usage

```
{'build_parser_symbolic_regression': 'build an argparse parser for symbolic regression function prediction experiments with model and training parameters', 'configure_transformer_model_args': 'configure transformer encoder and decoder embedding dimensions, layer counts, and attention heads via parser arguments', 'set_beam_search_decoding': 'set beam search decoding parameters including beam size, temperature, length penalty, and early stopping', 'configure_evaluation_metrics': 'configure evaluation metrics like r2, accuracy thresholds, and complexity for symbolic regression model validation', 'setup_distributed_training_args': 'setup multi-GPU multi-node distributed training arguments with SLURM debug, local rank, and master port'}
```

## File: facebookresearch_symbolicregression/submitit.py

Prompts

```
['run the symbolic regression evaluator on PMMLB datasets with configurable noise and random state', 'run in-domain evaluation on symbolic regression model with beam search and SymPy verification', 'read a CSV or gzipped CSV file and return features, targets, and feature names as numpy arrays', 'evaluate the symbolic regression model on PMMLB regression datasets with optional filtering and noise injection', 'create an Evaluator instance from a Trainer to access model modules and evaluation methods', 'build an argparse parser for symbolic regression function prediction experiments with model and training parameters', 'configure transformer encoder and decoder embedding dimensions, layer counts, and attention heads via parser arguments', 'set beam search decoding parameters including beam size, temperature, length penalty, and early stopping', 'configure evaluation metrics like r2, accuracy thresholds, and complexity for symbolic regression model validation', 'setup multi-GPU multi-node distributed training arguments with SLURM debug, local rank, and master port', 'run multinode symbolic regression training jobs on a Slurm cluster using submitit', 'submit a grid search of hyperparameter combinations as Slurm jobs via submitit AutoExecutor', 'create a Trainer class that wraps training args and handles GPU setup and checkpointing', 'setup GPU rank, world size, and job directory from submitit JobEnvironment in Trainer', 'checkpoint the Trainer and requeue it as a DelayedSubmission for fault tolerance']
```

Usage

```
{'run_multinode_training': 'run multinode symbolic regression training jobs on a Slurm cluster using submitit', 'submit_grid_search_jobs': 'submit a grid search of hyperparameter combinations as Slurm jobs via submitit AutoExecutor', 'create_Trainer_class': 'create a Trainer class that wraps training args and handles GPU setup and checkpointing', 'setup_gpu_args': 'setup GPU rank, world size, and job directory from submitit JobEnvironment in Trainer', 'checkpoint_and_requeue': 'checkpoint the Trainer and requeue it as a DelayedSubmission for fault tolerance'}
```

