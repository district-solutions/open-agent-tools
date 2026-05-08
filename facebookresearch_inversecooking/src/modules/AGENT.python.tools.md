# Agent Python Tools

- repo: facebookresearch/inversecooking
- repo_uri: https://github.com/facebookresearch/inversecooking

## File: facebookresearch_inversecooking/src/modules/encoder.py

Prompts

```
['build a CNN encoder using a pretrained ResNet model to extract image feature vectors', 'build an embedding-based label encoder that converts class indices into dense embeddings', 'test the EncoderCNN forward pass to extract features from input image tensors', 'test the EncoderLabels forward pass to encode class indices into embedding vectors', 'review the EncoderCNN forward method and its keep_cnn_gradients flag for gradient control', 'build a MultiheadAttention layer with a given embed_dim and num_heads for transformer models', 'run forward pass with query, key, value tensors to compute multi-head self-attention output and weights', 'test the in_proj_qkv method to project input into query, key, and value tensors', 'review the buffered_mask method that creates a causal mask for masking future timesteps', 'refactor the reorder_incremental_state method to reorder cached key-value states for beam search', 'build a transformer decoder model with configurable embedding size, vocab size, and number of layers', 'run the decoder forward pass with ingredient features, image features, and caption tokens', 'sample recipe tokens from the decoder using greedy or temperature-based sampling strategies', 'create sinusoidal positional embeddings for any sequence length using the get_embedding static method', 'create a decoder layer block with self-attention, cross-attention, and feed-forward sublayers', 'save a PyTorch model checkpoint with optimizer history and extra state to a file', "load a model's state dict from a checkpoint file and restore model parameters", 'load an ensemble of models from checkpoint files for inference with optional arg overrides', 'recursively convert all tensors in a state dict to a specified tensor type', 'replace non-padding symbols in a tensor with their position numbers for sequence modeling']
```

Usage

```
{'build_encoder_cnn': 'build a CNN encoder using a pretrained ResNet model to extract image feature vectors', 'build_encoder_labels': 'build an embedding-based label encoder that converts class indices into dense embeddings', 'test_encoder_cnn_forward': 'test the EncoderCNN forward pass to extract features from input image tensors', 'test_encoder_labels_forward': 'test the EncoderLabels forward pass to encode class indices into embedding vectors', 'review_encoder_cnn_gradients': 'review the EncoderCNN forward method and its keep_cnn_gradients flag for gradient control'}
```

## File: facebookresearch_inversecooking/src/modules/multihead_attention.py

Prompts

```
['build a CNN encoder using a pretrained ResNet model to extract image feature vectors', 'build an embedding-based label encoder that converts class indices into dense embeddings', 'test the EncoderCNN forward pass to extract features from input image tensors', 'test the EncoderLabels forward pass to encode class indices into embedding vectors', 'review the EncoderCNN forward method and its keep_cnn_gradients flag for gradient control', 'build a MultiheadAttention layer with a given embed_dim and num_heads for transformer models', 'run forward pass with query, key, value tensors to compute multi-head self-attention output and weights', 'test the in_proj_qkv method to project input into query, key, and value tensors', 'review the buffered_mask method that creates a causal mask for masking future timesteps', 'refactor the reorder_incremental_state method to reorder cached key-value states for beam search', 'build a transformer decoder model with configurable embedding size, vocab size, and number of layers', 'run the decoder forward pass with ingredient features, image features, and caption tokens', 'sample recipe tokens from the decoder using greedy or temperature-based sampling strategies', 'create sinusoidal positional embeddings for any sequence length using the get_embedding static method', 'create a decoder layer block with self-attention, cross-attention, and feed-forward sublayers', 'save a PyTorch model checkpoint with optimizer history and extra state to a file', "load a model's state dict from a checkpoint file and restore model parameters", 'load an ensemble of models from checkpoint files for inference with optional arg overrides', 'recursively convert all tensors in a state dict to a specified tensor type', 'replace non-padding symbols in a tensor with their position numbers for sequence modeling']
```

Usage

```
{'build_multihead_attention_layer': 'build a MultiheadAttention layer with a given embed_dim and num_heads for transformer models', 'run_forward_self_attention': 'run forward pass with query, key, value tensors to compute multi-head self-attention output and weights', 'test_in_proj_qkv': 'test the in_proj_qkv method to project input into query, key, and value tensors', 'review_buffered_mask': 'review the buffered_mask method that creates a causal mask for masking future timesteps', 'refactor_reorder_incremental_state': 'refactor the reorder_incremental_state method to reorder cached key-value states for beam search'}
```

## File: facebookresearch_inversecooking/src/modules/transformer_decoder.py

Prompts

```
['build a CNN encoder using a pretrained ResNet model to extract image feature vectors', 'build an embedding-based label encoder that converts class indices into dense embeddings', 'test the EncoderCNN forward pass to extract features from input image tensors', 'test the EncoderLabels forward pass to encode class indices into embedding vectors', 'review the EncoderCNN forward method and its keep_cnn_gradients flag for gradient control', 'build a MultiheadAttention layer with a given embed_dim and num_heads for transformer models', 'run forward pass with query, key, value tensors to compute multi-head self-attention output and weights', 'test the in_proj_qkv method to project input into query, key, and value tensors', 'review the buffered_mask method that creates a causal mask for masking future timesteps', 'refactor the reorder_incremental_state method to reorder cached key-value states for beam search', 'build a transformer decoder model with configurable embedding size, vocab size, and number of layers', 'run the decoder forward pass with ingredient features, image features, and caption tokens', 'sample recipe tokens from the decoder using greedy or temperature-based sampling strategies', 'create sinusoidal positional embeddings for any sequence length using the get_embedding static method', 'create a decoder layer block with self-attention, cross-attention, and feed-forward sublayers', 'save a PyTorch model checkpoint with optimizer history and extra state to a file', "load a model's state dict from a checkpoint file and restore model parameters", 'load an ensemble of models from checkpoint files for inference with optional arg overrides', 'recursively convert all tensors in a state dict to a specified tensor type', 'replace non-padding symbols in a tensor with their position numbers for sequence modeling']
```

Usage

```
{'build_DecoderTransformer': 'build a transformer decoder model with configurable embedding size, vocab size, and number of layers', 'run_DecoderTransformer_forward': 'run the decoder forward pass with ingredient features, image features, and caption tokens', 'run_DecoderTransformer_sample': 'sample recipe tokens from the decoder using greedy or temperature-based sampling strategies', 'create_SinusoidalPositionalEmbedding': 'create sinusoidal positional embeddings for any sequence length using the get_embedding static method', 'create_TransformerDecoderLayer': 'create a decoder layer block with self-attention, cross-attention, and feed-forward sublayers'}
```

## File: facebookresearch_inversecooking/src/modules/utils.py

Prompts

```
['build a CNN encoder using a pretrained ResNet model to extract image feature vectors', 'build an embedding-based label encoder that converts class indices into dense embeddings', 'test the EncoderCNN forward pass to extract features from input image tensors', 'test the EncoderLabels forward pass to encode class indices into embedding vectors', 'review the EncoderCNN forward method and its keep_cnn_gradients flag for gradient control', 'build a MultiheadAttention layer with a given embed_dim and num_heads for transformer models', 'run forward pass with query, key, value tensors to compute multi-head self-attention output and weights', 'test the in_proj_qkv method to project input into query, key, and value tensors', 'review the buffered_mask method that creates a causal mask for masking future timesteps', 'refactor the reorder_incremental_state method to reorder cached key-value states for beam search', 'build a transformer decoder model with configurable embedding size, vocab size, and number of layers', 'run the decoder forward pass with ingredient features, image features, and caption tokens', 'sample recipe tokens from the decoder using greedy or temperature-based sampling strategies', 'create sinusoidal positional embeddings for any sequence length using the get_embedding static method', 'create a decoder layer block with self-attention, cross-attention, and feed-forward sublayers', 'save a PyTorch model checkpoint with optimizer history and extra state to a file', "load a model's state dict from a checkpoint file and restore model parameters", 'load an ensemble of models from checkpoint files for inference with optional arg overrides', 'recursively convert all tensors in a state dict to a specified tensor type', 'replace non-padding symbols in a tensor with their position numbers for sequence modeling']
```

Usage

```
{'save_model_checkpoint': 'save a PyTorch model checkpoint with optimizer history and extra state to a file', 'load_model_state': "load a model's state dict from a checkpoint file and restore model parameters", 'load_ensemble_for_inference': 'load an ensemble of models from checkpoint files for inference with optional arg overrides', 'convert_state_dict_type': 'recursively convert all tensors in a state dict to a specified tensor type', 'make_positions': 'replace non-padding symbols in a tensor with their position numbers for sequence modeling'}
```

