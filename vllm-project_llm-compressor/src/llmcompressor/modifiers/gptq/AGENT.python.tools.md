# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/src/llmcompressor/modifiers/gptq/base.py

Prompts

```
['build a GPTQModifier to quantize model weights using hessian-based calibration and group-wise quantization', 'create a GPTQModifier with configurable block_size, dampening_frac, actorder, and quantization config_groups', 'test the calibrate_module hook to accumulate hessian matrices from model input activations', 'refactor compress_modules to distribute hessian reduction and quantization across multiple GPU ranks', 'review the GPTQModifier lifecycle hooks on_initialize, on_start, on_event, on_end, and on_finalize', 'create an empty hessian tensor for a given PyTorch module with specified device', 'run hessian accumulation from input tensors on a module, returning updated hessian and sample count', 'quantize a module weight using the GPTQ algorithm with a preaccumulated hessian and blockwise updates', 'build permuted weight and hessian tensors ordered by greatest output activations', 'test the quantize_weight function with channel, group, tensor, and block quantization strategies']
```

Usage

```
{'build_gptq_quantize_model': 'build a GPTQModifier to quantize model weights using hessian-based calibration and group-wise quantization', 'create_gptq_modifier_config': 'create a GPTQModifier with configurable block_size, dampening_frac, actorder, and quantization config_groups', 'test_gptq_calibrate_module': 'test the calibrate_module hook to accumulate hessian matrices from model input activations', 'refactor_gptq_compress_distributed': 'refactor compress_modules to distribute hessian reduction and quantization across multiple GPU ranks', 'review_gptq_lifecycle_hooks': 'review the GPTQModifier lifecycle hooks on_initialize, on_start, on_event, on_end, and on_finalize'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/modifiers/gptq/gptq_quantize.py

Prompts

```
['build a GPTQModifier to quantize model weights using hessian-based calibration and group-wise quantization', 'create a GPTQModifier with configurable block_size, dampening_frac, actorder, and quantization config_groups', 'test the calibrate_module hook to accumulate hessian matrices from model input activations', 'refactor compress_modules to distribute hessian reduction and quantization across multiple GPU ranks', 'review the GPTQModifier lifecycle hooks on_initialize, on_start, on_event, on_end, and on_finalize', 'create an empty hessian tensor for a given PyTorch module with specified device', 'run hessian accumulation from input tensors on a module, returning updated hessian and sample count', 'quantize a module weight using the GPTQ algorithm with a preaccumulated hessian and blockwise updates', 'build permuted weight and hessian tensors ordered by greatest output activations', 'test the quantize_weight function with channel, group, tensor, and block quantization strategies']
```

Usage

```
{'create_make_empty_hessian': 'create an empty hessian tensor for a given PyTorch module with specified device', 'run_accumulate_hessian': 'run hessian accumulation from input tensors on a module, returning updated hessian and sample count', 'quantize_weight_gptq': 'quantize a module weight using the GPTQ algorithm with a preaccumulated hessian and blockwise updates', 'build_activation_ordering': 'build permuted weight and hessian tensors ordered by greatest output activations', 'test_quantize_weight_strategies': 'test the quantize_weight function with channel, group, tensor, and block quantization strategies'}
```

