# Agent Python Tools

- repo: unslothai/unsloth
- repo_uri: https://github.com/unslothai/unsloth.git

## File: unslothai_unsloth/unsloth/optimizers/q_galore_adamw.py

Prompts

```
['build an AdamW optimizer with 8-bit states, GaLore low-rank gradient projection, and INT8 weight quantization', 'create parameter groups for QGaLoreAdamW8bit by partitioning model weights into GaLore and non-GaLore groups', 'initialize INT8 weight quantization tags on model parameters for memory-efficient training', 'install forward pre-hooks on model modules to dequantize INT8 weights before each forward pass', 'run a single optimization step with GaLore projection, 8-bit Adam update, and optional weight quantization', 'create a GaLoreProjector instance with configurable rank, quantization, and adaptive scheduling parameters', 'run the GaLoreProjector.project method to project a full-rank gradient into a low-rank subspace', 'run the GaLoreProjector.project_back method to project a low-rank gradient back to full rank', 'test the _quantize function to asymmetric min-max quantize a float tensor to uint8 with configurable bit-width', 'test the _quantize_stochastic function to quantize a float tensor using probabilistic stochastic rounding']
```

Usage

```
{'build_optimizer_q_galore_adamw8bit': 'build an AdamW optimizer with 8-bit states, GaLore low-rank gradient projection, and INT8 weight quantization', 'create_param_groups_q_galore': 'create parameter groups for QGaLoreAdamW8bit by partitioning model weights into GaLore and non-GaLore groups', 'init_weight_quantization_q_galore': 'initialize INT8 weight quantization tags on model parameters for memory-efficient training', 'install_weight_quant_hooks': 'install forward pre-hooks on model modules to dequantize INT8 weights before each forward pass', 'run_optimizer_step_q_galore': 'run a single optimization step with GaLore projection, 8-bit Adam update, and optional weight quantization'}
```

## File: unslothai_unsloth/unsloth/optimizers/q_galore_projector.py

Prompts

```
['build an AdamW optimizer with 8-bit states, GaLore low-rank gradient projection, and INT8 weight quantization', 'create parameter groups for QGaLoreAdamW8bit by partitioning model weights into GaLore and non-GaLore groups', 'initialize INT8 weight quantization tags on model parameters for memory-efficient training', 'install forward pre-hooks on model modules to dequantize INT8 weights before each forward pass', 'run a single optimization step with GaLore projection, 8-bit Adam update, and optional weight quantization', 'create a GaLoreProjector instance with configurable rank, quantization, and adaptive scheduling parameters', 'run the GaLoreProjector.project method to project a full-rank gradient into a low-rank subspace', 'run the GaLoreProjector.project_back method to project a low-rank gradient back to full rank', 'test the _quantize function to asymmetric min-max quantize a float tensor to uint8 with configurable bit-width', 'test the _quantize_stochastic function to quantize a float tensor using probabilistic stochastic rounding']
```

Usage

```
{'create_GaLoreProjector': 'create a GaLoreProjector instance with configurable rank, quantization, and adaptive scheduling parameters', 'run_project_gradient': 'run the GaLoreProjector.project method to project a full-rank gradient into a low-rank subspace', 'run_project_back': 'run the GaLoreProjector.project_back method to project a low-rank gradient back to full rank', 'test_quantize_tensor': 'test the _quantize function to asymmetric min-max quantize a float tensor to uint8 with configurable bit-width', 'test_quantize_stochastic': 'test the _quantize_stochastic function to quantize a float tensor using probabilistic stochastic rounding'}
```

