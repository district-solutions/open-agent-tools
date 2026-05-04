# Agent Python Tools

- repo: facebookresearch/all-atom-diffusion-transformer
- repo_uri: https://github.com/facebookresearch/all-atom-diffusion-transformer

## File: facebookresearch_all-atom-diffusion-transformer/src/models/decoders/equivariant_feedforward.py

Prompts

```
['build a FeedForwardDecoder to decode encoded atomic environments into atom types, positions, and lattice parameters', 'create a FeedForwardDecoder with custom sphere_channels and ffn_hidden_channels for molecular structure prediction', 'run the FeedForwardDecoder forward pass on an encoded batch to predict atom types, lattices, and coordinates', 'review the FeedForwardDecoder no_weight_decay method to identify parameters excluded from weight decay regularization', 'test the FeedForwardDecoder weight initialization using normal or uniform schemes for linear and radial function layers', 'build a TransformerDecoder model to decode encoded atomic environments into atom types and coordinates', 'run the TransformerDecoder forward pass with an encoded batch dict containing x, batch, and token_idx tensors', 'create sine and cosine positional embeddings from integer token indices using get_index_embedding', 'review the TransformerDecoder prediction heads for atom types, positions, fractional coordinates, and lattice parameters', 'test get_index_embedding to verify it returns positional embeddings of shape num_tokens by emb_dim']
```

Usage

```
{'build_feedforward_decoder': 'build a FeedForwardDecoder to decode encoded atomic environments into atom types, positions, and lattice parameters', 'create_decoder_with_custom_channels': 'create a FeedForwardDecoder with custom sphere_channels and ffn_hidden_channels for molecular structure prediction', 'run_forward_pass': 'run the FeedForwardDecoder forward pass on an encoded batch to predict atom types, lattices, and coordinates', 'review_no_weight_decay': 'review the FeedForwardDecoder no_weight_decay method to identify parameters excluded from weight decay regularization', 'test_weight_initialization': 'test the FeedForwardDecoder weight initialization using normal or uniform schemes for linear and radial function layers'}
```

## File: facebookresearch_all-atom-diffusion-transformer/src/models/decoders/transformer.py

Prompts

```
['build a FeedForwardDecoder to decode encoded atomic environments into atom types, positions, and lattice parameters', 'create a FeedForwardDecoder with custom sphere_channels and ffn_hidden_channels for molecular structure prediction', 'run the FeedForwardDecoder forward pass on an encoded batch to predict atom types, lattices, and coordinates', 'review the FeedForwardDecoder no_weight_decay method to identify parameters excluded from weight decay regularization', 'test the FeedForwardDecoder weight initialization using normal or uniform schemes for linear and radial function layers', 'build a TransformerDecoder model to decode encoded atomic environments into atom types and coordinates', 'run the TransformerDecoder forward pass with an encoded batch dict containing x, batch, and token_idx tensors', 'create sine and cosine positional embeddings from integer token indices using get_index_embedding', 'review the TransformerDecoder prediction heads for atom types, positions, fractional coordinates, and lattice parameters', 'test get_index_embedding to verify it returns positional embeddings of shape num_tokens by emb_dim']
```

Usage

```
{'build_transformer_decoder': 'build a TransformerDecoder model to decode encoded atomic environments into atom types and coordinates', 'run_transformer_decoder_forward': 'run the TransformerDecoder forward pass with an encoded batch dict containing x, batch, and token_idx tensors', 'create_index_embedding': 'create sine and cosine positional embeddings from integer token indices using get_index_embedding', 'review_transformer_decoder_heads': 'review the TransformerDecoder prediction heads for atom types, positions, fractional coordinates, and lattice parameters', 'test_get_index_embedding': 'test get_index_embedding to verify it returns positional embeddings of shape num_tokens by emb_dim'}
```

