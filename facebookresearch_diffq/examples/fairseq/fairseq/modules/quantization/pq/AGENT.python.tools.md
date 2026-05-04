# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/fairseq/modules/quantization/pq/em.py

Prompts

```
['build a python module that uses the EM class to quantize a weight matrix with k-means clustering', 'run a single EM algorithm iteration on a weight matrix to update centroids and assignments', 'create a function that initializes centroids by randomly sampling columns from a weight matrix', 'save EM algorithm centroids, assignments, and objective values to disk for a given layer', 'load previously saved EM centroids and assignments from disk for a given layer', 'build a python module that uses PQ to quantize fully-connected layer weights with k-means product quantization', 'build a python module that uses PQ to quantize convolutional layer weights with product quantization', 'run the PQ encode then decode cycle to reconstruct quantized neural network weights', 'review the PQ _reshape method that splits weight matrices into subvectors for product quantization', 'test the PQ encode method to verify it handles empty cluster resolution during k-means iterations', 'quantize a PyTorch model in-place by replacing targeted Linear, Conv2d, and Embedding layers with Product Quantization counterparts', 'get layers from a PyTorch model filtered by a regex pattern matching their names in named_parameters', 'get the quantization block size or centroid count for a module from a configuration dictionary', 'track compressed model size statistics including index size, centroid size, and compression ratio during quantization', 'set a nested attribute on a PyTorch module by resolving dot-separated attribute paths']
```

Usage

```
{'build_EM_quantizer': 'build a python module that uses the EM class to quantize a weight matrix with k-means clustering', 'run_EM_step': 'run a single EM algorithm iteration on a weight matrix to update centroids and assignments', 'create_centroid_initialization': 'create a function that initializes centroids by randomly sampling columns from a weight matrix', 'save_EM_results': 'save EM algorithm centroids, assignments, and objective values to disk for a given layer', 'load_EM_centroids': 'load previously saved EM centroids and assignments from disk for a given layer'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/modules/quantization/pq/pq.py

Prompts

```
['build a python module that uses the EM class to quantize a weight matrix with k-means clustering', 'run a single EM algorithm iteration on a weight matrix to update centroids and assignments', 'create a function that initializes centroids by randomly sampling columns from a weight matrix', 'save EM algorithm centroids, assignments, and objective values to disk for a given layer', 'load previously saved EM centroids and assignments from disk for a given layer', 'build a python module that uses PQ to quantize fully-connected layer weights with k-means product quantization', 'build a python module that uses PQ to quantize convolutional layer weights with product quantization', 'run the PQ encode then decode cycle to reconstruct quantized neural network weights', 'review the PQ _reshape method that splits weight matrices into subvectors for product quantization', 'test the PQ encode method to verify it handles empty cluster resolution during k-means iterations', 'quantize a PyTorch model in-place by replacing targeted Linear, Conv2d, and Embedding layers with Product Quantization counterparts', 'get layers from a PyTorch model filtered by a regex pattern matching their names in named_parameters', 'get the quantization block size or centroid count for a module from a configuration dictionary', 'track compressed model size statistics including index size, centroid size, and compression ratio during quantization', 'set a nested attribute on a PyTorch module by resolving dot-separated attribute paths']
```

Usage

```
{'build_PQ_quantize_fc_weights': 'build a python module that uses PQ to quantize fully-connected layer weights with k-means product quantization', 'build_PQ_quantize_conv_weights': 'build a python module that uses PQ to quantize convolutional layer weights with product quantization', 'run_PQ_encode_decode': 'run the PQ encode then decode cycle to reconstruct quantized neural network weights', 'review_PQ_reshape': 'review the PQ _reshape method that splits weight matrices into subvectors for product quantization', 'test_PQ_empty_cluster_resolve': 'test the PQ encode method to verify it handles empty cluster resolution during k-means iterations'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/modules/quantization/pq/utils.py

Prompts

```
['build a python module that uses the EM class to quantize a weight matrix with k-means clustering', 'run a single EM algorithm iteration on a weight matrix to update centroids and assignments', 'create a function that initializes centroids by randomly sampling columns from a weight matrix', 'save EM algorithm centroids, assignments, and objective values to disk for a given layer', 'load previously saved EM centroids and assignments from disk for a given layer', 'build a python module that uses PQ to quantize fully-connected layer weights with k-means product quantization', 'build a python module that uses PQ to quantize convolutional layer weights with product quantization', 'run the PQ encode then decode cycle to reconstruct quantized neural network weights', 'review the PQ _reshape method that splits weight matrices into subvectors for product quantization', 'test the PQ encode method to verify it handles empty cluster resolution during k-means iterations', 'quantize a PyTorch model in-place by replacing targeted Linear, Conv2d, and Embedding layers with Product Quantization counterparts', 'get layers from a PyTorch model filtered by a regex pattern matching their names in named_parameters', 'get the quantization block size or centroid count for a module from a configuration dictionary', 'track compressed model size statistics including index size, centroid size, and compression ratio during quantization', 'set a nested attribute on a PyTorch module by resolving dot-separated attribute paths']
```

Usage

```
{'quantize_model_inplace': 'quantize a PyTorch model in-place by replacing targeted Linear, Conv2d, and Embedding layers with Product Quantization counterparts', 'get_layers_by_regex': 'get layers from a PyTorch model filtered by a regex pattern matching their names in named_parameters', 'get_param_from_config': 'get the quantization block size or centroid count for a module from a configuration dictionary', 'track_compressed_model_size': 'track compressed model size statistics including index size, centroid size, and compression ratio during quantization', 'set_nested_attribute': 'set a nested attribute on a PyTorch module by resolving dot-separated attribute paths'}
```

