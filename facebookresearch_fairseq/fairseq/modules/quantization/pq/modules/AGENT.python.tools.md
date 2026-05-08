# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/fairseq/modules/quantization/pq/modules/qconv.py

Prompts

```
['create a PQConv2d quantized convolutional layer with centroids, assignments, and bias tensors', 'build the reconstructed weight tensor from centroids and assignments using the weight property', 'run a forward pass through a PQConv2d layer on an input tensor', 'review the PQConv2d centroid gradient averaging hook registered during initialization', 'test PQConv2d initialization with valid centroids, assignments, and convolution parameters', 'create a PQEmbedding module with centroids and assignments for product quantized embeddings', 'build a quantized embedding weight matrix from centroids and centroid assignments', 'run a forward pass through a PQEmbedding module to look up quantized embeddings', 'review the PQEmbedding constructor to validate centroids, assignments, and embedding dimensions', 'summarize the PQEmbedding module configuration including centroids, block size, and padding index', 'create a PQLinear quantized linear layer with centroids, assignments, and bias tensors', 'build a forward pass through a PQLinear module using input tensor x', 'test the PQLinear weight property that reconstructs full weights from centroids and assignments', 'review the PQLinear __init__ method for centroid and assignment compatibility validation', 'refactor the PQLinear extra_repr method to customize the module string representation']
```

Usage

```
{'create_PQConv2d_layer': 'create a PQConv2d quantized convolutional layer with centroids, assignments, and bias tensors', 'build_PQConv2d_weight_reconstruction': 'build the reconstructed weight tensor from centroids and assignments using the weight property', 'run_PQConv2d_forward': 'run a forward pass through a PQConv2d layer on an input tensor', 'review_PQConv2d_gradient_hook': 'review the PQConv2d centroid gradient averaging hook registered during initialization', 'test_PQConv2d_initialization': 'test PQConv2d initialization with valid centroids, assignments, and convolution parameters'}
```

## File: facebookresearch_fairseq/fairseq/modules/quantization/pq/modules/qemb.py

Prompts

```
['create a PQConv2d quantized convolutional layer with centroids, assignments, and bias tensors', 'build the reconstructed weight tensor from centroids and assignments using the weight property', 'run a forward pass through a PQConv2d layer on an input tensor', 'review the PQConv2d centroid gradient averaging hook registered during initialization', 'test PQConv2d initialization with valid centroids, assignments, and convolution parameters', 'create a PQEmbedding module with centroids and assignments for product quantized embeddings', 'build a quantized embedding weight matrix from centroids and centroid assignments', 'run a forward pass through a PQEmbedding module to look up quantized embeddings', 'review the PQEmbedding constructor to validate centroids, assignments, and embedding dimensions', 'summarize the PQEmbedding module configuration including centroids, block size, and padding index', 'create a PQLinear quantized linear layer with centroids, assignments, and bias tensors', 'build a forward pass through a PQLinear module using input tensor x', 'test the PQLinear weight property that reconstructs full weights from centroids and assignments', 'review the PQLinear __init__ method for centroid and assignment compatibility validation', 'refactor the PQLinear extra_repr method to customize the module string representation']
```

Usage

```
{'create_PQEmbedding': 'create a PQEmbedding module with centroids and assignments for product quantized embeddings', 'build_PQEmbedding_weight': 'build a quantized embedding weight matrix from centroids and centroid assignments', 'run_PQEmbedding_forward': 'run a forward pass through a PQEmbedding module to look up quantized embeddings', 'review_PQEmbedding_init': 'review the PQEmbedding constructor to validate centroids, assignments, and embedding dimensions', 'summarize_PQEmbedding_extra_repr': 'summarize the PQEmbedding module configuration including centroids, block size, and padding index'}
```

## File: facebookresearch_fairseq/fairseq/modules/quantization/pq/modules/qlinear.py

Prompts

```
['create a PQConv2d quantized convolutional layer with centroids, assignments, and bias tensors', 'build the reconstructed weight tensor from centroids and assignments using the weight property', 'run a forward pass through a PQConv2d layer on an input tensor', 'review the PQConv2d centroid gradient averaging hook registered during initialization', 'test PQConv2d initialization with valid centroids, assignments, and convolution parameters', 'create a PQEmbedding module with centroids and assignments for product quantized embeddings', 'build a quantized embedding weight matrix from centroids and centroid assignments', 'run a forward pass through a PQEmbedding module to look up quantized embeddings', 'review the PQEmbedding constructor to validate centroids, assignments, and embedding dimensions', 'summarize the PQEmbedding module configuration including centroids, block size, and padding index', 'create a PQLinear quantized linear layer with centroids, assignments, and bias tensors', 'build a forward pass through a PQLinear module using input tensor x', 'test the PQLinear weight property that reconstructs full weights from centroids and assignments', 'review the PQLinear __init__ method for centroid and assignment compatibility validation', 'refactor the PQLinear extra_repr method to customize the module string representation']
```

Usage

```
{'create_PQLinear_module': 'create a PQLinear quantized linear layer with centroids, assignments, and bias tensors', 'build_PQLinear_forward_pass': 'build a forward pass through a PQLinear module using input tensor x', 'test_PQLinear_weight_property': 'test the PQLinear weight property that reconstructs full weights from centroids and assignments', 'review_PQLinear_initialization': 'review the PQLinear __init__ method for centroid and assignment compatibility validation', 'refactor_PQLinear_extra_repr': 'refactor the PQLinear extra_repr method to customize the module string representation'}
```

