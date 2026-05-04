# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/fairseq/modules/quantization/scalar/modules/qact.py

Prompts

```
['create an ActivationQuantizer to fake scalar quantize post-activations of a PyTorch nn.Module using a forward hook', 'register a forward hook on a module that quantizes activations with configurable bits and quantization method', 'configure the number of bits for activation quantization when initializing an ActivationQuantizer instance', 'set the quantization method to tensor, histogram, or channel when creating an ActivationQuantizer', 'remove the registered forward hook from a module by calling handle.remove() on the ActivationQuantizer', 'create an IntConv2d quantized convolution layer with 8-bit histogram quantization noise', 'build an IntConv2d layer using channel-wise quantization method with custom bit width', 'test the IntConv2d forward pass with quantized weights and straight-through estimator', 'review the IntConv2d class quantization parameters including bits, method, and update_step', 'refactor the IntConv2d forward method to adjust quantization noise injection probability', 'create a quantized embedding layer with 8-bit integer quantization and histogram method', 'build an IntEmbedding module with a specified padding index for token sequences', 'test the IntEmbedding forward pass with quantized weights and straight-through estimator', 'review the IntEmbedding class quantization parameters including bits, method, and noise probability', 'refactor the IntEmbedding reset_parameters method to use a different weight initialization strategy', 'build a quantized IntLinear layer with 8-bit histogram quantization and quant noise for training', 'create an IntLinear module without bias using tensor quantization method and 4 bits', 'test the IntLinear forward pass with quantized weights and straight-through estimator during training', 'review the IntLinear reset_parameters method that initializes weights with Xavier uniform and bias to zero', 'refactor the IntLinear quantization method to switch between tensor histogram and channel approaches']
```

Usage

```
{'create_activation_quantizer': 'create an ActivationQuantizer to fake scalar quantize post-activations of a PyTorch nn.Module using a forward hook', 'register_quantize_hook': 'register a forward hook on a module that quantizes activations with configurable bits and quantization method', 'configure_quantization_bits': 'configure the number of bits for activation quantization when initializing an ActivationQuantizer instance', 'set_quantization_method': 'set the quantization method to tensor, histogram, or channel when creating an ActivationQuantizer', 'remove_quantization_hook': 'remove the registered forward hook from a module by calling handle.remove() on the ActivationQuantizer'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/modules/quantization/scalar/modules/qconv.py

Prompts

```
['create an ActivationQuantizer to fake scalar quantize post-activations of a PyTorch nn.Module using a forward hook', 'register a forward hook on a module that quantizes activations with configurable bits and quantization method', 'configure the number of bits for activation quantization when initializing an ActivationQuantizer instance', 'set the quantization method to tensor, histogram, or channel when creating an ActivationQuantizer', 'remove the registered forward hook from a module by calling handle.remove() on the ActivationQuantizer', 'create an IntConv2d quantized convolution layer with 8-bit histogram quantization noise', 'build an IntConv2d layer using channel-wise quantization method with custom bit width', 'test the IntConv2d forward pass with quantized weights and straight-through estimator', 'review the IntConv2d class quantization parameters including bits, method, and update_step', 'refactor the IntConv2d forward method to adjust quantization noise injection probability', 'create a quantized embedding layer with 8-bit integer quantization and histogram method', 'build an IntEmbedding module with a specified padding index for token sequences', 'test the IntEmbedding forward pass with quantized weights and straight-through estimator', 'review the IntEmbedding class quantization parameters including bits, method, and noise probability', 'refactor the IntEmbedding reset_parameters method to use a different weight initialization strategy', 'build a quantized IntLinear layer with 8-bit histogram quantization and quant noise for training', 'create an IntLinear module without bias using tensor quantization method and 4 bits', 'test the IntLinear forward pass with quantized weights and straight-through estimator during training', 'review the IntLinear reset_parameters method that initializes weights with Xavier uniform and bias to zero', 'refactor the IntLinear quantization method to switch between tensor histogram and channel approaches']
```

Usage

```
{'create_IntConv2d': 'create an IntConv2d quantized convolution layer with 8-bit histogram quantization noise', 'build_IntConv2d_channel': 'build an IntConv2d layer using channel-wise quantization method with custom bit width', 'test_IntConv2d_forward': 'test the IntConv2d forward pass with quantized weights and straight-through estimator', 'review_IntConv2d_quantization': 'review the IntConv2d class quantization parameters including bits, method, and update_step', 'refactor_IntConv2d_noise': 'refactor the IntConv2d forward method to adjust quantization noise injection probability'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/modules/quantization/scalar/modules/qemb.py

Prompts

```
['create an ActivationQuantizer to fake scalar quantize post-activations of a PyTorch nn.Module using a forward hook', 'register a forward hook on a module that quantizes activations with configurable bits and quantization method', 'configure the number of bits for activation quantization when initializing an ActivationQuantizer instance', 'set the quantization method to tensor, histogram, or channel when creating an ActivationQuantizer', 'remove the registered forward hook from a module by calling handle.remove() on the ActivationQuantizer', 'create an IntConv2d quantized convolution layer with 8-bit histogram quantization noise', 'build an IntConv2d layer using channel-wise quantization method with custom bit width', 'test the IntConv2d forward pass with quantized weights and straight-through estimator', 'review the IntConv2d class quantization parameters including bits, method, and update_step', 'refactor the IntConv2d forward method to adjust quantization noise injection probability', 'create a quantized embedding layer with 8-bit integer quantization and histogram method', 'build an IntEmbedding module with a specified padding index for token sequences', 'test the IntEmbedding forward pass with quantized weights and straight-through estimator', 'review the IntEmbedding class quantization parameters including bits, method, and noise probability', 'refactor the IntEmbedding reset_parameters method to use a different weight initialization strategy', 'build a quantized IntLinear layer with 8-bit histogram quantization and quant noise for training', 'create an IntLinear module without bias using tensor quantization method and 4 bits', 'test the IntLinear forward pass with quantized weights and straight-through estimator during training', 'review the IntLinear reset_parameters method that initializes weights with Xavier uniform and bias to zero', 'refactor the IntLinear quantization method to switch between tensor histogram and channel approaches']
```

Usage

```
{'create_IntEmbedding': 'create a quantized embedding layer with 8-bit integer quantization and histogram method', 'build_IntEmbedding_with_padding': 'build an IntEmbedding module with a specified padding index for token sequences', 'test_IntEmbedding_forward': 'test the IntEmbedding forward pass with quantized weights and straight-through estimator', 'review_IntEmbedding_quantization': 'review the IntEmbedding class quantization parameters including bits, method, and noise probability', 'refactor_IntEmbedding_reset_parameters': 'refactor the IntEmbedding reset_parameters method to use a different weight initialization strategy'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/modules/quantization/scalar/modules/qlinear.py

Prompts

```
['create an ActivationQuantizer to fake scalar quantize post-activations of a PyTorch nn.Module using a forward hook', 'register a forward hook on a module that quantizes activations with configurable bits and quantization method', 'configure the number of bits for activation quantization when initializing an ActivationQuantizer instance', 'set the quantization method to tensor, histogram, or channel when creating an ActivationQuantizer', 'remove the registered forward hook from a module by calling handle.remove() on the ActivationQuantizer', 'create an IntConv2d quantized convolution layer with 8-bit histogram quantization noise', 'build an IntConv2d layer using channel-wise quantization method with custom bit width', 'test the IntConv2d forward pass with quantized weights and straight-through estimator', 'review the IntConv2d class quantization parameters including bits, method, and update_step', 'refactor the IntConv2d forward method to adjust quantization noise injection probability', 'create a quantized embedding layer with 8-bit integer quantization and histogram method', 'build an IntEmbedding module with a specified padding index for token sequences', 'test the IntEmbedding forward pass with quantized weights and straight-through estimator', 'review the IntEmbedding class quantization parameters including bits, method, and noise probability', 'refactor the IntEmbedding reset_parameters method to use a different weight initialization strategy', 'build a quantized IntLinear layer with 8-bit histogram quantization and quant noise for training', 'create an IntLinear module without bias using tensor quantization method and 4 bits', 'test the IntLinear forward pass with quantized weights and straight-through estimator during training', 'review the IntLinear reset_parameters method that initializes weights with Xavier uniform and bias to zero', 'refactor the IntLinear quantization method to switch between tensor histogram and channel approaches']
```

Usage

```
{'build_intlinear_layer': 'build a quantized IntLinear layer with 8-bit histogram quantization and quant noise for training', 'create_intlinear_no_bias': 'create an IntLinear module without bias using tensor quantization method and 4 bits', 'test_intlinear_forward': 'test the IntLinear forward pass with quantized weights and straight-through estimator during training', 'review_intlinear_reset_parameters': 'review the IntLinear reset_parameters method that initializes weights with Xavier uniform and bias to zero', 'refactor_intlinear_quantization_method': 'refactor the IntLinear quantization method to switch between tensor histogram and channel approaches'}
```

