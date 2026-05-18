# Agent Python Tools

- repo: facebookresearch/mobile-vision
- repo_uri: https://github.com/facebookresearch/mobile-vision

## File: facebookresearch_mobile-vision/mobile_cv/arch/layers/batch_norm.py

Prompts

```
['create a FrozenBatchNorm2d module with fixed affine parameters for n channels', 'build a NaiveSyncBatchNorm layer that correctly syncs gradients across distributed workers', 'build a NaiveSyncBatchNorm1d layer for 1D inputs with cross-worker gradient synchronization', 'build a NaiveSyncBatchNorm3d layer for 3D tensor inputs with distributed statistics', 'create a SyncBatchNormWrapper that auto-selects GPU SyncBatchNorm or CPU NaiveSyncBatchNorm', 'create a Conv2d layer with optional normalization and activation functions built in', 'use the cat function to efficiently concatenate tensors without unnecessary copies', 'create a ConvTranspose2d layer that handles empty batch tensors gracefully', 'create an AvgPool2d layer that computes correct output shapes for empty tensors', 'use Conv2dArgs.FromConv2d to extract kernel, padding, stride, dilation, and output channels from a Conv2d']
```

Usage

```
{'create_frozen_batch_norm_2d': 'create a FrozenBatchNorm2d module with fixed affine parameters for n channels', 'build_naive_sync_batch_norm_2d': 'build a NaiveSyncBatchNorm layer that correctly syncs gradients across distributed workers', 'build_naive_sync_batch_norm_1d': 'build a NaiveSyncBatchNorm1d layer for 1D inputs with cross-worker gradient synchronization', 'build_naive_sync_batch_norm_3d': 'build a NaiveSyncBatchNorm3d layer for 3D tensor inputs with distributed statistics', 'create_sync_batch_norm_wrapper': 'create a SyncBatchNormWrapper that auto-selects GPU SyncBatchNorm or CPU NaiveSyncBatchNorm'}
```

## File: facebookresearch_mobile-vision/mobile_cv/arch/layers/misc.py

Prompts

```
['create a FrozenBatchNorm2d module with fixed affine parameters for n channels', 'build a NaiveSyncBatchNorm layer that correctly syncs gradients across distributed workers', 'build a NaiveSyncBatchNorm1d layer for 1D inputs with cross-worker gradient synchronization', 'build a NaiveSyncBatchNorm3d layer for 3D tensor inputs with distributed statistics', 'create a SyncBatchNormWrapper that auto-selects GPU SyncBatchNorm or CPU NaiveSyncBatchNorm', 'create a Conv2d layer with optional normalization and activation functions built in', 'use the cat function to efficiently concatenate tensors without unnecessary copies', 'create a ConvTranspose2d layer that handles empty batch tensors gracefully', 'create an AvgPool2d layer that computes correct output shapes for empty tensors', 'use Conv2dArgs.FromConv2d to extract kernel, padding, stride, dilation, and output channels from a Conv2d']
```

Usage

```
{'create_conv2d_with_norm_activation': 'create a Conv2d layer with optional normalization and activation functions built in', 'use_cat_efficient_concat': 'use the cat function to efficiently concatenate tensors without unnecessary copies', 'create_convtranspose2d_empty_batch': 'create a ConvTranspose2d layer that handles empty batch tensors gracefully', 'create_avgpool2d_empty_batch': 'create an AvgPool2d layer that computes correct output shapes for empty tensors', 'use_conv2dargs_from_conv': 'use Conv2dArgs.FromConv2d to extract kernel, padding, stride, dilation, and output channels from a Conv2d'}
```

