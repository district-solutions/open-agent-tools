# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/fairseq/modules/quantization/pq/em.py

Prompts

```
['build a python module that uses the EM class to quantize a weight matrix with k-means clustering', 'run a single EM algorithm iteration on a weight matrix to update centroids and assignments', 'create and initialize centroids by sampling random columns from a weight matrix W', 'save EM centroids, assignments, and objective values to disk for a given layer', 'load previously saved EM centroids and assignments from disk for a given layer', 'build a product quantization model to quantize fully-connected layer weights using k-means centroids', 'build a product quantization model to quantize convolutional layer weights with configurable block size', 'run the PQ encode then decode cycle to reconstruct quantized weight matrices', 'review the PQ _reshape method that handles 2D and 4D weight tensor reshaping for quantization', 'refactor the PQ class to support dynamic block size selection based on weight tensor dimensions', 'quantize a PyTorch model in-place by replacing targeted Linear, Conv2d, and Embedding layers with Product Quantization counterparts', 'filter PyTorch model layers by a regex pattern to find which layers match for quantization', 'resolve the block size or number of centroids for a module from a quantization configuration dictionary', 'track compressed model size statistics including index size, centroid size, and compression ratio during quantization', 'set nested attributes on a PyTorch module by resolving a dotted path string to the target attribute']
```

Usage

```
{'build_EM_quantizer': 'build a python module that uses the EM class to quantize a weight matrix with k-means clustering', 'run_EM_step': 'run a single EM algorithm iteration on a weight matrix to update centroids and assignments', 'create_EM_centroids': 'create and initialize centroids by sampling random columns from a weight matrix W', 'save_EM_results': 'save EM centroids, assignments, and objective values to disk for a given layer', 'load_EM_centroids': 'load previously saved EM centroids and assignments from disk for a given layer'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/modules/quantization/pq/pq.py

Prompts

```
['build a python module that uses the EM class to quantize a weight matrix with k-means clustering', 'run a single EM algorithm iteration on a weight matrix to update centroids and assignments', 'create and initialize centroids by sampling random columns from a weight matrix W', 'save EM centroids, assignments, and objective values to disk for a given layer', 'load previously saved EM centroids and assignments from disk for a given layer', 'build a product quantization model to quantize fully-connected layer weights using k-means centroids', 'build a product quantization model to quantize convolutional layer weights with configurable block size', 'run the PQ encode then decode cycle to reconstruct quantized weight matrices', 'review the PQ _reshape method that handles 2D and 4D weight tensor reshaping for quantization', 'refactor the PQ class to support dynamic block size selection based on weight tensor dimensions', 'quantize a PyTorch model in-place by replacing targeted Linear, Conv2d, and Embedding layers with Product Quantization counterparts', 'filter PyTorch model layers by a regex pattern to find which layers match for quantization', 'resolve the block size or number of centroids for a module from a quantization configuration dictionary', 'track compressed model size statistics including index size, centroid size, and compression ratio during quantization', 'set nested attributes on a PyTorch module by resolving a dotted path string to the target attribute']
```

Usage

```
{'build_PQ_quantize_fc_weights': 'build a product quantization model to quantize fully-connected layer weights using k-means centroids', 'build_PQ_quantize_conv_weights': 'build a product quantization model to quantize convolutional layer weights with configurable block size', 'run_PQ_encode_decode': 'run the PQ encode then decode cycle to reconstruct quantized weight matrices', 'review_PQ_reshape': 'review the PQ _reshape method that handles 2D and 4D weight tensor reshaping for quantization', 'refactor_PQ_block_size': 'refactor the PQ class to support dynamic block size selection based on weight tensor dimensions'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/modules/quantization/pq/utils.py

Prompts

```
['build a python module that uses the EM class to quantize a weight matrix with k-means clustering', 'run a single EM algorithm iteration on a weight matrix to update centroids and assignments', 'create and initialize centroids by sampling random columns from a weight matrix W', 'save EM centroids, assignments, and objective values to disk for a given layer', 'load previously saved EM centroids and assignments from disk for a given layer', 'build a product quantization model to quantize fully-connected layer weights using k-means centroids', 'build a product quantization model to quantize convolutional layer weights with configurable block size', 'run the PQ encode then decode cycle to reconstruct quantized weight matrices', 'review the PQ _reshape method that handles 2D and 4D weight tensor reshaping for quantization', 'refactor the PQ class to support dynamic block size selection based on weight tensor dimensions', 'quantize a PyTorch model in-place by replacing targeted Linear, Conv2d, and Embedding layers with Product Quantization counterparts', 'filter PyTorch model layers by a regex pattern to find which layers match for quantization', 'resolve the block size or number of centroids for a module from a quantization configuration dictionary', 'track compressed model size statistics including index size, centroid size, and compression ratio during quantization', 'set nested attributes on a PyTorch module by resolving a dotted path string to the target attribute']
```

Usage

```
{'quantize_model_': 'quantize a PyTorch model in-place by replacing targeted Linear, Conv2d, and Embedding layers with Product Quantization counterparts', 'get_layers': 'filter PyTorch model layers by a regex pattern to find which layers match for quantization', 'get_param': 'resolve the block size or number of centroids for a module from a quantization configuration dictionary', 'SizeTracker': 'track compressed model size statistics including index size, centroid size, and compression ratio during quantization', 'attrsetter': 'set nested attributes on a PyTorch module by resolving a dotted path string to the target attribute'}
```

