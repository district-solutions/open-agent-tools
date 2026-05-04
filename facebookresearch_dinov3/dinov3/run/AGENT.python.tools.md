# Agent Python Tools

- repo: facebookresearch/dinov3
- repo_uri: https://github.com/facebookresearch/dinov3

## File: facebookresearch_dinov3/dinov3/run/init.py

Prompts

```
['run a DINOv3 job using the job_context manager with distributed training and logging enabled', 'setup a DINOv3 training job with output directory, seed, and distributed timeout configuration', 'run distributed DINOv3 training with automatic setup and cleanup via the job_context context manager', 'configure DINOv3 job logging and distributed process setup using job_context with custom parameters', 'cleanup DINOv3 job resources including distributed processes and logging via the job_context finally block', 'submit a Python training script to a Slurm cluster using submitit with configurable GPUs and nodes', 'create a CheckpointableSubmitter instance to wrap a callable for checkpoint-aware Slurm job submission', 'build an argparse parser with Slurm job arguments like ngpus, nodes, timeout, partition, and QoS settings', 'get the shared experiments folder path under the user checkpoint directory for storing job outputs', "run the submit CLI entry point to launch a module's callable on a Slurm cluster with auto-requeue support"]
```

Usage

```
{'run_job_context': 'run a DINOv3 job using the job_context manager with distributed training and logging enabled', 'setup_job_with_context': 'setup a DINOv3 training job with output directory, seed, and distributed timeout configuration', 'run_distributed_training': 'run distributed DINOv3 training with automatic setup and cleanup via the job_context context manager', 'configure_job_logging': 'configure DINOv3 job logging and distributed process setup using job_context with custom parameters', 'cleanup_job_resources': 'cleanup DINOv3 job resources including distributed processes and logging via the job_context finally block'}
```

## File: facebookresearch_dinov3/dinov3/run/submit.py

Prompts

```
['run a DINOv3 job using the job_context manager with distributed training and logging enabled', 'setup a DINOv3 training job with output directory, seed, and distributed timeout configuration', 'run distributed DINOv3 training with automatic setup and cleanup via the job_context context manager', 'configure DINOv3 job logging and distributed process setup using job_context with custom parameters', 'cleanup DINOv3 job resources including distributed processes and logging via the job_context finally block', 'submit a Python training script to a Slurm cluster using submitit with configurable GPUs and nodes', 'create a CheckpointableSubmitter instance to wrap a callable for checkpoint-aware Slurm job submission', 'build an argparse parser with Slurm job arguments like ngpus, nodes, timeout, partition, and QoS settings', 'get the shared experiments folder path under the user checkpoint directory for storing job outputs', "run the submit CLI entry point to launch a module's callable on a Slurm cluster with auto-requeue support"]
```

Usage

```
{'submit_training_job': 'submit a Python training script to a Slurm cluster using submitit with configurable GPUs and nodes', 'create_checkpointable_submitter': 'create a CheckpointableSubmitter instance to wrap a callable for checkpoint-aware Slurm job submission', 'configure_slurm_parser': 'build an argparse parser with Slurm job arguments like ngpus, nodes, timeout, partition, and QoS settings', 'get_shared_folder': 'get the shared experiments folder path under the user checkpoint directory for storing job outputs', 'run_submitter_main': "run the submit CLI entry point to launch a module's callable on a Slurm cluster with auto-requeue support"}
```

