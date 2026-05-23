# Agent Python Tools

- repo: facebookresearch/fastmri
- repo_uri: https://github.com/facebookresearch/fastmri

## File: facebookresearch_fastmri/fastmri_examples/adaptive_varnet/eval_pretrained_adaptive_varnet.py

Prompts

```
['run the CLI to evaluate a pretrained AdaptiveVarNet or VarNet model on fastMRI knee data and compute SSIM, PSNR, and NMSE metrics', 'load a PyTorch Lightning model checkpoint for AdaptiveVarNetModule or VarNetModule by restoring hyperparameters and state dict', 'compute the binary cross-entropy of a probability mask tensor used for adaptive sampling analysis', 'build an ArgumentParser with model, data, and mask configuration defaults for evaluating pretrained VarNet models on fastMRI data', 'evaluate a model on validation or training data and compute per-volume SSIM, PSNR, NMSE, marginal entropy, and mutual information', 'create a mask function for k-space subsampling given a mask type string, center fractions, and accelerations', 'create an EquispacedMaskFractionFunc instance with center fractions, accelerations, and optional skip low frequencies flag', 'calculate an acceleration mask for non-central k-space lines given column count, acceleration rate, and low frequency count', 'review the create_mask_for_mask_type function to understand how it dispatches between random and adaptive equispaced mask types', 'review the EquispacedMaskFractionFunc class to understand equispaced k-space masking with exact acceleration matching', 'run the adaptive VarNet training pipeline on fastMRI knee data with configurable acquisition learning', 'build the argument parser with defaults for data path, mask type, cascades, and WandB logging', 'create a WandB callback that logs train and validation metrics including SSIM, PSNR, and NMSE per epoch', 'test a trained VarNet or AdaptiveVarNet model on the fastMRI test split using PyTorch Lightning', 'make a descriptive WandB run name from acquisition type, acceleration rate, cascades, and hyperparameters', 'copy a file from source to destination using a temporary file for atomic writes', 'copy a file only if the destination does not already exist', 'review the copy_file function that performs atomic file copies with skip-if-exists logic', 'test the copy_file function with source and destination pathlib.Path tuples', 'refactor the copy_file function to support additional file copy options']
```

Usage

```
{'run_eval_pretrained_adaptive_varnet': 'run the CLI to evaluate a pretrained AdaptiveVarNet or VarNet model on fastMRI knee data and compute SSIM, PSNR, and NMSE metrics', 'load_model_from_checkpoint': 'load a PyTorch Lightning model checkpoint for AdaptiveVarNetModule or VarNetModule by restoring hyperparameters and state dict', 'compute_entropy_of_prob_mask': 'compute the binary cross-entropy of a probability mask tensor used for adaptive sampling analysis', 'build_args_for_evaluation': 'build an ArgumentParser with model, data, and mask configuration defaults for evaluating pretrained VarNet models on fastMRI data', 'evaluate_model_metrics_per_volume': 'evaluate a model on validation or training data and compute per-volume SSIM, PSNR, NMSE, marginal entropy, and mutual information'}
```

## File: facebookresearch_fastmri/fastmri_examples/adaptive_varnet/subsample.py

Prompts

```
['run the CLI to evaluate a pretrained AdaptiveVarNet or VarNet model on fastMRI knee data and compute SSIM, PSNR, and NMSE metrics', 'load a PyTorch Lightning model checkpoint for AdaptiveVarNetModule or VarNetModule by restoring hyperparameters and state dict', 'compute the binary cross-entropy of a probability mask tensor used for adaptive sampling analysis', 'build an ArgumentParser with model, data, and mask configuration defaults for evaluating pretrained VarNet models on fastMRI data', 'evaluate a model on validation or training data and compute per-volume SSIM, PSNR, NMSE, marginal entropy, and mutual information', 'create a mask function for k-space subsampling given a mask type string, center fractions, and accelerations', 'create an EquispacedMaskFractionFunc instance with center fractions, accelerations, and optional skip low frequencies flag', 'calculate an acceleration mask for non-central k-space lines given column count, acceleration rate, and low frequency count', 'review the create_mask_for_mask_type function to understand how it dispatches between random and adaptive equispaced mask types', 'review the EquispacedMaskFractionFunc class to understand equispaced k-space masking with exact acceleration matching', 'run the adaptive VarNet training pipeline on fastMRI knee data with configurable acquisition learning', 'build the argument parser with defaults for data path, mask type, cascades, and WandB logging', 'create a WandB callback that logs train and validation metrics including SSIM, PSNR, and NMSE per epoch', 'test a trained VarNet or AdaptiveVarNet model on the fastMRI test split using PyTorch Lightning', 'make a descriptive WandB run name from acquisition type, acceleration rate, cascades, and hyperparameters', 'copy a file from source to destination using a temporary file for atomic writes', 'copy a file only if the destination does not already exist', 'review the copy_file function that performs atomic file copies with skip-if-exists logic', 'test the copy_file function with source and destination pathlib.Path tuples', 'refactor the copy_file function to support additional file copy options']
```

Usage

```
{'create_mask_for_mask_type': 'create a mask function for k-space subsampling given a mask type string, center fractions, and accelerations', 'create_equispaced_mask_fraction_func': 'create an EquispacedMaskFractionFunc instance with center fractions, accelerations, and optional skip low frequencies flag', 'calculate_acceleration_mask': 'calculate an acceleration mask for non-central k-space lines given column count, acceleration rate, and low frequency count', 'review_create_mask_for_mask_type': 'review the create_mask_for_mask_type function to understand how it dispatches between random and adaptive equispaced mask types', 'review_equispaced_mask_fraction_func': 'review the EquispacedMaskFractionFunc class to understand equispaced k-space masking with exact acceleration matching'}
```

## File: facebookresearch_fastmri/fastmri_examples/adaptive_varnet/train_adaptive_varnet_demo.py

Prompts

```
['run the CLI to evaluate a pretrained AdaptiveVarNet or VarNet model on fastMRI knee data and compute SSIM, PSNR, and NMSE metrics', 'load a PyTorch Lightning model checkpoint for AdaptiveVarNetModule or VarNetModule by restoring hyperparameters and state dict', 'compute the binary cross-entropy of a probability mask tensor used for adaptive sampling analysis', 'build an ArgumentParser with model, data, and mask configuration defaults for evaluating pretrained VarNet models on fastMRI data', 'evaluate a model on validation or training data and compute per-volume SSIM, PSNR, NMSE, marginal entropy, and mutual information', 'create a mask function for k-space subsampling given a mask type string, center fractions, and accelerations', 'create an EquispacedMaskFractionFunc instance with center fractions, accelerations, and optional skip low frequencies flag', 'calculate an acceleration mask for non-central k-space lines given column count, acceleration rate, and low frequency count', 'review the create_mask_for_mask_type function to understand how it dispatches between random and adaptive equispaced mask types', 'review the EquispacedMaskFractionFunc class to understand equispaced k-space masking with exact acceleration matching', 'run the adaptive VarNet training pipeline on fastMRI knee data with configurable acquisition learning', 'build the argument parser with defaults for data path, mask type, cascades, and WandB logging', 'create a WandB callback that logs train and validation metrics including SSIM, PSNR, and NMSE per epoch', 'test a trained VarNet or AdaptiveVarNet model on the fastMRI test split using PyTorch Lightning', 'make a descriptive WandB run name from acquisition type, acceleration rate, cascades, and hyperparameters', 'copy a file from source to destination using a temporary file for atomic writes', 'copy a file only if the destination does not already exist', 'review the copy_file function that performs atomic file copies with skip-if-exists logic', 'test the copy_file function with source and destination pathlib.Path tuples', 'refactor the copy_file function to support additional file copy options']
```

Usage

```
{'run_adaptive_varnet_training': 'run the adaptive VarNet training pipeline on fastMRI knee data with configurable acquisition learning', 'build_argument_parser': 'build the argument parser with defaults for data path, mask type, cascades, and WandB logging', 'create_wandb_logger_callback': 'create a WandB callback that logs train and validation metrics including SSIM, PSNR, and NMSE per epoch', 'test_varnet_model': 'test a trained VarNet or AdaptiveVarNet model on the fastMRI test split using PyTorch Lightning', 'make_wandb_run_name': 'make a descriptive WandB run name from acquisition type, acceleration rate, cascades, and hyperparameters'}
```

## File: facebookresearch_fastmri/fastmri_examples/adaptive_varnet/util.py

Prompts

```
['run the CLI to evaluate a pretrained AdaptiveVarNet or VarNet model on fastMRI knee data and compute SSIM, PSNR, and NMSE metrics', 'load a PyTorch Lightning model checkpoint for AdaptiveVarNetModule or VarNetModule by restoring hyperparameters and state dict', 'compute the binary cross-entropy of a probability mask tensor used for adaptive sampling analysis', 'build an ArgumentParser with model, data, and mask configuration defaults for evaluating pretrained VarNet models on fastMRI data', 'evaluate a model on validation or training data and compute per-volume SSIM, PSNR, NMSE, marginal entropy, and mutual information', 'create a mask function for k-space subsampling given a mask type string, center fractions, and accelerations', 'create an EquispacedMaskFractionFunc instance with center fractions, accelerations, and optional skip low frequencies flag', 'calculate an acceleration mask for non-central k-space lines given column count, acceleration rate, and low frequency count', 'review the create_mask_for_mask_type function to understand how it dispatches between random and adaptive equispaced mask types', 'review the EquispacedMaskFractionFunc class to understand equispaced k-space masking with exact acceleration matching', 'run the adaptive VarNet training pipeline on fastMRI knee data with configurable acquisition learning', 'build the argument parser with defaults for data path, mask type, cascades, and WandB logging', 'create a WandB callback that logs train and validation metrics including SSIM, PSNR, and NMSE per epoch', 'test a trained VarNet or AdaptiveVarNet model on the fastMRI test split using PyTorch Lightning', 'make a descriptive WandB run name from acquisition type, acceleration rate, cascades, and hyperparameters', 'copy a file from source to destination using a temporary file for atomic writes', 'copy a file only if the destination does not already exist', 'review the copy_file function that performs atomic file copies with skip-if-exists logic', 'test the copy_file function with source and destination pathlib.Path tuples', 'refactor the copy_file function to support additional file copy options']
```

Usage

```
{'copy_file_atomic': 'copy a file from source to destination using a temporary file for atomic writes', 'copy_file_skip_existing': 'copy a file only if the destination does not already exist', 'review_copy_file': 'review the copy_file function that performs atomic file copies with skip-if-exists logic', 'test_copy_file': 'test the copy_file function with source and destination pathlib.Path tuples', 'refactor_copy_file': 'refactor the copy_file function to support additional file copy options'}
```

