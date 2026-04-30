# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/dinov2_with_registers/convert_dinov2_with_registers_to_hf.py

Prompts

```
["convert a DINOv2 with Registers checkpoint from Facebook's repository to HuggingFace format", 'get a Dinov2WithRegistersConfig for a given model variant like vits, vitb, vitl, or vitg', 'create a mapping of key renames to transform original DINOv2 state dict keys to HuggingFace keys', 'split a combined qkv weight matrix into separate query, key, and value weight tensors', 'run the conversion script via argparse CLI with model name, output path, and optional hub push', 'create a Dinov2WithRegistersForImageClassification model with custom config for image classification', 'build a Dinov2WithRegistersBackbone for feature extraction in DETR or MaskFormer pipelines', 'run Dinov2WithRegistersModel forward pass on pixel values to extract hidden states and pooled output', 'test Dinov2WithRegistersEmbeddings interpolation of positional encodings for higher resolution images', 'review Dinov2WithRegistersSelfAttention implementation with QKV projections and attention interface dispatch', 'create a Dinov2WithRegistersConfig with custom hidden size, layers, and register tokens', 'build a Dinov2WithRegistersModel from a configuration for feature extraction', 'run a Dinov2WithRegistersForImageClassification forward pass on image pixel values with optional labels', 'build a Dinov2WithRegistersBackbone that extracts multi-stage feature maps from images', 'interpolate position embeddings for Dinov2WithRegistersEmbeddings to support higher resolution images']
```

Usage

```
{'convert_dinov2_checkpoint': "convert a DINOv2 with Registers checkpoint from Facebook's repository to HuggingFace format", 'get_dinov2_config': 'get a Dinov2WithRegistersConfig for a given model variant like vits, vitb, vitl, or vitg', 'create_rename_keys': 'create a mapping of key renames to transform original DINOv2 state dict keys to HuggingFace keys', 'read_in_q_k_v': 'split a combined qkv weight matrix into separate query, key, and value weight tensors', 'run_conversion_cli': 'run the conversion script via argparse CLI with model name, output path, and optional hub push'}
```

## File: huggingface_transformers/src/transformers/models/dinov2_with_registers/modeling_dinov2_with_registers.py

Prompts

```
["convert a DINOv2 with Registers checkpoint from Facebook's repository to HuggingFace format", 'get a Dinov2WithRegistersConfig for a given model variant like vits, vitb, vitl, or vitg', 'create a mapping of key renames to transform original DINOv2 state dict keys to HuggingFace keys', 'split a combined qkv weight matrix into separate query, key, and value weight tensors', 'run the conversion script via argparse CLI with model name, output path, and optional hub push', 'create a Dinov2WithRegistersForImageClassification model with custom config for image classification', 'build a Dinov2WithRegistersBackbone for feature extraction in DETR or MaskFormer pipelines', 'run Dinov2WithRegistersModel forward pass on pixel values to extract hidden states and pooled output', 'test Dinov2WithRegistersEmbeddings interpolation of positional encodings for higher resolution images', 'review Dinov2WithRegistersSelfAttention implementation with QKV projections and attention interface dispatch', 'create a Dinov2WithRegistersConfig with custom hidden size, layers, and register tokens', 'build a Dinov2WithRegistersModel from a configuration for feature extraction', 'run a Dinov2WithRegistersForImageClassification forward pass on image pixel values with optional labels', 'build a Dinov2WithRegistersBackbone that extracts multi-stage feature maps from images', 'interpolate position embeddings for Dinov2WithRegistersEmbeddings to support higher resolution images']
```

Usage

```
{'create_model_dinov2_with_registers_classification': 'create a Dinov2WithRegistersForImageClassification model with custom config for image classification', 'build_model_dinov2_with_registers_backbone': 'build a Dinov2WithRegistersBackbone for feature extraction in DETR or MaskFormer pipelines', 'run_model_dinov2_with_registers_forward': 'run Dinov2WithRegistersModel forward pass on pixel values to extract hidden states and pooled output', 'test_model_dinov2_with_registers_embeddings': 'test Dinov2WithRegistersEmbeddings interpolation of positional encodings for higher resolution images', 'review_model_dinov2_with_registers_attention': 'review Dinov2WithRegistersSelfAttention implementation with QKV projections and attention interface dispatch'}
```

## File: huggingface_transformers/src/transformers/models/dinov2_with_registers/modular_dinov2_with_registers.py

Prompts

```
["convert a DINOv2 with Registers checkpoint from Facebook's repository to HuggingFace format", 'get a Dinov2WithRegistersConfig for a given model variant like vits, vitb, vitl, or vitg', 'create a mapping of key renames to transform original DINOv2 state dict keys to HuggingFace keys', 'split a combined qkv weight matrix into separate query, key, and value weight tensors', 'run the conversion script via argparse CLI with model name, output path, and optional hub push', 'create a Dinov2WithRegistersForImageClassification model with custom config for image classification', 'build a Dinov2WithRegistersBackbone for feature extraction in DETR or MaskFormer pipelines', 'run Dinov2WithRegistersModel forward pass on pixel values to extract hidden states and pooled output', 'test Dinov2WithRegistersEmbeddings interpolation of positional encodings for higher resolution images', 'review Dinov2WithRegistersSelfAttention implementation with QKV projections and attention interface dispatch', 'create a Dinov2WithRegistersConfig with custom hidden size, layers, and register tokens', 'build a Dinov2WithRegistersModel from a configuration for feature extraction', 'run a Dinov2WithRegistersForImageClassification forward pass on image pixel values with optional labels', 'build a Dinov2WithRegistersBackbone that extracts multi-stage feature maps from images', 'interpolate position embeddings for Dinov2WithRegistersEmbeddings to support higher resolution images']
```

Usage

```
{'create_dinov2_with_registers_config': 'create a Dinov2WithRegistersConfig with custom hidden size, layers, and register tokens', 'build_dinov2_with_registers_model': 'build a Dinov2WithRegistersModel from a configuration for feature extraction', 'run_dinov2_with_registers_classification': 'run a Dinov2WithRegistersForImageClassification forward pass on image pixel values with optional labels', 'build_dinov2_with_registers_backbone': 'build a Dinov2WithRegistersBackbone that extracts multi-stage feature maps from images', 'interpolate_dinov2_position_embeddings': 'interpolate position embeddings for Dinov2WithRegistersEmbeddings to support higher resolution images'}
```

