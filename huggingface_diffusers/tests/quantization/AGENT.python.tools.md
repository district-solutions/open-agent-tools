# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/tests/quantization/test_pipeline_level_quantization.py

Prompts

```
['test that PipelineQuantizationConfig sets bitsandbytes 4bit quantization correctly through kwargs on selected components', 'test granular per-component quantization using quant_mapping with Quanto and BitsAndBytes configs', 'test that PipelineQuantizationConfig raises errors for invalid or conflicting quantization arguments', 'test saving and loading a quantized DiffusionPipeline and verify outputs match', 'test that invalid component names in quantization config produce warnings without crashing', 'test a quantized diffusion pipeline with torch compile fullgraph mode on the transformer', 'test a quantized diffusion pipeline with torch compile and model CPU offloading enabled', 'test a quantized diffusion pipeline with torch compile and leaf-level group offloading', 'create a quantized DiffusionPipeline from pretrained stable diffusion model with a given torch dtype', 'review the QuantCompileTests base class for quantization and torch compile test methods', 'create a LoRALayer that wraps a linear module with a low-rank adapter for testing', 'test the LoRALayer forward pass by running input through the wrapped module and adapter', 'run get_memory_consumption_stat to measure peak memory allocated during a model forward pass', 'review the LoRALayer initialization to verify adapter weight initialization with small standard deviation', 'refactor get_memory_consumption_stat to support custom device or additional memory metrics']
```

Usage

```
{'test_quant_config_kwargs': 'test that PipelineQuantizationConfig sets bitsandbytes 4bit quantization correctly through kwargs on selected components', 'test_quant_config_granular': 'test granular per-component quantization using quant_mapping with Quanto and BitsAndBytes configs', 'test_quant_config_errors': 'test that PipelineQuantizationConfig raises errors for invalid or conflicting quantization arguments', 'test_quant_save_load': 'test saving and loading a quantized DiffusionPipeline and verify outputs match', 'test_quant_invalid_component': 'test that invalid component names in quantization config produce warnings without crashing'}
```

## File: huggingface_diffusers/tests/quantization/test_torch_compile_utils.py

Prompts

```
['test that PipelineQuantizationConfig sets bitsandbytes 4bit quantization correctly through kwargs on selected components', 'test granular per-component quantization using quant_mapping with Quanto and BitsAndBytes configs', 'test that PipelineQuantizationConfig raises errors for invalid or conflicting quantization arguments', 'test saving and loading a quantized DiffusionPipeline and verify outputs match', 'test that invalid component names in quantization config produce warnings without crashing', 'test a quantized diffusion pipeline with torch compile fullgraph mode on the transformer', 'test a quantized diffusion pipeline with torch compile and model CPU offloading enabled', 'test a quantized diffusion pipeline with torch compile and leaf-level group offloading', 'create a quantized DiffusionPipeline from pretrained stable diffusion model with a given torch dtype', 'review the QuantCompileTests base class for quantization and torch compile test methods', 'create a LoRALayer that wraps a linear module with a low-rank adapter for testing', 'test the LoRALayer forward pass by running input through the wrapped module and adapter', 'run get_memory_consumption_stat to measure peak memory allocated during a model forward pass', 'review the LoRALayer initialization to verify adapter weight initialization with small standard deviation', 'refactor get_memory_consumption_stat to support custom device or additional memory metrics']
```

Usage

```
{'test_torch_compile_quantized_pipeline': 'test a quantized diffusion pipeline with torch compile fullgraph mode on the transformer', 'test_torch_compile_cpu_offload': 'test a quantized diffusion pipeline with torch compile and model CPU offloading enabled', 'test_torch_compile_group_offload_leaf': 'test a quantized diffusion pipeline with torch compile and leaf-level group offloading', 'init_quantized_diffusion_pipeline': 'create a quantized DiffusionPipeline from pretrained stable diffusion model with a given torch dtype', 'review_quant_compile_tests_class': 'review the QuantCompileTests base class for quantization and torch compile test methods'}
```

## File: huggingface_diffusers/tests/quantization/utils.py

Prompts

```
['test that PipelineQuantizationConfig sets bitsandbytes 4bit quantization correctly through kwargs on selected components', 'test granular per-component quantization using quant_mapping with Quanto and BitsAndBytes configs', 'test that PipelineQuantizationConfig raises errors for invalid or conflicting quantization arguments', 'test saving and loading a quantized DiffusionPipeline and verify outputs match', 'test that invalid component names in quantization config produce warnings without crashing', 'test a quantized diffusion pipeline with torch compile fullgraph mode on the transformer', 'test a quantized diffusion pipeline with torch compile and model CPU offloading enabled', 'test a quantized diffusion pipeline with torch compile and leaf-level group offloading', 'create a quantized DiffusionPipeline from pretrained stable diffusion model with a given torch dtype', 'review the QuantCompileTests base class for quantization and torch compile test methods', 'create a LoRALayer that wraps a linear module with a low-rank adapter for testing', 'test the LoRALayer forward pass by running input through the wrapped module and adapter', 'run get_memory_consumption_stat to measure peak memory allocated during a model forward pass', 'review the LoRALayer initialization to verify adapter weight initialization with small standard deviation', 'refactor get_memory_consumption_stat to support custom device or additional memory metrics']
```

Usage

```
{'create_LoRALayer': 'create a LoRALayer that wraps a linear module with a low-rank adapter for testing', 'test_LoRALayer_forward': 'test the LoRALayer forward pass by running input through the wrapped module and adapter', 'run_get_memory_consumption_stat': 'run get_memory_consumption_stat to measure peak memory allocated during a model forward pass', 'review_LoRALayer_initialization': 'review the LoRALayer initialization to verify adapter weight initialization with small standard deviation', 'refactor_get_memory_consumption_stat': 'refactor get_memory_consumption_stat to support custom device or additional memory metrics'}
```

