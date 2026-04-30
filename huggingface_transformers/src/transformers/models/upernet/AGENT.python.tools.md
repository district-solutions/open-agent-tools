# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/upernet/convert_convnext_upernet_to_pytorch.py

Prompts

```
['convert a ConvNext UperNet checkpoint from mmsegmentation to PyTorch format and save locally', 'get a UperNetConfig object for a specified ConvNext model size variant', 'create a list of key renames to map mmsegmentation checkpoint keys to PyTorch transformer keys', 'run the CLI conversion script for a ConvNext UperNet model with optional hub push', 'test the converted checkpoint by verifying logits against expected slice values', 'split combined qkv projection weights into separate query, key, and value weight tensors for attention layers', 'reverse the unfold-based downsampling weight reordering from mmsegmentation to match PyTorch expectations', 'build a UperNetForSemanticSegmentation model for semantic segmentation on ADE20k or CityScapes datasets', 'create a UperNetConvModule convolutional block with conv, batch norm, and ReLU activation layers', 'build a UperNetPyramidPoolingModule with configurable pooling scales for multi-scale feature extraction', 'run UperNetForSemanticSegmentation forward pass to produce semantic segmentation logits from pixel values', 'test UperNetForSemanticSegmentation training with auxiliary head loss and cross-entropy loss on segmentation labels']
```

Usage

```
{'convert_upernet_checkpoint': 'convert a ConvNext UperNet checkpoint from mmsegmentation to PyTorch format and save locally', 'get_upernet_config': 'get a UperNetConfig object for a specified ConvNext model size variant', 'create_rename_keys': 'create a list of key renames to map mmsegmentation checkpoint keys to PyTorch transformer keys', 'run_convnext_upernet_conversion': 'run the CLI conversion script for a ConvNext UperNet model with optional hub push', 'test_conversion_accuracy': 'test the converted checkpoint by verifying logits against expected slice values'}
```

## File: huggingface_transformers/src/transformers/models/upernet/convert_swin_upernet_to_pytorch.py

Prompts

```
['convert a ConvNext UperNet checkpoint from mmsegmentation to PyTorch format and save locally', 'get a UperNetConfig object for a specified ConvNext model size variant', 'create a list of key renames to map mmsegmentation checkpoint keys to PyTorch transformer keys', 'run the CLI conversion script for a ConvNext UperNet model with optional hub push', 'test the converted checkpoint by verifying logits against expected slice values', 'split combined qkv projection weights into separate query, key, and value weight tensors for attention layers', 'reverse the unfold-based downsampling weight reordering from mmsegmentation to match PyTorch expectations', 'build a UperNetForSemanticSegmentation model for semantic segmentation on ADE20k or CityScapes datasets', 'create a UperNetConvModule convolutional block with conv, batch norm, and ReLU activation layers', 'build a UperNetPyramidPoolingModule with configurable pooling scales for multi-scale feature extraction', 'run UperNetForSemanticSegmentation forward pass to produce semantic segmentation logits from pixel values', 'test UperNetForSemanticSegmentation training with auxiliary head loss and cross-entropy loss on segmentation labels']
```

Usage

```
{'convert_upernet_checkpoint': 'convert a mmsegmentation Swin UperNet checkpoint to PyTorch HuggingFace format for tiny, small, base, or large variants', 'create_rename_keys': 'create key renaming rules to map mmsegmentation Swin UperNet checkpoint keys to HuggingFace UperNetForSemanticSegmentation keys', 'read_in_q_k_v': 'split combined qkv projection weights into separate query, key, and value weight tensors for attention layers', 'get_upernet_config': 'generate a UperNetConfig with Swin backbone configuration for tiny, small, base, or large model variants on ADE20K', 'reverse_correct_unfold_reduction_order': 'reverse the unfold-based downsampling weight reordering from mmsegmentation to match PyTorch expectations'}
```

## File: huggingface_transformers/src/transformers/models/upernet/modeling_upernet.py

Prompts

```
['convert a ConvNext UperNet checkpoint from mmsegmentation to PyTorch format and save locally', 'get a UperNetConfig object for a specified ConvNext model size variant', 'create a list of key renames to map mmsegmentation checkpoint keys to PyTorch transformer keys', 'run the CLI conversion script for a ConvNext UperNet model with optional hub push', 'test the converted checkpoint by verifying logits against expected slice values', 'split combined qkv projection weights into separate query, key, and value weight tensors for attention layers', 'reverse the unfold-based downsampling weight reordering from mmsegmentation to match PyTorch expectations', 'build a UperNetForSemanticSegmentation model for semantic segmentation on ADE20k or CityScapes datasets', 'create a UperNetConvModule convolutional block with conv, batch norm, and ReLU activation layers', 'build a UperNetPyramidPoolingModule with configurable pooling scales for multi-scale feature extraction', 'run UperNetForSemanticSegmentation forward pass to produce semantic segmentation logits from pixel values', 'test UperNetForSemanticSegmentation training with auxiliary head loss and cross-entropy loss on segmentation labels']
```

Usage

```
{'build_upernet_semantic_segmentation_model': 'build a UperNetForSemanticSegmentation model for semantic segmentation on ADE20k or CityScapes datasets', 'create_upernet_conv_module': 'create a UperNetConvModule convolutional block with conv, batch norm, and ReLU activation layers', 'build_upernet_psp_module': 'build a UperNetPyramidPoolingModule with configurable pooling scales for multi-scale feature extraction', 'run_upernet_forward_inference': 'run UperNetForSemanticSegmentation forward pass to produce semantic segmentation logits from pixel values', 'test_upernet_training_with_auxiliary_loss': 'test UperNetForSemanticSegmentation training with auxiliary head loss and cross-entropy loss on segmentation labels'}
```

