# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/auto_round/compressors/base.py

Prompts

```
['build a python module that uses BaseCompressor to quantize an LLM with W4A16 scheme and save to GGUF format', 'create a BaseCompressor instance with a model name, tokenizer, and W4A16 quantization scheme for 4-bit weight quantization', 'quantize a loaded LLM model using the quantize_and_save method and export it to the auto_round format', 'run round-to-nearest quantization on a model by setting iters to zero and calling the quantize method', 'configure per-layer quantization settings using layer_config to apply different bit widths to specific model layers', 'create an ExtraConfig instance to configure model quantization with tuning, scheme, mllm, and diffusion settings', 'configure a TuningExtraConfig dataclass to set learning rate, nblocks, and minmax tuning parameters', 'configure a SchemeExtraConfig dataclass to set weight and activation quantization bits, group size, and symmetry', 'configure an MLLMExtraConfig dataclass to set processor, image processor, and template for multimodal models', 'convert an ExtraConfig or BaseExtraConfig subclass to a dictionary using the to_dict method', 'save model module tensors to shard files with automatic memory management and size limits', 'finalize shard saving by renaming temp files and writing the weight index JSON file', 'parse a human readable size string like 5GB into bytes for shard size configuration', 'offload a saved module to the meta device to free up system RAM after saving', 'detect and deduplicate tied weights in the current shard by tracking storage pointers', 'set layer-specific quantization configs for a PyTorch model with regex matching and GGUF format support', 'get the layer configuration by GGUF quantization format for a given model architecture', 'perform a forward pass through a model block with optional automatic mixed precision', 'check if a quantization scheme uses FP8 weights and FP8 activations with standard floating point', 'create a cyclic sampler that returns shuffled index batches for model calibration data sampling']
```

Usage

```
{'build_llm_quantization_pipeline': 'build a python module that uses BaseCompressor to quantize an LLM with W4A16 scheme and save to GGUF format', 'create_compressor_instance': 'create a BaseCompressor instance with a model name, tokenizer, and W4A16 quantization scheme for 4-bit weight quantization', 'quantize_and_save_model': 'quantize a loaded LLM model using the quantize_and_save method and export it to the auto_round format', 'run_rtn_quantization': 'run round-to-nearest quantization on a model by setting iters to zero and calling the quantize method', 'configure_layer_wise_quantization': 'configure per-layer quantization settings using layer_config to apply different bit widths to specific model layers'}
```

## File: intel_auto-round/auto_round/compressors/config.py

Prompts

```
['build a python module that uses BaseCompressor to quantize an LLM with W4A16 scheme and save to GGUF format', 'create a BaseCompressor instance with a model name, tokenizer, and W4A16 quantization scheme for 4-bit weight quantization', 'quantize a loaded LLM model using the quantize_and_save method and export it to the auto_round format', 'run round-to-nearest quantization on a model by setting iters to zero and calling the quantize method', 'configure per-layer quantization settings using layer_config to apply different bit widths to specific model layers', 'create an ExtraConfig instance to configure model quantization with tuning, scheme, mllm, and diffusion settings', 'configure a TuningExtraConfig dataclass to set learning rate, nblocks, and minmax tuning parameters', 'configure a SchemeExtraConfig dataclass to set weight and activation quantization bits, group size, and symmetry', 'configure an MLLMExtraConfig dataclass to set processor, image processor, and template for multimodal models', 'convert an ExtraConfig or BaseExtraConfig subclass to a dictionary using the to_dict method', 'save model module tensors to shard files with automatic memory management and size limits', 'finalize shard saving by renaming temp files and writing the weight index JSON file', 'parse a human readable size string like 5GB into bytes for shard size configuration', 'offload a saved module to the meta device to free up system RAM after saving', 'detect and deduplicate tied weights in the current shard by tracking storage pointers', 'set layer-specific quantization configs for a PyTorch model with regex matching and GGUF format support', 'get the layer configuration by GGUF quantization format for a given model architecture', 'perform a forward pass through a model block with optional automatic mixed precision', 'check if a quantization scheme uses FP8 weights and FP8 activations with standard floating point', 'create a cyclic sampler that returns shuffled index batches for model calibration data sampling']
```

Usage

```
{'create_extra_config': 'create an ExtraConfig instance to configure model quantization with tuning, scheme, mllm, and diffusion settings', 'configure_tuning_extra_config': 'configure a TuningExtraConfig dataclass to set learning rate, nblocks, and minmax tuning parameters', 'configure_scheme_extra_config': 'configure a SchemeExtraConfig dataclass to set weight and activation quantization bits, group size, and symmetry', 'configure_mllm_extra_config': 'configure an MLLMExtraConfig dataclass to set processor, image processor, and template for multimodal models', 'convert_config_to_dict': 'convert an ExtraConfig or BaseExtraConfig subclass to a dictionary using the to_dict method'}
```

## File: intel_auto-round/auto_round/compressors/shard_writer.py

Prompts

```
['build a python module that uses BaseCompressor to quantize an LLM with W4A16 scheme and save to GGUF format', 'create a BaseCompressor instance with a model name, tokenizer, and W4A16 quantization scheme for 4-bit weight quantization', 'quantize a loaded LLM model using the quantize_and_save method and export it to the auto_round format', 'run round-to-nearest quantization on a model by setting iters to zero and calling the quantize method', 'configure per-layer quantization settings using layer_config to apply different bit widths to specific model layers', 'create an ExtraConfig instance to configure model quantization with tuning, scheme, mllm, and diffusion settings', 'configure a TuningExtraConfig dataclass to set learning rate, nblocks, and minmax tuning parameters', 'configure a SchemeExtraConfig dataclass to set weight and activation quantization bits, group size, and symmetry', 'configure an MLLMExtraConfig dataclass to set processor, image processor, and template for multimodal models', 'convert an ExtraConfig or BaseExtraConfig subclass to a dictionary using the to_dict method', 'save model module tensors to shard files with automatic memory management and size limits', 'finalize shard saving by renaming temp files and writing the weight index JSON file', 'parse a human readable size string like 5GB into bytes for shard size configuration', 'offload a saved module to the meta device to free up system RAM after saving', 'detect and deduplicate tied weights in the current shard by tracking storage pointers', 'set layer-specific quantization configs for a PyTorch model with regex matching and GGUF format support', 'get the layer configuration by GGUF quantization format for a given model architecture', 'perform a forward pass through a model block with optional automatic mixed precision', 'check if a quantization scheme uses FP8 weights and FP8 activations with standard floating point', 'create a cyclic sampler that returns shuffled index batches for model calibration data sampling']
```

Usage

```
{'save_module_tensors': 'save model module tensors to shard files with automatic memory management and size limits', 'finalize_shard_saving': 'finalize shard saving by renaming temp files and writing the weight index JSON file', 'parse_size_string': 'parse a human readable size string like 5GB into bytes for shard size configuration', 'offload_module_to_meta': 'offload a saved module to the meta device to free up system RAM after saving', 'handle_tied_weights': 'detect and deduplicate tied weights in the current shard by tracking storage pointers'}
```

## File: intel_auto-round/auto_round/compressors/utils.py

Prompts

```
['build a python module that uses BaseCompressor to quantize an LLM with W4A16 scheme and save to GGUF format', 'create a BaseCompressor instance with a model name, tokenizer, and W4A16 quantization scheme for 4-bit weight quantization', 'quantize a loaded LLM model using the quantize_and_save method and export it to the auto_round format', 'run round-to-nearest quantization on a model by setting iters to zero and calling the quantize method', 'configure per-layer quantization settings using layer_config to apply different bit widths to specific model layers', 'create an ExtraConfig instance to configure model quantization with tuning, scheme, mllm, and diffusion settings', 'configure a TuningExtraConfig dataclass to set learning rate, nblocks, and minmax tuning parameters', 'configure a SchemeExtraConfig dataclass to set weight and activation quantization bits, group size, and symmetry', 'configure an MLLMExtraConfig dataclass to set processor, image processor, and template for multimodal models', 'convert an ExtraConfig or BaseExtraConfig subclass to a dictionary using the to_dict method', 'save model module tensors to shard files with automatic memory management and size limits', 'finalize shard saving by renaming temp files and writing the weight index JSON file', 'parse a human readable size string like 5GB into bytes for shard size configuration', 'offload a saved module to the meta device to free up system RAM after saving', 'detect and deduplicate tied weights in the current shard by tracking storage pointers', 'set layer-specific quantization configs for a PyTorch model with regex matching and GGUF format support', 'get the layer configuration by GGUF quantization format for a given model architecture', 'perform a forward pass through a model block with optional automatic mixed precision', 'check if a quantization scheme uses FP8 weights and FP8 activations with standard floating point', 'create a cyclic sampler that returns shuffled index batches for model calibration data sampling']
```

Usage

```
{'set_layer_config': 'set layer-specific quantization configs for a PyTorch model with regex matching and GGUF format support', 'get_layer_config_by_gguf_format': 'get the layer configuration by GGUF quantization format for a given model architecture', 'block_forward': 'perform a forward pass through a model block with optional automatic mixed precision', 'is_wfp8afp8': 'check if a quantization scheme uses FP8 weights and FP8 activations with standard floating point', 'IndexSampler': 'create a cyclic sampler that returns shuffled index batches for model calibration data sampling'}
```

