# Agent Python Tools

- repo: facebookresearch/mbrl-lib
- repo_uri: https://github.com/facebookresearch/mbrl-lib

## File: facebookresearch_mbrl-lib/mbrl/third_party/pytorch_sac/logger.py

Prompts

```
['create a Logger instance with a log directory and SAC agent format for training metrics', 'log training metrics like actor loss and critic loss to CSV and console output', 'log evaluation metrics like episode reward to CSV files with step tracking', 'dump accumulated training and evaluation meters to CSV and console at a given step', 'log model parameter weights and gradients as histograms at configurable step frequency', 'create a ReplayBuffer with observation shape, action shape, capacity, and device for storing RL transitions', 'add a single environment transition with obs, action, reward, next_obs, and done flags to the buffer', 'add a batch of environment transitions to the replay buffer with circular overflow handling', 'sample a random batch of transitions from the replay buffer and return PyTorch tensors on the device', 'get the current number of stored transitions in the replay buffer using the len method', 'run the SAC agent training loop with Hydra config and environment setup', 'run the Workspace evaluate method to compute average episode reward over eval episodes', 'run the Workspace run method to execute the full SAC training loop with logging', 'review the Workspace class that manages SAC agent training, evaluation, and replay buffer', 'review the Workspace evaluate method that runs eval episodes and logs average episode reward', 'create a gymnasium or dm_control environment from a config object with make_env', 'build a PyTorch MLP neural network with configurable hidden depth and output module', 'soft update target network parameters using tau interpolation with soft_update_params', 'set a random seed across torch, cuda, numpy, and python random modules', 'convert a PyTorch tensor to a numpy array using the to_np helper function', 'create a VideoRecorder instance with a root directory, frame dimensions, camera ID, and FPS settings', 'initialize the VideoRecorder to clear frames and enable or disable recording for a new episode', 'record a single RGB frame from a gym environment into the VideoRecorder using env render', "save the recorded frames as a video file to the recorder's save directory with the given filename", 'review the VideoRecorder class and its methods for recording and saving environment video frames']
```

Usage

```
{'create_logger_for_rl_agent': 'create a Logger instance with a log directory and SAC agent format for training metrics', 'log_training_metrics': 'log training metrics like actor loss and critic loss to CSV and console output', 'log_evaluation_metrics': 'log evaluation metrics like episode reward to CSV files with step tracking', 'dump_metrics_to_csv': 'dump accumulated training and evaluation meters to CSV and console at a given step', 'log_model_parameters': 'log model parameter weights and gradients as histograms at configurable step frequency'}
```

## File: facebookresearch_mbrl-lib/mbrl/third_party/pytorch_sac/replay_buffer.py

Prompts

```
['create a Logger instance with a log directory and SAC agent format for training metrics', 'log training metrics like actor loss and critic loss to CSV and console output', 'log evaluation metrics like episode reward to CSV files with step tracking', 'dump accumulated training and evaluation meters to CSV and console at a given step', 'log model parameter weights and gradients as histograms at configurable step frequency', 'create a ReplayBuffer with observation shape, action shape, capacity, and device for storing RL transitions', 'add a single environment transition with obs, action, reward, next_obs, and done flags to the buffer', 'add a batch of environment transitions to the replay buffer with circular overflow handling', 'sample a random batch of transitions from the replay buffer and return PyTorch tensors on the device', 'get the current number of stored transitions in the replay buffer using the len method', 'run the SAC agent training loop with Hydra config and environment setup', 'run the Workspace evaluate method to compute average episode reward over eval episodes', 'run the Workspace run method to execute the full SAC training loop with logging', 'review the Workspace class that manages SAC agent training, evaluation, and replay buffer', 'review the Workspace evaluate method that runs eval episodes and logs average episode reward', 'create a gymnasium or dm_control environment from a config object with make_env', 'build a PyTorch MLP neural network with configurable hidden depth and output module', 'soft update target network parameters using tau interpolation with soft_update_params', 'set a random seed across torch, cuda, numpy, and python random modules', 'convert a PyTorch tensor to a numpy array using the to_np helper function', 'create a VideoRecorder instance with a root directory, frame dimensions, camera ID, and FPS settings', 'initialize the VideoRecorder to clear frames and enable or disable recording for a new episode', 'record a single RGB frame from a gym environment into the VideoRecorder using env render', "save the recorded frames as a video file to the recorder's save directory with the given filename", 'review the VideoRecorder class and its methods for recording and saving environment video frames']
```

Usage

```
{'create_replay_buffer': 'create a ReplayBuffer with observation shape, action shape, capacity, and device for storing RL transitions', 'add_single_transition': 'add a single environment transition with obs, action, reward, next_obs, and done flags to the buffer', 'add_batch_transitions': 'add a batch of environment transitions to the replay buffer with circular overflow handling', 'sample_batch': 'sample a random batch of transitions from the replay buffer and return PyTorch tensors on the device', 'get_buffer_length': 'get the current number of stored transitions in the replay buffer using the len method'}
```

## File: facebookresearch_mbrl-lib/mbrl/third_party/pytorch_sac/train.py

Prompts

```
['create a Logger instance with a log directory and SAC agent format for training metrics', 'log training metrics like actor loss and critic loss to CSV and console output', 'log evaluation metrics like episode reward to CSV files with step tracking', 'dump accumulated training and evaluation meters to CSV and console at a given step', 'log model parameter weights and gradients as histograms at configurable step frequency', 'create a ReplayBuffer with observation shape, action shape, capacity, and device for storing RL transitions', 'add a single environment transition with obs, action, reward, next_obs, and done flags to the buffer', 'add a batch of environment transitions to the replay buffer with circular overflow handling', 'sample a random batch of transitions from the replay buffer and return PyTorch tensors on the device', 'get the current number of stored transitions in the replay buffer using the len method', 'run the SAC agent training loop with Hydra config and environment setup', 'run the Workspace evaluate method to compute average episode reward over eval episodes', 'run the Workspace run method to execute the full SAC training loop with logging', 'review the Workspace class that manages SAC agent training, evaluation, and replay buffer', 'review the Workspace evaluate method that runs eval episodes and logs average episode reward', 'create a gymnasium or dm_control environment from a config object with make_env', 'build a PyTorch MLP neural network with configurable hidden depth and output module', 'soft update target network parameters using tau interpolation with soft_update_params', 'set a random seed across torch, cuda, numpy, and python random modules', 'convert a PyTorch tensor to a numpy array using the to_np helper function', 'create a VideoRecorder instance with a root directory, frame dimensions, camera ID, and FPS settings', 'initialize the VideoRecorder to clear frames and enable or disable recording for a new episode', 'record a single RGB frame from a gym environment into the VideoRecorder using env render', "save the recorded frames as a video file to the recorder's save directory with the given filename", 'review the VideoRecorder class and its methods for recording and saving environment video frames']
```

Usage

```
{'run_sac_training': 'run the SAC agent training loop with Hydra config and environment setup', 'run_workspace_evaluate': 'run the Workspace evaluate method to compute average episode reward over eval episodes', 'run_workspace_run': 'run the Workspace run method to execute the full SAC training loop with logging', 'review_workspace_class': 'review the Workspace class that manages SAC agent training, evaluation, and replay buffer', 'review_workspace_evaluate': 'review the Workspace evaluate method that runs eval episodes and logs average episode reward'}
```

## File: facebookresearch_mbrl-lib/mbrl/third_party/pytorch_sac/utils.py

Prompts

```
['create a Logger instance with a log directory and SAC agent format for training metrics', 'log training metrics like actor loss and critic loss to CSV and console output', 'log evaluation metrics like episode reward to CSV files with step tracking', 'dump accumulated training and evaluation meters to CSV and console at a given step', 'log model parameter weights and gradients as histograms at configurable step frequency', 'create a ReplayBuffer with observation shape, action shape, capacity, and device for storing RL transitions', 'add a single environment transition with obs, action, reward, next_obs, and done flags to the buffer', 'add a batch of environment transitions to the replay buffer with circular overflow handling', 'sample a random batch of transitions from the replay buffer and return PyTorch tensors on the device', 'get the current number of stored transitions in the replay buffer using the len method', 'run the SAC agent training loop with Hydra config and environment setup', 'run the Workspace evaluate method to compute average episode reward over eval episodes', 'run the Workspace run method to execute the full SAC training loop with logging', 'review the Workspace class that manages SAC agent training, evaluation, and replay buffer', 'review the Workspace evaluate method that runs eval episodes and logs average episode reward', 'create a gymnasium or dm_control environment from a config object with make_env', 'build a PyTorch MLP neural network with configurable hidden depth and output module', 'soft update target network parameters using tau interpolation with soft_update_params', 'set a random seed across torch, cuda, numpy, and python random modules', 'convert a PyTorch tensor to a numpy array using the to_np helper function', 'create a VideoRecorder instance with a root directory, frame dimensions, camera ID, and FPS settings', 'initialize the VideoRecorder to clear frames and enable or disable recording for a new episode', 'record a single RGB frame from a gym environment into the VideoRecorder using env render', "save the recorded frames as a video file to the recorder's save directory with the given filename", 'review the VideoRecorder class and its methods for recording and saving environment video frames']
```

Usage

```
{'create_gym_or_dm_control_env': 'create a gymnasium or dm_control environment from a config object with make_env', 'build_mlp_network': 'build a PyTorch MLP neural network with configurable hidden depth and output module', 'soft_update_target_network': 'soft update target network parameters using tau interpolation with soft_update_params', 'set_random_seed_everywhere': 'set a random seed across torch, cuda, numpy, and python random modules', 'convert_tensor_to_numpy': 'convert a PyTorch tensor to a numpy array using the to_np helper function'}
```

## File: facebookresearch_mbrl-lib/mbrl/third_party/pytorch_sac/video.py

Prompts

```
['create a Logger instance with a log directory and SAC agent format for training metrics', 'log training metrics like actor loss and critic loss to CSV and console output', 'log evaluation metrics like episode reward to CSV files with step tracking', 'dump accumulated training and evaluation meters to CSV and console at a given step', 'log model parameter weights and gradients as histograms at configurable step frequency', 'create a ReplayBuffer with observation shape, action shape, capacity, and device for storing RL transitions', 'add a single environment transition with obs, action, reward, next_obs, and done flags to the buffer', 'add a batch of environment transitions to the replay buffer with circular overflow handling', 'sample a random batch of transitions from the replay buffer and return PyTorch tensors on the device', 'get the current number of stored transitions in the replay buffer using the len method', 'run the SAC agent training loop with Hydra config and environment setup', 'run the Workspace evaluate method to compute average episode reward over eval episodes', 'run the Workspace run method to execute the full SAC training loop with logging', 'review the Workspace class that manages SAC agent training, evaluation, and replay buffer', 'review the Workspace evaluate method that runs eval episodes and logs average episode reward', 'create a gymnasium or dm_control environment from a config object with make_env', 'build a PyTorch MLP neural network with configurable hidden depth and output module', 'soft update target network parameters using tau interpolation with soft_update_params', 'set a random seed across torch, cuda, numpy, and python random modules', 'convert a PyTorch tensor to a numpy array using the to_np helper function', 'create a VideoRecorder instance with a root directory, frame dimensions, camera ID, and FPS settings', 'initialize the VideoRecorder to clear frames and enable or disable recording for a new episode', 'record a single RGB frame from a gym environment into the VideoRecorder using env render', "save the recorded frames as a video file to the recorder's save directory with the given filename", 'review the VideoRecorder class and its methods for recording and saving environment video frames']
```

Usage

```
{'create_video_recorder': 'create a VideoRecorder instance with a root directory, frame dimensions, camera ID, and FPS settings', 'init_video_recorder': 'initialize the VideoRecorder to clear frames and enable or disable recording for a new episode', 'record_env_frame': 'record a single RGB frame from a gym environment into the VideoRecorder using env render', 'save_video': "save the recorded frames as a video file to the recorder's save directory with the given filename", 'review_video_recorder_class': 'review the VideoRecorder class and its methods for recording and saving environment video frames'}
```

