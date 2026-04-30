# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/model_executor/layers/quantization/turboquant/centroids.py

Prompts

```
['solve Lloyd-Max optimal scalar quantizer centroids for N(0, 1/d) distribution given dimension and bits', 'get precomputed Lloyd-Max centroids cached by dimension and quantization bits', 'build optimal quantization centroids for TurboQuant scalar quantizer with specified vector dimension and bit width', 'test Lloyd-Max iteration convergence for centroid optimization with tolerance and max iteration limits', 'review Gaussian PDF computation and trapezoidal numerical integration used in centroid calculation', 'create a TurboQuantConfig instance with custom head_dim, key_quant_bits, and value_quant_bits', 'build a TurboQuantConfig from a named preset like turboquant_k8v4 or turboquant_4bit_nc', 'calculate the packed slot size in bytes for a TurboQuant KV-cache configuration', 'get boundary layer indices to skip TurboQuant compression for a given number of model layers', 'check whether a TurboQuantConfig uses FP8 key storage instead of MSE quantization']
```

Usage

```
{'solve_lloyd_max_centroids': 'solve Lloyd-Max optimal scalar quantizer centroids for N(0, 1/d) distribution given dimension and bits', 'get_cached_centroids': 'get precomputed Lloyd-Max centroids cached by dimension and quantization bits', 'build_quantizer_centroids': 'build optimal quantization centroids for TurboQuant scalar quantizer with specified vector dimension and bit width', 'test_lloyd_max_convergence': 'test Lloyd-Max iteration convergence for centroid optimization with tolerance and max iteration limits', 'review_gaussian_pdf_integration': 'review Gaussian PDF computation and trapezoidal numerical integration used in centroid calculation'}
```

## File: vllm-project_vllm/vllm/model_executor/layers/quantization/turboquant/config.py

Prompts

```
['solve Lloyd-Max optimal scalar quantizer centroids for N(0, 1/d) distribution given dimension and bits', 'get precomputed Lloyd-Max centroids cached by dimension and quantization bits', 'build optimal quantization centroids for TurboQuant scalar quantizer with specified vector dimension and bit width', 'test Lloyd-Max iteration convergence for centroid optimization with tolerance and max iteration limits', 'review Gaussian PDF computation and trapezoidal numerical integration used in centroid calculation', 'create a TurboQuantConfig instance with custom head_dim, key_quant_bits, and value_quant_bits', 'build a TurboQuantConfig from a named preset like turboquant_k8v4 or turboquant_4bit_nc', 'calculate the packed slot size in bytes for a TurboQuant KV-cache configuration', 'get boundary layer indices to skip TurboQuant compression for a given number of model layers', 'check whether a TurboQuantConfig uses FP8 key storage instead of MSE quantization']
```

Usage

```
{'create_TurboQuantConfig': 'create a TurboQuantConfig instance with custom head_dim, key_quant_bits, and value_quant_bits', 'build_config_from_preset': 'build a TurboQuantConfig from a named preset like turboquant_k8v4 or turboquant_4bit_nc', 'calculate_slot_size': 'calculate the packed slot size in bytes for a TurboQuant KV-cache configuration', 'get_boundary_skip_layers': 'get boundary layer indices to skip TurboQuant compression for a given number of model layers', 'check_key_fp8_mode': 'check whether a TurboQuantConfig uses FP8 key storage instead of MSE quantization'}
```

