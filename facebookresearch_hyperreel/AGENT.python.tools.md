# Agent Python Tools

- repo: facebookresearch/hyperreel
- repo_uri: https://github.com/facebookresearch/hyperreel

## File: facebookresearch_hyperreel/losses.py

Prompts

```
['create a HuberLoss module with configurable delta for robust regression training', 'create an MSELoss module that computes mean squared error between inputs and targets', 'create a WeightedMSELoss module that applies per-sample weights to squared error', 'create a ComplexMSELoss module that computes MSE on real and imaginary parts separately', 'create an MSETopN module that computes MSE on the top N worst samples by fraction', 'run the INR training pipeline with a Hydra config and PyTorch Lightning trainer', 'run elastic multi-GPU training using torch distributed launcher with the run function', 'create a custom ModelCheckpoint callback that saves the last top k checkpoints every N epochs', 'run the main entry point that uses Hydra to load config and start training', 'review the INRModelCheckpoint class _save_last_checkpoint method to understand epoch-based saving logic', 'compute the mean squared error between predicted and ground truth image tensors', 'compute the peak signal to noise ratio between two images using scikit-image', 'compute the structural similarity index between two multichannel images with gaussian weights', 'compute the GPU-accelerated peak signal to noise ratio between predicted and ground truth tensors', 'compute the GPU-accelerated structural similarity index between two image tensors using kornia']
```

Usage

```
{'create_HuberLoss': 'create a HuberLoss module with configurable delta for robust regression training', 'create_MSELoss': 'create an MSELoss module that computes mean squared error between inputs and targets', 'create_WeightedMSELoss': 'create a WeightedMSELoss module that applies per-sample weights to squared error', 'create_ComplexMSELoss': 'create a ComplexMSELoss module that computes MSE on real and imaginary parts separately', 'create_MSETopN': 'create an MSETopN module that computes MSE on the top N worst samples by fraction'}
```

## File: facebookresearch_hyperreel/main.py

Prompts

```
['create a HuberLoss module with configurable delta for robust regression training', 'create an MSELoss module that computes mean squared error between inputs and targets', 'create a WeightedMSELoss module that applies per-sample weights to squared error', 'create a ComplexMSELoss module that computes MSE on real and imaginary parts separately', 'create an MSETopN module that computes MSE on the top N worst samples by fraction', 'run the INR training pipeline with a Hydra config and PyTorch Lightning trainer', 'run elastic multi-GPU training using torch distributed launcher with the run function', 'create a custom ModelCheckpoint callback that saves the last top k checkpoints every N epochs', 'run the main entry point that uses Hydra to load config and start training', 'review the INRModelCheckpoint class _save_last_checkpoint method to understand epoch-based saving logic', 'compute the mean squared error between predicted and ground truth image tensors', 'compute the peak signal to noise ratio between two images using scikit-image', 'compute the structural similarity index between two multichannel images with gaussian weights', 'compute the GPU-accelerated peak signal to noise ratio between predicted and ground truth tensors', 'compute the GPU-accelerated structural similarity index between two image tensors using kornia']
```

Usage

```
{'run_INR_training': 'run the INR training pipeline with a Hydra config and PyTorch Lightning trainer', 'run_elastic_multigpu': 'run elastic multi-GPU training using torch distributed launcher with the run function', 'create_INRModelCheckpoint': 'create a custom ModelCheckpoint callback that saves the last top k checkpoints every N epochs', 'run_Hydra_main': 'run the main entry point that uses Hydra to load config and start training', 'review_INRModelCheckpoint_save_last': 'review the INRModelCheckpoint class _save_last_checkpoint method to understand epoch-based saving logic'}
```

## File: facebookresearch_hyperreel/metrics.py

Prompts

```
['create a HuberLoss module with configurable delta for robust regression training', 'create an MSELoss module that computes mean squared error between inputs and targets', 'create a WeightedMSELoss module that applies per-sample weights to squared error', 'create a ComplexMSELoss module that computes MSE on real and imaginary parts separately', 'create an MSETopN module that computes MSE on the top N worst samples by fraction', 'run the INR training pipeline with a Hydra config and PyTorch Lightning trainer', 'run elastic multi-GPU training using torch distributed launcher with the run function', 'create a custom ModelCheckpoint callback that saves the last top k checkpoints every N epochs', 'run the main entry point that uses Hydra to load config and start training', 'review the INRModelCheckpoint class _save_last_checkpoint method to understand epoch-based saving logic', 'compute the mean squared error between predicted and ground truth image tensors', 'compute the peak signal to noise ratio between two images using scikit-image', 'compute the structural similarity index between two multichannel images with gaussian weights', 'compute the GPU-accelerated peak signal to noise ratio between predicted and ground truth tensors', 'compute the GPU-accelerated structural similarity index between two image tensors using kornia']
```

Usage

```
{'compute_mse': 'compute the mean squared error between predicted and ground truth image tensors', 'compute_psnr': 'compute the peak signal to noise ratio between two images using scikit-image', 'compute_ssim': 'compute the structural similarity index between two multichannel images with gaussian weights', 'compute_psnr_gpu': 'compute the GPU-accelerated peak signal to noise ratio between predicted and ground truth tensors', 'compute_ssim_gpu': 'compute the GPU-accelerated structural similarity index between two image tensors using kornia'}
```

