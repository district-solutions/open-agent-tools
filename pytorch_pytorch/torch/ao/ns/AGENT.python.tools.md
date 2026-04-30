# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/ao/ns/_numeric_suite.py

Prompts

```
['compare weights between a float model and its quantized counterpart using their state dicts', 'compare output activations between float and quantized models for the same input data', 'compare quantized modules with their floating point shadow modules using a module swap list', 'prepare a float and quantized model by attaching logger modules to track activations', 'traverse a quantized model and collect all logger stats for quantization accuracy debugging', 'extract weights from two models and return a weight comparison result dictionary', 'instrument two models with output loggers to capture intermediate activations for comparison', 'create a shadow model that logs activations from both original and transformed subgraphs', 'prepare a model with multiple quantized shadow copies for n-shadows testing', 'extend logger results with computed comparison metrics like SQNR between two models']
```

Usage

```
{'compare_weights': 'compare weights between a float model and its quantized counterpart using their state dicts', 'compare_model_outputs': 'compare output activations between float and quantized models for the same input data', 'compare_model_stub': 'compare quantized modules with their floating point shadow modules using a module swap list', 'prepare_model_outputs': 'prepare a float and quantized model by attaching logger modules to track activations', 'get_logger_dict': 'traverse a quantized model and collect all logger stats for quantization accuracy debugging'}
```

## File: pytorch_pytorch/torch/ao/ns/_numeric_suite_fx.py

Prompts

```
['compare weights between a float model and its quantized counterpart using their state dicts', 'compare output activations between float and quantized models for the same input data', 'compare quantized modules with their floating point shadow modules using a module swap list', 'prepare a float and quantized model by attaching logger modules to track activations', 'traverse a quantized model and collect all logger stats for quantization accuracy debugging', 'extract weights from two models and return a weight comparison result dictionary', 'instrument two models with output loggers to capture intermediate activations for comparison', 'create a shadow model that logs activations from both original and transformed subgraphs', 'prepare a model with multiple quantized shadow copies for n-shadows testing', 'extend logger results with computed comparison metrics like SQNR between two models']
```

Usage

```
{'extract_weights': 'extract weights from two models and return a weight comparison result dictionary', 'add_loggers': 'instrument two models with output loggers to capture intermediate activations for comparison', 'add_shadow_loggers': 'create a shadow model that logs activations from both original and transformed subgraphs', 'prepare_n_shadows_model': 'prepare a model with multiple quantized shadow copies for n-shadows testing', 'extend_logger_results_with_comparison': 'extend logger results with computed comparison metrics like SQNR between two models'}
```

