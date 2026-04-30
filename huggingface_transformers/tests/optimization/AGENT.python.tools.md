# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/optimization/test_greedy_lr.py

Prompts

```
['create a GreedyLR learning rate scheduler that adapts LR based on metric plateau behavior', 'test GreedyLR decreases LR when metrics plateau for more than patience steps', 'build a StreamingAverage with a fixed window size for smoothing metric values', 'use get_greedy_schedule factory function to create a GreedyLR scheduler from an optimizer', 'test GreedyLR state_dict and load_state_dict round trip preserves scheduler state', 'test the AdamW optimizer converges to target values using mean squared error loss over 100 training steps', 'test the Adafactor optimizer converges to target values using mean squared error loss over 1000 training steps', 'test learning rate schedules including constant, linear, cosine, polynomial decay, inverse sqrt, and WSD schedules with warmup', 'test saving and reloading scheduler state via torch.save and torch.load preserves learning rate progression', 'test the get_scheduler factory function with warmup_stable_decay and cosine scheduler configurations']
```

Usage

```
{'create_scheduler_greedy_lr': 'create a GreedyLR learning rate scheduler that adapts LR based on metric plateau behavior', 'test_greedy_lr_plateau_reduction': 'test GreedyLR decreases LR when metrics plateau for more than patience steps', 'build_streaming_average': 'build a StreamingAverage with a fixed window size for smoothing metric values', 'use_factory_get_greedy_schedule': 'use get_greedy_schedule factory function to create a GreedyLR scheduler from an optimizer', 'test_state_dict_round_trip': 'test GreedyLR state_dict and load_state_dict round trip preserves scheduler state'}
```

## File: huggingface_transformers/tests/optimization/test_optimization.py

Prompts

```
['create a GreedyLR learning rate scheduler that adapts LR based on metric plateau behavior', 'test GreedyLR decreases LR when metrics plateau for more than patience steps', 'build a StreamingAverage with a fixed window size for smoothing metric values', 'use get_greedy_schedule factory function to create a GreedyLR scheduler from an optimizer', 'test GreedyLR state_dict and load_state_dict round trip preserves scheduler state', 'test the AdamW optimizer converges to target values using mean squared error loss over 100 training steps', 'test the Adafactor optimizer converges to target values using mean squared error loss over 1000 training steps', 'test learning rate schedules including constant, linear, cosine, polynomial decay, inverse sqrt, and WSD schedules with warmup', 'test saving and reloading scheduler state via torch.save and torch.load preserves learning rate progression', 'test the get_scheduler factory function with warmup_stable_decay and cosine scheduler configurations']
```

Usage

```
{'test_adam_w_optimizer': 'test the AdamW optimizer converges to target values using mean squared error loss over 100 training steps', 'test_adafactor_optimizer': 'test the Adafactor optimizer converges to target values using mean squared error loss over 1000 training steps', 'test_learning_rate_schedules': 'test learning rate schedules including constant, linear, cosine, polynomial decay, inverse sqrt, and WSD schedules with warmup', 'test_scheduler_state_save_reload': 'test saving and reloading scheduler state via torch.save and torch.load preserves learning rate progression', 'test_get_scheduler_factory': 'test the get_scheduler factory function with warmup_stable_decay and cosine scheduler configurations'}
```

