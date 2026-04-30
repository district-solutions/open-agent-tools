# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/swinv2/convert_swinv2_timm_to_pytorch.py

Prompts

```
['convert a Swinv2 timm checkpoint to a Hugging Face PyTorch model and save it to a local directory', 'get a Swinv2Config object from a timm model name string with parsed embed_dim, depths, and num_heads', 'rename a timm state dict key to match the Hugging Face Swinv2 model key naming convention', 'convert a timm state dict into Hugging Face Swinv2 state dict format with qkv splitting and key renaming', 'run the Swinv2 timm-to-pytorch conversion CLI with a model name and output directory path', 'create a Swinv2 model for image classification with a linear classifier head on top of pooled hidden states', 'run Swinv2 masked image modeling to reconstruct pixel values from randomly masked patches using SimMIM', 'build a Swinv2 backbone to extract multi-scale feature maps for downstream tasks like DETR and MaskFormer', 'run the Swinv2 encoder to process patch embeddings through shifted window self-attention stages with hierarchical downsampling', 'test the Swinv2 self-attention module with cosine attention, continuous relative position bias, and shifted window partitioning']
```

Usage

```
{'convert_swinv2_checkpoint': 'convert a Swinv2 timm checkpoint to a Hugging Face PyTorch model and save it to a local directory', 'get_swinv2_config': 'get a Swinv2Config object from a timm model name string with parsed embed_dim, depths, and num_heads', 'rename_key': 'rename a timm state dict key to match the Hugging Face Swinv2 model key naming convention', 'convert_state_dict': 'convert a timm state dict into Hugging Face Swinv2 state dict format with qkv splitting and key renaming', 'run_swinv2_conversion_cli': 'run the Swinv2 timm-to-pytorch conversion CLI with a model name and output directory path'}
```

## File: huggingface_transformers/src/transformers/models/swinv2/modeling_swinv2.py

Prompts

```
['convert a Swinv2 timm checkpoint to a Hugging Face PyTorch model and save it to a local directory', 'get a Swinv2Config object from a timm model name string with parsed embed_dim, depths, and num_heads', 'rename a timm state dict key to match the Hugging Face Swinv2 model key naming convention', 'convert a timm state dict into Hugging Face Swinv2 state dict format with qkv splitting and key renaming', 'run the Swinv2 timm-to-pytorch conversion CLI with a model name and output directory path', 'create a Swinv2 model for image classification with a linear classifier head on top of pooled hidden states', 'run Swinv2 masked image modeling to reconstruct pixel values from randomly masked patches using SimMIM', 'build a Swinv2 backbone to extract multi-scale feature maps for downstream tasks like DETR and MaskFormer', 'run the Swinv2 encoder to process patch embeddings through shifted window self-attention stages with hierarchical downsampling', 'test the Swinv2 self-attention module with cosine attention, continuous relative position bias, and shifted window partitioning']
```

Usage

```
{'create_swinv2_image_classifier': 'create a Swinv2 model for image classification with a linear classifier head on top of pooled hidden states', 'run_swinv2_masked_image_modeling': 'run Swinv2 masked image modeling to reconstruct pixel values from randomly masked patches using SimMIM', 'build_swinv2_backbone': 'build a Swinv2 backbone to extract multi-scale feature maps for downstream tasks like DETR and MaskFormer', 'run_swinv2_encoder': 'run the Swinv2 encoder to process patch embeddings through shifted window self-attention stages with hierarchical downsampling', 'test_swinv2_self_attention': 'test the Swinv2 self-attention module with cosine attention, continuous relative position bias, and shifted window partitioning'}
```

