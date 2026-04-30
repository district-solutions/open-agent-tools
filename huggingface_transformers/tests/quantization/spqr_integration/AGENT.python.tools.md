# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/quantization/spqr_integration/test_spqr.py

Prompts

```
['load a SPQR quantized causal LM model from a HuggingFace hub repository', 'replace torch.nn.Linear layers with SPQR QuantizedLinear using replace_with_spqr_linear', 'create a SpQRConfig object from a dictionary with beta1, beta2, and bits keys', 'generate text tokens using a SPQR quantized model with AutoModelForCausalLM', 'set up a StaticCache and torch.compile for optimized token-by-token generation']
```

Usage

```
{'load_spqr_quantized_model': 'load a SPQR quantized causal LM model from a HuggingFace hub repository', 'convert_linear_to_spqr': 'replace torch.nn.Linear layers with SPQR QuantizedLinear using replace_with_spqr_linear', 'create_spqr_config_from_dict': 'create a SpQRConfig object from a dictionary with beta1, beta2, and bits keys', 'generate_text_with_quantized_model': 'generate text tokens using a SPQR quantized model with AutoModelForCausalLM', 'setup_static_cache_for_compiled_generation': 'set up a StaticCache and torch.compile for optimized token-by-token generation'}
```

