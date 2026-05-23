# Agent Python Tools

- repo: facebookresearch/fastmri
- repo_uri: https://github.com/facebookresearch/fastmri

## File: facebookresearch_fastmri/fastmri_examples/varnet/run_pretrained_varnet_inference.py

Prompts

```
['run pretrained VarNet MRI reconstruction inference on subsampled knee or brain multi-coil data', 'download a pretrained VarNet state dict from the fastMRI public model repository with progress tracking', 'run a single VarNet forward pass on a batch of masked k-space data and return cropped output', 'review the run_inference function that sets up data loading, model inference, and saves reconstructions', 'refactor the download_model function to support resumable downloads or alternative authentication methods', 'run the VarNet MRI reconstruction model training on knee data with configurable acceleration rates', 'build argument parser with defaults for VarNet training including mask type, learning rate, and GPU config', 'create VarNetDataTransform with k-space mask function for training and validation data augmentation', 'test the trained VarNet model on the multicoil challenge dataset using PyTorch Lightning trainer', 'review the cli_main function that orchestrates data module, model, and trainer setup for VarNet training']
```

Usage

```
{'run_varnet_inference': 'run pretrained VarNet MRI reconstruction inference on subsampled knee or brain multi-coil data', 'download_model': 'download a pretrained VarNet state dict from the fastMRI public model repository with progress tracking', 'run_varnet_model': 'run a single VarNet forward pass on a batch of masked k-space data and return cropped output', 'review_run_inference': 'review the run_inference function that sets up data loading, model inference, and saves reconstructions', 'refactor_download_model': 'refactor the download_model function to support resumable downloads or alternative authentication methods'}
```

## File: facebookresearch_fastmri/fastmri_examples/varnet/train_varnet_demo.py

Prompts

```
['run pretrained VarNet MRI reconstruction inference on subsampled knee or brain multi-coil data', 'download a pretrained VarNet state dict from the fastMRI public model repository with progress tracking', 'run a single VarNet forward pass on a batch of masked k-space data and return cropped output', 'review the run_inference function that sets up data loading, model inference, and saves reconstructions', 'refactor the download_model function to support resumable downloads or alternative authentication methods', 'run the VarNet MRI reconstruction model training on knee data with configurable acceleration rates', 'build argument parser with defaults for VarNet training including mask type, learning rate, and GPU config', 'create VarNetDataTransform with k-space mask function for training and validation data augmentation', 'test the trained VarNet model on the multicoil challenge dataset using PyTorch Lightning trainer', 'review the cli_main function that orchestrates data module, model, and trainer setup for VarNet training']
```

Usage

```
{'run_varnet_training': 'run the VarNet MRI reconstruction model training on knee data with configurable acceleration rates', 'build_args_varnet_demo': 'build argument parser with defaults for VarNet training including mask type, learning rate, and GPU config', 'create_varnet_data_transform': 'create VarNetDataTransform with k-space mask function for training and validation data augmentation', 'test_varnet_model': 'test the trained VarNet model on the multicoil challenge dataset using PyTorch Lightning trainer', 'review_cli_main': 'review the cli_main function that orchestrates data module, model, and trainer setup for VarNet training'}
```

