# Agent Python Tools

- repo: facebookresearch/neuralstpp
- repo_uri: https://github.com/facebookresearch/neural_stpp

## File: facebookresearch_neuralstpp/diffeq_layers/basic.py

Prompts

```
['build a HyperLinear layer that uses a hypernetwork to generate time-dependent linear transformation weights', 'create a ConcatLinear layer that concatenates the time scalar with input before applying a linear transformation', 'build a HyperConv2d layer that uses a hypernetwork to generate time-dependent convolutional weights and biases', 'create a GatedLinear or GatedConv module that applies a sigmoid-gated transformation to input features', 'build a BlendLinear or BlendConv2d layer that interpolates between two parallel layers using a time scalar', 'build a SequentialDiffEq module chaining multiple diffeq layers together for sequential forward passes', 'create a MixtureODELayer that blends multiple expert ODE functions using time-dependent mixture weights', 'test the SequentialDiffEq forward method by passing time t and input x through chained layers', 'test the MixtureODELayer forward method by evaluating blended expert outputs with time-dependent weights', 'review the MixtureODELayer mixture_weights linear layer that computes time-dependent expert blending coefficients', 'build a DiffEqWrapper module that adapts a neural network to accept time and state inputs for ODE solving', 'create a diffeq_wrapper function call to wrap a layer so it accepts (t, y) or (y,) signatures', 'build a ReshapeDiffEq module that flattens and unflattens tensor shapes around a differential equation network', 'create a reshape_wrapper call to wrap a layer with automatic batch-aware tensor reshaping for ODE inputs', 'review the DiffEqWrapper forward method to understand how it inspects and routes calls based on parameter count']
```

Usage

```
{'build_hyperlinear_layer': 'build a HyperLinear layer that uses a hypernetwork to generate time-dependent linear transformation weights', 'create_concatlinear_layer': 'create a ConcatLinear layer that concatenates the time scalar with input before applying a linear transformation', 'build_hyperconv2d_layer': 'build a HyperConv2d layer that uses a hypernetwork to generate time-dependent convolutional weights and biases', 'create_gated_linear_conv': 'create a GatedLinear or GatedConv module that applies a sigmoid-gated transformation to input features', 'build_blend_linear_conv': 'build a BlendLinear or BlendConv2d layer that interpolates between two parallel layers using a time scalar'}
```

## File: facebookresearch_neuralstpp/diffeq_layers/container.py

Prompts

```
['build a HyperLinear layer that uses a hypernetwork to generate time-dependent linear transformation weights', 'create a ConcatLinear layer that concatenates the time scalar with input before applying a linear transformation', 'build a HyperConv2d layer that uses a hypernetwork to generate time-dependent convolutional weights and biases', 'create a GatedLinear or GatedConv module that applies a sigmoid-gated transformation to input features', 'build a BlendLinear or BlendConv2d layer that interpolates between two parallel layers using a time scalar', 'build a SequentialDiffEq module chaining multiple diffeq layers together for sequential forward passes', 'create a MixtureODELayer that blends multiple expert ODE functions using time-dependent mixture weights', 'test the SequentialDiffEq forward method by passing time t and input x through chained layers', 'test the MixtureODELayer forward method by evaluating blended expert outputs with time-dependent weights', 'review the MixtureODELayer mixture_weights linear layer that computes time-dependent expert blending coefficients', 'build a DiffEqWrapper module that adapts a neural network to accept time and state inputs for ODE solving', 'create a diffeq_wrapper function call to wrap a layer so it accepts (t, y) or (y,) signatures', 'build a ReshapeDiffEq module that flattens and unflattens tensor shapes around a differential equation network', 'create a reshape_wrapper call to wrap a layer with automatic batch-aware tensor reshaping for ODE inputs', 'review the DiffEqWrapper forward method to understand how it inspects and routes calls based on parameter count']
```

Usage

```
{'build_sequential_diffeq': 'build a SequentialDiffEq module chaining multiple diffeq layers together for sequential forward passes', 'create_mixture_ode_layer': 'create a MixtureODELayer that blends multiple expert ODE functions using time-dependent mixture weights', 'test_sequential_diffeq_forward': 'test the SequentialDiffEq forward method by passing time t and input x through chained layers', 'test_mixture_ode_forward': 'test the MixtureODELayer forward method by evaluating blended expert outputs with time-dependent weights', 'review_mixture_weights': 'review the MixtureODELayer mixture_weights linear layer that computes time-dependent expert blending coefficients'}
```

## File: facebookresearch_neuralstpp/diffeq_layers/wrappers.py

Prompts

```
['build a HyperLinear layer that uses a hypernetwork to generate time-dependent linear transformation weights', 'create a ConcatLinear layer that concatenates the time scalar with input before applying a linear transformation', 'build a HyperConv2d layer that uses a hypernetwork to generate time-dependent convolutional weights and biases', 'create a GatedLinear or GatedConv module that applies a sigmoid-gated transformation to input features', 'build a BlendLinear or BlendConv2d layer that interpolates between two parallel layers using a time scalar', 'build a SequentialDiffEq module chaining multiple diffeq layers together for sequential forward passes', 'create a MixtureODELayer that blends multiple expert ODE functions using time-dependent mixture weights', 'test the SequentialDiffEq forward method by passing time t and input x through chained layers', 'test the MixtureODELayer forward method by evaluating blended expert outputs with time-dependent weights', 'review the MixtureODELayer mixture_weights linear layer that computes time-dependent expert blending coefficients', 'build a DiffEqWrapper module that adapts a neural network to accept time and state inputs for ODE solving', 'create a diffeq_wrapper function call to wrap a layer so it accepts (t, y) or (y,) signatures', 'build a ReshapeDiffEq module that flattens and unflattens tensor shapes around a differential equation network', 'create a reshape_wrapper call to wrap a layer with automatic batch-aware tensor reshaping for ODE inputs', 'review the DiffEqWrapper forward method to understand how it inspects and routes calls based on parameter count']
```

Usage

```
{'build_DiffEqWrapper': 'build a DiffEqWrapper module that adapts a neural network to accept time and state inputs for ODE solving', 'create_diffeq_wrapper': 'create a diffeq_wrapper function call to wrap a layer so it accepts (t, y) or (y,) signatures', 'build_ReshapeDiffEq': 'build a ReshapeDiffEq module that flattens and unflattens tensor shapes around a differential equation network', 'create_reshape_wrapper': 'create a reshape_wrapper call to wrap a layer with automatic batch-aware tensor reshaping for ODE inputs', 'review_DiffEqWrapper_forward': 'review the DiffEqWrapper forward method to understand how it inspects and routes calls based on parameter count'}
```

