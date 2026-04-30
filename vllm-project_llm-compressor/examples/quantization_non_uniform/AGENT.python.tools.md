# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/examples/quantization_non_uniform/quantization_int4_int8.py

Prompts

```
['run oneshot quantization on a transformer model with a GPTQModifier recipe for mixed int4 and int8', 'build a transformer causal language model from a pretrained HuggingFace checkpoint with auto dtype', 'test loading a HuggingFace dataset split and shuffling calibration samples for quantization', 'create a dataset preprocessing pipeline that applies chat templates and tokenizes text samples', 'run dispatch_model to offload a quantized model for inference on available devices', 'run quantization on a causal LM model using GPTQ and AWQ modifiers with a calibration dataset', 'create a GPTQModifier targeting self attention projection layers with W8A8 quantization scheme', 'create an AWQModifier targeting MLP projection layers with W4A16 quantization scheme and AWQMappings', 'configure a quantization recipe combining GPTQ and AWQ modifiers for different transformer layers', 'run mixed-precision quantization with NVFP4 and FP8 dynamic schemes on a causal language model', 'create a QuantizationModifier recipe with multiple config groups for NVFP4 and FP8_DYNAMIC quantization schemes', 'build a calibration dataset from HuggingFace H4 ultrachat data with tokenized inputs for quantization', 'test a quantized model by generating text output from a prompt after dispatching the model', 'save a quantized model and tokenizer to disk in compressed-tensors format with mixed-precision config']
```

Usage

```
{'run_oneshot_quantization': 'run oneshot quantization on a transformer model with a GPTQModifier recipe for mixed int4 and int8', 'build_load_model': 'build a transformer causal language model from a pretrained HuggingFace checkpoint with auto dtype', 'test_load_dataset': 'test loading a HuggingFace dataset split and shuffling calibration samples for quantization', 'create_preprocess_dataset': 'create a dataset preprocessing pipeline that applies chat templates and tokenizes text samples', 'run_dispatch_model': 'run dispatch_model to offload a quantized model for inference on available devices'}
```

## File: vllm-project_llm-compressor/examples/quantization_non_uniform/quantization_multiple_modifiers.py

Prompts

```
['run oneshot quantization on a transformer model with a GPTQModifier recipe for mixed int4 and int8', 'build a transformer causal language model from a pretrained HuggingFace checkpoint with auto dtype', 'test loading a HuggingFace dataset split and shuffling calibration samples for quantization', 'create a dataset preprocessing pipeline that applies chat templates and tokenizes text samples', 'run dispatch_model to offload a quantized model for inference on available devices', 'run quantization on a causal LM model using GPTQ and AWQ modifiers with a calibration dataset', 'create a GPTQModifier targeting self attention projection layers with W8A8 quantization scheme', 'create an AWQModifier targeting MLP projection layers with W4A16 quantization scheme and AWQMappings', 'configure a quantization recipe combining GPTQ and AWQ modifiers for different transformer layers', 'run mixed-precision quantization with NVFP4 and FP8 dynamic schemes on a causal language model', 'create a QuantizationModifier recipe with multiple config groups for NVFP4 and FP8_DYNAMIC quantization schemes', 'build a calibration dataset from HuggingFace H4 ultrachat data with tokenized inputs for quantization', 'test a quantized model by generating text output from a prompt after dispatching the model', 'save a quantized model and tokenizer to disk in compressed-tensors format with mixed-precision config']
```

Usage

```
{'run_quantization_gptq_awq': 'run quantization on a causal LM model using GPTQ and AWQ modifiers with a calibration dataset', 'create_gptq_modifier_w8a8': 'create a GPTQModifier targeting self attention projection layers with W8A8 quantization scheme', 'create_awq_modifier_w4a16': 'create an AWQModifier targeting MLP projection layers with W4A16 quantization scheme and AWQMappings', 'run_oneshot_quantization': 'run oneshot quantization with a recipe of multiple modifiers on a model using a calibration dataset', 'configure_quantization_recipe': 'configure a quantization recipe combining GPTQ and AWQ modifiers for different transformer layers'}
```

## File: vllm-project_llm-compressor/examples/quantization_non_uniform/quantization_nvfp4_fp8.py

Prompts

```
['run oneshot quantization on a transformer model with a GPTQModifier recipe for mixed int4 and int8', 'build a transformer causal language model from a pretrained HuggingFace checkpoint with auto dtype', 'test loading a HuggingFace dataset split and shuffling calibration samples for quantization', 'create a dataset preprocessing pipeline that applies chat templates and tokenizes text samples', 'run dispatch_model to offload a quantized model for inference on available devices', 'run quantization on a causal LM model using GPTQ and AWQ modifiers with a calibration dataset', 'create a GPTQModifier targeting self attention projection layers with W8A8 quantization scheme', 'create an AWQModifier targeting MLP projection layers with W4A16 quantization scheme and AWQMappings', 'configure a quantization recipe combining GPTQ and AWQ modifiers for different transformer layers', 'run mixed-precision quantization with NVFP4 and FP8 dynamic schemes on a causal language model', 'create a QuantizationModifier recipe with multiple config groups for NVFP4 and FP8_DYNAMIC quantization schemes', 'build a calibration dataset from HuggingFace H4 ultrachat data with tokenized inputs for quantization', 'test a quantized model by generating text output from a prompt after dispatching the model', 'save a quantized model and tokenizer to disk in compressed-tensors format with mixed-precision config']
```

Usage

```
{'run_quantization_nvfp4_fp8': 'run mixed-precision quantization with NVFP4 and FP8 dynamic schemes on a causal language model', 'create_quantization_recipe': 'create a QuantizationModifier recipe with multiple config groups for NVFP4 and FP8_DYNAMIC quantization schemes', 'build_calibration_dataset': 'build a calibration dataset from HuggingFace H4 ultrachat data with tokenized inputs for quantization', 'test_quantized_model_generation': 'test a quantized model by generating text output from a prompt after dispatching the model', 'save_quantized_model_compressed': 'save a quantized model and tokenizer to disk in compressed-tensors format with mixed-precision config'}
```

