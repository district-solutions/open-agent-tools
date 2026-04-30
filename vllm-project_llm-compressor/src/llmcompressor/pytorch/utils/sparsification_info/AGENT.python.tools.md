# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/src/llmcompressor/pytorch/utils/sparsification_info/configs.py

Prompts

```
['create SparsificationSummaries from a PyTorch module to get quantized and pruned operation counts', 'create SparsificationPruning from a PyTorch module to get per-parameter zero-weight counts and percentages', 'create SparsificationQuantization from a PyTorch module to get per-operation quantization status and precision info', 'summarize SparsificationSummaries loggable items to yield operation counts, parameter counts, and pruning percentages', 'filter SparsificationInfo loggable items by percentage-only or non-zero-only criteria', 'get leaf operations from a PyTorch model, skipping Identity and unwrapping QuantWrapper modules', 'test whether a PyTorch operation has a quantization scheme attribute', 'get precision info for a PyTorch operation, returning quantization scheme or weight bit count', 'get leaf operations from a PyTorch model with custom operations to skip', 'get leaf operations from a PyTorch model with custom operations to unwrap', 'create a ModuleSparsificationInfo object from a torch.nn.Module using the from_module factory method', 'get sparsification summary info from a torch module via ModuleSparsificationInfo.from_module', 'get pruning info for weights and masks from a torch module via ModuleSparsificationInfo', 'get quantization info for a torch module via ModuleSparsificationInfo.from_module', 'iterate loggable name-value pairs from ModuleSparsificationInfo for logging or debugging']
```

Usage

```
{'create_SparsificationSummaries_from_module': 'create SparsificationSummaries from a PyTorch module to get quantized and pruned operation counts', 'create_SparsificationPruning_from_module': 'create SparsificationPruning from a PyTorch module to get per-parameter zero-weight counts and percentages', 'create_SparsificationQuantization_from_module': 'create SparsificationQuantization from a PyTorch module to get per-operation quantization status and precision info', 'summarize_SparsificationSummaries_loggable_items': 'summarize SparsificationSummaries loggable items to yield operation counts, parameter counts, and pruning percentages', 'filter_SparsificationInfo_loggable_items': 'filter SparsificationInfo loggable items by percentage-only or non-zero-only criteria'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/pytorch/utils/sparsification_info/helpers.py

Prompts

```
['create SparsificationSummaries from a PyTorch module to get quantized and pruned operation counts', 'create SparsificationPruning from a PyTorch module to get per-parameter zero-weight counts and percentages', 'create SparsificationQuantization from a PyTorch module to get per-operation quantization status and precision info', 'summarize SparsificationSummaries loggable items to yield operation counts, parameter counts, and pruning percentages', 'filter SparsificationInfo loggable items by percentage-only or non-zero-only criteria', 'get leaf operations from a PyTorch model, skipping Identity and unwrapping QuantWrapper modules', 'test whether a PyTorch operation has a quantization scheme attribute', 'get precision info for a PyTorch operation, returning quantization scheme or weight bit count', 'get leaf operations from a PyTorch model with custom operations to skip', 'get leaf operations from a PyTorch model with custom operations to unwrap', 'create a ModuleSparsificationInfo object from a torch.nn.Module using the from_module factory method', 'get sparsification summary info from a torch module via ModuleSparsificationInfo.from_module', 'get pruning info for weights and masks from a torch module via ModuleSparsificationInfo', 'get quantization info for a torch module via ModuleSparsificationInfo.from_module', 'iterate loggable name-value pairs from ModuleSparsificationInfo for logging or debugging']
```

Usage

```
{'get_leaf_operations': 'get leaf operations from a PyTorch model, skipping Identity and unwrapping QuantWrapper modules', 'is_quantized': 'test whether a PyTorch operation has a quantization scheme attribute', 'get_precision_information': 'get precision info for a PyTorch operation, returning quantization scheme or weight bit count', 'get_leaf_operations_skip': 'get leaf operations from a PyTorch model with custom operations to skip', 'get_leaf_operations_unwrap': 'get leaf operations from a PyTorch model with custom operations to unwrap'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/pytorch/utils/sparsification_info/module_sparsification_info.py

Prompts

```
['create SparsificationSummaries from a PyTorch module to get quantized and pruned operation counts', 'create SparsificationPruning from a PyTorch module to get per-parameter zero-weight counts and percentages', 'create SparsificationQuantization from a PyTorch module to get per-operation quantization status and precision info', 'summarize SparsificationSummaries loggable items to yield operation counts, parameter counts, and pruning percentages', 'filter SparsificationInfo loggable items by percentage-only or non-zero-only criteria', 'get leaf operations from a PyTorch model, skipping Identity and unwrapping QuantWrapper modules', 'test whether a PyTorch operation has a quantization scheme attribute', 'get precision info for a PyTorch operation, returning quantization scheme or weight bit count', 'get leaf operations from a PyTorch model with custom operations to skip', 'get leaf operations from a PyTorch model with custom operations to unwrap', 'create a ModuleSparsificationInfo object from a torch.nn.Module using the from_module factory method', 'get sparsification summary info from a torch module via ModuleSparsificationInfo.from_module', 'get pruning info for weights and masks from a torch module via ModuleSparsificationInfo', 'get quantization info for a torch module via ModuleSparsificationInfo.from_module', 'iterate loggable name-value pairs from ModuleSparsificationInfo for logging or debugging']
```

Usage

```
{'create_module_sparsification_info': 'create a ModuleSparsificationInfo object from a torch.nn.Module using the from_module factory method', 'get_summary_info': 'get sparsification summary info from a torch module via ModuleSparsificationInfo.from_module', 'get_pruning_info': 'get pruning info for weights and masks from a torch module via ModuleSparsificationInfo', 'get_quantization_info': 'get quantization info for a torch module via ModuleSparsificationInfo.from_module', 'iterate_loggable_items': 'iterate loggable name-value pairs from ModuleSparsificationInfo for logging or debugging'}
```

