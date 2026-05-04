# Agent Python Tools

- repo: facebookresearch/dynamicstereo
- repo_uri: https://github.com/facebookresearch/dynamic_stereo

## File: facebookresearch_dynamicstereo/models/core/utils/config.py

Prompts

```
['get the default DictConfig arguments for a Configurable or ReplaceableBase class', 'expand a Configurable class into a dataclass with auto-generated args fields', 'run all creation functions to initialize nested Configurable members in __post_init__', 'register a subclass of ReplaceableBase in the global registry by name', 'remove unused pluggable component args from a DictConfig in place', 'create an InputPadder instance in sintel mode to pad 4D tensors to dimensions divisible by 8', 'create an InputPadder instance in kitti mode to pad tensors with height padding applied only to the bottom', 'pad multiple 4D input tensors using an InputPadder so their spatial dimensions are divisible by 8', 'unpad a 4D tensor back to its original dimensions using the same InputPadder instance', 'interpolate a tensor to a target size using bilinear interpolation with align corners enabled']
```

Usage

```
{'get_default_args_Configurable': 'get the default DictConfig arguments for a Configurable or ReplaceableBase class', 'expand_args_fields_Configurable': 'expand a Configurable class into a dataclass with auto-generated args fields', 'run_auto_creation_Configurable': 'run all creation functions to initialize nested Configurable members in __post_init__', 'registry_register_ReplaceableBase': 'register a subclass of ReplaceableBase in the global registry by name', 'remove_unused_components_DictConfig': 'remove unused pluggable component args from a DictConfig in place'}
```

## File: facebookresearch_dynamicstereo/models/core/utils/utils.py

Prompts

```
['get the default DictConfig arguments for a Configurable or ReplaceableBase class', 'expand a Configurable class into a dataclass with auto-generated args fields', 'run all creation functions to initialize nested Configurable members in __post_init__', 'register a subclass of ReplaceableBase in the global registry by name', 'remove unused pluggable component args from a DictConfig in place', 'create an InputPadder instance in sintel mode to pad 4D tensors to dimensions divisible by 8', 'create an InputPadder instance in kitti mode to pad tensors with height padding applied only to the bottom', 'pad multiple 4D input tensors using an InputPadder so their spatial dimensions are divisible by 8', 'unpad a 4D tensor back to its original dimensions using the same InputPadder instance', 'interpolate a tensor to a target size using bilinear interpolation with align corners enabled']
```

Usage

```
{'create_InputPadder_sintel_mode': 'create an InputPadder instance in sintel mode to pad 4D tensors to dimensions divisible by 8', 'create_InputPadder_kitti_mode': 'create an InputPadder instance in kitti mode to pad tensors with height padding applied only to the bottom', 'pad_tensors_with_InputPadder': 'pad multiple 4D input tensors using an InputPadder so their spatial dimensions are divisible by 8', 'unpad_tensor_with_InputPadder': 'unpad a 4D tensor back to its original dimensions using the same InputPadder instance', 'interpolate_tensor_bilinear': 'interpolate a tensor to a target size using bilinear interpolation with align corners enabled'}
```

