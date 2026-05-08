# Agent Python Tools

- repo: facebookresearch/crypten
- repo_uri: https://github.com/facebookresearch/crypten

## File: facebookresearch_crypten/crypten/autograd_cryptensor.py

Prompts

```
['review the deprecated AutogradContext class and migrate to crypten.gradients.AutogradContext', 'review the deprecated AutogradCrypTensor function and use requires_grad on CrypTensor instead', 'create a CrypTensor subclass that implements add, mul, matmul and other required functions', 'register a custom CrypTensor subclass using the register_cryptensor decorator with a unique name', 'run backward gradient computation on a CrypTensor through its autograd computation graph', 'detach a CrypTensor from the autograd graph to make it a leaf node', 'disable Crypten autograd temporarily using the CrypTensor no_grad context manager', 'encode a float tensor into a scaled integer tensor using FixedPointEncoder with precision bits', 'decode a scaled integer tensor back to a float tensor using FixedPointEncoder decode method', 'encode a scalar int or float value into a scaled 0-dim integer tensor', 'perform nearest integer division on an integer tensor with proper rounding for negative values', 'configure the FixedPointEncoder precision bits and scale factor via the precision_bits property', 'register a new autograd function class using the register_function decorator with a unique name', 'get the gradient function class for a CrypTen operation by name using get_grad_fn', 'create a custom autograd function by subclassing AutogradFunction and implementing forward and backward static methods', 'save tensors and mark non-differentiable outputs in the forward pass using AutogradContext for backward computation', 'review the AutogradConv2D backward method to understand how gradients are computed for input and kernel']
```

Usage

```
{'review_deprecated_autogradcontext': 'review the deprecated AutogradContext class and migrate to crypten.gradients.AutogradContext', 'review_deprecated_autogradcryptensor': 'review the deprecated AutogradCrypTensor function and use requires_grad on CrypTensor instead'}
```

## File: facebookresearch_crypten/crypten/cryptensor.py

Prompts

```
['review the deprecated AutogradContext class and migrate to crypten.gradients.AutogradContext', 'review the deprecated AutogradCrypTensor function and use requires_grad on CrypTensor instead', 'create a CrypTensor subclass that implements add, mul, matmul and other required functions', 'register a custom CrypTensor subclass using the register_cryptensor decorator with a unique name', 'run backward gradient computation on a CrypTensor through its autograd computation graph', 'detach a CrypTensor from the autograd graph to make it a leaf node', 'disable Crypten autograd temporarily using the CrypTensor no_grad context manager', 'encode a float tensor into a scaled integer tensor using FixedPointEncoder with precision bits', 'decode a scaled integer tensor back to a float tensor using FixedPointEncoder decode method', 'encode a scalar int or float value into a scaled 0-dim integer tensor', 'perform nearest integer division on an integer tensor with proper rounding for negative values', 'configure the FixedPointEncoder precision bits and scale factor via the precision_bits property', 'register a new autograd function class using the register_function decorator with a unique name', 'get the gradient function class for a CrypTen operation by name using get_grad_fn', 'create a custom autograd function by subclassing AutogradFunction and implementing forward and backward static methods', 'save tensors and mark non-differentiable outputs in the forward pass using AutogradContext for backward computation', 'review the AutogradConv2D backward method to understand how gradients are computed for input and kernel']
```

Usage

```
{'create_cryptensor_subclass': 'create a CrypTensor subclass that implements add, mul, matmul and other required functions', 'register_custom_cryptensor': 'register a custom CrypTensor subclass using the register_cryptensor decorator with a unique name', 'run_backward_pass': 'run backward gradient computation on a CrypTensor through its autograd computation graph', 'detach_cryptensor': 'detach a CrypTensor from the autograd graph to make it a leaf node', 'disable_autograd_context': 'disable Crypten autograd temporarily using the CrypTensor no_grad context manager'}
```

## File: facebookresearch_crypten/crypten/encoder.py

Prompts

```
['review the deprecated AutogradContext class and migrate to crypten.gradients.AutogradContext', 'review the deprecated AutogradCrypTensor function and use requires_grad on CrypTensor instead', 'create a CrypTensor subclass that implements add, mul, matmul and other required functions', 'register a custom CrypTensor subclass using the register_cryptensor decorator with a unique name', 'run backward gradient computation on a CrypTensor through its autograd computation graph', 'detach a CrypTensor from the autograd graph to make it a leaf node', 'disable Crypten autograd temporarily using the CrypTensor no_grad context manager', 'encode a float tensor into a scaled integer tensor using FixedPointEncoder with precision bits', 'decode a scaled integer tensor back to a float tensor using FixedPointEncoder decode method', 'encode a scalar int or float value into a scaled 0-dim integer tensor', 'perform nearest integer division on an integer tensor with proper rounding for negative values', 'configure the FixedPointEncoder precision bits and scale factor via the precision_bits property', 'register a new autograd function class using the register_function decorator with a unique name', 'get the gradient function class for a CrypTen operation by name using get_grad_fn', 'create a custom autograd function by subclassing AutogradFunction and implementing forward and backward static methods', 'save tensors and mark non-differentiable outputs in the forward pass using AutogradContext for backward computation', 'review the AutogradConv2D backward method to understand how gradients are computed for input and kernel']
```

Usage

```
{'encode_float_tensor_to_scaled_int': 'encode a float tensor into a scaled integer tensor using FixedPointEncoder with precision bits', 'decode_scaled_int_to_float': 'decode a scaled integer tensor back to a float tensor using FixedPointEncoder decode method', 'encode_scalar_to_tensor': 'encode a scalar int or float value into a scaled 0-dim integer tensor', 'nearest_integer_division_rounding': 'perform nearest integer division on an integer tensor with proper rounding for negative values', 'configure_encoder_precision_bits': 'configure the FixedPointEncoder precision bits and scale factor via the precision_bits property'}
```

## File: facebookresearch_crypten/crypten/gradients.py

Prompts

```
['review the deprecated AutogradContext class and migrate to crypten.gradients.AutogradContext', 'review the deprecated AutogradCrypTensor function and use requires_grad on CrypTensor instead', 'create a CrypTensor subclass that implements add, mul, matmul and other required functions', 'register a custom CrypTensor subclass using the register_cryptensor decorator with a unique name', 'run backward gradient computation on a CrypTensor through its autograd computation graph', 'detach a CrypTensor from the autograd graph to make it a leaf node', 'disable Crypten autograd temporarily using the CrypTensor no_grad context manager', 'encode a float tensor into a scaled integer tensor using FixedPointEncoder with precision bits', 'decode a scaled integer tensor back to a float tensor using FixedPointEncoder decode method', 'encode a scalar int or float value into a scaled 0-dim integer tensor', 'perform nearest integer division on an integer tensor with proper rounding for negative values', 'configure the FixedPointEncoder precision bits and scale factor via the precision_bits property', 'register a new autograd function class using the register_function decorator with a unique name', 'get the gradient function class for a CrypTen operation by name using get_grad_fn', 'create a custom autograd function by subclassing AutogradFunction and implementing forward and backward static methods', 'save tensors and mark non-differentiable outputs in the forward pass using AutogradContext for backward computation', 'review the AutogradConv2D backward method to understand how gradients are computed for input and kernel']
```

Usage

```
{'register_autograd_function': 'register a new autograd function class using the register_function decorator with a unique name', 'lookup_gradient_function': 'get the gradient function class for a CrypTen operation by name using get_grad_fn', 'implement_custom_autograd_function': 'create a custom autograd function by subclassing AutogradFunction and implementing forward and backward static methods', 'use_autograd_context': 'save tensors and mark non-differentiable outputs in the forward pass using AutogradContext for backward computation', 'review_conv2d_backward': 'review the AutogradConv2D backward method to understand how gradients are computed for input and kernel'}
```

