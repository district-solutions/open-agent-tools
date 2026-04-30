# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/examples/quantization_w8a8_int8/benchmark_smoothquant_ddp.py

Prompts

```
['benchmark single-gpu vs multi-gpu DDP SmoothQuant calibration time with a given number of GPUs', 'run SmoothQuant and GPTQ W8A8 quantization calibration on a HuggingFace causal language model', 'create a SmoothQuantModifier with a configurable smoothing strength for activation-weight quantization', 'create a GPTQModifier targeting Linear layers with W8A8 scheme and optional layer exclusions', 'run oneshot quantization on a model using a recipe of modifiers and a calibration dataset', 'run W8A8 int8 quantization on a causal language model using llmcompressor oneshot', 'build a tokenized calibration dataset from HuggingFace messages using a tokenizer', 'test a quantized model by generating text samples with dispatch_model and model.generate', 'save a quantized model and tokenizer to disk in compressed-tensors format', 'run dispatch_model to offload a quantized transformer model for inference', 'run model.generate with tokenized input to produce text output from a quantized model', 'run distributed W8A8 SmoothQuant + GPTQ quantization on a causal language model using torchrun', 'create a quantization recipe with SmoothQuantModifier and GPTQModifier for W8A8 weight-activation quantization', 'build a distributed calibration dataset with disjoint rank partitions for multi-GPU quantization', 'test the oneshot quantization pipeline with a model, dataset, and modifier recipe', 'summarize quantization results including elapsed time and peak GPU memory usage per rank']
```

Usage

```
{'benchmark_smoothquant_ddp_main': 'benchmark single-gpu vs multi-gpu DDP SmoothQuant calibration time with a given number of GPUs', 'run_smoothquant_gptq_quantization': 'run SmoothQuant and GPTQ W8A8 quantization calibration on a HuggingFace causal language model', 'create_smoothquant_modifier': 'create a SmoothQuantModifier with a configurable smoothing strength for activation-weight quantization', 'create_gptq_modifier': 'create a GPTQModifier targeting Linear layers with W8A8 scheme and optional layer exclusions', 'run_oneshot_quantization': 'run oneshot quantization on a model using a recipe of modifiers and a calibration dataset'}
```

## File: vllm-project_llm-compressor/examples/quantization_w8a8_int8/gemma2_example.py

Prompts

```
['benchmark single-gpu vs multi-gpu DDP SmoothQuant calibration time with a given number of GPUs', 'run SmoothQuant and GPTQ W8A8 quantization calibration on a HuggingFace causal language model', 'create a SmoothQuantModifier with a configurable smoothing strength for activation-weight quantization', 'create a GPTQModifier targeting Linear layers with W8A8 scheme and optional layer exclusions', 'run oneshot quantization on a model using a recipe of modifiers and a calibration dataset', 'run W8A8 int8 quantization on a causal language model using llmcompressor oneshot', 'build a tokenized calibration dataset from HuggingFace messages using a tokenizer', 'test a quantized model by generating text samples with dispatch_model and model.generate', 'save a quantized model and tokenizer to disk in compressed-tensors format', 'run dispatch_model to offload a quantized transformer model for inference', 'run model.generate with tokenized input to produce text output from a quantized model', 'run distributed W8A8 SmoothQuant + GPTQ quantization on a causal language model using torchrun', 'create a quantization recipe with SmoothQuantModifier and GPTQModifier for W8A8 weight-activation quantization', 'build a distributed calibration dataset with disjoint rank partitions for multi-GPU quantization', 'test the oneshot quantization pipeline with a model, dataset, and modifier recipe', 'summarize quantization results including elapsed time and peak GPU memory usage per rank']
```

Usage

```
{'run_quantization_oneshot': 'run W8A8 int8 quantization on a causal language model using llmcompressor oneshot', 'create_gptq_modifier': 'create a GPTQModifier recipe targeting Linear layers with W8A8 quantization scheme', 'build_calibration_dataset': 'build a tokenized calibration dataset from HuggingFace messages using a tokenizer', 'test_quantized_model': 'test a quantized model by generating text samples with dispatch_model and model.generate', 'save_quantized_model': 'save a quantized model and tokenizer to disk in compressed-tensors format'}
```

## File: vllm-project_llm-compressor/examples/quantization_w8a8_int8/llama3_example.py

Prompts

```
['benchmark single-gpu vs multi-gpu DDP SmoothQuant calibration time with a given number of GPUs', 'run SmoothQuant and GPTQ W8A8 quantization calibration on a HuggingFace causal language model', 'create a SmoothQuantModifier with a configurable smoothing strength for activation-weight quantization', 'create a GPTQModifier targeting Linear layers with W8A8 scheme and optional layer exclusions', 'run oneshot quantization on a model using a recipe of modifiers and a calibration dataset', 'run W8A8 int8 quantization on a causal language model using llmcompressor oneshot', 'build a tokenized calibration dataset from HuggingFace messages using a tokenizer', 'test a quantized model by generating text samples with dispatch_model and model.generate', 'save a quantized model and tokenizer to disk in compressed-tensors format', 'run dispatch_model to offload a quantized transformer model for inference', 'run model.generate with tokenized input to produce text output from a quantized model', 'run distributed W8A8 SmoothQuant + GPTQ quantization on a causal language model using torchrun', 'create a quantization recipe with SmoothQuantModifier and GPTQModifier for W8A8 weight-activation quantization', 'build a distributed calibration dataset with disjoint rank partitions for multi-GPU quantization', 'test the oneshot quantization pipeline with a model, dataset, and modifier recipe', 'summarize quantization results including elapsed time and peak GPU memory usage per rank']
```

Usage

```
{'run_oneshot_quantization': 'run oneshot to apply SmoothQuant and GPTQ W8A8 int8 quantization to a transformer model', 'create_smoothquant_modifier': 'create a SmoothQuantModifier with a given smoothing strength to ease activation quantization', 'create_gptq_modifier': 'create a GPTQModifier targeting Linear layers with W8A8 int8 scheme and ignoring lm_head', 'run_dispatch_model': 'run dispatch_model to offload a quantized transformer model for inference', 'run_model_generate': 'run model.generate with tokenized input to produce text output from a quantized model'}
```

## File: vllm-project_llm-compressor/examples/quantization_w8a8_int8/smoothquant_ddp_example.py

Prompts

```
['benchmark single-gpu vs multi-gpu DDP SmoothQuant calibration time with a given number of GPUs', 'run SmoothQuant and GPTQ W8A8 quantization calibration on a HuggingFace causal language model', 'create a SmoothQuantModifier with a configurable smoothing strength for activation-weight quantization', 'create a GPTQModifier targeting Linear layers with W8A8 scheme and optional layer exclusions', 'run oneshot quantization on a model using a recipe of modifiers and a calibration dataset', 'run W8A8 int8 quantization on a causal language model using llmcompressor oneshot', 'build a tokenized calibration dataset from HuggingFace messages using a tokenizer', 'test a quantized model by generating text samples with dispatch_model and model.generate', 'save a quantized model and tokenizer to disk in compressed-tensors format', 'run dispatch_model to offload a quantized transformer model for inference', 'run model.generate with tokenized input to produce text output from a quantized model', 'run distributed W8A8 SmoothQuant + GPTQ quantization on a causal language model using torchrun', 'create a quantization recipe with SmoothQuantModifier and GPTQModifier for W8A8 weight-activation quantization', 'build a distributed calibration dataset with disjoint rank partitions for multi-GPU quantization', 'test the oneshot quantization pipeline with a model, dataset, and modifier recipe', 'summarize quantization results including elapsed time and peak GPU memory usage per rank']
```

Usage

```
{'run_smoothquant_ddp_quantization': 'run distributed W8A8 SmoothQuant + GPTQ quantization on a causal language model using torchrun', 'create_smoothquant_recipe': 'create a quantization recipe with SmoothQuantModifier and GPTQModifier for W8A8 weight-activation quantization', 'build_ddp_calibration_dataset': 'build a distributed calibration dataset with disjoint rank partitions for multi-GPU quantization', 'test_oneshot_quantization': 'test the oneshot quantization pipeline with a model, dataset, and modifier recipe', 'summarize_quantization_results': 'summarize quantization results including elapsed time and peak GPU memory usage per rank'}
```

