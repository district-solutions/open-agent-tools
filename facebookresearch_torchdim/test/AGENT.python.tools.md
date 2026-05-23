# Agent Python Tools

- repo: facebookresearch/torchdim
- repo_uri: https://github.com/facebookresearch/torchdim

## File: facebookresearch_torchdim/test/attn_ft.py

Prompts

```
['build a BertSelfAttention module with named dimensions for multi-head self-attention using torchdim', 'create a Linear layer forward pass using explicit dimension symbols for input and output', 'test the BertSelfAttention forward pass with hidden states and optional past key values', 'review the dims function usage for binding named dimensions to tensors in attention layers', 'refactor the softmax call to use named dimension key_sequence instead of integer axis', 'build a BertSelfAttention module with hidden_size 768 and 12 attention heads without positional embeddings', 'build a BertSelfAttention module with relative_key positional embeddings and max_position_embeddings set to 512', 'build a BertSelfAttention module with relative_key_query positional embeddings for query and key vectors', 'review the BertSelfAttention transpose_for_scores method that reshapes tensors for multi-head attention computation', 'test that named dimension tensors A[i,k] * B[k,j].sum(k) match standard torch.mm results', 'test reordering tensor dimensions by name using Tensor.order(i, j) to match permuted shapes', 'test splitting and merging tensor dimensions using Tensor.index(k, [o, l]) to reshape views', 'test creating named dimension symbols with dims() and dimlists() for symbolic tensor indexing', 'test embedding table lookup using named dimensions embeddings[ids[batch], feature].order(batch, feature)']
```

Usage

```
{'build_BertSelfAttention': 'build a BertSelfAttention module with named dimensions for multi-head self-attention using torchdim', 'create_Linear_forward': 'create a Linear layer forward pass using explicit dimension symbols for input and output', 'test_BertSelfAttention_forward': 'test the BertSelfAttention forward pass with hidden states and optional past key values', 'review_dims_api': 'review the dims function usage for binding named dimensions to tensors in attention layers', 'refactor_softmax_dim': 'refactor the softmax call to use named dimension key_sequence instead of integer axis'}
```

## File: facebookresearch_torchdim/test/attn_positional.py

Prompts

```
['build a BertSelfAttention module with named dimensions for multi-head self-attention using torchdim', 'create a Linear layer forward pass using explicit dimension symbols for input and output', 'test the BertSelfAttention forward pass with hidden states and optional past key values', 'review the dims function usage for binding named dimensions to tensors in attention layers', 'refactor the softmax call to use named dimension key_sequence instead of integer axis', 'build a BertSelfAttention module with hidden_size 768 and 12 attention heads without positional embeddings', 'build a BertSelfAttention module with relative_key positional embeddings and max_position_embeddings set to 512', 'build a BertSelfAttention module with relative_key_query positional embeddings for query and key vectors', 'review the BertSelfAttention transpose_for_scores method that reshapes tensors for multi-head attention computation', 'test that named dimension tensors A[i,k] * B[k,j].sum(k) match standard torch.mm results', 'test reordering tensor dimensions by name using Tensor.order(i, j) to match permuted shapes', 'test splitting and merging tensor dimensions using Tensor.index(k, [o, l]) to reshape views', 'test creating named dimension symbols with dims() and dimlists() for symbolic tensor indexing', 'test embedding table lookup using named dimensions embeddings[ids[batch], feature].order(batch, feature)']
```

Usage

```
{'build_BertSelfAttention_no_positional': 'build a BertSelfAttention module with hidden_size 768 and 12 attention heads without positional embeddings', 'build_BertSelfAttention_relative_key': 'build a BertSelfAttention module with relative_key positional embeddings and max_position_embeddings set to 512', 'build_BertSelfAttention_relative_key_query': 'build a BertSelfAttention module with relative_key_query positional embeddings for query and key vectors', 'test_BertSelfAttention_forward': 'test the BertSelfAttention forward pass with hidden_states tensor and optional past_key_value caching', 'review_BertSelfAttention_transpose_for_scores': 'review the BertSelfAttention transpose_for_scores method that reshapes tensors for multi-head attention computation'}
```

## File: facebookresearch_torchdim/test/test_dims.py

Prompts

```
['build a BertSelfAttention module with named dimensions for multi-head self-attention using torchdim', 'create a Linear layer forward pass using explicit dimension symbols for input and output', 'test the BertSelfAttention forward pass with hidden states and optional past key values', 'review the dims function usage for binding named dimensions to tensors in attention layers', 'refactor the softmax call to use named dimension key_sequence instead of integer axis', 'build a BertSelfAttention module with hidden_size 768 and 12 attention heads without positional embeddings', 'build a BertSelfAttention module with relative_key positional embeddings and max_position_embeddings set to 512', 'build a BertSelfAttention module with relative_key_query positional embeddings for query and key vectors', 'review the BertSelfAttention transpose_for_scores method that reshapes tensors for multi-head attention computation', 'test that named dimension tensors A[i,k] * B[k,j].sum(k) match standard torch.mm results', 'test reordering tensor dimensions by name using Tensor.order(i, j) to match permuted shapes', 'test splitting and merging tensor dimensions using Tensor.index(k, [o, l]) to reshape views', 'test creating named dimension symbols with dims() and dimlists() for symbolic tensor indexing', 'test embedding table lookup using named dimensions embeddings[ids[batch], feature].order(batch, feature)']
```

Usage

```
{'test_named_dim_matrix_multiply': 'test that named dimension tensors A[i,k] * B[k,j].sum(k) match standard torch.mm results', 'test_tensor_order_reorder': 'test reordering tensor dimensions by name using Tensor.order(i, j) to match permuted shapes', 'test_dim_index_reshape': 'test splitting and merging tensor dimensions using Tensor.index(k, [o, l]) to reshape views', 'test_dims_creation': 'test creating named dimension symbols with dims() and dimlists() for symbolic tensor indexing', 'test_named_dim_embedding_lookup': 'test embedding table lookup using named dimensions embeddings[ids[batch], feature].order(batch, feature)'}
```

