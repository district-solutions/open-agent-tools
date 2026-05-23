# Agent Python Tools

- repo: facebookresearch/omnivore
- repo_uri: https://github.com/facebookresearch/omnivore

## File: facebookresearch_omnivore/omnivision/logger.py

Prompts

```
['create a TensorBoardLogger instance that writes scalar metrics to a specified log directory path', 'log a single scalar value with a tag name and step to the TensorBoard logger', 'log a dictionary of multiple scalar values at once to the TensorBoard logger', 'log hyperparameters and their corresponding metrics to the TensorBoard logger for experiment tracking', 'flush pending TensorBoard logs to disk to ensure all metrics are written immediately', 'run a distributed training job on a Slurm cluster using submitit AutoExecutor and Hydra config', 'run multi-GPU training locally using torch.multiprocessing.start_processes with spawn method', 'create a SubmititRunner checkpointable callable that sets environment variables and instantiates a trainer', 'run single process training on one GPU by setting rank and world size environment variables', 'configure submitit job parameters including timeout, partition, GPUs per node, and memory constraints']
```

Usage

```
{'create_tensorboard_logger': 'create a TensorBoardLogger instance that writes scalar metrics to a specified log directory path', 'log_scalar_to_tensorboard': 'log a single scalar value with a tag name and step to the TensorBoard logger', 'log_dict_to_tensorboard': 'log a dictionary of multiple scalar values at once to the TensorBoard logger', 'log_hparams_to_tensorboard': 'log hyperparameters and their corresponding metrics to the TensorBoard logger for experiment tracking', 'flush_tensorboard_logger': 'flush pending TensorBoard logs to disk to ensure all metrics are written immediately'}
```

## File: facebookresearch_omnivore/omnivision/train_app_submitit.py

Prompts

```
['create a TensorBoardLogger instance that writes scalar metrics to a specified log directory path', 'log a single scalar value with a tag name and step to the TensorBoard logger', 'log a dictionary of multiple scalar values at once to the TensorBoard logger', 'log hyperparameters and their corresponding metrics to the TensorBoard logger for experiment tracking', 'flush pending TensorBoard logs to disk to ensure all metrics are written immediately', 'run a distributed training job on a Slurm cluster using submitit AutoExecutor and Hydra config', 'run multi-GPU training locally using torch.multiprocessing.start_processes with spawn method', 'create a SubmititRunner checkpointable callable that sets environment variables and instantiates a trainer', 'run single process training on one GPU by setting rank and world size environment variables', 'configure submitit job parameters including timeout, partition, GPUs per node, and memory constraints']
```

Usage

```
{'run_training_job_on_cluster': 'run a distributed training job on a Slurm cluster using submitit AutoExecutor and Hydra config', 'run_local_multi_gpu_training': 'run multi-GPU training locally using torch.multiprocessing.start_processes with spawn method', 'create_submitit_runner': 'create a SubmititRunner checkpointable callable that sets environment variables and instantiates a trainer', 'run_single_process_training': 'run single process training on one GPU by setting rank and world size environment variables', 'configure_submitit_job_kwargs': 'configure submitit job parameters including timeout, partition, GPUs per node, and memory constraints'}
```

