# Agent Python Tools

- repo: facebookresearch/collaq
- repo_uri: https://github.com/facebookresearch/collaq

## File: facebookresearch_collaq/third_party/pymarl/src/utils/dict2namedtuple.py

Prompts

```
['convert a dictionary into a namedtuple so values are accessible as dot-notation attributes', 'convert a dictionary to a GenericDict namedtuple to enable attribute-style key access', 'convert a dictionary into an immutable namedtuple for read-only attribute access', 'review the convert function that transforms a dictionary into a namedtuple with keys as field names', 'test the convert function by passing a sample dictionary and verifying attribute access works', 'create a Logger instance with a console_logger to track training stats', 'setup TensorBoard logging for the Logger by calling setup_tb with a directory name', 'setup Sacred experiment tracking for the Logger by calling setup_sacred with a run dict', 'log a stat key value pair with timestamp to the Logger and optional backends', 'get a configured root logger with StreamHandler and DEBUG level for console output', 'build TD(lambda) targets for reinforcement learning using rewards, terminated flags, masks, and target Q-values', 'create lambda-return values from t=0 to t=T-1 for multi-agent RL training episodes', 'test the build_td_lambda_targets function with PyTorch tensors for rewards and target Q-values', 'refactor the rl_utils module to support additional TD target computation strategies', 'summarize the build_td_lambda_targets function that computes backward recursive forward view lambda returns', 'print training episode progress with elapsed time, time left, and recent episode rewards', 'calculate estimated time remaining for a training run based on start time and current progress', 'convert a number of seconds into a human-readable string showing days, hours, minutes, and seconds', 'refactor the print_time function to support custom formatting or additional training metrics', 'review the timehelper module functions for time estimation and progress printing utilities']
```

Usage

```
{'convert_dict_to_namedtuple': 'convert a dictionary into a namedtuple so values are accessible as dot-notation attributes', 'convert_dict_for_attribute_access': 'convert a dictionary to a GenericDict namedtuple to enable attribute-style key access', 'convert_dict_for_immutable_access': 'convert a dictionary into an immutable namedtuple for read-only attribute access', 'review_convert_function': 'review the convert function that transforms a dictionary into a namedtuple with keys as field names', 'test_convert_function': 'test the convert function by passing a sample dictionary and verifying attribute access works'}
```

## File: facebookresearch_collaq/third_party/pymarl/src/utils/logging.py

Prompts

```
['convert a dictionary into a namedtuple so values are accessible as dot-notation attributes', 'convert a dictionary to a GenericDict namedtuple to enable attribute-style key access', 'convert a dictionary into an immutable namedtuple for read-only attribute access', 'review the convert function that transforms a dictionary into a namedtuple with keys as field names', 'test the convert function by passing a sample dictionary and verifying attribute access works', 'create a Logger instance with a console_logger to track training stats', 'setup TensorBoard logging for the Logger by calling setup_tb with a directory name', 'setup Sacred experiment tracking for the Logger by calling setup_sacred with a run dict', 'log a stat key value pair with timestamp to the Logger and optional backends', 'get a configured root logger with StreamHandler and DEBUG level for console output', 'build TD(lambda) targets for reinforcement learning using rewards, terminated flags, masks, and target Q-values', 'create lambda-return values from t=0 to t=T-1 for multi-agent RL training episodes', 'test the build_td_lambda_targets function with PyTorch tensors for rewards and target Q-values', 'refactor the rl_utils module to support additional TD target computation strategies', 'summarize the build_td_lambda_targets function that computes backward recursive forward view lambda returns', 'print training episode progress with elapsed time, time left, and recent episode rewards', 'calculate estimated time remaining for a training run based on start time and current progress', 'convert a number of seconds into a human-readable string showing days, hours, minutes, and seconds', 'refactor the print_time function to support custom formatting or additional training metrics', 'review the timehelper module functions for time estimation and progress printing utilities']
```

Usage

```
{'create_logger': 'create a Logger instance with a console_logger to track training stats', 'setup_tensorboard': 'setup TensorBoard logging for the Logger by calling setup_tb with a directory name', 'setup_sacred': 'setup Sacred experiment tracking for the Logger by calling setup_sacred with a run dict', 'log_stat': 'log a stat key value pair with timestamp to the Logger and optional backends', 'get_logger': 'get a configured root logger with StreamHandler and DEBUG level for console output'}
```

## File: facebookresearch_collaq/third_party/pymarl/src/utils/rl_utils.py

Prompts

```
['convert a dictionary into a namedtuple so values are accessible as dot-notation attributes', 'convert a dictionary to a GenericDict namedtuple to enable attribute-style key access', 'convert a dictionary into an immutable namedtuple for read-only attribute access', 'review the convert function that transforms a dictionary into a namedtuple with keys as field names', 'test the convert function by passing a sample dictionary and verifying attribute access works', 'create a Logger instance with a console_logger to track training stats', 'setup TensorBoard logging for the Logger by calling setup_tb with a directory name', 'setup Sacred experiment tracking for the Logger by calling setup_sacred with a run dict', 'log a stat key value pair with timestamp to the Logger and optional backends', 'get a configured root logger with StreamHandler and DEBUG level for console output', 'build TD(lambda) targets for reinforcement learning using rewards, terminated flags, masks, and target Q-values', 'create lambda-return values from t=0 to t=T-1 for multi-agent RL training episodes', 'test the build_td_lambda_targets function with PyTorch tensors for rewards and target Q-values', 'refactor the rl_utils module to support additional TD target computation strategies', 'summarize the build_td_lambda_targets function that computes backward recursive forward view lambda returns', 'print training episode progress with elapsed time, time left, and recent episode rewards', 'calculate estimated time remaining for a training run based on start time and current progress', 'convert a number of seconds into a human-readable string showing days, hours, minutes, and seconds', 'refactor the print_time function to support custom formatting or additional training metrics', 'review the timehelper module functions for time estimation and progress printing utilities']
```

Usage

```
{'build_td_lambda_targets': 'build TD(lambda) targets for reinforcement learning using rewards, terminated flags, masks, and target Q-values', 'create_rl_lambda_returns': 'create lambda-return values from t=0 to t=T-1 for multi-agent RL training episodes', 'test_build_td_lambda_targets': 'test the build_td_lambda_targets function with PyTorch tensors for rewards and target Q-values', 'refactor_rl_utils': 'refactor the rl_utils module to support additional TD target computation strategies', 'summarize_build_td_lambda_targets': 'summarize the build_td_lambda_targets function that computes backward recursive forward view lambda returns'}
```

## File: facebookresearch_collaq/third_party/pymarl/src/utils/timehelper.py

Prompts

```
['convert a dictionary into a namedtuple so values are accessible as dot-notation attributes', 'convert a dictionary to a GenericDict namedtuple to enable attribute-style key access', 'convert a dictionary into an immutable namedtuple for read-only attribute access', 'review the convert function that transforms a dictionary into a namedtuple with keys as field names', 'test the convert function by passing a sample dictionary and verifying attribute access works', 'create a Logger instance with a console_logger to track training stats', 'setup TensorBoard logging for the Logger by calling setup_tb with a directory name', 'setup Sacred experiment tracking for the Logger by calling setup_sacred with a run dict', 'log a stat key value pair with timestamp to the Logger and optional backends', 'get a configured root logger with StreamHandler and DEBUG level for console output', 'build TD(lambda) targets for reinforcement learning using rewards, terminated flags, masks, and target Q-values', 'create lambda-return values from t=0 to t=T-1 for multi-agent RL training episodes', 'test the build_td_lambda_targets function with PyTorch tensors for rewards and target Q-values', 'refactor the rl_utils module to support additional TD target computation strategies', 'summarize the build_td_lambda_targets function that computes backward recursive forward view lambda returns', 'print training episode progress with elapsed time, time left, and recent episode rewards', 'calculate estimated time remaining for a training run based on start time and current progress', 'convert a number of seconds into a human-readable string showing days, hours, minutes, and seconds', 'refactor the print_time function to support custom formatting or additional training metrics', 'review the timehelper module functions for time estimation and progress printing utilities']
```

Usage

```
{'print_training_progress': 'print training episode progress with elapsed time, time left, and recent episode rewards', 'calculate_time_left': 'calculate estimated time remaining for a training run based on start time and current progress', 'convert_seconds_to_readable': 'convert a number of seconds into a human-readable string showing days, hours, minutes, and seconds', 'refactor_print_time': 'refactor the print_time function to support custom formatting or additional training metrics', 'review_timehelper_module': 'review the timehelper module functions for time estimation and progress printing utilities'}
```

