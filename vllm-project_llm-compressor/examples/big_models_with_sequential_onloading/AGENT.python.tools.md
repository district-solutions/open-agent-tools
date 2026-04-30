# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/examples/big_models_with_sequential_onloading/llama3.3_70b.py

Prompts

```
['run llmcompressor oneshot to quantize a large language model with GPTQ and SmoothQuant', 'create a SmoothQuantModifier to make activations easier to quantize before GPTQ', 'create a GPTQModifier to quantize model weights to int8 with static per-channel quantization', 'build a quantization recipe combining SmoothQuant and GPTQ for W8A8 int8 quantization', 'summarize the full quantization pipeline from dataset loading through model compression', 'run W8A8 distributed quantization on a large language model using llmcompressor oneshot with calibration dataset', 'init a distributed process group for multi-GPU quantization with torch.distributed and compressed_tensors', 'load a large causal language model with auto offloading for distributed DDP training', 'partition a HuggingFace dataset by rank for distributed calibration across multiple GPUs', 'generate text from a quantized model after dispatching offloaded layers to GPU memory']
```

Usage

```
{'run_oneshot_quantization': 'run llmcompressor oneshot to quantize a large language model with GPTQ and SmoothQuant', 'create_smoothquant_modifier': 'create a SmoothQuantModifier to make activations easier to quantize before GPTQ', 'create_gptq_modifier': 'create a GPTQModifier to quantize model weights to int8 with static per-channel quantization', 'build_w8a8_quantization_recipe': 'build a quantization recipe combining SmoothQuant and GPTQ for W8A8 int8 quantization', 'summarize_quantization_pipeline': 'summarize the full quantization pipeline from dataset loading through model compression'}
```

## File: vllm-project_llm-compressor/examples/big_models_with_sequential_onloading/llama3_8b_w8a8_distributed.py

Prompts

```
['run llmcompressor oneshot to quantize a large language model with GPTQ and SmoothQuant', 'create a SmoothQuantModifier to make activations easier to quantize before GPTQ', 'create a GPTQModifier to quantize model weights to int8 with static per-channel quantization', 'build a quantization recipe combining SmoothQuant and GPTQ for W8A8 int8 quantization', 'summarize the full quantization pipeline from dataset loading through model compression', 'run W8A8 distributed quantization on a large language model using llmcompressor oneshot with calibration dataset', 'init a distributed process group for multi-GPU quantization with torch.distributed and compressed_tensors', 'load a large causal language model with auto offloading for distributed DDP training', 'partition a HuggingFace dataset by rank for distributed calibration across multiple GPUs', 'generate text from a quantized model after dispatching offloaded layers to GPU memory']
```

Usage

```
{'run_quantize_model_oneshot': 'run W8A8 distributed quantization on a large language model using llmcompressor oneshot with calibration dataset', 'init_distributed_process_group': 'init a distributed process group for multi-GPU quantization with torch.distributed and compressed_tensors', 'load_offloaded_model_ddp': 'load a large causal language model with auto offloading for distributed DDP training', 'partition_calibration_dataset': 'partition a HuggingFace dataset by rank for distributed calibration across multiple GPUs', 'generate_text_quantized_model': 'generate text from a quantized model after dispatching offloaded layers to GPU memory'}
```

