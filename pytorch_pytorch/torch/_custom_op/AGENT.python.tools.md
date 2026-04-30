# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/_custom_op/autograd.py

Prompts

```
['build a pytorch autograd kernel from schema, custom op, and backward functions', 'create autograd kernel indirection that dispatches to user-registered backward or fallback', 'test autograd not implemented fallback that raises when gradients are required', 'validate backward function gradient dict keys and types match forward op inputs', 'summarize pytree saving utility that stores tensors and non-tensors on autograd context', 'register a functional variant of a mutable PyTorch operator using a Library and OpOverload', 'construct a functional implementation that clones mutable args and returns them as extra outputs', 'construct a functionalization kernel that unwraps FunctionalTensorWrapper tensors and syncs updates', 'validate that a mutable operator is a proper OpOverload with mutable schema kind and no annotated returns', 'generate a functional operator schema string from a mutable operator by renaming its signature', 'create a custom PyTorch operator with a namespace and qualified name using the custom_op decorator', 'register a CPU or CUDA implementation for a custom PyTorch operator using the impl method', 'register a backward formula and save_for_backward function for custom operator autograd support', 'register an abstract implementation for a custom operator to support FakeTensor and meta tensor execution', 'validate a custom operator schema, namespace, and device type against PyTorch custom op constraints']
```

Usage

```
{'build_construct_autograd_kernel': 'build a pytorch autograd kernel from schema, custom op, and backward functions', 'create_autograd_kernel_indirection': 'create autograd kernel indirection that dispatches to user-registered backward or fallback', 'test_autograd_not_implemented': 'test autograd not implemented fallback that raises when gradients are required', 'validate_grad_inputs_dict': 'validate backward function gradient dict keys and types match forward op inputs', 'summarize_save_pytree_for_backward': 'summarize pytree saving utility that stores tensors and non-tensors on autograd context'}
```

## File: pytorch_pytorch/torch/_custom_op/functional.py

Prompts

```
['build a pytorch autograd kernel from schema, custom op, and backward functions', 'create autograd kernel indirection that dispatches to user-registered backward or fallback', 'test autograd not implemented fallback that raises when gradients are required', 'validate backward function gradient dict keys and types match forward op inputs', 'summarize pytree saving utility that stores tensors and non-tensors on autograd context', 'register a functional variant of a mutable PyTorch operator using a Library and OpOverload', 'construct a functional implementation that clones mutable args and returns them as extra outputs', 'construct a functionalization kernel that unwraps FunctionalTensorWrapper tensors and syncs updates', 'validate that a mutable operator is a proper OpOverload with mutable schema kind and no annotated returns', 'generate a functional operator schema string from a mutable operator by renaming its signature', 'create a custom PyTorch operator with a namespace and qualified name using the custom_op decorator', 'register a CPU or CUDA implementation for a custom PyTorch operator using the impl method', 'register a backward formula and save_for_backward function for custom operator autograd support', 'register an abstract implementation for a custom operator to support FakeTensor and meta tensor execution', 'validate a custom operator schema, namespace, and device type against PyTorch custom op constraints']
```

Usage

```
{'register_functional_op': 'register a functional variant of a mutable PyTorch operator using a Library and OpOverload', 'construct_functional_impl': 'construct a functional implementation that clones mutable args and returns them as extra outputs', 'construct_functionalization_kernel': 'construct a functionalization kernel that unwraps FunctionalTensorWrapper tensors and syncs updates', 'validate': 'validate that a mutable operator is a proper OpOverload with mutable schema kind and no annotated returns', 'functional_schema': 'generate a functional operator schema string from a mutable operator by renaming its signature'}
```

## File: pytorch_pytorch/torch/_custom_op/impl.py

Prompts

```
['build a pytorch autograd kernel from schema, custom op, and backward functions', 'create autograd kernel indirection that dispatches to user-registered backward or fallback', 'test autograd not implemented fallback that raises when gradients are required', 'validate backward function gradient dict keys and types match forward op inputs', 'summarize pytree saving utility that stores tensors and non-tensors on autograd context', 'register a functional variant of a mutable PyTorch operator using a Library and OpOverload', 'construct a functional implementation that clones mutable args and returns them as extra outputs', 'construct a functionalization kernel that unwraps FunctionalTensorWrapper tensors and syncs updates', 'validate that a mutable operator is a proper OpOverload with mutable schema kind and no annotated returns', 'generate a functional operator schema string from a mutable operator by renaming its signature', 'create a custom PyTorch operator with a namespace and qualified name using the custom_op decorator', 'register a CPU or CUDA implementation for a custom PyTorch operator using the impl method', 'register a backward formula and save_for_backward function for custom operator autograd support', 'register an abstract implementation for a custom operator to support FakeTensor and meta tensor execution', 'validate a custom operator schema, namespace, and device type against PyTorch custom op constraints']
```

Usage

```
{'create_custom_op': 'create a custom PyTorch operator with a namespace and qualified name using the custom_op decorator', 'register_device_impl': 'register a CPU or CUDA implementation for a custom PyTorch operator using the impl method', 'register_autograd_backward': 'register a backward formula and save_for_backward function for custom operator autograd support', 'register_abstract_impl': 'register an abstract implementation for a custom operator to support FakeTensor and meta tensor execution', 'validate_custom_op_schema': 'validate a custom operator schema, namespace, and device type against PyTorch custom op constraints'}
```

