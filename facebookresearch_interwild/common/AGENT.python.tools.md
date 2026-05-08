# Agent Python Tools

- repo: facebookresearch/interwild
- repo_uri: https://github.com/facebookresearch/interwild

## File: facebookresearch_interwild/common/base.py

Prompts

```
['create an Adam optimizer for trainable modules using the Trainer get_optimizer method', 'save a model snapshot excluding mano_layer weights using the Trainer save_model method', 'load the latest model checkpoint and optimizer state using the Trainer load_model method', 'set the learning rate with step decay schedule using the Trainer set_lr method', 'run model evaluation on test data using the Tester _evaluate and _print_eval_result methods', 'create a colorlogger instance that writes colored log messages to a file and console', 'log an info message to both the console and log file using the colorlogger info method', 'log a warning message with yellow coloring and WRN prefix using the colorlogger warning method', 'log an error message with red coloring and ERR prefix using the colorlogger error method', 'log a critical message with red coloring and CRI prefix using the colorlogger critical method', 'create a Timer instance to track elapsed time for a code block', 'run a Timer by calling tic before and toc after the code to measure', 'test the Timer class toc method to return average time across multiple calls', 'review the Timer class warm_up logic that skips the first 10 calls from averaging', 'refactor the Timer toc method to return either average or single diff time']
```

Usage

```
{'create_Trainer_optimizer': 'create an Adam optimizer for trainable modules using the Trainer get_optimizer method', 'save_Trainer_model': 'save a model snapshot excluding mano_layer weights using the Trainer save_model method', 'load_Trainer_model': 'load the latest model checkpoint and optimizer state using the Trainer load_model method', 'set_Trainer_lr': 'set the learning rate with step decay schedule using the Trainer set_lr method', 'run_Tester_evaluation': 'run model evaluation on test data using the Tester _evaluate and _print_eval_result methods'}
```

## File: facebookresearch_interwild/common/logger.py

Prompts

```
['create an Adam optimizer for trainable modules using the Trainer get_optimizer method', 'save a model snapshot excluding mano_layer weights using the Trainer save_model method', 'load the latest model checkpoint and optimizer state using the Trainer load_model method', 'set the learning rate with step decay schedule using the Trainer set_lr method', 'run model evaluation on test data using the Tester _evaluate and _print_eval_result methods', 'create a colorlogger instance that writes colored log messages to a file and console', 'log an info message to both the console and log file using the colorlogger info method', 'log a warning message with yellow coloring and WRN prefix using the colorlogger warning method', 'log an error message with red coloring and ERR prefix using the colorlogger error method', 'log a critical message with red coloring and CRI prefix using the colorlogger critical method', 'create a Timer instance to track elapsed time for a code block', 'run a Timer by calling tic before and toc after the code to measure', 'test the Timer class toc method to return average time across multiple calls', 'review the Timer class warm_up logic that skips the first 10 calls from averaging', 'refactor the Timer toc method to return either average or single diff time']
```

Usage

```
{'create_colorlogger': 'create a colorlogger instance that writes colored log messages to a file and console', 'info_logging': 'log an info message to both the console and log file using the colorlogger info method', 'warning_logging': 'log a warning message with yellow coloring and WRN prefix using the colorlogger warning method', 'error_logging': 'log an error message with red coloring and ERR prefix using the colorlogger error method', 'critical_logging': 'log a critical message with red coloring and CRI prefix using the colorlogger critical method'}
```

## File: facebookresearch_interwild/common/timer.py

Prompts

```
['create an Adam optimizer for trainable modules using the Trainer get_optimizer method', 'save a model snapshot excluding mano_layer weights using the Trainer save_model method', 'load the latest model checkpoint and optimizer state using the Trainer load_model method', 'set the learning rate with step decay schedule using the Trainer set_lr method', 'run model evaluation on test data using the Tester _evaluate and _print_eval_result methods', 'create a colorlogger instance that writes colored log messages to a file and console', 'log an info message to both the console and log file using the colorlogger info method', 'log a warning message with yellow coloring and WRN prefix using the colorlogger warning method', 'log an error message with red coloring and ERR prefix using the colorlogger error method', 'log a critical message with red coloring and CRI prefix using the colorlogger critical method', 'create a Timer instance to track elapsed time for a code block', 'run a Timer by calling tic before and toc after the code to measure', 'test the Timer class toc method to return average time across multiple calls', 'review the Timer class warm_up logic that skips the first 10 calls from averaging', 'refactor the Timer toc method to return either average or single diff time']
```

Usage

```
{'create_timer_instance': 'create a Timer instance to track elapsed time for a code block', 'run_timer_tic_toc': 'run a Timer by calling tic before and toc after the code to measure', 'test_timer_average_time': 'test the Timer class toc method to return average time across multiple calls', 'review_timer_warm_up': 'review the Timer class warm_up logic that skips the first 10 calls from averaging', 'refactor_timer_toc': 'refactor the Timer toc method to return either average or single diff time'}
```

