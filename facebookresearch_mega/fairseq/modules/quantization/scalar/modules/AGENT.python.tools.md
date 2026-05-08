# Agent Python Tools

- repo: facebookresearch/mega
- repo_uri: https://github.com/facebookresearch/mega

## File: facebookresearch_mega/fairseq/modules/quantization/scalar/modules/qact.py

Prompts

```
["create an ActivationQuantizer to apply fake scalar quantization to a PyTorch module's post-activations", 'register a forward hook on a module to quantize activations using histogram-based scalar quantization', 'configure the number of bits for activation quantization when initializing an ActivationQuantizer instance', 'remove the registered forward hook from a module by calling handle.remove() on the ActivationQuantizer', 'quantize activations with configurable noise proportion p using the ActivationQuantizer straight-through estimator', 'create an IntConv2d layer with 8-bit histogram quantization noise for a PyTorch model', 'build a quantized Conv2d layer using IntConv2d with configurable bits and quantization method', 'test the IntConv2d forward pass to verify quantized weight output during training', 'review the IntConv2d class and its straight-through estimator for quantized convolution', 'refactor the IntConv2d update_step logic to recompute scale and zero_point on a custom interval', 'create an IntEmbedding layer with 10000 tokens and 512 dimensional embeddings using 8-bit quantization', 'build a quantized embedding module that injects quantization noise with probability p during training', 'test the IntEmbedding forward pass with a tensor of token indices to get quantized embeddings', 'review the IntEmbedding reset_parameters method that initializes weights with normal distribution and zeros padding', 'refactor the IntEmbedding to switch between tensor, histogram, or channel quantization methods', 'create an IntLinear layer with 256 input features and 128 output features using 8-bit histogram quantization', 'build a quantized linear module with configurable noise probability p and update_step for scale recomputation', 'test the IntLinear forward pass to verify quantized weight output matches expected tensor shape', 'review the IntLinear reset_parameters method that initializes weights with Xavier uniform and bias to zero', 'refactor the IntLinear forward method to switch from histogram to tensor or channel quantization method']
```

Usage

```
{'create_activation_quantizer': "create an ActivationQuantizer to apply fake scalar quantization to a PyTorch module's post-activations", 'register_quantization_hook': 'register a forward hook on a module to quantize activations using histogram-based scalar quantization', 'configure_quantization_bits': 'configure the number of bits for activation quantization when initializing an ActivationQuantizer instance', 'remove_quantization_hook': 'remove the registered forward hook from a module by calling handle.remove() on the ActivationQuantizer', 'quantize_activations_with_noise': 'quantize activations with configurable noise proportion p using the ActivationQuantizer straight-through estimator'}
```

## File: facebookresearch_mega/fairseq/modules/quantization/scalar/modules/qconv.py

Prompts

```
["create an ActivationQuantizer to apply fake scalar quantization to a PyTorch module's post-activations", 'register a forward hook on a module to quantize activations using histogram-based scalar quantization', 'configure the number of bits for activation quantization when initializing an ActivationQuantizer instance', 'remove the registered forward hook from a module by calling handle.remove() on the ActivationQuantizer', 'quantize activations with configurable noise proportion p using the ActivationQuantizer straight-through estimator', 'create an IntConv2d layer with 8-bit histogram quantization noise for a PyTorch model', 'build a quantized Conv2d layer using IntConv2d with configurable bits and quantization method', 'test the IntConv2d forward pass to verify quantized weight output during training', 'review the IntConv2d class and its straight-through estimator for quantized convolution', 'refactor the IntConv2d update_step logic to recompute scale and zero_point on a custom interval', 'create an IntEmbedding layer with 10000 tokens and 512 dimensional embeddings using 8-bit quantization', 'build a quantized embedding module that injects quantization noise with probability p during training', 'test the IntEmbedding forward pass with a tensor of token indices to get quantized embeddings', 'review the IntEmbedding reset_parameters method that initializes weights with normal distribution and zeros padding', 'refactor the IntEmbedding to switch between tensor, histogram, or channel quantization methods', 'create an IntLinear layer with 256 input features and 128 output features using 8-bit histogram quantization', 'build a quantized linear module with configurable noise probability p and update_step for scale recomputation', 'test the IntLinear forward pass to verify quantized weight output matches expected tensor shape', 'review the IntLinear reset_parameters method that initializes weights with Xavier uniform and bias to zero', 'refactor the IntLinear forward method to switch from histogram to tensor or channel quantization method']
```

Usage

```
{'create_IntConv2d_layer': 'create an IntConv2d layer with 8-bit histogram quantization noise for a PyTorch model', 'build_quantized_conv2d': 'build a quantized Conv2d layer using IntConv2d with configurable bits and quantization method', 'test_IntConv2d_forward': 'test the IntConv2d forward pass to verify quantized weight output during training', 'review_IntConv2d_quantization': 'review the IntConv2d class and its straight-through estimator for quantized convolution', 'refactor_IntConv2d_update_step': 'refactor the IntConv2d update_step logic to recompute scale and zero_point on a custom interval'}
```

## File: facebookresearch_mega/fairseq/modules/quantization/scalar/modules/qemb.py

Prompts

```
["create an ActivationQuantizer to apply fake scalar quantization to a PyTorch module's post-activations", 'register a forward hook on a module to quantize activations using histogram-based scalar quantization', 'configure the number of bits for activation quantization when initializing an ActivationQuantizer instance', 'remove the registered forward hook from a module by calling handle.remove() on the ActivationQuantizer', 'quantize activations with configurable noise proportion p using the ActivationQuantizer straight-through estimator', 'create an IntConv2d layer with 8-bit histogram quantization noise for a PyTorch model', 'build a quantized Conv2d layer using IntConv2d with configurable bits and quantization method', 'test the IntConv2d forward pass to verify quantized weight output during training', 'review the IntConv2d class and its straight-through estimator for quantized convolution', 'refactor the IntConv2d update_step logic to recompute scale and zero_point on a custom interval', 'create an IntEmbedding layer with 10000 tokens and 512 dimensional embeddings using 8-bit quantization', 'build a quantized embedding module that injects quantization noise with probability p during training', 'test the IntEmbedding forward pass with a tensor of token indices to get quantized embeddings', 'review the IntEmbedding reset_parameters method that initializes weights with normal distribution and zeros padding', 'refactor the IntEmbedding to switch between tensor, histogram, or channel quantization methods', 'create an IntLinear layer with 256 input features and 128 output features using 8-bit histogram quantization', 'build a quantized linear module with configurable noise probability p and update_step for scale recomputation', 'test the IntLinear forward pass to verify quantized weight output matches expected tensor shape', 'review the IntLinear reset_parameters method that initializes weights with Xavier uniform and bias to zero', 'refactor the IntLinear forward method to switch from histogram to tensor or channel quantization method']
```

Usage

```
{'create_quantized_embedding_layer': 'create an IntEmbedding layer with 10000 tokens and 512 dimensional embeddings using 8-bit quantization', 'build_embedding_with_quant_noise': 'build a quantized embedding module that injects quantization noise with probability p during training', 'test_intembedding_forward_pass': 'test the IntEmbedding forward pass with a tensor of token indices to get quantized embeddings', 'review_intembedding_reset_parameters': 'review the IntEmbedding reset_parameters method that initializes weights with normal distribution and zeros padding', 'refactor_intembedding_quantization_method': 'refactor the IntEmbedding to switch between tensor, histogram, or channel quantization methods'}
```

## File: facebookresearch_mega/fairseq/modules/quantization/scalar/modules/qlinear.py

Prompts

```
["create an ActivationQuantizer to apply fake scalar quantization to a PyTorch module's post-activations", 'register a forward hook on a module to quantize activations using histogram-based scalar quantization', 'configure the number of bits for activation quantization when initializing an ActivationQuantizer instance', 'remove the registered forward hook from a module by calling handle.remove() on the ActivationQuantizer', 'quantize activations with configurable noise proportion p using the ActivationQuantizer straight-through estimator', 'create an IntConv2d layer with 8-bit histogram quantization noise for a PyTorch model', 'build a quantized Conv2d layer using IntConv2d with configurable bits and quantization method', 'test the IntConv2d forward pass to verify quantized weight output during training', 'review the IntConv2d class and its straight-through estimator for quantized convolution', 'refactor the IntConv2d update_step logic to recompute scale and zero_point on a custom interval', 'create an IntEmbedding layer with 10000 tokens and 512 dimensional embeddings using 8-bit quantization', 'build a quantized embedding module that injects quantization noise with probability p during training', 'test the IntEmbedding forward pass with a tensor of token indices to get quantized embeddings', 'review the IntEmbedding reset_parameters method that initializes weights with normal distribution and zeros padding', 'refactor the IntEmbedding to switch between tensor, histogram, or channel quantization methods', 'create an IntLinear layer with 256 input features and 128 output features using 8-bit histogram quantization', 'build a quantized linear module with configurable noise probability p and update_step for scale recomputation', 'test the IntLinear forward pass to verify quantized weight output matches expected tensor shape', 'review the IntLinear reset_parameters method that initializes weights with Xavier uniform and bias to zero', 'refactor the IntLinear forward method to switch from histogram to tensor or channel quantization method']
```

Usage

```
{'create_IntLinear_layer': 'create an IntLinear layer with 256 input features and 128 output features using 8-bit histogram quantization', 'build_quantized_linear_module': 'build a quantized linear module with configurable noise probability p and update_step for scale recomputation', 'test_IntLinear_forward': 'test the IntLinear forward pass to verify quantized weight output matches expected tensor shape', 'review_IntLinear_reset_parameters': 'review the IntLinear reset_parameters method that initializes weights with Xavier uniform and bias to zero', 'refactor_IntLinear_quantization_method': 'refactor the IntLinear forward method to switch from histogram to tensor or channel quantization method'}
```

