# Agent Python Tools

- repo: facebookresearch/fast3r
- repo_uri: https://github.com/facebookresearch/fast3r

## File: facebookresearch_fast3r/fast3r/dust3r/datasets/base/base_stereo_view_dataset.py

Prompts

```
['create a custom stereo view dataset by subclassing BaseStereoViewDataset and implementing _get_views to return image pairs with depthmaps and camera intrinsics', 'use _crop_resize_if_necessary to downscale images with Lanczos interpolation, crop centered on principal point, and rescale to target resolution', 'use is_good_type to validate that dataset view values have acceptable dtypes like np.float32, torch.float32, bool, np.int32, np.int64, or np.uint8', 'use view_name to generate a formatted string identifying a view by its dataset, label, and instance fields with optional batch index support', 'use transpose_to_landscape to swap height and width axes on portrait images, depthmaps, pts3d, valid masks, and camera intrinsics', 'create a BatchedRandomSampler that yields tuples of sample and feature indices for each batch', 'use BatchedRandomSampler with a dataset to ensure each batch shares the same randomly chosen feature', 'set the epoch on a BatchedRandomSampler instance to control random seed for reproducibility', 'iterate over a BatchedRandomSampler to get (sample_idx, feat_idx) tuples aligned by batch size', 'round a number down to the nearest multiple using the round_by helper function', 'create a BatchedRandomSampler for an EasyDataset with specified batch size and world size for distributed training', 'duplicate each item in a dataset N times using the rmul operator to artificially augment dataset size', 'resize a dataset to a target size using the rmatmul operator with random sampling and epoch-based shuffling', 'concatenate multiple EasyDataset instances together using the add operator to create a combined CatDataset', 'set the epoch on a ResizedDataset or CatDataset to trigger epoch-dependent random shuffling of indices']
```

Usage

```
{'create_stereo_dataset': 'create a custom stereo view dataset by subclassing BaseStereoViewDataset and implementing _get_views to return image pairs with depthmaps and camera intrinsics', 'crop_resize_views': 'use _crop_resize_if_necessary to downscale images with Lanczos interpolation, crop centered on principal point, and rescale to target resolution', 'validate_view_types': 'use is_good_type to validate that dataset view values have acceptable dtypes like np.float32, torch.float32, bool, np.int32, np.int64, or np.uint8', 'get_view_name': 'use view_name to generate a formatted string identifying a view by its dataset, label, and instance fields with optional batch index support', 'transpose_portrait_to_landscape': 'use transpose_to_landscape to swap height and width axes on portrait images, depthmaps, pts3d, valid masks, and camera intrinsics'}
```

## File: facebookresearch_fast3r/fast3r/dust3r/datasets/base/batched_sampler.py

Prompts

```
['create a custom stereo view dataset by subclassing BaseStereoViewDataset and implementing _get_views to return image pairs with depthmaps and camera intrinsics', 'use _crop_resize_if_necessary to downscale images with Lanczos interpolation, crop centered on principal point, and rescale to target resolution', 'use is_good_type to validate that dataset view values have acceptable dtypes like np.float32, torch.float32, bool, np.int32, np.int64, or np.uint8', 'use view_name to generate a formatted string identifying a view by its dataset, label, and instance fields with optional batch index support', 'use transpose_to_landscape to swap height and width axes on portrait images, depthmaps, pts3d, valid masks, and camera intrinsics', 'create a BatchedRandomSampler that yields tuples of sample and feature indices for each batch', 'use BatchedRandomSampler with a dataset to ensure each batch shares the same randomly chosen feature', 'set the epoch on a BatchedRandomSampler instance to control random seed for reproducibility', 'iterate over a BatchedRandomSampler to get (sample_idx, feat_idx) tuples aligned by batch size', 'round a number down to the nearest multiple using the round_by helper function', 'create a BatchedRandomSampler for an EasyDataset with specified batch size and world size for distributed training', 'duplicate each item in a dataset N times using the rmul operator to artificially augment dataset size', 'resize a dataset to a target size using the rmatmul operator with random sampling and epoch-based shuffling', 'concatenate multiple EasyDataset instances together using the add operator to create a combined CatDataset', 'set the epoch on a ResizedDataset or CatDataset to trigger epoch-dependent random shuffling of indices']
```

Usage

```
{'create_batched_random_sampler': 'create a BatchedRandomSampler that yields tuples of sample and feature indices for each batch', 'use_sampler_with_dataset': 'use BatchedRandomSampler with a dataset to ensure each batch shares the same randomly chosen feature', 'set_epoch_for_sampler': 'set the epoch on a BatchedRandomSampler instance to control random seed for reproducibility', 'iterate_sampler_indices': 'iterate over a BatchedRandomSampler to get (sample_idx, feat_idx) tuples aligned by batch size', 'round_by_multiple': 'round a number down to the nearest multiple using the round_by helper function'}
```

## File: facebookresearch_fast3r/fast3r/dust3r/datasets/base/easy_dataset.py

Prompts

```
['create a custom stereo view dataset by subclassing BaseStereoViewDataset and implementing _get_views to return image pairs with depthmaps and camera intrinsics', 'use _crop_resize_if_necessary to downscale images with Lanczos interpolation, crop centered on principal point, and rescale to target resolution', 'use is_good_type to validate that dataset view values have acceptable dtypes like np.float32, torch.float32, bool, np.int32, np.int64, or np.uint8', 'use view_name to generate a formatted string identifying a view by its dataset, label, and instance fields with optional batch index support', 'use transpose_to_landscape to swap height and width axes on portrait images, depthmaps, pts3d, valid masks, and camera intrinsics', 'create a BatchedRandomSampler that yields tuples of sample and feature indices for each batch', 'use BatchedRandomSampler with a dataset to ensure each batch shares the same randomly chosen feature', 'set the epoch on a BatchedRandomSampler instance to control random seed for reproducibility', 'iterate over a BatchedRandomSampler to get (sample_idx, feat_idx) tuples aligned by batch size', 'round a number down to the nearest multiple using the round_by helper function', 'create a BatchedRandomSampler for an EasyDataset with specified batch size and world size for distributed training', 'duplicate each item in a dataset N times using the rmul operator to artificially augment dataset size', 'resize a dataset to a target size using the rmatmul operator with random sampling and epoch-based shuffling', 'concatenate multiple EasyDataset instances together using the add operator to create a combined CatDataset', 'set the epoch on a ResizedDataset or CatDataset to trigger epoch-dependent random shuffling of indices']
```

Usage

```
{'create_dataset_sampler': 'create a BatchedRandomSampler for an EasyDataset with specified batch size and world size for distributed training', 'duplicate_dataset_items': 'duplicate each item in a dataset N times using the rmul operator to artificially augment dataset size', 'resize_dataset_randomly': 'resize a dataset to a target size using the rmatmul operator with random sampling and epoch-based shuffling', 'concatenate_datasets': 'concatenate multiple EasyDataset instances together using the add operator to create a combined CatDataset', 'set_dataset_epoch': 'set the epoch on a ResizedDataset or CatDataset to trigger epoch-dependent random shuffling of indices'}
```

