# Agent Python Tools

- repo: ggml-org/llama.cpp
- repo_uri: https://github.com/ggml-org/llama.cpp

## File: ggml-org_llama.cpp/convert_hf_to_gguf.py

Prompts

```
['convert a huggingface model directory to GGUF format with specified output type like f16 or q8_0', 'export only the tokenizer vocabulary from a huggingface model directory to a GGUF vocab file', 'export the multimodal projector weights from a vision-language model to GGUF format', 'print the list of all supported model architectures for HF-to-GGUF conversion', 'convert a huggingface model repository from remote using its model ID without downloading locally', 'download tokenizer models from Huggingface repositories for specified list of LLM models', 'update convert_hf_to_gguf.py with generated get_vocab_base_pre function containing pre-tokenizer hashes', 'generate vocab test input and output files for each tokenizer model using standard test strings', 'compute sha256 hash of tokenizer encoding for a model to identify its BPE pre-tokenizer uniquely', 'check which models are missing pre-tokenizer hashes in convert_hf_to_gguf.py without downloading', 'convert a legacy GGML model file to GGUF format using command-line arguments', 'run GGML to GGUF conversion with HuggingFace metadata directory for vocab override', 'parse GGML model hyperparameters including n_vocab, n_embd, n_head, n_layer, and ftype', 'convert a GGML model specifying grouped-query attention factor and RMS norm epsilon', 'load tensor metadata including name, dimensions, dtype, and byte offset from a GGML file', 'convert a Hugging Face PEFT LoRA adapter to a GGUF file with specified output format', 'run the CLI to convert a LoRA adapter from safetensors or bin to GGUF format', 'build a GGUF LoRA adapter using a local base model directory or Hugging Face model ID', 'test a LoRA to GGUF conversion with dry-run mode to preview without writing files', 'review the LoraTorchTensor class that wraps LoRA A and B tensors for shape manipulation']
```

Usage

```
{'convert_hf_model_to_gguf': 'convert a huggingface model directory to GGUF format with specified output type like f16 or q8_0', 'export_model_vocab_only': 'export only the tokenizer vocabulary from a huggingface model directory to a GGUF vocab file', 'export_mmproj_for_vision_model': 'export the multimodal projector weights from a vision-language model to GGUF format', 'print_supported_models': 'print the list of all supported model architectures for HF-to-GGUF conversion', 'convert_remote_hf_model': 'convert a huggingface model repository from remote using its model ID without downloading locally'}
```

## File: ggml-org_llama.cpp/convert_hf_to_gguf_update.py

Prompts

```
['convert a huggingface model directory to GGUF format with specified output type like f16 or q8_0', 'export only the tokenizer vocabulary from a huggingface model directory to a GGUF vocab file', 'export the multimodal projector weights from a vision-language model to GGUF format', 'print the list of all supported model architectures for HF-to-GGUF conversion', 'convert a huggingface model repository from remote using its model ID without downloading locally', 'download tokenizer models from Huggingface repositories for specified list of LLM models', 'update convert_hf_to_gguf.py with generated get_vocab_base_pre function containing pre-tokenizer hashes', 'generate vocab test input and output files for each tokenizer model using standard test strings', 'compute sha256 hash of tokenizer encoding for a model to identify its BPE pre-tokenizer uniquely', 'check which models are missing pre-tokenizer hashes in convert_hf_to_gguf.py without downloading', 'convert a legacy GGML model file to GGUF format using command-line arguments', 'run GGML to GGUF conversion with HuggingFace metadata directory for vocab override', 'parse GGML model hyperparameters including n_vocab, n_embd, n_head, n_layer, and ftype', 'convert a GGML model specifying grouped-query attention factor and RMS norm epsilon', 'load tensor metadata including name, dimensions, dtype, and byte offset from a GGML file', 'convert a Hugging Face PEFT LoRA adapter to a GGUF file with specified output format', 'run the CLI to convert a LoRA adapter from safetensors or bin to GGUF format', 'build a GGUF LoRA adapter using a local base model directory or Hugging Face model ID', 'test a LoRA to GGUF conversion with dry-run mode to preview without writing files', 'review the LoraTorchTensor class that wraps LoRA A and B tensors for shape manipulation']
```

Usage

```
{'download_hf_tokenizers': 'download tokenizer models from Huggingface repositories for specified list of LLM models', 'update_get_vocab_base_pre': 'update convert_hf_to_gguf.py with generated get_vocab_base_pre function containing pre-tokenizer hashes', 'generate_tokenizer_tests': 'generate vocab test input and output files for each tokenizer model using standard test strings', 'compute_tokenizer_hash': 'compute sha256 hash of tokenizer encoding for a model to identify its BPE pre-tokenizer uniquely', 'check_missing_hashes': 'check which models are missing pre-tokenizer hashes in convert_hf_to_gguf.py without downloading'}
```

## File: ggml-org_llama.cpp/convert_llama_ggml_to_gguf.py

Prompts

```
['convert a huggingface model directory to GGUF format with specified output type like f16 or q8_0', 'export only the tokenizer vocabulary from a huggingface model directory to a GGUF vocab file', 'export the multimodal projector weights from a vision-language model to GGUF format', 'print the list of all supported model architectures for HF-to-GGUF conversion', 'convert a huggingface model repository from remote using its model ID without downloading locally', 'download tokenizer models from Huggingface repositories for specified list of LLM models', 'update convert_hf_to_gguf.py with generated get_vocab_base_pre function containing pre-tokenizer hashes', 'generate vocab test input and output files for each tokenizer model using standard test strings', 'compute sha256 hash of tokenizer encoding for a model to identify its BPE pre-tokenizer uniquely', 'check which models are missing pre-tokenizer hashes in convert_hf_to_gguf.py without downloading', 'convert a legacy GGML model file to GGUF format using command-line arguments', 'run GGML to GGUF conversion with HuggingFace metadata directory for vocab override', 'parse GGML model hyperparameters including n_vocab, n_embd, n_head, n_layer, and ftype', 'convert a GGML model specifying grouped-query attention factor and RMS norm epsilon', 'load tensor metadata including name, dimensions, dtype, and byte offset from a GGML file', 'convert a Hugging Face PEFT LoRA adapter to a GGUF file with specified output format', 'run the CLI to convert a LoRA adapter from safetensors or bin to GGUF format', 'build a GGUF LoRA adapter using a local base model directory or Hugging Face model ID', 'test a LoRA to GGUF conversion with dry-run mode to preview without writing files', 'review the LoraTorchTensor class that wraps LoRA A and B tensors for shape manipulation']
```

Usage

```
{'convert_ggml_to_gguf': 'convert a legacy GGML model file to GGUF format using command-line arguments', 'run_ggml_conversion_with_metadata': 'run GGML to GGUF conversion with HuggingFace metadata directory for vocab override', 'parse_ggml_model_hyperparameters': 'parse GGML model hyperparameters including n_vocab, n_embd, n_head, n_layer, and ftype', 'convert_ggml_with_gqa_and_eps': 'convert a GGML model specifying grouped-query attention factor and RMS norm epsilon', 'load_ggml_tensor_metadata': 'load tensor metadata including name, dimensions, dtype, and byte offset from a GGML file'}
```

## File: ggml-org_llama.cpp/convert_lora_to_gguf.py

Prompts

```
['convert a huggingface model directory to GGUF format with specified output type like f16 or q8_0', 'export only the tokenizer vocabulary from a huggingface model directory to a GGUF vocab file', 'export the multimodal projector weights from a vision-language model to GGUF format', 'print the list of all supported model architectures for HF-to-GGUF conversion', 'convert a huggingface model repository from remote using its model ID without downloading locally', 'download tokenizer models from Huggingface repositories for specified list of LLM models', 'update convert_hf_to_gguf.py with generated get_vocab_base_pre function containing pre-tokenizer hashes', 'generate vocab test input and output files for each tokenizer model using standard test strings', 'compute sha256 hash of tokenizer encoding for a model to identify its BPE pre-tokenizer uniquely', 'check which models are missing pre-tokenizer hashes in convert_hf_to_gguf.py without downloading', 'convert a legacy GGML model file to GGUF format using command-line arguments', 'run GGML to GGUF conversion with HuggingFace metadata directory for vocab override', 'parse GGML model hyperparameters including n_vocab, n_embd, n_head, n_layer, and ftype', 'convert a GGML model specifying grouped-query attention factor and RMS norm epsilon', 'load tensor metadata including name, dimensions, dtype, and byte offset from a GGML file', 'convert a Hugging Face PEFT LoRA adapter to a GGUF file with specified output format', 'run the CLI to convert a LoRA adapter from safetensors or bin to GGUF format', 'build a GGUF LoRA adapter using a local base model directory or Hugging Face model ID', 'test a LoRA to GGUF conversion with dry-run mode to preview without writing files', 'review the LoraTorchTensor class that wraps LoRA A and B tensors for shape manipulation']
```

Usage

```
{'convert_lora_adapter_to_gguf': 'convert a Hugging Face PEFT LoRA adapter to a GGUF file with specified output format', 'run_lora_conversion_cli': 'run the CLI to convert a LoRA adapter from safetensors or bin to GGUF format', 'build_lora_gguf_with_base_model': 'build a GGUF LoRA adapter using a local base model directory or Hugging Face model ID', 'test_lora_conversion_dry_run': 'test a LoRA to GGUF conversion with dry-run mode to preview without writing files', 'review_lora_tensor_operations': 'review the LoraTorchTensor class that wraps LoRA A and B tensors for shape manipulation'}
```

