# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/chmv2/convert_chmv2_to_hf.py

Prompts

```
['convert a CHMv2 checkpoint to HuggingFace format with optional backbone and verification', 'create a CHMv2Config with DINOv3 backbone and depth estimation parameters', 'convert CHMv2 head state dict keys to HuggingFace naming convention via regex mapping', 'convert DINOv3 backbone state dict keys to HuggingFace format with qkv splitting', 'load a PyTorch checkpoint handling model or state_dict wrapper keys', 'create a CHMv2ImageProcessor instance for preprocessing images and segmentation maps for the CHMV2 model', 'run preprocess on input images and optional segmentation maps to produce pixel values and labels tensors', 'run reduce_label to shift segmentation map labels by 1, replacing background 0 with 255', 'test resize on a torch tensor image to a target size with aspect ratio preservation and size divisor alignment', 'review post_process_depth_estimation to convert raw DepthEstimatorOutput into final depth prediction tensors resized to target sizes', 'create a CHMv2ForDepthEstimation model with a depth estimation head for canopy height estimation', 'run the CHMv2ForDepthEstimation forward pass to predict depth maps from input pixel values', 'build a CHMv2ReassembleStage that processes backbone hidden states into multi-resolution feature representations', 'build a CHMv2FeatureFusionLayer that fuses multi-scale features with residual connections and upsampling', 'run CHMv2FeaturesToDepth to convert head logits into depth maps using configurable bin and normalization strategies', 'build a CHMv2ForDepthEstimation model from a CHMv2Config for canopy height estimation', 'run CHMv2ForDepthEstimation forward pass on pixel_values to produce predicted_depth output', 'process CHMv2ForDepthEstimation DepthEstimatorOutput with CHMv2ImageProcessor post_process_depth_estimation', 'convert CHMv2 head logits to depth values using CHMv2FeaturesToDepth with mixlog bins strategy']
```

Usage

```
{'convert_chmv2_checkpoint': 'convert a CHMv2 checkpoint to HuggingFace format with optional backbone and verification', 'create_chmv2_config': 'create a CHMv2Config with DINOv3 backbone and depth estimation parameters', 'convert_head_keys': 'convert CHMv2 head state dict keys to HuggingFace naming convention via regex mapping', 'convert_backbone_keys': 'convert DINOv3 backbone state dict keys to HuggingFace format with qkv splitting', 'load_original_state_dict': 'load a PyTorch checkpoint handling model or state_dict wrapper keys'}
```

## File: huggingface_transformers/src/transformers/models/chmv2/image_processing_chmv2.py

Prompts

```
['convert a CHMv2 checkpoint to HuggingFace format with optional backbone and verification', 'create a CHMv2Config with DINOv3 backbone and depth estimation parameters', 'convert CHMv2 head state dict keys to HuggingFace naming convention via regex mapping', 'convert DINOv3 backbone state dict keys to HuggingFace format with qkv splitting', 'load a PyTorch checkpoint handling model or state_dict wrapper keys', 'create a CHMv2ImageProcessor instance for preprocessing images and segmentation maps for the CHMV2 model', 'run preprocess on input images and optional segmentation maps to produce pixel values and labels tensors', 'run reduce_label to shift segmentation map labels by 1, replacing background 0 with 255', 'test resize on a torch tensor image to a target size with aspect ratio preservation and size divisor alignment', 'review post_process_depth_estimation to convert raw DepthEstimatorOutput into final depth prediction tensors resized to target sizes', 'create a CHMv2ForDepthEstimation model with a depth estimation head for canopy height estimation', 'run the CHMv2ForDepthEstimation forward pass to predict depth maps from input pixel values', 'build a CHMv2ReassembleStage that processes backbone hidden states into multi-resolution feature representations', 'build a CHMv2FeatureFusionLayer that fuses multi-scale features with residual connections and upsampling', 'run CHMv2FeaturesToDepth to convert head logits into depth maps using configurable bin and normalization strategies', 'build a CHMv2ForDepthEstimation model from a CHMv2Config for canopy height estimation', 'run CHMv2ForDepthEstimation forward pass on pixel_values to produce predicted_depth output', 'process CHMv2ForDepthEstimation DepthEstimatorOutput with CHMv2ImageProcessor post_process_depth_estimation', 'convert CHMv2 head logits to depth values using CHMv2FeaturesToDepth with mixlog bins strategy']
```

Usage

```
{'create_CHMv2ImageProcessor': 'create a CHMv2ImageProcessor instance for preprocessing images and segmentation maps for the CHMV2 model', 'run_preprocess_images': 'run preprocess on input images and optional segmentation maps to produce pixel values and labels tensors', 'run_reduce_label': 'run reduce_label to shift segmentation map labels by 1, replacing background 0 with 255', 'test_resize_image': 'test resize on a torch tensor image to a target size with aspect ratio preservation and size divisor alignment', 'review_post_process_depth_estimation': 'review post_process_depth_estimation to convert raw DepthEstimatorOutput into final depth prediction tensors resized to target sizes'}
```

## File: huggingface_transformers/src/transformers/models/chmv2/modeling_chmv2.py

Prompts

```
['convert a CHMv2 checkpoint to HuggingFace format with optional backbone and verification', 'create a CHMv2Config with DINOv3 backbone and depth estimation parameters', 'convert CHMv2 head state dict keys to HuggingFace naming convention via regex mapping', 'convert DINOv3 backbone state dict keys to HuggingFace format with qkv splitting', 'load a PyTorch checkpoint handling model or state_dict wrapper keys', 'create a CHMv2ImageProcessor instance for preprocessing images and segmentation maps for the CHMV2 model', 'run preprocess on input images and optional segmentation maps to produce pixel values and labels tensors', 'run reduce_label to shift segmentation map labels by 1, replacing background 0 with 255', 'test resize on a torch tensor image to a target size with aspect ratio preservation and size divisor alignment', 'review post_process_depth_estimation to convert raw DepthEstimatorOutput into final depth prediction tensors resized to target sizes', 'create a CHMv2ForDepthEstimation model with a depth estimation head for canopy height estimation', 'run the CHMv2ForDepthEstimation forward pass to predict depth maps from input pixel values', 'build a CHMv2ReassembleStage that processes backbone hidden states into multi-resolution feature representations', 'build a CHMv2FeatureFusionLayer that fuses multi-scale features with residual connections and upsampling', 'run CHMv2FeaturesToDepth to convert head logits into depth maps using configurable bin and normalization strategies', 'build a CHMv2ForDepthEstimation model from a CHMv2Config for canopy height estimation', 'run CHMv2ForDepthEstimation forward pass on pixel_values to produce predicted_depth output', 'process CHMv2ForDepthEstimation DepthEstimatorOutput with CHMv2ImageProcessor post_process_depth_estimation', 'convert CHMv2 head logits to depth values using CHMv2FeaturesToDepth with mixlog bins strategy']
```

Usage

```
{'create_model_CHMv2ForDepthEstimation': 'create a CHMv2ForDepthEstimation model with a depth estimation head for canopy height estimation', 'run_forward_CHMv2ForDepthEstimation': 'run the CHMv2ForDepthEstimation forward pass to predict depth maps from input pixel values', 'build_reassemble_stage': 'build a CHMv2ReassembleStage that processes backbone hidden states into multi-resolution feature representations', 'build_feature_fusion_layer': 'build a CHMv2FeatureFusionLayer that fuses multi-scale features with residual connections and upsampling', 'run_depth_conversion': 'run CHMv2FeaturesToDepth to convert head logits into depth maps using configurable bin and normalization strategies'}
```

## File: huggingface_transformers/src/transformers/models/chmv2/modular_chmv2.py

Prompts

```
['convert a CHMv2 checkpoint to HuggingFace format with optional backbone and verification', 'create a CHMv2Config with DINOv3 backbone and depth estimation parameters', 'convert CHMv2 head state dict keys to HuggingFace naming convention via regex mapping', 'convert DINOv3 backbone state dict keys to HuggingFace format with qkv splitting', 'load a PyTorch checkpoint handling model or state_dict wrapper keys', 'create a CHMv2ImageProcessor instance for preprocessing images and segmentation maps for the CHMV2 model', 'run preprocess on input images and optional segmentation maps to produce pixel values and labels tensors', 'run reduce_label to shift segmentation map labels by 1, replacing background 0 with 255', 'test resize on a torch tensor image to a target size with aspect ratio preservation and size divisor alignment', 'review post_process_depth_estimation to convert raw DepthEstimatorOutput into final depth prediction tensors resized to target sizes', 'create a CHMv2ForDepthEstimation model with a depth estimation head for canopy height estimation', 'run the CHMv2ForDepthEstimation forward pass to predict depth maps from input pixel values', 'build a CHMv2ReassembleStage that processes backbone hidden states into multi-resolution feature representations', 'build a CHMv2FeatureFusionLayer that fuses multi-scale features with residual connections and upsampling', 'run CHMv2FeaturesToDepth to convert head logits into depth maps using configurable bin and normalization strategies', 'build a CHMv2ForDepthEstimation model from a CHMv2Config for canopy height estimation', 'run CHMv2ForDepthEstimation forward pass on pixel_values to produce predicted_depth output', 'process CHMv2ForDepthEstimation DepthEstimatorOutput with CHMv2ImageProcessor post_process_depth_estimation', 'convert CHMv2 head logits to depth values using CHMv2FeaturesToDepth with mixlog bins strategy']
```

Usage

```
{'create_chmv2_config': 'create a CHMv2Config instance with custom patch_size, min_depth, max_depth, and bins_strategy', 'build_chmv2_depth_model': 'build a CHMv2ForDepthEstimation model from a CHMv2Config for canopy height estimation', 'run_chmv2_depth_prediction': 'run CHMv2ForDepthEstimation forward pass on pixel_values to produce predicted_depth output', 'process_chmv2_depth_output': 'process CHMv2ForDepthEstimation DepthEstimatorOutput with CHMv2ImageProcessor post_process_depth_estimation', 'convert_chmv2_logits_to_depth': 'convert CHMv2 head logits to depth values using CHMv2FeaturesToDepth with mixlog bins strategy'}
```

