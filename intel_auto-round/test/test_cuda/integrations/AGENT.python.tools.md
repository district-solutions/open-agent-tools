# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/test/test_cuda/integrations/test_llmc_integration.py

Prompts

```
['run oneshot quantization on a Llama model using an AutoRoundModifier recipe and save output', 'test oneshot application of quantization recipes including NVFP4 and MXFP4 schemes on a model', 'test oneshot quantization across multiple GPU device IDs using AutoRoundModifier', 'test round-to-nearest oneshot quantization with W8A8 dynamic and static recipes', 'review the AutoRoundModifier recipe configurations for 4-bit group and 8-bit channel quantization', 'run AutoRound W4A16 quantization on a model and test inference with SGLang Engine', 'test mixed precision quantization with layer config for self_attn, lm_head, and mlp layers', 'run SGLang Engine inference on a quantized model path with temperature and top_p sampling params', 'test AWQ format quantization by converting auto_round format to auto_awq and running SGLang inference', 'verify quantization config extra_config only saves attributes differing from default Scheme values', 'test AutoRound quantized model inference with vLLM LLM and SamplingParams for text generation', 'test mixed precision AutoRound quantization with layer config and save quantized model in auto_round format', 'test mixed precision quantization with LLMCompressor format using NVFP4 scheme and layer-wise bit configuration', 'test vLLM evaluation backend with custom args like tensor_parallel_size and gpu_memory_utilization via CLI', 'test AutoRound AWQ format quantization and vLLM inference with W4A16 scheme and sampling parameters']
```

Usage

```
{'run_oneshot_quantization': 'run oneshot quantization on a Llama model using an AutoRoundModifier recipe and save output', 'test_oneshot_application': 'test oneshot application of quantization recipes including NVFP4 and MXFP4 schemes on a model', 'test_oneshot_with_device_ids': 'test oneshot quantization across multiple GPU device IDs using AutoRoundModifier', 'test_rtn_oneshot': 'test round-to-nearest oneshot quantization with W8A8 dynamic and static recipes', 'review_autoround_modifier_recipes': 'review the AutoRoundModifier recipe configurations for 4-bit group and 8-bit channel quantization'}
```

## File: intel_auto-round/test/test_cuda/integrations/test_sglang.py

Prompts

```
['run oneshot quantization on a Llama model using an AutoRoundModifier recipe and save output', 'test oneshot application of quantization recipes including NVFP4 and MXFP4 schemes on a model', 'test oneshot quantization across multiple GPU device IDs using AutoRoundModifier', 'test round-to-nearest oneshot quantization with W8A8 dynamic and static recipes', 'review the AutoRoundModifier recipe configurations for 4-bit group and 8-bit channel quantization', 'run AutoRound W4A16 quantization on a model and test inference with SGLang Engine', 'test mixed precision quantization with layer config for self_attn, lm_head, and mlp layers', 'run SGLang Engine inference on a quantized model path with temperature and top_p sampling params', 'test AWQ format quantization by converting auto_round format to auto_awq and running SGLang inference', 'verify quantization config extra_config only saves attributes differing from default Scheme values', 'test AutoRound quantized model inference with vLLM LLM and SamplingParams for text generation', 'test mixed precision AutoRound quantization with layer config and save quantized model in auto_round format', 'test mixed precision quantization with LLMCompressor format using NVFP4 scheme and layer-wise bit configuration', 'test vLLM evaluation backend with custom args like tensor_parallel_size and gpu_memory_utilization via CLI', 'test AutoRound AWQ format quantization and vLLM inference with W4A16 scheme and sampling parameters']
```

Usage

```
{'run_autoround_quantization_sglang': 'run AutoRound W4A16 quantization on a model and test inference with SGLang Engine', 'test_mixed_precision_quantization': 'test mixed precision quantization with layer config for self_attn, lm_head, and mlp layers', 'run_sglang_inference_on_quantized_model': 'run SGLang Engine inference on a quantized model path with temperature and top_p sampling params', 'test_awq_format_quantization': 'test AWQ format quantization by converting auto_round format to auto_awq and running SGLang inference', 'verify_quantization_config_extra_attrs': 'verify quantization config extra_config only saves attributes differing from default Scheme values'}
```

## File: intel_auto-round/test/test_cuda/integrations/test_vllm.py

Prompts

```
['run oneshot quantization on a Llama model using an AutoRoundModifier recipe and save output', 'test oneshot application of quantization recipes including NVFP4 and MXFP4 schemes on a model', 'test oneshot quantization across multiple GPU device IDs using AutoRoundModifier', 'test round-to-nearest oneshot quantization with W8A8 dynamic and static recipes', 'review the AutoRoundModifier recipe configurations for 4-bit group and 8-bit channel quantization', 'run AutoRound W4A16 quantization on a model and test inference with SGLang Engine', 'test mixed precision quantization with layer config for self_attn, lm_head, and mlp layers', 'run SGLang Engine inference on a quantized model path with temperature and top_p sampling params', 'test AWQ format quantization by converting auto_round format to auto_awq and running SGLang inference', 'verify quantization config extra_config only saves attributes differing from default Scheme values', 'test AutoRound quantized model inference with vLLM LLM and SamplingParams for text generation', 'test mixed precision AutoRound quantization with layer config and save quantized model in auto_round format', 'test mixed precision quantization with LLMCompressor format using NVFP4 scheme and layer-wise bit configuration', 'test vLLM evaluation backend with custom args like tensor_parallel_size and gpu_memory_utilization via CLI', 'test AutoRound AWQ format quantization and vLLM inference with W4A16 scheme and sampling parameters']
```

Usage

```
{'test_auto_round_inference': 'test AutoRound quantized model inference with vLLM LLM and SamplingParams for text generation', 'test_mixed_autoround_format': 'test mixed precision AutoRound quantization with layer config and save quantized model in auto_round format', 'test_mixed_llmcompressor_format': 'test mixed precision quantization with LLMCompressor format using NVFP4 scheme and layer-wise bit configuration', 'test_vllm_evaluation_backend': 'test vLLM evaluation backend with custom args like tensor_parallel_size and gpu_memory_utilization via CLI', 'test_auto_round_awq_format': 'test AutoRound AWQ format quantization and vLLM inference with W4A16 scheme and sampling parameters'}
```

