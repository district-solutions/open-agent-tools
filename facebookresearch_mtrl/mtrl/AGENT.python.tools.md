# Agent Python Tools

- repo: facebookresearch/mtrl
- repo_uri: https://github.com/facebookresearch/mtrl

## File: facebookresearch_mtrl/mtrl/logger.py

Prompts

```
['create a Logger instance to track training and evaluation metrics for reinforcement learning experiments', 'log a metric value with a key like train/loss to the Logger for a given step', 'dump all accumulated metrics to JSON log files and console output at a given step', 'create an AverageMeter to track running averages of values updated with weighted counts', 'serialize numpy float32 and int64 values to JSON-compatible types using the singledispatch serialize_log function', 'create a ReplayBuffer instance with env_obs_shape, task_obs_shape, action_shape, capacity, batch_size, and device', 'add an environment transition with obs, action, reward, next_obs, done flag, and task_obs to the buffer', 'sample a batch of random transitions from the replay buffer and return a ReplayBufferSample', 'save the replay buffer to disk in chunked .pt files with optional sampling of num_samples_to_save', 'load a previously saved replay buffer from disk by reading sorted chunk files into the buffer']
```

Usage

```
{'create_logger_for_rl_training': 'create a Logger instance to track training and evaluation metrics for reinforcement learning experiments', 'log_metric_values': 'log a metric value with a key like train/loss to the Logger for a given step', 'dump_metrics_to_file': 'dump all accumulated metrics to JSON log files and console output at a given step', 'create_average_meter': 'create an AverageMeter to track running averages of values updated with weighted counts', 'serialize_numpy_for_json': 'serialize numpy float32 and int64 values to JSON-compatible types using the singledispatch serialize_log function'}
```

## File: facebookresearch_mtrl/mtrl/replay_buffer.py

Prompts

```
['create a Logger instance to track training and evaluation metrics for reinforcement learning experiments', 'log a metric value with a key like train/loss to the Logger for a given step', 'dump all accumulated metrics to JSON log files and console output at a given step', 'create an AverageMeter to track running averages of values updated with weighted counts', 'serialize numpy float32 and int64 values to JSON-compatible types using the singledispatch serialize_log function', 'create a ReplayBuffer instance with env_obs_shape, task_obs_shape, action_shape, capacity, batch_size, and device', 'add an environment transition with obs, action, reward, next_obs, done flag, and task_obs to the buffer', 'sample a batch of random transitions from the replay buffer and return a ReplayBufferSample', 'save the replay buffer to disk in chunked .pt files with optional sampling of num_samples_to_save', 'load a previously saved replay buffer from disk by reading sorted chunk files into the buffer']
```

Usage

```
{'create_replay_buffer': 'create a ReplayBuffer instance with env_obs_shape, task_obs_shape, action_shape, capacity, batch_size, and device', 'add_transition_to_buffer': 'add an environment transition with obs, action, reward, next_obs, done flag, and task_obs to the buffer', 'sample_from_replay_buffer': 'sample a batch of random transitions from the replay buffer and return a ReplayBufferSample', 'save_replay_buffer': 'save the replay buffer to disk in chunked .pt files with optional sampling of num_samples_to_save', 'load_replay_buffer': 'load a previously saved replay buffer from disk by reading sorted chunk files into the buffer'}
```

