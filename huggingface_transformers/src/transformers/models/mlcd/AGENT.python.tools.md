# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/mlcd/convert_mlcd_weights_to_hf.py

Prompts

```
['convert MLCD model weights from original checkpoint to HuggingFace format', 'create MLCDVisionConfig for a specified model name with hidden size and layer parameters', 'create CLIPImageProcessor for MLCD model with normalization and resizing settings', 'rename state dict keys from original MLCD format to HuggingFace model naming convention', 'flatten a nested checkpoint dictionary into a flat key-value dictionary', 'build an MLCDVisionModel from pretrained weights for image feature extraction with RoPE attention', 'run the MLCDVisionModel forward pass on pixel values to extract pooled and sequence features', 'configure an MLCDAttention module with multi-head attention and rotary position embeddings', 'test the MLCDEncoder forward pass on embedded inputs with position embeddings and attention masks', 'review the MLCDPreTrainedModel _init_weights method for initializing vision model parameters', 'create an MLCDVisionModel from MLCDVisionConfig for vision feature extraction', 'build an MLCDVisionConfig with custom hidden size, layers, and attention heads for MLCD vision model', 'run MLCDVisionModel forward pass on pixel values to extract image embeddings with RoPE', 'initialize MLCDPreTrainedModel weights for embeddings, attention, MLP, and rotary embedding layers', 'test MLCDEncoder forward pass with hidden states and rotary position embeddings']
```

Usage

```
{'convert_mlcd_checkpoint': 'convert MLCD model weights from original checkpoint to HuggingFace format', 'get_mlcd_config': 'create MLCDVisionConfig for a specified model name with hidden size and layer parameters', 'get_mlcd_image_processor': 'create CLIPImageProcessor for MLCD model with normalization and resizing settings', 'convert_old_keys_to_new_keys': 'rename state dict keys from original MLCD format to HuggingFace model naming convention', 'flatten_nested_dict': 'flatten a nested checkpoint dictionary into a flat key-value dictionary'}
```

## File: huggingface_transformers/src/transformers/models/mlcd/modeling_mlcd.py

Prompts

```
['convert MLCD model weights from original checkpoint to HuggingFace format', 'create MLCDVisionConfig for a specified model name with hidden size and layer parameters', 'create CLIPImageProcessor for MLCD model with normalization and resizing settings', 'rename state dict keys from original MLCD format to HuggingFace model naming convention', 'flatten a nested checkpoint dictionary into a flat key-value dictionary', 'build an MLCDVisionModel from pretrained weights for image feature extraction with RoPE attention', 'run the MLCDVisionModel forward pass on pixel values to extract pooled and sequence features', 'configure an MLCDAttention module with multi-head attention and rotary position embeddings', 'test the MLCDEncoder forward pass on embedded inputs with position embeddings and attention masks', 'review the MLCDPreTrainedModel _init_weights method for initializing vision model parameters', 'create an MLCDVisionModel from MLCDVisionConfig for vision feature extraction', 'build an MLCDVisionConfig with custom hidden size, layers, and attention heads for MLCD vision model', 'run MLCDVisionModel forward pass on pixel values to extract image embeddings with RoPE', 'initialize MLCDPreTrainedModel weights for embeddings, attention, MLP, and rotary embedding layers', 'test MLCDEncoder forward pass with hidden states and rotary position embeddings']
```

Usage

```
{'build_MLCDVisionModel': 'build an MLCDVisionModel from pretrained weights for image feature extraction with RoPE attention', 'run_MLCDVisionModel_forward': 'run the MLCDVisionModel forward pass on pixel values to extract pooled and sequence features', 'configure_MLCDAttention': 'configure an MLCDAttention module with multi-head attention and rotary position embeddings', 'test_MLCDEncoder_forward': 'test the MLCDEncoder forward pass on embedded inputs with position embeddings and attention masks', 'review_MLCDPreTrainedModel_init': 'review the MLCDPreTrainedModel _init_weights method for initializing vision model parameters'}
```

## File: huggingface_transformers/src/transformers/models/mlcd/modular_mlcd.py

Prompts

```
['convert MLCD model weights from original checkpoint to HuggingFace format', 'create MLCDVisionConfig for a specified model name with hidden size and layer parameters', 'create CLIPImageProcessor for MLCD model with normalization and resizing settings', 'rename state dict keys from original MLCD format to HuggingFace model naming convention', 'flatten a nested checkpoint dictionary into a flat key-value dictionary', 'build an MLCDVisionModel from pretrained weights for image feature extraction with RoPE attention', 'run the MLCDVisionModel forward pass on pixel values to extract pooled and sequence features', 'configure an MLCDAttention module with multi-head attention and rotary position embeddings', 'test the MLCDEncoder forward pass on embedded inputs with position embeddings and attention masks', 'review the MLCDPreTrainedModel _init_weights method for initializing vision model parameters', 'create an MLCDVisionModel from MLCDVisionConfig for vision feature extraction', 'build an MLCDVisionConfig with custom hidden size, layers, and attention heads for MLCD vision model', 'run MLCDVisionModel forward pass on pixel values to extract image embeddings with RoPE', 'initialize MLCDPreTrainedModel weights for embeddings, attention, MLP, and rotary embedding layers', 'test MLCDEncoder forward pass with hidden states and rotary position embeddings']
```

Usage

```
{'create_mlcd_vision_model': 'create an MLCDVisionModel from MLCDVisionConfig for vision feature extraction', 'build_mlcd_vision_config': 'build an MLCDVisionConfig with custom hidden size, layers, and attention heads for MLCD vision model', 'run_mlcd_vision_forward': 'run MLCDVisionModel forward pass on pixel values to extract image embeddings with RoPE', 'initialize_mlcd_weights': 'initialize MLCDPreTrainedModel weights for embeddings, attention, MLP, and rotary embedding layers', 'test_mlcd_encoder_forward': 'test MLCDEncoder forward pass with hidden states and rotary position embeddings'}
```

