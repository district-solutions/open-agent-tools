# Agent Python Tools

- repo: facebookresearch/hgnn
- repo_uri: https://github.com/facebookresearch/hgnn

## File: facebookresearch_hgnn/utils/EarlyStoppingCriterion.py

Prompts

```
['create an EarlyStoppingCriterion instance with max mode to track best validation accuracy during training', 'create an EarlyStoppingCriterion instance with min mode and patience 5 to monitor training loss', 'run the step method with current dev and test scores to check if training should continue', 'test the EarlyStoppingCriterion class to verify it stops training after patience epochs without improvement', 'review the EarlyStoppingCriterion constructor to understand patience, mode, and min_delta parameter validation', 'create a logger that writes debug logs to a file and info logs to the console', 'create a LogFormatter that prefixes log messages with level name, timestamp, and elapsed time', 'reset the logger elapsed time by calling the reset_time method on the logger object', 'format a log message that replaces newlines with indented lines to align with the prefix', 'configure a logger with debug level for file output and info level for console output', 'initialize PyTorch module weights using orthogonal, xavier, or kaiming methods via nn_init', 'create an SGD, Adam, or AMSGrad optimizer from args and parameter list using get_optimizer', 'create a RiemannianSGD or RiemannianAMSGrad hyperbolic optimizer from args and params using get_hyperbolic_optimizer', 'set up euclidean and hyperbolic optimizers with LR schedulers using set_up_optimizer_scheduler', 'categorize model parameters into hyperbolic and euclidean groups using categorize_params']
```

Usage

```
{'create_EarlyStoppingCriterion_max_mode': 'create an EarlyStoppingCriterion instance with max mode to track best validation accuracy during training', 'create_EarlyStoppingCriterion_min_mode': 'create an EarlyStoppingCriterion instance with min mode and patience 5 to monitor training loss', 'run_EarlyStoppingCriterion_step': 'run the step method with current dev and test scores to check if training should continue', 'test_EarlyStoppingCriterion_patience': 'test the EarlyStoppingCriterion class to verify it stops training after patience epochs without improvement', 'review_EarlyStoppingCriterion_init': 'review the EarlyStoppingCriterion constructor to understand patience, mode, and min_delta parameter validation'}
```

## File: facebookresearch_hgnn/utils/logger.py

Prompts

```
['create an EarlyStoppingCriterion instance with max mode to track best validation accuracy during training', 'create an EarlyStoppingCriterion instance with min mode and patience 5 to monitor training loss', 'run the step method with current dev and test scores to check if training should continue', 'test the EarlyStoppingCriterion class to verify it stops training after patience epochs without improvement', 'review the EarlyStoppingCriterion constructor to understand patience, mode, and min_delta parameter validation', 'create a logger that writes debug logs to a file and info logs to the console', 'create a LogFormatter that prefixes log messages with level name, timestamp, and elapsed time', 'reset the logger elapsed time by calling the reset_time method on the logger object', 'format a log message that replaces newlines with indented lines to align with the prefix', 'configure a logger with debug level for file output and info level for console output', 'initialize PyTorch module weights using orthogonal, xavier, or kaiming methods via nn_init', 'create an SGD, Adam, or AMSGrad optimizer from args and parameter list using get_optimizer', 'create a RiemannianSGD or RiemannianAMSGrad hyperbolic optimizer from args and params using get_hyperbolic_optimizer', 'set up euclidean and hyperbolic optimizers with LR schedulers using set_up_optimizer_scheduler', 'categorize model parameters into hyperbolic and euclidean groups using categorize_params']
```

Usage

```
{'create_logger_with_file_and_console_handlers': 'create a logger that writes debug logs to a file and info logs to the console', 'create_log_formatter_with_elapsed_time': 'create a LogFormatter that prefixes log messages with level name, timestamp, and elapsed time', 'reset_logger_elapsed_time': 'reset the logger elapsed time by calling the reset_time method on the logger object', 'format_log_message_with_multiline_support': 'format a log message that replaces newlines with indented lines to align with the prefix', 'configure_logger_debug_and_info_levels': 'configure a logger with debug level for file output and info level for console output'}
```

## File: facebookresearch_hgnn/utils/utils.py

Prompts

```
['create an EarlyStoppingCriterion instance with max mode to track best validation accuracy during training', 'create an EarlyStoppingCriterion instance with min mode and patience 5 to monitor training loss', 'run the step method with current dev and test scores to check if training should continue', 'test the EarlyStoppingCriterion class to verify it stops training after patience epochs without improvement', 'review the EarlyStoppingCriterion constructor to understand patience, mode, and min_delta parameter validation', 'create a logger that writes debug logs to a file and info logs to the console', 'create a LogFormatter that prefixes log messages with level name, timestamp, and elapsed time', 'reset the logger elapsed time by calling the reset_time method on the logger object', 'format a log message that replaces newlines with indented lines to align with the prefix', 'configure a logger with debug level for file output and info level for console output', 'initialize PyTorch module weights using orthogonal, xavier, or kaiming methods via nn_init', 'create an SGD, Adam, or AMSGrad optimizer from args and parameter list using get_optimizer', 'create a RiemannianSGD or RiemannianAMSGrad hyperbolic optimizer from args and params using get_hyperbolic_optimizer', 'set up euclidean and hyperbolic optimizers with LR schedulers using set_up_optimizer_scheduler', 'categorize model parameters into hyperbolic and euclidean groups using categorize_params']
```

Usage

```
{'init_nn_module_weights': 'initialize PyTorch module weights using orthogonal, xavier, or kaiming methods via nn_init', 'get_optimizer_for_params': 'create an SGD, Adam, or AMSGrad optimizer from args and parameter list using get_optimizer', 'get_hyperbolic_optimizer_for_params': 'create a RiemannianSGD or RiemannianAMSGrad hyperbolic optimizer from args and params using get_hyperbolic_optimizer', 'set_up_optimizer_and_scheduler': 'set up euclidean and hyperbolic optimizers with LR schedulers using set_up_optimizer_scheduler', 'categorize_model_params': 'categorize model parameters into hyperbolic and euclidean groups using categorize_params'}
```

