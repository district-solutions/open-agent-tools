# Agent Python Tools

- repo: facebookresearch/audiocraft
- repo_uri: https://github.com/facebookresearch/audiocraft.git

## File: facebookresearch_audiocraft/audiocraft/quantization/base.py

Prompts

```
['create a QuantizedResult dataclass with tensor x, codes, bandwidth, optional penalty, and metrics dict', 'implement a custom quantizer by subclassing BaseQuantizer and overriding forward, encode, decode, and codebook properties', 'use DummyQuantizer forward method to pass a tensor and frame rate and get a QuantizedResult with computed bandwidth', 'encode a tensor with DummyQuantizer to get codes then decode the codes back to the quantized representation', 'review the BaseQuantizer abstract class API including forward, encode, decode, total_codebooks, num_codebooks, and set_num_codebooks', 'build a EuclideanCodebook module with a given dimension and codebook size for vector quantization', 'build a VectorQuantization module with optional kmeans initialization and orthogonal regularization for audio quantization', 'build a ResidualVectorQuantization module with multiple quantizer layers following the SoundStream algorithm', 'run the kmeans function on sample tensors to compute cluster centroids and bin counts', 'run the orthogonal_loss_fn on a codebook tensor to compute cosine similarity based orthogonality loss', 'build a ResidualVectorQuantizer with custom dimension, codebook size, and number of quantizers', 'encode an input tensor into discrete codes using the ResidualVectorQuantizer encode method', 'decode discrete codes back to a quantized tensor using the ResidualVectorQuantizer decode method', 'run a forward pass through the ResidualVectorQuantizer with an input tensor and frame rate', 'set the number of active codebooks on a ResidualVectorQuantizer instance to control bandwidth']
```

Usage

```
{'create_quantized_result': 'create a QuantizedResult dataclass with tensor x, codes, bandwidth, optional penalty, and metrics dict', 'implement_custom_quantizer': 'implement a custom quantizer by subclassing BaseQuantizer and overriding forward, encode, decode, and codebook properties', 'use_dummy_quantizer_forward': 'use DummyQuantizer forward method to pass a tensor and frame rate and get a QuantizedResult with computed bandwidth', 'encode_decode_with_dummy_quantizer': 'encode a tensor with DummyQuantizer to get codes then decode the codes back to the quantized representation', 'review_base_quantizer_api': 'review the BaseQuantizer abstract class API including forward, encode, decode, total_codebooks, num_codebooks, and set_num_codebooks'}
```

## File: facebookresearch_audiocraft/audiocraft/quantization/core_vq.py

Prompts

```
['create a QuantizedResult dataclass with tensor x, codes, bandwidth, optional penalty, and metrics dict', 'implement a custom quantizer by subclassing BaseQuantizer and overriding forward, encode, decode, and codebook properties', 'use DummyQuantizer forward method to pass a tensor and frame rate and get a QuantizedResult with computed bandwidth', 'encode a tensor with DummyQuantizer to get codes then decode the codes back to the quantized representation', 'review the BaseQuantizer abstract class API including forward, encode, decode, total_codebooks, num_codebooks, and set_num_codebooks', 'build a EuclideanCodebook module with a given dimension and codebook size for vector quantization', 'build a VectorQuantization module with optional kmeans initialization and orthogonal regularization for audio quantization', 'build a ResidualVectorQuantization module with multiple quantizer layers following the SoundStream algorithm', 'run the kmeans function on sample tensors to compute cluster centroids and bin counts', 'run the orthogonal_loss_fn on a codebook tensor to compute cosine similarity based orthogonality loss', 'build a ResidualVectorQuantizer with custom dimension, codebook size, and number of quantizers', 'encode an input tensor into discrete codes using the ResidualVectorQuantizer encode method', 'decode discrete codes back to a quantized tensor using the ResidualVectorQuantizer decode method', 'run a forward pass through the ResidualVectorQuantizer with an input tensor and frame rate', 'set the number of active codebooks on a ResidualVectorQuantizer instance to control bandwidth']
```

Usage

```
{'build_EuclideanCodebook': 'build a EuclideanCodebook module with a given dimension and codebook size for vector quantization', 'build_VectorQuantization': 'build a VectorQuantization module with optional kmeans initialization and orthogonal regularization for audio quantization', 'build_ResidualVectorQuantization': 'build a ResidualVectorQuantization module with multiple quantizer layers following the SoundStream algorithm', 'run_kmeans': 'run the kmeans function on sample tensors to compute cluster centroids and bin counts', 'run_orthogonal_loss_fn': 'run the orthogonal_loss_fn on a codebook tensor to compute cosine similarity based orthogonality loss'}
```

## File: facebookresearch_audiocraft/audiocraft/quantization/vq.py

Prompts

```
['create a QuantizedResult dataclass with tensor x, codes, bandwidth, optional penalty, and metrics dict', 'implement a custom quantizer by subclassing BaseQuantizer and overriding forward, encode, decode, and codebook properties', 'use DummyQuantizer forward method to pass a tensor and frame rate and get a QuantizedResult with computed bandwidth', 'encode a tensor with DummyQuantizer to get codes then decode the codes back to the quantized representation', 'review the BaseQuantizer abstract class API including forward, encode, decode, total_codebooks, num_codebooks, and set_num_codebooks', 'build a EuclideanCodebook module with a given dimension and codebook size for vector quantization', 'build a VectorQuantization module with optional kmeans initialization and orthogonal regularization for audio quantization', 'build a ResidualVectorQuantization module with multiple quantizer layers following the SoundStream algorithm', 'run the kmeans function on sample tensors to compute cluster centroids and bin counts', 'run the orthogonal_loss_fn on a codebook tensor to compute cosine similarity based orthogonality loss', 'build a ResidualVectorQuantizer with custom dimension, codebook size, and number of quantizers', 'encode an input tensor into discrete codes using the ResidualVectorQuantizer encode method', 'decode discrete codes back to a quantized tensor using the ResidualVectorQuantizer decode method', 'run a forward pass through the ResidualVectorQuantizer with an input tensor and frame rate', 'set the number of active codebooks on a ResidualVectorQuantizer instance to control bandwidth']
```

Usage

```
{'build_rvq_quantizer': 'build a ResidualVectorQuantizer with custom dimension, codebook size, and number of quantizers', 'encode_audio_tensor': 'encode an input tensor into discrete codes using the ResidualVectorQuantizer encode method', 'decode_codes_to_tensor': 'decode discrete codes back to a quantized tensor using the ResidualVectorQuantizer decode method', 'run_rvq_forward_pass': 'run a forward pass through the ResidualVectorQuantizer with an input tensor and frame rate', 'set_num_codebooks': 'set the number of active codebooks on a ResidualVectorQuantizer instance to control bandwidth'}
```

