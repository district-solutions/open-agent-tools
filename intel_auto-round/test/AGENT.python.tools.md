# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/test/envs.py

Prompts

```
['check if a package satisfies a version requirement using require_package_version', 'skip a unittest test method unless a package version requirement is met', 'check if a PyTorch model contains a specific module type using has_module', 'skip a unittest test method unless multiple CUDA GPUs are available', 'check if a quantization library like gguf, auto_gptq, or awq is installed', 'create a pytest fixture that saves a tiny version of a HuggingFace model for fast testing', 'create a pytest fixture that builds a tiny FP8 quantized Qwen model with mocked CUDA capability', 'create a pytest fixture that saves a tiny diffusion model like Flux with reduced layers and config overrides', 'create a pytest fixture that saves a tiny multimodal LLM like Qwen-VL with reduced layers and tokenizer', 'create a pytest fixture that saves a tiny MoE model with FP8 experts and reduced hidden layers', 'generate text from a prompt using a loaded LLM model and tokenizer', 'evaluate model accuracy on a benchmark task like lambada_openai with a threshold check', 'create a tiny sliced model with reduced layers for faster testing', 'compare outputs of two models using cosine similarity or top-k agreement metrics', 'save a tiny sliced model with reduced layers to a local directory for testing']
```

Usage

```
{'check_package_version': 'check if a package satisfies a version requirement using require_package_version', 'skip_test_unless_version': 'skip a unittest test method unless a package version requirement is met', 'check_module_in_model': 'check if a PyTorch model contains a specific module type using has_module', 'skip_test_unless_multi_gpu': 'skip a unittest test method unless multiple CUDA GPUs are available', 'check_library_availability': 'check if a quantization library like gguf, auto_gptq, or awq is installed'}
```

## File: intel_auto-round/test/fixtures.py

Prompts

```
['check if a package satisfies a version requirement using require_package_version', 'skip a unittest test method unless a package version requirement is met', 'check if a PyTorch model contains a specific module type using has_module', 'skip a unittest test method unless multiple CUDA GPUs are available', 'check if a quantization library like gguf, auto_gptq, or awq is installed', 'create a pytest fixture that saves a tiny version of a HuggingFace model for fast testing', 'create a pytest fixture that builds a tiny FP8 quantized Qwen model with mocked CUDA capability', 'create a pytest fixture that saves a tiny diffusion model like Flux with reduced layers and config overrides', 'create a pytest fixture that saves a tiny multimodal LLM like Qwen-VL with reduced layers and tokenizer', 'create a pytest fixture that saves a tiny MoE model with FP8 experts and reduced hidden layers', 'generate text from a prompt using a loaded LLM model and tokenizer', 'evaluate model accuracy on a benchmark task like lambada_openai with a threshold check', 'create a tiny sliced model with reduced layers for faster testing', 'compare outputs of two models using cosine similarity or top-k agreement metrics', 'save a tiny sliced model with reduced layers to a local directory for testing']
```

Usage

```
{'create_tiny_model_fixture': 'create a pytest fixture that saves a tiny version of a HuggingFace model for fast testing', 'create_fp8_model_fixture': 'create a pytest fixture that builds a tiny FP8 quantized Qwen model with mocked CUDA capability', 'create_diffusion_model_fixture': 'create a pytest fixture that saves a tiny diffusion model like Flux with reduced layers and config overrides', 'create_mllm_model_fixture': 'create a pytest fixture that saves a tiny multimodal LLM like Qwen-VL with reduced layers and tokenizer', 'create_moe_model_fixture': 'create a pytest fixture that saves a tiny MoE model with FP8 experts and reduced hidden layers'}
```

## File: intel_auto-round/test/helpers.py

Prompts

```
['check if a package satisfies a version requirement using require_package_version', 'skip a unittest test method unless a package version requirement is met', 'check if a PyTorch model contains a specific module type using has_module', 'skip a unittest test method unless multiple CUDA GPUs are available', 'check if a quantization library like gguf, auto_gptq, or awq is installed', 'create a pytest fixture that saves a tiny version of a HuggingFace model for fast testing', 'create a pytest fixture that builds a tiny FP8 quantized Qwen model with mocked CUDA capability', 'create a pytest fixture that saves a tiny diffusion model like Flux with reduced layers and config overrides', 'create a pytest fixture that saves a tiny multimodal LLM like Qwen-VL with reduced layers and tokenizer', 'create a pytest fixture that saves a tiny MoE model with FP8 experts and reduced hidden layers', 'generate text from a prompt using a loaded LLM model and tokenizer', 'evaluate model accuracy on a benchmark task like lambada_openai with a threshold check', 'create a tiny sliced model with reduced layers for faster testing', 'compare outputs of two models using cosine similarity or top-k agreement metrics', 'save a tiny sliced model with reduced layers to a local directory for testing']
```

Usage

```
{'generate_prompt': 'generate text from a prompt using a loaded LLM model and tokenizer', 'evaluate_accuracy': 'evaluate model accuracy on a benchmark task like lambada_openai with a threshold check', 'get_tiny_model': 'create a tiny sliced model with reduced layers for faster testing', 'is_model_outputs_similar': 'compare outputs of two models using cosine similarity or top-k agreement metrics', 'save_tiny_model': 'save a tiny sliced model with reduced layers to a local directory for testing'}
```

