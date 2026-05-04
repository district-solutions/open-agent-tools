# Agent Python Tools

- repo: facebookresearch/audioseal
- repo_uri: https://github.com/facebookresearch/audioseal

## File: facebookresearch_audioseal/src/audioseal/libs/moshi/quantization/base.py

Prompts

```
['create a DummyQuantizer instance with a specified dimension for no-op quantization', 'encode an input tensor using the DummyQuantizer encode method to get codes', 'decode codes back to a tensor using the DummyQuantizer decode method', 'run the DummyQuantizer forward pass with a tensor and frame rate to get QuantizedResult', 'set whether EMA is frozen on a BaseQuantizer using the ema_frozen_ method', 'build a EuclideanCodebook with a given dimension and codebook size for nearest centroid lookup', 'encode a tensor of shape [B, D, N] into discrete integer codes using VectorQuantization', 'decode integer codes back into quantized vectors using the VectorQuantization decode method', 'encode an input tensor into stacked integer codes across multiple RVQ quantizer layers', 'decode stacked integer codes from RVQ back into reconstructed quantized vectors', 'build a ResidualVectorQuantizer with custom dimension, codebook size, and number of quantizers for audio encoding', 'encode an input tensor into discrete codes using the ResidualVectorQuantizer encode method', 'decode discrete codes back to quantized tensor using the ResidualVectorQuantizer decode method', 'build a SplitResidualVectorQuantizer with separate semantic and acoustic quantizers for hierarchical audio encoding', 'set the number of active codebooks on a ResidualVectorQuantizer to control bandwidth and quantization depth']
```

Usage

```
{'create_DummyQuantizer': 'create a DummyQuantizer instance with a specified dimension for no-op quantization', 'encode_DummyQuantizer': 'encode an input tensor using the DummyQuantizer encode method to get codes', 'decode_DummyQuantizer': 'decode codes back to a tensor using the DummyQuantizer decode method', 'forward_DummyQuantizer': 'run the DummyQuantizer forward pass with a tensor and frame rate to get QuantizedResult', 'set_ema_frozen_BaseQuantizer': 'set whether EMA is frozen on a BaseQuantizer using the ema_frozen_ method'}
```

## File: facebookresearch_audioseal/src/audioseal/libs/moshi/quantization/core_vq.py

Prompts

```
['create a DummyQuantizer instance with a specified dimension for no-op quantization', 'encode an input tensor using the DummyQuantizer encode method to get codes', 'decode codes back to a tensor using the DummyQuantizer decode method', 'run the DummyQuantizer forward pass with a tensor and frame rate to get QuantizedResult', 'set whether EMA is frozen on a BaseQuantizer using the ema_frozen_ method', 'build a EuclideanCodebook with a given dimension and codebook size for nearest centroid lookup', 'encode a tensor of shape [B, D, N] into discrete integer codes using VectorQuantization', 'decode integer codes back into quantized vectors using the VectorQuantization decode method', 'encode an input tensor into stacked integer codes across multiple RVQ quantizer layers', 'decode stacked integer codes from RVQ back into reconstructed quantized vectors', 'build a ResidualVectorQuantizer with custom dimension, codebook size, and number of quantizers for audio encoding', 'encode an input tensor into discrete codes using the ResidualVectorQuantizer encode method', 'decode discrete codes back to quantized tensor using the ResidualVectorQuantizer decode method', 'build a SplitResidualVectorQuantizer with separate semantic and acoustic quantizers for hierarchical audio encoding', 'set the number of active codebooks on a ResidualVectorQuantizer to control bandwidth and quantization depth']
```

Usage

```
{'build_EuclideanCodebook': 'build a EuclideanCodebook with a given dimension and codebook size for nearest centroid lookup', 'encode_VectorQuantization': 'encode a tensor of shape [B, D, N] into discrete integer codes using VectorQuantization', 'decode_VectorQuantization': 'decode integer codes back into quantized vectors using the VectorQuantization decode method', 'encode_ResidualVectorQuantization': 'encode an input tensor into stacked integer codes across multiple RVQ quantizer layers', 'decode_ResidualVectorQuantization': 'decode stacked integer codes from RVQ back into reconstructed quantized vectors'}
```

## File: facebookresearch_audioseal/src/audioseal/libs/moshi/quantization/vq.py

Prompts

```
['create a DummyQuantizer instance with a specified dimension for no-op quantization', 'encode an input tensor using the DummyQuantizer encode method to get codes', 'decode codes back to a tensor using the DummyQuantizer decode method', 'run the DummyQuantizer forward pass with a tensor and frame rate to get QuantizedResult', 'set whether EMA is frozen on a BaseQuantizer using the ema_frozen_ method', 'build a EuclideanCodebook with a given dimension and codebook size for nearest centroid lookup', 'encode a tensor of shape [B, D, N] into discrete integer codes using VectorQuantization', 'decode integer codes back into quantized vectors using the VectorQuantization decode method', 'encode an input tensor into stacked integer codes across multiple RVQ quantizer layers', 'decode stacked integer codes from RVQ back into reconstructed quantized vectors', 'build a ResidualVectorQuantizer with custom dimension, codebook size, and number of quantizers for audio encoding', 'encode an input tensor into discrete codes using the ResidualVectorQuantizer encode method', 'decode discrete codes back to quantized tensor using the ResidualVectorQuantizer decode method', 'build a SplitResidualVectorQuantizer with separate semantic and acoustic quantizers for hierarchical audio encoding', 'set the number of active codebooks on a ResidualVectorQuantizer to control bandwidth and quantization depth']
```

Usage

```
{'build_rvq_quantizer': 'build a ResidualVectorQuantizer with custom dimension, codebook size, and number of quantizers for audio encoding', 'encode_audio_with_rvq': 'encode an input tensor into discrete codes using the ResidualVectorQuantizer encode method', 'decode_rvq_codes': 'decode discrete codes back to quantized tensor using the ResidualVectorQuantizer decode method', 'build_split_rvq_quantizer': 'build a SplitResidualVectorQuantizer with separate semantic and acoustic quantizers for hierarchical audio encoding', 'set_rvq_codebooks': 'set the number of active codebooks on a ResidualVectorQuantizer to control bandwidth and quantization depth'}
```

