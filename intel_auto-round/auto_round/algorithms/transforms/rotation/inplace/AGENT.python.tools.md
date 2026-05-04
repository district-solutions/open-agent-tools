# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/auto_round/algorithms/transforms/rotation/inplace/apply.py

Prompts

```
['apply hadamard rotation to a huggingface causal lm model and register online hooks', 'rotate a linear layer weight matrix by a given rotation matrix Q on input or output side', 'fuse layernorm parameters into adjacent linear layer weights and biases in place', 'register online hadamard pre-forward hooks on down_proj and o_proj modules for inference', 'replace all layernorm modules in a model with rmsnorm modules that skip mean subtraction', 'register online Hadamard pre-forward hooks on down_proj and o_proj layers of a rotated HuggingFace model', 'apply Hadamard rotation to a Linear layer weight in-place on the input or output dimension', 'register per-group block-diagonal Hadamard hooks on down_proj and o_proj with a fixed group size', 'apply a cross-head Hadamard rotation to a Linear layer input side across attention heads', 'compute the butterfly Hadamard transform on a tensor using the get_hadK divisor and recursive butterfly pattern', 'create a RotationMapping dataclass to describe transformer architecture module paths for Hadamard rotation', 'register a new RotationMapping under a model type key in the MAPPING_REGISTRY dictionary', 'get a RotationMapping by key from the registry or fall back to the default LLaMA-like mapping', 'infer the best RotationMapping for a model by checking config model_type and class name', 'inspect the MAPPING_REGISTRY dictionary to see all registered RotationMapping entries for supported architectures']
```

Usage

```
{'apply_rotation_transform': 'apply hadamard rotation to a huggingface causal lm model and register online hooks', 'rotate_linear_by_Q': 'rotate a linear layer weight matrix by a given rotation matrix Q on input or output side', 'fuse_ln_linear': 'fuse layernorm parameters into adjacent linear layer weights and biases in place', 'register_online_hooks': 'register online hadamard pre-forward hooks on down_proj and o_proj modules for inference', 'replace_layernorms_with_rmsnorm': 'replace all layernorm modules in a model with rmsnorm modules that skip mean subtraction'}
```

## File: intel_auto-round/auto_round/algorithms/transforms/rotation/inplace/hooks.py

Prompts

```
['apply hadamard rotation to a huggingface causal lm model and register online hooks', 'rotate a linear layer weight matrix by a given rotation matrix Q on input or output side', 'fuse layernorm parameters into adjacent linear layer weights and biases in place', 'register online hadamard pre-forward hooks on down_proj and o_proj modules for inference', 'replace all layernorm modules in a model with rmsnorm modules that skip mean subtraction', 'register online Hadamard pre-forward hooks on down_proj and o_proj layers of a rotated HuggingFace model', 'apply Hadamard rotation to a Linear layer weight in-place on the input or output dimension', 'register per-group block-diagonal Hadamard hooks on down_proj and o_proj with a fixed group size', 'apply a cross-head Hadamard rotation to a Linear layer input side across attention heads', 'compute the butterfly Hadamard transform on a tensor using the get_hadK divisor and recursive butterfly pattern', 'create a RotationMapping dataclass to describe transformer architecture module paths for Hadamard rotation', 'register a new RotationMapping under a model type key in the MAPPING_REGISTRY dictionary', 'get a RotationMapping by key from the registry or fall back to the default LLaMA-like mapping', 'infer the best RotationMapping for a model by checking config model_type and class name', 'inspect the MAPPING_REGISTRY dictionary to see all registered RotationMapping entries for supported architectures']
```

Usage

```
{'register_online_had_hooks': 'register online Hadamard pre-forward hooks on down_proj and o_proj layers of a rotated HuggingFace model', 'apply_exact_had_to_linear': 'apply Hadamard rotation to a Linear layer weight in-place on the input or output dimension', 'register_online_had_hooks_grouped': 'register per-group block-diagonal Hadamard hooks on down_proj and o_proj with a fixed group size', 'apply_cross_head_had_to_linear': 'apply a cross-head Hadamard rotation to a Linear layer input side across attention heads', 'matmul_hadU': 'compute the butterfly Hadamard transform on a tensor using the get_hadK divisor and recursive butterfly pattern'}
```

## File: intel_auto-round/auto_round/algorithms/transforms/rotation/inplace/model_config.py

Prompts

```
['apply hadamard rotation to a huggingface causal lm model and register online hooks', 'rotate a linear layer weight matrix by a given rotation matrix Q on input or output side', 'fuse layernorm parameters into adjacent linear layer weights and biases in place', 'register online hadamard pre-forward hooks on down_proj and o_proj modules for inference', 'replace all layernorm modules in a model with rmsnorm modules that skip mean subtraction', 'register online Hadamard pre-forward hooks on down_proj and o_proj layers of a rotated HuggingFace model', 'apply Hadamard rotation to a Linear layer weight in-place on the input or output dimension', 'register per-group block-diagonal Hadamard hooks on down_proj and o_proj with a fixed group size', 'apply a cross-head Hadamard rotation to a Linear layer input side across attention heads', 'compute the butterfly Hadamard transform on a tensor using the get_hadK divisor and recursive butterfly pattern', 'create a RotationMapping dataclass to describe transformer architecture module paths for Hadamard rotation', 'register a new RotationMapping under a model type key in the MAPPING_REGISTRY dictionary', 'get a RotationMapping by key from the registry or fall back to the default LLaMA-like mapping', 'infer the best RotationMapping for a model by checking config model_type and class name', 'inspect the MAPPING_REGISTRY dictionary to see all registered RotationMapping entries for supported architectures']
```

Usage

```
{'create_RotationMapping': 'create a RotationMapping dataclass to describe transformer architecture module paths for Hadamard rotation', 'register_mapping': 'register a new RotationMapping under a model type key in the MAPPING_REGISTRY dictionary', 'get_mapping': 'get a RotationMapping by key from the registry or fall back to the default LLaMA-like mapping', 'infer_mapping_from_model': 'infer the best RotationMapping for a model by checking config model_type and class name', 'inspect_MAPPING_REGISTRY': 'inspect the MAPPING_REGISTRY dictionary to see all registered RotationMapping entries for supported architectures'}
```

