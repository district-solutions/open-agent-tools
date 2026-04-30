# Agent Python Tools

- repo: huggingface/optimum-habana
- repo_uri: https://github.com/huggingface/optimum-habana

## File: huggingface_optimum-habana/optimum/habana/transformers/integrations/awq.py

Prompts

```
['replace all nn.Linear modules in a model with WQLinear_HPU for HPU-optimized AWQ quantization', 'validate that autoawq and accelerate are installed and the device_map does not include cpu or disk', 'replace linear modules with AWQ quantized versions and apply quantization scales before loading model weights', 'run post-init weight unpacking reordering and repacking for AWQ GEMM HPU layers in a model', 'parse a string like gemm gemv exllama or hpu into a GaudiAWQLinearVersion enum value', 'create a GaudiTrainerDeepSpeedConfig instance from a DeepSpeed config file or dictionary for HPU training', 'review the GaudiTrainerDeepSpeedConfig trainer_config_process method to adjust config with TrainingArguments values', 'run deepspeed_init to initialize a trainer model with DeepSpeed on HPU for training or inference', 'test the deepspeed_init function with inference mode enabled for ZeRO Stage 3', 'use unwrap_deepspeed_model to extract the underlying PyTorch module from a DeepSpeed wrapped model', 'create a GaudiFP8Linear layer with blockwise FP8 quantization for HPU inference', 'replace all linear layers in a PyTorch model with GaudiFP8Linear modules', 'get the FP8 quantization method from a model config or environment variable', 'dequantize a blockwise FP8 weight tensor back to bfloat16 precision', 'pad a weight tensor so its dimensions are multiples of a given block size', 'run the gaudi_fused_sdpa_attention_forward function with query, key, value tensors on a Habana Gaudi accelerator', 'review the gaudi_fused_sdpa_attention_forward function to understand how it wraps FusedSDPA.apply with softmax and recompute modes', 'refactor the gaudi_fused_sdpa_attention_forward function to change the FLASH_ATTENTION_FAST_SOFTMAX environment variable logic', 'test the gaudi_fused_sdpa_attention_forward function to verify the output tensor shape matches the expected dimensions', 'summarize the gaudi_fused_sdpa_attention_forward function recompute_mode logic that differs between first token and next token generation']
```

Usage

```
{'replace_linear_with_awq_hpu': 'replace all nn.Linear modules in a model with WQLinear_HPU for HPU-optimized AWQ quantization', 'validate_awq_quantizer_environment': 'validate that autoawq and accelerate are installed and the device_map does not include cpu or disk', 'process_model_before_weight_loading': 'replace linear modules with AWQ quantized versions and apply quantization scales before loading model weights', 'post_init_awq_gemm_hpu_modules': 'run post-init weight unpacking reordering and repacking for AWQ GEMM HPU layers in a model', 'parse_gaudi_awq_version': 'parse a string like gemm gemv exllama or hpu into a GaudiAWQLinearVersion enum value'}
```

## File: huggingface_optimum-habana/optimum/habana/transformers/integrations/deepspeed.py

Prompts

```
['replace all nn.Linear modules in a model with WQLinear_HPU for HPU-optimized AWQ quantization', 'validate that autoawq and accelerate are installed and the device_map does not include cpu or disk', 'replace linear modules with AWQ quantized versions and apply quantization scales before loading model weights', 'run post-init weight unpacking reordering and repacking for AWQ GEMM HPU layers in a model', 'parse a string like gemm gemv exllama or hpu into a GaudiAWQLinearVersion enum value', 'create a GaudiTrainerDeepSpeedConfig instance from a DeepSpeed config file or dictionary for HPU training', 'review the GaudiTrainerDeepSpeedConfig trainer_config_process method to adjust config with TrainingArguments values', 'run deepspeed_init to initialize a trainer model with DeepSpeed on HPU for training or inference', 'test the deepspeed_init function with inference mode enabled for ZeRO Stage 3', 'use unwrap_deepspeed_model to extract the underlying PyTorch module from a DeepSpeed wrapped model', 'create a GaudiFP8Linear layer with blockwise FP8 quantization for HPU inference', 'replace all linear layers in a PyTorch model with GaudiFP8Linear modules', 'get the FP8 quantization method from a model config or environment variable', 'dequantize a blockwise FP8 weight tensor back to bfloat16 precision', 'pad a weight tensor so its dimensions are multiples of a given block size', 'run the gaudi_fused_sdpa_attention_forward function with query, key, value tensors on a Habana Gaudi accelerator', 'review the gaudi_fused_sdpa_attention_forward function to understand how it wraps FusedSDPA.apply with softmax and recompute modes', 'refactor the gaudi_fused_sdpa_attention_forward function to change the FLASH_ATTENTION_FAST_SOFTMAX environment variable logic', 'test the gaudi_fused_sdpa_attention_forward function to verify the output tensor shape matches the expected dimensions', 'summarize the gaudi_fused_sdpa_attention_forward function recompute_mode logic that differs between first token and next token generation']
```

Usage

```
{'create_GaudiTrainerDeepSpeedConfig': 'create a GaudiTrainerDeepSpeedConfig instance from a DeepSpeed config file or dictionary for HPU training', 'review_GaudiTrainerDeepSpeedConfig_trainer_config_process': 'review the GaudiTrainerDeepSpeedConfig trainer_config_process method to adjust config with TrainingArguments values', 'run_deepspeed_init': 'run deepspeed_init to initialize a trainer model with DeepSpeed on HPU for training or inference', 'test_deepspeed_init_inference': 'test the deepspeed_init function with inference mode enabled for ZeRO Stage 3', 'use_unwrap_deepspeed_model': 'use unwrap_deepspeed_model to extract the underlying PyTorch module from a DeepSpeed wrapped model'}
```

## File: huggingface_optimum-habana/optimum/habana/transformers/integrations/finegrained_fp8.py

Prompts

```
['replace all nn.Linear modules in a model with WQLinear_HPU for HPU-optimized AWQ quantization', 'validate that autoawq and accelerate are installed and the device_map does not include cpu or disk', 'replace linear modules with AWQ quantized versions and apply quantization scales before loading model weights', 'run post-init weight unpacking reordering and repacking for AWQ GEMM HPU layers in a model', 'parse a string like gemm gemv exllama or hpu into a GaudiAWQLinearVersion enum value', 'create a GaudiTrainerDeepSpeedConfig instance from a DeepSpeed config file or dictionary for HPU training', 'review the GaudiTrainerDeepSpeedConfig trainer_config_process method to adjust config with TrainingArguments values', 'run deepspeed_init to initialize a trainer model with DeepSpeed on HPU for training or inference', 'test the deepspeed_init function with inference mode enabled for ZeRO Stage 3', 'use unwrap_deepspeed_model to extract the underlying PyTorch module from a DeepSpeed wrapped model', 'create a GaudiFP8Linear layer with blockwise FP8 quantization for HPU inference', 'replace all linear layers in a PyTorch model with GaudiFP8Linear modules', 'get the FP8 quantization method from a model config or environment variable', 'dequantize a blockwise FP8 weight tensor back to bfloat16 precision', 'pad a weight tensor so its dimensions are multiples of a given block size', 'run the gaudi_fused_sdpa_attention_forward function with query, key, value tensors on a Habana Gaudi accelerator', 'review the gaudi_fused_sdpa_attention_forward function to understand how it wraps FusedSDPA.apply with softmax and recompute modes', 'refactor the gaudi_fused_sdpa_attention_forward function to change the FLASH_ATTENTION_FAST_SOFTMAX environment variable logic', 'test the gaudi_fused_sdpa_attention_forward function to verify the output tensor shape matches the expected dimensions', 'summarize the gaudi_fused_sdpa_attention_forward function recompute_mode logic that differs between first token and next token generation']
```

Usage

```
{'create_GaudiFP8Linear': 'create a GaudiFP8Linear layer with blockwise FP8 quantization for HPU inference', 'replace_with_fp8_linear': 'replace all linear layers in a PyTorch model with GaudiFP8Linear modules', 'get_fp8_method': 'get the FP8 quantization method from a model config or environment variable', 'dequant_block_fp8_weight_naive': 'dequantize a blockwise FP8 weight tensor back to bfloat16 precision', 'pad_weight': 'pad a weight tensor so its dimensions are multiples of a given block size'}
```

## File: huggingface_optimum-habana/optimum/habana/transformers/integrations/gaudi_fused_sdpa_attention.py

Prompts

```
['replace all nn.Linear modules in a model with WQLinear_HPU for HPU-optimized AWQ quantization', 'validate that autoawq and accelerate are installed and the device_map does not include cpu or disk', 'replace linear modules with AWQ quantized versions and apply quantization scales before loading model weights', 'run post-init weight unpacking reordering and repacking for AWQ GEMM HPU layers in a model', 'parse a string like gemm gemv exllama or hpu into a GaudiAWQLinearVersion enum value', 'create a GaudiTrainerDeepSpeedConfig instance from a DeepSpeed config file or dictionary for HPU training', 'review the GaudiTrainerDeepSpeedConfig trainer_config_process method to adjust config with TrainingArguments values', 'run deepspeed_init to initialize a trainer model with DeepSpeed on HPU for training or inference', 'test the deepspeed_init function with inference mode enabled for ZeRO Stage 3', 'use unwrap_deepspeed_model to extract the underlying PyTorch module from a DeepSpeed wrapped model', 'create a GaudiFP8Linear layer with blockwise FP8 quantization for HPU inference', 'replace all linear layers in a PyTorch model with GaudiFP8Linear modules', 'get the FP8 quantization method from a model config or environment variable', 'dequantize a blockwise FP8 weight tensor back to bfloat16 precision', 'pad a weight tensor so its dimensions are multiples of a given block size', 'run the gaudi_fused_sdpa_attention_forward function with query, key, value tensors on a Habana Gaudi accelerator', 'review the gaudi_fused_sdpa_attention_forward function to understand how it wraps FusedSDPA.apply with softmax and recompute modes', 'refactor the gaudi_fused_sdpa_attention_forward function to change the FLASH_ATTENTION_FAST_SOFTMAX environment variable logic', 'test the gaudi_fused_sdpa_attention_forward function to verify the output tensor shape matches the expected dimensions', 'summarize the gaudi_fused_sdpa_attention_forward function recompute_mode logic that differs between first token and next token generation']
```

Usage

```
{'run_gaudi_fused_sdpa_attention': 'run the gaudi_fused_sdpa_attention_forward function with query, key, value tensors on a Habana Gaudi accelerator', 'review_fused_sdpa_forward': 'review the gaudi_fused_sdpa_attention_forward function to understand how it wraps FusedSDPA.apply with softmax and recompute modes', 'refactor_attention_softmax_mode': 'refactor the gaudi_fused_sdpa_attention_forward function to change the FLASH_ATTENTION_FAST_SOFTMAX environment variable logic', 'test_fused_sdpa_output_shape': 'test the gaudi_fused_sdpa_attention_forward function to verify the output tensor shape matches the expected dimensions', 'summarize_recompute_mode_logic': 'summarize the gaudi_fused_sdpa_attention_forward function recompute_mode logic that differs between first token and next token generation'}
```

