# Agent Python Tools

- repo: facebookresearch/eft
- repo_uri: https://github.com/facebookresearch/eft

## File: facebookresearch_eft/eft/cores/base_trainer.py

Prompts

```
['build a python module that subclasses BaseTrainer and implements init_fn, train_step, and train_summaries methods', 'run the BaseTrainer train method with a list of test dataset instances and dataset names', 'test the BaseTrainer by loading a pretrained checkpoint file and verifying model state dict', 'refactor the BaseTrainer train_step method to process input batches and return training outputs', 'review the BaseTrainer backupModel and reloadModel methods for exemplar tuning model state management', 'use SetDBName to set a training dataset name to a custom npz filename in DATASET_FILES', 'inspect DATASET_FILES[0] to list all test dataset names and their npz file paths', 'inspect DATASET_FILES[1] to list all train dataset names and their npz file paths', 'use DATASET_FOLDERS to map a dataset name like h36m or coco to its root folder path', 'set SMPL_MODEL_DIR or JOINT_REGRESSOR_H36M to point to SMPL model and regressor files']
```

Usage

```
{'build_BaseTrainer_subclass': 'build a python module that subclasses BaseTrainer and implements init_fn, train_step, and train_summaries methods', 'run_BaseTrainer_train': 'run the BaseTrainer train method with a list of test dataset instances and dataset names', 'test_BaseTrainer_checkpoint': 'test the BaseTrainer by loading a pretrained checkpoint file and verifying model state dict', 'refactor_BaseTrainer_train_step': 'refactor the BaseTrainer train_step method to process input batches and return training outputs', 'review_BaseTrainer_backup_reload': 'review the BaseTrainer backupModel and reloadModel methods for exemplar tuning model state management'}
```

## File: facebookresearch_eft/eft/cores/config.py

Prompts

```
['build a python module that subclasses BaseTrainer and implements init_fn, train_step, and train_summaries methods', 'run the BaseTrainer train method with a list of test dataset instances and dataset names', 'test the BaseTrainer by loading a pretrained checkpoint file and verifying model state dict', 'refactor the BaseTrainer train_step method to process input batches and return training outputs', 'review the BaseTrainer backupModel and reloadModel methods for exemplar tuning model state management', 'use SetDBName to set a training dataset name to a custom npz filename in DATASET_FILES', 'inspect DATASET_FILES[0] to list all test dataset names and their npz file paths', 'inspect DATASET_FILES[1] to list all train dataset names and their npz file paths', 'use DATASET_FOLDERS to map a dataset name like h36m or coco to its root folder path', 'set SMPL_MODEL_DIR or JOINT_REGRESSOR_H36M to point to SMPL model and regressor files']
```

Usage

```
{'set_dataset_npz_path': 'use SetDBName to set a training dataset name to a custom npz filename in DATASET_FILES', 'list_test_dataset_files': 'inspect DATASET_FILES[0] to list all test dataset names and their npz file paths', 'list_train_dataset_files': 'inspect DATASET_FILES[1] to list all train dataset names and their npz file paths', 'lookup_dataset_folder': 'use DATASET_FOLDERS to map a dataset name like h36m or coco to its root folder path', 'configure_smpl_model_paths': 'set SMPL_MODEL_DIR or JOINT_REGRESSOR_H36M to point to SMPL model and regressor files'}
```

