# Agent Python Tools

- repo: facebookresearch/metamorph
- repo_uri: https://github.com/facebookresearch/metamorph

## File: facebookresearch_metamorph/metamorph/model/multimodal_encoder/builder.py

Prompts

```
['build a SiglipVisionTower from a vision tower config object with mm_vision_tower or vision_tower attribute', 'build a Siglip-based vision encoder using build_vision_tower with a config containing model name and hyperparameters', 'review the build_vision_tower function to understand how it extracts the vision tower name from config', 'refactor build_vision_tower to support additional vision tower types beyond SiglipVisionTower', 'test build_vision_tower by passing a config object with mm_vision_tower set to a valid SigLIP model name', 'build a SiglipVisionTower module that loads a pretrained SigLIP vision model and extracts image features', 'create a ProcessorWrapper class to preprocess PIL images with a custom transform and crop size', 'test the extract_res_interp function to parse model names and return resolution and interpolation values', 'refactor the SiglipVisionTower forward method to support additional image token reduction strategies', 'review the SiglipVisionTower feature_select method to extract patch features from hidden states']
```

Usage

```
{'build_vision_tower': 'build a SiglipVisionTower from a vision tower config object with mm_vision_tower or vision_tower attribute', 'build_siglip_encoder': 'build a Siglip-based vision encoder using build_vision_tower with a config containing model name and hyperparameters', 'review_build_vision_tower': 'review the build_vision_tower function to understand how it extracts the vision tower name from config', 'refactor_build_vision_tower': 'refactor build_vision_tower to support additional vision tower types beyond SiglipVisionTower', 'test_build_vision_tower': 'test build_vision_tower by passing a config object with mm_vision_tower set to a valid SigLIP model name'}
```

## File: facebookresearch_metamorph/metamorph/model/multimodal_encoder/siglip_encoder.py

Prompts

```
['build a SiglipVisionTower from a vision tower config object with mm_vision_tower or vision_tower attribute', 'build a Siglip-based vision encoder using build_vision_tower with a config containing model name and hyperparameters', 'review the build_vision_tower function to understand how it extracts the vision tower name from config', 'refactor build_vision_tower to support additional vision tower types beyond SiglipVisionTower', 'test build_vision_tower by passing a config object with mm_vision_tower set to a valid SigLIP model name', 'build a SiglipVisionTower module that loads a pretrained SigLIP vision model and extracts image features', 'create a ProcessorWrapper class to preprocess PIL images with a custom transform and crop size', 'test the extract_res_interp function to parse model names and return resolution and interpolation values', 'refactor the SiglipVisionTower forward method to support additional image token reduction strategies', 'review the SiglipVisionTower feature_select method to extract patch features from hidden states']
```

Usage

```
{'build_siglip_vision_tower': 'build a SiglipVisionTower module that loads a pretrained SigLIP vision model and extracts image features', 'create_processor_wrapper': 'create a ProcessorWrapper class to preprocess PIL images with a custom transform and crop size', 'test_extract_res_interp': 'test the extract_res_interp function to parse model names and return resolution and interpolation values', 'refactor_siglip_forward': 'refactor the SiglipVisionTower forward method to support additional image token reduction strategies', 'review_feature_select': 'review the SiglipVisionTower feature_select method to extract patch features from hidden states'}
```

