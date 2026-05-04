# Agent Python Tools

- repo: facebookresearch/eft
- repo_uri: https://github.com/facebookresearch/eft

## File: facebookresearch_eft/bodymocap/core/base_trainer.py

Prompts

```
['create a BaseTrainer instance with options to initialize models, optimizers, and checkpointing', 'run the training loop over epochs with periodic testing on 3DPW and H36M datasets', 'load a pretrained checkpoint file into the models dictionary with non-strict matching', 'backup the current model and optimizer state then reload to restore previous training state', 'evaluate the model on a test dataset and log error metrics to TensorBoard', 'review the DATASET_FILES list of dicts mapping dataset names to npz file paths for test and train splits', 'review the DATASET_FOLDERS dict mapping dataset names to their root folder paths', 'review the module-level dataset root path constants like H36M_ROOT, COCO_ROOT, MPII_ROOT, and PW3D_ROOT', 'review the SMPL model and regressor file path constants like SMPL_MODEL_DIR, JOINT_REGRESSOR_H36M, and SMPL_MEAN_PARAMS', 'test the SetDBName function to add or update a dataset entry in the training DATASET_FILES dict']
```

Usage

```
{'init_BaseTrainer': 'create a BaseTrainer instance with options to initialize models, optimizers, and checkpointing', 'train_BaseTrainer': 'run the training loop over epochs with periodic testing on 3DPW and H36M datasets', 'load_pretrained_BaseTrainer': 'load a pretrained checkpoint file into the models dictionary with non-strict matching', 'backup_and_reload_model': 'backup the current model and optimizer state then reload to restore previous training state', 'test_BaseTrainer': 'evaluate the model on a test dataset and log error metrics to TensorBoard'}
```

## File: facebookresearch_eft/bodymocap/core/config.py

Prompts

```
['create a BaseTrainer instance with options to initialize models, optimizers, and checkpointing', 'run the training loop over epochs with periodic testing on 3DPW and H36M datasets', 'load a pretrained checkpoint file into the models dictionary with non-strict matching', 'backup the current model and optimizer state then reload to restore previous training state', 'evaluate the model on a test dataset and log error metrics to TensorBoard', 'review the DATASET_FILES list of dicts mapping dataset names to npz file paths for test and train splits', 'review the DATASET_FOLDERS dict mapping dataset names to their root folder paths', 'review the module-level dataset root path constants like H36M_ROOT, COCO_ROOT, MPII_ROOT, and PW3D_ROOT', 'review the SMPL model and regressor file path constants like SMPL_MODEL_DIR, JOINT_REGRESSOR_H36M, and SMPL_MEAN_PARAMS', 'test the SetDBName function to add or update a dataset entry in the training DATASET_FILES dict']
```

Usage

```
{'review_DATASET_FILES': 'review the DATASET_FILES list of dicts mapping dataset names to npz file paths for test and train splits', 'review_DATASET_FOLDERS': 'review the DATASET_FOLDERS dict mapping dataset names to their root folder paths', 'review_dataset_root_constants': 'review the module-level dataset root path constants like H36M_ROOT, COCO_ROOT, MPII_ROOT, and PW3D_ROOT', 'review_model_file_constants': 'review the SMPL model and regressor file path constants like SMPL_MODEL_DIR, JOINT_REGRESSOR_H36M, and SMPL_MEAN_PARAMS', 'test_SetDBName': 'test the SetDBName function to add or update a dataset entry in the training DATASET_FILES dict'}
```

