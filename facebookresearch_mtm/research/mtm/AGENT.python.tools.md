# Agent Python Tools

- repo: facebookresearch/mtm
- repo_uri: https://github.com/facebookresearch/mtm

## File: facebookresearch_mtm/research/mtm/distributed_utils.py

Prompts

```
['get distributed training parameters from submitit or environment variables', 'create a DistributedParams dataclass with rank, world_size, master_addr, and master_port fields', 'review the DistributedParams dataclass fields for rank, local_rank, world_size, and master_addr', 'summarize the get_distributed_params function that loads job info from submitit or env vars', 'test the get_distributed_params function to verify it falls back to defaults when no env is set', 'create a random binary mask tensor for a given trajectory length and mask ratio', 'create a full random mask tensor across trajectory length and data dimensions', 'create goal-reaching masks that expose start, end, and a random middle state', 'create an inverse dynamics mask that exposes all states but no actions', 'create autoregressive masks with random masking across states, returns, and actions', 'train a MTM model on a dataset using Hydra config with distributed training support', 'evaluate the MTM model on forward dynamics task by predicting next states from actions', 'evaluate the MTM model on inverse dynamics task by predicting actions from states', 'create evaluation logs with visualization plots for states actions and images using mask patterns', 'configure and launch a MTM training job with Hydra config including wandb logging and checkpointing', 'run the MTM policy training script with Hydra config to train a model on a dataset', 'train one batch by encoding data, computing loss, backpropagating, and updating optimizer and scheduler', 'configure training hyperparameters like batch size, learning rate, warmup steps, and trajectory length', 'resume training from a saved checkpoint by loading model and optimizer state dicts', 'evaluate the trained model on a validation dataset and log metrics to Weights and Biases', 'load a Hydra config from a path and convert mask indices to mask pattern names', 'get the checkpoint path with the highest step number from a folder of PyTorch checkpoint files', 'compute an MD5 hash of a Hydra config object serialized to YAML', 'get the current Git commit SHA hash from the repository', 'set a random seed across PyTorch, CUDA, NumPy, and Python random modules']
```

Usage

```
{'get_distributed_params': 'get distributed training parameters from submitit or environment variables', 'create_DistributedParams': 'create a DistributedParams dataclass with rank, world_size, master_addr, and master_port fields', 'review_DistributedParams': 'review the DistributedParams dataclass fields for rank, local_rank, world_size, and master_addr', 'summarize_get_distributed_params': 'summarize the get_distributed_params function that loads job info from submitit or env vars', 'test_get_distributed_params': 'test the get_distributed_params function to verify it falls back to defaults when no env is set'}
```

## File: facebookresearch_mtm/research/mtm/masks.py

Prompts

```
['get distributed training parameters from submitit or environment variables', 'create a DistributedParams dataclass with rank, world_size, master_addr, and master_port fields', 'review the DistributedParams dataclass fields for rank, local_rank, world_size, and master_addr', 'summarize the get_distributed_params function that loads job info from submitit or env vars', 'test the get_distributed_params function to verify it falls back to defaults when no env is set', 'create a random binary mask tensor for a given trajectory length and mask ratio', 'create a full random mask tensor across trajectory length and data dimensions', 'create goal-reaching masks that expose start, end, and a random middle state', 'create an inverse dynamics mask that exposes all states but no actions', 'create autoregressive masks with random masking across states, returns, and actions', 'train a MTM model on a dataset using Hydra config with distributed training support', 'evaluate the MTM model on forward dynamics task by predicting next states from actions', 'evaluate the MTM model on inverse dynamics task by predicting actions from states', 'create evaluation logs with visualization plots for states actions and images using mask patterns', 'configure and launch a MTM training job with Hydra config including wandb logging and checkpointing', 'run the MTM policy training script with Hydra config to train a model on a dataset', 'train one batch by encoding data, computing loss, backpropagating, and updating optimizer and scheduler', 'configure training hyperparameters like batch size, learning rate, warmup steps, and trajectory length', 'resume training from a saved checkpoint by loading model and optimizer state dicts', 'evaluate the trained model on a validation dataset and log metrics to Weights and Biases', 'load a Hydra config from a path and convert mask indices to mask pattern names', 'get the checkpoint path with the highest step number from a folder of PyTorch checkpoint files', 'compute an MD5 hash of a Hydra config object serialized to YAML', 'get the current Git commit SHA hash from the repository', 'set a random seed across PyTorch, CUDA, NumPy, and Python random modules']
```

Usage

```
{'create_random_mask': 'create a random binary mask tensor for a given trajectory length and mask ratio', 'create_full_random_mask': 'create a full random mask tensor across trajectory length and data dimensions', 'create_goal_reaching_masks': 'create goal-reaching masks that expose start, end, and a random middle state', 'create_inverse_dynamics_mask': 'create an inverse dynamics mask that exposes all states but no actions', 'create_random_autoregressize_mask': 'create autoregressive masks with random masking across states, returns, and actions'}
```

## File: facebookresearch_mtm/research/mtm/train.py

Prompts

```
['get distributed training parameters from submitit or environment variables', 'create a DistributedParams dataclass with rank, world_size, master_addr, and master_port fields', 'review the DistributedParams dataclass fields for rank, local_rank, world_size, and master_addr', 'summarize the get_distributed_params function that loads job info from submitit or env vars', 'test the get_distributed_params function to verify it falls back to defaults when no env is set', 'create a random binary mask tensor for a given trajectory length and mask ratio', 'create a full random mask tensor across trajectory length and data dimensions', 'create goal-reaching masks that expose start, end, and a random middle state', 'create an inverse dynamics mask that exposes all states but no actions', 'create autoregressive masks with random masking across states, returns, and actions', 'train a MTM model on a dataset using Hydra config with distributed training support', 'evaluate the MTM model on forward dynamics task by predicting next states from actions', 'evaluate the MTM model on inverse dynamics task by predicting actions from states', 'create evaluation logs with visualization plots for states actions and images using mask patterns', 'configure and launch a MTM training job with Hydra config including wandb logging and checkpointing', 'run the MTM policy training script with Hydra config to train a model on a dataset', 'train one batch by encoding data, computing loss, backpropagating, and updating optimizer and scheduler', 'configure training hyperparameters like batch size, learning rate, warmup steps, and trajectory length', 'resume training from a saved checkpoint by loading model and optimizer state dicts', 'evaluate the trained model on a validation dataset and log metrics to Weights and Biases', 'load a Hydra config from a path and convert mask indices to mask pattern names', 'get the checkpoint path with the highest step number from a folder of PyTorch checkpoint files', 'compute an MD5 hash of a Hydra config object serialized to YAML', 'get the current Git commit SHA hash from the repository', 'set a random seed across PyTorch, CUDA, NumPy, and Python random modules']
```

Usage

```
{'train_mtm_model': 'train a MTM model on a dataset using Hydra config with distributed training support', 'eval_forward_dynamics': 'evaluate the MTM model on forward dynamics task by predicting next states from actions', 'eval_inverse_dynamics': 'evaluate the MTM model on inverse dynamics task by predicting actions from states', 'create_eval_visualizations': 'create evaluation logs with visualization plots for states actions and images using mask patterns', 'configure_training_run': 'configure and launch a MTM training job with Hydra config including wandb logging and checkpointing'}
```

## File: facebookresearch_mtm/research/mtm/train_mlp.py

Prompts

```
['get distributed training parameters from submitit or environment variables', 'create a DistributedParams dataclass with rank, world_size, master_addr, and master_port fields', 'review the DistributedParams dataclass fields for rank, local_rank, world_size, and master_addr', 'summarize the get_distributed_params function that loads job info from submitit or env vars', 'test the get_distributed_params function to verify it falls back to defaults when no env is set', 'create a random binary mask tensor for a given trajectory length and mask ratio', 'create a full random mask tensor across trajectory length and data dimensions', 'create goal-reaching masks that expose start, end, and a random middle state', 'create an inverse dynamics mask that exposes all states but no actions', 'create autoregressive masks with random masking across states, returns, and actions', 'train a MTM model on a dataset using Hydra config with distributed training support', 'evaluate the MTM model on forward dynamics task by predicting next states from actions', 'evaluate the MTM model on inverse dynamics task by predicting actions from states', 'create evaluation logs with visualization plots for states actions and images using mask patterns', 'configure and launch a MTM training job with Hydra config including wandb logging and checkpointing', 'run the MTM policy training script with Hydra config to train a model on a dataset', 'train one batch by encoding data, computing loss, backpropagating, and updating optimizer and scheduler', 'configure training hyperparameters like batch size, learning rate, warmup steps, and trajectory length', 'resume training from a saved checkpoint by loading model and optimizer state dicts', 'evaluate the trained model on a validation dataset and log metrics to Weights and Biases', 'load a Hydra config from a path and convert mask indices to mask pattern names', 'get the checkpoint path with the highest step number from a folder of PyTorch checkpoint files', 'compute an MD5 hash of a Hydra config object serialized to YAML', 'get the current Git commit SHA hash from the repository', 'set a random seed across PyTorch, CUDA, NumPy, and Python random modules']
```

Usage

```
{'run_MLM_training': 'run the MTM policy training script with Hydra config to train a model on a dataset', 'train_one_batch': 'train one batch by encoding data, computing loss, backpropagating, and updating optimizer and scheduler', 'configure_RunConfig': 'configure training hyperparameters like batch size, learning rate, warmup steps, and trajectory length', 'resume_checkpoint_training': 'resume training from a saved checkpoint by loading model and optimizer state dicts', 'evaluate_model': 'evaluate the trained model on a validation dataset and log metrics to Weights and Biases'}
```

## File: facebookresearch_mtm/research/mtm/utils.py

Prompts

```
['get distributed training parameters from submitit or environment variables', 'create a DistributedParams dataclass with rank, world_size, master_addr, and master_port fields', 'review the DistributedParams dataclass fields for rank, local_rank, world_size, and master_addr', 'summarize the get_distributed_params function that loads job info from submitit or env vars', 'test the get_distributed_params function to verify it falls back to defaults when no env is set', 'create a random binary mask tensor for a given trajectory length and mask ratio', 'create a full random mask tensor across trajectory length and data dimensions', 'create goal-reaching masks that expose start, end, and a random middle state', 'create an inverse dynamics mask that exposes all states but no actions', 'create autoregressive masks with random masking across states, returns, and actions', 'train a MTM model on a dataset using Hydra config with distributed training support', 'evaluate the MTM model on forward dynamics task by predicting next states from actions', 'evaluate the MTM model on inverse dynamics task by predicting actions from states', 'create evaluation logs with visualization plots for states actions and images using mask patterns', 'configure and launch a MTM training job with Hydra config including wandb logging and checkpointing', 'run the MTM policy training script with Hydra config to train a model on a dataset', 'train one batch by encoding data, computing loss, backpropagating, and updating optimizer and scheduler', 'configure training hyperparameters like batch size, learning rate, warmup steps, and trajectory length', 'resume training from a saved checkpoint by loading model and optimizer state dicts', 'evaluate the trained model on a validation dataset and log metrics to Weights and Biases', 'load a Hydra config from a path and convert mask indices to mask pattern names', 'get the checkpoint path with the highest step number from a folder of PyTorch checkpoint files', 'compute an MD5 hash of a Hydra config object serialized to YAML', 'get the current Git commit SHA hash from the repository', 'set a random seed across PyTorch, CUDA, NumPy, and Python random modules']
```

Usage

```
{'load_hydra_config': 'load a Hydra config from a path and convert mask indices to mask pattern names', 'get_ckpt_path': 'get the checkpoint path with the highest step number from a folder of PyTorch checkpoint files', 'get_cfg_hash': 'compute an MD5 hash of a Hydra config object serialized to YAML', 'get_git_hash': 'get the current Git commit SHA hash from the repository', 'set_seed_everywhere': 'set a random seed across PyTorch, CUDA, NumPy, and Python random modules'}
```

