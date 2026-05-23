# Agent Python Tools

- repo: facebookresearch/tava
- repo_uri: https://github.com/facebookresearch/tava

## File: facebookresearch_tava/tava/engines/abstract.py

Prompts

```
['build a subclass of AbstractEngine that implements build_model and build_dataset methods', 'implement the build_model abstract method to return a model and optimizer tuple', 'implement the build_dataset abstract method to return a dataset and metadata tuple', 'resume training from a checkpoint directory using the resume_from_ckpt utility function', 'initialize an AbstractEngine subclass with local_rank, world_size, and a DictConfig', 'build an Evaluator engine that instantiates a model from config and sets it to eval mode', 'build an Evaluator engine that creates datasets for each evaluation split with pose metadata', 'run the Evaluator engine to evaluate a model across all configured evaluation splits', 'review the Evaluator _preprocess method that moves data tensors and pose info to GPU', 'refactor the Evaluator run method to support custom metric logging or distributed sync logic', 'run the Trainer training loop with configurable max steps, evaluation, and checkpointing', 'build a model and Adam optimizer from the Hydra config using Trainer.build_model', 'build train and eval datasets with pose metadata using Trainer.build_dataset', 'run a single training step with coarse and fine loss computation and backpropagation', 'review the Trainer._preprocess method that moves data to GPU and loads bone pose metadata', 'run the Trainer engine to execute the full training loop with logging and checkpointing', 'build the model and Adam optimizer from config with deterministic seeding for multi-GPU', 'build train and eval datasets from config using Hydra instantiate for each split', 'execute a single training step computing MSE loss and PSNR for coarse and fine predictions', 'review the Trainer run method to understand the training loop, evaluation, and checkpointing logic']
```

Usage

```
{'build_engine_subclass': 'build a subclass of AbstractEngine that implements build_model and build_dataset methods', 'implement_build_model': 'implement the build_model abstract method to return a model and optimizer tuple', 'implement_build_dataset': 'implement the build_dataset abstract method to return a dataset and metadata tuple', 'resume_training_from_ckpt': 'resume training from a checkpoint directory using the resume_from_ckpt utility function', 'initialize_abstract_engine': 'initialize an AbstractEngine subclass with local_rank, world_size, and a DictConfig'}
```

## File: facebookresearch_tava/tava/engines/evaluator.py

Prompts

```
['build a subclass of AbstractEngine that implements build_model and build_dataset methods', 'implement the build_model abstract method to return a model and optimizer tuple', 'implement the build_dataset abstract method to return a dataset and metadata tuple', 'resume training from a checkpoint directory using the resume_from_ckpt utility function', 'initialize an AbstractEngine subclass with local_rank, world_size, and a DictConfig', 'build an Evaluator engine that instantiates a model from config and sets it to eval mode', 'build an Evaluator engine that creates datasets for each evaluation split with pose metadata', 'run the Evaluator engine to evaluate a model across all configured evaluation splits', 'review the Evaluator _preprocess method that moves data tensors and pose info to GPU', 'refactor the Evaluator run method to support custom metric logging or distributed sync logic', 'run the Trainer training loop with configurable max steps, evaluation, and checkpointing', 'build a model and Adam optimizer from the Hydra config using Trainer.build_model', 'build train and eval datasets with pose metadata using Trainer.build_dataset', 'run a single training step with coarse and fine loss computation and backpropagation', 'review the Trainer._preprocess method that moves data to GPU and loads bone pose metadata', 'run the Trainer engine to execute the full training loop with logging and checkpointing', 'build the model and Adam optimizer from config with deterministic seeding for multi-GPU', 'build train and eval datasets from config using Hydra instantiate for each split', 'execute a single training step computing MSE loss and PSNR for coarse and fine predictions', 'review the Trainer run method to understand the training loop, evaluation, and checkpointing logic']
```

Usage

```
{'build_evaluator_model': 'build an Evaluator engine that instantiates a model from config and sets it to eval mode', 'build_evaluator_dataset': 'build an Evaluator engine that creates datasets for each evaluation split with pose metadata', 'run_evaluator': 'run the Evaluator engine to evaluate a model across all configured evaluation splits', 'review_Evaluator_preprocess': 'review the Evaluator _preprocess method that moves data tensors and pose info to GPU', 'refactor_Evaluator_run': 'refactor the Evaluator run method to support custom metric logging or distributed sync logic'}
```

## File: facebookresearch_tava/tava/engines/trainer.py

Prompts

```
['build a subclass of AbstractEngine that implements build_model and build_dataset methods', 'implement the build_model abstract method to return a model and optimizer tuple', 'implement the build_dataset abstract method to return a dataset and metadata tuple', 'resume training from a checkpoint directory using the resume_from_ckpt utility function', 'initialize an AbstractEngine subclass with local_rank, world_size, and a DictConfig', 'build an Evaluator engine that instantiates a model from config and sets it to eval mode', 'build an Evaluator engine that creates datasets for each evaluation split with pose metadata', 'run the Evaluator engine to evaluate a model across all configured evaluation splits', 'review the Evaluator _preprocess method that moves data tensors and pose info to GPU', 'refactor the Evaluator run method to support custom metric logging or distributed sync logic', 'run the Trainer training loop with configurable max steps, evaluation, and checkpointing', 'build a model and Adam optimizer from the Hydra config using Trainer.build_model', 'build train and eval datasets with pose metadata using Trainer.build_dataset', 'run a single training step with coarse and fine loss computation and backpropagation', 'review the Trainer._preprocess method that moves data to GPU and loads bone pose metadata', 'run the Trainer engine to execute the full training loop with logging and checkpointing', 'build the model and Adam optimizer from config with deterministic seeding for multi-GPU', 'build train and eval datasets from config using Hydra instantiate for each split', 'execute a single training step computing MSE loss and PSNR for coarse and fine predictions', 'review the Trainer run method to understand the training loop, evaluation, and checkpointing logic']
```

Usage

```
{'run_Trainer_training_loop': 'run the Trainer training loop with configurable max steps, evaluation, and checkpointing', 'build_Trainer_model': 'build a model and Adam optimizer from the Hydra config using Trainer.build_model', 'build_Trainer_dataset': 'build train and eval datasets with pose metadata using Trainer.build_dataset', 'run_Trainer_train_step': 'run a single training step with coarse and fine loss computation and backpropagation', 'review_Trainer_preprocess': 'review the Trainer._preprocess method that moves data to GPU and loads bone pose metadata'}
```

## File: facebookresearch_tava/tava/engines/trainer_static.py

Prompts

```
['build a subclass of AbstractEngine that implements build_model and build_dataset methods', 'implement the build_model abstract method to return a model and optimizer tuple', 'implement the build_dataset abstract method to return a dataset and metadata tuple', 'resume training from a checkpoint directory using the resume_from_ckpt utility function', 'initialize an AbstractEngine subclass with local_rank, world_size, and a DictConfig', 'build an Evaluator engine that instantiates a model from config and sets it to eval mode', 'build an Evaluator engine that creates datasets for each evaluation split with pose metadata', 'run the Evaluator engine to evaluate a model across all configured evaluation splits', 'review the Evaluator _preprocess method that moves data tensors and pose info to GPU', 'refactor the Evaluator run method to support custom metric logging or distributed sync logic', 'run the Trainer training loop with configurable max steps, evaluation, and checkpointing', 'build a model and Adam optimizer from the Hydra config using Trainer.build_model', 'build train and eval datasets with pose metadata using Trainer.build_dataset', 'run a single training step with coarse and fine loss computation and backpropagation', 'review the Trainer._preprocess method that moves data to GPU and loads bone pose metadata', 'run the Trainer engine to execute the full training loop with logging and checkpointing', 'build the model and Adam optimizer from config with deterministic seeding for multi-GPU', 'build train and eval datasets from config using Hydra instantiate for each split', 'execute a single training step computing MSE loss and PSNR for coarse and fine predictions', 'review the Trainer run method to understand the training loop, evaluation, and checkpointing logic']
```

Usage

```
{'run_Trainer': 'run the Trainer engine to execute the full training loop with logging and checkpointing', 'build_model_Trainer': 'build the model and Adam optimizer from config with deterministic seeding for multi-GPU', 'build_dataset_Trainer': 'build train and eval datasets from config using Hydra instantiate for each split', 'train_step_Trainer': 'execute a single training step computing MSE loss and PSNR for coarse and fine predictions', 'review_Trainer_run': 'review the Trainer run method to understand the training loop, evaluation, and checkpointing logic'}
```

