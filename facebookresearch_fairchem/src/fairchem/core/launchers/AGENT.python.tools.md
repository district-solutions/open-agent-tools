# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/src/fairchem/core/launchers/ray_on_slurm_launch.py

Prompts

```
['run a Ray remote SPMDWorker actor that sets up distributed training and executes a FairChem runner', 'create an SPMDController that orchestrates SPMD workers across Ray placement groups on a SLURM cluster', 'run the ray_entrypoint payload function that instantiates and executes a FairChem runner from config', 'launch a Ray cluster on SLURM with resource requirements and submit a runner payload', 'review the SPMDWorker _distributed_setup method that initializes PyTorch process groups with NCCL or Gloo backends', 'submit a FairChem job to a SLURM cluster using submitit with AutoExecutor and scheduler config', 'launch a FairChem job locally using torch elastic launch or single process mode', 'run a SPMD program on SLURM with distributed setup, seed initialization, and checkpoint support', 'convert a FairChem JobConfig into a distributed training config with world size and backend settings', 'decouple a SLURM job submission from runner state to prevent re-submission on node failure']
```

Usage

```
{'run_SPMDWorker': 'run a Ray remote SPMDWorker actor that sets up distributed training and executes a FairChem runner', 'create_SPMDController': 'create an SPMDController that orchestrates SPMD workers across Ray placement groups on a SLURM cluster', 'run_ray_entrypoint': 'run the ray_entrypoint payload function that instantiates and executes a FairChem runner from config', 'launch_ray_on_slurm': 'launch a Ray cluster on SLURM with resource requirements and submit a runner payload', 'review_SPMDWorker_distributed_setup': 'review the SPMDWorker _distributed_setup method that initializes PyTorch process groups with NCCL or Gloo backends'}
```

## File: facebookresearch_fairchem/src/fairchem/core/launchers/slurm_launch.py

Prompts

```
['run a Ray remote SPMDWorker actor that sets up distributed training and executes a FairChem runner', 'create an SPMDController that orchestrates SPMD workers across Ray placement groups on a SLURM cluster', 'run the ray_entrypoint payload function that instantiates and executes a FairChem runner from config', 'launch a Ray cluster on SLURM with resource requirements and submit a runner payload', 'review the SPMDWorker _distributed_setup method that initializes PyTorch process groups with NCCL or Gloo backends', 'submit a FairChem job to a SLURM cluster using submitit with AutoExecutor and scheduler config', 'launch a FairChem job locally using torch elastic launch or single process mode', 'run a SPMD program on SLURM with distributed setup, seed initialization, and checkpoint support', 'convert a FairChem JobConfig into a distributed training config with world size and backend settings', 'decouple a SLURM job submission from runner state to prevent re-submission on node failure']
```

Usage

```
{'launch_slurm_job': 'submit a FairChem job to a SLURM cluster using submitit with AutoExecutor and scheduler config', 'launch_local_job': 'launch a FairChem job locally using torch elastic launch or single process mode', 'run_slurm_spmd_program': 'run a SPMD program on SLURM with distributed setup, seed initialization, and checkpoint support', 'map_job_to_dist_config': 'convert a FairChem JobConfig into a distributed training config with world size and backend settings', 'remove_runner_state_from_submission': 'decouple a SLURM job submission from runner state to prevent re-submission on node failure'}
```

