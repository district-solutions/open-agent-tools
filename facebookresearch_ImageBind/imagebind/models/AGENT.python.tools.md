# Agent Python Tools

- repo: facebookresearch/ImageBind
- repo_uri: https://github.com/facebookresearch/ImageBind.git

## File: facebookresearch_ImageBind/imagebind/models/helpers.py

Prompts

```
['build a PyTorch module that L2-normalizes a tensor along a specified dimension', 'build a learnable logit scaling module with configurable init value and max cap', 'build a PyTorch module that wraps einops rearrange with a fixed expression string', 'build a QuickGELU activation module using the x * sigmoid(1.702 * x) approximation', 'build a text pooling module that selects EOS token features and projects them', 'create an ImageBind huge model with pretrained weights for multimodal embedding', 'create an ImageBindModel instance with custom embed dimensions and transformer block configurations', 'run the ImageBindModel forward pass with a dictionary of modality inputs like vision and text', 'review the ImageBindModel modality preprocessors for vision text audio depth thermal and imu', 'review the ImageBindModel modality heads that project each modality to a shared output embedding space', 'create a SimpleTokenizer from a BPE merges file to encode and decode text into token IDs', 'build a TextPreprocessor module with token embedding, positional encoding, and optional causal masking for text inputs', 'create an RGBDTPreprocessor to tokenize RGB and depth vision inputs with patch embedding and positional encoding', 'create an IMUPreprocessor to patchify and tokenize IMU sensor data with positional and class tokens', 'build a causal attention mask tensor for transformer models with a given context length', 'build a multi-head attention module with configurable heads, dropout, and QKV bias', 'build a two-layer MLP with GELU activation and configurable dropout rate', 'build a transformer block supporting masked attention, DropPath, and LayerScale', 'build a transformer with progressive DropPath, LayerScale, and gradient checkpointing support', 'review the ViTAttention class that extends Attention and asserts no attention mask is used']
```

Usage

```
{'build_normalize_module': 'build a PyTorch module that L2-normalizes a tensor along a specified dimension', 'build_learnable_logit_scaling': 'build a learnable logit scaling module with configurable init value and max cap', 'build_einops_rearrange_module': 'build a PyTorch module that wraps einops rearrange with a fixed expression string', 'build_quick_gelu_activation': 'build a QuickGELU activation module using the x * sigmoid(1.702 * x) approximation', 'build_select_eos_and_project': 'build a text pooling module that selects EOS token features and projects them'}
```

## File: facebookresearch_ImageBind/imagebind/models/imagebind_model.py

Prompts

```
['build a PyTorch module that L2-normalizes a tensor along a specified dimension', 'build a learnable logit scaling module with configurable init value and max cap', 'build a PyTorch module that wraps einops rearrange with a fixed expression string', 'build a QuickGELU activation module using the x * sigmoid(1.702 * x) approximation', 'build a text pooling module that selects EOS token features and projects them', 'create an ImageBind huge model with pretrained weights for multimodal embedding', 'create an ImageBindModel instance with custom embed dimensions and transformer block configurations', 'run the ImageBindModel forward pass with a dictionary of modality inputs like vision and text', 'review the ImageBindModel modality preprocessors for vision text audio depth thermal and imu', 'review the ImageBindModel modality heads that project each modality to a shared output embedding space', 'create a SimpleTokenizer from a BPE merges file to encode and decode text into token IDs', 'build a TextPreprocessor module with token embedding, positional encoding, and optional causal masking for text inputs', 'create an RGBDTPreprocessor to tokenize RGB and depth vision inputs with patch embedding and positional encoding', 'create an IMUPreprocessor to patchify and tokenize IMU sensor data with positional and class tokens', 'build a causal attention mask tensor for transformer models with a given context length', 'build a multi-head attention module with configurable heads, dropout, and QKV bias', 'build a two-layer MLP with GELU activation and configurable dropout rate', 'build a transformer block supporting masked attention, DropPath, and LayerScale', 'build a transformer with progressive DropPath, LayerScale, and gradient checkpointing support', 'review the ViTAttention class that extends Attention and asserts no attention mask is used']
```

Usage

```
{'create_imagebind_huge_model': 'create an ImageBind huge model with pretrained weights for multimodal embedding', 'create_imagebind_model': 'create an ImageBindModel instance with custom embed dimensions and transformer block configurations', 'run_forward_multimodal': 'run the ImageBindModel forward pass with a dictionary of modality inputs like vision and text', 'review_modality_preprocessors': 'review the ImageBindModel modality preprocessors for vision text audio depth thermal and imu', 'review_modality_heads': 'review the ImageBindModel modality heads that project each modality to a shared output embedding space'}
```

## File: facebookresearch_ImageBind/imagebind/models/multimodal_preprocessors.py

Prompts

```
['build a PyTorch module that L2-normalizes a tensor along a specified dimension', 'build a learnable logit scaling module with configurable init value and max cap', 'build a PyTorch module that wraps einops rearrange with a fixed expression string', 'build a QuickGELU activation module using the x * sigmoid(1.702 * x) approximation', 'build a text pooling module that selects EOS token features and projects them', 'create an ImageBind huge model with pretrained weights for multimodal embedding', 'create an ImageBindModel instance with custom embed dimensions and transformer block configurations', 'run the ImageBindModel forward pass with a dictionary of modality inputs like vision and text', 'review the ImageBindModel modality preprocessors for vision text audio depth thermal and imu', 'review the ImageBindModel modality heads that project each modality to a shared output embedding space', 'create a SimpleTokenizer from a BPE merges file to encode and decode text into token IDs', 'build a TextPreprocessor module with token embedding, positional encoding, and optional causal masking for text inputs', 'create an RGBDTPreprocessor to tokenize RGB and depth vision inputs with patch embedding and positional encoding', 'create an IMUPreprocessor to patchify and tokenize IMU sensor data with positional and class tokens', 'build a causal attention mask tensor for transformer models with a given context length', 'build a multi-head attention module with configurable heads, dropout, and QKV bias', 'build a two-layer MLP with GELU activation and configurable dropout rate', 'build a transformer block supporting masked attention, DropPath, and LayerScale', 'build a transformer with progressive DropPath, LayerScale, and gradient checkpointing support', 'review the ViTAttention class that extends Attention and asserts no attention mask is used']
```

Usage

```
{'create_simple_tokenizer': 'create a SimpleTokenizer from a BPE merges file to encode and decode text into token IDs', 'build_text_preprocessor': 'build a TextPreprocessor module with token embedding, positional encoding, and optional causal masking for text inputs', 'create_rgbdt_preprocessor': 'create an RGBDTPreprocessor to tokenize RGB and depth vision inputs with patch embedding and positional encoding', 'create_imu_preprocessor': 'create an IMUPreprocessor to patchify and tokenize IMU sensor data with positional and class tokens', 'build_causal_attention_mask': 'build a causal attention mask tensor for transformer models with a given context length'}
```

## File: facebookresearch_ImageBind/imagebind/models/transformer.py

Prompts

```
['build a PyTorch module that L2-normalizes a tensor along a specified dimension', 'build a learnable logit scaling module with configurable init value and max cap', 'build a PyTorch module that wraps einops rearrange with a fixed expression string', 'build a QuickGELU activation module using the x * sigmoid(1.702 * x) approximation', 'build a text pooling module that selects EOS token features and projects them', 'create an ImageBind huge model with pretrained weights for multimodal embedding', 'create an ImageBindModel instance with custom embed dimensions and transformer block configurations', 'run the ImageBindModel forward pass with a dictionary of modality inputs like vision and text', 'review the ImageBindModel modality preprocessors for vision text audio depth thermal and imu', 'review the ImageBindModel modality heads that project each modality to a shared output embedding space', 'create a SimpleTokenizer from a BPE merges file to encode and decode text into token IDs', 'build a TextPreprocessor module with token embedding, positional encoding, and optional causal masking for text inputs', 'create an RGBDTPreprocessor to tokenize RGB and depth vision inputs with patch embedding and positional encoding', 'create an IMUPreprocessor to patchify and tokenize IMU sensor data with positional and class tokens', 'build a causal attention mask tensor for transformer models with a given context length', 'build a multi-head attention module with configurable heads, dropout, and QKV bias', 'build a two-layer MLP with GELU activation and configurable dropout rate', 'build a transformer block supporting masked attention, DropPath, and LayerScale', 'build a transformer with progressive DropPath, LayerScale, and gradient checkpointing support', 'review the ViTAttention class that extends Attention and asserts no attention mask is used']
```

Usage

```
{'build_attention_module': 'build a multi-head attention module with configurable heads, dropout, and QKV bias', 'build_mlp_module': 'build a two-layer MLP with GELU activation and configurable dropout rate', 'build_block_with_masking': 'build a transformer block supporting masked attention, DropPath, and LayerScale', 'build_simple_transformer': 'build a transformer with progressive DropPath, LayerScale, and gradient checkpointing support', 'review_vit_attention': 'review the ViTAttention class that extends Attention and asserts no attention mask is used'}
```

