# Agent Python Tools

- repo: facebookresearch/neuralcompression
- repo_uri: https://github.com/facebookresearch/neuralcompression

## File: facebookresearch_neuralcompression/tests/layers/test_channelnorm.py

Prompts

```
['test the ChannelNorm2D layer with affine parameters enabled using pytest', 'test the ChannelNorm2D layer with affine parameters disabled using pytest', 'review the ChannelNorm2D forward pass that normalizes input tensors per channel', 'review the parametrized test that validates ChannelNorm2D output against manual normalization math', 'summarize the ChannelNorm2D class that implements channel normalization for image compression models', 'create a ContinuousEntropy layer using a NoisyNormal prior distribution for entropy coding', 'create a ContinuousEntropy layer by specifying prior_shape and prior_dtype instead of a prior distribution', 'create a compressible ContinuousEntropy layer with CDF tables for range encoding and decoding', 'test the prior_shape, prior_dtype, tail_mass, and range_coder_precision properties of a ContinuousEntropy layer', 'use the ContinuousEntropy quantize static method to round a floating-point tensor to integer values']
```

Usage

```
{'test_ChannelNorm2D_affine': 'test the ChannelNorm2D layer with affine parameters enabled using pytest', 'test_ChannelNorm2D_no_affine': 'test the ChannelNorm2D layer with affine parameters disabled using pytest', 'review_ChannelNorm2D_forward': 'review the ChannelNorm2D forward pass that normalizes input tensors per channel', 'review_test_channel_norm_2d': 'review the parametrized test that validates ChannelNorm2D output against manual normalization math', 'summarize_ChannelNorm2D': 'summarize the ChannelNorm2D class that implements channel normalization for image compression models'}
```

## File: facebookresearch_neuralcompression/tests/layers/test_continuous_entropy.py

Prompts

```
['test the ChannelNorm2D layer with affine parameters enabled using pytest', 'test the ChannelNorm2D layer with affine parameters disabled using pytest', 'review the ChannelNorm2D forward pass that normalizes input tensors per channel', 'review the parametrized test that validates ChannelNorm2D output against manual normalization math', 'summarize the ChannelNorm2D class that implements channel normalization for image compression models', 'create a ContinuousEntropy layer using a NoisyNormal prior distribution for entropy coding', 'create a ContinuousEntropy layer by specifying prior_shape and prior_dtype instead of a prior distribution', 'create a compressible ContinuousEntropy layer with CDF tables for range encoding and decoding', 'test the prior_shape, prior_dtype, tail_mass, and range_coder_precision properties of a ContinuousEntropy layer', 'use the ContinuousEntropy quantize static method to round a floating-point tensor to integer values']
```

Usage

```
{'init_continuous_entropy_with_prior': 'create a ContinuousEntropy layer using a NoisyNormal prior distribution for entropy coding', 'init_continuous_entropy_with_shape_dtype': 'create a ContinuousEntropy layer by specifying prior_shape and prior_dtype instead of a prior distribution', 'init_compressible_continuous_entropy': 'create a compressible ContinuousEntropy layer with CDF tables for range encoding and decoding', 'test_continuous_entropy_properties': 'test the prior_shape, prior_dtype, tail_mass, and range_coder_precision properties of a ContinuousEntropy layer', 'quantize_bottleneck_tensor': 'use the ContinuousEntropy quantize static method to round a floating-point tensor to integer values'}
```

