# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/auto_round/auto_scheme/delta_loss.py

Prompts

```
['generate an optimal per-layer quantization config for a model using delta loss scoring and DP bit-budget optimization', 'score a quantization scheme by computing mixed weight and activation quantization loss across all quantizable layers', 'solve a DP knapsack problem to pick the best per-layer quantization scheme within a total bit budget', 'compute the activation importance matrix for a model by accumulating squared activation norms across a calibration dataset', 'run a block-by-block forward and backward pass with gradient checkpointing to score quantization under low GPU memory', 'create an AutoScheme dataclass with avg_bits target and quantization options for model layer schemes', 'build a GenScheme instance with an AutoScheme config, model, quant layer names, and tokenizer', 'get the layer configuration dictionary by calling get_layer_config on a GenScheme instance', 'compute the minimum and maximum average bitwidths across candidate quantization options for a model', 'apply GGUF quantization type fallback for layers with incompatible input feature alignment', 'use the register_scheme_methods decorator to register a mixed precision algorithm class into the AUTO_SCHEME_METHODS registry', 'use the register_scheme_methods decorator with a list of names to register an algorithm under multiple keys', 'access the AUTO_SCHEME_METHODS dictionary to retrieve a registered mixed precision algorithm class by its name', 'review the register_scheme_methods decorator to understand how it maps algorithm classes to string keys in the registry', 'summarize the AUTO_SCHEME_METHODS dictionary registry that stores mixed precision algorithm classes keyed by their scheme names', 'apply a quantization scheme to specified layers of a PyTorch model using preset names or custom dictionaries', 'remove all quantization scheme attributes from every module in a PyTorch model', 'compute the average and total bit usage for a quantization scheme across specified model layers', 'compute the total and average bitwidth for a single quantized layer including scale and zero-point overhead', 'parse and match shared layer groups in a model using regex patterns or substring matching']
```

Usage

```
{'gen_layer_config': 'generate an optimal per-layer quantization config for a model using delta loss scoring and DP bit-budget optimization', 'get_score_for_scheme': 'score a quantization scheme by computing mixed weight and activation quantization loss across all quantizable layers', 'choose_bits_per_layer_with_path': 'solve a DP knapsack problem to pick the best per-layer quantization scheme within a total bit budget', 'cal_imatrix': 'compute the activation importance matrix for a model by accumulating squared activation norms across a calibration dataset', 'model_forward_low_gpu': 'run a block-by-block forward and backward pass with gradient checkpointing to score quantization under low GPU memory'}
```

## File: intel_auto-round/auto_round/auto_scheme/gen_auto_scheme.py

Prompts

```
['generate an optimal per-layer quantization config for a model using delta loss scoring and DP bit-budget optimization', 'score a quantization scheme by computing mixed weight and activation quantization loss across all quantizable layers', 'solve a DP knapsack problem to pick the best per-layer quantization scheme within a total bit budget', 'compute the activation importance matrix for a model by accumulating squared activation norms across a calibration dataset', 'run a block-by-block forward and backward pass with gradient checkpointing to score quantization under low GPU memory', 'create an AutoScheme dataclass with avg_bits target and quantization options for model layer schemes', 'build a GenScheme instance with an AutoScheme config, model, quant layer names, and tokenizer', 'get the layer configuration dictionary by calling get_layer_config on a GenScheme instance', 'compute the minimum and maximum average bitwidths across candidate quantization options for a model', 'apply GGUF quantization type fallback for layers with incompatible input feature alignment', 'use the register_scheme_methods decorator to register a mixed precision algorithm class into the AUTO_SCHEME_METHODS registry', 'use the register_scheme_methods decorator with a list of names to register an algorithm under multiple keys', 'access the AUTO_SCHEME_METHODS dictionary to retrieve a registered mixed precision algorithm class by its name', 'review the register_scheme_methods decorator to understand how it maps algorithm classes to string keys in the registry', 'summarize the AUTO_SCHEME_METHODS dictionary registry that stores mixed precision algorithm classes keyed by their scheme names', 'apply a quantization scheme to specified layers of a PyTorch model using preset names or custom dictionaries', 'remove all quantization scheme attributes from every module in a PyTorch model', 'compute the average and total bit usage for a quantization scheme across specified model layers', 'compute the total and average bitwidth for a single quantized layer including scale and zero-point overhead', 'parse and match shared layer groups in a model using regex patterns or substring matching']
```

Usage

```
{'create_autoscheme_dataclass': 'create an AutoScheme dataclass with avg_bits target and quantization options for model layer schemes', 'build_genscheme_instance': 'build a GenScheme instance with an AutoScheme config, model, quant layer names, and tokenizer', 'get_layer_config': 'get the layer configuration dictionary by calling get_layer_config on a GenScheme instance', 'compute_avg_bit_range': 'compute the minimum and maximum average bitwidths across candidate quantization options for a model', 'apply_gguf_fallback': 'apply GGUF quantization type fallback for layers with incompatible input feature alignment'}
```

## File: intel_auto-round/auto_round/auto_scheme/register.py

Prompts

```
['generate an optimal per-layer quantization config for a model using delta loss scoring and DP bit-budget optimization', 'score a quantization scheme by computing mixed weight and activation quantization loss across all quantizable layers', 'solve a DP knapsack problem to pick the best per-layer quantization scheme within a total bit budget', 'compute the activation importance matrix for a model by accumulating squared activation norms across a calibration dataset', 'run a block-by-block forward and backward pass with gradient checkpointing to score quantization under low GPU memory', 'create an AutoScheme dataclass with avg_bits target and quantization options for model layer schemes', 'build a GenScheme instance with an AutoScheme config, model, quant layer names, and tokenizer', 'get the layer configuration dictionary by calling get_layer_config on a GenScheme instance', 'compute the minimum and maximum average bitwidths across candidate quantization options for a model', 'apply GGUF quantization type fallback for layers with incompatible input feature alignment', 'use the register_scheme_methods decorator to register a mixed precision algorithm class into the AUTO_SCHEME_METHODS registry', 'use the register_scheme_methods decorator with a list of names to register an algorithm under multiple keys', 'access the AUTO_SCHEME_METHODS dictionary to retrieve a registered mixed precision algorithm class by its name', 'review the register_scheme_methods decorator to understand how it maps algorithm classes to string keys in the registry', 'summarize the AUTO_SCHEME_METHODS dictionary registry that stores mixed precision algorithm classes keyed by their scheme names', 'apply a quantization scheme to specified layers of a PyTorch model using preset names or custom dictionaries', 'remove all quantization scheme attributes from every module in a PyTorch model', 'compute the average and total bit usage for a quantization scheme across specified model layers', 'compute the total and average bitwidth for a single quantized layer including scale and zero-point overhead', 'parse and match shared layer groups in a model using regex patterns or substring matching']
```

Usage

```
{'register_mixed_precision_algorithm': 'use the register_scheme_methods decorator to register a mixed precision algorithm class into the AUTO_SCHEME_METHODS registry', 'register_algorithm_with_multiple_names': 'use the register_scheme_methods decorator with a list of names to register an algorithm under multiple keys', 'access_registered_schemes': 'access the AUTO_SCHEME_METHODS dictionary to retrieve a registered mixed precision algorithm class by its name', 'review_register_scheme_methods': 'review the register_scheme_methods decorator to understand how it maps algorithm classes to string keys in the registry', 'summarize_auto_scheme_methods_registry': 'summarize the AUTO_SCHEME_METHODS dictionary registry that stores mixed precision algorithm classes keyed by their scheme names'}
```

## File: intel_auto-round/auto_round/auto_scheme/utils.py

Prompts

```
['generate an optimal per-layer quantization config for a model using delta loss scoring and DP bit-budget optimization', 'score a quantization scheme by computing mixed weight and activation quantization loss across all quantizable layers', 'solve a DP knapsack problem to pick the best per-layer quantization scheme within a total bit budget', 'compute the activation importance matrix for a model by accumulating squared activation norms across a calibration dataset', 'run a block-by-block forward and backward pass with gradient checkpointing to score quantization under low GPU memory', 'create an AutoScheme dataclass with avg_bits target and quantization options for model layer schemes', 'build a GenScheme instance with an AutoScheme config, model, quant layer names, and tokenizer', 'get the layer configuration dictionary by calling get_layer_config on a GenScheme instance', 'compute the minimum and maximum average bitwidths across candidate quantization options for a model', 'apply GGUF quantization type fallback for layers with incompatible input feature alignment', 'use the register_scheme_methods decorator to register a mixed precision algorithm class into the AUTO_SCHEME_METHODS registry', 'use the register_scheme_methods decorator with a list of names to register an algorithm under multiple keys', 'access the AUTO_SCHEME_METHODS dictionary to retrieve a registered mixed precision algorithm class by its name', 'review the register_scheme_methods decorator to understand how it maps algorithm classes to string keys in the registry', 'summarize the AUTO_SCHEME_METHODS dictionary registry that stores mixed precision algorithm classes keyed by their scheme names', 'apply a quantization scheme to specified layers of a PyTorch model using preset names or custom dictionaries', 'remove all quantization scheme attributes from every module in a PyTorch model', 'compute the average and total bit usage for a quantization scheme across specified model layers', 'compute the total and average bitwidth for a single quantized layer including scale and zero-point overhead', 'parse and match shared layer groups in a model using regex patterns or substring matching']
```

Usage

```
{'apply_quant_scheme': 'apply a quantization scheme to specified layers of a PyTorch model using preset names or custom dictionaries', 'remove_quant_scheme': 'remove all quantization scheme attributes from every module in a PyTorch model', 'compute_avg_bits_for_scheme': 'compute the average and total bit usage for a quantization scheme across specified model layers', 'compute_layer_bits': 'compute the total and average bitwidth for a single quantized layer including scale and zero-point overhead', 'parse_shared_layers': 'parse and match shared layer groups in a model using regex patterns or substring matching'}
```

