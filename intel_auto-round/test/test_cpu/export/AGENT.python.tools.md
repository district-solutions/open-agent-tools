# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/test/test_cpu/export/test_export.py

Prompts

```
['quantize a model and export it in auto_gptq format with 4-bit asymmetric quantization', 'quantize a model and export it in auto_round format with 4-bit symmetric quantization', 'quantize a model and export it in auto_awq format using the auto_round:auto_awq hybrid format', 'export an fp8 static quantized model with configurable static_kv_dtype for key and value projections', 'export a quantized model in llm_compressor format supporting int8 dynamic or w4a16 weight-only schemes', 'test quantizing a model to GGUF Q4_0 format using AutoRound with 4-bit symmetric quantization', 'test quantizing a model with custom per-layer configuration using GGUF Q4_K_M mixed format', 'test running AutoRound via command line with various GGUF quantization formats like q4_k_m', 'test quantizing a vision-language model to GGUF format with and without non-text module quantization', 'test setting layer-specific quantization types for embed tokens and lm_head using set_layer_config', 'test AutoRound FP8 static quantization and export to llm_compressor format', 'test AutoRound MXFP8 quantization and save to llm_compressor format', 'test AutoRound mixed precision MXFP4 and MXFP8 quantization with AutoScheme', 'test AutoRound quantize_and_save method with llm_compressor format output', 'test AutoRound serial export packing for FP8 static and MXFP8 formats']
```

Usage

```
{'quantize_and_save_autogptq_format': 'quantize a model and export it in auto_gptq format with 4-bit asymmetric quantization', 'quantize_and_save_autoround_format': 'quantize a model and export it in auto_round format with 4-bit symmetric quantization', 'quantize_and_save_autoawq_format': 'quantize a model and export it in auto_awq format using the auto_round:auto_awq hybrid format', 'export_fp8_static_quantization': 'export an fp8 static quantized model with configurable static_kv_dtype for key and value projections', 'export_llm_compressor_format': 'export a quantized model in llm_compressor format supporting int8 dynamic or w4a16 weight-only schemes'}
```

## File: intel_auto-round/test/test_cpu/export/test_gguf_format.py

Prompts

```
['quantize a model and export it in auto_gptq format with 4-bit asymmetric quantization', 'quantize a model and export it in auto_round format with 4-bit symmetric quantization', 'quantize a model and export it in auto_awq format using the auto_round:auto_awq hybrid format', 'export an fp8 static quantized model with configurable static_kv_dtype for key and value projections', 'export a quantized model in llm_compressor format supporting int8 dynamic or w4a16 weight-only schemes', 'test quantizing a model to GGUF Q4_0 format using AutoRound with 4-bit symmetric quantization', 'test quantizing a model with custom per-layer configuration using GGUF Q4_K_M mixed format', 'test running AutoRound via command line with various GGUF quantization formats like q4_k_m', 'test quantizing a vision-language model to GGUF format with and without non-text module quantization', 'test setting layer-specific quantization types for embed tokens and lm_head using set_layer_config', 'test AutoRound FP8 static quantization and export to llm_compressor format', 'test AutoRound MXFP8 quantization and save to llm_compressor format', 'test AutoRound mixed precision MXFP4 and MXFP8 quantization with AutoScheme', 'test AutoRound quantize_and_save method with llm_compressor format output', 'test AutoRound serial export packing for FP8 static and MXFP8 formats']
```

Usage

```
{'test_gguf_q4_0_quantization': 'test quantizing a model to GGUF Q4_0 format using AutoRound with 4-bit symmetric quantization', 'test_gguf_q4_k_m_layer_config': 'test quantizing a model with custom per-layer configuration using GGUF Q4_K_M mixed format', 'test_gguf_cli_all_formats': 'test running AutoRound via command line with various GGUF quantization formats like q4_k_m', 'test_vlm_gguf_quantization': 'test quantizing a vision-language model to GGUF format with and without non-text module quantization', 'test_gguf_qtype_layer_config': 'test setting layer-specific quantization types for embed tokens and lm_head using set_layer_config'}
```

## File: intel_auto-round/test/test_cpu/export/test_llmc_format.py

Prompts

```
['quantize a model and export it in auto_gptq format with 4-bit asymmetric quantization', 'quantize a model and export it in auto_round format with 4-bit symmetric quantization', 'quantize a model and export it in auto_awq format using the auto_round:auto_awq hybrid format', 'export an fp8 static quantized model with configurable static_kv_dtype for key and value projections', 'export a quantized model in llm_compressor format supporting int8 dynamic or w4a16 weight-only schemes', 'test quantizing a model to GGUF Q4_0 format using AutoRound with 4-bit symmetric quantization', 'test quantizing a model with custom per-layer configuration using GGUF Q4_K_M mixed format', 'test running AutoRound via command line with various GGUF quantization formats like q4_k_m', 'test quantizing a vision-language model to GGUF format with and without non-text module quantization', 'test setting layer-specific quantization types for embed tokens and lm_head using set_layer_config', 'test AutoRound FP8 static quantization and export to llm_compressor format', 'test AutoRound MXFP8 quantization and save to llm_compressor format', 'test AutoRound mixed precision MXFP4 and MXFP8 quantization with AutoScheme', 'test AutoRound quantize_and_save method with llm_compressor format output', 'test AutoRound serial export packing for FP8 static and MXFP8 formats']
```

Usage

```
{'test_AutoRound_FP8_static_quantization': 'test AutoRound FP8 static quantization and export to llm_compressor format', 'test_AutoRound_mxfp8_quantization': 'test AutoRound MXFP8 quantization and save to llm_compressor format', 'test_AutoRound_mixed_precision_quantization': 'test AutoRound mixed precision MXFP4 and MXFP8 quantization with AutoScheme', 'test_AutoRound_quantize_and_save': 'test AutoRound quantize_and_save method with llm_compressor format output', 'test_AutoRound_serial_export_packing': 'test AutoRound serial export packing for FP8 static and MXFP8 formats'}
```

