# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/align/convert_align_tf_to_hf.py

Prompts

```
['run the convert_align_checkpoint function to convert a TensorFlow ALIGN checkpoint to PyTorch HuggingFace format', 'build an AlignConfig with EfficientNet-B7 vision encoder and BERT text encoder for the ALIGN multimodal model', 'build an AlignProcessor with EfficientNetImageProcessor and BertTokenizer for ALIGN image-text preprocessing', 'test the rename_keys function to map TensorFlow parameter names to HuggingFace PyTorch parameter names', 'review the replace_params function to copy TensorFlow weights into HuggingFace model state dict with proper tensor permutation', 'run the ALIGN model forward pass to compute image-text similarity logits and contrastive loss', 'create text embeddings from input token IDs using the ALIGN text model with projection', 'create image embeddings from pixel values using the ALIGN vision model', 'build an ALIGN vision encoder with EfficientNet-style blocks for image feature extraction', 'build an ALIGN text encoder with BERT-style self-attention layers for text feature extraction']
```

Usage

```
{'run_convert_align_checkpoint': 'run the convert_align_checkpoint function to convert a TensorFlow ALIGN checkpoint to PyTorch HuggingFace format', 'build_align_config': 'build an AlignConfig with EfficientNet-B7 vision encoder and BERT text encoder for the ALIGN multimodal model', 'build_align_processor': 'build an AlignProcessor with EfficientNetImageProcessor and BertTokenizer for ALIGN image-text preprocessing', 'test_rename_keys': 'test the rename_keys function to map TensorFlow parameter names to HuggingFace PyTorch parameter names', 'review_replace_params': 'review the replace_params function to copy TensorFlow weights into HuggingFace model state dict with proper tensor permutation'}
```

## File: huggingface_transformers/src/transformers/models/align/modeling_align.py

Prompts

```
['run the convert_align_checkpoint function to convert a TensorFlow ALIGN checkpoint to PyTorch HuggingFace format', 'build an AlignConfig with EfficientNet-B7 vision encoder and BERT text encoder for the ALIGN multimodal model', 'build an AlignProcessor with EfficientNetImageProcessor and BertTokenizer for ALIGN image-text preprocessing', 'test the rename_keys function to map TensorFlow parameter names to HuggingFace PyTorch parameter names', 'review the replace_params function to copy TensorFlow weights into HuggingFace model state dict with proper tensor permutation', 'run the ALIGN model forward pass to compute image-text similarity logits and contrastive loss', 'create text embeddings from input token IDs using the ALIGN text model with projection', 'create image embeddings from pixel values using the ALIGN vision model', 'build an ALIGN vision encoder with EfficientNet-style blocks for image feature extraction', 'build an ALIGN text encoder with BERT-style self-attention layers for text feature extraction']
```

Usage

```
{'run_ALIGNModel_forward': 'run the ALIGN model forward pass to compute image-text similarity logits and contrastive loss', 'create_get_text_features': 'create text embeddings from input token IDs using the ALIGN text model with projection', 'create_get_image_features': 'create image embeddings from pixel values using the ALIGN vision model', 'build_ALIGNVisionModel': 'build an ALIGN vision encoder with EfficientNet-style blocks for image feature extraction', 'build_ALIGNTextModel': 'build an ALIGN text encoder with BERT-style self-attention layers for text feature extraction'}
```

