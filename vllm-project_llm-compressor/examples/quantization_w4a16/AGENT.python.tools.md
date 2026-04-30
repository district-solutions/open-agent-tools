# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/examples/quantization_w4a16/llama3_ddp_example.py

Prompts

```
['run W4A16 GPTQ quantization on Llama 3 8B model using distributed data parallel', 'create a GPTQModifier with W4A16 quantization scheme targeting Linear layers', 'run oneshot quantization on a transformer model with a calibration dataset', 'build a distributed model loader using init_dist and load_offloaded_model context manager', 'test the quantized model by generating text samples after quantization', 'preprocess a chat dataset by applying a tokenizer chat template to message pairs', 'tokenize dataset samples with truncation and max sequence length constraints', 'dispatch an offloaded model and generate text completions from a prompt']
```

Usage

```
{'run_quantization_ddp': 'run W4A16 GPTQ quantization on Llama 3 8B model using distributed data parallel', 'create_gptq_modifier': 'create a GPTQModifier with W4A16 quantization scheme targeting Linear layers', 'run_oneshot_quantization': 'run oneshot quantization on a transformer model with a calibration dataset', 'build_ddp_model_load': 'build a distributed model loader using init_dist and load_offloaded_model context manager', 'test_quantized_model_generation': 'test the quantized model by generating text samples after quantization'}
```

## File: vllm-project_llm-compressor/examples/quantization_w4a16/llama3_example.py

Prompts

```
['run W4A16 GPTQ quantization on Llama 3 8B model using distributed data parallel', 'create a GPTQModifier with W4A16 quantization scheme targeting Linear layers', 'run oneshot quantization on a transformer model with a calibration dataset', 'build a distributed model loader using init_dist and load_offloaded_model context manager', 'test the quantized model by generating text samples after quantization', 'preprocess a chat dataset by applying a tokenizer chat template to message pairs', 'tokenize dataset samples with truncation and max sequence length constraints', 'dispatch an offloaded model and generate text completions from a prompt']
```

Usage

```
{'run_oneshot_quantization': 'run oneshot quantization on a transformer model using GPTQ with W4A16 scheme', 'create_gptq_modifier': 'create a GPTQModifier recipe targeting Linear layers with W4A16 quantization', 'preprocess_chat_dataset': 'preprocess a chat dataset by applying a tokenizer chat template to message pairs', 'tokenize_dataset_samples': 'tokenize dataset samples with truncation and max sequence length constraints', 'dispatch_and_generate': 'dispatch an offloaded model and generate text completions from a prompt'}
```

