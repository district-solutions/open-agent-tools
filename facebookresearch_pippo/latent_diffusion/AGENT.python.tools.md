# Agent Python Tools

- repo: facebookresearch/pippo
- repo_uri: https://github.com/facebookresearch/pippo

## File: facebookresearch_pippo/latent_diffusion/data.py

Prompts

```
['load all numpy sample files from the ava_samples directory and return them as a list', 'load sample batches with configurable batch size, views, and resolution for overfitting', 'visualize a single dataset sample as an MP4 video with video, keypoints, and reference image', 'review the load_batches function to understand how it preprocesses and collates samples', 'refactor the visualize_sample function to support additional tensor reshaping and video output options', 'build a PyTorch module that computes L2 loss between predicted noise and ground truth noise', 'create a forward pass that takes a preds dict with noise_preds and noise keys and returns L2 loss', 'test the DenoisingLoss class by passing a preds dict with noise_preds and noise tensors', 'refactor the DenoisingLoss forward method to support additional loss types beyond L2', 'review the DenoisingLoss forward method to understand how it computes and returns loss dictionaries', 'load a Python class dynamically given its fully qualified dotted path string', 'instantiate a model or object from an OmegaConf config with optional checkpoint loading', 'load a PyTorch checkpoint into one or more modules with shape mismatch and ignore filters', 'build a PyTorch optimizer from a config dict with per-module learning rate support', 'count the total number of trainable or non-trainable parameters in a PyTorch model']
```

Usage

```
{'load_samples': 'load all numpy sample files from the ava_samples directory and return them as a list', 'load_batches': 'load sample batches with configurable batch size, views, and resolution for overfitting', 'visualize_sample': 'visualize a single dataset sample as an MP4 video with video, keypoints, and reference image', 'review_load_batches': 'review the load_batches function to understand how it preprocesses and collates samples', 'refactor_visualize_sample': 'refactor the visualize_sample function to support additional tensor reshaping and video output options'}
```

## File: facebookresearch_pippo/latent_diffusion/losses.py

Prompts

```
['load all numpy sample files from the ava_samples directory and return them as a list', 'load sample batches with configurable batch size, views, and resolution for overfitting', 'visualize a single dataset sample as an MP4 video with video, keypoints, and reference image', 'review the load_batches function to understand how it preprocesses and collates samples', 'refactor the visualize_sample function to support additional tensor reshaping and video output options', 'build a PyTorch module that computes L2 loss between predicted noise and ground truth noise', 'create a forward pass that takes a preds dict with noise_preds and noise keys and returns L2 loss', 'test the DenoisingLoss class by passing a preds dict with noise_preds and noise tensors', 'refactor the DenoisingLoss forward method to support additional loss types beyond L2', 'review the DenoisingLoss forward method to understand how it computes and returns loss dictionaries', 'load a Python class dynamically given its fully qualified dotted path string', 'instantiate a model or object from an OmegaConf config with optional checkpoint loading', 'load a PyTorch checkpoint into one or more modules with shape mismatch and ignore filters', 'build a PyTorch optimizer from a config dict with per-module learning rate support', 'count the total number of trainable or non-trainable parameters in a PyTorch model']
```

Usage

```
{'build_denoising_loss_module': 'build a PyTorch module that computes L2 loss between predicted noise and ground truth noise', 'create_denoising_loss_forward': 'create a forward pass that takes a preds dict with noise_preds and noise keys and returns L2 loss', 'test_DenoisingLoss': 'test the DenoisingLoss class by passing a preds dict with noise_preds and noise tensors', 'refactor_DenoisingLoss': 'refactor the DenoisingLoss forward method to support additional loss types beyond L2', 'review_DenoisingLoss_forward': 'review the DenoisingLoss forward method to understand how it computes and returns loss dictionaries'}
```

## File: facebookresearch_pippo/latent_diffusion/utils.py

Prompts

```
['load all numpy sample files from the ava_samples directory and return them as a list', 'load sample batches with configurable batch size, views, and resolution for overfitting', 'visualize a single dataset sample as an MP4 video with video, keypoints, and reference image', 'review the load_batches function to understand how it preprocesses and collates samples', 'refactor the visualize_sample function to support additional tensor reshaping and video output options', 'build a PyTorch module that computes L2 loss between predicted noise and ground truth noise', 'create a forward pass that takes a preds dict with noise_preds and noise keys and returns L2 loss', 'test the DenoisingLoss class by passing a preds dict with noise_preds and noise tensors', 'refactor the DenoisingLoss forward method to support additional loss types beyond L2', 'review the DenoisingLoss forward method to understand how it computes and returns loss dictionaries', 'load a Python class dynamically given its fully qualified dotted path string', 'instantiate a model or object from an OmegaConf config with optional checkpoint loading', 'load a PyTorch checkpoint into one or more modules with shape mismatch and ignore filters', 'build a PyTorch optimizer from a config dict with per-module learning rate support', 'count the total number of trainable or non-trainable parameters in a PyTorch model']
```

Usage

```
{'load_class_from_string': 'load a Python class dynamically given its fully qualified dotted path string', 'load_from_config_instantiate': 'instantiate a model or object from an OmegaConf config with optional checkpoint loading', 'load_checkpoint_state_dict': 'load a PyTorch checkpoint into one or more modules with shape mismatch and ignore filters', 'build_optimizer_from_config': 'build a PyTorch optimizer from a config dict with per-module learning rate support', 'count_parameters_model': 'count the total number of trainable or non-trainable parameters in a PyTorch model'}
```

