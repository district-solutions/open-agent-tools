# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/clip/configuration_clip.py

Prompts

```
['create a CLIPTextConfig instance with default text model settings for CLIP vision-language architecture', 'create a CLIPVisionConfig instance with default vision model settings for CLIP vision-language architecture', 'create a CLIPConfig instance combining text and vision configs for a complete CLIP model', 'initialize CLIPTextConfig with custom hidden size, layer count, and attention head parameters', 'validate CLIP text and vision config architecture ensuring hidden size is a multiple of attention heads', 'convert an OpenAI CLIP checkpoint to Hugging Face transformers format and save it', 'copy text encoder weights and projection matrix from OpenAI CLIP to a Hugging Face model', 'copy vision encoder weights and projection matrix from OpenAI CLIP to a Hugging Face model', 'copy transformer encoder layers, embeddings, and layer norms from OpenAI CLIP to Hugging Face', 'copy attention layer weights including q, k, v projections and output projection from OpenAI CLIP', 'create CLIP embeddings from images and text to compute cross-modal similarity scores', 'compute the bidirectional contrastive loss between image and text embeddings', 'run image classification using CLIP vision encoder with a linear classification head', 'get projected text embeddings from CLIP text model for downstream tasks', 'get projected image embeddings from CLIP vision model for downstream tasks', 'create a CLIPTokenizer instance with custom vocab and merges for byte-level BPE tokenization', 'build a CLIP tokenizer with NFC normalization, whitespace replacement, and lowercase processing', 'test the CLIPTokenizer pre-tokenizer with ByteLevel splitting and regex pattern matching', 'summarize the CLIPTokenizer decode method that strips end-of-word suffixes from decoded text', 'review the CLIPTokenizer post processor using RobertaProcessing with bos and eos tokens']
```

Usage

```
{'create_CLIPTextConfig': 'create a CLIPTextConfig instance with default text model settings for CLIP vision-language architecture', 'create_CLIPVisionConfig': 'create a CLIPVisionConfig instance with default vision model settings for CLIP vision-language architecture', 'create_CLIPConfig': 'create a CLIPConfig instance combining text and vision configs for a complete CLIP model', 'initialize_CLIPTextConfig_custom': 'initialize CLIPTextConfig with custom hidden size, layer count, and attention head parameters', 'validate_CLIPConfig_architecture': 'validate CLIP text and vision config architecture ensuring hidden size is a multiple of attention heads'}
```

## File: huggingface_transformers/src/transformers/models/clip/convert_clip_original_pytorch_to_hf.py

Prompts

```
['create a CLIPTextConfig instance with default text model settings for CLIP vision-language architecture', 'create a CLIPVisionConfig instance with default vision model settings for CLIP vision-language architecture', 'create a CLIPConfig instance combining text and vision configs for a complete CLIP model', 'initialize CLIPTextConfig with custom hidden size, layer count, and attention head parameters', 'validate CLIP text and vision config architecture ensuring hidden size is a multiple of attention heads', 'convert an OpenAI CLIP checkpoint to Hugging Face transformers format and save it', 'copy text encoder weights and projection matrix from OpenAI CLIP to a Hugging Face model', 'copy vision encoder weights and projection matrix from OpenAI CLIP to a Hugging Face model', 'copy transformer encoder layers, embeddings, and layer norms from OpenAI CLIP to Hugging Face', 'copy attention layer weights including q, k, v projections and output projection from OpenAI CLIP', 'create CLIP embeddings from images and text to compute cross-modal similarity scores', 'compute the bidirectional contrastive loss between image and text embeddings', 'run image classification using CLIP vision encoder with a linear classification head', 'get projected text embeddings from CLIP text model for downstream tasks', 'get projected image embeddings from CLIP vision model for downstream tasks', 'create a CLIPTokenizer instance with custom vocab and merges for byte-level BPE tokenization', 'build a CLIP tokenizer with NFC normalization, whitespace replacement, and lowercase processing', 'test the CLIPTokenizer pre-tokenizer with ByteLevel splitting and regex pattern matching', 'summarize the CLIPTokenizer decode method that strips end-of-word suffixes from decoded text', 'review the CLIPTokenizer post processor using RobertaProcessing with bos and eos tokens']
```

Usage

```
{'convert_clip_checkpoint': 'convert an OpenAI CLIP checkpoint to Hugging Face transformers format and save it', 'copy_text_model_and_projection': 'copy text encoder weights and projection matrix from OpenAI CLIP to a Hugging Face model', 'copy_vison_model_and_projection': 'copy vision encoder weights and projection matrix from OpenAI CLIP to a Hugging Face model', 'copy_encoder': 'copy transformer encoder layers, embeddings, and layer norms from OpenAI CLIP to Hugging Face', 'copy_attn_layer': 'copy attention layer weights including q, k, v projections and output projection from OpenAI CLIP'}
```

## File: huggingface_transformers/src/transformers/models/clip/modeling_clip.py

Prompts

```
['create a CLIPTextConfig instance with default text model settings for CLIP vision-language architecture', 'create a CLIPVisionConfig instance with default vision model settings for CLIP vision-language architecture', 'create a CLIPConfig instance combining text and vision configs for a complete CLIP model', 'initialize CLIPTextConfig with custom hidden size, layer count, and attention head parameters', 'validate CLIP text and vision config architecture ensuring hidden size is a multiple of attention heads', 'convert an OpenAI CLIP checkpoint to Hugging Face transformers format and save it', 'copy text encoder weights and projection matrix from OpenAI CLIP to a Hugging Face model', 'copy vision encoder weights and projection matrix from OpenAI CLIP to a Hugging Face model', 'copy transformer encoder layers, embeddings, and layer norms from OpenAI CLIP to Hugging Face', 'copy attention layer weights including q, k, v projections and output projection from OpenAI CLIP', 'create CLIP embeddings from images and text to compute cross-modal similarity scores', 'compute the bidirectional contrastive loss between image and text embeddings', 'run image classification using CLIP vision encoder with a linear classification head', 'get projected text embeddings from CLIP text model for downstream tasks', 'get projected image embeddings from CLIP vision model for downstream tasks', 'create a CLIPTokenizer instance with custom vocab and merges for byte-level BPE tokenization', 'build a CLIP tokenizer with NFC normalization, whitespace replacement, and lowercase processing', 'test the CLIPTokenizer pre-tokenizer with ByteLevel splitting and regex pattern matching', 'summarize the CLIPTokenizer decode method that strips end-of-word suffixes from decoded text', 'review the CLIPTokenizer post processor using RobertaProcessing with bos and eos tokens']
```

Usage

```
{'create_clip_image_text_embeddings': 'create CLIP embeddings from images and text to compute cross-modal similarity scores', 'compute_image_text_contrastive_loss': 'compute the bidirectional contrastive loss between image and text embeddings', 'run_image_classification': 'run image classification using CLIP vision encoder with a linear classification head', 'get_text_features_with_projection': 'get projected text embeddings from CLIP text model for downstream tasks', 'get_image_features_with_projection': 'get projected image embeddings from CLIP vision model for downstream tasks'}
```

## File: huggingface_transformers/src/transformers/models/clip/tokenization_clip.py

Prompts

```
['create a CLIPTextConfig instance with default text model settings for CLIP vision-language architecture', 'create a CLIPVisionConfig instance with default vision model settings for CLIP vision-language architecture', 'create a CLIPConfig instance combining text and vision configs for a complete CLIP model', 'initialize CLIPTextConfig with custom hidden size, layer count, and attention head parameters', 'validate CLIP text and vision config architecture ensuring hidden size is a multiple of attention heads', 'convert an OpenAI CLIP checkpoint to Hugging Face transformers format and save it', 'copy text encoder weights and projection matrix from OpenAI CLIP to a Hugging Face model', 'copy vision encoder weights and projection matrix from OpenAI CLIP to a Hugging Face model', 'copy transformer encoder layers, embeddings, and layer norms from OpenAI CLIP to Hugging Face', 'copy attention layer weights including q, k, v projections and output projection from OpenAI CLIP', 'create CLIP embeddings from images and text to compute cross-modal similarity scores', 'compute the bidirectional contrastive loss between image and text embeddings', 'run image classification using CLIP vision encoder with a linear classification head', 'get projected text embeddings from CLIP text model for downstream tasks', 'get projected image embeddings from CLIP vision model for downstream tasks', 'create a CLIPTokenizer instance with custom vocab and merges for byte-level BPE tokenization', 'build a CLIP tokenizer with NFC normalization, whitespace replacement, and lowercase processing', 'test the CLIPTokenizer pre-tokenizer with ByteLevel splitting and regex pattern matching', 'summarize the CLIPTokenizer decode method that strips end-of-word suffixes from decoded text', 'review the CLIPTokenizer post processor using RobertaProcessing with bos and eos tokens']
```

Usage

```
{'create_CLIPTokenizer': 'create a CLIPTokenizer instance with custom vocab and merges for byte-level BPE tokenization', 'build_CLIPTokenizer_normalizer': 'build a CLIP tokenizer with NFC normalization, whitespace replacement, and lowercase processing', 'test_CLIPTokenizer_pre_tokenizer': 'test the CLIPTokenizer pre-tokenizer with ByteLevel splitting and regex pattern matching', 'summarize_CLIPTokenizer_decode': 'summarize the CLIPTokenizer decode method that strips end-of-word suffixes from decoded text', 'review_CLIPTokenizer_post_processor': 'review the CLIPTokenizer post processor using RobertaProcessing with bos and eos tokens'}
```

