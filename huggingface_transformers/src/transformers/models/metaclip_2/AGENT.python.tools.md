# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/metaclip_2/configuration_metaclip_2.py

Prompts

```
['create a MetaClip2Config instance with default text and vision sub-configurations', 'build a MetaClip2TextConfig with custom hidden_size, num_hidden_layers, and num_attention_heads', 'build a MetaClip2VisionConfig with custom image_size, patch_size, and hidden_size', 'test MetaClip2TextConfig and MetaClip2VisionConfig validate that hidden_size is a multiple of num_attention_heads', 'create a MetaClip2Config initialized from separate MetaClip2TextConfig and MetaClip2VisionConfig instances', 'convert a MetaCLIP 2 checkpoint to Hugging Face format using the convert_metaclip_2_to_hf.py script', 'create a MetaClip2Config with vision and text config parameters from a MetaCLIP model name', 'convert a MetaCLIP state dict to Hugging Face format by mapping and splitting qkv projections', 'verify that a converted MetaCLIP 2 model produces matching outputs against the original checkpoint', 'push a converted MetaCLIP 2 model and processor to a Hugging Face Hub repository', 'build a MetaClip2Model for image-text contrastive retrieval with cosine similarity logits', 'create a MetaClip2TextModel that encodes text with causal attention and EOS-token pooling', 'create a MetaClip2VisionModel that encodes images with ViT-style patches and CLS pooling', 'run image classification with MetaClip2ForImageClassification using a classifier head on pooled vision features', 'get text and image embeddings from MetaClip2Model for contrastive similarity scoring', 'test the MetaClip2TextModel forward pass with input_ids, attention_mask, and position_ids', 'initialize MetaClip2 model weights using the _init_weights method with layer-specific std scaling']
```

Usage

```
{'create_config_metaclip2': 'create a MetaClip2Config instance with default text and vision sub-configurations', 'build_config_metaclip2_text': 'build a MetaClip2TextConfig with custom hidden_size, num_hidden_layers, and num_attention_heads', 'build_config_metaclip2_vision': 'build a MetaClip2VisionConfig with custom image_size, patch_size, and hidden_size', 'test_config_metaclip2_validation': 'test MetaClip2TextConfig and MetaClip2VisionConfig validate that hidden_size is a multiple of num_attention_heads', 'create_config_metaclip2_subconfigs': 'create a MetaClip2Config initialized from separate MetaClip2TextConfig and MetaClip2VisionConfig instances'}
```

## File: huggingface_transformers/src/transformers/models/metaclip_2/convert_metaclip_2_to_hf.py

Prompts

```
['create a MetaClip2Config instance with default text and vision sub-configurations', 'build a MetaClip2TextConfig with custom hidden_size, num_hidden_layers, and num_attention_heads', 'build a MetaClip2VisionConfig with custom image_size, patch_size, and hidden_size', 'test MetaClip2TextConfig and MetaClip2VisionConfig validate that hidden_size is a multiple of num_attention_heads', 'create a MetaClip2Config initialized from separate MetaClip2TextConfig and MetaClip2VisionConfig instances', 'convert a MetaCLIP 2 checkpoint to Hugging Face format using the convert_metaclip_2_to_hf.py script', 'create a MetaClip2Config with vision and text config parameters from a MetaCLIP model name', 'convert a MetaCLIP state dict to Hugging Face format by mapping and splitting qkv projections', 'verify that a converted MetaCLIP 2 model produces matching outputs against the original checkpoint', 'push a converted MetaCLIP 2 model and processor to a Hugging Face Hub repository', 'build a MetaClip2Model for image-text contrastive retrieval with cosine similarity logits', 'create a MetaClip2TextModel that encodes text with causal attention and EOS-token pooling', 'create a MetaClip2VisionModel that encodes images with ViT-style patches and CLS pooling', 'run image classification with MetaClip2ForImageClassification using a classifier head on pooled vision features', 'get text and image embeddings from MetaClip2Model for contrastive similarity scoring', 'test the MetaClip2TextModel forward pass with input_ids, attention_mask, and position_ids', 'initialize MetaClip2 model weights using the _init_weights method with layer-specific std scaling']
```

Usage

```
{'convert_metaclip2_checkpoint': 'convert a MetaCLIP 2 checkpoint to Hugging Face format using the convert_metaclip_2_to_hf.py script', 'create_hf_config': 'create a MetaClip2Config with vision and text config parameters from a MetaCLIP model name', 'convert_state_dict': 'convert a MetaCLIP state dict to Hugging Face format by mapping and splitting qkv projections', 'verify_conversion': 'verify that a converted MetaCLIP 2 model produces matching outputs against the original checkpoint', 'push_to_hub': 'push a converted MetaCLIP 2 model and processor to a Hugging Face Hub repository'}
```

## File: huggingface_transformers/src/transformers/models/metaclip_2/modeling_metaclip_2.py

Prompts

```
['create a MetaClip2Config instance with default text and vision sub-configurations', 'build a MetaClip2TextConfig with custom hidden_size, num_hidden_layers, and num_attention_heads', 'build a MetaClip2VisionConfig with custom image_size, patch_size, and hidden_size', 'test MetaClip2TextConfig and MetaClip2VisionConfig validate that hidden_size is a multiple of num_attention_heads', 'create a MetaClip2Config initialized from separate MetaClip2TextConfig and MetaClip2VisionConfig instances', 'convert a MetaCLIP 2 checkpoint to Hugging Face format using the convert_metaclip_2_to_hf.py script', 'create a MetaClip2Config with vision and text config parameters from a MetaCLIP model name', 'convert a MetaCLIP state dict to Hugging Face format by mapping and splitting qkv projections', 'verify that a converted MetaCLIP 2 model produces matching outputs against the original checkpoint', 'push a converted MetaCLIP 2 model and processor to a Hugging Face Hub repository', 'build a MetaClip2Model for image-text contrastive retrieval with cosine similarity logits', 'create a MetaClip2TextModel that encodes text with causal attention and EOS-token pooling', 'create a MetaClip2VisionModel that encodes images with ViT-style patches and CLS pooling', 'run image classification with MetaClip2ForImageClassification using a classifier head on pooled vision features', 'get text and image embeddings from MetaClip2Model for contrastive similarity scoring', 'test the MetaClip2TextModel forward pass with input_ids, attention_mask, and position_ids', 'initialize MetaClip2 model weights using the _init_weights method with layer-specific std scaling']
```

Usage

```
{'build_metaclip2_model': 'build a MetaClip2Model for image-text contrastive retrieval with cosine similarity logits', 'create_metaclip2_text_model': 'create a MetaClip2TextModel that encodes text with causal attention and EOS-token pooling', 'create_metaclip2_vision_model': 'create a MetaClip2VisionModel that encodes images with ViT-style patches and CLS pooling', 'run_image_classification': 'run image classification with MetaClip2ForImageClassification using a classifier head on pooled vision features', 'get_text_image_embeddings': 'get text and image embeddings from MetaClip2Model for contrastive similarity scoring'}
```

## File: huggingface_transformers/src/transformers/models/metaclip_2/modular_metaclip_2.py

Prompts

```
['create a MetaClip2Config instance with default text and vision sub-configurations', 'build a MetaClip2TextConfig with custom hidden_size, num_hidden_layers, and num_attention_heads', 'build a MetaClip2VisionConfig with custom image_size, patch_size, and hidden_size', 'test MetaClip2TextConfig and MetaClip2VisionConfig validate that hidden_size is a multiple of num_attention_heads', 'create a MetaClip2Config initialized from separate MetaClip2TextConfig and MetaClip2VisionConfig instances', 'convert a MetaCLIP 2 checkpoint to Hugging Face format using the convert_metaclip_2_to_hf.py script', 'create a MetaClip2Config with vision and text config parameters from a MetaCLIP model name', 'convert a MetaCLIP state dict to Hugging Face format by mapping and splitting qkv projections', 'verify that a converted MetaCLIP 2 model produces matching outputs against the original checkpoint', 'push a converted MetaCLIP 2 model and processor to a Hugging Face Hub repository', 'build a MetaClip2Model for image-text contrastive retrieval with cosine similarity logits', 'create a MetaClip2TextModel that encodes text with causal attention and EOS-token pooling', 'create a MetaClip2VisionModel that encodes images with ViT-style patches and CLS pooling', 'run image classification with MetaClip2ForImageClassification using a classifier head on pooled vision features', 'get text and image embeddings from MetaClip2Model for contrastive similarity scoring', 'test the MetaClip2TextModel forward pass with input_ids, attention_mask, and position_ids', 'initialize MetaClip2 model weights using the _init_weights method with layer-specific std scaling']
```

Usage

```
{'build_metaclip2_model': 'build a MetaClip2Model from a MetaClip2Config for image-text contrastive retrieval', 'create_metaclip2_text_model': 'create a MetaClip2TextModel that encodes text with causal attention and EOS-token pooling', 'create_metaclip2_vision_model': 'create a MetaClip2VisionModel that encodes images and returns pooled CLS output', 'test_metaclip2_text_forward': 'test the MetaClip2TextModel forward pass with input_ids, attention_mask, and position_ids', 'init_metaclip2_weights': 'initialize MetaClip2 model weights using the _init_weights method with layer-specific std scaling'}
```

