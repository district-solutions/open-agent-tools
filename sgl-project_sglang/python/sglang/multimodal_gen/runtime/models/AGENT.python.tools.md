# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/models/parameter.py

Prompts

```
['create a BasevLLMParameter with tensor data and a weight_loader callable for vLLM-style weight loading', 'load column-parallel weight into a _ColumnvLLMParameter by sharding along the output dimension across tensor-parallel ranks', 'load row-parallel weight into a RowvLLMParameter by sharding along the input dimension across tensor-parallel ranks', 'load QKV weight into a _ColumnvLLMParameter with shard_id mapping for q, k, v heads across tensor-parallel ranks', "permute a parameter's tensor layout to a specified input_dim and output_dim for known weight matrix orientation", 'resolve the model class for a given model architecture name from the registry', 'inspect the model info for a given model architecture without loading it into memory', 'register a new model architecture with its class or module path string in the model registry', 'get the set of all supported model architectures registered in the model registry', 'resolve a model class by its external alias name mapped through the alias registry', 'set attributes on a PyTorch weight tensor without overwriting existing attributes', 'extract the layer index from a module name string containing a single integer', 'modulate a tensor by applying optional shift and scale factors', 'convert predicted noise to a clean video latent using a scheduler and timestep', 'wrap a weight loader to sync the parameter tensor after loading on TPU platforms', 'convert a PIL image or list of PIL images to a NumPy array', 'convert a NumPy image array to a PyTorch tensor', 'load an image from a local path or URL and return a PIL Image', 'load a video from a local path or URL and return a list of PIL Images', 'resize a PIL image to specified height and width with lanczos resampling']
```

Usage

```
{'create_parameter': 'create a BasevLLMParameter with tensor data and a weight_loader callable for vLLM-style weight loading', 'load_column_parallel_weight': 'load column-parallel weight into a _ColumnvLLMParameter by sharding along the output dimension across tensor-parallel ranks', 'load_row_parallel_weight': 'load row-parallel weight into a RowvLLMParameter by sharding along the input dimension across tensor-parallel ranks', 'load_qkv_weight': 'load QKV weight into a _ColumnvLLMParameter with shard_id mapping for q, k, v heads across tensor-parallel ranks', 'permute_param_layout': "permute a parameter's tensor layout to a specified input_dim and output_dim for known weight matrix orientation"}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/models/registry.py

Prompts

```
['create a BasevLLMParameter with tensor data and a weight_loader callable for vLLM-style weight loading', 'load column-parallel weight into a _ColumnvLLMParameter by sharding along the output dimension across tensor-parallel ranks', 'load row-parallel weight into a RowvLLMParameter by sharding along the input dimension across tensor-parallel ranks', 'load QKV weight into a _ColumnvLLMParameter with shard_id mapping for q, k, v heads across tensor-parallel ranks', "permute a parameter's tensor layout to a specified input_dim and output_dim for known weight matrix orientation", 'resolve the model class for a given model architecture name from the registry', 'inspect the model info for a given model architecture without loading it into memory', 'register a new model architecture with its class or module path string in the model registry', 'get the set of all supported model architectures registered in the model registry', 'resolve a model class by its external alias name mapped through the alias registry', 'set attributes on a PyTorch weight tensor without overwriting existing attributes', 'extract the layer index from a module name string containing a single integer', 'modulate a tensor by applying optional shift and scale factors', 'convert predicted noise to a clean video latent using a scheduler and timestep', 'wrap a weight loader to sync the parameter tensor after loading on TPU platforms', 'convert a PIL image or list of PIL images to a NumPy array', 'convert a NumPy image array to a PyTorch tensor', 'load an image from a local path or URL and return a PIL Image', 'load a video from a local path or URL and return a list of PIL Images', 'resize a PIL image to specified height and width with lanczos resampling']
```

Usage

```
{'resolve_MODELARCH': 'resolve the model class for a given model architecture name from the registry', 'inspect_MODELARCH': 'inspect the model info for a given model architecture without loading it into memory', 'register_MODELARCH_MODELCLS': 'register a new model architecture with its class or module path string in the model registry', 'get_supported_ARCHS': 'get the set of all supported model architectures registered in the model registry', 'resolve_BYALIAS': 'resolve a model class by its external alias name mapped through the alias registry'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/models/utils.py

Prompts

```
['create a BasevLLMParameter with tensor data and a weight_loader callable for vLLM-style weight loading', 'load column-parallel weight into a _ColumnvLLMParameter by sharding along the output dimension across tensor-parallel ranks', 'load row-parallel weight into a RowvLLMParameter by sharding along the input dimension across tensor-parallel ranks', 'load QKV weight into a _ColumnvLLMParameter with shard_id mapping for q, k, v heads across tensor-parallel ranks', "permute a parameter's tensor layout to a specified input_dim and output_dim for known weight matrix orientation", 'resolve the model class for a given model architecture name from the registry', 'inspect the model info for a given model architecture without loading it into memory', 'register a new model architecture with its class or module path string in the model registry', 'get the set of all supported model architectures registered in the model registry', 'resolve a model class by its external alias name mapped through the alias registry', 'set attributes on a PyTorch weight tensor without overwriting existing attributes', 'extract the layer index from a module name string containing a single integer', 'modulate a tensor by applying optional shift and scale factors', 'convert predicted noise to a clean video latent using a scheduler and timestep', 'wrap a weight loader to sync the parameter tensor after loading on TPU platforms', 'convert a PIL image or list of PIL images to a NumPy array', 'convert a NumPy image array to a PyTorch tensor', 'load an image from a local path or URL and return a PIL Image', 'load a video from a local path or URL and return a list of PIL Images', 'resize a PIL image to specified height and width with lanczos resampling']
```

Usage

```
{'set_weight_attrs_tensor': 'set attributes on a PyTorch weight tensor without overwriting existing attributes', 'extract_layer_index': 'extract the layer index from a module name string containing a single integer', 'modulate_tensor': 'modulate a tensor by applying optional shift and scale factors', 'pred_noise_to_pred_video': 'convert predicted noise to a clean video latent using a scheduler and timestep', 'make_synced_weight_loader': 'wrap a weight loader to sync the parameter tensor after loading on TPU platforms'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/models/vision_utils.py

Prompts

```
['create a BasevLLMParameter with tensor data and a weight_loader callable for vLLM-style weight loading', 'load column-parallel weight into a _ColumnvLLMParameter by sharding along the output dimension across tensor-parallel ranks', 'load row-parallel weight into a RowvLLMParameter by sharding along the input dimension across tensor-parallel ranks', 'load QKV weight into a _ColumnvLLMParameter with shard_id mapping for q, k, v heads across tensor-parallel ranks', "permute a parameter's tensor layout to a specified input_dim and output_dim for known weight matrix orientation", 'resolve the model class for a given model architecture name from the registry', 'inspect the model info for a given model architecture without loading it into memory', 'register a new model architecture with its class or module path string in the model registry', 'get the set of all supported model architectures registered in the model registry', 'resolve a model class by its external alias name mapped through the alias registry', 'set attributes on a PyTorch weight tensor without overwriting existing attributes', 'extract the layer index from a module name string containing a single integer', 'modulate a tensor by applying optional shift and scale factors', 'convert predicted noise to a clean video latent using a scheduler and timestep', 'wrap a weight loader to sync the parameter tensor after loading on TPU platforms', 'convert a PIL image or list of PIL images to a NumPy array', 'convert a NumPy image array to a PyTorch tensor', 'load an image from a local path or URL and return a PIL Image', 'load a video from a local path or URL and return a list of PIL Images', 'resize a PIL image to specified height and width with lanczos resampling']
```

Usage

```
{'create_pil_to_numpy': 'convert a PIL image or list of PIL images to a NumPy array', 'create_numpy_to_pt': 'convert a NumPy image array to a PyTorch tensor', 'create_load_image': 'load an image from a local path or URL and return a PIL Image', 'create_load_video': 'load a video from a local path or URL and return a list of PIL Images', 'create_resize_image': 'resize a PIL image to specified height and width with lanczos resampling'}
```

