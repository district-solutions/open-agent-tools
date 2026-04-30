# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/quantization/fbgemm_fp8/test_fbgemm_fp8.py

Prompts

```
['test that FbgemmFp8Config converts to a dict with matching attribute values', 'test that FbgemmFp8Config creates a config object from a dictionary', 'test replacing all Linear layers with FbgemmFp8Linear quantized modules', 'test loading a pretrained causal LM model with FbgemmFp8Config quantization', 'test saving a quantized model and reloading it for inference']
```

Usage

```
{'test_FbgemmFp8Config_to_dict': 'test that FbgemmFp8Config converts to a dict with matching attribute values', 'test_FbgemmFp8Config_from_dict': 'test that FbgemmFp8Config creates a config object from a dictionary', 'test_replace_with_fbgemm_fp8_linear': 'test replacing all Linear layers with FbgemmFp8Linear quantized modules', 'test_load_quantized_model': 'test loading a pretrained causal LM model with FbgemmFp8Config quantization', 'test_save_and_reload_quantized_model': 'test saving a quantized model and reloading it for inference'}
```

