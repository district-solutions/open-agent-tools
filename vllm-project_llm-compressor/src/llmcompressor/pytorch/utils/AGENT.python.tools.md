# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/src/llmcompressor/pytorch/utils/helpers.py

Prompts

```
['move a tensor or nested collection of tensors to a specified device like cuda or cpu', 'convert a tensor or nested collection of tensors to full or half precision', 'run a forward pass through a pytorch module with tensor data handling features and labels', 'calculate the sparsity of a tensor as the fraction of zero values optionally over specified dimensions', 'find all quantized layers in a pytorch module by checking for quantization_scheme attributes', 'create a ModuleSparsificationInfo instance from a torch module to analyze its sparsity', 'get the total number of trainable parameters from a ModuleSparsificationInfo object', 'get the total number of sparse zero-valued parameters from a ModuleSparsificationInfo object', 'get the percentage of sparsified parameters from a ModuleSparsificationInfo object', 'get the number of parameters across quantized layers from a ModuleSparsificationInfo object']
```

Usage

```
{'build_move_tensors_to_device': 'move a tensor or nested collection of tensors to a specified device like cuda or cpu', 'create_convert_tensor_precision': 'convert a tensor or nested collection of tensors to full or half precision', 'run_forward_pass_module': 'run a forward pass through a pytorch module with tensor data handling features and labels', 'test_tensor_sparsity': 'calculate the sparsity of a tensor as the fraction of zero values optionally over specified dimensions', 'review_quantized_layers': 'find all quantized layers in a pytorch module by checking for quantization_scheme attributes'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/pytorch/utils/sparsification.py

Prompts

```
['move a tensor or nested collection of tensors to a specified device like cuda or cpu', 'convert a tensor or nested collection of tensors to full or half precision', 'run a forward pass through a pytorch module with tensor data handling features and labels', 'calculate the sparsity of a tensor as the fraction of zero values optionally over specified dimensions', 'find all quantized layers in a pytorch module by checking for quantization_scheme attributes', 'create a ModuleSparsificationInfo instance from a torch module to analyze its sparsity', 'get the total number of trainable parameters from a ModuleSparsificationInfo object', 'get the total number of sparse zero-valued parameters from a ModuleSparsificationInfo object', 'get the percentage of sparsified parameters from a ModuleSparsificationInfo object', 'get the number of parameters across quantized layers from a ModuleSparsificationInfo object']
```

Usage

```
{'create_ModuleSparsificationInfo': 'create a ModuleSparsificationInfo instance from a torch module to analyze its sparsity', 'get_params_total': 'get the total number of trainable parameters from a ModuleSparsificationInfo object', 'get_params_sparse': 'get the total number of sparse zero-valued parameters from a ModuleSparsificationInfo object', 'get_params_sparse_percent': 'get the percentage of sparsified parameters from a ModuleSparsificationInfo object', 'get_params_quantized': 'get the number of parameters across quantized layers from a ModuleSparsificationInfo object'}
```

