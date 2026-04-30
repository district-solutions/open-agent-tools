# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/aimv2/convert_aimv2_original_pytorch_to_hf.py

Prompts

```
['convert an Apple AIMV2 model checkpoint from Hugging Face Hub to Hugging Face transformers format and save locally', 'convert an AIMV2 vision-only model checkpoint without text encoder to Hugging Face transformers format', 'convert an AIMV2 model checkpoint to Hugging Face format and push the converted model and processor to the Hugging Face Hub', 'convert AIMV2 model state dict by splitting fused qkv tensors into separate q_proj, k_proj, and v_proj tensors', 'convert AIMV2 original state dict keys to Hugging Face key naming convention using regex-based key mapping', 'run AIMv2 model to compute image-text similarity scores and embeddings', 'get image features from AIMv2 vision model using pixel values', 'get text features from AIMv2 text model using input ids and attention mask', 'build 2D sinusoidal cosine position embedding for vision model patches', 'create an AIMv2 encoder layer with attention, MLP, and RMS normalization', 'build an Aimv2Model for vision-language tasks with image-text similarity scoring', 'create an Aimv2VisionModel to extract image embeddings from pixel values', 'create an Aimv2TextModel to extract text embeddings from input token IDs', 'build an Aimv2AttentionPoolingHead to pool image features via attention over a learnable CLS token', 'review the Aimv2Model forward method that computes image-text logits with normalized embeddings and learnable logit scale']
```

Usage

```
{'convert_aimv2_checkpoint_to_hf': 'convert an Apple AIMV2 model checkpoint from Hugging Face Hub to Hugging Face transformers format and save locally', 'convert_aimv2_vision_checkpoint': 'convert an AIMV2 vision-only model checkpoint without text encoder to Hugging Face transformers format', 'convert_aimv2_checkpoint_push_hub': 'convert an AIMV2 model checkpoint to Hugging Face format and push the converted model and processor to the Hugging Face Hub', 'convert_aimv2_qkv_tensors': 'convert AIMV2 model state dict by splitting fused qkv tensors into separate q_proj, k_proj, and v_proj tensors', 'convert_aimv2_rename_keys': 'convert AIMV2 original state dict keys to Hugging Face key naming convention using regex-based key mapping'}
```

## File: huggingface_transformers/src/transformers/models/aimv2/modeling_aimv2.py

Prompts

```
['convert an Apple AIMV2 model checkpoint from Hugging Face Hub to Hugging Face transformers format and save locally', 'convert an AIMV2 vision-only model checkpoint without text encoder to Hugging Face transformers format', 'convert an AIMV2 model checkpoint to Hugging Face format and push the converted model and processor to the Hugging Face Hub', 'convert AIMV2 model state dict by splitting fused qkv tensors into separate q_proj, k_proj, and v_proj tensors', 'convert AIMV2 original state dict keys to Hugging Face key naming convention using regex-based key mapping', 'run AIMv2 model to compute image-text similarity scores and embeddings', 'get image features from AIMv2 vision model using pixel values', 'get text features from AIMv2 text model using input ids and attention mask', 'build 2D sinusoidal cosine position embedding for vision model patches', 'create an AIMv2 encoder layer with attention, MLP, and RMS normalization', 'build an Aimv2Model for vision-language tasks with image-text similarity scoring', 'create an Aimv2VisionModel to extract image embeddings from pixel values', 'create an Aimv2TextModel to extract text embeddings from input token IDs', 'build an Aimv2AttentionPoolingHead to pool image features via attention over a learnable CLS token', 'review the Aimv2Model forward method that computes image-text logits with normalized embeddings and learnable logit scale']
```

Usage

```
{'run_aimv2_model': 'run AIMv2 model to compute image-text similarity scores and embeddings', 'get_image_features': 'get image features from AIMv2 vision model using pixel values', 'get_text_features': 'get text features from AIMv2 text model using input ids and attention mask', 'build_2d_sincos_position_embedding': 'build 2D sinusoidal cosine position embedding for vision model patches', 'create_aimv2_encoder_layer': 'create an AIMv2 encoder layer with attention, MLP, and RMS normalization'}
```

## File: huggingface_transformers/src/transformers/models/aimv2/modular_aimv2.py

Prompts

```
['convert an Apple AIMV2 model checkpoint from Hugging Face Hub to Hugging Face transformers format and save locally', 'convert an AIMV2 vision-only model checkpoint without text encoder to Hugging Face transformers format', 'convert an AIMV2 model checkpoint to Hugging Face format and push the converted model and processor to the Hugging Face Hub', 'convert AIMV2 model state dict by splitting fused qkv tensors into separate q_proj, k_proj, and v_proj tensors', 'convert AIMV2 original state dict keys to Hugging Face key naming convention using regex-based key mapping', 'run AIMv2 model to compute image-text similarity scores and embeddings', 'get image features from AIMv2 vision model using pixel values', 'get text features from AIMv2 text model using input ids and attention mask', 'build 2D sinusoidal cosine position embedding for vision model patches', 'create an AIMv2 encoder layer with attention, MLP, and RMS normalization', 'build an Aimv2Model for vision-language tasks with image-text similarity scoring', 'create an Aimv2VisionModel to extract image embeddings from pixel values', 'create an Aimv2TextModel to extract text embeddings from input token IDs', 'build an Aimv2AttentionPoolingHead to pool image features via attention over a learnable CLS token', 'review the Aimv2Model forward method that computes image-text logits with normalized embeddings and learnable logit scale']
```

Usage

```
{'build_aimv2_model': 'build an Aimv2Model for vision-language tasks with image-text similarity scoring', 'create_aimv2_vision_model': 'create an Aimv2VisionModel to extract image embeddings from pixel values', 'create_aimv2_text_model': 'create an Aimv2TextModel to extract text embeddings from input token IDs', 'build_aimv2_attention_pooling_head': 'build an Aimv2AttentionPoolingHead to pool image features via attention over a learnable CLS token', 'review_aimv2_forward': 'review the Aimv2Model forward method that computes image-text logits with normalized embeddings and learnable logit scale'}
```

