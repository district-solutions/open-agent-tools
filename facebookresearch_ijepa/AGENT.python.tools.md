# Agent Python Tools

- repo: facebookresearch/ijepa
- repo_uri: https://github.com/facebookresearch/ijepa

## File: facebookresearch_ijepa/main.py

Prompts

```
['run the I-JEPA training loop using a YAML config file and specified GPU devices', 'run multi-GPU training by spawning processes for each device with the process_main function', 'load a YAML config file and parse training parameters with yaml.FullLoader', 'initialize distributed training with init_distributed using rank and world_size arguments', 'run the training process on custom CUDA devices using the --devices CLI argument', 'run distributed training jobs on a SLURM cluster using submitit with a YAML config file', 'submit a Trainer job to the SLURM executor with specified nodes, GPUs, and partition', 'create a Trainer instance that loads training params from a YAML config file', 'checkpoint a Trainer to resume preempted jobs using submitit DelayedSubmission', 'launch batch training jobs via AutoExecutor with configurable SLURM parameters like time and memory']
```

Usage

```
{'run_ijepa_training': 'run the I-JEPA training loop using a YAML config file and specified GPU devices', 'run_multigpu_training': 'run multi-GPU training by spawning processes for each device with the process_main function', 'load_config_yaml': 'load a YAML config file and parse training parameters with yaml.FullLoader', 'init_distributed_training': 'initialize distributed training with init_distributed using rank and world_size arguments', 'run_with_custom_devices': 'run the training process on custom CUDA devices using the --devices CLI argument'}
```

## File: facebookresearch_ijepa/main_distributed.py

Prompts

```
['run the I-JEPA training loop using a YAML config file and specified GPU devices', 'run multi-GPU training by spawning processes for each device with the process_main function', 'load a YAML config file and parse training parameters with yaml.FullLoader', 'initialize distributed training with init_distributed using rank and world_size arguments', 'run the training process on custom CUDA devices using the --devices CLI argument', 'run distributed training jobs on a SLURM cluster using submitit with a YAML config file', 'submit a Trainer job to the SLURM executor with specified nodes, GPUs, and partition', 'create a Trainer instance that loads training params from a YAML config file', 'checkpoint a Trainer to resume preempted jobs using submitit DelayedSubmission', 'launch batch training jobs via AutoExecutor with configurable SLURM parameters like time and memory']
```

Usage

```
{'run_distributed_training': 'run distributed training jobs on a SLURM cluster using submitit with a YAML config file', 'submit_trainer_job': 'submit a Trainer job to the SLURM executor with specified nodes, GPUs, and partition', 'create_trainer': 'create a Trainer instance that loads training params from a YAML config file', 'checkpoint_trainer': 'checkpoint a Trainer to resume preempted jobs using submitit DelayedSubmission', 'launch_batch_jobs': 'launch batch training jobs via AutoExecutor with configurable SLURM parameters like time and memory'}
```

