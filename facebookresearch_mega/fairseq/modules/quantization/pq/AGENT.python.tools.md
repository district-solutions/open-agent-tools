# Agent Python Tools

- repo: facebookresearch/mega
- repo_uri: https://github.com/facebookresearch/mega

## File: facebookresearch_mega/fairseq/modules/quantization/pq/em.py

Prompts

```
['run the EM algorithm to quantize a weight matrix W to n centroids using k-means iterations', 'build an EM instance and initialize centroids by sampling random columns from a weight matrix', 'test the EM step method to perform E-step assignment and M-step centroid computation', 'refactor the EM resolve_empty_clusters method to handle empty cluster reassignment with centroid splitting', 'summarize the EM save and load methods for persisting centroids and assignments to disk', 'build a python module that uses PQ to quantize fully connected layer weights with k-means centroids', 'build a python module that uses PQ to quantize convolutional layer weights with product quantization', 'run the PQ encode and decode cycle to quantize and reconstruct a weight matrix', 'review the PQ class _reshape method for handling 2D and 4D weight tensor reshaping', 'test the PQ encode method to handle EmptyClusterResolveError during k-means iterations', 'quantize a PyTorch model in-place by replacing targeted Linear, Conv2d, and Embedding layers with product quantization counterparts', 'filter model layers by regex pattern to select which layers to quantize while excluding biases', 'get the block size or centroid count for a module based on its type, feature attribute, or fuzzy name match', 'track compressed model size statistics including index size, centroid size, and compression ratio during quantization', 'set a nested attribute on a PyTorch module by resolving dot-separated attribute paths']
```

Usage

```
{'run_EM_quantize_weight_matrix': 'run the EM algorithm to quantize a weight matrix W to n centroids using k-means iterations', 'build_EM_initialize_centroids': 'build an EM instance and initialize centroids by sampling random columns from a weight matrix', 'test_EM_step': 'test the EM step method to perform E-step assignment and M-step centroid computation', 'refactor_EM_resolve_empty_clusters': 'refactor the EM resolve_empty_clusters method to handle empty cluster reassignment with centroid splitting', 'summarize_EM_save_load': 'summarize the EM save and load methods for persisting centroids and assignments to disk'}
```

## File: facebookresearch_mega/fairseq/modules/quantization/pq/pq.py

Prompts

```
['run the EM algorithm to quantize a weight matrix W to n centroids using k-means iterations', 'build an EM instance and initialize centroids by sampling random columns from a weight matrix', 'test the EM step method to perform E-step assignment and M-step centroid computation', 'refactor the EM resolve_empty_clusters method to handle empty cluster reassignment with centroid splitting', 'summarize the EM save and load methods for persisting centroids and assignments to disk', 'build a python module that uses PQ to quantize fully connected layer weights with k-means centroids', 'build a python module that uses PQ to quantize convolutional layer weights with product quantization', 'run the PQ encode and decode cycle to quantize and reconstruct a weight matrix', 'review the PQ class _reshape method for handling 2D and 4D weight tensor reshaping', 'test the PQ encode method to handle EmptyClusterResolveError during k-means iterations', 'quantize a PyTorch model in-place by replacing targeted Linear, Conv2d, and Embedding layers with product quantization counterparts', 'filter model layers by regex pattern to select which layers to quantize while excluding biases', 'get the block size or centroid count for a module based on its type, feature attribute, or fuzzy name match', 'track compressed model size statistics including index size, centroid size, and compression ratio during quantization', 'set a nested attribute on a PyTorch module by resolving dot-separated attribute paths']
```

Usage

```
{'build_PQ_quantize_fc_weights': 'build a python module that uses PQ to quantize fully connected layer weights with k-means centroids', 'build_PQ_quantize_conv_weights': 'build a python module that uses PQ to quantize convolutional layer weights with product quantization', 'run_PQ_encode_decode': 'run the PQ encode and decode cycle to quantize and reconstruct a weight matrix', 'review_PQ_reshape': 'review the PQ class _reshape method for handling 2D and 4D weight tensor reshaping', 'test_PQ_empty_cluster': 'test the PQ encode method to handle EmptyClusterResolveError during k-means iterations'}
```

## File: facebookresearch_mega/fairseq/modules/quantization/pq/utils.py

Prompts

```
['run the EM algorithm to quantize a weight matrix W to n centroids using k-means iterations', 'build an EM instance and initialize centroids by sampling random columns from a weight matrix', 'test the EM step method to perform E-step assignment and M-step centroid computation', 'refactor the EM resolve_empty_clusters method to handle empty cluster reassignment with centroid splitting', 'summarize the EM save and load methods for persisting centroids and assignments to disk', 'build a python module that uses PQ to quantize fully connected layer weights with k-means centroids', 'build a python module that uses PQ to quantize convolutional layer weights with product quantization', 'run the PQ encode and decode cycle to quantize and reconstruct a weight matrix', 'review the PQ class _reshape method for handling 2D and 4D weight tensor reshaping', 'test the PQ encode method to handle EmptyClusterResolveError during k-means iterations', 'quantize a PyTorch model in-place by replacing targeted Linear, Conv2d, and Embedding layers with product quantization counterparts', 'filter model layers by regex pattern to select which layers to quantize while excluding biases', 'get the block size or centroid count for a module based on its type, feature attribute, or fuzzy name match', 'track compressed model size statistics including index size, centroid size, and compression ratio during quantization', 'set a nested attribute on a PyTorch module by resolving dot-separated attribute paths']
```

Usage

```
{'quantize_model_inplace': 'quantize a PyTorch model in-place by replacing targeted Linear, Conv2d, and Embedding layers with product quantization counterparts', 'filter_layers_by_regex': 'filter model layers by regex pattern to select which layers to quantize while excluding biases', 'get_quantization_param': 'get the block size or centroid count for a module based on its type, feature attribute, or fuzzy name match', 'track_compression_size': 'track compressed model size statistics including index size, centroid size, and compression ratio during quantization', 'set_nested_attribute': 'set a nested attribute on a PyTorch module by resolving dot-separated attribute paths'}
```

