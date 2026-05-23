# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/det/tools/analysis_tools/mot/browse_dataset.py

Prompts

```
['run the browse dataset tool with a config file to visualize dataset samples with ground truth annotations', 'run the browse dataset tool with --output-dir to save annotated images to a directory for offline review', 'run the browse dataset tool with --cfg-options to override settings in the config file before browsing', 'run the browse dataset tool with --show-interval to control the display interval between dataset samples', 'review the parse_args function that defines CLI arguments for config path, output directory, show flag, interval, and cfg-options', 'run the MOT error visualization script to visualize false positives, false negatives, and ID switches for multiple object tracking', 'run the MOT error visualization script with --show flag to display results on the fly without saving', 'run the MOT error visualization script with --output-dir to save painted images and videos to a directory', 'compare inference results against ground truth for a MOT video and return accuracy metrics, results, and ground truth data', 'parse command line arguments for the MOT error visualization tool including config path, result directory, output directory, and FPS', 'run a parameter search across tracker config values to evaluate MOTA, HOTA, and Identity metrics', 'run MOT evaluation using a separate detector checkpoint file with the --detector flag', 'run MOT evaluation using a separate reid checkpoint file with the --reid flag', 'recursively extract all list-valued config keys from a tracker config for parameter search', 'parse CLI arguments for config path, checkpoint, work dir, launcher, and cfg options']
```

Usage

```
{'browse_dataset_with_config': 'run the browse dataset tool with a config file to visualize dataset samples with ground truth annotations', 'browse_dataset_save_output': 'run the browse dataset tool with --output-dir to save annotated images to a directory for offline review', 'browse_dataset_override_config': 'run the browse dataset tool with --cfg-options to override settings in the config file before browsing', 'browse_dataset_adjust_interval': 'run the browse dataset tool with --show-interval to control the display interval between dataset samples', 'browse_dataset_parse_args': 'review the parse_args function that defines CLI arguments for config path, output directory, show flag, interval, and cfg-options'}
```

## File: facebookresearch_sapiens/det/tools/analysis_tools/mot/mot_error_visualize.py

Prompts

```
['run the browse dataset tool with a config file to visualize dataset samples with ground truth annotations', 'run the browse dataset tool with --output-dir to save annotated images to a directory for offline review', 'run the browse dataset tool with --cfg-options to override settings in the config file before browsing', 'run the browse dataset tool with --show-interval to control the display interval between dataset samples', 'review the parse_args function that defines CLI arguments for config path, output directory, show flag, interval, and cfg-options', 'run the MOT error visualization script to visualize false positives, false negatives, and ID switches for multiple object tracking', 'run the MOT error visualization script with --show flag to display results on the fly without saving', 'run the MOT error visualization script with --output-dir to save painted images and videos to a directory', 'compare inference results against ground truth for a MOT video and return accuracy metrics, results, and ground truth data', 'parse command line arguments for the MOT error visualization tool including config path, result directory, output directory, and FPS', 'run a parameter search across tracker config values to evaluate MOTA, HOTA, and Identity metrics', 'run MOT evaluation using a separate detector checkpoint file with the --detector flag', 'run MOT evaluation using a separate reid checkpoint file with the --reid flag', 'recursively extract all list-valued config keys from a tracker config for parameter search', 'parse CLI arguments for config path, checkpoint, work dir, launcher, and cfg options']
```

Usage

```
{'run_mot_error_visualization': 'run the MOT error visualization script to visualize false positives, false negatives, and ID switches for multiple object tracking', 'run_mot_error_visualize_with_show': 'run the MOT error visualization script with --show flag to display results on the fly without saving', 'run_mot_error_visualize_with_output': 'run the MOT error visualization script with --output-dir to save painted images and videos to a directory', 'compare_res_gts_evaluate_video': 'compare inference results against ground truth for a MOT video and return accuracy metrics, results, and ground truth data', 'parse_args_mot_visualization': 'parse command line arguments for the MOT error visualization tool including config path, result directory, output directory, and FPS'}
```

## File: facebookresearch_sapiens/det/tools/analysis_tools/mot/mot_param_search.py

Prompts

```
['run the browse dataset tool with a config file to visualize dataset samples with ground truth annotations', 'run the browse dataset tool with --output-dir to save annotated images to a directory for offline review', 'run the browse dataset tool with --cfg-options to override settings in the config file before browsing', 'run the browse dataset tool with --show-interval to control the display interval between dataset samples', 'review the parse_args function that defines CLI arguments for config path, output directory, show flag, interval, and cfg-options', 'run the MOT error visualization script to visualize false positives, false negatives, and ID switches for multiple object tracking', 'run the MOT error visualization script with --show flag to display results on the fly without saving', 'run the MOT error visualization script with --output-dir to save painted images and videos to a directory', 'compare inference results against ground truth for a MOT video and return accuracy metrics, results, and ground truth data', 'parse command line arguments for the MOT error visualization tool including config path, result directory, output directory, and FPS', 'run a parameter search across tracker config values to evaluate MOTA, HOTA, and Identity metrics', 'run MOT evaluation using a separate detector checkpoint file with the --detector flag', 'run MOT evaluation using a separate reid checkpoint file with the --reid flag', 'recursively extract all list-valued config keys from a tracker config for parameter search', 'parse CLI arguments for config path, checkpoint, work dir, launcher, and cfg options']
```

Usage

```
{'run_mot_param_search': 'run a parameter search across tracker config values to evaluate MOTA, HOTA, and Identity metrics', 'run_mot_eval_with_detector': 'run MOT evaluation using a separate detector checkpoint file with the --detector flag', 'run_mot_eval_with_reid': 'run MOT evaluation using a separate reid checkpoint file with the --reid flag', 'get_search_params': 'recursively extract all list-valued config keys from a tracker config for parameter search', 'parse_args_mot_test': 'parse CLI arguments for config path, checkpoint, work dir, launcher, and cfg options'}
```

