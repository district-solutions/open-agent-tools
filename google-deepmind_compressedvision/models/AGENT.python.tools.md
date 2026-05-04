# Agent Python Tools

- repo: google-deepmind/compressedvision
- repo_uri: https://github.com/google-deepmind/compressed_vision

## File: google-deepmind_compressedvision/models/encoder_decoder_unet.py

Prompts

```
['build a Haiku VQGAN-style 3D convolutional encoder/decoder model with vector quantization for video compression', 'create a CompressionConvEncoderDecoder instance with configurable channels, codebooks, and VQ parameters for video encoding', 'encode a video tensor into discrete VQ codes using the CompressionConvEncoderDecoder encode method', 'decode discrete VQ codes back into reconstructed video logits using the CompressionConvEncoderDecoder decode method', 'run the full embed, quantize, and reconstruct pipeline by calling the CompressionConvEncoderDecoder model directly', 'build a NeuralTransformation module that uses a transformer to transform latent codes for video data', 'create a call to NeuralTransformation that transforms video tensors using augmentation parameters and a spatio-temporal transformer', "create a call to get_equivariant_network with name 'transformer' to return the NeuralTransformation class", 'review the NeuralTransformation __init__ to understand transformer hyperparameters like channels, heads, and layer sizes', 'summarize the NeuralTransformation __call__ method that processes video and augmentation through an MLP and transformer', 'create a Haiku batch normalization layer with custom decay rate and test local stats', 'get a batch normalization function using get_normalize_fn with the batch_norm normalizer name', 'get a normalization function with custom kwargs like decay rate passed to the constructor', 'review the _BatchNorm class that extends hk.BatchNorm with adapted default arguments', 'test the get_normalize_fn function with an unrecognized normalizer name to verify ValueError is raised', 'build a SpatioTemporalTransformerXL module with configurable layers, heads, and dropout for compressed vision', 'create a DenseBlock Haiku module with configurable hidden size, activation, and dropout for feed-forward layers', 'review the SpaceTimeMultiHeadAttention class to understand space and time attention modes with multi-head einsum', 'refactor the spatio_temporal_gpt2_block function to add custom residual connections or layer norm options', 'test the _get_position_embedding method to verify absolute positional embeddings are applied correctly']
```

Usage

```
{'build_vqgan_encoder_decoder': 'build a Haiku VQGAN-style 3D convolutional encoder/decoder model with vector quantization for video compression', 'create_compression_model': 'create a CompressionConvEncoderDecoder instance with configurable channels, codebooks, and VQ parameters for video encoding', 'encode_video_to_codes': 'encode a video tensor into discrete VQ codes using the CompressionConvEncoderDecoder encode method', 'decode_codes_to_video': 'decode discrete VQ codes back into reconstructed video logits using the CompressionConvEncoderDecoder decode method', 'run_full_compression_pipeline': 'run the full embed, quantize, and reconstruct pipeline by calling the CompressionConvEncoderDecoder model directly'}
```

## File: google-deepmind_compressedvision/models/equivariant_networks.py

Prompts

```
['build a Haiku VQGAN-style 3D convolutional encoder/decoder model with vector quantization for video compression', 'create a CompressionConvEncoderDecoder instance with configurable channels, codebooks, and VQ parameters for video encoding', 'encode a video tensor into discrete VQ codes using the CompressionConvEncoderDecoder encode method', 'decode discrete VQ codes back into reconstructed video logits using the CompressionConvEncoderDecoder decode method', 'run the full embed, quantize, and reconstruct pipeline by calling the CompressionConvEncoderDecoder model directly', 'build a NeuralTransformation module that uses a transformer to transform latent codes for video data', 'create a call to NeuralTransformation that transforms video tensors using augmentation parameters and a spatio-temporal transformer', "create a call to get_equivariant_network with name 'transformer' to return the NeuralTransformation class", 'review the NeuralTransformation __init__ to understand transformer hyperparameters like channels, heads, and layer sizes', 'summarize the NeuralTransformation __call__ method that processes video and augmentation through an MLP and transformer', 'create a Haiku batch normalization layer with custom decay rate and test local stats', 'get a batch normalization function using get_normalize_fn with the batch_norm normalizer name', 'get a normalization function with custom kwargs like decay rate passed to the constructor', 'review the _BatchNorm class that extends hk.BatchNorm with adapted default arguments', 'test the get_normalize_fn function with an unrecognized normalizer name to verify ValueError is raised', 'build a SpatioTemporalTransformerXL module with configurable layers, heads, and dropout for compressed vision', 'create a DenseBlock Haiku module with configurable hidden size, activation, and dropout for feed-forward layers', 'review the SpaceTimeMultiHeadAttention class to understand space and time attention modes with multi-head einsum', 'refactor the spatio_temporal_gpt2_block function to add custom residual connections or layer norm options', 'test the _get_position_embedding method to verify absolute positional embeddings are applied correctly']
```

Usage

```
{'build_NeuralTransformation': 'build a NeuralTransformation module that uses a transformer to transform latent codes for video data', 'create_NeuralTransformation_call': 'create a call to NeuralTransformation that transforms video tensors using augmentation parameters and a spatio-temporal transformer', 'create_get_equivariant_network': "create a call to get_equivariant_network with name 'transformer' to return the NeuralTransformation class", 'review_NeuralTransformation_init': 'review the NeuralTransformation __init__ to understand transformer hyperparameters like channels, heads, and layer sizes', 'summarize_NeuralTransformation_call': 'summarize the NeuralTransformation __call__ method that processes video and augmentation through an MLP and transformer'}
```

## File: google-deepmind_compressedvision/models/normalization.py

Prompts

```
['build a Haiku VQGAN-style 3D convolutional encoder/decoder model with vector quantization for video compression', 'create a CompressionConvEncoderDecoder instance with configurable channels, codebooks, and VQ parameters for video encoding', 'encode a video tensor into discrete VQ codes using the CompressionConvEncoderDecoder encode method', 'decode discrete VQ codes back into reconstructed video logits using the CompressionConvEncoderDecoder decode method', 'run the full embed, quantize, and reconstruct pipeline by calling the CompressionConvEncoderDecoder model directly', 'build a NeuralTransformation module that uses a transformer to transform latent codes for video data', 'create a call to NeuralTransformation that transforms video tensors using augmentation parameters and a spatio-temporal transformer', "create a call to get_equivariant_network with name 'transformer' to return the NeuralTransformation class", 'review the NeuralTransformation __init__ to understand transformer hyperparameters like channels, heads, and layer sizes', 'summarize the NeuralTransformation __call__ method that processes video and augmentation through an MLP and transformer', 'create a Haiku batch normalization layer with custom decay rate and test local stats', 'get a batch normalization function using get_normalize_fn with the batch_norm normalizer name', 'get a normalization function with custom kwargs like decay rate passed to the constructor', 'review the _BatchNorm class that extends hk.BatchNorm with adapted default arguments', 'test the get_normalize_fn function with an unrecognized normalizer name to verify ValueError is raised', 'build a SpatioTemporalTransformerXL module with configurable layers, heads, and dropout for compressed vision', 'create a DenseBlock Haiku module with configurable hidden size, activation, and dropout for feed-forward layers', 'review the SpaceTimeMultiHeadAttention class to understand space and time attention modes with multi-head einsum', 'refactor the spatio_temporal_gpt2_block function to add custom residual connections or layer norm options', 'test the _get_position_embedding method to verify absolute positional embeddings are applied correctly']
```

Usage

```
{'create_batchnorm_layer': 'create a Haiku batch normalization layer with custom decay rate and test local stats', 'get_normalize_fn_batch_norm': 'get a batch normalization function using get_normalize_fn with the batch_norm normalizer name', 'get_normalize_fn_custom_kwargs': 'get a normalization function with custom kwargs like decay rate passed to the constructor', 'review_BatchNorm_class': 'review the _BatchNorm class that extends hk.BatchNorm with adapted default arguments', 'test_get_normalize_fn': 'test the get_normalize_fn function with an unrecognized normalizer name to verify ValueError is raised'}
```

## File: google-deepmind_compressedvision/models/transformer.py

Prompts

```
['build a Haiku VQGAN-style 3D convolutional encoder/decoder model with vector quantization for video compression', 'create a CompressionConvEncoderDecoder instance with configurable channels, codebooks, and VQ parameters for video encoding', 'encode a video tensor into discrete VQ codes using the CompressionConvEncoderDecoder encode method', 'decode discrete VQ codes back into reconstructed video logits using the CompressionConvEncoderDecoder decode method', 'run the full embed, quantize, and reconstruct pipeline by calling the CompressionConvEncoderDecoder model directly', 'build a NeuralTransformation module that uses a transformer to transform latent codes for video data', 'create a call to NeuralTransformation that transforms video tensors using augmentation parameters and a spatio-temporal transformer', "create a call to get_equivariant_network with name 'transformer' to return the NeuralTransformation class", 'review the NeuralTransformation __init__ to understand transformer hyperparameters like channels, heads, and layer sizes', 'summarize the NeuralTransformation __call__ method that processes video and augmentation through an MLP and transformer', 'create a Haiku batch normalization layer with custom decay rate and test local stats', 'get a batch normalization function using get_normalize_fn with the batch_norm normalizer name', 'get a normalization function with custom kwargs like decay rate passed to the constructor', 'review the _BatchNorm class that extends hk.BatchNorm with adapted default arguments', 'test the get_normalize_fn function with an unrecognized normalizer name to verify ValueError is raised', 'build a SpatioTemporalTransformerXL module with configurable layers, heads, and dropout for compressed vision', 'create a DenseBlock Haiku module with configurable hidden size, activation, and dropout for feed-forward layers', 'review the SpaceTimeMultiHeadAttention class to understand space and time attention modes with multi-head einsum', 'refactor the spatio_temporal_gpt2_block function to add custom residual connections or layer norm options', 'test the _get_position_embedding method to verify absolute positional embeddings are applied correctly']
```

Usage

```
{'build_spatiotemporal_transformer': 'build a SpatioTemporalTransformerXL module with configurable layers, heads, and dropout for compressed vision', 'create_dense_block': 'create a DenseBlock Haiku module with configurable hidden size, activation, and dropout for feed-forward layers', 'review_spacetime_attention': 'review the SpaceTimeMultiHeadAttention class to understand space and time attention modes with multi-head einsum', 'refactor_gpt2_block': 'refactor the spatio_temporal_gpt2_block function to add custom residual connections or layer norm options', 'test_position_embedding': 'test the _get_position_embedding method to verify absolute positional embeddings are applied correctly'}
```

