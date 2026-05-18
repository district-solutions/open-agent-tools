# Agent Python Tools

- repo: facebookresearch/omnimatterf
- repo_uri: https://github.com/facebookresearch/omnimatterf

## File: facebookresearch_omnimatterf/core/module/dummy.py

Prompts

```
['create a DummyModel instance that registers as both foreground and background model under the name dummy', 'review the DummyModel forward method which accepts a data dict and RenderContext but returns None', 'test the DummyModel constructor to verify it initializes a single trainable scalar parameter', 'refactor the DummyModel class to produce actual output instead of returning None from forward', 'summarize the DummyModel class registered via decorators as a no-op foreground and background model', 'build an OmnimatteModel instance with hidden channels, frame count, image dimensions, and feature mode config', 'review the OmnimatteModel forward pass that processes masks, flows, and features through the Omnimatte network', 'test the build_feature_cache method to pre-compute xyt positional encodings, zeros, or noise features', 'refactor the check_feature_cfg function to validate feature mode configuration for zeros, xyt, or noise modes', 'summarize the load_xyt_cache and save_xyt_cache functions that persist positional encoding tensors to disk', 'create a TensoRFModel instance with voxel grid, contraction mode, and ray marching parameters for background rendering', 'run the TensoRFModel forward pass to compute bg_rgb and bg_depths from camera rays and render context', 'create a SafeTVLoss module to compute total variation regularization loss on tensor fields', 'review the TensoRFModel post_training_step method that updates alpha mask and upsamples the volume grid', 'test the TensoRFModel load_state_dict and state_dict methods for saving and loading model checkpoints']
```

Usage

```
{'create_DummyModel': 'create a DummyModel instance that registers as both foreground and background model under the name dummy', 'review_DummyModel_forward': 'review the DummyModel forward method which accepts a data dict and RenderContext but returns None', 'test_DummyModel_init': 'test the DummyModel constructor to verify it initializes a single trainable scalar parameter', 'refactor_DummyModel': 'refactor the DummyModel class to produce actual output instead of returning None from forward', 'summarize_DummyModel': 'summarize the DummyModel class registered via decorators as a no-op foreground and background model'}
```

## File: facebookresearch_omnimatterf/core/module/omnimatte.py

Prompts

```
['create a DummyModel instance that registers as both foreground and background model under the name dummy', 'review the DummyModel forward method which accepts a data dict and RenderContext but returns None', 'test the DummyModel constructor to verify it initializes a single trainable scalar parameter', 'refactor the DummyModel class to produce actual output instead of returning None from forward', 'summarize the DummyModel class registered via decorators as a no-op foreground and background model', 'build an OmnimatteModel instance with hidden channels, frame count, image dimensions, and feature mode config', 'review the OmnimatteModel forward pass that processes masks, flows, and features through the Omnimatte network', 'test the build_feature_cache method to pre-compute xyt positional encodings, zeros, or noise features', 'refactor the check_feature_cfg function to validate feature mode configuration for zeros, xyt, or noise modes', 'summarize the load_xyt_cache and save_xyt_cache functions that persist positional encoding tensors to disk', 'create a TensoRFModel instance with voxel grid, contraction mode, and ray marching parameters for background rendering', 'run the TensoRFModel forward pass to compute bg_rgb and bg_depths from camera rays and render context', 'create a SafeTVLoss module to compute total variation regularization loss on tensor fields', 'review the TensoRFModel post_training_step method that updates alpha mask and upsamples the volume grid', 'test the TensoRFModel load_state_dict and state_dict methods for saving and loading model checkpoints']
```

Usage

```
{'build_OmnimatteModel': 'build an OmnimatteModel instance with hidden channels, frame count, image dimensions, and feature mode config', 'review_OmnimatteModel_forward': 'review the OmnimatteModel forward pass that processes masks, flows, and features through the Omnimatte network', 'test_build_feature_cache': 'test the build_feature_cache method to pre-compute xyt positional encodings, zeros, or noise features', 'refactor_check_feature_cfg': 'refactor the check_feature_cfg function to validate feature mode configuration for zeros, xyt, or noise modes', 'summarize_xyt_cache_functions': 'summarize the load_xyt_cache and save_xyt_cache functions that persist positional encoding tensors to disk'}
```

## File: facebookresearch_omnimatterf/core/module/tensorf.py

Prompts

```
['create a DummyModel instance that registers as both foreground and background model under the name dummy', 'review the DummyModel forward method which accepts a data dict and RenderContext but returns None', 'test the DummyModel constructor to verify it initializes a single trainable scalar parameter', 'refactor the DummyModel class to produce actual output instead of returning None from forward', 'summarize the DummyModel class registered via decorators as a no-op foreground and background model', 'build an OmnimatteModel instance with hidden channels, frame count, image dimensions, and feature mode config', 'review the OmnimatteModel forward pass that processes masks, flows, and features through the Omnimatte network', 'test the build_feature_cache method to pre-compute xyt positional encodings, zeros, or noise features', 'refactor the check_feature_cfg function to validate feature mode configuration for zeros, xyt, or noise modes', 'summarize the load_xyt_cache and save_xyt_cache functions that persist positional encoding tensors to disk', 'create a TensoRFModel instance with voxel grid, contraction mode, and ray marching parameters for background rendering', 'run the TensoRFModel forward pass to compute bg_rgb and bg_depths from camera rays and render context', 'create a SafeTVLoss module to compute total variation regularization loss on tensor fields', 'review the TensoRFModel post_training_step method that updates alpha mask and upsamples the volume grid', 'test the TensoRFModel load_state_dict and state_dict methods for saving and loading model checkpoints']
```

Usage

```
{'create_tensorf_model': 'create a TensoRFModel instance with voxel grid, contraction mode, and ray marching parameters for background rendering', 'run_tensorf_forward': 'run the TensoRFModel forward pass to compute bg_rgb and bg_depths from camera rays and render context', 'create_tvloss': 'create a SafeTVLoss module to compute total variation regularization loss on tensor fields', 'review_tensorf_upsample': 'review the TensoRFModel post_training_step method that updates alpha mask and upsamples the volume grid', 'test_tensorf_state_dict': 'test the TensoRFModel load_state_dict and state_dict methods for saving and loading model checkpoints'}
```

