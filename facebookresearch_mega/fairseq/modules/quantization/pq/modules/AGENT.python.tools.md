# Agent Python Tools

- repo: facebookresearch/mega
- repo_uri: https://github.com/facebookresearch/mega

## File: facebookresearch_mega/fairseq/modules/quantization/pq/modules/qconv.py

Prompts

```
['create a PQConv2d quantized convolutional layer with centroids, assignments, and bias tensors', 'build a PQConv2d layer and access its reconstructed weight tensor from centroids and assignments', 'run a forward pass through a PQConv2d quantized convolutional layer on input tensor x', 'review the PQConv2d centroid gradient averaging hook that divides gradients by cluster counts', 'test PQConv2d initialization with valid centroids, assignments, and convolution parameters like kernel size and stride', 'create a PQEmbedding module with centroids and assignments for product quantized embeddings', 'build the reconstructed embedding weight matrix from centroids and centroid assignments', 'run a forward pass through PQEmbedding to get quantized embeddings for input indices', 'review the PQEmbedding constructor to validate PQ sizes and register centroids and assignments', 'summarize the PQEmbedding module representation including embedding dims, padding, and quantization params', 'create a PQLinear quantized linear layer with centroids, assignments, and bias tensors', 'build a PQLinear module that reconstructs full weights from centroids and assignments on each forward pass', 'test the PQLinear forward pass by passing input tensor through the quantized linear layer', 'review the PQLinear class to understand product quantization of nn.Linear weights using centroids', 'refactor the PQLinear centroids parameter to adjust the number of centroids or block size']
```

Usage

```
{'create_PQConv2d_layer': 'create a PQConv2d quantized convolutional layer with centroids, assignments, and bias tensors', 'build_PQConv2d_weight_reconstruction': 'build a PQConv2d layer and access its reconstructed weight tensor from centroids and assignments', 'run_PQConv2d_forward': 'run a forward pass through a PQConv2d quantized convolutional layer on input tensor x', 'review_PQConv2d_gradient_hook': 'review the PQConv2d centroid gradient averaging hook that divides gradients by cluster counts', 'test_PQConv2d_initialization': 'test PQConv2d initialization with valid centroids, assignments, and convolution parameters like kernel size and stride'}
```

## File: facebookresearch_mega/fairseq/modules/quantization/pq/modules/qemb.py

Prompts

```
['create a PQConv2d quantized convolutional layer with centroids, assignments, and bias tensors', 'build a PQConv2d layer and access its reconstructed weight tensor from centroids and assignments', 'run a forward pass through a PQConv2d quantized convolutional layer on input tensor x', 'review the PQConv2d centroid gradient averaging hook that divides gradients by cluster counts', 'test PQConv2d initialization with valid centroids, assignments, and convolution parameters like kernel size and stride', 'create a PQEmbedding module with centroids and assignments for product quantized embeddings', 'build the reconstructed embedding weight matrix from centroids and centroid assignments', 'run a forward pass through PQEmbedding to get quantized embeddings for input indices', 'review the PQEmbedding constructor to validate PQ sizes and register centroids and assignments', 'summarize the PQEmbedding module representation including embedding dims, padding, and quantization params', 'create a PQLinear quantized linear layer with centroids, assignments, and bias tensors', 'build a PQLinear module that reconstructs full weights from centroids and assignments on each forward pass', 'test the PQLinear forward pass by passing input tensor through the quantized linear layer', 'review the PQLinear class to understand product quantization of nn.Linear weights using centroids', 'refactor the PQLinear centroids parameter to adjust the number of centroids or block size']
```

Usage

```
{'create_PQEmbedding': 'create a PQEmbedding module with centroids and assignments for product quantized embeddings', 'build_PQEmbedding_weight': 'build the reconstructed embedding weight matrix from centroids and centroid assignments', 'run_PQEmbedding_forward': 'run a forward pass through PQEmbedding to get quantized embeddings for input indices', 'review_PQEmbedding_init': 'review the PQEmbedding constructor to validate PQ sizes and register centroids and assignments', 'summarize_PQEmbedding_extra_repr': 'summarize the PQEmbedding module representation including embedding dims, padding, and quantization params'}
```

## File: facebookresearch_mega/fairseq/modules/quantization/pq/modules/qlinear.py

Prompts

```
['create a PQConv2d quantized convolutional layer with centroids, assignments, and bias tensors', 'build a PQConv2d layer and access its reconstructed weight tensor from centroids and assignments', 'run a forward pass through a PQConv2d quantized convolutional layer on input tensor x', 'review the PQConv2d centroid gradient averaging hook that divides gradients by cluster counts', 'test PQConv2d initialization with valid centroids, assignments, and convolution parameters like kernel size and stride', 'create a PQEmbedding module with centroids and assignments for product quantized embeddings', 'build the reconstructed embedding weight matrix from centroids and centroid assignments', 'run a forward pass through PQEmbedding to get quantized embeddings for input indices', 'review the PQEmbedding constructor to validate PQ sizes and register centroids and assignments', 'summarize the PQEmbedding module representation including embedding dims, padding, and quantization params', 'create a PQLinear quantized linear layer with centroids, assignments, and bias tensors', 'build a PQLinear module that reconstructs full weights from centroids and assignments on each forward pass', 'test the PQLinear forward pass by passing input tensor through the quantized linear layer', 'review the PQLinear class to understand product quantization of nn.Linear weights using centroids', 'refactor the PQLinear centroids parameter to adjust the number of centroids or block size']
```

Usage

```
{'create_PQLinear_module': 'create a PQLinear quantized linear layer with centroids, assignments, and bias tensors', 'build_PQLinear_weight_reconstruction': 'build a PQLinear module that reconstructs full weights from centroids and assignments on each forward pass', 'test_PQLinear_forward': 'test the PQLinear forward pass by passing input tensor through the quantized linear layer', 'review_PQLinear_quantization': 'review the PQLinear class to understand product quantization of nn.Linear weights using centroids', 'refactor_PQLinear_centroids': 'refactor the PQLinear centroids parameter to adjust the number of centroids or block size'}
```

