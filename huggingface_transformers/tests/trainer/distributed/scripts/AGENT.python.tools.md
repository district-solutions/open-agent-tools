# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/trainer/distributed/scripts/dispatch_batches.py

Prompts

```
['run training with dispatch_batches=False on a finite iterable dataset using Trainer', 'create a FiniteIterableDataset that yields items from a RegressionDataset with configurable parameters', 'build a RegressionModel with learnable parameters a and b for linear regression', 'test the Trainer with a finite iterable dataset and multiple label names', 'configure TrainingArguments with per_device_train_batch_size=1 and max_steps=1', 'test the fsdp_generate function that runs a GPT-2 model with FullyShardedDataParallel and generate', 'test the fsdp2_generate function that runs a GPT-2 model with FSDP2 composable API and generate', 'run the fsdp_generate.py script with --fsdp flag via torchrun to test FSDP generation', 'run the fsdp_generate.py script with --fsdp2 flag via torchrun to test FSDP2 generation', 'review the manage_process_group decorator that initializes and destroys a distributed process group', 'run distributed training with loss averaging and store losses to a JSON file', 'test loss averaging by running distributed training with and without average_tokens_across_devices', 'create a TrainerCallback that stores per-step loss values during training', 'test distributed training on a tiny Qwen2 model using wikitext dataset with 50 samples', 'run both averaging and non-averaging training modes in a single process launch', 'test gathering tensors from all GPUs and verifying all ranks see different random augmentations', 'test the DummyDataset class that generates random values using random, numpy, and torch', 'test the DummyModel class that gathers tensors from all GPUs and asserts they differ across ranks', 'test running distributed training with set_seed, Trainer, and dataloader_num_workers > 0']
```

Usage

```
{'run_train_dispatch_batches_false': 'run training with dispatch_batches=False on a finite iterable dataset using Trainer', 'create_finite_iterable_dataset': 'create a FiniteIterableDataset that yields items from a RegressionDataset with configurable parameters', 'build_regression_model': 'build a RegressionModel with learnable parameters a and b for linear regression', 'test_trainer_with_iterable_dataset': 'test the Trainer with a finite iterable dataset and multiple label names', 'configure_training_args': 'configure TrainingArguments with per_device_train_batch_size=1 and max_steps=1'}
```

## File: huggingface_transformers/tests/trainer/distributed/scripts/fsdp_generate.py

Prompts

```
['run training with dispatch_batches=False on a finite iterable dataset using Trainer', 'create a FiniteIterableDataset that yields items from a RegressionDataset with configurable parameters', 'build a RegressionModel with learnable parameters a and b for linear regression', 'test the Trainer with a finite iterable dataset and multiple label names', 'configure TrainingArguments with per_device_train_batch_size=1 and max_steps=1', 'test the fsdp_generate function that runs a GPT-2 model with FullyShardedDataParallel and generate', 'test the fsdp2_generate function that runs a GPT-2 model with FSDP2 composable API and generate', 'run the fsdp_generate.py script with --fsdp flag via torchrun to test FSDP generation', 'run the fsdp_generate.py script with --fsdp2 flag via torchrun to test FSDP2 generation', 'review the manage_process_group decorator that initializes and destroys a distributed process group', 'run distributed training with loss averaging and store losses to a JSON file', 'test loss averaging by running distributed training with and without average_tokens_across_devices', 'create a TrainerCallback that stores per-step loss values during training', 'test distributed training on a tiny Qwen2 model using wikitext dataset with 50 samples', 'run both averaging and non-averaging training modes in a single process launch', 'test gathering tensors from all GPUs and verifying all ranks see different random augmentations', 'test the DummyDataset class that generates random values using random, numpy, and torch', 'test the DummyModel class that gathers tensors from all GPUs and asserts they differ across ranks', 'test running distributed training with set_seed, Trainer, and dataloader_num_workers > 0']
```

Usage

```
{'test_fsdp_generate': 'test the fsdp_generate function that runs a GPT-2 model with FullyShardedDataParallel and generate', 'test_fsdp2_generate': 'test the fsdp2_generate function that runs a GPT-2 model with FSDP2 composable API and generate', 'run_fsdp_generate_cli': 'run the fsdp_generate.py script with --fsdp flag via torchrun to test FSDP generation', 'run_fsdp2_generate_cli': 'run the fsdp_generate.py script with --fsdp2 flag via torchrun to test FSDP2 generation', 'review_manage_process_group': 'review the manage_process_group decorator that initializes and destroys a distributed process group'}
```

## File: huggingface_transformers/tests/trainer/distributed/scripts/loss_averaging.py

Prompts

```
['run training with dispatch_batches=False on a finite iterable dataset using Trainer', 'create a FiniteIterableDataset that yields items from a RegressionDataset with configurable parameters', 'build a RegressionModel with learnable parameters a and b for linear regression', 'test the Trainer with a finite iterable dataset and multiple label names', 'configure TrainingArguments with per_device_train_batch_size=1 and max_steps=1', 'test the fsdp_generate function that runs a GPT-2 model with FullyShardedDataParallel and generate', 'test the fsdp2_generate function that runs a GPT-2 model with FSDP2 composable API and generate', 'run the fsdp_generate.py script with --fsdp flag via torchrun to test FSDP generation', 'run the fsdp_generate.py script with --fsdp2 flag via torchrun to test FSDP2 generation', 'review the manage_process_group decorator that initializes and destroys a distributed process group', 'run distributed training with loss averaging and store losses to a JSON file', 'test loss averaging by running distributed training with and without average_tokens_across_devices', 'create a TrainerCallback that stores per-step loss values during training', 'test distributed training on a tiny Qwen2 model using wikitext dataset with 50 samples', 'run both averaging and non-averaging training modes in a single process launch', 'test gathering tensors from all GPUs and verifying all ranks see different random augmentations', 'test the DummyDataset class that generates random values using random, numpy, and torch', 'test the DummyModel class that gathers tensors from all GPUs and asserts they differ across ranks', 'test running distributed training with set_seed, Trainer, and dataloader_num_workers > 0']
```

Usage

```
{'run_distributed_training': 'run distributed training with loss averaging and store losses to a JSON file', 'test_loss_averaging': 'test loss averaging by running distributed training with and without average_tokens_across_devices', 'create_StoreLossCallback': 'create a TrainerCallback that stores per-step loss values during training', 'test_distributed_training': 'test distributed training on a tiny Qwen2 model using wikitext dataset with 50 samples', 'run_both_averaging_modes': 'run both averaging and non-averaging training modes in a single process launch'}
```

## File: huggingface_transformers/tests/trainer/distributed/scripts/worker_seed.py

Prompts

```
['run training with dispatch_batches=False on a finite iterable dataset using Trainer', 'create a FiniteIterableDataset that yields items from a RegressionDataset with configurable parameters', 'build a RegressionModel with learnable parameters a and b for linear regression', 'test the Trainer with a finite iterable dataset and multiple label names', 'configure TrainingArguments with per_device_train_batch_size=1 and max_steps=1', 'test the fsdp_generate function that runs a GPT-2 model with FullyShardedDataParallel and generate', 'test the fsdp2_generate function that runs a GPT-2 model with FSDP2 composable API and generate', 'run the fsdp_generate.py script with --fsdp flag via torchrun to test FSDP generation', 'run the fsdp_generate.py script with --fsdp2 flag via torchrun to test FSDP2 generation', 'review the manage_process_group decorator that initializes and destroys a distributed process group', 'run distributed training with loss averaging and store losses to a JSON file', 'test loss averaging by running distributed training with and without average_tokens_across_devices', 'create a TrainerCallback that stores per-step loss values during training', 'test distributed training on a tiny Qwen2 model using wikitext dataset with 50 samples', 'run both averaging and non-averaging training modes in a single process launch', 'test gathering tensors from all GPUs and verifying all ranks see different random augmentations', 'test the DummyDataset class that generates random values using random, numpy, and torch', 'test the DummyModel class that gathers tensors from all GPUs and asserts they differ across ranks', 'test running distributed training with set_seed, Trainer, and dataloader_num_workers > 0']
```

Usage

```
{'run_distributed_training': 'run distributed training with dataloader worker seed divergence tests across multiple GPUs', 'test_gather_from_all_gpus': 'test gathering tensors from all GPUs and verifying all ranks see different random augmentations', 'test_DummyDataset': 'test the DummyDataset class that generates random values using random, numpy, and torch', 'test_DummyModel': 'test the DummyModel class that gathers tensors from all GPUs and asserts they differ across ranks', 'test_run_distributed_training': 'test running distributed training with set_seed, Trainer, and dataloader_num_workers > 0'}
```

