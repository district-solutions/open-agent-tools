# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/examples/quantization_kv_cache/gemma2_fp8_kv_example.py

Prompts

```
['load a HuggingFace causal language model and tokenizer for FP8 quantization', 'quantize a model weights, activations, and KV cache to FP8 using llmcompressor oneshot', 'preprocess and tokenize a HuggingFace dataset for model quantization calibration', 'generate text from a quantized model using dispatch_model and model.generate', 'save a quantized model and tokenizer to disk in compressed format', 'run FP8 dynamic quantization on a transformer model using llmcompressor oneshot with a calibration dataset', 'create a QuantizationModifier recipe targeting Linear layers with FP8_DYNAMIC scheme and FP8 KV cache per attention head', 'preprocess a HuggingFace chat dataset by applying a tokenizer chat template to convert messages to text', 'tokenize dataset samples with truncation and max sequence length for model calibration', 'generate text from a quantized transformer model using dispatch_model and model.generate', 'run oneshot quantization on a transformer model with fp8 weights, activations, and kv cache', 'run dispatch_model to offload a quantized llm for inference on available devices', 'create and load a causal language model from pretrained huggingface checkpoint with auto dtype', 'create and load a tokenizer from a pretrained huggingface model checkpoint', 'run save_pretrained to save a quantized model and tokenizer to disk in compressed format', 'load a causal language model from pretrained using AutoModelForCausalLM with auto dtype', 'generate text from a quantized model using model.generate with max_new_tokens']
```

Usage

```
{'load_quantization_model': 'load a HuggingFace causal language model and tokenizer for FP8 quantization', 'quantize_model_fp8_kv_cache': 'quantize a model weights, activations, and KV cache to FP8 using llmcompressor oneshot', 'preprocess_calibration_dataset': 'preprocess and tokenize a HuggingFace dataset for model quantization calibration', 'generate_text_quantized_model': 'generate text from a quantized model using dispatch_model and model.generate', 'save_quantized_model_compressed': 'save a quantized model and tokenizer to disk in compressed format'}
```

## File: vllm-project_llm-compressor/examples/quantization_kv_cache/llama3_fp8_head_kv_example.py

Prompts

```
['load a HuggingFace causal language model and tokenizer for FP8 quantization', 'quantize a model weights, activations, and KV cache to FP8 using llmcompressor oneshot', 'preprocess and tokenize a HuggingFace dataset for model quantization calibration', 'generate text from a quantized model using dispatch_model and model.generate', 'save a quantized model and tokenizer to disk in compressed format', 'run FP8 dynamic quantization on a transformer model using llmcompressor oneshot with a calibration dataset', 'create a QuantizationModifier recipe targeting Linear layers with FP8_DYNAMIC scheme and FP8 KV cache per attention head', 'preprocess a HuggingFace chat dataset by applying a tokenizer chat template to convert messages to text', 'tokenize dataset samples with truncation and max sequence length for model calibration', 'generate text from a quantized transformer model using dispatch_model and model.generate', 'run oneshot quantization on a transformer model with fp8 weights, activations, and kv cache', 'run dispatch_model to offload a quantized llm for inference on available devices', 'create and load a causal language model from pretrained huggingface checkpoint with auto dtype', 'create and load a tokenizer from a pretrained huggingface model checkpoint', 'run save_pretrained to save a quantized model and tokenizer to disk in compressed format', 'load a causal language model from pretrained using AutoModelForCausalLM with auto dtype', 'generate text from a quantized model using model.generate with max_new_tokens']
```

Usage

```
{'run_quantization_oneshot': 'run FP8 dynamic quantization on a transformer model using llmcompressor oneshot with a calibration dataset', 'create_quantization_modifier': 'create a QuantizationModifier recipe targeting Linear layers with FP8_DYNAMIC scheme and FP8 KV cache per attention head', 'preprocess_chat_dataset': 'preprocess a HuggingFace chat dataset by applying a tokenizer chat template to convert messages to text', 'tokenize_dataset_samples': 'tokenize dataset samples with truncation and max sequence length for model calibration', 'generate_with_quantized_model': 'generate text from a quantized transformer model using dispatch_model and model.generate'}
```

## File: vllm-project_llm-compressor/examples/quantization_kv_cache/llama3_fp8_kv_example.py

Prompts

```
['load a HuggingFace causal language model and tokenizer for FP8 quantization', 'quantize a model weights, activations, and KV cache to FP8 using llmcompressor oneshot', 'preprocess and tokenize a HuggingFace dataset for model quantization calibration', 'generate text from a quantized model using dispatch_model and model.generate', 'save a quantized model and tokenizer to disk in compressed format', 'run FP8 dynamic quantization on a transformer model using llmcompressor oneshot with a calibration dataset', 'create a QuantizationModifier recipe targeting Linear layers with FP8_DYNAMIC scheme and FP8 KV cache per attention head', 'preprocess a HuggingFace chat dataset by applying a tokenizer chat template to convert messages to text', 'tokenize dataset samples with truncation and max sequence length for model calibration', 'generate text from a quantized transformer model using dispatch_model and model.generate', 'run oneshot quantization on a transformer model with fp8 weights, activations, and kv cache', 'run dispatch_model to offload a quantized llm for inference on available devices', 'create and load a causal language model from pretrained huggingface checkpoint with auto dtype', 'create and load a tokenizer from a pretrained huggingface model checkpoint', 'run save_pretrained to save a quantized model and tokenizer to disk in compressed format', 'load a causal language model from pretrained using AutoModelForCausalLM with auto dtype', 'generate text from a quantized model using model.generate with max_new_tokens']
```

Usage

```
{'run_oneshot_quantization': 'run oneshot quantization on a transformer model with fp8 weights, activations, and kv cache', 'run_dispatch_model': 'run dispatch_model to offload a quantized llm for inference on available devices', 'create_load_model': 'create and load a causal language model from pretrained huggingface checkpoint with auto dtype', 'create_load_tokenizer': 'create and load a tokenizer from a pretrained huggingface model checkpoint', 'run_save_pretrained': 'run save_pretrained to save a quantized model and tokenizer to disk in compressed format'}
```

## File: vllm-project_llm-compressor/examples/quantization_kv_cache/phi3.5_fp8_kv_example.py

Prompts

```
['load a HuggingFace causal language model and tokenizer for FP8 quantization', 'quantize a model weights, activations, and KV cache to FP8 using llmcompressor oneshot', 'preprocess and tokenize a HuggingFace dataset for model quantization calibration', 'generate text from a quantized model using dispatch_model and model.generate', 'save a quantized model and tokenizer to disk in compressed format', 'run FP8 dynamic quantization on a transformer model using llmcompressor oneshot with a calibration dataset', 'create a QuantizationModifier recipe targeting Linear layers with FP8_DYNAMIC scheme and FP8 KV cache per attention head', 'preprocess a HuggingFace chat dataset by applying a tokenizer chat template to convert messages to text', 'tokenize dataset samples with truncation and max sequence length for model calibration', 'generate text from a quantized transformer model using dispatch_model and model.generate', 'run oneshot quantization on a transformer model with fp8 weights, activations, and kv cache', 'run dispatch_model to offload a quantized llm for inference on available devices', 'create and load a causal language model from pretrained huggingface checkpoint with auto dtype', 'create and load a tokenizer from a pretrained huggingface model checkpoint', 'run save_pretrained to save a quantized model and tokenizer to disk in compressed format', 'load a causal language model from pretrained using AutoModelForCausalLM with auto dtype', 'generate text from a quantized model using model.generate with max_new_tokens']
```

Usage

```
{'run_oneshot_quantization': 'run oneshot quantization on a causal LM model with fp8 weights, activations, and kv cache', 'load_model_from_pretrained': 'load a causal language model from pretrained using AutoModelForCausalLM with auto dtype', 'quantize_model_fp8_kv_cache': 'quantize model weights, activations, and kv cache to fp8 with per-tensor strategy', 'generate_text_with_quantized_model': 'generate text from a quantized model using model.generate with max_new_tokens', 'save_quantized_model_compressed': 'save a quantized model and tokenizer to disk with save_compressed enabled'}
```

