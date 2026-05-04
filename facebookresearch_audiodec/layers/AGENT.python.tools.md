# Agent Python Tools

- repo: facebookresearch/audiodec
- repo_uri: https://github.com/facebookresearch/audiodec

## File: facebookresearch_audiodec/layers/activation_function.py

Prompts

```
['get a ReLU activation module by calling get_activation with the string ReLU', 'get a GELU activation module by calling get_activation with the string GELU and optional params', 'get an activation module with custom parameters by passing nonlinear_activation_params as a dict', 'list supported activation functions by checking which names exist on torch.nn', 'review the get_activation function to understand how it dynamically instantiates torch.nn activation modules', 'build a CausalConv1d layer with 64 in/out channels and kernel size 3 for audio processing', 'build a NonCausalConv1d layer with 128 channels and kernel size 5 for bidirectional audio features', 'build a CausalConvTranspose1d layer with 64 to 128 channels and stride 2 for upsampling', 'build a NonCausalConv2d layer with 32 channels and 3x3 kernel for 2D feature extraction', 'build a Conv1d1x1 layer with 64 to 128 channels for channel-wise feature transformation', 'build a VectorQuantize module with a given embedding dimension and codebook size for vector quantization', 'build a ResidualVQ module with multiple quantizer layers for residual vector quantization', 'test the VectorQuantize forward pass to get quantized output, loss, and perplexity values', 'test the ResidualVQ forward_index method to get quantized output and discrete token indices', 'test the ResidualVQ lookup method to reconstruct quantized output from stored token indices']
```

Usage

```
{'get_activation_ReLU': 'get a ReLU activation module by calling get_activation with the string ReLU', 'get_activation_GELU': 'get a GELU activation module by calling get_activation with the string GELU and optional params', 'get_activation_with_params': 'get an activation module with custom parameters by passing nonlinear_activation_params as a dict', 'get_activation_list_supported': 'list supported activation functions by checking which names exist on torch.nn', 'review_get_activation': 'review the get_activation function to understand how it dynamically instantiates torch.nn activation modules'}
```

## File: facebookresearch_audiodec/layers/conv_layer.py

Prompts

```
['get a ReLU activation module by calling get_activation with the string ReLU', 'get a GELU activation module by calling get_activation with the string GELU and optional params', 'get an activation module with custom parameters by passing nonlinear_activation_params as a dict', 'list supported activation functions by checking which names exist on torch.nn', 'review the get_activation function to understand how it dynamically instantiates torch.nn activation modules', 'build a CausalConv1d layer with 64 in/out channels and kernel size 3 for audio processing', 'build a NonCausalConv1d layer with 128 channels and kernel size 5 for bidirectional audio features', 'build a CausalConvTranspose1d layer with 64 to 128 channels and stride 2 for upsampling', 'build a NonCausalConv2d layer with 32 channels and 3x3 kernel for 2D feature extraction', 'build a Conv1d1x1 layer with 64 to 128 channels for channel-wise feature transformation', 'build a VectorQuantize module with a given embedding dimension and codebook size for vector quantization', 'build a ResidualVQ module with multiple quantizer layers for residual vector quantization', 'test the VectorQuantize forward pass to get quantized output, loss, and perplexity values', 'test the ResidualVQ forward_index method to get quantized output and discrete token indices', 'test the ResidualVQ lookup method to reconstruct quantized output from stored token indices']
```

Usage

```
{'build_causal_conv1d_layer': 'build a CausalConv1d layer with 64 in/out channels and kernel size 3 for audio processing', 'build_noncausal_conv1d_layer': 'build a NonCausalConv1d layer with 128 channels and kernel size 5 for bidirectional audio features', 'build_causal_conv_transpose1d_layer': 'build a CausalConvTranspose1d layer with 64 to 128 channels and stride 2 for upsampling', 'build_noncausal_conv2d_layer': 'build a NonCausalConv2d layer with 32 channels and 3x3 kernel for 2D feature extraction', 'build_conv1d1x1_layer': 'build a Conv1d1x1 layer with 64 to 128 channels for channel-wise feature transformation'}
```

## File: facebookresearch_audiodec/layers/vq_module.py

Prompts

```
['get a ReLU activation module by calling get_activation with the string ReLU', 'get a GELU activation module by calling get_activation with the string GELU and optional params', 'get an activation module with custom parameters by passing nonlinear_activation_params as a dict', 'list supported activation functions by checking which names exist on torch.nn', 'review the get_activation function to understand how it dynamically instantiates torch.nn activation modules', 'build a CausalConv1d layer with 64 in/out channels and kernel size 3 for audio processing', 'build a NonCausalConv1d layer with 128 channels and kernel size 5 for bidirectional audio features', 'build a CausalConvTranspose1d layer with 64 to 128 channels and stride 2 for upsampling', 'build a NonCausalConv2d layer with 32 channels and 3x3 kernel for 2D feature extraction', 'build a Conv1d1x1 layer with 64 to 128 channels for channel-wise feature transformation', 'build a VectorQuantize module with a given embedding dimension and codebook size for vector quantization', 'build a ResidualVQ module with multiple quantizer layers for residual vector quantization', 'test the VectorQuantize forward pass to get quantized output, loss, and perplexity values', 'test the ResidualVQ forward_index method to get quantized output and discrete token indices', 'test the ResidualVQ lookup method to reconstruct quantized output from stored token indices']
```

Usage

```
{'build_VectorQuantize': 'build a VectorQuantize module with a given embedding dimension and codebook size for vector quantization', 'build_ResidualVQ': 'build a ResidualVQ module with multiple quantizer layers for residual vector quantization', 'test_VectorQuantize_forward': 'test the VectorQuantize forward pass to get quantized output, loss, and perplexity values', 'test_ResidualVQ_forward_index': 'test the ResidualVQ forward_index method to get quantized output and discrete token indices', 'test_ResidualVQ_lookup': 'test the ResidualVQ lookup method to reconstruct quantized output from stored token indices'}
```

