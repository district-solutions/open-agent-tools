# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/src/llmcompressor/modifiers/transform/awq/base.py

Prompts

```
['create an AWQModifier instance to smooth model weights and reduce quantization error', 'run AWQ smoothing on a model using calibration data to compute optimal per-channel scales', 'build AWQ mappings from model architecture by inferring smooth and balance layers automatically', 'test AWQ grid search to find best scaling factors that minimize quantization output error', 'review the AWQModifier class for applying activation-weighted quantization smoothing to transformer models', 'build AWQ mappings for hybrid attention models like Qwen3Next and Qwen3.5 with full and linear attention layers', 'get AWQ layer mappings for a PyTorch model by checking dynamic registry, static registry, and default mappings', 'test get_layer_mappings_from_model with a Qwen3NextForCausalLM model to verify correct mapping selection', 'refactor build_hybrid_attention_mappings to support additional hybrid attention architectures beyond Qwen3Next and Qwen3.5', 'review the AWQ_DYNAMIC_MAPPING_REGISTRY to ensure all supported model classes are registered with correct mapping builders']
```

Usage

```
{'create_awq_modifier': 'create an AWQModifier instance to smooth model weights and reduce quantization error', 'run_awq_smoothing': 'run AWQ smoothing on a model using calibration data to compute optimal per-channel scales', 'build_awq_mappings': 'build AWQ mappings from model architecture by inferring smooth and balance layers automatically', 'test_awq_grid_search': 'test AWQ grid search to find best scaling factors that minimize quantization output error', 'review_awq_modifier': 'review the AWQModifier class for applying activation-weighted quantization smoothing to transformer models'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/modifiers/transform/awq/dynamic_mappings.py

Prompts

```
['create an AWQModifier instance to smooth model weights and reduce quantization error', 'run AWQ smoothing on a model using calibration data to compute optimal per-channel scales', 'build AWQ mappings from model architecture by inferring smooth and balance layers automatically', 'test AWQ grid search to find best scaling factors that minimize quantization output error', 'review the AWQModifier class for applying activation-weighted quantization smoothing to transformer models', 'build AWQ mappings for hybrid attention models like Qwen3Next and Qwen3.5 with full and linear attention layers', 'get AWQ layer mappings for a PyTorch model by checking dynamic registry, static registry, and default mappings', 'test get_layer_mappings_from_model with a Qwen3NextForCausalLM model to verify correct mapping selection', 'refactor build_hybrid_attention_mappings to support additional hybrid attention architectures beyond Qwen3Next and Qwen3.5', 'review the AWQ_DYNAMIC_MAPPING_REGISTRY to ensure all supported model classes are registered with correct mapping builders']
```

Usage

```
{'build_hybrid_attention_mappings': 'build AWQ mappings for hybrid attention models like Qwen3Next and Qwen3.5 with full and linear attention layers', 'get_layer_mappings_from_model': 'get AWQ layer mappings for a PyTorch model by checking dynamic registry, static registry, and default mappings', 'test_get_layer_mappings_from_model': 'test get_layer_mappings_from_model with a Qwen3NextForCausalLM model to verify correct mapping selection', 'refactor_build_hybrid_attention_mappings': 'refactor build_hybrid_attention_mappings to support additional hybrid attention architectures beyond Qwen3Next and Qwen3.5', 'review_AWQ_DYNAMIC_MAPPING_REGISTRY': 'review the AWQ_DYNAMIC_MAPPING_REGISTRY to ensure all supported model classes are registered with correct mapping builders'}
```

