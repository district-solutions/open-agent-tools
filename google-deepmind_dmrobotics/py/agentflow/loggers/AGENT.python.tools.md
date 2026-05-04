# Agent Python Tools

- repo: google-deepmind/dmrobotics
- repo_uri: https://github.com/google-deepmind/dm_robotics

## File: google-deepmind_dmrobotics/py/agentflow/loggers/print_logger.py

Prompts

```
['create a PrintLogger instance that serializes and prints logging values as formatted strings', 'write a dictionary of key-value pairs to the PrintLogger for formatted console output', 'customize the PrintLogger serialize function to format log values with a custom formatter', 'customize the PrintLogger print function to route output to a file or custom handler', 'format float and numpy number values to three decimal places using the _format_value helper', 'create a subclass of Aggregator that implements the accumulate method to log custom subtask data', 'build an EpisodeReturnAggregator to compute episode return and length when a subtask ends', 'configure an EpisodeReturnAggregator with a custom discount factor and custom metric names', 'create a SubTaskLogger with an Acme logger and an Aggregator to log agent performance', 'review the SubTaskLogger step method to understand how it accumulates and writes logging data', 'test the SubtaskLoggerTest class to verify SubTaskLogger episode return logging behavior', 'test the episode return logger to verify rewards and discounts are aggregated correctly', 'run the FakeLogger class to capture and verify logged values as JSON strings', 'test the step through sequence helper to drive observer steps with rewards and discounts', 'review the FakeLogger is_logged method to check if expected kwargs were written to the log', 'compute the discounted return of an RL episode from a list of rewards and discounts', 'test the compute_return function with sample episode rewards and discount sequences', 'refactor compute_return to use numpy for vectorized discounted return calculation', 'review the compute_return function for edge cases with empty or mismatched input sequences', 'summarize the compute_return function which calculates discounted episode return from rewards and discounts', 'run the UtilsTest suite to validate compute_return with simple and random inputs', 'review the UtilsTest class and its parameterized test_compute_return method', 'refactor the UtilsTest class to add additional parameterized test cases for compute_return']
```

Usage

```
{'create_PrintLogger': 'create a PrintLogger instance that serializes and prints logging values as formatted strings', 'write_log_values': 'write a dictionary of key-value pairs to the PrintLogger for formatted console output', 'customize_serialize_fn': 'customize the PrintLogger serialize function to format log values with a custom formatter', 'customize_print_fn': 'customize the PrintLogger print function to route output to a file or custom handler', 'format_numeric_values': 'format float and numpy number values to three decimal places using the _format_value helper'}
```

## File: google-deepmind_dmrobotics/py/agentflow/loggers/subtask_logger.py

Prompts

```
['create a PrintLogger instance that serializes and prints logging values as formatted strings', 'write a dictionary of key-value pairs to the PrintLogger for formatted console output', 'customize the PrintLogger serialize function to format log values with a custom formatter', 'customize the PrintLogger print function to route output to a file or custom handler', 'format float and numpy number values to three decimal places using the _format_value helper', 'create a subclass of Aggregator that implements the accumulate method to log custom subtask data', 'build an EpisodeReturnAggregator to compute episode return and length when a subtask ends', 'configure an EpisodeReturnAggregator with a custom discount factor and custom metric names', 'create a SubTaskLogger with an Acme logger and an Aggregator to log agent performance', 'review the SubTaskLogger step method to understand how it accumulates and writes logging data', 'test the SubtaskLoggerTest class to verify SubTaskLogger episode return logging behavior', 'test the episode return logger to verify rewards and discounts are aggregated correctly', 'run the FakeLogger class to capture and verify logged values as JSON strings', 'test the step through sequence helper to drive observer steps with rewards and discounts', 'review the FakeLogger is_logged method to check if expected kwargs were written to the log', 'compute the discounted return of an RL episode from a list of rewards and discounts', 'test the compute_return function with sample episode rewards and discount sequences', 'refactor compute_return to use numpy for vectorized discounted return calculation', 'review the compute_return function for edge cases with empty or mismatched input sequences', 'summarize the compute_return function which calculates discounted episode return from rewards and discounts', 'run the UtilsTest suite to validate compute_return with simple and random inputs', 'review the UtilsTest class and its parameterized test_compute_return method', 'refactor the UtilsTest class to add additional parameterized test cases for compute_return']
```

Usage

```
{'create_aggregator_subclass': 'create a subclass of Aggregator that implements the accumulate method to log custom subtask data', 'build_episode_return_aggregator': 'build an EpisodeReturnAggregator to compute episode return and length when a subtask ends', 'configure_episode_return_aggregator': 'configure an EpisodeReturnAggregator with a custom discount factor and custom metric names', 'create_subtask_logger': 'create a SubTaskLogger with an Acme logger and an Aggregator to log agent performance', 'review_subtask_logger_step': 'review the SubTaskLogger step method to understand how it accumulates and writes logging data'}
```

## File: google-deepmind_dmrobotics/py/agentflow/loggers/subtask_logger_test.py

Prompts

```
['create a PrintLogger instance that serializes and prints logging values as formatted strings', 'write a dictionary of key-value pairs to the PrintLogger for formatted console output', 'customize the PrintLogger serialize function to format log values with a custom formatter', 'customize the PrintLogger print function to route output to a file or custom handler', 'format float and numpy number values to three decimal places using the _format_value helper', 'create a subclass of Aggregator that implements the accumulate method to log custom subtask data', 'build an EpisodeReturnAggregator to compute episode return and length when a subtask ends', 'configure an EpisodeReturnAggregator with a custom discount factor and custom metric names', 'create a SubTaskLogger with an Acme logger and an Aggregator to log agent performance', 'review the SubTaskLogger step method to understand how it accumulates and writes logging data', 'test the SubtaskLoggerTest class to verify SubTaskLogger episode return logging behavior', 'test the episode return logger to verify rewards and discounts are aggregated correctly', 'run the FakeLogger class to capture and verify logged values as JSON strings', 'test the step through sequence helper to drive observer steps with rewards and discounts', 'review the FakeLogger is_logged method to check if expected kwargs were written to the log', 'compute the discounted return of an RL episode from a list of rewards and discounts', 'test the compute_return function with sample episode rewards and discount sequences', 'refactor compute_return to use numpy for vectorized discounted return calculation', 'review the compute_return function for edge cases with empty or mismatched input sequences', 'summarize the compute_return function which calculates discounted episode return from rewards and discounts', 'run the UtilsTest suite to validate compute_return with simple and random inputs', 'review the UtilsTest class and its parameterized test_compute_return method', 'refactor the UtilsTest class to add additional parameterized test cases for compute_return']
```

Usage

```
{'test_SubtaskLoggerTest': 'test the SubtaskLoggerTest class to verify SubTaskLogger episode return logging behavior', 'test_episode_return_logger': 'test the episode return logger to verify rewards and discounts are aggregated correctly', 'run_FakeLogger': 'run the FakeLogger class to capture and verify logged values as JSON strings', 'test_step_through_sequence': 'test the step through sequence helper to drive observer steps with rewards and discounts', 'review_FakeLogger_is_logged': 'review the FakeLogger is_logged method to check if expected kwargs were written to the log'}
```

## File: google-deepmind_dmrobotics/py/agentflow/loggers/utils.py

Prompts

```
['create a PrintLogger instance that serializes and prints logging values as formatted strings', 'write a dictionary of key-value pairs to the PrintLogger for formatted console output', 'customize the PrintLogger serialize function to format log values with a custom formatter', 'customize the PrintLogger print function to route output to a file or custom handler', 'format float and numpy number values to three decimal places using the _format_value helper', 'create a subclass of Aggregator that implements the accumulate method to log custom subtask data', 'build an EpisodeReturnAggregator to compute episode return and length when a subtask ends', 'configure an EpisodeReturnAggregator with a custom discount factor and custom metric names', 'create a SubTaskLogger with an Acme logger and an Aggregator to log agent performance', 'review the SubTaskLogger step method to understand how it accumulates and writes logging data', 'test the SubtaskLoggerTest class to verify SubTaskLogger episode return logging behavior', 'test the episode return logger to verify rewards and discounts are aggregated correctly', 'run the FakeLogger class to capture and verify logged values as JSON strings', 'test the step through sequence helper to drive observer steps with rewards and discounts', 'review the FakeLogger is_logged method to check if expected kwargs were written to the log', 'compute the discounted return of an RL episode from a list of rewards and discounts', 'test the compute_return function with sample episode rewards and discount sequences', 'refactor compute_return to use numpy for vectorized discounted return calculation', 'review the compute_return function for edge cases with empty or mismatched input sequences', 'summarize the compute_return function which calculates discounted episode return from rewards and discounts', 'run the UtilsTest suite to validate compute_return with simple and random inputs', 'review the UtilsTest class and its parameterized test_compute_return method', 'refactor the UtilsTest class to add additional parameterized test cases for compute_return']
```

Usage

```
{'compute_return': 'compute the discounted return of an RL episode from a list of rewards and discounts', 'test_compute_return': 'test the compute_return function with sample episode rewards and discount sequences', 'refactor_compute_return': 'refactor compute_return to use numpy for vectorized discounted return calculation', 'review_compute_return': 'review the compute_return function for edge cases with empty or mismatched input sequences', 'summarize_compute_return': 'summarize the compute_return function which calculates discounted episode return from rewards and discounts'}
```

## File: google-deepmind_dmrobotics/py/agentflow/loggers/utils_test.py

Prompts

```
['create a PrintLogger instance that serializes and prints logging values as formatted strings', 'write a dictionary of key-value pairs to the PrintLogger for formatted console output', 'customize the PrintLogger serialize function to format log values with a custom formatter', 'customize the PrintLogger print function to route output to a file or custom handler', 'format float and numpy number values to three decimal places using the _format_value helper', 'create a subclass of Aggregator that implements the accumulate method to log custom subtask data', 'build an EpisodeReturnAggregator to compute episode return and length when a subtask ends', 'configure an EpisodeReturnAggregator with a custom discount factor and custom metric names', 'create a SubTaskLogger with an Acme logger and an Aggregator to log agent performance', 'review the SubTaskLogger step method to understand how it accumulates and writes logging data', 'test the SubtaskLoggerTest class to verify SubTaskLogger episode return logging behavior', 'test the episode return logger to verify rewards and discounts are aggregated correctly', 'run the FakeLogger class to capture and verify logged values as JSON strings', 'test the step through sequence helper to drive observer steps with rewards and discounts', 'review the FakeLogger is_logged method to check if expected kwargs were written to the log', 'compute the discounted return of an RL episode from a list of rewards and discounts', 'test the compute_return function with sample episode rewards and discount sequences', 'refactor compute_return to use numpy for vectorized discounted return calculation', 'review the compute_return function for edge cases with empty or mismatched input sequences', 'summarize the compute_return function which calculates discounted episode return from rewards and discounts', 'run the UtilsTest suite to validate compute_return with simple and random inputs', 'review the UtilsTest class and its parameterized test_compute_return method', 'refactor the UtilsTest class to add additional parameterized test cases for compute_return']
```

Usage

```
{'test_compute_return': 'test the compute_return utility with parameterized rewards and discount arrays', 'run_utils_test': 'run the UtilsTest suite to validate compute_return with simple and random inputs', 'review_UtilsTest': 'review the UtilsTest class and its parameterized test_compute_return method', 'summarize_compute_return': 'summarize how compute_return calculates discounted cumulative rewards from numpy arrays', 'refactor_UtilsTest': 'refactor the UtilsTest class to add additional parameterized test cases for compute_return'}
```

