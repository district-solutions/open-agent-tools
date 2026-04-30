# Agent Python Tools

- repo: ggml-org/llama.cpp
- repo_uri: https://github.com/ggml-org/llama.cpp

## File: ggml-org_llama.cpp/gguf-py/tests/test_metadata.py

Prompts

```
['test the gguf.Metadata.id_to_title method converts model IDs to readable titles', 'test the gguf.Metadata.get_model_id_components method parses model IDs into organization, basename, finetune, version, and size label', 'test the gguf.Metadata.apply_metadata_heuristic method extracts metadata from HuggingFace model card dictionaries', 'test the gguf.Metadata.apply_metadata_heuristic method infers metadata from HF parameters dict', 'test the gguf.Metadata.apply_metadata_heuristic method infers metadata from a model directory path', 'test the Python (de)quantization implementations match the C libggml reference implementation', 'test the ggml_quantize_chunk C binding for quantizing float tensors to various quantization types', 'test the dequantize_row C bindings for converting quantized tensors back to float32', 'test the compare_tensors function for bitwise comparison of quantized tensor blocks', 'test the GGMLQuants class interface for loading libggml and performing quantize and dequantize operations']
```

Usage

```
{'test_id_to_title': 'test the gguf.Metadata.id_to_title method converts model IDs to readable titles', 'test_get_model_id_components': 'test the gguf.Metadata.get_model_id_components method parses model IDs into organization, basename, finetune, version, and size label', 'test_apply_metadata_heuristic_from_model_card': 'test the gguf.Metadata.apply_metadata_heuristic method extracts metadata from HuggingFace model card dictionaries', 'test_apply_metadata_heuristic_from_hf_parameters': 'test the gguf.Metadata.apply_metadata_heuristic method infers metadata from HF parameters dict', 'test_apply_metadata_heuristic_from_model_dir': 'test the gguf.Metadata.apply_metadata_heuristic method infers metadata from a model directory path'}
```

## File: ggml-org_llama.cpp/gguf-py/tests/test_quants.py

Prompts

```
['test the gguf.Metadata.id_to_title method converts model IDs to readable titles', 'test the gguf.Metadata.get_model_id_components method parses model IDs into organization, basename, finetune, version, and size label', 'test the gguf.Metadata.apply_metadata_heuristic method extracts metadata from HuggingFace model card dictionaries', 'test the gguf.Metadata.apply_metadata_heuristic method infers metadata from HF parameters dict', 'test the gguf.Metadata.apply_metadata_heuristic method infers metadata from a model directory path', 'test the Python (de)quantization implementations match the C libggml reference implementation', 'test the ggml_quantize_chunk C binding for quantizing float tensors to various quantization types', 'test the dequantize_row C bindings for converting quantized tensors back to float32', 'test the compare_tensors function for bitwise comparison of quantized tensor blocks', 'test the GGMLQuants class interface for loading libggml and performing quantize and dequantize operations']
```

Usage

```
{'test_QUANTIZATION_PYTHON_AGAINST_C': 'test the Python (de)quantization implementations match the C libggml reference implementation', 'test_QUANTIZE_CHUNK_C_BINDING': 'test the ggml_quantize_chunk C binding for quantizing float tensors to various quantization types', 'test_DEQUANTIZE_ROW_C_BINDING': 'test the dequantize_row C bindings for converting quantized tensors back to float32', 'test_COMPARE_TENSORS_BITWISE': 'test the compare_tensors function for bitwise comparison of quantized tensor blocks', 'test_GGMLQUANTS_CLASS_INTERFACE': 'test the GGMLQuants class interface for loading libggml and performing quantize and dequantize operations'}
```

