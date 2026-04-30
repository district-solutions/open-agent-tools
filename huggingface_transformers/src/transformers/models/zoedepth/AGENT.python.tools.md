# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/zoedepth/convert_zoedepth_to_hf.py

Prompts

```
['convert a ZoeDepth checkpoint from the original repository to HuggingFace format', 'get the ZoeDepth configuration for a given model name like ZoeD_N, ZoeD_K, or ZoeD_NK', 'rename state dict keys from the original ZoeDepth repository to HuggingFace Transformers naming convention', 'split the original qkv projection matrices into separate query, key, and value weights for the backbone encoder', 'split the metric head qkv projection matrices into separate query, key, and value weights for the patch transformer', 'create a ZoeDepthImageProcessorPil instance with custom size, keep_aspect_ratio, and ensure_multiple_of settings', 'build a resize operation that preserves aspect ratio and snaps dimensions to multiples of 32 for ZoeDepth input', 'run padding on a numpy image using reflect mode with computed pad dimensions based on image height and width', 'test the preprocess pipeline that rescales, pads, resizes, and normalizes images for ZoeDepth depth estimation', 'summarize post_process_depth_estimation that converts raw ZoeDepthDepthEstimatorOutput into final depth predictions with padding removal and resizing', 'build image preprocessing pipeline with resize, pad, rescale, and normalize for ZoeDepth input', 'run image resizing with aspect ratio preservation and multiple-of constraints for ZoeDepth', 'test image padding with reflect mode to fix boundary artifacts in ZoeDepth depth maps', 'run ZoeDepthForDepthEstimation model on input pixel values to predict depth maps', 'create ZoeDepthDepthEstimatorOutput dataclass with predicted depth and domain logits', 'build ZoeDepthNeck to fuse backbone hidden states into multi-resolution feature maps', 'test ZoeDepthMultipleMetricDepthEstimationHeads for multi-domain depth estimation routing', 'review ZoeDepthMetricDepthEstimationHead single metric head forward pass logic']
```

Usage

```
{'convert_zoedepth_checkpoint': 'convert a ZoeDepth checkpoint from the original repository to HuggingFace format', 'get_zoedepth_config': 'get the ZoeDepth configuration for a given model name like ZoeD_N, ZoeD_K, or ZoeD_NK', 'rename_key': 'rename state dict keys from the original ZoeDepth repository to HuggingFace Transformers naming convention', 'read_in_q_k_v': 'split the original qkv projection matrices into separate query, key, and value weights for the backbone encoder', 'read_in_q_k_v_metric_head': 'split the metric head qkv projection matrices into separate query, key, and value weights for the patch transformer'}
```

## File: huggingface_transformers/src/transformers/models/zoedepth/image_processing_pil_zoedepth.py

Prompts

```
['convert a ZoeDepth checkpoint from the original repository to HuggingFace format', 'get the ZoeDepth configuration for a given model name like ZoeD_N, ZoeD_K, or ZoeD_NK', 'rename state dict keys from the original ZoeDepth repository to HuggingFace Transformers naming convention', 'split the original qkv projection matrices into separate query, key, and value weights for the backbone encoder', 'split the metric head qkv projection matrices into separate query, key, and value weights for the patch transformer', 'create a ZoeDepthImageProcessorPil instance with custom size, keep_aspect_ratio, and ensure_multiple_of settings', 'build a resize operation that preserves aspect ratio and snaps dimensions to multiples of 32 for ZoeDepth input', 'run padding on a numpy image using reflect mode with computed pad dimensions based on image height and width', 'test the preprocess pipeline that rescales, pads, resizes, and normalizes images for ZoeDepth depth estimation', 'summarize post_process_depth_estimation that converts raw ZoeDepthDepthEstimatorOutput into final depth predictions with padding removal and resizing', 'build image preprocessing pipeline with resize, pad, rescale, and normalize for ZoeDepth input', 'run image resizing with aspect ratio preservation and multiple-of constraints for ZoeDepth', 'test image padding with reflect mode to fix boundary artifacts in ZoeDepth depth maps', 'run ZoeDepthForDepthEstimation model on input pixel values to predict depth maps', 'create ZoeDepthDepthEstimatorOutput dataclass with predicted depth and domain logits', 'build ZoeDepthNeck to fuse backbone hidden states into multi-resolution feature maps', 'test ZoeDepthMultipleMetricDepthEstimationHeads for multi-domain depth estimation routing', 'review ZoeDepthMetricDepthEstimationHead single metric head forward pass logic']
```

Usage

```
{'create_zoedepth_image_processor': 'create a ZoeDepthImageProcessorPil instance with custom size, keep_aspect_ratio, and ensure_multiple_of settings', 'build_resize_image': 'build a resize operation that preserves aspect ratio and snaps dimensions to multiples of 32 for ZoeDepth input', 'run_pad_image': 'run padding on a numpy image using reflect mode with computed pad dimensions based on image height and width', 'test_preprocess_pipeline': 'test the preprocess pipeline that rescales, pads, resizes, and normalizes images for ZoeDepth depth estimation', 'summarize_post_process_depth': 'summarize post_process_depth_estimation that converts raw ZoeDepthDepthEstimatorOutput into final depth predictions with padding removal and resizing'}
```

## File: huggingface_transformers/src/transformers/models/zoedepth/image_processing_zoedepth.py

Prompts

```
['convert a ZoeDepth checkpoint from the original repository to HuggingFace format', 'get the ZoeDepth configuration for a given model name like ZoeD_N, ZoeD_K, or ZoeD_NK', 'rename state dict keys from the original ZoeDepth repository to HuggingFace Transformers naming convention', 'split the original qkv projection matrices into separate query, key, and value weights for the backbone encoder', 'split the metric head qkv projection matrices into separate query, key, and value weights for the patch transformer', 'create a ZoeDepthImageProcessorPil instance with custom size, keep_aspect_ratio, and ensure_multiple_of settings', 'build a resize operation that preserves aspect ratio and snaps dimensions to multiples of 32 for ZoeDepth input', 'run padding on a numpy image using reflect mode with computed pad dimensions based on image height and width', 'test the preprocess pipeline that rescales, pads, resizes, and normalizes images for ZoeDepth depth estimation', 'summarize post_process_depth_estimation that converts raw ZoeDepthDepthEstimatorOutput into final depth predictions with padding removal and resizing', 'build image preprocessing pipeline with resize, pad, rescale, and normalize for ZoeDepth input', 'run image resizing with aspect ratio preservation and multiple-of constraints for ZoeDepth', 'test image padding with reflect mode to fix boundary artifacts in ZoeDepth depth maps', 'run ZoeDepthForDepthEstimation model on input pixel values to predict depth maps', 'create ZoeDepthDepthEstimatorOutput dataclass with predicted depth and domain logits', 'build ZoeDepthNeck to fuse backbone hidden states into multi-resolution feature maps', 'test ZoeDepthMultipleMetricDepthEstimationHeads for multi-domain depth estimation routing', 'review ZoeDepthMetricDepthEstimationHead single metric head forward pass logic']
```

Usage

```
{'create_zoedepth_image_processor': 'create a ZoeDepthImageProcessor instance for preprocessing images for depth estimation', 'build_preprocess_images': 'build image preprocessing pipeline with resize, pad, rescale, and normalize for ZoeDepth input', 'run_resize_images': 'run image resizing with aspect ratio preservation and multiple-of constraints for ZoeDepth', 'test_pad_images': 'test image padding with reflect mode to fix boundary artifacts in ZoeDepth depth maps', 'summarize_post_process_depth': 'summarize post-processing of ZoeDepth depth estimation outputs with flipped averaging and padding removal'}
```

## File: huggingface_transformers/src/transformers/models/zoedepth/modeling_zoedepth.py

Prompts

```
['convert a ZoeDepth checkpoint from the original repository to HuggingFace format', 'get the ZoeDepth configuration for a given model name like ZoeD_N, ZoeD_K, or ZoeD_NK', 'rename state dict keys from the original ZoeDepth repository to HuggingFace Transformers naming convention', 'split the original qkv projection matrices into separate query, key, and value weights for the backbone encoder', 'split the metric head qkv projection matrices into separate query, key, and value weights for the patch transformer', 'create a ZoeDepthImageProcessorPil instance with custom size, keep_aspect_ratio, and ensure_multiple_of settings', 'build a resize operation that preserves aspect ratio and snaps dimensions to multiples of 32 for ZoeDepth input', 'run padding on a numpy image using reflect mode with computed pad dimensions based on image height and width', 'test the preprocess pipeline that rescales, pads, resizes, and normalizes images for ZoeDepth depth estimation', 'summarize post_process_depth_estimation that converts raw ZoeDepthDepthEstimatorOutput into final depth predictions with padding removal and resizing', 'build image preprocessing pipeline with resize, pad, rescale, and normalize for ZoeDepth input', 'run image resizing with aspect ratio preservation and multiple-of constraints for ZoeDepth', 'test image padding with reflect mode to fix boundary artifacts in ZoeDepth depth maps', 'run ZoeDepthForDepthEstimation model on input pixel values to predict depth maps', 'create ZoeDepthDepthEstimatorOutput dataclass with predicted depth and domain logits', 'build ZoeDepthNeck to fuse backbone hidden states into multi-resolution feature maps', 'test ZoeDepthMultipleMetricDepthEstimationHeads for multi-domain depth estimation routing', 'review ZoeDepthMetricDepthEstimationHead single metric head forward pass logic']
```

Usage

```
{'run_ZoeDepthForDepthEstimation': 'run ZoeDepthForDepthEstimation model on input pixel values to predict depth maps', 'create_ZoeDepthDepthEstimatorOutput': 'create ZoeDepthDepthEstimatorOutput dataclass with predicted depth and domain logits', 'build_ZoeDepthNeck': 'build ZoeDepthNeck to fuse backbone hidden states into multi-resolution feature maps', 'test_ZoeDepthMultipleMetricDepthEstimationHeads': 'test ZoeDepthMultipleMetricDepthEstimationHeads for multi-domain depth estimation routing', 'review_ZoeDepthMetricDepthEstimationHead': 'review ZoeDepthMetricDepthEstimationHead single metric head forward pass logic'}
```

