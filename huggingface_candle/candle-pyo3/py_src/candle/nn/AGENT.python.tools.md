# Agent Python Tools

- repo: huggingface/candle
- repo_uri: https://github.com/huggingface/candle

## File: huggingface_candle/candle-pyo3/py_src/candle/nn/container.py

Prompts

```
['create a Sequential container that chains modules in order and forwards input through each module', 'build a ModuleList to hold and register submodules in an indexed list', 'create a ModuleDict to hold and register submodules in an ordered dictionary', 'extend a Sequential container by appending modules from another Sequential or iterable', 'update a ModuleDict with key-value pairs of string names and module instances', 'create an Identity module that passes input tensors through unchanged', 'create a Linear layer with specified in_features and out_features for neural networks', 'build a Linear layer with bias set to False for custom neural network architectures', 'test the Linear forward method with a 2D or 3D input tensor', 'review the Linear forward method QTensor quantized matmul implementation', 'create a subclass of candle.nn.Module and override the forward method to define a neural network layer', 'add a child module to a candle.nn.Module instance using add_module with a name and module argument', 'save the full state of a candle.nn.Module including parameters and buffers to an OrderedDict via state_dict', 'load parameters and buffers from a state_dict into a candle.nn.Module using load_state_dict with strict mode', 'move all parameters and buffers of a candle.nn.Module to cuda or cpu using the to method', 'create a LayerNorm module with a specified normalized_shape and default epsilon value', 'create a LayerNorm module with bias disabled for a given normalized shape', 'run the forward pass of a LayerNorm module on an input Tensor', 'review the LayerNorm forward method to understand the normalization computation steps', 'refactor the LayerNorm class to support a custom epsilon value for numerical stability', 'create an Embedding layer with num_embeddings and embedding_dim parameters for word lookup', 'initialize embedding weights using candle.randn with shape num_embeddings by embedding_dim', 'forward pass indexes through Embedding to retrieve corresponding embedding vectors', 'reshape embedding output to match input shape with appended embedding dimension', 'use index_select on embedding weights to retrieve embeddings by index tensor']
```

Usage

```
{'create_sequential_model': 'create a Sequential container that chains modules in order and forwards input through each module', 'build_module_list': 'build a ModuleList to hold and register submodules in an indexed list', 'create_module_dict': 'create a ModuleDict to hold and register submodules in an ordered dictionary', 'extend_sequential_with_modules': 'extend a Sequential container by appending modules from another Sequential or iterable', 'update_module_dict': 'update a ModuleDict with key-value pairs of string names and module instances'}
```

## File: huggingface_candle/candle-pyo3/py_src/candle/nn/linear.py

Prompts

```
['create a Sequential container that chains modules in order and forwards input through each module', 'build a ModuleList to hold and register submodules in an indexed list', 'create a ModuleDict to hold and register submodules in an ordered dictionary', 'extend a Sequential container by appending modules from another Sequential or iterable', 'update a ModuleDict with key-value pairs of string names and module instances', 'create an Identity module that passes input tensors through unchanged', 'create a Linear layer with specified in_features and out_features for neural networks', 'build a Linear layer with bias set to False for custom neural network architectures', 'test the Linear forward method with a 2D or 3D input tensor', 'review the Linear forward method QTensor quantized matmul implementation', 'create a subclass of candle.nn.Module and override the forward method to define a neural network layer', 'add a child module to a candle.nn.Module instance using add_module with a name and module argument', 'save the full state of a candle.nn.Module including parameters and buffers to an OrderedDict via state_dict', 'load parameters and buffers from a state_dict into a candle.nn.Module using load_state_dict with strict mode', 'move all parameters and buffers of a candle.nn.Module to cuda or cpu using the to method', 'create a LayerNorm module with a specified normalized_shape and default epsilon value', 'create a LayerNorm module with bias disabled for a given normalized shape', 'run the forward pass of a LayerNorm module on an input Tensor', 'review the LayerNorm forward method to understand the normalization computation steps', 'refactor the LayerNorm class to support a custom epsilon value for numerical stability', 'create an Embedding layer with num_embeddings and embedding_dim parameters for word lookup', 'initialize embedding weights using candle.randn with shape num_embeddings by embedding_dim', 'forward pass indexes through Embedding to retrieve corresponding embedding vectors', 'reshape embedding output to match input shape with appended embedding dimension', 'use index_select on embedding weights to retrieve embeddings by index tensor']
```

Usage

```
{'create_identity_module': 'create an Identity module that passes input tensors through unchanged', 'create_linear_layer': 'create a Linear layer with specified in_features and out_features for neural networks', 'build_linear_without_bias': 'build a Linear layer with bias set to False for custom neural network architectures', 'test_linear_forward': 'test the Linear forward method with a 2D or 3D input tensor', 'review_linear_quantized': 'review the Linear forward method QTensor quantized matmul implementation'}
```

## File: huggingface_candle/candle-pyo3/py_src/candle/nn/module.py

Prompts

```
['create a Sequential container that chains modules in order and forwards input through each module', 'build a ModuleList to hold and register submodules in an indexed list', 'create a ModuleDict to hold and register submodules in an ordered dictionary', 'extend a Sequential container by appending modules from another Sequential or iterable', 'update a ModuleDict with key-value pairs of string names and module instances', 'create an Identity module that passes input tensors through unchanged', 'create a Linear layer with specified in_features and out_features for neural networks', 'build a Linear layer with bias set to False for custom neural network architectures', 'test the Linear forward method with a 2D or 3D input tensor', 'review the Linear forward method QTensor quantized matmul implementation', 'create a subclass of candle.nn.Module and override the forward method to define a neural network layer', 'add a child module to a candle.nn.Module instance using add_module with a name and module argument', 'save the full state of a candle.nn.Module including parameters and buffers to an OrderedDict via state_dict', 'load parameters and buffers from a state_dict into a candle.nn.Module using load_state_dict with strict mode', 'move all parameters and buffers of a candle.nn.Module to cuda or cpu using the to method', 'create a LayerNorm module with a specified normalized_shape and default epsilon value', 'create a LayerNorm module with bias disabled for a given normalized shape', 'run the forward pass of a LayerNorm module on an input Tensor', 'review the LayerNorm forward method to understand the normalization computation steps', 'refactor the LayerNorm class to support a custom epsilon value for numerical stability', 'create an Embedding layer with num_embeddings and embedding_dim parameters for word lookup', 'initialize embedding weights using candle.randn with shape num_embeddings by embedding_dim', 'forward pass indexes through Embedding to retrieve corresponding embedding vectors', 'reshape embedding output to match input shape with appended embedding dimension', 'use index_select on embedding weights to retrieve embeddings by index tensor']
```

Usage

```
{'create_neural_network_module': 'create a subclass of candle.nn.Module and override the forward method to define a neural network layer', 'add_child_module': 'add a child module to a candle.nn.Module instance using add_module with a name and module argument', 'save_state_dict': 'save the full state of a candle.nn.Module including parameters and buffers to an OrderedDict via state_dict', 'load_state_dict': 'load parameters and buffers from a state_dict into a candle.nn.Module using load_state_dict with strict mode', 'move_module_to_device': 'move all parameters and buffers of a candle.nn.Module to cuda or cpu using the to method'}
```

## File: huggingface_candle/candle-pyo3/py_src/candle/nn/normalization.py

Prompts

```
['create a Sequential container that chains modules in order and forwards input through each module', 'build a ModuleList to hold and register submodules in an indexed list', 'create a ModuleDict to hold and register submodules in an ordered dictionary', 'extend a Sequential container by appending modules from another Sequential or iterable', 'update a ModuleDict with key-value pairs of string names and module instances', 'create an Identity module that passes input tensors through unchanged', 'create a Linear layer with specified in_features and out_features for neural networks', 'build a Linear layer with bias set to False for custom neural network architectures', 'test the Linear forward method with a 2D or 3D input tensor', 'review the Linear forward method QTensor quantized matmul implementation', 'create a subclass of candle.nn.Module and override the forward method to define a neural network layer', 'add a child module to a candle.nn.Module instance using add_module with a name and module argument', 'save the full state of a candle.nn.Module including parameters and buffers to an OrderedDict via state_dict', 'load parameters and buffers from a state_dict into a candle.nn.Module using load_state_dict with strict mode', 'move all parameters and buffers of a candle.nn.Module to cuda or cpu using the to method', 'create a LayerNorm module with a specified normalized_shape and default epsilon value', 'create a LayerNorm module with bias disabled for a given normalized shape', 'run the forward pass of a LayerNorm module on an input Tensor', 'review the LayerNorm forward method to understand the normalization computation steps', 'refactor the LayerNorm class to support a custom epsilon value for numerical stability', 'create an Embedding layer with num_embeddings and embedding_dim parameters for word lookup', 'initialize embedding weights using candle.randn with shape num_embeddings by embedding_dim', 'forward pass indexes through Embedding to retrieve corresponding embedding vectors', 'reshape embedding output to match input shape with appended embedding dimension', 'use index_select on embedding weights to retrieve embeddings by index tensor']
```

Usage

```
{'create_layernorm_instance': 'create a LayerNorm module with a specified normalized_shape and default epsilon value', 'create_layernorm_no_bias': 'create a LayerNorm module with bias disabled for a given normalized shape', 'forward_layernorm': 'run the forward pass of a LayerNorm module on an input Tensor', 'review_layernorm_forward': 'review the LayerNorm forward method to understand the normalization computation steps', 'refactor_layernorm_eps': 'refactor the LayerNorm class to support a custom epsilon value for numerical stability'}
```

## File: huggingface_candle/candle-pyo3/py_src/candle/nn/sparse.py

Prompts

```
['create a Sequential container that chains modules in order and forwards input through each module', 'build a ModuleList to hold and register submodules in an indexed list', 'create a ModuleDict to hold and register submodules in an ordered dictionary', 'extend a Sequential container by appending modules from another Sequential or iterable', 'update a ModuleDict with key-value pairs of string names and module instances', 'create an Identity module that passes input tensors through unchanged', 'create a Linear layer with specified in_features and out_features for neural networks', 'build a Linear layer with bias set to False for custom neural network architectures', 'test the Linear forward method with a 2D or 3D input tensor', 'review the Linear forward method QTensor quantized matmul implementation', 'create a subclass of candle.nn.Module and override the forward method to define a neural network layer', 'add a child module to a candle.nn.Module instance using add_module with a name and module argument', 'save the full state of a candle.nn.Module including parameters and buffers to an OrderedDict via state_dict', 'load parameters and buffers from a state_dict into a candle.nn.Module using load_state_dict with strict mode', 'move all parameters and buffers of a candle.nn.Module to cuda or cpu using the to method', 'create a LayerNorm module with a specified normalized_shape and default epsilon value', 'create a LayerNorm module with bias disabled for a given normalized shape', 'run the forward pass of a LayerNorm module on an input Tensor', 'review the LayerNorm forward method to understand the normalization computation steps', 'refactor the LayerNorm class to support a custom epsilon value for numerical stability', 'create an Embedding layer with num_embeddings and embedding_dim parameters for word lookup', 'initialize embedding weights using candle.randn with shape num_embeddings by embedding_dim', 'forward pass indexes through Embedding to retrieve corresponding embedding vectors', 'reshape embedding output to match input shape with appended embedding dimension', 'use index_select on embedding weights to retrieve embeddings by index tensor']
```

Usage

```
{'create_embedding_layer': 'create an Embedding layer with num_embeddings and embedding_dim parameters for word lookup', 'initialize_embedding_weights': 'initialize embedding weights using candle.randn with shape num_embeddings by embedding_dim', 'forward_embedding_lookup': 'forward pass indexes through Embedding to retrieve corresponding embedding vectors', 'reshape_embedding_output': 'reshape embedding output to match input shape with appended embedding dimension', 'index_select_embeddings': 'use index_select on embedding weights to retrieve embeddings by index tensor'}
```

