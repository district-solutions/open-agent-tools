# Agent Python Tools

- repo: facebookresearch/pearl
- repo_uri: https://github.com/facebookresearch/pearl

## File: facebookresearch_pearl/pearl/utils/functional_utils/train_and_eval/learning_logger.py

Prompts

```
['implement a custom LearningLogger protocol class that logs training results to a file or database', 'use the LearningLogger protocol to type hint a callable that logs batch results during training', 'call the null_learning_logger function as a no-op logger when logging is disabled', 'replace the null_learning_logger with a custom logger to enable result tracking during training', 'review the LearningLogger protocol to understand the required __call__ signature for batch logging', 'fetch offline RL transition data from a URL or local .pt file into a BasicReplayBuffer', 'train a PearlAgent on offline data by sampling batches from a ReplayBuffer for N epochs', 'evaluate an offline trained PearlAgent in an Environment over multiple episodes and return episode returns', 'check if a file path exists and is readable by the current process', 'review the offline learning and evaluation utilities for offline RL training and agent evaluation', 'run online learning for a PearlAgent in an Environment for a specified number of episodes', 'generate a PNG graph of returns from online learning episodes for a PearlAgent', 'run learning until a PearlAgent reaches a target return value within max episodes', 'run a single episode with a PearlAgent in an Environment and return episode info and steps', 'calculate the latest moving average of episode returns using a fixed window size']
```

Usage

```
{'implement_LearningLogger_protocol': 'implement a custom LearningLogger protocol class that logs training results to a file or database', 'use_LearningLogger_protocol': 'use the LearningLogger protocol to type hint a callable that logs batch results during training', 'call_null_learning_logger': 'call the null_learning_logger function as a no-op logger when logging is disabled', 'replace_null_learning_logger': 'replace the null_learning_logger with a custom logger to enable result tracking during training', 'review_LearningLogger_protocol': 'review the LearningLogger protocol to understand the required __call__ signature for batch logging'}
```

## File: facebookresearch_pearl/pearl/utils/functional_utils/train_and_eval/offline_learning_and_evaluation.py

Prompts

```
['implement a custom LearningLogger protocol class that logs training results to a file or database', 'use the LearningLogger protocol to type hint a callable that logs batch results during training', 'call the null_learning_logger function as a no-op logger when logging is disabled', 'replace the null_learning_logger with a custom logger to enable result tracking during training', 'review the LearningLogger protocol to understand the required __call__ signature for batch logging', 'fetch offline RL transition data from a URL or local .pt file into a BasicReplayBuffer', 'train a PearlAgent on offline data by sampling batches from a ReplayBuffer for N epochs', 'evaluate an offline trained PearlAgent in an Environment over multiple episodes and return episode returns', 'check if a file path exists and is readable by the current process', 'review the offline learning and evaluation utilities for offline RL training and agent evaluation', 'run online learning for a PearlAgent in an Environment for a specified number of episodes', 'generate a PNG graph of returns from online learning episodes for a PearlAgent', 'run learning until a PearlAgent reaches a target return value within max episodes', 'run a single episode with a PearlAgent in an Environment and return episode info and steps', 'calculate the latest moving average of episode returns using a fixed window size']
```

Usage

```
{'get_offline_data_in_buffer': 'fetch offline RL transition data from a URL or local .pt file into a BasicReplayBuffer', 'offline_learning': 'train a PearlAgent on offline data by sampling batches from a ReplayBuffer for N epochs', 'offline_evaluation': 'evaluate an offline trained PearlAgent in an Environment over multiple episodes and return episode returns', 'is_file_readable': 'check if a file path exists and is readable by the current process', 'review_offline_learning_and_evaluation': 'review the offline learning and evaluation utilities for offline RL training and agent evaluation'}
```

## File: facebookresearch_pearl/pearl/utils/functional_utils/train_and_eval/online_learning.py

Prompts

```
['implement a custom LearningLogger protocol class that logs training results to a file or database', 'use the LearningLogger protocol to type hint a callable that logs batch results during training', 'call the null_learning_logger function as a no-op logger when logging is disabled', 'replace the null_learning_logger with a custom logger to enable result tracking during training', 'review the LearningLogger protocol to understand the required __call__ signature for batch logging', 'fetch offline RL transition data from a URL or local .pt file into a BasicReplayBuffer', 'train a PearlAgent on offline data by sampling batches from a ReplayBuffer for N epochs', 'evaluate an offline trained PearlAgent in an Environment over multiple episodes and return episode returns', 'check if a file path exists and is readable by the current process', 'review the offline learning and evaluation utilities for offline RL training and agent evaluation', 'run online learning for a PearlAgent in an Environment for a specified number of episodes', 'generate a PNG graph of returns from online learning episodes for a PearlAgent', 'run learning until a PearlAgent reaches a target return value within max episodes', 'run a single episode with a PearlAgent in an Environment and return episode info and steps', 'calculate the latest moving average of episode returns using a fixed window size']
```

Usage

```
{'run_online_learning': 'run online learning for a PearlAgent in an Environment for a specified number of episodes', 'run_online_learning_to_png': 'generate a PNG graph of returns from online learning episodes for a PearlAgent', 'run_target_return_check': 'run learning until a PearlAgent reaches a target return value within max episodes', 'run_single_episode': 'run a single episode with a PearlAgent in an Environment and return episode info and steps', 'run_moving_average': 'calculate the latest moving average of episode returns using a fixed window size'}
```

