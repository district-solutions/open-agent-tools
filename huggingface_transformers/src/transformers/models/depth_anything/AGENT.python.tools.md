# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/depth_anything/configuration_depth_anything.py

Prompts

```
['create a DepthAnythingConfig instance with default settings for depth estimation', 'configure a DepthAnythingConfig with custom reassemble_hidden_size and reassemble_factors', 'validate the DepthAnythingConfig architecture to ensure depth_estimation_type is relative or metric', 'build a DepthAnythingConfig with depth_estimation_type set to metric and a custom max_depth value', 'review the DepthAnythingConfig class and its backbone consolidation logic in __post_init__', 'convert a Depth Anything checkpoint from the original repository to HuggingFace Transformers format', 'create a mapping of key renames from the original Depth Anything checkpoint to HuggingFace model structure', 'split combined qkv weight matrices into separate query, key, and value tensors for each encoder layer', 'generate a DepthAnythingConfig from a model name string with variant and size selection', 'run the Depth Anything to HuggingFace checkpoint conversion via argparse command-line interface', 'convert a Distill Any Depth checkpoint to HuggingFace DepthAnythingForDepthEstimation format', 'build a DepthAnythingConfig from a Dinov2 backbone config for small, base, or large model variants', 'convert original Distill Any Depth state dict keys to HuggingFace key naming conventions', 'verify the converted model produces expected depth predictions on a sample image', 'save the converted model and DPTImageProcessor to a local directory', 'build a DepthAnythingForDepthEstimation model that performs depth estimation on input images', 'create a DepthAnythingNeck with reassemble and feature fusion stages to process backbone hidden states', 'run forward pass on DepthAnythingForDepthEstimation to predict per-pixel depth from pixel values', 'create a DepthAnythingFeatureFusionLayer that merges feature maps from different backbone stages', 'build a DepthAnythingReassembleStage that reshapes backbone embeddings into image-like feature representations']
```

Usage

```
{'create_depth_anything_config': 'create a DepthAnythingConfig instance with default settings for depth estimation', 'configure_depth_anything_model': 'configure a DepthAnythingConfig with custom reassemble_hidden_size and reassemble_factors', 'validate_depth_anything_config': 'validate the DepthAnythingConfig architecture to ensure depth_estimation_type is relative or metric', 'build_depth_anything_config_metric': 'build a DepthAnythingConfig with depth_estimation_type set to metric and a custom max_depth value', 'review_depth_anything_config': 'review the DepthAnythingConfig class and its backbone consolidation logic in __post_init__'}
```

## File: huggingface_transformers/src/transformers/models/depth_anything/convert_depth_anything_to_hf.py

Prompts

```
['create a DepthAnythingConfig instance with default settings for depth estimation', 'configure a DepthAnythingConfig with custom reassemble_hidden_size and reassemble_factors', 'validate the DepthAnythingConfig architecture to ensure depth_estimation_type is relative or metric', 'build a DepthAnythingConfig with depth_estimation_type set to metric and a custom max_depth value', 'review the DepthAnythingConfig class and its backbone consolidation logic in __post_init__', 'convert a Depth Anything checkpoint from the original repository to HuggingFace Transformers format', 'create a mapping of key renames from the original Depth Anything checkpoint to HuggingFace model structure', 'split combined qkv weight matrices into separate query, key, and value tensors for each encoder layer', 'generate a DepthAnythingConfig from a model name string with variant and size selection', 'run the Depth Anything to HuggingFace checkpoint conversion via argparse command-line interface', 'convert a Distill Any Depth checkpoint to HuggingFace DepthAnythingForDepthEstimation format', 'build a DepthAnythingConfig from a Dinov2 backbone config for small, base, or large model variants', 'convert original Distill Any Depth state dict keys to HuggingFace key naming conventions', 'verify the converted model produces expected depth predictions on a sample image', 'save the converted model and DPTImageProcessor to a local directory', 'build a DepthAnythingForDepthEstimation model that performs depth estimation on input images', 'create a DepthAnythingNeck with reassemble and feature fusion stages to process backbone hidden states', 'run forward pass on DepthAnythingForDepthEstimation to predict per-pixel depth from pixel values', 'create a DepthAnythingFeatureFusionLayer that merges feature maps from different backbone stages', 'build a DepthAnythingReassembleStage that reshapes backbone embeddings into image-like feature representations']
```

Usage

```
{'convert_depth_anything_checkpoint': 'convert a Depth Anything checkpoint from the original repository to HuggingFace Transformers format', 'create_rename_keys': 'create a mapping of key renames from the original Depth Anything checkpoint to HuggingFace model structure', 'read_in_q_k_v': 'split combined qkv weight matrices into separate query, key, and value tensors for each encoder layer', 'get_dpt_config': 'generate a DepthAnythingConfig from a model name string with variant and size selection', 'run_depth_anything_conversion_cli': 'run the Depth Anything to HuggingFace checkpoint conversion via argparse command-line interface'}
```

## File: huggingface_transformers/src/transformers/models/depth_anything/convert_distill_any_depth_to_hf.py

Prompts

```
['create a DepthAnythingConfig instance with default settings for depth estimation', 'configure a DepthAnythingConfig with custom reassemble_hidden_size and reassemble_factors', 'validate the DepthAnythingConfig architecture to ensure depth_estimation_type is relative or metric', 'build a DepthAnythingConfig with depth_estimation_type set to metric and a custom max_depth value', 'review the DepthAnythingConfig class and its backbone consolidation logic in __post_init__', 'convert a Depth Anything checkpoint from the original repository to HuggingFace Transformers format', 'create a mapping of key renames from the original Depth Anything checkpoint to HuggingFace model structure', 'split combined qkv weight matrices into separate query, key, and value tensors for each encoder layer', 'generate a DepthAnythingConfig from a model name string with variant and size selection', 'run the Depth Anything to HuggingFace checkpoint conversion via argparse command-line interface', 'convert a Distill Any Depth checkpoint to HuggingFace DepthAnythingForDepthEstimation format', 'build a DepthAnythingConfig from a Dinov2 backbone config for small, base, or large model variants', 'convert original Distill Any Depth state dict keys to HuggingFace key naming conventions', 'verify the converted model produces expected depth predictions on a sample image', 'save the converted model and DPTImageProcessor to a local directory', 'build a DepthAnythingForDepthEstimation model that performs depth estimation on input images', 'create a DepthAnythingNeck with reassemble and feature fusion stages to process backbone hidden states', 'run forward pass on DepthAnythingForDepthEstimation to predict per-pixel depth from pixel values', 'create a DepthAnythingFeatureFusionLayer that merges feature maps from different backbone stages', 'build a DepthAnythingReassembleStage that reshapes backbone embeddings into image-like feature representations']
```

Usage

```
{'convert_distill_any_depth_checkpoint': 'convert a Distill Any Depth checkpoint to HuggingFace DepthAnythingForDepthEstimation format', 'build_depth_anything_config': 'build a DepthAnythingConfig from a Dinov2 backbone config for small, base, or large model variants', 'convert_state_dict_keys': 'convert original Distill Any Depth state dict keys to HuggingFace key naming conventions', 'verify_converted_model_logits': 'verify the converted model produces expected depth predictions on a sample image', 'save_converted_model_to_disk': 'save the converted model and DPTImageProcessor to a local directory'}
```

## File: huggingface_transformers/src/transformers/models/depth_anything/modeling_depth_anything.py

Prompts

```
['create a DepthAnythingConfig instance with default settings for depth estimation', 'configure a DepthAnythingConfig with custom reassemble_hidden_size and reassemble_factors', 'validate the DepthAnythingConfig architecture to ensure depth_estimation_type is relative or metric', 'build a DepthAnythingConfig with depth_estimation_type set to metric and a custom max_depth value', 'review the DepthAnythingConfig class and its backbone consolidation logic in __post_init__', 'convert a Depth Anything checkpoint from the original repository to HuggingFace Transformers format', 'create a mapping of key renames from the original Depth Anything checkpoint to HuggingFace model structure', 'split combined qkv weight matrices into separate query, key, and value tensors for each encoder layer', 'generate a DepthAnythingConfig from a model name string with variant and size selection', 'run the Depth Anything to HuggingFace checkpoint conversion via argparse command-line interface', 'convert a Distill Any Depth checkpoint to HuggingFace DepthAnythingForDepthEstimation format', 'build a DepthAnythingConfig from a Dinov2 backbone config for small, base, or large model variants', 'convert original Distill Any Depth state dict keys to HuggingFace key naming conventions', 'verify the converted model produces expected depth predictions on a sample image', 'save the converted model and DPTImageProcessor to a local directory', 'build a DepthAnythingForDepthEstimation model that performs depth estimation on input images', 'create a DepthAnythingNeck with reassemble and feature fusion stages to process backbone hidden states', 'run forward pass on DepthAnythingForDepthEstimation to predict per-pixel depth from pixel values', 'create a DepthAnythingFeatureFusionLayer that merges feature maps from different backbone stages', 'build a DepthAnythingReassembleStage that reshapes backbone embeddings into image-like feature representations']
```

Usage

```
{'build_depth_estimation_model': 'build a DepthAnythingForDepthEstimation model that performs depth estimation on input images', 'create_neck_fusion_stages': 'create a DepthAnythingNeck with reassemble and feature fusion stages to process backbone hidden states', 'run_depth_prediction': 'run forward pass on DepthAnythingForDepthEstimation to predict per-pixel depth from pixel values', 'create_feature_fusion_layer': 'create a DepthAnythingFeatureFusionLayer that merges feature maps from different backbone stages', 'build_reassemble_stage': 'build a DepthAnythingReassembleStage that reshapes backbone embeddings into image-like feature representations'}
```

