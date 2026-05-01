# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/kernels/test_kernels.py

Prompts

```
['run a kernelized Llama model forward pass and verify generated output matches expected text', 'test the kernelize function by comparing forward methods between kernelized and non kernelized models', 'test setting use_kernels to True on a model and verify forward methods differ from the original', 'test KernelConfig with a custom kernel mapping for RMSNorm and verify model generation works', 'test lazy_load_kernel to verify it caches loaded kernel modules and returns the same object on repeated calls']
```

Usage

```
{'test_kernelized_model_forward': 'run a kernelized Llama model forward pass and verify generated output matches expected text', 'test_kernelize_function': 'test the kernelize function by comparing forward methods between kernelized and non kernelized models', 'test_use_kernels_setter': 'test setting use_kernels to True on a model and verify forward methods differ from the original', 'test_kernel_config_mapping': 'test KernelConfig with a custom kernel mapping for RMSNorm and verify model generation works', 'test_lazy_load_kernel': 'test lazy_load_kernel to verify it caches loaded kernel modules and returns the same object on repeated calls'}
```

