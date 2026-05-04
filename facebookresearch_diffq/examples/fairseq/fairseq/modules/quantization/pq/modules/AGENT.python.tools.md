# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/fairseq/modules/quantization/pq/modules/qconv.py

Prompts

```
['build a product quantization conv2d layer with centroids and assignments for quantized convolution', 'create a PQConv2d module with non-quantized bias and configurable stride padding and dilation', 'run a forward pass through a PQConv2d layer that reconstructs weights from centroids', 'review the PQConv2d weight property that reshapes centroids by assignments into conv weights', 'test the PQConv2d gradient averaging hook that divides gradients by centroid cluster counts', 'create a PQEmbedding module with centroids and assignments for product quantized embeddings', 'build a reconstructed embedding weight matrix from centroids and centroid assignments', 'run a forward pass through PQEmbedding to look up quantized embeddings for input indices', 'test the PQEmbedding constructor to validate PQ sizes and padding index constraints', 'review the PQEmbedding extra_repr method to inspect module configuration and quantization parameters', 'create a PQLinear quantized linear layer with centroids, assignments, and bias tensors', 'build a forward pass through a PQLinear module using reconstructed quantized weights', 'test the PQLinear weight property that reconstructs full weights from centroids and assignments', 'review the PQLinear constructor to validate centroid and assignment tensor compatibility', "refactor the PQLinear extra_repr method to customize the module's string representation"]
```

Usage

```
{'build_PQConv2d_layer': 'build a product quantization conv2d layer with centroids and assignments for quantized convolution', 'create_PQConv2d_with_bias': 'create a PQConv2d module with non-quantized bias and configurable stride padding and dilation', 'run_PQConv2d_forward': 'run a forward pass through a PQConv2d layer that reconstructs weights from centroids', 'review_PQConv2d_weight_property': 'review the PQConv2d weight property that reshapes centroids by assignments into conv weights', 'test_PQConv2d_gradient_hook': 'test the PQConv2d gradient averaging hook that divides gradients by centroid cluster counts'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/modules/quantization/pq/modules/qemb.py

Prompts

```
['build a product quantization conv2d layer with centroids and assignments for quantized convolution', 'create a PQConv2d module with non-quantized bias and configurable stride padding and dilation', 'run a forward pass through a PQConv2d layer that reconstructs weights from centroids', 'review the PQConv2d weight property that reshapes centroids by assignments into conv weights', 'test the PQConv2d gradient averaging hook that divides gradients by centroid cluster counts', 'create a PQEmbedding module with centroids and assignments for product quantized embeddings', 'build a reconstructed embedding weight matrix from centroids and centroid assignments', 'run a forward pass through PQEmbedding to look up quantized embeddings for input indices', 'test the PQEmbedding constructor to validate PQ sizes and padding index constraints', 'review the PQEmbedding extra_repr method to inspect module configuration and quantization parameters', 'create a PQLinear quantized linear layer with centroids, assignments, and bias tensors', 'build a forward pass through a PQLinear module using reconstructed quantized weights', 'test the PQLinear weight property that reconstructs full weights from centroids and assignments', 'review the PQLinear constructor to validate centroid and assignment tensor compatibility', "refactor the PQLinear extra_repr method to customize the module's string representation"]
```

Usage

```
{'create_PQEmbedding': 'create a PQEmbedding module with centroids and assignments for product quantized embeddings', 'build_PQEmbedding_weight': 'build a reconstructed embedding weight matrix from centroids and centroid assignments', 'run_PQEmbedding_forward': 'run a forward pass through PQEmbedding to look up quantized embeddings for input indices', 'test_PQEmbedding_init': 'test the PQEmbedding constructor to validate PQ sizes and padding index constraints', 'review_PQEmbedding_extra_repr': 'review the PQEmbedding extra_repr method to inspect module configuration and quantization parameters'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/modules/quantization/pq/modules/qlinear.py

Prompts

```
['build a product quantization conv2d layer with centroids and assignments for quantized convolution', 'create a PQConv2d module with non-quantized bias and configurable stride padding and dilation', 'run a forward pass through a PQConv2d layer that reconstructs weights from centroids', 'review the PQConv2d weight property that reshapes centroids by assignments into conv weights', 'test the PQConv2d gradient averaging hook that divides gradients by centroid cluster counts', 'create a PQEmbedding module with centroids and assignments for product quantized embeddings', 'build a reconstructed embedding weight matrix from centroids and centroid assignments', 'run a forward pass through PQEmbedding to look up quantized embeddings for input indices', 'test the PQEmbedding constructor to validate PQ sizes and padding index constraints', 'review the PQEmbedding extra_repr method to inspect module configuration and quantization parameters', 'create a PQLinear quantized linear layer with centroids, assignments, and bias tensors', 'build a forward pass through a PQLinear module using reconstructed quantized weights', 'test the PQLinear weight property that reconstructs full weights from centroids and assignments', 'review the PQLinear constructor to validate centroid and assignment tensor compatibility', "refactor the PQLinear extra_repr method to customize the module's string representation"]
```

Usage

```
{'create_PQLinear_module': 'create a PQLinear quantized linear layer with centroids, assignments, and bias tensors', 'build_PQLinear_forward_pass': 'build a forward pass through a PQLinear module using reconstructed quantized weights', 'test_PQLinear_weight_property': 'test the PQLinear weight property that reconstructs full weights from centroids and assignments', 'review_PQLinear_initialization': 'review the PQLinear constructor to validate centroid and assignment tensor compatibility', 'refactor_PQLinear_extra_repr': "refactor the PQLinear extra_repr method to customize the module's string representation"}
```

