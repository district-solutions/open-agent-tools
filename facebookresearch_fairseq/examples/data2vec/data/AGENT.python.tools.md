# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/data2vec/data/add_class_target_dataset.py

Prompts

```
['create an AddClassTargetDataset wrapper that adds class labels to a fairseq dataset for supervised training', 'use AddClassTargetDataset with multi_class mode to generate one-hot encoded label vectors for each sample', 'use AddClassTargetDataset in single-class mode to map labels via label_indices for classification tasks', 'review the AddClassTargetDataset collater method that stacks labels and optionally adds them to net_input', 'refactor AddClassTargetDataset to use label_indices for remapping raw labels to class indices', 'create an ImageDataset that loads image files from a root directory and auto-discovers class labels from subdirectories', 'create an ImageDataset that loads image files from a root directory without class labels for unsupervised learning', 'test the ImageDataset __getitem__ method to verify it returns a dictionary with image tensor and optional label', 'review the ImageDataset collater method that stacks sample images into batched tensors for model input', 'refactor the ImageDataset ordered_indices method to customize batch ordering with or without shuffling', 'build a training image transform with color jitter, auto augment, and random erasing for MAE finetuning', 'build an evaluation image transform with resize, center crop, and normalization for MAE finetuning', 'create a MaeFinetuningImageDataset from an ImageFolder path with caching and augmentation transforms', 'collate MaeFinetuningImageDataset samples into batched tensors with ids, images, and labels', 'get shuffled or sequential ordered indices for batch construction from MaeFinetuningImageDataset', 'create a MaeImageDataset from an ImageFolder root with configurable mask probability and patch size', 'use caching_loader to wrap a torchvision loader with a local cache directory for faster image loading', 'apply RandomResizedCropAndInterpolationWithTwoPic to crop and resize PIL images with random aspect ratio', 'compute a precomputed block mask for MAE image patches using compute_block_mask_1d or compute_block_mask_2d', 'collate MaeImageDataset samples into batched tensors with optional target and precomputed mask keys']
```

Usage

```
{'create_AddClassTargetDataset': 'create an AddClassTargetDataset wrapper that adds class labels to a fairseq dataset for supervised training', 'use_AddClassTargetDataset_multiclass': 'use AddClassTargetDataset with multi_class mode to generate one-hot encoded label vectors for each sample', 'use_AddClassTargetDataset_singleclass': 'use AddClassTargetDataset in single-class mode to map labels via label_indices for classification tasks', 'review_AddClassTargetDataset_collater': 'review the AddClassTargetDataset collater method that stacks labels and optionally adds them to net_input', 'refactor_AddClassTargetDataset_label_indices': 'refactor AddClassTargetDataset to use label_indices for remapping raw labels to class indices'}
```

## File: facebookresearch_fairseq/examples/data2vec/data/image_dataset.py

Prompts

```
['create an AddClassTargetDataset wrapper that adds class labels to a fairseq dataset for supervised training', 'use AddClassTargetDataset with multi_class mode to generate one-hot encoded label vectors for each sample', 'use AddClassTargetDataset in single-class mode to map labels via label_indices for classification tasks', 'review the AddClassTargetDataset collater method that stacks labels and optionally adds them to net_input', 'refactor AddClassTargetDataset to use label_indices for remapping raw labels to class indices', 'create an ImageDataset that loads image files from a root directory and auto-discovers class labels from subdirectories', 'create an ImageDataset that loads image files from a root directory without class labels for unsupervised learning', 'test the ImageDataset __getitem__ method to verify it returns a dictionary with image tensor and optional label', 'review the ImageDataset collater method that stacks sample images into batched tensors for model input', 'refactor the ImageDataset ordered_indices method to customize batch ordering with or without shuffling', 'build a training image transform with color jitter, auto augment, and random erasing for MAE finetuning', 'build an evaluation image transform with resize, center crop, and normalization for MAE finetuning', 'create a MaeFinetuningImageDataset from an ImageFolder path with caching and augmentation transforms', 'collate MaeFinetuningImageDataset samples into batched tensors with ids, images, and labels', 'get shuffled or sequential ordered indices for batch construction from MaeFinetuningImageDataset', 'create a MaeImageDataset from an ImageFolder root with configurable mask probability and patch size', 'use caching_loader to wrap a torchvision loader with a local cache directory for faster image loading', 'apply RandomResizedCropAndInterpolationWithTwoPic to crop and resize PIL images with random aspect ratio', 'compute a precomputed block mask for MAE image patches using compute_block_mask_1d or compute_block_mask_2d', 'collate MaeImageDataset samples into batched tensors with optional target and precomputed mask keys']
```

Usage

```
{'create_ImageDataset_with_classes': 'create an ImageDataset that loads image files from a root directory and auto-discovers class labels from subdirectories', 'create_ImageDataset_without_classes': 'create an ImageDataset that loads image files from a root directory without class labels for unsupervised learning', 'test_ImageDataset_getitem': 'test the ImageDataset __getitem__ method to verify it returns a dictionary with image tensor and optional label', 'review_ImageDataset_collater': 'review the ImageDataset collater method that stacks sample images into batched tensors for model input', 'refactor_ImageDataset_ordered_indices': 'refactor the ImageDataset ordered_indices method to customize batch ordering with or without shuffling'}
```

## File: facebookresearch_fairseq/examples/data2vec/data/mae_finetuning_image_dataset.py

Prompts

```
['create an AddClassTargetDataset wrapper that adds class labels to a fairseq dataset for supervised training', 'use AddClassTargetDataset with multi_class mode to generate one-hot encoded label vectors for each sample', 'use AddClassTargetDataset in single-class mode to map labels via label_indices for classification tasks', 'review the AddClassTargetDataset collater method that stacks labels and optionally adds them to net_input', 'refactor AddClassTargetDataset to use label_indices for remapping raw labels to class indices', 'create an ImageDataset that loads image files from a root directory and auto-discovers class labels from subdirectories', 'create an ImageDataset that loads image files from a root directory without class labels for unsupervised learning', 'test the ImageDataset __getitem__ method to verify it returns a dictionary with image tensor and optional label', 'review the ImageDataset collater method that stacks sample images into batched tensors for model input', 'refactor the ImageDataset ordered_indices method to customize batch ordering with or without shuffling', 'build a training image transform with color jitter, auto augment, and random erasing for MAE finetuning', 'build an evaluation image transform with resize, center crop, and normalization for MAE finetuning', 'create a MaeFinetuningImageDataset from an ImageFolder path with caching and augmentation transforms', 'collate MaeFinetuningImageDataset samples into batched tensors with ids, images, and labels', 'get shuffled or sequential ordered indices for batch construction from MaeFinetuningImageDataset', 'create a MaeImageDataset from an ImageFolder root with configurable mask probability and patch size', 'use caching_loader to wrap a torchvision loader with a local cache directory for faster image loading', 'apply RandomResizedCropAndInterpolationWithTwoPic to crop and resize PIL images with random aspect ratio', 'compute a precomputed block mask for MAE image patches using compute_block_mask_1d or compute_block_mask_2d', 'collate MaeImageDataset samples into batched tensors with optional target and precomputed mask keys']
```

Usage

```
{'build_transform_train': 'build a training image transform with color jitter, auto augment, and random erasing for MAE finetuning', 'build_transform_eval': 'build an evaluation image transform with resize, center crop, and normalization for MAE finetuning', 'create_MaeFinetuningImageDataset': 'create a MaeFinetuningImageDataset from an ImageFolder path with caching and augmentation transforms', 'collate_MaeFinetuningImageDataset_samples': 'collate MaeFinetuningImageDataset samples into batched tensors with ids, images, and labels', 'get_ordered_indices_MaeFinetuningImageDataset': 'get shuffled or sequential ordered indices for batch construction from MaeFinetuningImageDataset'}
```

## File: facebookresearch_fairseq/examples/data2vec/data/mae_image_dataset.py

Prompts

```
['create an AddClassTargetDataset wrapper that adds class labels to a fairseq dataset for supervised training', 'use AddClassTargetDataset with multi_class mode to generate one-hot encoded label vectors for each sample', 'use AddClassTargetDataset in single-class mode to map labels via label_indices for classification tasks', 'review the AddClassTargetDataset collater method that stacks labels and optionally adds them to net_input', 'refactor AddClassTargetDataset to use label_indices for remapping raw labels to class indices', 'create an ImageDataset that loads image files from a root directory and auto-discovers class labels from subdirectories', 'create an ImageDataset that loads image files from a root directory without class labels for unsupervised learning', 'test the ImageDataset __getitem__ method to verify it returns a dictionary with image tensor and optional label', 'review the ImageDataset collater method that stacks sample images into batched tensors for model input', 'refactor the ImageDataset ordered_indices method to customize batch ordering with or without shuffling', 'build a training image transform with color jitter, auto augment, and random erasing for MAE finetuning', 'build an evaluation image transform with resize, center crop, and normalization for MAE finetuning', 'create a MaeFinetuningImageDataset from an ImageFolder path with caching and augmentation transforms', 'collate MaeFinetuningImageDataset samples into batched tensors with ids, images, and labels', 'get shuffled or sequential ordered indices for batch construction from MaeFinetuningImageDataset', 'create a MaeImageDataset from an ImageFolder root with configurable mask probability and patch size', 'use caching_loader to wrap a torchvision loader with a local cache directory for faster image loading', 'apply RandomResizedCropAndInterpolationWithTwoPic to crop and resize PIL images with random aspect ratio', 'compute a precomputed block mask for MAE image patches using compute_block_mask_1d or compute_block_mask_2d', 'collate MaeImageDataset samples into batched tensors with optional target and precomputed mask keys']
```

Usage

```
{'create_mae_image_dataset': 'create a MaeImageDataset from an ImageFolder root with configurable mask probability and patch size', 'use_caching_loader': 'use caching_loader to wrap a torchvision loader with a local cache directory for faster image loading', 'apply_random_resized_crop_transform': 'apply RandomResizedCropAndInterpolationWithTwoPic to crop and resize PIL images with random aspect ratio', 'compute_mae_mask': 'compute a precomputed block mask for MAE image patches using compute_block_mask_1d or compute_block_mask_2d', 'collate_mae_samples': 'collate MaeImageDataset samples into batched tensors with optional target and precomputed mask keys'}
```

