# Agent Python Tools

- repo: facebookresearch/fastmri
- repo_uri: https://github.com/facebookresearch/fastmri

## File: facebookresearch_fastmri/fastmri_examples/adaptive_varnet/pl_modules/adaptive_varnet_module.py

Prompts

```
['build an AdaptiveVarNetModule instance with configurable cascades, pools, and channels for MRI reconstruction', 'run a training step on kspace data to compute loss and reconstruction output', 'run a validation step on kspace data to compute validation loss and log images', 'configure an Adam optimizer with StepLR scheduler for the adaptive variational network', 'add model-specific CLI arguments for num_cascades, pools, chans, lr, and weight_decay', 'create a DistributedArraySum metric to accumulate tensor arrays across distributed training steps', 'create a DistributedMetricSum metric to accumulate scalar values across distributed training steps', 'use DistributedArraySum update method to add batch tensors to the accumulated quantity state', 'use DistributedMetricSum update method to add scalar values to the accumulated quantity state', 'compute the final accumulated tensor array from a DistributedArraySum metric instance', 'build a VarNet model with configurable cascades, sensitivity map U-Net channels, and data consistency mode for accelerated MRI reconstruction', 'run the VarNet forward pass on k-space data with masked k-space and mask tensors to produce reconstructed MRI images', 'train a VarNetModule using PyTorch Lightning with Adam optimizer, SSIM loss, and learning rate scheduling for MRI reconstruction', 'review the VarNetModule validation step that computes NMSE, SSIM, and PSNR metrics and logs reconstruction images to TensorBoard', 'configure VarNetModule command-line arguments for cascades, U-Net channels, pooling layers, learning rate, and weight decay via argparse']
```

Usage

```
{'build_adaptive_varnet_module': 'build an AdaptiveVarNetModule instance with configurable cascades, pools, and channels for MRI reconstruction', 'run_training_step': 'run a training step on kspace data to compute loss and reconstruction output', 'run_validation_step': 'run a validation step on kspace data to compute validation loss and log images', 'configure_optimizers': 'configure an Adam optimizer with StepLR scheduler for the adaptive variational network', 'add_model_specific_args': 'add model-specific CLI arguments for num_cascades, pools, chans, lr, and weight_decay'}
```

## File: facebookresearch_fastmri/fastmri_examples/adaptive_varnet/pl_modules/metrics.py

Prompts

```
['build an AdaptiveVarNetModule instance with configurable cascades, pools, and channels for MRI reconstruction', 'run a training step on kspace data to compute loss and reconstruction output', 'run a validation step on kspace data to compute validation loss and log images', 'configure an Adam optimizer with StepLR scheduler for the adaptive variational network', 'add model-specific CLI arguments for num_cascades, pools, chans, lr, and weight_decay', 'create a DistributedArraySum metric to accumulate tensor arrays across distributed training steps', 'create a DistributedMetricSum metric to accumulate scalar values across distributed training steps', 'use DistributedArraySum update method to add batch tensors to the accumulated quantity state', 'use DistributedMetricSum update method to add scalar values to the accumulated quantity state', 'compute the final accumulated tensor array from a DistributedArraySum metric instance', 'build a VarNet model with configurable cascades, sensitivity map U-Net channels, and data consistency mode for accelerated MRI reconstruction', 'run the VarNet forward pass on k-space data with masked k-space and mask tensors to produce reconstructed MRI images', 'train a VarNetModule using PyTorch Lightning with Adam optimizer, SSIM loss, and learning rate scheduling for MRI reconstruction', 'review the VarNetModule validation step that computes NMSE, SSIM, and PSNR metrics and logs reconstruction images to TensorBoard', 'configure VarNetModule command-line arguments for cascades, U-Net channels, pooling layers, learning rate, and weight decay via argparse']
```

Usage

```
{'create_DistributedArraySum': 'create a DistributedArraySum metric to accumulate tensor arrays across distributed training steps', 'create_DistributedMetricSum': 'create a DistributedMetricSum metric to accumulate scalar values across distributed training steps', 'use_DistributedArraySum_update': 'use DistributedArraySum update method to add batch tensors to the accumulated quantity state', 'use_DistributedMetricSum_update': 'use DistributedMetricSum update method to add scalar values to the accumulated quantity state', 'compute_DistributedArraySum': 'compute the final accumulated tensor array from a DistributedArraySum metric instance'}
```

## File: facebookresearch_fastmri/fastmri_examples/adaptive_varnet/pl_modules/varnet_module.py

Prompts

```
['build an AdaptiveVarNetModule instance with configurable cascades, pools, and channels for MRI reconstruction', 'run a training step on kspace data to compute loss and reconstruction output', 'run a validation step on kspace data to compute validation loss and log images', 'configure an Adam optimizer with StepLR scheduler for the adaptive variational network', 'add model-specific CLI arguments for num_cascades, pools, chans, lr, and weight_decay', 'create a DistributedArraySum metric to accumulate tensor arrays across distributed training steps', 'create a DistributedMetricSum metric to accumulate scalar values across distributed training steps', 'use DistributedArraySum update method to add batch tensors to the accumulated quantity state', 'use DistributedMetricSum update method to add scalar values to the accumulated quantity state', 'compute the final accumulated tensor array from a DistributedArraySum metric instance', 'build a VarNet model with configurable cascades, sensitivity map U-Net channels, and data consistency mode for accelerated MRI reconstruction', 'run the VarNet forward pass on k-space data with masked k-space and mask tensors to produce reconstructed MRI images', 'train a VarNetModule using PyTorch Lightning with Adam optimizer, SSIM loss, and learning rate scheduling for MRI reconstruction', 'review the VarNetModule validation step that computes NMSE, SSIM, and PSNR metrics and logs reconstruction images to TensorBoard', 'configure VarNetModule command-line arguments for cascades, U-Net channels, pooling layers, learning rate, and weight decay via argparse']
```

Usage

```
{'build_varnet_model': 'build a VarNet model with configurable cascades, sensitivity map U-Net channels, and data consistency mode for accelerated MRI reconstruction', 'run_varnet_forward': 'run the VarNet forward pass on k-space data with masked k-space and mask tensors to produce reconstructed MRI images', 'train_varnet_module': 'train a VarNetModule using PyTorch Lightning with Adam optimizer, SSIM loss, and learning rate scheduling for MRI reconstruction', 'review_varnet_validation': 'review the VarNetModule validation step that computes NMSE, SSIM, and PSNR metrics and logs reconstruction images to TensorBoard', 'configure_varnet_args': 'configure VarNetModule command-line arguments for cascades, U-Net channels, pooling layers, learning rate, and weight decay via argparse'}
```

