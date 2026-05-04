# Agent Python Tools

- repo: facebookresearch/flsim
- repo_uri: https://github.com/facebookresearch/flsim

## File: facebookresearch_flsim/flsim/utils/fl/common.py

Prompts

```
['average parameters across multiple PyTorch models and save the result into a target model', 'deep copy a PyTorch model with optional dtype conversion to float32 or float64', 'clip model gradients by a maximum normalized L2 norm value', 'compare parameters across multiple models and return the name of the first mismatched parameter', 'compute a weighted linear combination of two models and save the result into a third model', 'build a subclass of FLModelWithPrivateModules that implements _get_user_private_module_names for federated learning', 'create a federated state dict from FLModelWithPrivateModules excluding user private module parameters', 'load a federated state dict into FLModelWithPrivateModules skipping user private module keys', 'get all user private parameters from FLModelWithPrivateModules as an iterable of tensors', 'clear the class-level user private module dictionary in FLModelWithPrivateModules to reset shared state', 'create a QuantilesTracker to track median and quartile values of a random variable', 'use ModelSequenceNumberTracker to track global model sequence numbers and client staleness in federated learning', 'create a RandomVariableStatsTracker to track mean, standard deviation, min, and max of a random variable', 'use RandomVariableStatsTrackerMA to track simple or exponential moving average and standard deviation with a window', 'use AverageType.from_str to parse a string into an SMA or EMA average type enum', 'create a TargetMetricTracker to track sliding window eval metrics during federated learning training', 'update the TargetMetricTracker with a new eval metric value and check if target is reached', 'use the TargetMetricDirection enum to specify min or max optimization direction for metrics', 'access the mean property of TargetMetricTracker to get the current moving average of tracked metrics', 'review the TargetMetricTracker class and its sliding window target detection logic for ML training']
```

Usage

```
{'average_models': 'average parameters across multiple PyTorch models and save the result into a target model', 'clone_model': 'deep copy a PyTorch model with optional dtype conversion to float32 or float64', 'clip_gradients': 'clip model gradients by a maximum normalized L2 norm value', 'get_mismatched_param': 'compare parameters across multiple models and return the name of the first mismatched parameter', 'linear_comb_models': 'compute a weighted linear combination of two models and save the result into a third model'}
```

## File: facebookresearch_flsim/flsim/utils/fl/personalized_model.py

Prompts

```
['average parameters across multiple PyTorch models and save the result into a target model', 'deep copy a PyTorch model with optional dtype conversion to float32 or float64', 'clip model gradients by a maximum normalized L2 norm value', 'compare parameters across multiple models and return the name of the first mismatched parameter', 'compute a weighted linear combination of two models and save the result into a third model', 'build a subclass of FLModelWithPrivateModules that implements _get_user_private_module_names for federated learning', 'create a federated state dict from FLModelWithPrivateModules excluding user private module parameters', 'load a federated state dict into FLModelWithPrivateModules skipping user private module keys', 'get all user private parameters from FLModelWithPrivateModules as an iterable of tensors', 'clear the class-level user private module dictionary in FLModelWithPrivateModules to reset shared state', 'create a QuantilesTracker to track median and quartile values of a random variable', 'use ModelSequenceNumberTracker to track global model sequence numbers and client staleness in federated learning', 'create a RandomVariableStatsTracker to track mean, standard deviation, min, and max of a random variable', 'use RandomVariableStatsTrackerMA to track simple or exponential moving average and standard deviation with a window', 'use AverageType.from_str to parse a string into an SMA or EMA average type enum', 'create a TargetMetricTracker to track sliding window eval metrics during federated learning training', 'update the TargetMetricTracker with a new eval metric value and check if target is reached', 'use the TargetMetricDirection enum to specify min or max optimization direction for metrics', 'access the mean property of TargetMetricTracker to get the current moving average of tracked metrics', 'review the TargetMetricTracker class and its sliding window target detection logic for ML training']
```

Usage

```
{'build_FLModelWithPrivateModules_subclass': 'build a subclass of FLModelWithPrivateModules that implements _get_user_private_module_names for federated learning', 'create_federated_state_dict': 'create a federated state dict from FLModelWithPrivateModules excluding user private module parameters', 'load_federated_state_dict': 'load a federated state dict into FLModelWithPrivateModules skipping user private module keys', 'get_user_private_parameters': 'get all user private parameters from FLModelWithPrivateModules as an iterable of tensors', 'clear_user_private_module_dict': 'clear the class-level user private module dictionary in FLModelWithPrivateModules to reset shared state'}
```

## File: facebookresearch_flsim/flsim/utils/fl/stats.py

Prompts

```
['average parameters across multiple PyTorch models and save the result into a target model', 'deep copy a PyTorch model with optional dtype conversion to float32 or float64', 'clip model gradients by a maximum normalized L2 norm value', 'compare parameters across multiple models and return the name of the first mismatched parameter', 'compute a weighted linear combination of two models and save the result into a third model', 'build a subclass of FLModelWithPrivateModules that implements _get_user_private_module_names for federated learning', 'create a federated state dict from FLModelWithPrivateModules excluding user private module parameters', 'load a federated state dict into FLModelWithPrivateModules skipping user private module keys', 'get all user private parameters from FLModelWithPrivateModules as an iterable of tensors', 'clear the class-level user private module dictionary in FLModelWithPrivateModules to reset shared state', 'create a QuantilesTracker to track median and quartile values of a random variable', 'use ModelSequenceNumberTracker to track global model sequence numbers and client staleness in federated learning', 'create a RandomVariableStatsTracker to track mean, standard deviation, min, and max of a random variable', 'use RandomVariableStatsTrackerMA to track simple or exponential moving average and standard deviation with a window', 'use AverageType.from_str to parse a string into an SMA or EMA average type enum', 'create a TargetMetricTracker to track sliding window eval metrics during federated learning training', 'update the TargetMetricTracker with a new eval metric value and check if target is reached', 'use the TargetMetricDirection enum to specify min or max optimization direction for metrics', 'access the mean property of TargetMetricTracker to get the current moving average of tracked metrics', 'review the TargetMetricTracker class and its sliding window target detection logic for ML training']
```

Usage

```
{'create_quantiles_tracker': 'create a QuantilesTracker to track median and quartile values of a random variable', 'track_model_sequence_numbers': 'use ModelSequenceNumberTracker to track global model sequence numbers and client staleness in federated learning', 'track_random_variable_stats': 'create a RandomVariableStatsTracker to track mean, standard deviation, min, and max of a random variable', 'track_moving_average_stats': 'use RandomVariableStatsTrackerMA to track simple or exponential moving average and standard deviation with a window', 'parse_average_type': 'use AverageType.from_str to parse a string into an SMA or EMA average type enum'}
```

## File: facebookresearch_flsim/flsim/utils/fl/target_metric.py

Prompts

```
['average parameters across multiple PyTorch models and save the result into a target model', 'deep copy a PyTorch model with optional dtype conversion to float32 or float64', 'clip model gradients by a maximum normalized L2 norm value', 'compare parameters across multiple models and return the name of the first mismatched parameter', 'compute a weighted linear combination of two models and save the result into a third model', 'build a subclass of FLModelWithPrivateModules that implements _get_user_private_module_names for federated learning', 'create a federated state dict from FLModelWithPrivateModules excluding user private module parameters', 'load a federated state dict into FLModelWithPrivateModules skipping user private module keys', 'get all user private parameters from FLModelWithPrivateModules as an iterable of tensors', 'clear the class-level user private module dictionary in FLModelWithPrivateModules to reset shared state', 'create a QuantilesTracker to track median and quartile values of a random variable', 'use ModelSequenceNumberTracker to track global model sequence numbers and client staleness in federated learning', 'create a RandomVariableStatsTracker to track mean, standard deviation, min, and max of a random variable', 'use RandomVariableStatsTrackerMA to track simple or exponential moving average and standard deviation with a window', 'use AverageType.from_str to parse a string into an SMA or EMA average type enum', 'create a TargetMetricTracker to track sliding window eval metrics during federated learning training', 'update the TargetMetricTracker with a new eval metric value and check if target is reached', 'use the TargetMetricDirection enum to specify min or max optimization direction for metrics', 'access the mean property of TargetMetricTracker to get the current moving average of tracked metrics', 'review the TargetMetricTracker class and its sliding window target detection logic for ML training']
```

Usage

```
{'create_TargetMetricTracker': 'create a TargetMetricTracker to track sliding window eval metrics during federated learning training', 'update_and_check_target_method': 'update the TargetMetricTracker with a new eval metric value and check if target is reached', 'use_TargetMetricDirection_enum': 'use the TargetMetricDirection enum to specify min or max optimization direction for metrics', 'access_mean_property': 'access the mean property of TargetMetricTracker to get the current moving average of tracked metrics', 'review_TargetMetricTracker_class': 'review the TargetMetricTracker class and its sliding window target detection logic for ML training'}
```

