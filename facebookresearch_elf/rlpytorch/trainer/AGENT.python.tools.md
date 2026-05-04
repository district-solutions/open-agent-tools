# Agent Python Tools

- repo: facebookresearch/elf
- repo_uri: https://github.com/facebookresearch/elf

## File: facebookresearch_elf/rlpytorch/trainer/lstm_trainer.py

Prompts

```
['create an LSTMTrainer instance with verbose logging for reinforcement learning training', 'setup the LSTMTrainer with an RL method, model interface, and sampler', 'run the actor method to sample actions from the current model state', 'train the LSTMTrainer model on a batch and update weights periodically', 'print the episode summary with counter stats and reset after 10000 completions', 'create an RLTimer instance to track durations and counts of named operations in a reinforcement learning training loop', 'record a named timing event with RLTimer.Record to measure elapsed microseconds between consecutive calls', 'print average timing statistics per named operation and total duration per step using RLTimer.Print', 'use RLTimer.PrintInterval to periodically invoke a callback and restart the timer every nstep records', 'check if a named operation has reached a periodic milestone using RLTimer.CheckPeriodicCondition', 'create an Evaluator instance with stats tracking and a custom actor name for RL evaluation', 'run the Evaluator actor method to forward a batch through the model and sample an action', 'setup the Evaluator with a ModelInterface and Sampler to prepare for evaluation episodes', 'train the RL model by calling Trainer.train with a batch to update weights via the RL method', 'setup the Trainer with an RLMethod, ModelInterface, and Sampler to begin training episodes', 'create a SymLink instance to manage rotating symlinks for the latest K checkpoint files', 'create a ModelSaver instance to save model checkpoints with automatic symlink rotation', 'create a ValueStats instance to track running min, max, and average of fed values', 'call topk_accuracy with output and target tensors to compute precision at k for classification', 'create a MultiCounter instance to increment and summarize counts across multiple named keys']
```

Usage

```
{'create_LSTMTrainer': 'create an LSTMTrainer instance with verbose logging for reinforcement learning training', 'setup_LSTMTrainer': 'setup the LSTMTrainer with an RL method, model interface, and sampler', 'run_actor_loop': 'run the actor method to sample actions from the current model state', 'train_LSTMTrainer': 'train the LSTMTrainer model on a batch and update weights periodically', 'print_episode_summary': 'print the episode summary with counter stats and reset after 10000 completions'}
```

## File: facebookresearch_elf/rlpytorch/trainer/timer.py

Prompts

```
['create an LSTMTrainer instance with verbose logging for reinforcement learning training', 'setup the LSTMTrainer with an RL method, model interface, and sampler', 'run the actor method to sample actions from the current model state', 'train the LSTMTrainer model on a batch and update weights periodically', 'print the episode summary with counter stats and reset after 10000 completions', 'create an RLTimer instance to track durations and counts of named operations in a reinforcement learning training loop', 'record a named timing event with RLTimer.Record to measure elapsed microseconds between consecutive calls', 'print average timing statistics per named operation and total duration per step using RLTimer.Print', 'use RLTimer.PrintInterval to periodically invoke a callback and restart the timer every nstep records', 'check if a named operation has reached a periodic milestone using RLTimer.CheckPeriodicCondition', 'create an Evaluator instance with stats tracking and a custom actor name for RL evaluation', 'run the Evaluator actor method to forward a batch through the model and sample an action', 'setup the Evaluator with a ModelInterface and Sampler to prepare for evaluation episodes', 'train the RL model by calling Trainer.train with a batch to update weights via the RL method', 'setup the Trainer with an RLMethod, ModelInterface, and Sampler to begin training episodes', 'create a SymLink instance to manage rotating symlinks for the latest K checkpoint files', 'create a ModelSaver instance to save model checkpoints with automatic symlink rotation', 'create a ValueStats instance to track running min, max, and average of fed values', 'call topk_accuracy with output and target tensors to compute precision at k for classification', 'create a MultiCounter instance to increment and summarize counts across multiple named keys']
```

Usage

```
{'create_RLTimer': 'create an RLTimer instance to track durations and counts of named operations in a reinforcement learning training loop', 'record_RLTimer': 'record a named timing event with RLTimer.Record to measure elapsed microseconds between consecutive calls', 'print_RLTimer': 'print average timing statistics per named operation and total duration per step using RLTimer.Print', 'printinterval_RLTimer': 'use RLTimer.PrintInterval to periodically invoke a callback and restart the timer every nstep records', 'checkperiodiccondition_RLTimer': 'check if a named operation has reached a periodic milestone using RLTimer.CheckPeriodicCondition'}
```

## File: facebookresearch_elf/rlpytorch/trainer/trainer.py

Prompts

```
['create an LSTMTrainer instance with verbose logging for reinforcement learning training', 'setup the LSTMTrainer with an RL method, model interface, and sampler', 'run the actor method to sample actions from the current model state', 'train the LSTMTrainer model on a batch and update weights periodically', 'print the episode summary with counter stats and reset after 10000 completions', 'create an RLTimer instance to track durations and counts of named operations in a reinforcement learning training loop', 'record a named timing event with RLTimer.Record to measure elapsed microseconds between consecutive calls', 'print average timing statistics per named operation and total duration per step using RLTimer.Print', 'use RLTimer.PrintInterval to periodically invoke a callback and restart the timer every nstep records', 'check if a named operation has reached a periodic milestone using RLTimer.CheckPeriodicCondition', 'create an Evaluator instance with stats tracking and a custom actor name for RL evaluation', 'run the Evaluator actor method to forward a batch through the model and sample an action', 'setup the Evaluator with a ModelInterface and Sampler to prepare for evaluation episodes', 'train the RL model by calling Trainer.train with a batch to update weights via the RL method', 'setup the Trainer with an RLMethod, ModelInterface, and Sampler to begin training episodes', 'create a SymLink instance to manage rotating symlinks for the latest K checkpoint files', 'create a ModelSaver instance to save model checkpoints with automatic symlink rotation', 'create a ValueStats instance to track running min, max, and average of fed values', 'call topk_accuracy with output and target tensors to compute precision at k for classification', 'create a MultiCounter instance to increment and summarize counts across multiple named keys']
```

Usage

```
{'create_Evaluator': 'create an Evaluator instance with stats tracking and a custom actor name for RL evaluation', 'run_Evaluator_actor': 'run the Evaluator actor method to forward a batch through the model and sample an action', 'setup_Evaluator': 'setup the Evaluator with a ModelInterface and Sampler to prepare for evaluation episodes', 'train_Trainer': 'train the RL model by calling Trainer.train with a batch to update weights via the RL method', 'setup_Trainer': 'setup the Trainer with an RLMethod, ModelInterface, and Sampler to begin training episodes'}
```

## File: facebookresearch_elf/rlpytorch/trainer/utils.py

Prompts

```
['create an LSTMTrainer instance with verbose logging for reinforcement learning training', 'setup the LSTMTrainer with an RL method, model interface, and sampler', 'run the actor method to sample actions from the current model state', 'train the LSTMTrainer model on a batch and update weights periodically', 'print the episode summary with counter stats and reset after 10000 completions', 'create an RLTimer instance to track durations and counts of named operations in a reinforcement learning training loop', 'record a named timing event with RLTimer.Record to measure elapsed microseconds between consecutive calls', 'print average timing statistics per named operation and total duration per step using RLTimer.Print', 'use RLTimer.PrintInterval to periodically invoke a callback and restart the timer every nstep records', 'check if a named operation has reached a periodic milestone using RLTimer.CheckPeriodicCondition', 'create an Evaluator instance with stats tracking and a custom actor name for RL evaluation', 'run the Evaluator actor method to forward a batch through the model and sample an action', 'setup the Evaluator with a ModelInterface and Sampler to prepare for evaluation episodes', 'train the RL model by calling Trainer.train with a batch to update weights via the RL method', 'setup the Trainer with an RLMethod, ModelInterface, and Sampler to begin training episodes', 'create a SymLink instance to manage rotating symlinks for the latest K checkpoint files', 'create a ModelSaver instance to save model checkpoints with automatic symlink rotation', 'create a ValueStats instance to track running min, max, and average of fed values', 'call topk_accuracy with output and target tensors to compute precision at k for classification', 'create a MultiCounter instance to increment and summarize counts across multiple named keys']
```

Usage

```
{'create_symlink_manager': 'create a SymLink instance to manage rotating symlinks for the latest K checkpoint files', 'save_model_checkpoints': 'create a ModelSaver instance to save model checkpoints with automatic symlink rotation', 'track_value_statistics': 'create a ValueStats instance to track running min, max, and average of fed values', 'compute_topk_accuracy': 'call topk_accuracy with output and target tensors to compute precision at k for classification', 'track_multi_key_counts': 'create a MultiCounter instance to increment and summarize counts across multiple named keys'}
```

