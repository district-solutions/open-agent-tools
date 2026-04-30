# Agent Python Tools

- repo: OpenBMB/VoxCPM
- repo_uri: https://github.com/OpenBMB/VoxCPM

## File: OpenBMB_VoxCPM/src/voxcpm/modules/layers/lora.py

Prompts

```
['create a LoRALinear module wrapping an nn.Linear with rank and alpha parameters', 'apply LoRA injection to all named linear modules matching target submodule names in a PyTorch model', 'reset LoRA A and B matrices to their initial random state', 'enable or disable LoRA contribution in a LoRALinear forward pass', 'retrieve the parent module of a named submodule in a PyTorch module tree', 'create a ScalarQuantizationLayer with in_dim, out_dim, latent_dim, and scale parameters', 'forward a hidden tensor through ScalarQuantizationLayer with quantization applied', 'test ScalarQuantizationLayer in training mode with straight-through quantization gradient', 'test ScalarQuantizationLayer in eval mode with deterministic quantization output', 'configure ScalarQuantizationLayer with custom latent_dim and scale quantization levels']
```

Usage

```
{'create_LoRALinear': 'create a LoRALinear module wrapping an nn.Linear with rank and alpha parameters', 'apply_lora_to_modules': 'apply LoRA injection to all named linear modules matching target submodule names in a PyTorch model', 'reset_LoRA_parameters': 'reset LoRA A and B matrices to their initial random state', 'toggle_LoRA_enabled': 'enable or disable LoRA contribution in a LoRALinear forward pass', 'get_parent_module': 'retrieve the parent module of a named submodule in a PyTorch module tree'}
```

## File: OpenBMB_VoxCPM/src/voxcpm/modules/layers/scalar_quantization_layer.py

Prompts

```
['create a LoRALinear module wrapping an nn.Linear with rank and alpha parameters', 'apply LoRA injection to all named linear modules matching target submodule names in a PyTorch model', 'reset LoRA A and B matrices to their initial random state', 'enable or disable LoRA contribution in a LoRALinear forward pass', 'retrieve the parent module of a named submodule in a PyTorch module tree', 'create a ScalarQuantizationLayer with in_dim, out_dim, latent_dim, and scale parameters', 'forward a hidden tensor through ScalarQuantizationLayer with quantization applied', 'test ScalarQuantizationLayer in training mode with straight-through quantization gradient', 'test ScalarQuantizationLayer in eval mode with deterministic quantization output', 'configure ScalarQuantizationLayer with custom latent_dim and scale quantization levels']
```

Usage

```
{'create_ScalarQuantizationLayer': 'create a ScalarQuantizationLayer with in_dim, out_dim, latent_dim, and scale parameters', 'forward_ScalarQuantizationLayer': 'forward a hidden tensor through ScalarQuantizationLayer with quantization applied', 'train_mode_ScalarQuantizationLayer': 'test ScalarQuantizationLayer in training mode with straight-through quantization gradient', 'eval_mode_ScalarQuantizationLayer': 'test ScalarQuantizationLayer in eval mode with deterministic quantization output', 'configure_ScalarQuantizationLayer': 'configure ScalarQuantizationLayer with custom latent_dim and scale quantization levels'}
```

