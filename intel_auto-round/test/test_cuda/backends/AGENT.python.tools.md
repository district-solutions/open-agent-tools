# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/test/test_cuda/backends/test_exllamav2_backend.py

Prompts

```
['run AutoRound to quantize a model with 4-bit asymmetric quantization and save in gptqmodel format', 'run AutoRound quantization with configurable group sizes ranging from 32 to 1024 for symmetric 4-bit models', 'run AutoRound to quantize a model in auto_awq format and load with gptqmodel:awq_exllamav2 backend', 'run inference on a quantized model using the gptqmodel:exllamav2 backend with float16 dtype', 'run inference on a quantized model using the gptqmodel:exllamav2 backend with bfloat16 dtype', 'run AutoRound 4-bit symmetric quantization with marlin backend on a causal LM model', 'test AutoRound marlin backend quantization across multiple group sizes like 32, 64, and 128', 'test AWQ quantization with gptqmodel awq_marlin backend using AutoRound and evaluate accuracy', 'quantize a model with AutoRound and save it in auto_gptq format for marlin backend loading', 'evaluate the accuracy of a marlin-quantized model using evaluate_accuracy with a threshold', 'run AutoRound 4-bit asymmetric quantization on a model with group size 128 and save in gptqmodel format', 'run AutoRound 4-bit symmetric quantization on a model and save in auto_round format for torch backend', 'run AutoRound 3-bit asymmetric quantization on a model and save in gptqmodel format for inference', 'test the AutoRound quantize_and_save method with a specified output directory and format string', 'test the AutoRound save_quantized method with inplace false and auto_round format for model export', 'test AutoRound 2-bit asymmetric quantization with tritonv2 backend on a causal language model', 'test AutoRound 4-bit symmetric quantization with tritonv2 backend and evaluate accuracy on float16 and bfloat16', 'create an AutoRoundConfig with tritonv2 backend to load a quantized model from a saved path', 'review the TestAutoRoundTritonBackend test class that validates quantization accuracy across multiple bit widths and symmetry settings']
```

Usage

```
{'run_autoround_quantize_and_save': 'run AutoRound to quantize a model with 4-bit asymmetric quantization and save in gptqmodel format', 'run_autoround_with_group_size': 'run AutoRound quantization with configurable group sizes ranging from 32 to 1024 for symmetric 4-bit models', 'run_autoround_awq_quantization': 'run AutoRound to quantize a model in auto_awq format and load with gptqmodel:awq_exllamav2 backend', 'run_exllamav2_inference_float16': 'run inference on a quantized model using the gptqmodel:exllamav2 backend with float16 dtype', 'run_exllamav2_inference_bfloat16': 'run inference on a quantized model using the gptqmodel:exllamav2 backend with bfloat16 dtype'}
```

## File: intel_auto-round/test/test_cuda/backends/test_marlin_backend.py

Prompts

```
['run AutoRound to quantize a model with 4-bit asymmetric quantization and save in gptqmodel format', 'run AutoRound quantization with configurable group sizes ranging from 32 to 1024 for symmetric 4-bit models', 'run AutoRound to quantize a model in auto_awq format and load with gptqmodel:awq_exllamav2 backend', 'run inference on a quantized model using the gptqmodel:exllamav2 backend with float16 dtype', 'run inference on a quantized model using the gptqmodel:exllamav2 backend with bfloat16 dtype', 'run AutoRound 4-bit symmetric quantization with marlin backend on a causal LM model', 'test AutoRound marlin backend quantization across multiple group sizes like 32, 64, and 128', 'test AWQ quantization with gptqmodel awq_marlin backend using AutoRound and evaluate accuracy', 'quantize a model with AutoRound and save it in auto_gptq format for marlin backend loading', 'evaluate the accuracy of a marlin-quantized model using evaluate_accuracy with a threshold', 'run AutoRound 4-bit asymmetric quantization on a model with group size 128 and save in gptqmodel format', 'run AutoRound 4-bit symmetric quantization on a model and save in auto_round format for torch backend', 'run AutoRound 3-bit asymmetric quantization on a model and save in gptqmodel format for inference', 'test the AutoRound quantize_and_save method with a specified output directory and format string', 'test the AutoRound save_quantized method with inplace false and auto_round format for model export', 'test AutoRound 2-bit asymmetric quantization with tritonv2 backend on a causal language model', 'test AutoRound 4-bit symmetric quantization with tritonv2 backend and evaluate accuracy on float16 and bfloat16', 'create an AutoRoundConfig with tritonv2 backend to load a quantized model from a saved path', 'review the TestAutoRoundTritonBackend test class that validates quantization accuracy across multiple bit widths and symmetry settings']
```

Usage

```
{'run_autoround_marlin_4bit_quantization': 'run AutoRound 4-bit symmetric quantization with marlin backend on a causal LM model', 'test_autoround_marlin_group_sizes': 'test AutoRound marlin backend quantization across multiple group sizes like 32, 64, and 128', 'test_gptqmodel_awq_marlin_backend': 'test AWQ quantization with gptqmodel awq_marlin backend using AutoRound and evaluate accuracy', 'quantize_and_save_auto_gptq_format': 'quantize a model with AutoRound and save it in auto_gptq format for marlin backend loading', 'evaluate_quantized_model_accuracy': 'evaluate the accuracy of a marlin-quantized model using evaluate_accuracy with a threshold'}
```

## File: intel_auto-round/test/test_cuda/backends/test_torch_backend.py

Prompts

```
['run AutoRound to quantize a model with 4-bit asymmetric quantization and save in gptqmodel format', 'run AutoRound quantization with configurable group sizes ranging from 32 to 1024 for symmetric 4-bit models', 'run AutoRound to quantize a model in auto_awq format and load with gptqmodel:awq_exllamav2 backend', 'run inference on a quantized model using the gptqmodel:exllamav2 backend with float16 dtype', 'run inference on a quantized model using the gptqmodel:exllamav2 backend with bfloat16 dtype', 'run AutoRound 4-bit symmetric quantization with marlin backend on a causal LM model', 'test AutoRound marlin backend quantization across multiple group sizes like 32, 64, and 128', 'test AWQ quantization with gptqmodel awq_marlin backend using AutoRound and evaluate accuracy', 'quantize a model with AutoRound and save it in auto_gptq format for marlin backend loading', 'evaluate the accuracy of a marlin-quantized model using evaluate_accuracy with a threshold', 'run AutoRound 4-bit asymmetric quantization on a model with group size 128 and save in gptqmodel format', 'run AutoRound 4-bit symmetric quantization on a model and save in auto_round format for torch backend', 'run AutoRound 3-bit asymmetric quantization on a model and save in gptqmodel format for inference', 'test the AutoRound quantize_and_save method with a specified output directory and format string', 'test the AutoRound save_quantized method with inplace false and auto_round format for model export', 'test AutoRound 2-bit asymmetric quantization with tritonv2 backend on a causal language model', 'test AutoRound 4-bit symmetric quantization with tritonv2 backend and evaluate accuracy on float16 and bfloat16', 'create an AutoRoundConfig with tritonv2 backend to load a quantized model from a saved path', 'review the TestAutoRoundTritonBackend test class that validates quantization accuracy across multiple bit widths and symmetry settings']
```

Usage

```
{'run_autoround_4bit_asym_quantization': 'run AutoRound 4-bit asymmetric quantization on a model with group size 128 and save in gptqmodel format', 'run_autoround_4bit_sym_quantization': 'run AutoRound 4-bit symmetric quantization on a model and save in auto_round format for torch backend', 'run_autoround_3bit_quantization': 'run AutoRound 3-bit asymmetric quantization on a model and save in gptqmodel format for inference', 'test_autoround_quantize_and_save': 'test the AutoRound quantize_and_save method with a specified output directory and format string', 'test_autoround_save_quantized': 'test the AutoRound save_quantized method with inplace false and auto_round format for model export'}
```

## File: intel_auto-round/test/test_cuda/backends/test_triton_backend.py

Prompts

```
['run AutoRound to quantize a model with 4-bit asymmetric quantization and save in gptqmodel format', 'run AutoRound quantization with configurable group sizes ranging from 32 to 1024 for symmetric 4-bit models', 'run AutoRound to quantize a model in auto_awq format and load with gptqmodel:awq_exllamav2 backend', 'run inference on a quantized model using the gptqmodel:exllamav2 backend with float16 dtype', 'run inference on a quantized model using the gptqmodel:exllamav2 backend with bfloat16 dtype', 'run AutoRound 4-bit symmetric quantization with marlin backend on a causal LM model', 'test AutoRound marlin backend quantization across multiple group sizes like 32, 64, and 128', 'test AWQ quantization with gptqmodel awq_marlin backend using AutoRound and evaluate accuracy', 'quantize a model with AutoRound and save it in auto_gptq format for marlin backend loading', 'evaluate the accuracy of a marlin-quantized model using evaluate_accuracy with a threshold', 'run AutoRound 4-bit asymmetric quantization on a model with group size 128 and save in gptqmodel format', 'run AutoRound 4-bit symmetric quantization on a model and save in auto_round format for torch backend', 'run AutoRound 3-bit asymmetric quantization on a model and save in gptqmodel format for inference', 'test the AutoRound quantize_and_save method with a specified output directory and format string', 'test the AutoRound save_quantized method with inplace false and auto_round format for model export', 'test AutoRound 2-bit asymmetric quantization with tritonv2 backend on a causal language model', 'test AutoRound 4-bit symmetric quantization with tritonv2 backend and evaluate accuracy on float16 and bfloat16', 'create an AutoRoundConfig with tritonv2 backend to load a quantized model from a saved path', 'review the TestAutoRoundTritonBackend test class that validates quantization accuracy across multiple bit widths and symmetry settings']
```

Usage

```
{'run_autoround_quantize_and_save': 'run AutoRound to quantize a model with specified bits, group_size, and symmetry then save it', 'test_autoround_tritonv2_2bits_asym': 'test AutoRound 2-bit asymmetric quantization with tritonv2 backend on a causal language model', 'test_autoround_tritonv2_4bits_sym': 'test AutoRound 4-bit symmetric quantization with tritonv2 backend and evaluate accuracy on float16 and bfloat16', 'create_autoround_config_tritonv2': 'create an AutoRoundConfig with tritonv2 backend to load a quantized model from a saved path', 'review_test_autoround_triton_backend': 'review the TestAutoRoundTritonBackend test class that validates quantization accuracy across multiple bit widths and symmetry settings'}
```

