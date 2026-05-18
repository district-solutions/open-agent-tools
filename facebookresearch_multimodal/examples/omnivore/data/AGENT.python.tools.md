# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/examples/omnivore/data/data_builder.py

Prompts

```
['build a multimodal data loader combining image, video, and rgbd datasets with configurable sampling factors', 'build a video data loader for the Kinetics dataset with clip sampling and caching support', 'build an image data loader for ImageNet with mixup and cutmix augmentation transforms', 'build a depth data loader for the SUN RGB-D dataset with RGBD channel classification presets', 'construct a PyTorch DataLoader with optional mixup/cutmix collate function and distributed sampler support', 'create a Kinetics video dataset subclass that returns video, label, and video index tuples', 'create a SUN RGB-D vision dataset that loads RGBD images and scene class labels for 19 classes', 'use the SUN RGB-D dataset to compute disparity tensors from depth images and camera intrinsics', 'create a concatenated data loader that groups multiple data loaders with configurable repeat factors and shuffling', 'use the ConcatDataLoader set_epoch method to enable reproducible shuffling across distributed training epochs', 'build a RandAugment3d transform to apply random augmentations to RGBD tensor images', 'create a function that applies a named augmentation operation like ShearX or Rotate to a tensor', 'test the RandAugment3d forward method by passing a 4-channel RGBD tensor and verifying output shape', 'refactor _apply_op to support additional augmentation operations beyond the current 14 supported ops', 'review the RandAugment3d class and its geom_ops set to understand which operations apply to all channels', 'build a data augmentation pipeline using RandomMixup to blend image batches with configurable probability and alpha', 'build a data augmentation pipeline using RandomCutmix to patch-swap regions between rolled image batches', 'create a DropChannels transform to randomly drop and pad input channels with tied channel groups', 'create a DepthNorm transform to normalize and clamp the depth channel of 4-channel RGBD tensors', 'build a ConvertTCHWtoCTHW transform to permute video tensors from TCHW to CTHW layout']
```

Usage

```
{'build_omnivore_data_loader': 'build a multimodal data loader combining image, video, and rgbd datasets with configurable sampling factors', 'build_kinetics_data_loader': 'build a video data loader for the Kinetics dataset with clip sampling and caching support', 'build_imagenet_data_loader': 'build an image data loader for ImageNet with mixup and cutmix augmentation transforms', 'build_sunrgbd_data_loader': 'build a depth data loader for the SUN RGB-D dataset with RGBD channel classification presets', 'construct_data_loader': 'construct a PyTorch DataLoader with optional mixup/cutmix collate function and distributed sampler support'}
```

## File: facebookresearch_multimodal/examples/omnivore/data/datasets.py

Prompts

```
['build a multimodal data loader combining image, video, and rgbd datasets with configurable sampling factors', 'build a video data loader for the Kinetics dataset with clip sampling and caching support', 'build an image data loader for ImageNet with mixup and cutmix augmentation transforms', 'build a depth data loader for the SUN RGB-D dataset with RGBD channel classification presets', 'construct a PyTorch DataLoader with optional mixup/cutmix collate function and distributed sampler support', 'create a Kinetics video dataset subclass that returns video, label, and video index tuples', 'create a SUN RGB-D vision dataset that loads RGBD images and scene class labels for 19 classes', 'use the SUN RGB-D dataset to compute disparity tensors from depth images and camera intrinsics', 'create a concatenated data loader that groups multiple data loaders with configurable repeat factors and shuffling', 'use the ConcatDataLoader set_epoch method to enable reproducible shuffling across distributed training epochs', 'build a RandAugment3d transform to apply random augmentations to RGBD tensor images', 'create a function that applies a named augmentation operation like ShearX or Rotate to a tensor', 'test the RandAugment3d forward method by passing a 4-channel RGBD tensor and verifying output shape', 'refactor _apply_op to support additional augmentation operations beyond the current 14 supported ops', 'review the RandAugment3d class and its geom_ops set to understand which operations apply to all channels', 'build a data augmentation pipeline using RandomMixup to blend image batches with configurable probability and alpha', 'build a data augmentation pipeline using RandomCutmix to patch-swap regions between rolled image batches', 'create a DropChannels transform to randomly drop and pad input channels with tied channel groups', 'create a DepthNorm transform to normalize and clamp the depth channel of 4-channel RGBD tensors', 'build a ConvertTCHWtoCTHW transform to permute video tensors from TCHW to CTHW layout']
```

Usage

```
{'create_OmnivoreKinetics_dataset': 'create a Kinetics video dataset subclass that returns video, label, and video index tuples', 'create_OmnivoreSunRgbdDatasets_dataset': 'create a SUN RGB-D vision dataset that loads RGBD images and scene class labels for 19 classes', 'use_OmnivoreSunRgbdDatasets_disparity': 'use the SUN RGB-D dataset to compute disparity tensors from depth images and camera intrinsics', 'create_ConcatDataLoader': 'create a concatenated data loader that groups multiple data loaders with configurable repeat factors and shuffling', 'use_ConcatDataLoader_set_epoch': 'use the ConcatDataLoader set_epoch method to enable reproducible shuffling across distributed training epochs'}
```

## File: facebookresearch_multimodal/examples/omnivore/data/rand_aug3d.py

Prompts

```
['build a multimodal data loader combining image, video, and rgbd datasets with configurable sampling factors', 'build a video data loader for the Kinetics dataset with clip sampling and caching support', 'build an image data loader for ImageNet with mixup and cutmix augmentation transforms', 'build a depth data loader for the SUN RGB-D dataset with RGBD channel classification presets', 'construct a PyTorch DataLoader with optional mixup/cutmix collate function and distributed sampler support', 'create a Kinetics video dataset subclass that returns video, label, and video index tuples', 'create a SUN RGB-D vision dataset that loads RGBD images and scene class labels for 19 classes', 'use the SUN RGB-D dataset to compute disparity tensors from depth images and camera intrinsics', 'create a concatenated data loader that groups multiple data loaders with configurable repeat factors and shuffling', 'use the ConcatDataLoader set_epoch method to enable reproducible shuffling across distributed training epochs', 'build a RandAugment3d transform to apply random augmentations to RGBD tensor images', 'create a function that applies a named augmentation operation like ShearX or Rotate to a tensor', 'test the RandAugment3d forward method by passing a 4-channel RGBD tensor and verifying output shape', 'refactor _apply_op to support additional augmentation operations beyond the current 14 supported ops', 'review the RandAugment3d class and its geom_ops set to understand which operations apply to all channels', 'build a data augmentation pipeline using RandomMixup to blend image batches with configurable probability and alpha', 'build a data augmentation pipeline using RandomCutmix to patch-swap regions between rolled image batches', 'create a DropChannels transform to randomly drop and pad input channels with tied channel groups', 'create a DepthNorm transform to normalize and clamp the depth channel of 4-channel RGBD tensors', 'build a ConvertTCHWtoCTHW transform to permute video tensors from TCHW to CTHW layout']
```

Usage

```
{'build_rand_augment_3d': 'build a RandAugment3d transform to apply random augmentations to RGBD tensor images', 'create_apply_op': 'create a function that applies a named augmentation operation like ShearX or Rotate to a tensor', 'test_RandAugment3d_forward': 'test the RandAugment3d forward method by passing a 4-channel RGBD tensor and verifying output shape', 'refactor_apply_op': 'refactor _apply_op to support additional augmentation operations beyond the current 14 supported ops', 'review_RandAugment3d_geom_ops': 'review the RandAugment3d class and its geom_ops set to understand which operations apply to all channels'}
```

## File: facebookresearch_multimodal/examples/omnivore/data/transforms.py

Prompts

```
['build a multimodal data loader combining image, video, and rgbd datasets with configurable sampling factors', 'build a video data loader for the Kinetics dataset with clip sampling and caching support', 'build an image data loader for ImageNet with mixup and cutmix augmentation transforms', 'build a depth data loader for the SUN RGB-D dataset with RGBD channel classification presets', 'construct a PyTorch DataLoader with optional mixup/cutmix collate function and distributed sampler support', 'create a Kinetics video dataset subclass that returns video, label, and video index tuples', 'create a SUN RGB-D vision dataset that loads RGBD images and scene class labels for 19 classes', 'use the SUN RGB-D dataset to compute disparity tensors from depth images and camera intrinsics', 'create a concatenated data loader that groups multiple data loaders with configurable repeat factors and shuffling', 'use the ConcatDataLoader set_epoch method to enable reproducible shuffling across distributed training epochs', 'build a RandAugment3d transform to apply random augmentations to RGBD tensor images', 'create a function that applies a named augmentation operation like ShearX or Rotate to a tensor', 'test the RandAugment3d forward method by passing a 4-channel RGBD tensor and verifying output shape', 'refactor _apply_op to support additional augmentation operations beyond the current 14 supported ops', 'review the RandAugment3d class and its geom_ops set to understand which operations apply to all channels', 'build a data augmentation pipeline using RandomMixup to blend image batches with configurable probability and alpha', 'build a data augmentation pipeline using RandomCutmix to patch-swap regions between rolled image batches', 'create a DropChannels transform to randomly drop and pad input channels with tied channel groups', 'create a DepthNorm transform to normalize and clamp the depth channel of 4-channel RGBD tensors', 'build a ConvertTCHWtoCTHW transform to permute video tensors from TCHW to CTHW layout']
```

Usage

```
{'build_random_mixup_augmentation': 'build a data augmentation pipeline using RandomMixup to blend image batches with configurable probability and alpha', 'build_random_cutmix_augmentation': 'build a data augmentation pipeline using RandomCutmix to patch-swap regions between rolled image batches', 'create_drop_channels_transform': 'create a DropChannels transform to randomly drop and pad input channels with tied channel groups', 'create_depth_norm_transform': 'create a DepthNorm transform to normalize and clamp the depth channel of 4-channel RGBD tensors', 'build_tensor_permute_transform': 'build a ConvertTCHWtoCTHW transform to permute video tensors from TCHW to CTHW layout'}
```

