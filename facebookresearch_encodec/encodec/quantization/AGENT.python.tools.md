# Agent Python Tools

- repo: facebookresearch/encodec
- repo_uri: https://github.com/facebookresearch/encodec

## File: facebookresearch_encodec/encodec/quantization/ac.py

Prompts

```
['build a quantized CDF from a PDF tensor for arithmetic coding with configurable range bits', 'create an ArithmeticCoder instance to encode symbols into a compressed bit stream on a file object', 'encode a sequence of symbols by pushing each symbol with its quantized CDF to the coder', 'decode symbols from a compressed bit stream by pulling each symbol with its matching quantized CDF', 'test the arithmetic coder and decoder by encoding then decoding random symbols and verifying correctness', 'build a ResidualVectorQuantization model with multiple quantizer layers for audio feature quantization', 'create a EuclideanCodebook with k-means initialization and dead code expiration for vector quantization', 'run the kmeans function to cluster sample vectors into centroids for codebook initialization', 'test the VectorQuantization class encode and decode methods with a batch of feature tensors', 'review the ResidualVectorQuantization forward pass that iteratively quantizes residuals across layers', 'build a ResidualVectorQuantizer with custom dimension, n_q, bins, and decay parameters for audio quantization', 'run forward pass on input tensor through ResidualVectorQuantizer with frame rate and optional bandwidth target', 'encode a torch tensor into discrete codes using ResidualVectorQuantizer encode method with target bandwidth', 'decode quantized codes back to a tensor representation using ResidualVectorQuantizer decode method', 'calculate the bandwidth per quantizer for a given frame rate using get_bandwidth_per_quantizer method']
```

Usage

```
{'build_stable_quantized_cdf': 'build a quantized CDF from a PDF tensor for arithmetic coding with configurable range bits', 'create_arithmetic_coder': 'create an ArithmeticCoder instance to encode symbols into a compressed bit stream on a file object', 'encode_symbols_with_push': 'encode a sequence of symbols by pushing each symbol with its quantized CDF to the coder', 'decode_symbols_with_pull': 'decode symbols from a compressed bit stream by pulling each symbol with its matching quantized CDF', 'test_arithmetic_coding_roundtrip': 'test the arithmetic coder and decoder by encoding then decoding random symbols and verifying correctness'}
```

## File: facebookresearch_encodec/encodec/quantization/core_vq.py

Prompts

```
['build a quantized CDF from a PDF tensor for arithmetic coding with configurable range bits', 'create an ArithmeticCoder instance to encode symbols into a compressed bit stream on a file object', 'encode a sequence of symbols by pushing each symbol with its quantized CDF to the coder', 'decode symbols from a compressed bit stream by pulling each symbol with its matching quantized CDF', 'test the arithmetic coder and decoder by encoding then decoding random symbols and verifying correctness', 'build a ResidualVectorQuantization model with multiple quantizer layers for audio feature quantization', 'create a EuclideanCodebook with k-means initialization and dead code expiration for vector quantization', 'run the kmeans function to cluster sample vectors into centroids for codebook initialization', 'test the VectorQuantization class encode and decode methods with a batch of feature tensors', 'review the ResidualVectorQuantization forward pass that iteratively quantizes residuals across layers', 'build a ResidualVectorQuantizer with custom dimension, n_q, bins, and decay parameters for audio quantization', 'run forward pass on input tensor through ResidualVectorQuantizer with frame rate and optional bandwidth target', 'encode a torch tensor into discrete codes using ResidualVectorQuantizer encode method with target bandwidth', 'decode quantized codes back to a tensor representation using ResidualVectorQuantizer decode method', 'calculate the bandwidth per quantizer for a given frame rate using get_bandwidth_per_quantizer method']
```

Usage

```
{'build_residual_vq_model': 'build a ResidualVectorQuantization model with multiple quantizer layers for audio feature quantization', 'create_euclidean_codebook': 'create a EuclideanCodebook with k-means initialization and dead code expiration for vector quantization', 'run_kmeans_clustering': 'run the kmeans function to cluster sample vectors into centroids for codebook initialization', 'test_vector_quantization': 'test the VectorQuantization class encode and decode methods with a batch of feature tensors', 'review_rvq_forward': 'review the ResidualVectorQuantization forward pass that iteratively quantizes residuals across layers'}
```

## File: facebookresearch_encodec/encodec/quantization/vq.py

Prompts

```
['build a quantized CDF from a PDF tensor for arithmetic coding with configurable range bits', 'create an ArithmeticCoder instance to encode symbols into a compressed bit stream on a file object', 'encode a sequence of symbols by pushing each symbol with its quantized CDF to the coder', 'decode symbols from a compressed bit stream by pulling each symbol with its matching quantized CDF', 'test the arithmetic coder and decoder by encoding then decoding random symbols and verifying correctness', 'build a ResidualVectorQuantization model with multiple quantizer layers for audio feature quantization', 'create a EuclideanCodebook with k-means initialization and dead code expiration for vector quantization', 'run the kmeans function to cluster sample vectors into centroids for codebook initialization', 'test the VectorQuantization class encode and decode methods with a batch of feature tensors', 'review the ResidualVectorQuantization forward pass that iteratively quantizes residuals across layers', 'build a ResidualVectorQuantizer with custom dimension, n_q, bins, and decay parameters for audio quantization', 'run forward pass on input tensor through ResidualVectorQuantizer with frame rate and optional bandwidth target', 'encode a torch tensor into discrete codes using ResidualVectorQuantizer encode method with target bandwidth', 'decode quantized codes back to a tensor representation using ResidualVectorQuantizer decode method', 'calculate the bandwidth per quantizer for a given frame rate using get_bandwidth_per_quantizer method']
```

Usage

```
{'build_residual_vector_quantizer': 'build a ResidualVectorQuantizer with custom dimension, n_q, bins, and decay parameters for audio quantization', 'run_forward_quantization': 'run forward pass on input tensor through ResidualVectorQuantizer with frame rate and optional bandwidth target', 'encode_tensor_with_rvq': 'encode a torch tensor into discrete codes using ResidualVectorQuantizer encode method with target bandwidth', 'decode_codes_to_tensor': 'decode quantized codes back to a tensor representation using ResidualVectorQuantizer decode method', 'calculate_bandwidth_per_quantizer': 'calculate the bandwidth per quantizer for a given frame rate using get_bandwidth_per_quantizer method'}
```

