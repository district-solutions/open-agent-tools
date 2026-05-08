# Agent Python Tools

- repo: facebookresearch/memory
- repo_uri: https://github.com/facebookresearch/memory

## File: facebookresearch_memory/lingua/product_key/colwise_embedding_bag.py

Prompts

```
['create an xFormerEmbeddingBag module with a given size and embedding dimension', 'run the xFormerEmbeddingBag forward pass with indices and per-sample weight scores', 'create a ColwiseEmbeddingBag parallel style with custom input and output sharding layouts', 'review the ColwiseEmbeddingBag partition function that column-shards EmbeddingBag weights across devices', 'test the ColwiseEmbeddingBag _apply method to distribute an xFormerEmbeddingBag module on a DeviceMesh', 'build a HashingMemory module with product key memory for a given input and output dimension', 'create a forward pass through HashingMemory to read values from the memory using product key retrieval', 'configure ProductKeyArgs dataclass to enable product key memory with custom key count, heads, and k-NN parameters', 'build a QueryMLP module to compute multi-head queries from input embeddings for memory retrieval', 'reset HashingMemory parameters including keys, values, and query projections with configurable initialization', 'run xformers_embedding_bag with indices, weight, and per_sample_weights tensors to compute embedding bag lookups', 'run custom_embedding_bag_function with indices, weight, and per_sample_weights tensors for a chunked backward embedding bag', 'run embedding_bag_triton with indices, weight, and per_sample_weights tensors for a Triton-accelerated embedding bag forward pass', 'run embedding_bag_bw_rev_indices to compute weight and per_sample_weights gradients using reverse index aggregation', 'run embedding_bag_bw2 to compute weight and per_sample_weights gradients using atomics or locking strategies']
```

Usage

```
{'create_xformer_embedding_bag': 'create an xFormerEmbeddingBag module with a given size and embedding dimension', 'run_xformer_embedding_bag_forward': 'run the xFormerEmbeddingBag forward pass with indices and per-sample weight scores', 'create_colwise_embedding_bag_style': 'create a ColwiseEmbeddingBag parallel style with custom input and output sharding layouts', 'review_colwise_partition_fn': 'review the ColwiseEmbeddingBag partition function that column-shards EmbeddingBag weights across devices', 'test_colwise_apply': 'test the ColwiseEmbeddingBag _apply method to distribute an xFormerEmbeddingBag module on a DeviceMesh'}
```

## File: facebookresearch_memory/lingua/product_key/memory.py

Prompts

```
['create an xFormerEmbeddingBag module with a given size and embedding dimension', 'run the xFormerEmbeddingBag forward pass with indices and per-sample weight scores', 'create a ColwiseEmbeddingBag parallel style with custom input and output sharding layouts', 'review the ColwiseEmbeddingBag partition function that column-shards EmbeddingBag weights across devices', 'test the ColwiseEmbeddingBag _apply method to distribute an xFormerEmbeddingBag module on a DeviceMesh', 'build a HashingMemory module with product key memory for a given input and output dimension', 'create a forward pass through HashingMemory to read values from the memory using product key retrieval', 'configure ProductKeyArgs dataclass to enable product key memory with custom key count, heads, and k-NN parameters', 'build a QueryMLP module to compute multi-head queries from input embeddings for memory retrieval', 'reset HashingMemory parameters including keys, values, and query projections with configurable initialization', 'run xformers_embedding_bag with indices, weight, and per_sample_weights tensors to compute embedding bag lookups', 'run custom_embedding_bag_function with indices, weight, and per_sample_weights tensors for a chunked backward embedding bag', 'run embedding_bag_triton with indices, weight, and per_sample_weights tensors for a Triton-accelerated embedding bag forward pass', 'run embedding_bag_bw_rev_indices to compute weight and per_sample_weights gradients using reverse index aggregation', 'run embedding_bag_bw2 to compute weight and per_sample_weights gradients using atomics or locking strategies']
```

Usage

```
{'build_hashingmemory_module': 'build a HashingMemory module with product key memory for a given input and output dimension', 'create_hashingmemory_forward': 'create a forward pass through HashingMemory to read values from the memory using product key retrieval', 'configure_productkeyargs': 'configure ProductKeyArgs dataclass to enable product key memory with custom key count, heads, and k-NN parameters', 'build_querymlp_module': 'build a QueryMLP module to compute multi-head queries from input embeddings for memory retrieval', 'reset_hashingmemory_parameters': 'reset HashingMemory parameters including keys, values, and query projections with configurable initialization'}
```

## File: facebookresearch_memory/lingua/product_key/xformer_embeddingbag.py

Prompts

```
['create an xFormerEmbeddingBag module with a given size and embedding dimension', 'run the xFormerEmbeddingBag forward pass with indices and per-sample weight scores', 'create a ColwiseEmbeddingBag parallel style with custom input and output sharding layouts', 'review the ColwiseEmbeddingBag partition function that column-shards EmbeddingBag weights across devices', 'test the ColwiseEmbeddingBag _apply method to distribute an xFormerEmbeddingBag module on a DeviceMesh', 'build a HashingMemory module with product key memory for a given input and output dimension', 'create a forward pass through HashingMemory to read values from the memory using product key retrieval', 'configure ProductKeyArgs dataclass to enable product key memory with custom key count, heads, and k-NN parameters', 'build a QueryMLP module to compute multi-head queries from input embeddings for memory retrieval', 'reset HashingMemory parameters including keys, values, and query projections with configurable initialization', 'run xformers_embedding_bag with indices, weight, and per_sample_weights tensors to compute embedding bag lookups', 'run custom_embedding_bag_function with indices, weight, and per_sample_weights tensors for a chunked backward embedding bag', 'run embedding_bag_triton with indices, weight, and per_sample_weights tensors for a Triton-accelerated embedding bag forward pass', 'run embedding_bag_bw_rev_indices to compute weight and per_sample_weights gradients using reverse index aggregation', 'run embedding_bag_bw2 to compute weight and per_sample_weights gradients using atomics or locking strategies']
```

Usage

```
{'run_xformers_embedding_bag': 'run xformers_embedding_bag with indices, weight, and per_sample_weights tensors to compute embedding bag lookups', 'run_custom_embedding_bag_function': 'run custom_embedding_bag_function with indices, weight, and per_sample_weights tensors for a chunked backward embedding bag', 'run_embedding_bag_triton': 'run embedding_bag_triton with indices, weight, and per_sample_weights tensors for a Triton-accelerated embedding bag forward pass', 'run_embedding_bag_bw_rev_indices': 'run embedding_bag_bw_rev_indices to compute weight and per_sample_weights gradients using reverse index aggregation', 'run_embedding_bag_bw2': 'run embedding_bag_bw2 to compute weight and per_sample_weights gradients using atomics or locking strategies'}
```

