# Agent Python Tools

- repo: facebookresearch/meru
- repo_uri: https://github.com/facebookresearch/meru

## File: facebookresearch_meru/meru/utils/checkpointing.py

Prompts

```
['create a CheckpointManager to periodically save PyTorch models and optimizers during training', 'build a checkpoint at a given training iteration using CheckpointManager step method', 'test resuming a training job by loading the last saved checkpoint from disk', 'refactor checkpoint loading to restore model and optimizer state dicts from a saved file', 'summarize the final checkpoint saving process that writes checkpoint_final.pth without cleanup', 'launch a multi-GPU distributed training job across machines using torch multiprocessing spawn', 'synchronize all processes in a distributed process group with a barrier call', 'get the total number of processes in the distributed process group', 'gather tensors from multiple GPU processes into a list preserving order by rank', 'check if the current process is the main process for logging and checkpointing', 'create a Timer instance with a start iteration and total iterations for ETA tracking', 'call tic on a Timer instance to start recording time at the beginning of an iteration', 'call toc on a Timer instance to stop recording time at the end of an iteration', 'get the estimated time remaining in hh mm format using the eta_hhmm property on a Timer', 'review the Timer class and its tic toc methods for iteration timing and ETA estimation']
```

Usage

```
{'create_CheckpointManager': 'create a CheckpointManager to periodically save PyTorch models and optimizers during training', 'build_CheckpointManager_step': 'build a checkpoint at a given training iteration using CheckpointManager step method', 'test_CheckpointManager_resume': 'test resuming a training job by loading the last saved checkpoint from disk', 'refactor_CheckpointManager_load': 'refactor checkpoint loading to restore model and optimizer state dicts from a saved file', 'summarize_CheckpointManager_final_step': 'summarize the final checkpoint saving process that writes checkpoint_final.pth without cleanup'}
```

## File: facebookresearch_meru/meru/utils/distributed.py

Prompts

```
['create a CheckpointManager to periodically save PyTorch models and optimizers during training', 'build a checkpoint at a given training iteration using CheckpointManager step method', 'test resuming a training job by loading the last saved checkpoint from disk', 'refactor checkpoint loading to restore model and optimizer state dicts from a saved file', 'summarize the final checkpoint saving process that writes checkpoint_final.pth without cleanup', 'launch a multi-GPU distributed training job across machines using torch multiprocessing spawn', 'synchronize all processes in a distributed process group with a barrier call', 'get the total number of processes in the distributed process group', 'gather tensors from multiple GPU processes into a list preserving order by rank', 'check if the current process is the main process for logging and checkpointing', 'create a Timer instance with a start iteration and total iterations for ETA tracking', 'call tic on a Timer instance to start recording time at the beginning of an iteration', 'call toc on a Timer instance to stop recording time at the end of an iteration', 'get the estimated time remaining in hh mm format using the eta_hhmm property on a Timer', 'review the Timer class and its tic toc methods for iteration timing and ETA estimation']
```

Usage

```
{'launch_distributed_job': 'launch a multi-GPU distributed training job across machines using torch multiprocessing spawn', 'synchronize_processes': 'synchronize all processes in a distributed process group with a barrier call', 'get_world_size': 'get the total number of processes in the distributed process group', 'gather_tensors_across_processes': 'gather tensors from multiple GPU processes into a list preserving order by rank', 'check_main_process': 'check if the current process is the main process for logging and checkpointing'}
```

## File: facebookresearch_meru/meru/utils/timer.py

Prompts

```
['create a CheckpointManager to periodically save PyTorch models and optimizers during training', 'build a checkpoint at a given training iteration using CheckpointManager step method', 'test resuming a training job by loading the last saved checkpoint from disk', 'refactor checkpoint loading to restore model and optimizer state dicts from a saved file', 'summarize the final checkpoint saving process that writes checkpoint_final.pth without cleanup', 'launch a multi-GPU distributed training job across machines using torch multiprocessing spawn', 'synchronize all processes in a distributed process group with a barrier call', 'get the total number of processes in the distributed process group', 'gather tensors from multiple GPU processes into a list preserving order by rank', 'check if the current process is the main process for logging and checkpointing', 'create a Timer instance with a start iteration and total iterations for ETA tracking', 'call tic on a Timer instance to start recording time at the beginning of an iteration', 'call toc on a Timer instance to stop recording time at the end of an iteration', 'get the estimated time remaining in hh mm format using the eta_hhmm property on a Timer', 'review the Timer class and its tic toc methods for iteration timing and ETA estimation']
```

Usage

```
{'create_timer_instance': 'create a Timer instance with a start iteration and total iterations for ETA tracking', 'start_timer_tic': 'call tic on a Timer instance to start recording time at the beginning of an iteration', 'stop_timer_toc': 'call toc on a Timer instance to stop recording time at the end of an iteration', 'get_eta_hhmm': 'get the estimated time remaining in hh mm format using the eta_hhmm property on a Timer', 'review_timer_class': 'review the Timer class and its tic toc methods for iteration timing and ETA estimation'}
```

