# Agent Python Tools

- repo: facebookresearch/minihack
- repo_uri: https://github.com/facebookresearch/minihack

## File: facebookresearch_minihack/minihack/agent/common/models/dynamics.py

Prompts

```
['build a ForwardDynamicsNet module to predict next state embeddings from state and action inputs', 'build an InverseDynamicsNet module to predict action logits from state and next state embeddings', 'test the ForwardDynamicsNet forward method by passing state embeddings and action tensors', 'test the InverseDynamicsNet forward method by passing state and next state embedding tensors', 'review the ForwardDynamicsNet and InverseDynamicsNet classes for ELU activation and linear layer architecture', 'build a GlyphEmbedding module with a given glyph_type strategy and embedding dimension', 'prepare input dictionary into a GlyphTuple namedtuple for embedding lookup', 'run the forward pass to embed a GlyphTuple and return concatenated embedding vectors', 'convert glyph tensors into subgroup ids and group ids using the id_pairs_table', 'configure a Targets NamedTuple to select which glyph features to embed and in what ratios', 'create a LearnedPositionalEncoder with model dimension k, height, width, and device parameters', 'build a TransformerEncoder with d_model, N layers, heads, height, width, and device parameters', 'test the LearnedPositionalEncoder forward pass by concatenating input with learned positional encoding through an MLP', 'test the TransformerEncoder forward pass by applying positional encoding then N transformer encoder layers', 'review the TransformerEncoder layers cloning and sequential application of TransformerEncoderLayer instances']
```

Usage

```
{'build_forward_dynamics_net': 'build a ForwardDynamicsNet module to predict next state embeddings from state and action inputs', 'build_inverse_dynamics_net': 'build an InverseDynamicsNet module to predict action logits from state and next state embeddings', 'test_forward_dynamics_forward': 'test the ForwardDynamicsNet forward method by passing state embeddings and action tensors', 'test_inverse_dynamics_forward': 'test the InverseDynamicsNet forward method by passing state and next state embedding tensors', 'review_dynamics_classes': 'review the ForwardDynamicsNet and InverseDynamicsNet classes for ELU activation and linear layer architecture'}
```

## File: facebookresearch_minihack/minihack/agent/common/models/embed.py

Prompts

```
['build a ForwardDynamicsNet module to predict next state embeddings from state and action inputs', 'build an InverseDynamicsNet module to predict action logits from state and next state embeddings', 'test the ForwardDynamicsNet forward method by passing state embeddings and action tensors', 'test the InverseDynamicsNet forward method by passing state and next state embedding tensors', 'review the ForwardDynamicsNet and InverseDynamicsNet classes for ELU activation and linear layer architecture', 'build a GlyphEmbedding module with a given glyph_type strategy and embedding dimension', 'prepare input dictionary into a GlyphTuple namedtuple for embedding lookup', 'run the forward pass to embed a GlyphTuple and return concatenated embedding vectors', 'convert glyph tensors into subgroup ids and group ids using the id_pairs_table', 'configure a Targets NamedTuple to select which glyph features to embed and in what ratios', 'create a LearnedPositionalEncoder with model dimension k, height, width, and device parameters', 'build a TransformerEncoder with d_model, N layers, heads, height, width, and device parameters', 'test the LearnedPositionalEncoder forward pass by concatenating input with learned positional encoding through an MLP', 'test the TransformerEncoder forward pass by applying positional encoding then N transformer encoder layers', 'review the TransformerEncoder layers cloning and sequential application of TransformerEncoderLayer instances']
```

Usage

```
{'build_glyph_embedding': 'build a GlyphEmbedding module with a given glyph_type strategy and embedding dimension', 'prepare_input_glyph_tuple': 'prepare input dictionary into a GlyphTuple namedtuple for embedding lookup', 'forward_embed_glyphs': 'run the forward pass to embed a GlyphTuple and return concatenated embedding vectors', 'glyphs_to_idgroup': 'convert glyph tensors into subgroup ids and group ids using the id_pairs_table', 'configure_targets_strategy': 'configure a Targets NamedTuple to select which glyph features to embed and in what ratios'}
```

## File: facebookresearch_minihack/minihack/agent/common/models/transformer.py

Prompts

```
['build a ForwardDynamicsNet module to predict next state embeddings from state and action inputs', 'build an InverseDynamicsNet module to predict action logits from state and next state embeddings', 'test the ForwardDynamicsNet forward method by passing state embeddings and action tensors', 'test the InverseDynamicsNet forward method by passing state and next state embedding tensors', 'review the ForwardDynamicsNet and InverseDynamicsNet classes for ELU activation and linear layer architecture', 'build a GlyphEmbedding module with a given glyph_type strategy and embedding dimension', 'prepare input dictionary into a GlyphTuple namedtuple for embedding lookup', 'run the forward pass to embed a GlyphTuple and return concatenated embedding vectors', 'convert glyph tensors into subgroup ids and group ids using the id_pairs_table', 'configure a Targets NamedTuple to select which glyph features to embed and in what ratios', 'create a LearnedPositionalEncoder with model dimension k, height, width, and device parameters', 'build a TransformerEncoder with d_model, N layers, heads, height, width, and device parameters', 'test the LearnedPositionalEncoder forward pass by concatenating input with learned positional encoding through an MLP', 'test the TransformerEncoder forward pass by applying positional encoding then N transformer encoder layers', 'review the TransformerEncoder layers cloning and sequential application of TransformerEncoderLayer instances']
```

Usage

```
{'create_learned_positional_encoder': 'create a LearnedPositionalEncoder with model dimension k, height, width, and device parameters', 'build_transformer_encoder': 'build a TransformerEncoder with d_model, N layers, heads, height, width, and device parameters', 'test_learned_positional_encoder_forward': 'test the LearnedPositionalEncoder forward pass by concatenating input with learned positional encoding through an MLP', 'test_transformer_encoder_forward': 'test the TransformerEncoder forward pass by applying positional encoding then N transformer encoder layers', 'review_transformer_encoder_layers': 'review the TransformerEncoder layers cloning and sequential application of TransformerEncoderLayer instances'}
```

