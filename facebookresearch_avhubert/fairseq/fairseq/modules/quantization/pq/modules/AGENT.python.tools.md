# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/fairseq/modules/quantization/pq/modules/qconv.py

Prompts

```
['create a PQConv2d quantized convolutional layer with centroids, assignments, and bias tensors', 'build a forward pass through a PQConv2d layer using reconstructed weights from product quantization centroids', 'test the PQConv2d weight property that reconstructs full weights from centroids and assignments', 'review the PQConv2d centroid gradient hook that averages gradients per cluster during backpropagation', 'refactor the PQConv2d initialization to validate PQ sizes, channel divisibility, and group compatibility', 'create a PQEmbedding module with centroids and assignments for product quantized embeddings', 'build a PQEmbedding layer with a padding index for quantized token embeddings', 'test the PQEmbedding forward pass by passing input indices through the quantized embedding', 'review the PQEmbedding weight property that reconstructs full weights from centroids and assignments', 'summarize the PQEmbedding extra_repr method that returns a string representation of quantization parameters', 'create a PQLinear quantized linear layer with centroids, assignments, and bias tensors', 'build a PQLinear module and access the reconstructed weight matrix from centroids and assignments', 'run a forward pass through a PQLinear quantized linear layer with input tensor x', 'test PQLinear initialization with valid centroids, assignments, bias, and feature dimensions', 'review the PQLinear module configuration string showing in_features, out_features, n_centroids, and block_size']
```

Usage

```
{'create_PQConv2d_layer': 'create a PQConv2d quantized convolutional layer with centroids, assignments, and bias tensors', 'build_PQConv2d_forward_pass': 'build a forward pass through a PQConv2d layer using reconstructed weights from product quantization centroids', 'test_PQConv2d_weight_reconstruction': 'test the PQConv2d weight property that reconstructs full weights from centroids and assignments', 'review_PQConv2d_gradient_hook': 'review the PQConv2d centroid gradient hook that averages gradients per cluster during backpropagation', 'refactor_PQConv2d_initialization': 'refactor the PQConv2d initialization to validate PQ sizes, channel divisibility, and group compatibility'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/modules/quantization/pq/modules/qemb.py

Prompts

```
['create a PQConv2d quantized convolutional layer with centroids, assignments, and bias tensors', 'build a forward pass through a PQConv2d layer using reconstructed weights from product quantization centroids', 'test the PQConv2d weight property that reconstructs full weights from centroids and assignments', 'review the PQConv2d centroid gradient hook that averages gradients per cluster during backpropagation', 'refactor the PQConv2d initialization to validate PQ sizes, channel divisibility, and group compatibility', 'create a PQEmbedding module with centroids and assignments for product quantized embeddings', 'build a PQEmbedding layer with a padding index for quantized token embeddings', 'test the PQEmbedding forward pass by passing input indices through the quantized embedding', 'review the PQEmbedding weight property that reconstructs full weights from centroids and assignments', 'summarize the PQEmbedding extra_repr method that returns a string representation of quantization parameters', 'create a PQLinear quantized linear layer with centroids, assignments, and bias tensors', 'build a PQLinear module and access the reconstructed weight matrix from centroids and assignments', 'run a forward pass through a PQLinear quantized linear layer with input tensor x', 'test PQLinear initialization with valid centroids, assignments, bias, and feature dimensions', 'review the PQLinear module configuration string showing in_features, out_features, n_centroids, and block_size']
```

Usage

```
{'create_PQEmbedding': 'create a PQEmbedding module with centroids and assignments for product quantized embeddings', 'build_PQEmbedding_with_padding': 'build a PQEmbedding layer with a padding index for quantized token embeddings', 'test_PQEmbedding_forward': 'test the PQEmbedding forward pass by passing input indices through the quantized embedding', 'review_PQEmbedding_weight_property': 'review the PQEmbedding weight property that reconstructs full weights from centroids and assignments', 'summarize_PQEmbedding_extra_repr': 'summarize the PQEmbedding extra_repr method that returns a string representation of quantization parameters'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/modules/quantization/pq/modules/qlinear.py

Prompts

```
['create a PQConv2d quantized convolutional layer with centroids, assignments, and bias tensors', 'build a forward pass through a PQConv2d layer using reconstructed weights from product quantization centroids', 'test the PQConv2d weight property that reconstructs full weights from centroids and assignments', 'review the PQConv2d centroid gradient hook that averages gradients per cluster during backpropagation', 'refactor the PQConv2d initialization to validate PQ sizes, channel divisibility, and group compatibility', 'create a PQEmbedding module with centroids and assignments for product quantized embeddings', 'build a PQEmbedding layer with a padding index for quantized token embeddings', 'test the PQEmbedding forward pass by passing input indices through the quantized embedding', 'review the PQEmbedding weight property that reconstructs full weights from centroids and assignments', 'summarize the PQEmbedding extra_repr method that returns a string representation of quantization parameters', 'create a PQLinear quantized linear layer with centroids, assignments, and bias tensors', 'build a PQLinear module and access the reconstructed weight matrix from centroids and assignments', 'run a forward pass through a PQLinear quantized linear layer with input tensor x', 'test PQLinear initialization with valid centroids, assignments, bias, and feature dimensions', 'review the PQLinear module configuration string showing in_features, out_features, n_centroids, and block_size']
```

Usage

```
{'create_PQLinear_module': 'create a PQLinear quantized linear layer with centroids, assignments, and bias tensors', 'build_PQLinear_weight_reconstruction': 'build a PQLinear module and access the reconstructed weight matrix from centroids and assignments', 'run_PQLinear_forward_pass': 'run a forward pass through a PQLinear quantized linear layer with input tensor x', 'test_PQLinear_initialization': 'test PQLinear initialization with valid centroids, assignments, bias, and feature dimensions', 'review_PQLinear_extra_repr': 'review the PQLinear module configuration string showing in_features, out_features, n_centroids, and block_size'}
```

