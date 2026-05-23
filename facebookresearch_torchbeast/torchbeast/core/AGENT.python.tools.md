# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/torchbeast/core/environment.py

Prompts

```
['create an Environment instance wrapping a gym environment for reinforcement learning', 'run the initial method to reset the gym environment and get the first observation', 'step the Environment with a torch action tensor to advance the gym environment', 'review the Environment close method to properly shut down the underlying gym environment', 'summarize the _format_frame function that converts numpy frames to PyTorch tensors with T,B dimensions', 'create a FileWriter instance to log experiment data to CSV files under a custom root directory', 'log a dictionary of key-value metrics to the FileWriter CSV log file with auto incrementing ticks', 'close the FileWriter and save final metadata including end date and success status to meta.json', 'gather git commit info, slurm environment variables, and process environment into a metadata dictionary', 'save the experiment metadata dictionary to a JSON file using the FileWriter internal _save_metadata method', 'create a Timings instance to profile code sections with online mean and variance tracking', 'call the time method on a Timings object to record elapsed time for a named event', 'call the means method on a Timings object to retrieve a dictionary of mean timings per event', 'call the stds method on a Timings object to retrieve standard deviations for each timed event', 'call the summary method on a Timings object to get a formatted string of all timings with percentages', 'compute V-trace off-policy actor-critic targets from behavior and target policy logits with importance weighting', 'compute V-trace returns from log importance weights, rewards, discounts, and values using backward accumulation', 'compute the log probabilities of taken actions given policy logits using negative log-likelihood loss', 'review the VTraceFromLogitsReturns namedtuple structure containing vs, pg_advantages, log_rhos, and action log probs fields', 'review the VTraceReturns namedtuple structure containing vs and pg_advantages fields for V-trace targets']
```

Usage

```
{'create_environment_instance': 'create an Environment instance wrapping a gym environment for reinforcement learning', 'run_environment_initial': 'run the initial method to reset the gym environment and get the first observation', 'step_environment_action': 'step the Environment with a torch action tensor to advance the gym environment', 'review_environment_close': 'review the Environment close method to properly shut down the underlying gym environment', 'summarize_format_frame': 'summarize the _format_frame function that converts numpy frames to PyTorch tensors with T,B dimensions'}
```

## File: facebookresearch_torchbeast/torchbeast/core/file_writer.py

Prompts

```
['create an Environment instance wrapping a gym environment for reinforcement learning', 'run the initial method to reset the gym environment and get the first observation', 'step the Environment with a torch action tensor to advance the gym environment', 'review the Environment close method to properly shut down the underlying gym environment', 'summarize the _format_frame function that converts numpy frames to PyTorch tensors with T,B dimensions', 'create a FileWriter instance to log experiment data to CSV files under a custom root directory', 'log a dictionary of key-value metrics to the FileWriter CSV log file with auto incrementing ticks', 'close the FileWriter and save final metadata including end date and success status to meta.json', 'gather git commit info, slurm environment variables, and process environment into a metadata dictionary', 'save the experiment metadata dictionary to a JSON file using the FileWriter internal _save_metadata method', 'create a Timings instance to profile code sections with online mean and variance tracking', 'call the time method on a Timings object to record elapsed time for a named event', 'call the means method on a Timings object to retrieve a dictionary of mean timings per event', 'call the stds method on a Timings object to retrieve standard deviations for each timed event', 'call the summary method on a Timings object to get a formatted string of all timings with percentages', 'compute V-trace off-policy actor-critic targets from behavior and target policy logits with importance weighting', 'compute V-trace returns from log importance weights, rewards, discounts, and values using backward accumulation', 'compute the log probabilities of taken actions given policy logits using negative log-likelihood loss', 'review the VTraceFromLogitsReturns namedtuple structure containing vs, pg_advantages, log_rhos, and action log probs fields', 'review the VTraceReturns namedtuple structure containing vs and pg_advantages fields for V-trace targets']
```

Usage

```
{'create_FileWriter': 'create a FileWriter instance to log experiment data to CSV files under a custom root directory', 'log_with_FileWriter': 'log a dictionary of key-value metrics to the FileWriter CSV log file with auto incrementing ticks', 'close_FileWriter': 'close the FileWriter and save final metadata including end date and success status to meta.json', 'gather_metadata': 'gather git commit info, slurm environment variables, and process environment into a metadata dictionary', 'save_metadata_FileWriter': 'save the experiment metadata dictionary to a JSON file using the FileWriter internal _save_metadata method'}
```

## File: facebookresearch_torchbeast/torchbeast/core/prof.py

Prompts

```
['create an Environment instance wrapping a gym environment for reinforcement learning', 'run the initial method to reset the gym environment and get the first observation', 'step the Environment with a torch action tensor to advance the gym environment', 'review the Environment close method to properly shut down the underlying gym environment', 'summarize the _format_frame function that converts numpy frames to PyTorch tensors with T,B dimensions', 'create a FileWriter instance to log experiment data to CSV files under a custom root directory', 'log a dictionary of key-value metrics to the FileWriter CSV log file with auto incrementing ticks', 'close the FileWriter and save final metadata including end date and success status to meta.json', 'gather git commit info, slurm environment variables, and process environment into a metadata dictionary', 'save the experiment metadata dictionary to a JSON file using the FileWriter internal _save_metadata method', 'create a Timings instance to profile code sections with online mean and variance tracking', 'call the time method on a Timings object to record elapsed time for a named event', 'call the means method on a Timings object to retrieve a dictionary of mean timings per event', 'call the stds method on a Timings object to retrieve standard deviations for each timed event', 'call the summary method on a Timings object to get a formatted string of all timings with percentages', 'compute V-trace off-policy actor-critic targets from behavior and target policy logits with importance weighting', 'compute V-trace returns from log importance weights, rewards, discounts, and values using backward accumulation', 'compute the log probabilities of taken actions given policy logits using negative log-likelihood loss', 'review the VTraceFromLogitsReturns namedtuple structure containing vs, pg_advantages, log_rhos, and action log probs fields', 'review the VTraceReturns namedtuple structure containing vs and pg_advantages fields for V-trace targets']
```

Usage

```
{'create_timings_profiler': 'create a Timings instance to profile code sections with online mean and variance tracking', 'time_named_event': 'call the time method on a Timings object to record elapsed time for a named event', 'get_profiling_means': 'call the means method on a Timings object to retrieve a dictionary of mean timings per event', 'get_profiling_stds': 'call the stds method on a Timings object to retrieve standard deviations for each timed event', 'print_profiling_summary': 'call the summary method on a Timings object to get a formatted string of all timings with percentages'}
```

## File: facebookresearch_torchbeast/torchbeast/core/vtrace.py

Prompts

```
['create an Environment instance wrapping a gym environment for reinforcement learning', 'run the initial method to reset the gym environment and get the first observation', 'step the Environment with a torch action tensor to advance the gym environment', 'review the Environment close method to properly shut down the underlying gym environment', 'summarize the _format_frame function that converts numpy frames to PyTorch tensors with T,B dimensions', 'create a FileWriter instance to log experiment data to CSV files under a custom root directory', 'log a dictionary of key-value metrics to the FileWriter CSV log file with auto incrementing ticks', 'close the FileWriter and save final metadata including end date and success status to meta.json', 'gather git commit info, slurm environment variables, and process environment into a metadata dictionary', 'save the experiment metadata dictionary to a JSON file using the FileWriter internal _save_metadata method', 'create a Timings instance to profile code sections with online mean and variance tracking', 'call the time method on a Timings object to record elapsed time for a named event', 'call the means method on a Timings object to retrieve a dictionary of mean timings per event', 'call the stds method on a Timings object to retrieve standard deviations for each timed event', 'call the summary method on a Timings object to get a formatted string of all timings with percentages', 'compute V-trace off-policy actor-critic targets from behavior and target policy logits with importance weighting', 'compute V-trace returns from log importance weights, rewards, discounts, and values using backward accumulation', 'compute the log probabilities of taken actions given policy logits using negative log-likelihood loss', 'review the VTraceFromLogitsReturns namedtuple structure containing vs, pg_advantages, log_rhos, and action log probs fields', 'review the VTraceReturns namedtuple structure containing vs and pg_advantages fields for V-trace targets']
```

Usage

```
{'compute_vtrace_from_logits': 'compute V-trace off-policy actor-critic targets from behavior and target policy logits with importance weighting', 'compute_vtrace_from_importance_weights': 'compute V-trace returns from log importance weights, rewards, discounts, and values using backward accumulation', 'compute_action_log_probs': 'compute the log probabilities of taken actions given policy logits using negative log-likelihood loss', 'review_VTraceFromLogitsReturns_namedtuple': 'review the VTraceFromLogitsReturns namedtuple structure containing vs, pg_advantages, log_rhos, and action log probs fields', 'review_VTraceReturns_namedtuple': 'review the VTraceReturns namedtuple structure containing vs and pg_advantages fields for V-trace targets'}
```

