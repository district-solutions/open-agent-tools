# Agent Python Tools

- repo: facebookresearch/flowmatching
- repo_uri: https://github.com/facebookresearch/flow_matching

## File: facebookresearch_flowmatching/examples/text/model/rotary.py

Prompts

```
['build a Rotary module to compute cached cosine and sine embeddings for a given tensor dimension and base frequency', 'create a function that splits a tensor in half and returns the negated second half concatenated with the first half', 'apply rotary embeddings to a tensor using precomputed cosine and sine values with optional interleaved mode', 'review the Rotary class forward method to understand how it caches and returns cosine and sine embeddings for sequence dimensions', 'test the apply_rotary_emb_torch function with sample tensors to verify correct rotary embedding application', 'build a Transformer model with vocab embeddings, timestep conditioning, and rotary embeddings for text flow matching', 'create a DDiTBlock with multi-head attention, AdaLN modulation, and rotary positional embeddings', 'create a TimestepEmbedder that converts scalar timesteps into sinusoidal vector representations via an MLP', 'create a DDitFinalLayer that applies AdaLN modulation and a linear projection to produce output logits', 'review the Transformer forward pass that embeds tokens, applies timestep conditioning, and runs through DDiT blocks']
```

Usage

```
{'build_rotary_embeddings': 'build a Rotary module to compute cached cosine and sine embeddings for a given tensor dimension and base frequency', 'create_rotate_half': 'create a function that splits a tensor in half and returns the negated second half concatenated with the first half', 'apply_rotary_embedding': 'apply rotary embeddings to a tensor using precomputed cosine and sine values with optional interleaved mode', 'review_rotary_forward': 'review the Rotary class forward method to understand how it caches and returns cosine and sine embeddings for sequence dimensions', 'test_apply_rotary_emb_torch': 'test the apply_rotary_emb_torch function with sample tensors to verify correct rotary embedding application'}
```

## File: facebookresearch_flowmatching/examples/text/model/transformer.py

Prompts

```
['build a Rotary module to compute cached cosine and sine embeddings for a given tensor dimension and base frequency', 'create a function that splits a tensor in half and returns the negated second half concatenated with the first half', 'apply rotary embeddings to a tensor using precomputed cosine and sine values with optional interleaved mode', 'review the Rotary class forward method to understand how it caches and returns cosine and sine embeddings for sequence dimensions', 'test the apply_rotary_emb_torch function with sample tensors to verify correct rotary embedding application', 'build a Transformer model with vocab embeddings, timestep conditioning, and rotary embeddings for text flow matching', 'create a DDiTBlock with multi-head attention, AdaLN modulation, and rotary positional embeddings', 'create a TimestepEmbedder that converts scalar timesteps into sinusoidal vector representations via an MLP', 'create a DDitFinalLayer that applies AdaLN modulation and a linear projection to produce output logits', 'review the Transformer forward pass that embeds tokens, applies timestep conditioning, and runs through DDiT blocks']
```

Usage

```
{'build_transformer_for_text_diffusion': 'build a Transformer model with vocab embeddings, timestep conditioning, and rotary embeddings for text flow matching', 'create_dditblock_with_attention': 'create a DDiTBlock with multi-head attention, AdaLN modulation, and rotary positional embeddings', 'create_timestep_embedder': 'create a TimestepEmbedder that converts scalar timesteps into sinusoidal vector representations via an MLP', 'create_dditfinal_layer': 'create a DDitFinalLayer that applies AdaLN modulation and a linear projection to produce output logits', 'review_transformer_forward_pass': 'review the Transformer forward pass that embeds tokens, applies timestep conditioning, and runs through DDiT blocks'}
```

