# Agent Python Tools

- repo: facebookresearch/rlstructures
- repo_uri: https://github.com/facebookresearch/rlstructures

## File: facebookresearch_rlstructures/rlalgos/atari_wrappers.py

Prompts

```
['build an Atari environment with NoopResetEnv and MaxAndSkipEnv wrappers for a given env_id', 'wrap an Atari environment with DeepMind-style preprocessing including frame stacking and reward clipping', 'wrap an environment to convert image observations from HWC to CHW format for PyTorch', 'create a FrameStack wrapper that stacks k last frames into a single observation for temporal context', 'apply a WarpFrame wrapper to resize and grayscale Atari frames to 84x84', 'create a Logger instance to store experimental measures in memory with config hyperparameters', 'add a scalar value to the Logger at a given training iteration for tracking metrics', 'add a nested dictionary of metrics to the Logger by flattening keys with slash separators', 'create a TFLogger instance that logs scalars to both TensorBoard and a CSV file', 'update the CSV file in TFLogger by writing all new scalar values since the last update', 'apply the weight_init function to a PyTorch model using model.apply(weight_init)', 'initialize Conv1d, Conv2d, and Conv3d layer weights with normal or xavier_normal initialization', 'initialize BatchNorm1d, BatchNorm2d, and BatchNorm3d layer weights with mean=1 and std=0.02', 'initialize Linear layer weights with xavier_normal and bias with normal initialization', 'initialize LSTM, GRU, LSTMCell, and GRUCell parameters with orthogonal or normal initialization']
```

Usage

```
{'make_atari_env': 'build an Atari environment with NoopResetEnv and MaxAndSkipEnv wrappers for a given env_id', 'wrap_deepmind_env': 'wrap an Atari environment with DeepMind-style preprocessing including frame stacking and reward clipping', 'wrap_pytorch_env': 'wrap an environment to convert image observations from HWC to CHW format for PyTorch', 'use_FrameStack_wrapper': 'create a FrameStack wrapper that stacks k last frames into a single observation for temporal context', 'use_WarpFrame_wrapper': 'apply a WarpFrame wrapper to resize and grayscale Atari frames to 84x84'}
```

## File: facebookresearch_rlstructures/rlalgos/logger.py

Prompts

```
['build an Atari environment with NoopResetEnv and MaxAndSkipEnv wrappers for a given env_id', 'wrap an Atari environment with DeepMind-style preprocessing including frame stacking and reward clipping', 'wrap an environment to convert image observations from HWC to CHW format for PyTorch', 'create a FrameStack wrapper that stacks k last frames into a single observation for temporal context', 'apply a WarpFrame wrapper to resize and grayscale Atari frames to 84x84', 'create a Logger instance to store experimental measures in memory with config hyperparameters', 'add a scalar value to the Logger at a given training iteration for tracking metrics', 'add a nested dictionary of metrics to the Logger by flattening keys with slash separators', 'create a TFLogger instance that logs scalars to both TensorBoard and a CSV file', 'update the CSV file in TFLogger by writing all new scalar values since the last update', 'apply the weight_init function to a PyTorch model using model.apply(weight_init)', 'initialize Conv1d, Conv2d, and Conv3d layer weights with normal or xavier_normal initialization', 'initialize BatchNorm1d, BatchNorm2d, and BatchNorm3d layer weights with mean=1 and std=0.02', 'initialize Linear layer weights with xavier_normal and bias with normal initialization', 'initialize LSTM, GRU, LSTMCell, and GRUCell parameters with orthogonal or normal initialization']
```

Usage

```
{'create_Logger': 'create a Logger instance to store experimental measures in memory with config hyperparameters', 'add_scalar_to_Logger': 'add a scalar value to the Logger at a given training iteration for tracking metrics', 'add_dict_to_Logger': 'add a nested dictionary of metrics to the Logger by flattening keys with slash separators', 'create_TFLogger': 'create a TFLogger instance that logs scalars to both TensorBoard and a CSV file', 'update_csv_in_TFLogger': 'update the CSV file in TFLogger by writing all new scalar values since the last update'}
```

## File: facebookresearch_rlstructures/rlalgos/tools.py

Prompts

```
['build an Atari environment with NoopResetEnv and MaxAndSkipEnv wrappers for a given env_id', 'wrap an Atari environment with DeepMind-style preprocessing including frame stacking and reward clipping', 'wrap an environment to convert image observations from HWC to CHW format for PyTorch', 'create a FrameStack wrapper that stacks k last frames into a single observation for temporal context', 'apply a WarpFrame wrapper to resize and grayscale Atari frames to 84x84', 'create a Logger instance to store experimental measures in memory with config hyperparameters', 'add a scalar value to the Logger at a given training iteration for tracking metrics', 'add a nested dictionary of metrics to the Logger by flattening keys with slash separators', 'create a TFLogger instance that logs scalars to both TensorBoard and a CSV file', 'update the CSV file in TFLogger by writing all new scalar values since the last update', 'apply the weight_init function to a PyTorch model using model.apply(weight_init)', 'initialize Conv1d, Conv2d, and Conv3d layer weights with normal or xavier_normal initialization', 'initialize BatchNorm1d, BatchNorm2d, and BatchNorm3d layer weights with mean=1 and std=0.02', 'initialize Linear layer weights with xavier_normal and bias with normal initialization', 'initialize LSTM, GRU, LSTMCell, and GRUCell parameters with orthogonal or normal initialization']
```

Usage

```
{'apply_weight_init_to_model': 'apply the weight_init function to a PyTorch model using model.apply(weight_init)', 'initialize_conv_layers': 'initialize Conv1d, Conv2d, and Conv3d layer weights with normal or xavier_normal initialization', 'initialize_batch_norm_layers': 'initialize BatchNorm1d, BatchNorm2d, and BatchNorm3d layer weights with mean=1 and std=0.02', 'initialize_linear_layers': 'initialize Linear layer weights with xavier_normal and bias with normal initialization', 'initialize_rnn_layers': 'initialize LSTM, GRU, LSTMCell, and GRUCell parameters with orthogonal or normal initialization'}
```

