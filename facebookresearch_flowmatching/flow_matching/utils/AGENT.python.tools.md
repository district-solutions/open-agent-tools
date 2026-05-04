# Agent Python Tools

- repo: facebookresearch/flowmatching
- repo_uri: https://github.com/facebookresearch/flow_matching

## File: facebookresearch_flowmatching/flow_matching/utils/categorical_sampler.py

Prompts

```
['run the categorical function to sample from a probability distribution tensor using torch.multinomial', 'create samples from a categorical distribution by passing a probability tensor to the categorical function', 'test the categorical function with a 2D probability tensor and verify sample shapes match input', 'refactor the categorical function to support sampling multiple times per category instead of once', 'review the categorical function implementation that flattens batch dimensions before calling torch.multinomial', 'create a subclass of ModelWrapper to wrap a PyTorch nn.Module with custom forward pass logic', 'run the ModelWrapper forward method passing input tensor x, time tensor t, and optional extras', 'test the ModelWrapper by wrapping a dummy nn.Module and verifying forward passes x and t correctly', 'refactor the ModelWrapper forward method to add custom preprocessing before calling the wrapped model', 'review the ModelWrapper abstract class that wraps an nn.Module and forwards x, t, and extras to it', 'unsqueeze a source tensor to match the dimensionality of a target tensor using prefix or suffix', 'expand a 1d batch vector to match the shape of a higher-dimensional target tensor', 'compute the gradient of an output tensor with respect to an input tensor using autograd', 'compute the gradient of an output tensor with respect to an input tensor and create a differentiable graph', 'review the tensor utility functions for unsqueeze, expand, and gradient operations in PyTorch']
```

Usage

```
{'run_categorical_sampler': 'run the categorical function to sample from a probability distribution tensor using torch.multinomial', 'create_categorical_samples': 'create samples from a categorical distribution by passing a probability tensor to the categorical function', 'test_categorical_function': 'test the categorical function with a 2D probability tensor and verify sample shapes match input', 'refactor_categorical_sampler': 'refactor the categorical function to support sampling multiple times per category instead of once', 'review_categorical_implementation': 'review the categorical function implementation that flattens batch dimensions before calling torch.multinomial'}
```

## File: facebookresearch_flowmatching/flow_matching/utils/model_wrapper.py

Prompts

```
['run the categorical function to sample from a probability distribution tensor using torch.multinomial', 'create samples from a categorical distribution by passing a probability tensor to the categorical function', 'test the categorical function with a 2D probability tensor and verify sample shapes match input', 'refactor the categorical function to support sampling multiple times per category instead of once', 'review the categorical function implementation that flattens batch dimensions before calling torch.multinomial', 'create a subclass of ModelWrapper to wrap a PyTorch nn.Module with custom forward pass logic', 'run the ModelWrapper forward method passing input tensor x, time tensor t, and optional extras', 'test the ModelWrapper by wrapping a dummy nn.Module and verifying forward passes x and t correctly', 'refactor the ModelWrapper forward method to add custom preprocessing before calling the wrapped model', 'review the ModelWrapper abstract class that wraps an nn.Module and forwards x, t, and extras to it', 'unsqueeze a source tensor to match the dimensionality of a target tensor using prefix or suffix', 'expand a 1d batch vector to match the shape of a higher-dimensional target tensor', 'compute the gradient of an output tensor with respect to an input tensor using autograd', 'compute the gradient of an output tensor with respect to an input tensor and create a differentiable graph', 'review the tensor utility functions for unsqueeze, expand, and gradient operations in PyTorch']
```

Usage

```
{'create_model_wrapper': 'create a subclass of ModelWrapper to wrap a PyTorch nn.Module with custom forward pass logic', 'run_model_wrapper_forward': 'run the ModelWrapper forward method passing input tensor x, time tensor t, and optional extras', 'test_model_wrapper': 'test the ModelWrapper by wrapping a dummy nn.Module and verifying forward passes x and t correctly', 'refactor_model_wrapper_forward': 'refactor the ModelWrapper forward method to add custom preprocessing before calling the wrapped model', 'review_model_wrapper_class': 'review the ModelWrapper abstract class that wraps an nn.Module and forwards x, t, and extras to it'}
```

## File: facebookresearch_flowmatching/flow_matching/utils/utils.py

Prompts

```
['run the categorical function to sample from a probability distribution tensor using torch.multinomial', 'create samples from a categorical distribution by passing a probability tensor to the categorical function', 'test the categorical function with a 2D probability tensor and verify sample shapes match input', 'refactor the categorical function to support sampling multiple times per category instead of once', 'review the categorical function implementation that flattens batch dimensions before calling torch.multinomial', 'create a subclass of ModelWrapper to wrap a PyTorch nn.Module with custom forward pass logic', 'run the ModelWrapper forward method passing input tensor x, time tensor t, and optional extras', 'test the ModelWrapper by wrapping a dummy nn.Module and verifying forward passes x and t correctly', 'refactor the ModelWrapper forward method to add custom preprocessing before calling the wrapped model', 'review the ModelWrapper abstract class that wraps an nn.Module and forwards x, t, and extras to it', 'unsqueeze a source tensor to match the dimensionality of a target tensor using prefix or suffix', 'expand a 1d batch vector to match the shape of a higher-dimensional target tensor', 'compute the gradient of an output tensor with respect to an input tensor using autograd', 'compute the gradient of an output tensor with respect to an input tensor and create a differentiable graph', 'review the tensor utility functions for unsqueeze, expand, and gradient operations in PyTorch']
```

Usage

```
{'unsqueeze_tensor_to_match': 'unsqueeze a source tensor to match the dimensionality of a target tensor using prefix or suffix', 'expand_tensor_like': 'expand a 1d batch vector to match the shape of a higher-dimensional target tensor', 'compute_gradient': 'compute the gradient of an output tensor with respect to an input tensor using autograd', 'compute_gradient_with_graph': 'compute the gradient of an output tensor with respect to an input tensor and create a differentiable graph', 'review_tensor_utils': 'review the tensor utility functions for unsqueeze, expand, and gradient operations in PyTorch'}
```

