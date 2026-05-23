# Agent Python Tools

- repo: facebookresearch/omnimatterf
- repo_uri: https://github.com/facebookresearch/omnimatterf

## File: facebookresearch_omnimatterf/ui/commands.py

Prompts

```
['run the matting training pipeline on a dataset with specified pose, mask, and scale options', 'add a new dataset by extracting images from a video and running flow, segmentation, and homography preprocessing', 'run the omnimatte training pipeline on a dataset with automatic scale detection and optional evaluation', 'run COLMAP structure from motion to compute camera poses for a dataset using images and masks', 'run evaluation on trained matting checkpoints and save metrics to the experiment output folder', 'create a DataManager instance from the data_manager.json config file using create_data_manager()', 'review the create_data_manager function to understand how it validates the config file path', 'refactor create_data_manager to accept an optional custom config file path argument', 'test that create_data_manager raises ValueError when data_manager.json config file is missing', 'summarize the dm_config_file module-level variable and its derived path from the ui package', 'create a DataManager instance from a config JSON file to load local datasets and experiments', 'get the local filesystem path for a dataset given its key string', 'get the local output path for an experiment by dataset key, method, and name', 'sort a list of checkpoint filenames numerically by their checkpoint index', 'populate a DataAvailability object by scanning folder children for images, flow, depth, and poses']
```

Usage

```
{'run_train_ours': 'run the matting training pipeline on a dataset with specified pose, mask, and scale options', 'run_add_data': 'add a new dataset by extracting images from a video and running flow, segmentation, and homography preprocessing', 'run_train_omnimatte': 'run the omnimatte training pipeline on a dataset with automatic scale detection and optional evaluation', 'run_run_colmap': 'run COLMAP structure from motion to compute camera poses for a dataset using images and masks', 'run_eval_ours': 'run evaluation on trained matting checkpoints and save metrics to the experiment output folder'}
```

## File: facebookresearch_omnimatterf/ui/common.py

Prompts

```
['run the matting training pipeline on a dataset with specified pose, mask, and scale options', 'add a new dataset by extracting images from a video and running flow, segmentation, and homography preprocessing', 'run the omnimatte training pipeline on a dataset with automatic scale detection and optional evaluation', 'run COLMAP structure from motion to compute camera poses for a dataset using images and masks', 'run evaluation on trained matting checkpoints and save metrics to the experiment output folder', 'create a DataManager instance from the data_manager.json config file using create_data_manager()', 'review the create_data_manager function to understand how it validates the config file path', 'refactor create_data_manager to accept an optional custom config file path argument', 'test that create_data_manager raises ValueError when data_manager.json config file is missing', 'summarize the dm_config_file module-level variable and its derived path from the ui package', 'create a DataManager instance from a config JSON file to load local datasets and experiments', 'get the local filesystem path for a dataset given its key string', 'get the local output path for an experiment by dataset key, method, and name', 'sort a list of checkpoint filenames numerically by their checkpoint index', 'populate a DataAvailability object by scanning folder children for images, flow, depth, and poses']
```

Usage

```
{'create_data_manager': 'create a DataManager instance from the data_manager.json config file using create_data_manager()', 'review_create_data_manager': 'review the create_data_manager function to understand how it validates the config file path', 'refactor_create_data_manager': 'refactor create_data_manager to accept an optional custom config file path argument', 'test_create_data_manager': 'test that create_data_manager raises ValueError when data_manager.json config file is missing', 'summarize_dm_config_file': 'summarize the dm_config_file module-level variable and its derived path from the ui package'}
```

## File: facebookresearch_omnimatterf/ui/data_manager.py

Prompts

```
['run the matting training pipeline on a dataset with specified pose, mask, and scale options', 'add a new dataset by extracting images from a video and running flow, segmentation, and homography preprocessing', 'run the omnimatte training pipeline on a dataset with automatic scale detection and optional evaluation', 'run COLMAP structure from motion to compute camera poses for a dataset using images and masks', 'run evaluation on trained matting checkpoints and save metrics to the experiment output folder', 'create a DataManager instance from the data_manager.json config file using create_data_manager()', 'review the create_data_manager function to understand how it validates the config file path', 'refactor create_data_manager to accept an optional custom config file path argument', 'test that create_data_manager raises ValueError when data_manager.json config file is missing', 'summarize the dm_config_file module-level variable and its derived path from the ui package', 'create a DataManager instance from a config JSON file to load local datasets and experiments', 'get the local filesystem path for a dataset given its key string', 'get the local output path for an experiment by dataset key, method, and name', 'sort a list of checkpoint filenames numerically by their checkpoint index', 'populate a DataAvailability object by scanning folder children for images, flow, depth, and poses']
```

Usage

```
{'init_DataManager': 'create a DataManager instance from a config JSON file to load local datasets and experiments', 'get_local_data_path': 'get the local filesystem path for a dataset given its key string', 'get_local_experiment_path': 'get the local output path for an experiment by dataset key, method, and name', 'sorted_checkpoints': 'sort a list of checkpoint filenames numerically by their checkpoint index', 'set_data_availability': 'populate a DataAvailability object by scanning folder children for images, flow, depth, and poses'}
```

