# Agent Python Tools

- repo: facebookresearch/perfect
- repo_uri: https://github.com/facebookresearch/perfect

## File: facebookresearch_perfect/fewshot/adapters/adapter_controller.py

Prompts

```
['create an AdapterController instance with a config object and input dimension for transformer adapter layers', "call construct_adapters to build Adapter layers from the controller's config and input dimension", 'run the forward pass through the adapter controller with optional layer normalization before and after', 'set add_layer_norm_before_adapter in config to enable pre-adapter layer normalization on inputs', 'set add_layer_norm_after_adapter in config to enable post-adapter layer normalization on outputs', 'create an Adapter instance with a config and input_dim to build a bottleneck adapter layer', 'run the Adapter forward pass by passing a tensor through down-sampler, activation, and up-sampler', 'configure the Adapter reduction_factor in AdapterConfig to control the bottleneck down-sample size', 'review the Adapter nonlinearity setting in AdapterConfig to choose the activation function for the bottleneck', 'test the Adapter module by instantiating it with AdapterConfig and verifying forward pass output shape', 'create a PyTorch nn.Module that wraps a HuggingFace activation function by type string', 'build a forward pass that applies a configurable activation function to an input tensor', 'test the Activations class initialization with a specific activation type string', 'refactor the Activations class to support additional activation function configurations', 'review the Activations class and its use of transformers get_activation for PyTorch modules']
```

Usage

```
{'create_adapter_controller': 'create an AdapterController instance with a config object and input dimension for transformer adapter layers', 'construct_adapters': "call construct_adapters to build Adapter layers from the controller's config and input dimension", 'forward_adapter': 'run the forward pass through the adapter controller with optional layer normalization before and after', 'configure_layer_norm_before': 'set add_layer_norm_before_adapter in config to enable pre-adapter layer normalization on inputs', 'configure_layer_norm_after': 'set add_layer_norm_after_adapter in config to enable post-adapter layer normalization on outputs'}
```

## File: facebookresearch_perfect/fewshot/adapters/adapter_modeling.py

Prompts

```
['create an AdapterController instance with a config object and input dimension for transformer adapter layers', "call construct_adapters to build Adapter layers from the controller's config and input dimension", 'run the forward pass through the adapter controller with optional layer normalization before and after', 'set add_layer_norm_before_adapter in config to enable pre-adapter layer normalization on inputs', 'set add_layer_norm_after_adapter in config to enable post-adapter layer normalization on outputs', 'create an Adapter instance with a config and input_dim to build a bottleneck adapter layer', 'run the Adapter forward pass by passing a tensor through down-sampler, activation, and up-sampler', 'configure the Adapter reduction_factor in AdapterConfig to control the bottleneck down-sample size', 'review the Adapter nonlinearity setting in AdapterConfig to choose the activation function for the bottleneck', 'test the Adapter module by instantiating it with AdapterConfig and verifying forward pass output shape', 'create a PyTorch nn.Module that wraps a HuggingFace activation function by type string', 'build a forward pass that applies a configurable activation function to an input tensor', 'test the Activations class initialization with a specific activation type string', 'refactor the Activations class to support additional activation function configurations', 'review the Activations class and its use of transformers get_activation for PyTorch modules']
```

Usage

```
{'create_adapter_layer': 'create an Adapter instance with a config and input_dim to build a bottleneck adapter layer', 'run_adapter_forward': 'run the Adapter forward pass by passing a tensor through down-sampler, activation, and up-sampler', 'configure_adapter_reduction': 'configure the Adapter reduction_factor in AdapterConfig to control the bottleneck down-sample size', 'review_adapter_nonlinearity': 'review the Adapter nonlinearity setting in AdapterConfig to choose the activation function for the bottleneck', 'test_adapter_integration': 'test the Adapter module by instantiating it with AdapterConfig and verifying forward pass output shape'}
```

## File: facebookresearch_perfect/fewshot/adapters/utils.py

Prompts

```
['create an AdapterController instance with a config object and input dimension for transformer adapter layers', "call construct_adapters to build Adapter layers from the controller's config and input dimension", 'run the forward pass through the adapter controller with optional layer normalization before and after', 'set add_layer_norm_before_adapter in config to enable pre-adapter layer normalization on inputs', 'set add_layer_norm_after_adapter in config to enable post-adapter layer normalization on outputs', 'create an Adapter instance with a config and input_dim to build a bottleneck adapter layer', 'run the Adapter forward pass by passing a tensor through down-sampler, activation, and up-sampler', 'configure the Adapter reduction_factor in AdapterConfig to control the bottleneck down-sample size', 'review the Adapter nonlinearity setting in AdapterConfig to choose the activation function for the bottleneck', 'test the Adapter module by instantiating it with AdapterConfig and verifying forward pass output shape', 'create a PyTorch nn.Module that wraps a HuggingFace activation function by type string', 'build a forward pass that applies a configurable activation function to an input tensor', 'test the Activations class initialization with a specific activation type string', 'refactor the Activations class to support additional activation function configurations', 'review the Activations class and its use of transformers get_activation for PyTorch modules']
```

Usage

```
{'create_activations_module': 'create a PyTorch nn.Module that wraps a HuggingFace activation function by type string', 'build_activations_forward': 'build a forward pass that applies a configurable activation function to an input tensor', 'test_activations_init': 'test the Activations class initialization with a specific activation type string', 'refactor_activations_class': 'refactor the Activations class to support additional activation function configurations', 'review_activations_usage': 'review the Activations class and its use of transformers get_activation for PyTorch modules'}
```

