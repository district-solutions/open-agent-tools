# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/fairseq/modules/quantization/pq/em.py

Prompts

```
['run the EM algorithm to quantize a weight matrix W to k centroids minimizing reconstruction error', 'run a single EM iteration performing E-step assignment and M-step centroid update on the weight matrix', 'run the empty cluster resolution logic that splits the most populated cluster to fill empty ones', 'run the distance computation between all centroids and weight matrix columns using PyTorch broadcasting', 'run the EM save and load methods to persist and restore centroids, assignments, and objective history', 'build a product quantization model to quantize neural network layer weights using k-means centroids', 'create a PQ encoder to perform EM steps and learn centroids from weight matrices', 'run the PQ decode method to reconstruct the quantized weight matrix from centroids and assignments', 'review the PQ reshape method that handles fully connected and convolutional weight matrix reshaping', 'test the PQ class to quantize a 2D or 4D weight tensor with configurable block size and centroids', 'quantize a PyTorch model in-place by replacing targeted layers with product quantization counterparts', 'filter model layers by regex pattern to select which layers to quantize while omitting biases', 'get the block size or centroid count for a module based on its type and feature configuration', 'track compressed model size statistics including index size, centroid size, and compression ratio during quantization', 'set a nested attribute on a PyTorch module by resolving dotted attribute paths dynamically']
```

Usage

```
{'run_EM_quantize_weight_matrix': 'run the EM algorithm to quantize a weight matrix W to k centroids minimizing reconstruction error', 'run_EM_step': 'run a single EM iteration performing E-step assignment and M-step centroid update on the weight matrix', 'run_EM_resolve_empty_clusters': 'run the empty cluster resolution logic that splits the most populated cluster to fill empty ones', 'run_EM_compute_distances': 'run the distance computation between all centroids and weight matrix columns using PyTorch broadcasting', 'run_EM_save_load': 'run the EM save and load methods to persist and restore centroids, assignments, and objective history'}
```

## File: facebookresearch_fairseq/fairseq/modules/quantization/pq/pq.py

Prompts

```
['run the EM algorithm to quantize a weight matrix W to k centroids minimizing reconstruction error', 'run a single EM iteration performing E-step assignment and M-step centroid update on the weight matrix', 'run the empty cluster resolution logic that splits the most populated cluster to fill empty ones', 'run the distance computation between all centroids and weight matrix columns using PyTorch broadcasting', 'run the EM save and load methods to persist and restore centroids, assignments, and objective history', 'build a product quantization model to quantize neural network layer weights using k-means centroids', 'create a PQ encoder to perform EM steps and learn centroids from weight matrices', 'run the PQ decode method to reconstruct the quantized weight matrix from centroids and assignments', 'review the PQ reshape method that handles fully connected and convolutional weight matrix reshaping', 'test the PQ class to quantize a 2D or 4D weight tensor with configurable block size and centroids', 'quantize a PyTorch model in-place by replacing targeted layers with product quantization counterparts', 'filter model layers by regex pattern to select which layers to quantize while omitting biases', 'get the block size or centroid count for a module based on its type and feature configuration', 'track compressed model size statistics including index size, centroid size, and compression ratio during quantization', 'set a nested attribute on a PyTorch module by resolving dotted attribute paths dynamically']
```

Usage

```
{'build_pq_quantizer': 'build a product quantization model to quantize neural network layer weights using k-means centroids', 'create_pq_encode': 'create a PQ encoder to perform EM steps and learn centroids from weight matrices', 'run_pq_decode': 'run the PQ decode method to reconstruct the quantized weight matrix from centroids and assignments', 'review_pq_reshape': 'review the PQ reshape method that handles fully connected and convolutional weight matrix reshaping', 'test_pq_quantization': 'test the PQ class to quantize a 2D or 4D weight tensor with configurable block size and centroids'}
```

## File: facebookresearch_fairseq/fairseq/modules/quantization/pq/utils.py

Prompts

```
['run the EM algorithm to quantize a weight matrix W to k centroids minimizing reconstruction error', 'run a single EM iteration performing E-step assignment and M-step centroid update on the weight matrix', 'run the empty cluster resolution logic that splits the most populated cluster to fill empty ones', 'run the distance computation between all centroids and weight matrix columns using PyTorch broadcasting', 'run the EM save and load methods to persist and restore centroids, assignments, and objective history', 'build a product quantization model to quantize neural network layer weights using k-means centroids', 'create a PQ encoder to perform EM steps and learn centroids from weight matrices', 'run the PQ decode method to reconstruct the quantized weight matrix from centroids and assignments', 'review the PQ reshape method that handles fully connected and convolutional weight matrix reshaping', 'test the PQ class to quantize a 2D or 4D weight tensor with configurable block size and centroids', 'quantize a PyTorch model in-place by replacing targeted layers with product quantization counterparts', 'filter model layers by regex pattern to select which layers to quantize while omitting biases', 'get the block size or centroid count for a module based on its type and feature configuration', 'track compressed model size statistics including index size, centroid size, and compression ratio during quantization', 'set a nested attribute on a PyTorch module by resolving dotted attribute paths dynamically']
```

Usage

```
{'quantize_model_inplace': 'quantize a PyTorch model in-place by replacing targeted layers with product quantization counterparts', 'filter_layers_by_regex': 'filter model layers by regex pattern to select which layers to quantize while omitting biases', 'get_quantization_param': 'get the block size or centroid count for a module based on its type and feature configuration', 'track_compression_size': 'track compressed model size statistics including index size, centroid size, and compression ratio during quantization', 'set_nested_attribute': 'set a nested attribute on a PyTorch module by resolving dotted attribute paths dynamically'}
```

