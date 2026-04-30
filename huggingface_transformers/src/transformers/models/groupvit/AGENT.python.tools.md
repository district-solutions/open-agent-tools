# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/groupvit/configuration_groupvit.py

Prompts

```
['create a GroupViTTextConfig with default text model settings for initializing a GroupViT text encoder', 'create a GroupViTVisionConfig with default vision model settings including depths and group tokens', 'create a GroupViTConfig combining text and vision sub-configs with projection dimensions for multimodal modeling', 'validate GroupViTVisionConfig architecture by checking num_hidden_layers matches sum of depths', 'initialize GroupViTConfig from text_config_dict and vision_config_dict with conflict resolution logging', 'convert a GroupViT checkpoint from NVlabs to HuggingFace Transformers format and save locally', 'convert a GroupViT state dict from NVlabs naming to HuggingFace naming conventions', 'rename a GroupViT checkpoint key from NVlabs to HuggingFace Transformers naming scheme', 'prepare a sample cat image from COCO dataset for verifying the converted GroupViT model', 'run the GroupViT checkpoint conversion script via argparse CLI with checkpoint path and output folder', 'create a GroupViTModel instance for image-text retrieval with segmentation support', 'run the GroupViTModel forward pass to compute image-text similarity logits and contrastive loss', 'get image features from GroupViTModel by projecting vision encoder pooled output', 'get text features from GroupViTModel by projecting text encoder pooled output', 'test the image_text_contrastive_loss function that computes bidirectional image-text contrastive loss']
```

Usage

```
{'create_GroupViTTextConfig': 'create a GroupViTTextConfig with default text model settings for initializing a GroupViT text encoder', 'create_GroupViTVisionConfig': 'create a GroupViTVisionConfig with default vision model settings including depths and group tokens', 'create_GroupViTConfig': 'create a GroupViTConfig combining text and vision sub-configs with projection dimensions for multimodal modeling', 'validate_GroupViTVisionConfig': 'validate GroupViTVisionConfig architecture by checking num_hidden_layers matches sum of depths', 'initialize_GroupViTConfig_from_dicts': 'initialize GroupViTConfig from text_config_dict and vision_config_dict with conflict resolution logging'}
```

## File: huggingface_transformers/src/transformers/models/groupvit/convert_groupvit_nvlab_to_hf.py

Prompts

```
['create a GroupViTTextConfig with default text model settings for initializing a GroupViT text encoder', 'create a GroupViTVisionConfig with default vision model settings including depths and group tokens', 'create a GroupViTConfig combining text and vision sub-configs with projection dimensions for multimodal modeling', 'validate GroupViTVisionConfig architecture by checking num_hidden_layers matches sum of depths', 'initialize GroupViTConfig from text_config_dict and vision_config_dict with conflict resolution logging', 'convert a GroupViT checkpoint from NVlabs to HuggingFace Transformers format and save locally', 'convert a GroupViT state dict from NVlabs naming to HuggingFace naming conventions', 'rename a GroupViT checkpoint key from NVlabs to HuggingFace Transformers naming scheme', 'prepare a sample cat image from COCO dataset for verifying the converted GroupViT model', 'run the GroupViT checkpoint conversion script via argparse CLI with checkpoint path and output folder', 'create a GroupViTModel instance for image-text retrieval with segmentation support', 'run the GroupViTModel forward pass to compute image-text similarity logits and contrastive loss', 'get image features from GroupViTModel by projecting vision encoder pooled output', 'get text features from GroupViTModel by projecting text encoder pooled output', 'test the image_text_contrastive_loss function that computes bidirectional image-text contrastive loss']
```

Usage

```
{'convert_groupvit_checkpoint': 'convert a GroupViT checkpoint from NVlabs to HuggingFace Transformers format and save locally', 'convert_state_dict': 'convert a GroupViT state dict from NVlabs naming to HuggingFace naming conventions', 'rename_key': 'rename a GroupViT checkpoint key from NVlabs to HuggingFace Transformers naming scheme', 'prepare_img': 'prepare a sample cat image from COCO dataset for verifying the converted GroupViT model', 'run_convert_cli': 'run the GroupViT checkpoint conversion script via argparse CLI with checkpoint path and output folder'}
```

## File: huggingface_transformers/src/transformers/models/groupvit/modeling_groupvit.py

Prompts

```
['create a GroupViTTextConfig with default text model settings for initializing a GroupViT text encoder', 'create a GroupViTVisionConfig with default vision model settings including depths and group tokens', 'create a GroupViTConfig combining text and vision sub-configs with projection dimensions for multimodal modeling', 'validate GroupViTVisionConfig architecture by checking num_hidden_layers matches sum of depths', 'initialize GroupViTConfig from text_config_dict and vision_config_dict with conflict resolution logging', 'convert a GroupViT checkpoint from NVlabs to HuggingFace Transformers format and save locally', 'convert a GroupViT state dict from NVlabs naming to HuggingFace naming conventions', 'rename a GroupViT checkpoint key from NVlabs to HuggingFace Transformers naming scheme', 'prepare a sample cat image from COCO dataset for verifying the converted GroupViT model', 'run the GroupViT checkpoint conversion script via argparse CLI with checkpoint path and output folder', 'create a GroupViTModel instance for image-text retrieval with segmentation support', 'run the GroupViTModel forward pass to compute image-text similarity logits and contrastive loss', 'get image features from GroupViTModel by projecting vision encoder pooled output', 'get text features from GroupViTModel by projecting text encoder pooled output', 'test the image_text_contrastive_loss function that computes bidirectional image-text contrastive loss']
```

Usage

```
{'create_GroupViTModel': 'create a GroupViTModel instance for image-text retrieval with segmentation support', 'run_GroupViTModel_forward': 'run the GroupViTModel forward pass to compute image-text similarity logits and contrastive loss', 'get_GroupViTModel_image_features': 'get image features from GroupViTModel by projecting vision encoder pooled output', 'get_GroupViTModel_text_features': 'get text features from GroupViTModel by projecting text encoder pooled output', 'test_image_text_contrastive_loss': 'test the image_text_contrastive_loss function that computes bidirectional image-text contrastive loss'}
```

