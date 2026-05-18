# Agent Python Tools

- repo: facebookresearch/minihack
- repo_uri: https://github.com/facebookresearch/minihack

## File: facebookresearch_minihack/minihack/agent/polybeast/core/file_writer.py

Prompts

```
['create a FileWriter instance to log experiment data to CSV and JSON files', 'log a dictionary of key-value metrics to the FileWriter CSV log file', 'gather git commit, environment, and slurm metadata for experiment tracking', 'close the FileWriter and mark the experiment as successful in metadata', 'save experiment metadata including args and git info to a JSON file', 'create a Timings instance to profile code sections by calling time with event names', 'run the Timings summary method to print mean and std deviation for each timed event', 'test the Timings time method by recording elapsed time between consecutive calls for named events', 'review the Timings class online mean and variance computation using Welford-style incremental updates', 'refactor the Timings reset method to reinitialize the last_time timer for a new profiling session', 'compute V-trace off-policy actor critic targets from behavior and target policy logits with importance weighting', 'compute V-trace targets from log importance weights, rewards, discounts, and values using backward accumulation', 'compute the log probabilities of taken actions given policy logits using negative log-likelihood loss', 'review the VTraceFromLogitsReturns namedtuple structure containing vs, pg_advantages, log_rhos, and action log probs', 'review the VTraceReturns namedtuple structure containing computed vs values and policy gradient advantages', 'run the V-trace unit tests for action_log_probs and from_importance_weights', 'test the vtrace.action_log_probs function with policy logits and action tensors', 'test vtrace.from_importance_weights against numpy ground truth V-trace calculations', 'test vtrace.from_logits by comparing output to from_importance_weights with computed log_rhos', 'test vtrace.from_importance_weights with additional dimensions beyond sequence and batch']
```

Usage

```
{'create_FileWriter': 'create a FileWriter instance to log experiment data to CSV and JSON files', 'log_data_with_FileWriter': 'log a dictionary of key-value metrics to the FileWriter CSV log file', 'gather_experiment_metadata': 'gather git commit, environment, and slurm metadata for experiment tracking', 'close_FileWriter_successfully': 'close the FileWriter and mark the experiment as successful in metadata', 'save_experiment_metadata': 'save experiment metadata including args and git info to a JSON file'}
```

## File: facebookresearch_minihack/minihack/agent/polybeast/core/prof.py

Prompts

```
['create a FileWriter instance to log experiment data to CSV and JSON files', 'log a dictionary of key-value metrics to the FileWriter CSV log file', 'gather git commit, environment, and slurm metadata for experiment tracking', 'close the FileWriter and mark the experiment as successful in metadata', 'save experiment metadata including args and git info to a JSON file', 'create a Timings instance to profile code sections by calling time with event names', 'run the Timings summary method to print mean and std deviation for each timed event', 'test the Timings time method by recording elapsed time between consecutive calls for named events', 'review the Timings class online mean and variance computation using Welford-style incremental updates', 'refactor the Timings reset method to reinitialize the last_time timer for a new profiling session', 'compute V-trace off-policy actor critic targets from behavior and target policy logits with importance weighting', 'compute V-trace targets from log importance weights, rewards, discounts, and values using backward accumulation', 'compute the log probabilities of taken actions given policy logits using negative log-likelihood loss', 'review the VTraceFromLogitsReturns namedtuple structure containing vs, pg_advantages, log_rhos, and action log probs', 'review the VTraceReturns namedtuple structure containing computed vs values and policy gradient advantages', 'run the V-trace unit tests for action_log_probs and from_importance_weights', 'test the vtrace.action_log_probs function with policy logits and action tensors', 'test vtrace.from_importance_weights against numpy ground truth V-trace calculations', 'test vtrace.from_logits by comparing output to from_importance_weights with computed log_rhos', 'test vtrace.from_importance_weights with additional dimensions beyond sequence and batch']
```

Usage

```
{'create_timings_profiler': 'create a Timings instance to profile code sections by calling time with event names', 'run_timings_summary': 'run the Timings summary method to print mean and std deviation for each timed event', 'test_timings_time': 'test the Timings time method by recording elapsed time between consecutive calls for named events', 'review_timings_online_stats': 'review the Timings class online mean and variance computation using Welford-style incremental updates', 'refactor_timings_reset': 'refactor the Timings reset method to reinitialize the last_time timer for a new profiling session'}
```

## File: facebookresearch_minihack/minihack/agent/polybeast/core/vtrace.py

Prompts

```
['create a FileWriter instance to log experiment data to CSV and JSON files', 'log a dictionary of key-value metrics to the FileWriter CSV log file', 'gather git commit, environment, and slurm metadata for experiment tracking', 'close the FileWriter and mark the experiment as successful in metadata', 'save experiment metadata including args and git info to a JSON file', 'create a Timings instance to profile code sections by calling time with event names', 'run the Timings summary method to print mean and std deviation for each timed event', 'test the Timings time method by recording elapsed time between consecutive calls for named events', 'review the Timings class online mean and variance computation using Welford-style incremental updates', 'refactor the Timings reset method to reinitialize the last_time timer for a new profiling session', 'compute V-trace off-policy actor critic targets from behavior and target policy logits with importance weighting', 'compute V-trace targets from log importance weights, rewards, discounts, and values using backward accumulation', 'compute the log probabilities of taken actions given policy logits using negative log-likelihood loss', 'review the VTraceFromLogitsReturns namedtuple structure containing vs, pg_advantages, log_rhos, and action log probs', 'review the VTraceReturns namedtuple structure containing computed vs values and policy gradient advantages', 'run the V-trace unit tests for action_log_probs and from_importance_weights', 'test the vtrace.action_log_probs function with policy logits and action tensors', 'test vtrace.from_importance_weights against numpy ground truth V-trace calculations', 'test vtrace.from_logits by comparing output to from_importance_weights with computed log_rhos', 'test vtrace.from_importance_weights with additional dimensions beyond sequence and batch']
```

Usage

```
{'compute_vtrace_from_logits': 'compute V-trace off-policy actor critic targets from behavior and target policy logits with importance weighting', 'compute_vtrace_from_importance_weights': 'compute V-trace targets from log importance weights, rewards, discounts, and values using backward accumulation', 'compute_action_log_probs': 'compute the log probabilities of taken actions given policy logits using negative log-likelihood loss', 'review_VTraceFromLogitsReturns': 'review the VTraceFromLogitsReturns namedtuple structure containing vs, pg_advantages, log_rhos, and action log probs', 'review_VTraceReturns': 'review the VTraceReturns namedtuple structure containing computed vs values and policy gradient advantages'}
```

## File: facebookresearch_minihack/minihack/agent/polybeast/core/vtrace_test.py

Prompts

```
['create a FileWriter instance to log experiment data to CSV and JSON files', 'log a dictionary of key-value metrics to the FileWriter CSV log file', 'gather git commit, environment, and slurm metadata for experiment tracking', 'close the FileWriter and mark the experiment as successful in metadata', 'save experiment metadata including args and git info to a JSON file', 'create a Timings instance to profile code sections by calling time with event names', 'run the Timings summary method to print mean and std deviation for each timed event', 'test the Timings time method by recording elapsed time between consecutive calls for named events', 'review the Timings class online mean and variance computation using Welford-style incremental updates', 'refactor the Timings reset method to reinitialize the last_time timer for a new profiling session', 'compute V-trace off-policy actor critic targets from behavior and target policy logits with importance weighting', 'compute V-trace targets from log importance weights, rewards, discounts, and values using backward accumulation', 'compute the log probabilities of taken actions given policy logits using negative log-likelihood loss', 'review the VTraceFromLogitsReturns namedtuple structure containing vs, pg_advantages, log_rhos, and action log probs', 'review the VTraceReturns namedtuple structure containing computed vs values and policy gradient advantages', 'run the V-trace unit tests for action_log_probs and from_importance_weights', 'test the vtrace.action_log_probs function with policy logits and action tensors', 'test vtrace.from_importance_weights against numpy ground truth V-trace calculations', 'test vtrace.from_logits by comparing output to from_importance_weights with computed log_rhos', 'test vtrace.from_importance_weights with additional dimensions beyond sequence and batch']
```

Usage

```
{'run_vtrace_tests': 'run the V-trace unit tests for action_log_probs and from_importance_weights', 'test_action_log_probs': 'test the vtrace.action_log_probs function with policy logits and action tensors', 'test_from_importance_weights': 'test vtrace.from_importance_weights against numpy ground truth V-trace calculations', 'test_from_logits': 'test vtrace.from_logits by comparing output to from_importance_weights with computed log_rhos', 'test_higher_rank_inputs': 'test vtrace.from_importance_weights with additional dimensions beyond sequence and batch'}
```

