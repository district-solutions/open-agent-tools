# Agent Python Tools

- repo: facebookresearch/neural-light-fields
- repo_uri: https://github.com/facebookresearch/neural-light-fields

## File: facebookresearch_neural-light-fields/losses.py

Prompts

```
['build a PyTorch module that computes mean squared error loss between inputs and targets', 'build a PyTorch module that computes mean absolute error loss between inputs and targets', 'build a PyTorch module that computes MSE loss on both real and imaginary parts of complex tensors', 'build a PyTorch module that computes MAE loss on both real and imaginary parts of complex tensors', 'build a PyTorch module that computes MSE loss on the top N smallest-difference samples using a config fraction', 'run the neural light field training pipeline with a Hydra config and PyTorch Lightning trainer', 'run elastic multi-GPU training using torch distributed launcher with the zeus rendezvous backend', 'run the main entry point using Hydra CLI to load config from conf/config.yaml', 'review the run function ModelCheckpoint callbacks that save full checkpoints and weights-only checkpoints', 'review the elastic_run function that branches between single GPU and multi-GPU distributed training', 'compute the mean squared error between two PyTorch image tensors with optional valid mask', 'calculate the peak signal-to-noise ratio between two images using scikit-image', 'calculate the structural similarity index between two multichannel images using scikit-image', 'compute the GPU-accelerated PSNR between predicted and ground truth image tensors', 'compute the GPU-accelerated SSIM between two image tensors using kornia']
```

Usage

```
{'build_MSELoss': 'build a PyTorch module that computes mean squared error loss between inputs and targets', 'build_MAEloss': 'build a PyTorch module that computes mean absolute error loss between inputs and targets', 'build_ComplexMSELoss': 'build a PyTorch module that computes MSE loss on both real and imaginary parts of complex tensors', 'build_ComplexMAELoss': 'build a PyTorch module that computes MAE loss on both real and imaginary parts of complex tensors', 'build_MSETopN': 'build a PyTorch module that computes MSE loss on the top N smallest-difference samples using a config fraction'}
```

## File: facebookresearch_neural-light-fields/main.py

Prompts

```
['build a PyTorch module that computes mean squared error loss between inputs and targets', 'build a PyTorch module that computes mean absolute error loss between inputs and targets', 'build a PyTorch module that computes MSE loss on both real and imaginary parts of complex tensors', 'build a PyTorch module that computes MAE loss on both real and imaginary parts of complex tensors', 'build a PyTorch module that computes MSE loss on the top N smallest-difference samples using a config fraction', 'run the neural light field training pipeline with a Hydra config and PyTorch Lightning trainer', 'run elastic multi-GPU training using torch distributed launcher with the zeus rendezvous backend', 'run the main entry point using Hydra CLI to load config from conf/config.yaml', 'review the run function ModelCheckpoint callbacks that save full checkpoints and weights-only checkpoints', 'review the elastic_run function that branches between single GPU and multi-GPU distributed training', 'compute the mean squared error between two PyTorch image tensors with optional valid mask', 'calculate the peak signal-to-noise ratio between two images using scikit-image', 'calculate the structural similarity index between two multichannel images using scikit-image', 'compute the GPU-accelerated PSNR between predicted and ground truth image tensors', 'compute the GPU-accelerated SSIM between two image tensors using kornia']
```

Usage

```
{'run_neural_lightfield_training': 'run the neural light field training pipeline with a Hydra config and PyTorch Lightning trainer', 'run_elastic_multi_gpu_training': 'run elastic multi-GPU training using torch distributed launcher with the zeus rendezvous backend', 'run_with_hydra_config': 'run the main entry point using Hydra CLI to load config from conf/config.yaml', 'review_run_checkpointing': 'review the run function ModelCheckpoint callbacks that save full checkpoints and weights-only checkpoints', 'review_elastic_run_gpu_logic': 'review the elastic_run function that branches between single GPU and multi-GPU distributed training'}
```

## File: facebookresearch_neural-light-fields/metrics.py

Prompts

```
['build a PyTorch module that computes mean squared error loss between inputs and targets', 'build a PyTorch module that computes mean absolute error loss between inputs and targets', 'build a PyTorch module that computes MSE loss on both real and imaginary parts of complex tensors', 'build a PyTorch module that computes MAE loss on both real and imaginary parts of complex tensors', 'build a PyTorch module that computes MSE loss on the top N smallest-difference samples using a config fraction', 'run the neural light field training pipeline with a Hydra config and PyTorch Lightning trainer', 'run elastic multi-GPU training using torch distributed launcher with the zeus rendezvous backend', 'run the main entry point using Hydra CLI to load config from conf/config.yaml', 'review the run function ModelCheckpoint callbacks that save full checkpoints and weights-only checkpoints', 'review the elastic_run function that branches between single GPU and multi-GPU distributed training', 'compute the mean squared error between two PyTorch image tensors with optional valid mask', 'calculate the peak signal-to-noise ratio between two images using scikit-image', 'calculate the structural similarity index between two multichannel images using scikit-image', 'compute the GPU-accelerated PSNR between predicted and ground truth image tensors', 'compute the GPU-accelerated SSIM between two image tensors using kornia']
```

Usage

```
{'compute_mse_loss': 'compute the mean squared error between two PyTorch image tensors with optional valid mask', 'calculate_psnr': 'calculate the peak signal-to-noise ratio between two images using scikit-image', 'calculate_ssim': 'calculate the structural similarity index between two multichannel images using scikit-image', 'compute_psnr_gpu': 'compute the GPU-accelerated PSNR between predicted and ground truth image tensors', 'compute_ssim_gpu': 'compute the GPU-accelerated SSIM between two image tensors using kornia'}
```

