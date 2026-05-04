# Agent Python Tools

- repo: facebookresearch/assemblyhands-toolkit
- repo_uri: https://github.com/facebookresearch/assemblyhands-toolkit

## File: facebookresearch_assemblyhands-toolkit/src/common/base.py

Prompts

```
['create a Trainer instance with a config object to prepare model training with Adam optimizer', 'run the Trainer _make_model method to build a DataParallel model and optimizer for training', 'test the Trainer set_lr method to adjust learning rate based on epoch and decay schedule', 'build a Tester instance with config and test epoch to load a model checkpoint for evaluation', 'run the Tester _evaluate method to evaluate predictions against the test dataset', 'create a colorlogger instance that writes colored logs to a directory and console', 'log an info message with a green timestamp to both file and console', 'log a warning message with a yellow WRN prefix to both file and console', 'log an error message with a red ERR prefix to both file and console', 'log a critical message with a red CRI prefix to both file and console', 'create a Timer instance to track elapsed time for benchmarking code execution', 'start the Timer by calling tic to record the current start time', 'stop the Timer by calling toc to get elapsed time or average time', 'get the average elapsed time across multiple tic/toc calls after warmup period', 'get the single elapsed time diff by calling toc with average set to False']
```

Usage

```
{'create_Trainer': 'create a Trainer instance with a config object to prepare model training with Adam optimizer', 'run_Trainer_make_model': 'run the Trainer _make_model method to build a DataParallel model and optimizer for training', 'test_Trainer_set_lr': 'test the Trainer set_lr method to adjust learning rate based on epoch and decay schedule', 'build_Tester': 'build a Tester instance with config and test epoch to load a model checkpoint for evaluation', 'run_Tester_evaluate': 'run the Tester _evaluate method to evaluate predictions against the test dataset'}
```

## File: facebookresearch_assemblyhands-toolkit/src/common/logger.py

Prompts

```
['create a Trainer instance with a config object to prepare model training with Adam optimizer', 'run the Trainer _make_model method to build a DataParallel model and optimizer for training', 'test the Trainer set_lr method to adjust learning rate based on epoch and decay schedule', 'build a Tester instance with config and test epoch to load a model checkpoint for evaluation', 'run the Tester _evaluate method to evaluate predictions against the test dataset', 'create a colorlogger instance that writes colored logs to a directory and console', 'log an info message with a green timestamp to both file and console', 'log a warning message with a yellow WRN prefix to both file and console', 'log an error message with a red ERR prefix to both file and console', 'log a critical message with a red CRI prefix to both file and console', 'create a Timer instance to track elapsed time for benchmarking code execution', 'start the Timer by calling tic to record the current start time', 'stop the Timer by calling toc to get elapsed time or average time', 'get the average elapsed time across multiple tic/toc calls after warmup period', 'get the single elapsed time diff by calling toc with average set to False']
```

Usage

```
{'create_colorlogger': 'create a colorlogger instance that writes colored logs to a directory and console', 'log_info_message': 'log an info message with a green timestamp to both file and console', 'log_warning_message': 'log a warning message with a yellow WRN prefix to both file and console', 'log_error_message': 'log an error message with a red ERR prefix to both file and console', 'log_critical_message': 'log a critical message with a red CRI prefix to both file and console'}
```

## File: facebookresearch_assemblyhands-toolkit/src/common/timer.py

Prompts

```
['create a Trainer instance with a config object to prepare model training with Adam optimizer', 'run the Trainer _make_model method to build a DataParallel model and optimizer for training', 'test the Trainer set_lr method to adjust learning rate based on epoch and decay schedule', 'build a Tester instance with config and test epoch to load a model checkpoint for evaluation', 'run the Tester _evaluate method to evaluate predictions against the test dataset', 'create a colorlogger instance that writes colored logs to a directory and console', 'log an info message with a green timestamp to both file and console', 'log a warning message with a yellow WRN prefix to both file and console', 'log an error message with a red ERR prefix to both file and console', 'log a critical message with a red CRI prefix to both file and console', 'create a Timer instance to track elapsed time for benchmarking code execution', 'start the Timer by calling tic to record the current start time', 'stop the Timer by calling toc to get elapsed time or average time', 'get the average elapsed time across multiple tic/toc calls after warmup period', 'get the single elapsed time diff by calling toc with average set to False']
```

Usage

```
{'create_timer_instance': 'create a Timer instance to track elapsed time for benchmarking code execution', 'start_timer_with_tic': 'start the Timer by calling tic to record the current start time', 'stop_timer_with_toc': 'stop the Timer by calling toc to get elapsed time or average time', 'get_average_elapsed_time': 'get the average elapsed time across multiple tic/toc calls after warmup period', 'get_single_elapsed_time': 'get the single elapsed time diff by calling toc with average set to False'}
```

