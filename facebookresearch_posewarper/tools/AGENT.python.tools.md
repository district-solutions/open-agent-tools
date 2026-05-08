# Agent Python Tools

- repo: facebookresearch/posewarper
- repo_uri: https://github.com/facebookresearch/posewarper

## File: facebookresearch_posewarper/tools/_init_paths.py

Prompts

```
['summarize the add_path function that inserts a directory into sys.path if not already present', 'review the add_path function to check if it safely avoids duplicate entries in sys.path', 'test the add_path function to verify it inserts a given path at the front of sys.path', 'refactor the add_path function to accept a list of paths instead of a single path', 'build a python module that adds the lib and py-motmetrics directories to sys.path on import', 'run the pose estimation model validation on a test dataset using a config file', 'parse command-line arguments including --cfg config file and optional --modelDir --logDir --dataDir --prevModelDir', 'copy previous model checkpoints from a Philly VC source directory to a destination directory', 'load a pose net model from a config-specified checkpoint file and wrap with DataParallel', 'create a validation DataLoader with image normalization transforms for the pose estimation dataset', 'run the keypoints network training loop with a config file via the --cfg argument', 'run the argument parser to parse training config file and philly directory options', 'run the copy_prev_models function to copy previous model checkpoints from source to destination directory', 'run the main training loop that trains a pose estimation model across multiple epochs with validation', 'run training with auto-resume from an existing checkpoint file to continue from a previous epoch']
```

Usage

```
{'summarize_add_path': 'summarize the add_path function that inserts a directory into sys.path if not already present', 'review_add_path': 'review the add_path function to check if it safely avoids duplicate entries in sys.path', 'test_add_path': 'test the add_path function to verify it inserts a given path at the front of sys.path', 'refactor_add_path': 'refactor the add_path function to accept a list of paths instead of a single path', 'build_init_paths_module': 'build a python module that adds the lib and py-motmetrics directories to sys.path on import'}
```

## File: facebookresearch_posewarper/tools/test.py

Prompts

```
['summarize the add_path function that inserts a directory into sys.path if not already present', 'review the add_path function to check if it safely avoids duplicate entries in sys.path', 'test the add_path function to verify it inserts a given path at the front of sys.path', 'refactor the add_path function to accept a list of paths instead of a single path', 'build a python module that adds the lib and py-motmetrics directories to sys.path on import', 'run the pose estimation model validation on a test dataset using a config file', 'parse command-line arguments including --cfg config file and optional --modelDir --logDir --dataDir --prevModelDir', 'copy previous model checkpoints from a Philly VC source directory to a destination directory', 'load a pose net model from a config-specified checkpoint file and wrap with DataParallel', 'create a validation DataLoader with image normalization transforms for the pose estimation dataset', 'run the keypoints network training loop with a config file via the --cfg argument', 'run the argument parser to parse training config file and philly directory options', 'run the copy_prev_models function to copy previous model checkpoints from source to destination directory', 'run the main training loop that trains a pose estimation model across multiple epochs with validation', 'run training with auto-resume from an existing checkpoint file to continue from a previous epoch']
```

Usage

```
{'run_pose_model_validation': 'run the pose estimation model validation on a test dataset using a config file', 'parse_args_cli': 'parse command-line arguments including --cfg config file and optional --modelDir --logDir --dataDir --prevModelDir', 'copy_prev_models': 'copy previous model checkpoints from a Philly VC source directory to a destination directory', 'load_pose_net_model': 'load a pose net model from a config-specified checkpoint file and wrap with DataParallel', 'create_validation_loader': 'create a validation DataLoader with image normalization transforms for the pose estimation dataset'}
```

## File: facebookresearch_posewarper/tools/train.py

Prompts

```
['summarize the add_path function that inserts a directory into sys.path if not already present', 'review the add_path function to check if it safely avoids duplicate entries in sys.path', 'test the add_path function to verify it inserts a given path at the front of sys.path', 'refactor the add_path function to accept a list of paths instead of a single path', 'build a python module that adds the lib and py-motmetrics directories to sys.path on import', 'run the pose estimation model validation on a test dataset using a config file', 'parse command-line arguments including --cfg config file and optional --modelDir --logDir --dataDir --prevModelDir', 'copy previous model checkpoints from a Philly VC source directory to a destination directory', 'load a pose net model from a config-specified checkpoint file and wrap with DataParallel', 'create a validation DataLoader with image normalization transforms for the pose estimation dataset', 'run the keypoints network training loop with a config file via the --cfg argument', 'run the argument parser to parse training config file and philly directory options', 'run the copy_prev_models function to copy previous model checkpoints from source to destination directory', 'run the main training loop that trains a pose estimation model across multiple epochs with validation', 'run training with auto-resume from an existing checkpoint file to continue from a previous epoch']
```

Usage

```
{'run_train_keypoints_network': 'run the keypoints network training loop with a config file via the --cfg argument', 'run_parse_args': 'run the argument parser to parse training config file and philly directory options', 'run_copy_prev_models': 'run the copy_prev_models function to copy previous model checkpoints from source to destination directory', 'run_main_training_loop': 'run the main training loop that trains a pose estimation model across multiple epochs with validation', 'run_resume_training': 'run training with auto-resume from an existing checkpoint file to continue from a previous epoch'}
```

