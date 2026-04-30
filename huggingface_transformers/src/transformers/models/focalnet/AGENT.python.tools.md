# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/focalnet/convert_focalnet_to_hf_format.py

Prompts

```
["convert a FocalNet checkpoint from Microsoft's repository to HuggingFace Transformers format", 'build a FocalNet config object for a given model name with correct embed_dim, depths, and focal settings', 'rename FocalNet checkpoint keys to match HuggingFace Transformers naming conventions', 'run the FocalNet conversion CLI to download and convert a model to HuggingFace format', 'test the converted FocalNet model by verifying logits against expected values on a sample image', 'create a FocalNetModel for extracting image features with optional pooling and mask token support', 'build a FocalNetForImageClassification model with a linear classifier head for image classification tasks', 'build a FocalNetForMaskedImageModeling model with a decoder on top for masked image modeling pretraining', 'build a FocalNetBackbone for extracting multi-scale feature maps to use with frameworks like X-Decoder', 'review the FocalNetModulation class that implements focal modulation with multi-scale context aggregation and gating']
```

Usage

```
{'convert_focalnet_checkpoint': "convert a FocalNet checkpoint from Microsoft's repository to HuggingFace Transformers format", 'get_focalnet_config': 'build a FocalNet config object for a given model name with correct embed_dim, depths, and focal settings', 'rename_key': 'rename FocalNet checkpoint keys to match HuggingFace Transformers naming conventions', 'run_focalnet_conversion_cli': 'run the FocalNet conversion CLI to download and convert a model to HuggingFace format', 'test_conversion_accuracy': 'test the converted FocalNet model by verifying logits against expected values on a sample image'}
```

## File: huggingface_transformers/src/transformers/models/focalnet/modeling_focalnet.py

Prompts

```
["convert a FocalNet checkpoint from Microsoft's repository to HuggingFace Transformers format", 'build a FocalNet config object for a given model name with correct embed_dim, depths, and focal settings', 'rename FocalNet checkpoint keys to match HuggingFace Transformers naming conventions', 'run the FocalNet conversion CLI to download and convert a model to HuggingFace format', 'test the converted FocalNet model by verifying logits against expected values on a sample image', 'create a FocalNetModel for extracting image features with optional pooling and mask token support', 'build a FocalNetForImageClassification model with a linear classifier head for image classification tasks', 'build a FocalNetForMaskedImageModeling model with a decoder on top for masked image modeling pretraining', 'build a FocalNetBackbone for extracting multi-scale feature maps to use with frameworks like X-Decoder', 'review the FocalNetModulation class that implements focal modulation with multi-scale context aggregation and gating']
```

Usage

```
{'create_focalnet_model': 'create a FocalNetModel for extracting image features with optional pooling and mask token support', 'build_focalnet_classifier': 'build a FocalNetForImageClassification model with a linear classifier head for image classification tasks', 'build_focalnet_masked_image_model': 'build a FocalNetForMaskedImageModeling model with a decoder on top for masked image modeling pretraining', 'build_focalnet_backbone': 'build a FocalNetBackbone for extracting multi-scale feature maps to use with frameworks like X-Decoder', 'review_focalnet_modulation': 'review the FocalNetModulation class that implements focal modulation with multi-scale context aggregation and gating'}
```

