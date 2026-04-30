# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/swin/convert_swin_simmim_to_pytorch.py

Prompts

```
['convert a Swin SimMIM checkpoint to a PyTorch model and optionally push to the Hugging Face hub', 'get a SwinConfig for base or large Swin SimMIM model variants with appropriate architecture parameters', 'rename state dict keys from the original Swin repository format to Hugging Face transformers format', 'convert a state dictionary from the original Swin SimMIM checkpoint to the transformers model format', 'run the Swin SimMIM to PyTorch conversion script via argparse command line interface', 'test that a converted Swin model produces outputs matching the original timm model', 'create a SwinForImageClassification model to classify images into predefined categories', 'create a SwinForMaskedImageModeling model to reconstruct masked patches of input images', 'build a SwinBackbone model to extract multi-scale feature maps for downstream detection tasks', 'run a forward pass through the SwinModel encoder to produce hidden states and attention outputs', 'review the SwinSelfAttention and window_partition functions that implement shifted window attention']
```

Usage

```
{'convert_swin_checkpoint': 'convert a Swin SimMIM checkpoint to a PyTorch model and optionally push to the Hugging Face hub', 'get_swin_config': 'get a SwinConfig for base or large Swin SimMIM model variants with appropriate architecture parameters', 'rename_key': 'rename state dict keys from the original Swin repository format to Hugging Face transformers format', 'convert_state_dict': 'convert a state dictionary from the original Swin SimMIM checkpoint to the transformers model format', 'run_swin_conversion_cli': 'run the Swin SimMIM to PyTorch conversion script via argparse command line interface'}
```

## File: huggingface_transformers/src/transformers/models/swin/convert_swin_timm_to_pytorch.py

Prompts

```
['convert a Swin SimMIM checkpoint to a PyTorch model and optionally push to the Hugging Face hub', 'get a SwinConfig for base or large Swin SimMIM model variants with appropriate architecture parameters', 'rename state dict keys from the original Swin repository format to Hugging Face transformers format', 'convert a state dictionary from the original Swin SimMIM checkpoint to the transformers model format', 'run the Swin SimMIM to PyTorch conversion script via argparse command line interface', 'test that a converted Swin model produces outputs matching the original timm model', 'create a SwinForImageClassification model to classify images into predefined categories', 'create a SwinForMaskedImageModeling model to reconstruct masked patches of input images', 'build a SwinBackbone model to extract multi-scale feature maps for downstream detection tasks', 'run a forward pass through the SwinModel encoder to produce hidden states and attention outputs', 'review the SwinSelfAttention and window_partition functions that implement shifted window attention']
```

Usage

```
{'convert_swin_checkpoint': 'convert a timm Swin Transformer checkpoint to a Hugging Face PyTorch model and save it', 'get_swin_config': 'get a SwinConfig object from a timm Swin model name with correct architecture parameters', 'rename_key': 'rename a timm state dict key to match the Hugging Face Swin model key naming convention', 'convert_state_dict': 'convert a timm state dictionary to the Hugging Face Swin model state dictionary format', 'test_swin_conversion': 'test that a converted Swin model produces outputs matching the original timm model'}
```

## File: huggingface_transformers/src/transformers/models/swin/modeling_swin.py

Prompts

```
['convert a Swin SimMIM checkpoint to a PyTorch model and optionally push to the Hugging Face hub', 'get a SwinConfig for base or large Swin SimMIM model variants with appropriate architecture parameters', 'rename state dict keys from the original Swin repository format to Hugging Face transformers format', 'convert a state dictionary from the original Swin SimMIM checkpoint to the transformers model format', 'run the Swin SimMIM to PyTorch conversion script via argparse command line interface', 'test that a converted Swin model produces outputs matching the original timm model', 'create a SwinForImageClassification model to classify images into predefined categories', 'create a SwinForMaskedImageModeling model to reconstruct masked patches of input images', 'build a SwinBackbone model to extract multi-scale feature maps for downstream detection tasks', 'run a forward pass through the SwinModel encoder to produce hidden states and attention outputs', 'review the SwinSelfAttention and window_partition functions that implement shifted window attention']
```

Usage

```
{'create_swin_image_classification': 'create a SwinForImageClassification model to classify images into predefined categories', 'create_swin_masked_image_modeling': 'create a SwinForMaskedImageModeling model to reconstruct masked patches of input images', 'build_swin_backbone': 'build a SwinBackbone model to extract multi-scale feature maps for downstream detection tasks', 'run_swin_forward_pass': 'run a forward pass through the SwinModel encoder to produce hidden states and attention outputs', 'review_swin_attention_windows': 'review the SwinSelfAttention and window_partition functions that implement shifted window attention'}
```

