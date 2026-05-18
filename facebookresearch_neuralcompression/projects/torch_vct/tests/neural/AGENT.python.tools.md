# Agent Python Tools

- repo: facebookresearch/neuralcompression
- repo_uri: https://github.com/facebookresearch/neuralcompression

## File: facebookresearch_neuralcompression/projects/torch_vct/tests/neural/test_entropy_model_layers.py

Prompts

```
['test StartSym._shift_to_the_right to shift a tensor right and prefix with zeros or a custom prefix', 'test StartSym to prefix a sequence tensor with a learned start symbol parameter', 'test LearnedPosition to add learned positional encodings to a 3D input tensor', 'test TransformerBlock forward pass with self-attention and cross-attention on batched sequence data', 'test Transformer to stack multiple TransformerBlock layers for encoder or decoder use', 'test the MLP class forward pass with a 3D tensor of shape (batch, seq_len, in_features)', 'test the make_embedding function creates a Linear layer with uniformly initialized weights within scale bounds', 'test the WindowMultiHeadAttention class forward pass with query, key, value tensors and optional attention mask', 'review the MLP class that applies two linear layers with GELU activation and dropout for transformer blocks', 'review the WindowMultiHeadAttention class that computes windowed multi-head self-attention with masking support', 'test the Patcher class _pad method with various stride and patch_size configurations', 'test the Patcher class forward method to verify patch extraction produces correct tensor shapes', 'test the Patcher class unpatch method to verify roundtrip reconstruction when patch_size equals stride', 'create a Patcher instance with a given stride and pad_mode for tensor patching operations', 'review the Patcher class and its _pad, forward, and unpatch methods for tensor patching logic']
```

Usage

```
{'test_StartSym_shift_right': 'test StartSym._shift_to_the_right to shift a tensor right and prefix with zeros or a custom prefix', 'test_StartSym_learned_symbol': 'test StartSym to prefix a sequence tensor with a learned start symbol parameter', 'test_LearnedPosition_encoding': 'test LearnedPosition to add learned positional encodings to a 3D input tensor', 'test_TransformerBlock_forward': 'test TransformerBlock forward pass with self-attention and cross-attention on batched sequence data', 'test_Transformer_stack': 'test Transformer to stack multiple TransformerBlock layers for encoder or decoder use'}
```

## File: facebookresearch_neuralcompression/projects/torch_vct/tests/neural/test_layers_utils.py

Prompts

```
['test StartSym._shift_to_the_right to shift a tensor right and prefix with zeros or a custom prefix', 'test StartSym to prefix a sequence tensor with a learned start symbol parameter', 'test LearnedPosition to add learned positional encodings to a 3D input tensor', 'test TransformerBlock forward pass with self-attention and cross-attention on batched sequence data', 'test Transformer to stack multiple TransformerBlock layers for encoder or decoder use', 'test the MLP class forward pass with a 3D tensor of shape (batch, seq_len, in_features)', 'test the make_embedding function creates a Linear layer with uniformly initialized weights within scale bounds', 'test the WindowMultiHeadAttention class forward pass with query, key, value tensors and optional attention mask', 'review the MLP class that applies two linear layers with GELU activation and dropout for transformer blocks', 'review the WindowMultiHeadAttention class that computes windowed multi-head self-attention with masking support', 'test the Patcher class _pad method with various stride and patch_size configurations', 'test the Patcher class forward method to verify patch extraction produces correct tensor shapes', 'test the Patcher class unpatch method to verify roundtrip reconstruction when patch_size equals stride', 'create a Patcher instance with a given stride and pad_mode for tensor patching operations', 'review the Patcher class and its _pad, forward, and unpatch methods for tensor patching logic']
```

Usage

```
{'test_MLP': 'test the MLP class forward pass with a 3D tensor of shape (batch, seq_len, in_features)', 'test_make_embedding': 'test the make_embedding function creates a Linear layer with uniformly initialized weights within scale bounds', 'test_WindowMultiHeadAttention': 'test the WindowMultiHeadAttention class forward pass with query, key, value tensors and optional attention mask', 'review_MLP': 'review the MLP class that applies two linear layers with GELU activation and dropout for transformer blocks', 'review_WindowMultiHeadAttention': 'review the WindowMultiHeadAttention class that computes windowed multi-head self-attention with masking support'}
```

## File: facebookresearch_neuralcompression/projects/torch_vct/tests/neural/test_patcher.py

Prompts

```
['test StartSym._shift_to_the_right to shift a tensor right and prefix with zeros or a custom prefix', 'test StartSym to prefix a sequence tensor with a learned start symbol parameter', 'test LearnedPosition to add learned positional encodings to a 3D input tensor', 'test TransformerBlock forward pass with self-attention and cross-attention on batched sequence data', 'test Transformer to stack multiple TransformerBlock layers for encoder or decoder use', 'test the MLP class forward pass with a 3D tensor of shape (batch, seq_len, in_features)', 'test the make_embedding function creates a Linear layer with uniformly initialized weights within scale bounds', 'test the WindowMultiHeadAttention class forward pass with query, key, value tensors and optional attention mask', 'review the MLP class that applies two linear layers with GELU activation and dropout for transformer blocks', 'review the WindowMultiHeadAttention class that computes windowed multi-head self-attention with masking support', 'test the Patcher class _pad method with various stride and patch_size configurations', 'test the Patcher class forward method to verify patch extraction produces correct tensor shapes', 'test the Patcher class unpatch method to verify roundtrip reconstruction when patch_size equals stride', 'create a Patcher instance with a given stride and pad_mode for tensor patching operations', 'review the Patcher class and its _pad, forward, and unpatch methods for tensor patching logic']
```

Usage

```
{'test_Patcher_pad': 'test the Patcher class _pad method with various stride and patch_size configurations', 'test_Patcher_forward': 'test the Patcher class forward method to verify patch extraction produces correct tensor shapes', 'test_Patcher_unpatch': 'test the Patcher class unpatch method to verify roundtrip reconstruction when patch_size equals stride', 'create_Patcher_instance': 'create a Patcher instance with a given stride and pad_mode for tensor patching operations', 'review_Patcher_class': 'review the Patcher class and its _pad, forward, and unpatch methods for tensor patching logic'}
```

