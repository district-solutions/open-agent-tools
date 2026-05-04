# Agent Python Tools

- repo: facebookresearch/fillerbuster
- repo_uri: https://github.com/facebookresearch/fillerbuster

## File: facebookresearch_fillerbuster/fillerbuster/data/datamanager.py

Prompts

```
['create a FillerbusterDataManagerConfig with custom train_stride eval_stride and patch_size values', 'build a FillerbusterDataManager instance with a config object and target device for training', 'review the setup_train method to understand how MultiViewDatasetConfig is initialized for training data', 'review the setup_eval method to understand how MultiViewDatasetConfig is initialized for validation data', 'test the next_train method to verify it returns ray bundles and batches from the training dataset', 'create a PatchPixelSamplerConfig dataclass with patch_size, force_one_patch_per_image, force_fixed_location, and force_center_crop settings', 'instantiate a PatchPixelSampler with a PatchPixelSamplerConfig to sample square patches from image batches', 'call set_num_rays_per_batch on PatchPixelSampler to align ray count to patch size multiples', 'call sample_method on PatchPixelSampler to sample pixel indices from images with optional mask and device', 'review the PatchPixelSampler sample_method to understand mask-based and random patch sampling logic']
```

Usage

```
{'create_FillerbusterDataManagerConfig': 'create a FillerbusterDataManagerConfig with custom train_stride eval_stride and patch_size values', 'build_FillerbusterDataManager': 'build a FillerbusterDataManager instance with a config object and target device for training', 'review_setup_train': 'review the setup_train method to understand how MultiViewDatasetConfig is initialized for training data', 'review_setup_eval': 'review the setup_eval method to understand how MultiViewDatasetConfig is initialized for validation data', 'test_next_train': 'test the next_train method to verify it returns ray bundles and batches from the training dataset'}
```

## File: facebookresearch_fillerbuster/fillerbuster/data/pixel_samplers.py

Prompts

```
['create a FillerbusterDataManagerConfig with custom train_stride eval_stride and patch_size values', 'build a FillerbusterDataManager instance with a config object and target device for training', 'review the setup_train method to understand how MultiViewDatasetConfig is initialized for training data', 'review the setup_eval method to understand how MultiViewDatasetConfig is initialized for validation data', 'test the next_train method to verify it returns ray bundles and batches from the training dataset', 'create a PatchPixelSamplerConfig dataclass with patch_size, force_one_patch_per_image, force_fixed_location, and force_center_crop settings', 'instantiate a PatchPixelSampler with a PatchPixelSamplerConfig to sample square patches from image batches', 'call set_num_rays_per_batch on PatchPixelSampler to align ray count to patch size multiples', 'call sample_method on PatchPixelSampler to sample pixel indices from images with optional mask and device', 'review the PatchPixelSampler sample_method to understand mask-based and random patch sampling logic']
```

Usage

```
{'create_PatchPixelSamplerConfig': 'create a PatchPixelSamplerConfig dataclass with patch_size, force_one_patch_per_image, force_fixed_location, and force_center_crop settings', 'instantiate_PatchPixelSampler': 'instantiate a PatchPixelSampler with a PatchPixelSamplerConfig to sample square patches from image batches', 'call_set_num_rays_per_batch': 'call set_num_rays_per_batch on PatchPixelSampler to align ray count to patch size multiples', 'call_sample_method': 'call sample_method on PatchPixelSampler to sample pixel indices from images with optional mask and device', 'review_PatchPixelSampler_sample_method': 'review the PatchPixelSampler sample_method to understand mask-based and random patch sampling logic'}
```

