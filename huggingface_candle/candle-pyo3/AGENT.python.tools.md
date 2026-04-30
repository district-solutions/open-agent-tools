# Agent Python Tools

- repo: huggingface/candle
- repo_uri: https://github.com/huggingface/candle

## File: huggingface_candle/candle-pyo3/e5.py

Prompts

```
['run a BERT model forward pass on tokenized sentences using candle tensors', 'quantize model tensors to q4k, q5_0, or q8_0 formats for compression', 'save quantized tensors and config to a GGUF file for efficient storage', 'load a GGUF model file and reconstruct the BertModel with quantized weights', 'compare candle model output against HuggingFace reference using L1 loss', 'run quantized llama model inference from a GGUF or GGML weight file with greedy sampling', 'load a GGML model file and extract tensors, hyperparameters, and vocabulary using candle utils', 'rename GGUF tensor names to match llama.cpp naming convention using gguf_rename function', 'build a QuantizedLlama model instance from hyperparameters and tensor dictionary for inference', 'run stub.py to generate .pyi type stub files for the candle Python bindings module', 'run stub.py with --check flag to verify existing stub files are up to date', 'generate __init__.py files that re-export all public members from the candle module', 'extract class types from a module to use as additional type hints for stub generation', 'format generated stub content using black with Python 3.5 target and 119 character line length']
```

Usage

```
{'run_bert_inference': 'run a BERT model forward pass on tokenized sentences using candle tensors', 'quantize_tensors': 'quantize model tensors to q4k, q5_0, or q8_0 formats for compression', 'save_gguf_model': 'save quantized tensors and config to a GGUF file for efficient storage', 'load_gguf_model': 'load a GGUF model file and reconstruct the BertModel with quantized weights', 'compare_model_outputs': 'compare candle model output against HuggingFace reference using L1 loss'}
```

## File: huggingface_candle/candle-pyo3/quant-llama.py

Prompts

```
['run a BERT model forward pass on tokenized sentences using candle tensors', 'quantize model tensors to q4k, q5_0, or q8_0 formats for compression', 'save quantized tensors and config to a GGUF file for efficient storage', 'load a GGUF model file and reconstruct the BertModel with quantized weights', 'compare candle model output against HuggingFace reference using L1 loss', 'run quantized llama model inference from a GGUF or GGML weight file with greedy sampling', 'load a GGML model file and extract tensors, hyperparameters, and vocabulary using candle utils', 'rename GGUF tensor names to match llama.cpp naming convention using gguf_rename function', 'build a QuantizedLlama model instance from hyperparameters and tensor dictionary for inference', 'run stub.py to generate .pyi type stub files for the candle Python bindings module', 'run stub.py with --check flag to verify existing stub files are up to date', 'generate __init__.py files that re-export all public members from the candle module', 'extract class types from a module to use as additional type hints for stub generation', 'format generated stub content using black with Python 3.5 target and 119 character line length']
```

Usage

```
{'run_quantized_llama_inference': 'run quantized llama model inference from a GGUF or GGML weight file with greedy sampling', 'load_gguf_model': 'load a GGUF model file and extract tensors, metadata, and vocabulary using candle utils', 'load_ggml_model': 'load a GGML model file and extract tensors, hyperparameters, and vocabulary using candle utils', 'rename_gguf_tensors': 'rename GGUF tensor names to match llama.cpp naming convention using gguf_rename function', 'build_quantized_llama_model': 'build a QuantizedLlama model instance from hyperparameters and tensor dictionary for inference'}
```

## File: huggingface_candle/candle-pyo3/stub.py

Prompts

```
['run a BERT model forward pass on tokenized sentences using candle tensors', 'quantize model tensors to q4k, q5_0, or q8_0 formats for compression', 'save quantized tensors and config to a GGUF file for efficient storage', 'load a GGUF model file and reconstruct the BertModel with quantized weights', 'compare candle model output against HuggingFace reference using L1 loss', 'run quantized llama model inference from a GGUF or GGML weight file with greedy sampling', 'load a GGML model file and extract tensors, hyperparameters, and vocabulary using candle utils', 'rename GGUF tensor names to match llama.cpp naming convention using gguf_rename function', 'build a QuantizedLlama model instance from hyperparameters and tensor dictionary for inference', 'run stub.py to generate .pyi type stub files for the candle Python bindings module', 'run stub.py with --check flag to verify existing stub files are up to date', 'generate __init__.py files that re-export all public members from the candle module', 'extract class types from a module to use as additional type hints for stub generation', 'format generated stub content using black with Python 3.5 target and 119 character line length']
```

Usage

```
{'generate_pyi_stubs': 'run stub.py to generate .pyi type stub files for the candle Python bindings module', 'check_stubs_outdated': 'run stub.py with --check flag to verify existing stub files are up to date', 'generate_init_py': 'generate __init__.py files that re-export all public members from the candle module', 'extract_additional_types': 'extract class types from a module to use as additional type hints for stub generation', 'format_with_black': 'format generated stub content using black with Python 3.5 target and 119 character line length'}
```

