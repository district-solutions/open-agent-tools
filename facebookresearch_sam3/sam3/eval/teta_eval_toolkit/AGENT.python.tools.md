# Agent Python Tools

- repo: facebookresearch/sam3
- repo_uri: https://github.com/facebookresearch/sam3

## File: facebookresearch_sam3/sam3/eval/teta_eval_toolkit/_timing.py

Prompts

```
['summarize the python decorator function time that wraps functions with performance timing using perf_counter', 'run the time decorator on a function to measure and print its execution time in seconds', 'build a timing summary by setting DO_TIMING to true and calling timed methods to accumulate elapsed time in timer_dict', 'refactor the time decorator to customize progress printing behavior with DISPLAY_LESS_PROGRESS flag', 'test the time decorator accumulative timing by calling Evaluator.evaluate to print final timing analysis', 'run the teta evaluation toolkit by parsing command line arguments into eval, dataset, and metrics configs', 'create a dict of default evaluation config values including parallelism, error handling, and output settings', 'create a dict of default dataset config values including ground truth folder, trackers folder, and split settings', 'test the init_config function to fill missing keys in a partial config with default values', 'refactor the update_config function to update a config dict from command line argparse arguments', 'build an Evaluator instance to evaluate metrics on tracking datasets', 'run the Evaluator.evaluate method to evaluate metrics across multiple datasets and trackers', 'run the Evaluator.evaluate_tracker method to evaluate a single tracker across all sequences', 'run the eval_sequence function to evaluate a single sequence against a tracker and metrics', 'run the class and super-category combination logic in evaluate_tracker to aggregate results', 'validate a list of metric objects ensuring all metric names and fields are unique', 'get the track ID string key from an annotation dict supporting track_id, instance_id, or scalabel_id', 'create a custom exception class for catching expected errors in track evaluation code']
```

Usage

```
{'summarize_time': 'summarize the python decorator function time that wraps functions with performance timing using perf_counter', 'run_time_decorator': 'run the time decorator on a function to measure and print its execution time in seconds', 'build_timing_summary': 'build a timing summary by setting DO_TIMING to true and calling timed methods to accumulate elapsed time in timer_dict', 'refactor_time_printing': 'refactor the time decorator to customize progress printing behavior with DISPLAY_LESS_PROGRESS flag', 'test_time_accumulation': 'test the time decorator accumulative timing by calling Evaluator.evaluate to print final timing analysis'}
```

## File: facebookresearch_sam3/sam3/eval/teta_eval_toolkit/config.py

Prompts

```
['summarize the python decorator function time that wraps functions with performance timing using perf_counter', 'run the time decorator on a function to measure and print its execution time in seconds', 'build a timing summary by setting DO_TIMING to true and calling timed methods to accumulate elapsed time in timer_dict', 'refactor the time decorator to customize progress printing behavior with DISPLAY_LESS_PROGRESS flag', 'test the time decorator accumulative timing by calling Evaluator.evaluate to print final timing analysis', 'run the teta evaluation toolkit by parsing command line arguments into eval, dataset, and metrics configs', 'create a dict of default evaluation config values including parallelism, error handling, and output settings', 'create a dict of default dataset config values including ground truth folder, trackers folder, and split settings', 'test the init_config function to fill missing keys in a partial config with default values', 'refactor the update_config function to update a config dict from command line argparse arguments', 'build an Evaluator instance to evaluate metrics on tracking datasets', 'run the Evaluator.evaluate method to evaluate metrics across multiple datasets and trackers', 'run the Evaluator.evaluate_tracker method to evaluate a single tracker across all sequences', 'run the eval_sequence function to evaluate a single sequence against a tracker and metrics', 'run the class and super-category combination logic in evaluate_tracker to aggregate results', 'validate a list of metric objects ensuring all metric names and fields are unique', 'get the track ID string key from an annotation dict supporting track_id, instance_id, or scalabel_id', 'create a custom exception class for catching expected errors in track evaluation code']
```

Usage

```
{'run_teta_eval_parse_configs': 'run the teta evaluation toolkit by parsing command line arguments into eval, dataset, and metrics configs', 'create_get_default_eval_config': 'create a dict of default evaluation config values including parallelism, error handling, and output settings', 'create_get_default_dataset_config': 'create a dict of default dataset config values including ground truth folder, trackers folder, and split settings', 'test_init_config': 'test the init_config function to fill missing keys in a partial config with default values', 'refactor_update_config': 'refactor the update_config function to update a config dict from command line argparse arguments'}
```

## File: facebookresearch_sam3/sam3/eval/teta_eval_toolkit/eval.py

Prompts

```
['summarize the python decorator function time that wraps functions with performance timing using perf_counter', 'run the time decorator on a function to measure and print its execution time in seconds', 'build a timing summary by setting DO_TIMING to true and calling timed methods to accumulate elapsed time in timer_dict', 'refactor the time decorator to customize progress printing behavior with DISPLAY_LESS_PROGRESS flag', 'test the time decorator accumulative timing by calling Evaluator.evaluate to print final timing analysis', 'run the teta evaluation toolkit by parsing command line arguments into eval, dataset, and metrics configs', 'create a dict of default evaluation config values including parallelism, error handling, and output settings', 'create a dict of default dataset config values including ground truth folder, trackers folder, and split settings', 'test the init_config function to fill missing keys in a partial config with default values', 'refactor the update_config function to update a config dict from command line argparse arguments', 'build an Evaluator instance to evaluate metrics on tracking datasets', 'run the Evaluator.evaluate method to evaluate metrics across multiple datasets and trackers', 'run the Evaluator.evaluate_tracker method to evaluate a single tracker across all sequences', 'run the eval_sequence function to evaluate a single sequence against a tracker and metrics', 'run the class and super-category combination logic in evaluate_tracker to aggregate results', 'validate a list of metric objects ensuring all metric names and fields are unique', 'get the track ID string key from an annotation dict supporting track_id, instance_id, or scalabel_id', 'create a custom exception class for catching expected errors in track evaluation code']
```

Usage

```
{'build_evaluator_instance': 'build an Evaluator instance to evaluate metrics on tracking datasets', 'run_evaluate_datasets': 'run the Evaluator.evaluate method to evaluate metrics across multiple datasets and trackers', 'run_evaluate_tracker': 'run the Evaluator.evaluate_tracker method to evaluate a single tracker across all sequences', 'run_eval_sequence': 'run the eval_sequence function to evaluate a single sequence against a tracker and metrics', 'run_combine_classes': 'run the class and super-category combination logic in evaluate_tracker to aggregate results'}
```

## File: facebookresearch_sam3/sam3/eval/teta_eval_toolkit/utils.py

Prompts

```
['summarize the python decorator function time that wraps functions with performance timing using perf_counter', 'run the time decorator on a function to measure and print its execution time in seconds', 'build a timing summary by setting DO_TIMING to true and calling timed methods to accumulate elapsed time in timer_dict', 'refactor the time decorator to customize progress printing behavior with DISPLAY_LESS_PROGRESS flag', 'test the time decorator accumulative timing by calling Evaluator.evaluate to print final timing analysis', 'run the teta evaluation toolkit by parsing command line arguments into eval, dataset, and metrics configs', 'create a dict of default evaluation config values including parallelism, error handling, and output settings', 'create a dict of default dataset config values including ground truth folder, trackers folder, and split settings', 'test the init_config function to fill missing keys in a partial config with default values', 'refactor the update_config function to update a config dict from command line argparse arguments', 'build an Evaluator instance to evaluate metrics on tracking datasets', 'run the Evaluator.evaluate method to evaluate metrics across multiple datasets and trackers', 'run the Evaluator.evaluate_tracker method to evaluate a single tracker across all sequences', 'run the eval_sequence function to evaluate a single sequence against a tracker and metrics', 'run the class and super-category combination logic in evaluate_tracker to aggregate results', 'validate a list of metric objects ensuring all metric names and fields are unique', 'get the track ID string key from an annotation dict supporting track_id, instance_id, or scalabel_id', 'create a custom exception class for catching expected errors in track evaluation code']
```

Usage

```
{'validate_metrics_list': 'validate a list of metric objects ensuring all metric names and fields are unique', 'get_track_id_str': 'get the track ID string key from an annotation dict supporting track_id, instance_id, or scalabel_id', 'TrackEvalException': 'create a custom exception class for catching expected errors in track evaluation code'}
```

