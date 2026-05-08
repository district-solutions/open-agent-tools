# Agent Python Tools

- repo: facebookresearch/ram
- repo_uri: https://github.com/facebookresearch/ram

## File: facebookresearch_ram/projects/cope/src/main.py

Prompts

```
['run the COPE model training loop with configurable epochs, evaluation splits, and checkpointing', 'evaluate the COPE model on validation, test, or training data splits', 'interactively display generated model output samples from the validation set', 'initialize logging, distributed training, data loaders, model, and trainer from config', 'register COPE training CLI arguments including eval, seed, display, and distributed options', 'build a Trainer instance with a PyTorch model, logger, tokenizer, and config namespace', 'run the training loop on a data loader with optional eval-only mode and split name', 'run the evaluation loop on a validation data loader with no gradient computation', 'run text generation on a batch to produce answer tokens from context and question', 'review the early stopping logic based on validation metric patience and distributed broadcast']
```

Usage

```
{'train_model': 'run the COPE model training loop with configurable epochs, evaluation splits, and checkpointing', 'eval_model': 'evaluate the COPE model on validation, test, or training data splits', 'display_model_output': 'interactively display generated model output samples from the validation set', 'setup_training_environment': 'initialize logging, distributed training, data loaders, model, and trainer from config', 'add_train_args_parser': 'register COPE training CLI arguments including eval, seed, display, and distributed options'}
```

## File: facebookresearch_ram/projects/cope/src/trainer.py

Prompts

```
['run the COPE model training loop with configurable epochs, evaluation splits, and checkpointing', 'evaluate the COPE model on validation, test, or training data splits', 'interactively display generated model output samples from the validation set', 'initialize logging, distributed training, data loaders, model, and trainer from config', 'register COPE training CLI arguments including eval, seed, display, and distributed options', 'build a Trainer instance with a PyTorch model, logger, tokenizer, and config namespace', 'run the training loop on a data loader with optional eval-only mode and split name', 'run the evaluation loop on a validation data loader with no gradient computation', 'run text generation on a batch to produce answer tokens from context and question', 'review the early stopping logic based on validation metric patience and distributed broadcast']
```

Usage

```
{'build_Trainer': 'build a Trainer instance with a PyTorch model, logger, tokenizer, and config namespace', 'run_Trainer_train': 'run the training loop on a data loader with optional eval-only mode and split name', 'run_Trainer_eval': 'run the evaluation loop on a validation data loader with no gradient computation', 'run_Trainer_generate': 'run text generation on a batch to produce answer tokens from context and question', 'review_Trainer_is_stopping_criteria': 'review the early stopping logic based on validation metric patience and distributed broadcast'}
```

