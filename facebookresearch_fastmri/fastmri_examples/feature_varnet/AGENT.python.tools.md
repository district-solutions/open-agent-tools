# Agent Python Tools

- repo: facebookresearch/fastmri
- repo_uri: https://github.com/facebookresearch/fastmri

## File: facebookresearch_fastmri/fastmri_examples/feature_varnet/feature_varnet.py

Prompts

```
['build a python module to instantiate an E2EVarNet model for MRI k-space reconstruction with configurable cascades', 'build a python module to create a FIVarNet model that combines feature-space and image-space cascades for MRI reconstruction', 'build a python module to create a SensitivityModel that estimates coil sensitivity maps from masked k-space data', 'build a python module to instantiate a U-Net model for biomedical image segmentation with configurable pool layers', 'build a python module to create a VarNetBlock that applies soft data consistency with a U-Net regularizer', 'create a FIVarNetModule instance with a FIVarNet model and configurable learning rate and weight decay', 'run a training step on a batch of masked k-space MRI data using the FIVarNet model', 'run a validation step on a batch of MRI data and return output, target, and SSIM loss', 'run a test step on a batch of MRI data and return cropped output as a numpy array', 'configure an AdamW optimizer with a linear warmup and cosine decay learning rate schedule', 'run the feature varnet training CLI to train an MRI reconstruction model on fastMRI data', 'build argparse arguments to configure feature varnet training with GPU, batch size, and model hyperparameters', 'fetch and instantiate a VarNet model variant like FIVarNet or IFVarNet with specified cascades and channels', 'run the main CLI entry point to train or test a feature varnet model on MRI data', 'reload a saved model state dict from a checkpoint file to resume training a FIVarNetModule']
```

Usage

```
{'build_E2EVarNet': 'build a python module to instantiate an E2EVarNet model for MRI k-space reconstruction with configurable cascades', 'build_FIVarNet': 'build a python module to create a FIVarNet model that combines feature-space and image-space cascades for MRI reconstruction', 'build_SensitivityModel': 'build a python module to create a SensitivityModel that estimates coil sensitivity maps from masked k-space data', 'build_Unet': 'build a python module to instantiate a U-Net model for biomedical image segmentation with configurable pool layers', 'build_VarNetBlock': 'build a python module to create a VarNetBlock that applies soft data consistency with a U-Net regularizer'}
```

## File: facebookresearch_fastmri/fastmri_examples/feature_varnet/feature_varnet_module.py

Prompts

```
['build a python module to instantiate an E2EVarNet model for MRI k-space reconstruction with configurable cascades', 'build a python module to create a FIVarNet model that combines feature-space and image-space cascades for MRI reconstruction', 'build a python module to create a SensitivityModel that estimates coil sensitivity maps from masked k-space data', 'build a python module to instantiate a U-Net model for biomedical image segmentation with configurable pool layers', 'build a python module to create a VarNetBlock that applies soft data consistency with a U-Net regularizer', 'create a FIVarNetModule instance with a FIVarNet model and configurable learning rate and weight decay', 'run a training step on a batch of masked k-space MRI data using the FIVarNet model', 'run a validation step on a batch of MRI data and return output, target, and SSIM loss', 'run a test step on a batch of MRI data and return cropped output as a numpy array', 'configure an AdamW optimizer with a linear warmup and cosine decay learning rate schedule', 'run the feature varnet training CLI to train an MRI reconstruction model on fastMRI data', 'build argparse arguments to configure feature varnet training with GPU, batch size, and model hyperparameters', 'fetch and instantiate a VarNet model variant like FIVarNet or IFVarNet with specified cascades and channels', 'run the main CLI entry point to train or test a feature varnet model on MRI data', 'reload a saved model state dict from a checkpoint file to resume training a FIVarNetModule']
```

Usage

```
{'create_FIVarNetModule': 'create a FIVarNetModule instance with a FIVarNet model and configurable learning rate and weight decay', 'run_training_step': 'run a training step on a batch of masked k-space MRI data using the FIVarNet model', 'run_validation_step': 'run a validation step on a batch of MRI data and return output, target, and SSIM loss', 'run_test_step': 'run a test step on a batch of MRI data and return cropped output as a numpy array', 'configure_optimizers': 'configure an AdamW optimizer with a linear warmup and cosine decay learning rate schedule'}
```

## File: facebookresearch_fastmri/fastmri_examples/feature_varnet/train_feature_varnet.py

Prompts

```
['build a python module to instantiate an E2EVarNet model for MRI k-space reconstruction with configurable cascades', 'build a python module to create a FIVarNet model that combines feature-space and image-space cascades for MRI reconstruction', 'build a python module to create a SensitivityModel that estimates coil sensitivity maps from masked k-space data', 'build a python module to instantiate a U-Net model for biomedical image segmentation with configurable pool layers', 'build a python module to create a VarNetBlock that applies soft data consistency with a U-Net regularizer', 'create a FIVarNetModule instance with a FIVarNet model and configurable learning rate and weight decay', 'run a training step on a batch of masked k-space MRI data using the FIVarNet model', 'run a validation step on a batch of MRI data and return output, target, and SSIM loss', 'run a test step on a batch of MRI data and return cropped output as a numpy array', 'configure an AdamW optimizer with a linear warmup and cosine decay learning rate schedule', 'run the feature varnet training CLI to train an MRI reconstruction model on fastMRI data', 'build argparse arguments to configure feature varnet training with GPU, batch size, and model hyperparameters', 'fetch and instantiate a VarNet model variant like FIVarNet or IFVarNet with specified cascades and channels', 'run the main CLI entry point to train or test a feature varnet model on MRI data', 'reload a saved model state dict from a checkpoint file to resume training a FIVarNetModule']
```

Usage

```
{'run_cli_train_feature_varnet': 'run the feature varnet training CLI to train an MRI reconstruction model on fastMRI data', 'build_args_configure_training': 'build argparse arguments to configure feature varnet training with GPU, batch size, and model hyperparameters', 'fetch_model_create_varnet': 'fetch and instantiate a VarNet model variant like FIVarNet or IFVarNet with specified cascades and channels', 'cli_main_train_or_test': 'run the main CLI entry point to train or test a feature varnet model on MRI data', 'reload_state_dict_resume_checkpoint': 'reload a saved model state dict from a checkpoint file to resume training a FIVarNetModule'}
```

