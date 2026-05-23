# Agent Python Tools

- repo: facebookresearch/sam-3d-objects
- repo_uri: https://github.com/facebookresearch/sam-3d-objects

## File: facebookresearch_sam-3d-objects/sam3d_objects/model/backbone/tdfy_dit/modules/sparse/transformer/blocks.py

Prompts

```
['build a SparseFeedForwardNet module with configurable channels and mlp_ratio for sparse tensor MLP processing', 'create a SparseTransformerBlock with self-attention and FFN for processing sparse tensor features with configurable attention modes', 'create a SparseTransformerCrossBlock with self-attention, cross-attention, and FFN for sparse tensor and context tensor processing', 'review the SparseTransformerBlock forward pass that applies layer norm, self-attention, and FFN with residual connections', 'test the SparseTransformerCrossBlock forward method with gradient checkpointing enabled for memory-efficient training', 'build a ModulatedSparseTransformerBlock with channels, num_heads, and attention mode for sparse transformer self-attention', 'build a ModulatedSparseTransformerCrossBlock with channels, ctx_channels, and num_heads for sparse cross-attention', 'run forward pass of ModulatedSparseTransformerBlock with SparseTensor input and modulation tensor', 'run forward pass of ModulatedSparseTransformerCrossBlock with SparseTensor, modulation, and context tensors', 'review the adaLN_modulation mechanism that produces shift, scale, and gate parameters for MSA and MLP']
```

Usage

```
{'build_sparse_feedforward_net': 'build a SparseFeedForwardNet module with configurable channels and mlp_ratio for sparse tensor MLP processing', 'create_sparse_transformer_block': 'create a SparseTransformerBlock with self-attention and FFN for processing sparse tensor features with configurable attention modes', 'create_sparse_transformer_cross_block': 'create a SparseTransformerCrossBlock with self-attention, cross-attention, and FFN for sparse tensor and context tensor processing', 'review_sparse_transformer_block_forward': 'review the SparseTransformerBlock forward pass that applies layer norm, self-attention, and FFN with residual connections', 'test_sparse_transformer_cross_block_checkpoint': 'test the SparseTransformerCrossBlock forward method with gradient checkpointing enabled for memory-efficient training'}
```

## File: facebookresearch_sam-3d-objects/sam3d_objects/model/backbone/tdfy_dit/modules/sparse/transformer/modulated.py

Prompts

```
['build a SparseFeedForwardNet module with configurable channels and mlp_ratio for sparse tensor MLP processing', 'create a SparseTransformerBlock with self-attention and FFN for processing sparse tensor features with configurable attention modes', 'create a SparseTransformerCrossBlock with self-attention, cross-attention, and FFN for sparse tensor and context tensor processing', 'review the SparseTransformerBlock forward pass that applies layer norm, self-attention, and FFN with residual connections', 'test the SparseTransformerCrossBlock forward method with gradient checkpointing enabled for memory-efficient training', 'build a ModulatedSparseTransformerBlock with channels, num_heads, and attention mode for sparse transformer self-attention', 'build a ModulatedSparseTransformerCrossBlock with channels, ctx_channels, and num_heads for sparse cross-attention', 'run forward pass of ModulatedSparseTransformerBlock with SparseTensor input and modulation tensor', 'run forward pass of ModulatedSparseTransformerCrossBlock with SparseTensor, modulation, and context tensors', 'review the adaLN_modulation mechanism that produces shift, scale, and gate parameters for MSA and MLP']
```

Usage

```
{'build_modulated_sparse_transformer_block': 'build a ModulatedSparseTransformerBlock with channels, num_heads, and attention mode for sparse transformer self-attention', 'build_modulated_sparse_cross_block': 'build a ModulatedSparseTransformerCrossBlock with channels, ctx_channels, and num_heads for sparse cross-attention', 'run_modulated_block_forward': 'run forward pass of ModulatedSparseTransformerBlock with SparseTensor input and modulation tensor', 'run_cross_block_forward': 'run forward pass of ModulatedSparseTransformerCrossBlock with SparseTensor, modulation, and context tensors', 'review_adaln_modulation': 'review the adaLN_modulation mechanism that produces shift, scale, and gate parameters for MSA and MLP'}
```

