# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/quantization/bnb/test_4bit.py

Prompts

```
['run the bnb 4-bit quantization test suite for transformers models using pytest', 'test that 4-bit quantized models achieve expected memory reduction compared to fp16', 'test BitsAndBytesConfig serialization and deserialization for 4-bit quantization settings', 'test saving and loading a 4-bit quantized model with nf4 or fp4 quant types', 'test text generation pipeline inference using a 4-bit quantized model', 'test 8-bit quantization of causal language models using BitsAndBytesConfig with load_in_8bit', 'test saving and loading 8-bit quantized models with quantization_config preserved', 'test loading quantized models across multiple GPUs with custom device_map assignments', 'test loading quantized models with CPU and disk offload using llm_int8_enable_fp32_cpu_offload', 'test training quantized models with LoRA adapters on frozen INT8 parameters']
```

Usage

```
{'run_4bit_quantization_tests': 'run the bnb 4-bit quantization test suite for transformers models using pytest', 'test_quantization_memory_footprint': 'test that 4-bit quantized models achieve expected memory reduction compared to fp16', 'test_bitsandbytes_config': 'test BitsAndBytesConfig serialization and deserialization for 4-bit quantization settings', 'test_4bit_model_serialization': 'test saving and loading a 4-bit quantized model with nf4 or fp4 quant types', 'test_4bit_pipeline_inference': 'test text generation pipeline inference using a 4-bit quantized model'}
```

## File: huggingface_transformers/tests/quantization/bnb/test_mixed_int8.py

Prompts

```
['run the bnb 4-bit quantization test suite for transformers models using pytest', 'test that 4-bit quantized models achieve expected memory reduction compared to fp16', 'test BitsAndBytesConfig serialization and deserialization for 4-bit quantization settings', 'test saving and loading a 4-bit quantized model with nf4 or fp4 quant types', 'test text generation pipeline inference using a 4-bit quantized model', 'test 8-bit quantization of causal language models using BitsAndBytesConfig with load_in_8bit', 'test saving and loading 8-bit quantized models with quantization_config preserved', 'test loading quantized models across multiple GPUs with custom device_map assignments', 'test loading quantized models with CPU and disk offload using llm_int8_enable_fp32_cpu_offload', 'test training quantized models with LoRA adapters on frozen INT8 parameters']
```

Usage

```
{'test_mixed_int8_quantization': 'test 8-bit quantization of causal language models using BitsAndBytesConfig with load_in_8bit', 'test_model_serialization': 'test saving and loading 8-bit quantized models with quantization_config preserved', 'test_multi_gpu_device_map': 'test loading quantized models across multiple GPUs with custom device_map assignments', 'test_cpu_gpu_offload': 'test loading quantized models with CPU and disk offload using llm_int8_enable_fp32_cpu_offload', 'test_lora_training': 'test training quantized models with LoRA adapters on frozen INT8 parameters'}
```

