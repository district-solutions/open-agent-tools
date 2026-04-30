# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/depth_pro/configuration_depth_pro.py

Prompts

```
['create a DepthProConfig instance with default Apple DepthPro model settings', 'configure DepthProConfig fusion_hidden_size and num_fov_head_layers for custom model architecture', 'initialize DepthProConfig sub_configs with Dinov2 image, patch, and fov model configurations', 'validate DepthProConfig architecture consistency of ratios, dims, and layer parameters', 'review DepthProConfig default values for patch_size, intermediate_hook_ids, and scaled_images_ratios', "run the DepthPro weight converter CLI to convert Apple's DepthPro model weights to HuggingFace format", "build a converted DepthPro model from Apple's official checkpoint and save it with config and image processor", 'convert old state dict keys to new HuggingFace-style keys using the regex-based mapping table', 'split combined QKV weight tensors into separate query, key, and value parameter tensors', 'save the DepthProFastImageProcessor to the output directory for inference use', 'create a DepthProImageProcessor instance for preprocessing images with rescale, normalize, and resize', 'run the _preprocess method on a list of torch tensors to rescale, normalize, and resize images grouped by shape', 'run post_process_depth_estimation to convert raw depth predictions with field of view into scaled depth maps', 'test the _preprocess method with batched torch tensor images and verify grouped-by-shape rescale-normalize-then-resize output', 'review the post_process_depth_estimation method that scales depth predictions by focal length and interpolates to target sizes', 'run DepthProForDepthEstimation to predict depth maps from input images with optional field-of-view estimation', 'create a DepthProModel that encodes images using patch and image encoders with multi-scale feature fusion', 'build a DepthProFeatureFusionStage that fuses multi-scale features using pre-activated residual layers and deconvolution', 'estimate field-of-view from input images using DepthProFovModel with encoder features and a convolutional head', 'reconstruct 2D feature maps from transformer hidden states by reshaping, merging patches, and interpolating to target size']
```

Usage

```
{'create_DepthProConfig': 'create a DepthProConfig instance with default Apple DepthPro model settings', 'configure_DepthProConfig_fusion': 'configure DepthProConfig fusion_hidden_size and num_fov_head_layers for custom model architecture', 'initialize_sub_configs_Dinov2': 'initialize DepthProConfig sub_configs with Dinov2 image, patch, and fov model configurations', 'validate_DepthProConfig_architecture': 'validate DepthProConfig architecture consistency of ratios, dims, and layer parameters', 'review_DepthProConfig_defaults': 'review DepthProConfig default values for patch_size, intermediate_hook_ids, and scaled_images_ratios'}
```

## File: huggingface_transformers/src/transformers/models/depth_pro/convert_depth_pro_weights_to_hf.py

Prompts

```
['create a DepthProConfig instance with default Apple DepthPro model settings', 'configure DepthProConfig fusion_hidden_size and num_fov_head_layers for custom model architecture', 'initialize DepthProConfig sub_configs with Dinov2 image, patch, and fov model configurations', 'validate DepthProConfig architecture consistency of ratios, dims, and layer parameters', 'review DepthProConfig default values for patch_size, intermediate_hook_ids, and scaled_images_ratios', "run the DepthPro weight converter CLI to convert Apple's DepthPro model weights to HuggingFace format", "build a converted DepthPro model from Apple's official checkpoint and save it with config and image processor", 'convert old state dict keys to new HuggingFace-style keys using the regex-based mapping table', 'split combined QKV weight tensors into separate query, key, and value parameter tensors', 'save the DepthProFastImageProcessor to the output directory for inference use', 'create a DepthProImageProcessor instance for preprocessing images with rescale, normalize, and resize', 'run the _preprocess method on a list of torch tensors to rescale, normalize, and resize images grouped by shape', 'run post_process_depth_estimation to convert raw depth predictions with field of view into scaled depth maps', 'test the _preprocess method with batched torch tensor images and verify grouped-by-shape rescale-normalize-then-resize output', 'review the post_process_depth_estimation method that scales depth predictions by focal length and interpolates to target sizes', 'run DepthProForDepthEstimation to predict depth maps from input images with optional field-of-view estimation', 'create a DepthProModel that encodes images using patch and image encoders with multi-scale feature fusion', 'build a DepthProFeatureFusionStage that fuses multi-scale features using pre-activated residual layers and deconvolution', 'estimate field-of-view from input images using DepthProFovModel with encoder features and a convolutional head', 'reconstruct 2D feature maps from transformer hidden states by reshaping, merging patches, and interpolating to target size']
```

Usage

```
{'run_convert_depth_pro_weights_cli': "run the DepthPro weight converter CLI to convert Apple's DepthPro model weights to HuggingFace format", 'build_convert_depth_pro_model': "build a converted DepthPro model from Apple's official checkpoint and save it with config and image processor", 'convert_state_dict_keys': 'convert old state dict keys to new HuggingFace-style keys using the regex-based mapping table', 'split_qkv_parameters': 'split combined QKV weight tensors into separate query, key, and value parameter tensors', 'save_depth_pro_image_processor': 'save the DepthProFastImageProcessor to the output directory for inference use'}
```

## File: huggingface_transformers/src/transformers/models/depth_pro/image_processing_depth_pro.py

Prompts

```
['create a DepthProConfig instance with default Apple DepthPro model settings', 'configure DepthProConfig fusion_hidden_size and num_fov_head_layers for custom model architecture', 'initialize DepthProConfig sub_configs with Dinov2 image, patch, and fov model configurations', 'validate DepthProConfig architecture consistency of ratios, dims, and layer parameters', 'review DepthProConfig default values for patch_size, intermediate_hook_ids, and scaled_images_ratios', "run the DepthPro weight converter CLI to convert Apple's DepthPro model weights to HuggingFace format", "build a converted DepthPro model from Apple's official checkpoint and save it with config and image processor", 'convert old state dict keys to new HuggingFace-style keys using the regex-based mapping table', 'split combined QKV weight tensors into separate query, key, and value parameter tensors', 'save the DepthProFastImageProcessor to the output directory for inference use', 'create a DepthProImageProcessor instance for preprocessing images with rescale, normalize, and resize', 'run the _preprocess method on a list of torch tensors to rescale, normalize, and resize images grouped by shape', 'run post_process_depth_estimation to convert raw depth predictions with field of view into scaled depth maps', 'test the _preprocess method with batched torch tensor images and verify grouped-by-shape rescale-normalize-then-resize output', 'review the post_process_depth_estimation method that scales depth predictions by focal length and interpolates to target sizes', 'run DepthProForDepthEstimation to predict depth maps from input images with optional field-of-view estimation', 'create a DepthProModel that encodes images using patch and image encoders with multi-scale feature fusion', 'build a DepthProFeatureFusionStage that fuses multi-scale features using pre-activated residual layers and deconvolution', 'estimate field-of-view from input images using DepthProFovModel with encoder features and a convolutional head', 'reconstruct 2D feature maps from transformer hidden states by reshaping, merging patches, and interpolating to target size']
```

Usage

```
{'create_DepthProImageProcessor': 'create a DepthProImageProcessor instance for preprocessing images with rescale, normalize, and resize', 'run_DepthProImageProcessor__preprocess': 'run the _preprocess method on a list of torch tensors to rescale, normalize, and resize images grouped by shape', 'run_DepthProImageProcessor_post_process_depth_estimation': 'run post_process_depth_estimation to convert raw depth predictions with field of view into scaled depth maps', 'test_DepthProImageProcessor__preprocess': 'test the _preprocess method with batched torch tensor images and verify grouped-by-shape rescale-normalize-then-resize output', 'review_DepthProImageProcessor_post_process_depth_estimation': 'review the post_process_depth_estimation method that scales depth predictions by focal length and interpolates to target sizes'}
```

## File: huggingface_transformers/src/transformers/models/depth_pro/modeling_depth_pro.py

Prompts

```
['create a DepthProConfig instance with default Apple DepthPro model settings', 'configure DepthProConfig fusion_hidden_size and num_fov_head_layers for custom model architecture', 'initialize DepthProConfig sub_configs with Dinov2 image, patch, and fov model configurations', 'validate DepthProConfig architecture consistency of ratios, dims, and layer parameters', 'review DepthProConfig default values for patch_size, intermediate_hook_ids, and scaled_images_ratios', "run the DepthPro weight converter CLI to convert Apple's DepthPro model weights to HuggingFace format", "build a converted DepthPro model from Apple's official checkpoint and save it with config and image processor", 'convert old state dict keys to new HuggingFace-style keys using the regex-based mapping table', 'split combined QKV weight tensors into separate query, key, and value parameter tensors', 'save the DepthProFastImageProcessor to the output directory for inference use', 'create a DepthProImageProcessor instance for preprocessing images with rescale, normalize, and resize', 'run the _preprocess method on a list of torch tensors to rescale, normalize, and resize images grouped by shape', 'run post_process_depth_estimation to convert raw depth predictions with field of view into scaled depth maps', 'test the _preprocess method with batched torch tensor images and verify grouped-by-shape rescale-normalize-then-resize output', 'review the post_process_depth_estimation method that scales depth predictions by focal length and interpolates to target sizes', 'run DepthProForDepthEstimation to predict depth maps from input images with optional field-of-view estimation', 'create a DepthProModel that encodes images using patch and image encoders with multi-scale feature fusion', 'build a DepthProFeatureFusionStage that fuses multi-scale features using pre-activated residual layers and deconvolution', 'estimate field-of-view from input images using DepthProFovModel with encoder features and a convolutional head', 'reconstruct 2D feature maps from transformer hidden states by reshaping, merging patches, and interpolating to target size']
```

Usage

```
{'run_depth_pro_depth_estimation': 'run DepthProForDepthEstimation to predict depth maps from input images with optional field-of-view estimation', 'create_depth_pro_model': 'create a DepthProModel that encodes images using patch and image encoders with multi-scale feature fusion', 'build_feature_fusion_stage': 'build a DepthProFeatureFusionStage that fuses multi-scale features using pre-activated residual layers and deconvolution', 'estimate_field_of_view': 'estimate field-of-view from input images using DepthProFovModel with encoder features and a convolutional head', 'reconstruct_feature_maps': 'reconstruct 2D feature maps from transformer hidden states by reshaping, merging patches, and interpolating to target size'}
```

