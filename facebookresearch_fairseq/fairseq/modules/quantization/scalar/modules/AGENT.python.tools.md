# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/fairseq/modules/quantization/scalar/modules/qact.py

Prompts

```
['create an ActivationQuantizer to fake scalar quantize post-activations of a PyTorch nn.Module', 'register a forward hook on a module to quantize activations using histogram or tensor method', 'configure the number of bits for fake quantization when initializing ActivationQuantizer', 'remove the quantization forward hook from a module by calling handle.remove()', 'review the ActivationQuantizer class and its straight-through estimator for gradient back-propagation', 'create an IntConv2d quantized convolution layer with 8-bit histogram quantization noise', 'build a quantized Conv2d module with configurable bits, noise probability, and update step', 'test the IntConv2d forward pass with quantized weights and straight-through estimator', 'review the IntConv2d class quantization parameters including scale and zero_point recomputation', 'refactor the IntConv2d quantization method to switch between tensor, histogram, and channel modes', 'create an IntEmbedding layer with 10000 tokens and 512 dimensional embeddings using 8-bit quantization', 'build a quantized embedding module that injects quantization noise with probability p during training', 'test the IntEmbedding forward pass with a tensor of token indices and verify quantized output shape', 'review the IntEmbedding reset_parameters method that initializes weights with normal distribution and zeros padding index', 'refactor the IntEmbedding to switch between tensor, histogram, and channel quantization methods', 'create an IntLinear module with 128 input features and 64 output features using 8-bit histogram quantization', 'build an IntLinear quantized linear layer without bias using tensor quantization method and 4 bits', 'test the IntLinear forward pass by passing a random tensor through the quantized layer', 'refactor the IntLinear reset_parameters method to use kaiming initialization instead of xavier uniform', 'review the IntLinear class and its straight-through estimator quantization noise approach during training']
```

Usage

```
{'create_activation_quantizer': 'create an ActivationQuantizer to fake scalar quantize post-activations of a PyTorch nn.Module', 'register_quantization_hook': 'register a forward hook on a module to quantize activations using histogram or tensor method', 'configure_quantization_bits': 'configure the number of bits for fake quantization when initializing ActivationQuantizer', 'remove_quantization_hook': 'remove the quantization forward hook from a module by calling handle.remove()', 'review_activation_quantizer': 'review the ActivationQuantizer class and its straight-through estimator for gradient back-propagation'}
```

## File: facebookresearch_fairseq/fairseq/modules/quantization/scalar/modules/qconv.py

Prompts

```
['create an ActivationQuantizer to fake scalar quantize post-activations of a PyTorch nn.Module', 'register a forward hook on a module to quantize activations using histogram or tensor method', 'configure the number of bits for fake quantization when initializing ActivationQuantizer', 'remove the quantization forward hook from a module by calling handle.remove()', 'review the ActivationQuantizer class and its straight-through estimator for gradient back-propagation', 'create an IntConv2d quantized convolution layer with 8-bit histogram quantization noise', 'build a quantized Conv2d module with configurable bits, noise probability, and update step', 'test the IntConv2d forward pass with quantized weights and straight-through estimator', 'review the IntConv2d class quantization parameters including scale and zero_point recomputation', 'refactor the IntConv2d quantization method to switch between tensor, histogram, and channel modes', 'create an IntEmbedding layer with 10000 tokens and 512 dimensional embeddings using 8-bit quantization', 'build a quantized embedding module that injects quantization noise with probability p during training', 'test the IntEmbedding forward pass with a tensor of token indices and verify quantized output shape', 'review the IntEmbedding reset_parameters method that initializes weights with normal distribution and zeros padding index', 'refactor the IntEmbedding to switch between tensor, histogram, and channel quantization methods', 'create an IntLinear module with 128 input features and 64 output features using 8-bit histogram quantization', 'build an IntLinear quantized linear layer without bias using tensor quantization method and 4 bits', 'test the IntLinear forward pass by passing a random tensor through the quantized layer', 'refactor the IntLinear reset_parameters method to use kaiming initialization instead of xavier uniform', 'review the IntLinear class and its straight-through estimator quantization noise approach during training']
```

Usage

```
{'create_IntConv2d_module': 'create an IntConv2d quantized convolution layer with 8-bit histogram quantization noise', 'build_IntConv2d_with_params': 'build a quantized Conv2d module with configurable bits, noise probability, and update step', 'test_IntConv2d_forward': 'test the IntConv2d forward pass with quantized weights and straight-through estimator', 'review_IntConv2d_quantization': 'review the IntConv2d class quantization parameters including scale and zero_point recomputation', 'refactor_IntConv2d_method': 'refactor the IntConv2d quantization method to switch between tensor, histogram, and channel modes'}
```

## File: facebookresearch_fairseq/fairseq/modules/quantization/scalar/modules/qemb.py

Prompts

```
['create an ActivationQuantizer to fake scalar quantize post-activations of a PyTorch nn.Module', 'register a forward hook on a module to quantize activations using histogram or tensor method', 'configure the number of bits for fake quantization when initializing ActivationQuantizer', 'remove the quantization forward hook from a module by calling handle.remove()', 'review the ActivationQuantizer class and its straight-through estimator for gradient back-propagation', 'create an IntConv2d quantized convolution layer with 8-bit histogram quantization noise', 'build a quantized Conv2d module with configurable bits, noise probability, and update step', 'test the IntConv2d forward pass with quantized weights and straight-through estimator', 'review the IntConv2d class quantization parameters including scale and zero_point recomputation', 'refactor the IntConv2d quantization method to switch between tensor, histogram, and channel modes', 'create an IntEmbedding layer with 10000 tokens and 512 dimensional embeddings using 8-bit quantization', 'build a quantized embedding module that injects quantization noise with probability p during training', 'test the IntEmbedding forward pass with a tensor of token indices and verify quantized output shape', 'review the IntEmbedding reset_parameters method that initializes weights with normal distribution and zeros padding index', 'refactor the IntEmbedding to switch between tensor, histogram, and channel quantization methods', 'create an IntLinear module with 128 input features and 64 output features using 8-bit histogram quantization', 'build an IntLinear quantized linear layer without bias using tensor quantization method and 4 bits', 'test the IntLinear forward pass by passing a random tensor through the quantized layer', 'refactor the IntLinear reset_parameters method to use kaiming initialization instead of xavier uniform', 'review the IntLinear class and its straight-through estimator quantization noise approach during training']
```

Usage

```
{'create_quantized_embedding_layer': 'create an IntEmbedding layer with 10000 tokens and 512 dimensional embeddings using 8-bit quantization', 'build_embedding_with_quant_noise': 'build a quantized embedding module that injects quantization noise with probability p during training', 'test_IntEmbedding_forward': 'test the IntEmbedding forward pass with a tensor of token indices and verify quantized output shape', 'review_IntEmbedding_reset_parameters': 'review the IntEmbedding reset_parameters method that initializes weights with normal distribution and zeros padding index', 'refactor_IntEmbedding_quantization_method': 'refactor the IntEmbedding to switch between tensor, histogram, and channel quantization methods'}
```

## File: facebookresearch_fairseq/fairseq/modules/quantization/scalar/modules/qlinear.py

Prompts

```
['create an ActivationQuantizer to fake scalar quantize post-activations of a PyTorch nn.Module', 'register a forward hook on a module to quantize activations using histogram or tensor method', 'configure the number of bits for fake quantization when initializing ActivationQuantizer', 'remove the quantization forward hook from a module by calling handle.remove()', 'review the ActivationQuantizer class and its straight-through estimator for gradient back-propagation', 'create an IntConv2d quantized convolution layer with 8-bit histogram quantization noise', 'build a quantized Conv2d module with configurable bits, noise probability, and update step', 'test the IntConv2d forward pass with quantized weights and straight-through estimator', 'review the IntConv2d class quantization parameters including scale and zero_point recomputation', 'refactor the IntConv2d quantization method to switch between tensor, histogram, and channel modes', 'create an IntEmbedding layer with 10000 tokens and 512 dimensional embeddings using 8-bit quantization', 'build a quantized embedding module that injects quantization noise with probability p during training', 'test the IntEmbedding forward pass with a tensor of token indices and verify quantized output shape', 'review the IntEmbedding reset_parameters method that initializes weights with normal distribution and zeros padding index', 'refactor the IntEmbedding to switch between tensor, histogram, and channel quantization methods', 'create an IntLinear module with 128 input features and 64 output features using 8-bit histogram quantization', 'build an IntLinear quantized linear layer without bias using tensor quantization method and 4 bits', 'test the IntLinear forward pass by passing a random tensor through the quantized layer', 'refactor the IntLinear reset_parameters method to use kaiming initialization instead of xavier uniform', 'review the IntLinear class and its straight-through estimator quantization noise approach during training']
```

Usage

```
{'create_IntLinear': 'create an IntLinear module with 128 input features and 64 output features using 8-bit histogram quantization', 'build_IntLinear_no_bias': 'build an IntLinear quantized linear layer without bias using tensor quantization method and 4 bits', 'test_IntLinear_forward': 'test the IntLinear forward pass by passing a random tensor through the quantized layer', 'refactor_IntLinear_reset_parameters': 'refactor the IntLinear reset_parameters method to use kaiming initialization instead of xavier uniform', 'review_IntLinear_quantization': 'review the IntLinear class and its straight-through estimator quantization noise approach during training'}
```

