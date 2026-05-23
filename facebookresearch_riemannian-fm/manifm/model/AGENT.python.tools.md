# Agent Python Tools

- repo: facebookresearch/riemannian-fm
- repo_uri: https://github.com/facebookresearch/riemannian-fm

## File: facebookresearch_riemannian-fm/manifm/model/actfn.py

Prompts

```
['create a Sine activation module that applies torch.sin to input tensor x', 'create a Softplus activation module with configurable beta parameter for smooth non-linearity', 'use the Sine forward method to compute sin of tensor x with time input t', 'use the Softplus forward method to apply softplus with beta=100 to tensor x', 'review the Sine and Softplus activation function classes for use in neural network models', 'build a time-dependent MLP with configurable layers, activation functions, and optional Fourier positional encoding', 'create a PositionalEncoding module that maps inputs in [0, 2pi] to sin and cos Fourier features', 'create an Unbatch wrapper that handles batched and unbatched inputs for a vector field module', 'create a ProjectToTangent module that projects a vector field onto the tangent plane of a manifold', 'review the ACTFNS dictionary mapping activation function names to their corresponding diffeq layer classes']
```

Usage

```
{'create_sine_activation': 'create a Sine activation module that applies torch.sin to input tensor x', 'create_softplus_activation': 'create a Softplus activation module with configurable beta parameter for smooth non-linearity', 'use_sine_forward': 'use the Sine forward method to compute sin of tensor x with time input t', 'use_softplus_forward': 'use the Softplus forward method to apply softplus with beta=100 to tensor x', 'review_activation_classes': 'review the Sine and Softplus activation function classes for use in neural network models'}
```

## File: facebookresearch_riemannian-fm/manifm/model/arch.py

Prompts

```
['create a Sine activation module that applies torch.sin to input tensor x', 'create a Softplus activation module with configurable beta parameter for smooth non-linearity', 'use the Sine forward method to compute sin of tensor x with time input t', 'use the Softplus forward method to apply softplus with beta=100 to tensor x', 'review the Sine and Softplus activation function classes for use in neural network models', 'build a time-dependent MLP with configurable layers, activation functions, and optional Fourier positional encoding', 'create a PositionalEncoding module that maps inputs in [0, 2pi] to sin and cos Fourier features', 'create an Unbatch wrapper that handles batched and unbatched inputs for a vector field module', 'create a ProjectToTangent module that projects a vector field onto the tangent plane of a manifold', 'review the ACTFNS dictionary mapping activation function names to their corresponding diffeq layer classes']
```

Usage

```
{'build_tMLP': 'build a time-dependent MLP with configurable layers, activation functions, and optional Fourier positional encoding', 'create_PositionalEncoding': 'create a PositionalEncoding module that maps inputs in [0, 2pi] to sin and cos Fourier features', 'create_Unbatch': 'create an Unbatch wrapper that handles batched and unbatched inputs for a vector field module', 'create_ProjectToTangent': 'create a ProjectToTangent module that projects a vector field onto the tangent plane of a manifold', 'review_ACTFNS': 'review the ACTFNS dictionary mapping activation function names to their corresponding diffeq layer classes'}
```

