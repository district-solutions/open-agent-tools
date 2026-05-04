# Agent Python Tools

- repo: facebookresearch/fbtt-embedding
- repo_uri: https://github.com/facebookresearch/fbtt-embedding

## File: facebookresearch_fbtt-embedding/tt_embeddings_benchmark.py

Prompts

```
['run the TTEmbeddingBag benchmark with configurable batch size, pooling factor, and TT shapes via CLI', 'run the benchmark with --run-baseline to compare TTEmbeddingBag against standard EmbeddingBag performance', 'generate synthetic embedding lookup requests with configurable Zipf or uniform index distributions', 'benchmark a callable function over a list of index, offset, and weight tensor requests on CUDA', 'convert dense merged indices tensor of shape T,B,L into flattened indices and batched offsets', 'create a TTEmbeddingBag with specified num_embeddings, embedding_dim, and tt_ranks for tensor train embeddings', 'create a TableBatchedTTEmbeddingBag with multiple tables sharing the same num_embeddings and embedding_dim', 'run a forward pass on TTEmbeddingBag with indices and offsets tensors to get embedding sums', 'compute suggested tensor train shapes for a given dimension using the suggested_tt_shapes function', 'convert tensor train cores to a full dense matrix using the tt_matrix_to_full function', 'test the TTEmbeddingBag forward pass against a reference nn.EmbeddingBag on CUDA', 'test the TTEmbeddingBag backward pass with dense gradient computation and core gradient comparison', 'test the TTEmbeddingBag backward pass with SGD optimizer and verify weight updates', 'test the TTEmbeddingBag backward pass with Adagrad optimizer and verify optimizer state updates', 'test the TableBatchedTTEmbeddingBag forward pass across multiple tables and compare outputs']
```

Usage

```
{'run_tt_embedding_benchmark': 'run the TTEmbeddingBag benchmark with configurable batch size, pooling factor, and TT shapes via CLI', 'run_baseline_embedding_comparison': 'run the benchmark with --run-baseline to compare TTEmbeddingBag against standard EmbeddingBag performance', 'generate_requests': 'generate synthetic embedding lookup requests with configurable Zipf or uniform index distributions', 'benchmark_requests': 'benchmark a callable function over a list of index, offset, and weight tensor requests on CUDA', 'get_table_batched_offsets_from_dense': 'convert dense merged indices tensor of shape T,B,L into flattened indices and batched offsets'}
```

## File: facebookresearch_fbtt-embedding/tt_embeddings_ops.py

Prompts

```
['run the TTEmbeddingBag benchmark with configurable batch size, pooling factor, and TT shapes via CLI', 'run the benchmark with --run-baseline to compare TTEmbeddingBag against standard EmbeddingBag performance', 'generate synthetic embedding lookup requests with configurable Zipf or uniform index distributions', 'benchmark a callable function over a list of index, offset, and weight tensor requests on CUDA', 'convert dense merged indices tensor of shape T,B,L into flattened indices and batched offsets', 'create a TTEmbeddingBag with specified num_embeddings, embedding_dim, and tt_ranks for tensor train embeddings', 'create a TableBatchedTTEmbeddingBag with multiple tables sharing the same num_embeddings and embedding_dim', 'run a forward pass on TTEmbeddingBag with indices and offsets tensors to get embedding sums', 'compute suggested tensor train shapes for a given dimension using the suggested_tt_shapes function', 'convert tensor train cores to a full dense matrix using the tt_matrix_to_full function', 'test the TTEmbeddingBag forward pass against a reference nn.EmbeddingBag on CUDA', 'test the TTEmbeddingBag backward pass with dense gradient computation and core gradient comparison', 'test the TTEmbeddingBag backward pass with SGD optimizer and verify weight updates', 'test the TTEmbeddingBag backward pass with Adagrad optimizer and verify optimizer state updates', 'test the TableBatchedTTEmbeddingBag forward pass across multiple tables and compare outputs']
```

Usage

```
{'create_tt_embedding_bag': 'create a TTEmbeddingBag with specified num_embeddings, embedding_dim, and tt_ranks for tensor train embeddings', 'create_table_batched_tt_embedding_bag': 'create a TableBatchedTTEmbeddingBag with multiple tables sharing the same num_embeddings and embedding_dim', 'run_tt_embedding_lookup': 'run a forward pass on TTEmbeddingBag with indices and offsets tensors to get embedding sums', 'compute_suggested_tt_shapes': 'compute suggested tensor train shapes for a given dimension using the suggested_tt_shapes function', 'convert_tt_cores_to_full_matrix': 'convert tensor train cores to a full dense matrix using the tt_matrix_to_full function'}
```

## File: facebookresearch_fbtt-embedding/tt_embeddings_test.py

Prompts

```
['run the TTEmbeddingBag benchmark with configurable batch size, pooling factor, and TT shapes via CLI', 'run the benchmark with --run-baseline to compare TTEmbeddingBag against standard EmbeddingBag performance', 'generate synthetic embedding lookup requests with configurable Zipf or uniform index distributions', 'benchmark a callable function over a list of index, offset, and weight tensor requests on CUDA', 'convert dense merged indices tensor of shape T,B,L into flattened indices and batched offsets', 'create a TTEmbeddingBag with specified num_embeddings, embedding_dim, and tt_ranks for tensor train embeddings', 'create a TableBatchedTTEmbeddingBag with multiple tables sharing the same num_embeddings and embedding_dim', 'run a forward pass on TTEmbeddingBag with indices and offsets tensors to get embedding sums', 'compute suggested tensor train shapes for a given dimension using the suggested_tt_shapes function', 'convert tensor train cores to a full dense matrix using the tt_matrix_to_full function', 'test the TTEmbeddingBag forward pass against a reference nn.EmbeddingBag on CUDA', 'test the TTEmbeddingBag backward pass with dense gradient computation and core gradient comparison', 'test the TTEmbeddingBag backward pass with SGD optimizer and verify weight updates', 'test the TTEmbeddingBag backward pass with Adagrad optimizer and verify optimizer state updates', 'test the TableBatchedTTEmbeddingBag forward pass across multiple tables and compare outputs']
```

Usage

```
{'test_TTEmbeddingBag_forward': 'test the TTEmbeddingBag forward pass against a reference nn.EmbeddingBag on CUDA', 'test_TTEmbeddingBag_backward_dense': 'test the TTEmbeddingBag backward pass with dense gradient computation and core gradient comparison', 'test_TTEmbeddingBag_backward_sgd': 'test the TTEmbeddingBag backward pass with SGD optimizer and verify weight updates', 'test_TTEmbeddingBag_backward_adagrad': 'test the TTEmbeddingBag backward pass with Adagrad optimizer and verify optimizer state updates', 'test_TableBatchedTTEmbeddingBag_forward': 'test the TableBatchedTTEmbeddingBag forward pass across multiple tables and compare outputs'}
```

