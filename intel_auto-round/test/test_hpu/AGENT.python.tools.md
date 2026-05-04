# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/test/test_hpu/test_auto_round.py

Prompts

```
['run the opt-125m model quantization on HPU using AutoRound with 4-bit weights and group size 128', 'test the opt-125m model quantization on HPU in lazy mode using pytest', 'test the opt-125m model quantization on HPU in compile mode using pytest', 'test the w4a8 mixed precision quantization with fp8 activations and int4 weights using AutoRound', 'review the run_opt_125m_on_hpu function that loads opt-125m and quantizes it with AutoRound on HPU', 'check if habana frameworks torch core is available for hpu inference', 'review the is_hpex_available function that checks for habana frameworks availability', 'test auto_gptq format quantized model inference on habana hpu devices', 'test auto_round format quantized model inference on habana hpu devices', 'refactor the commented out TestAutoRound class into proper pytest format', 'test AutoRound FP8 static quantization on Qwen3-0.6B model and verify FP8 linear layers', 'run the rtn generation test that quantizes a model to FP8 and saves with llm_compressor format', 'test the check_nan_inf_in_tensor method to detect NaN or Inf values in a PyTorch tensor', 'review the TestAutoRound class and its FP8 quantization test parametrized over Qwen3 model variants', 'summarize how AutoRound quantize_and_save converts model linears to FP8QLinear with float8_e4m3fn weights', 'test DeepSeek-V2 model quantization with FP8 static attention on HPU using AutoRound', 'create a pytest fixture that loads DeepSeek-V2 model, tokenizer, and config with reduced layers', 'run AutoRound quantize_and_save with FP8_STATIC scheme and llm_compressor format for a model', 'review the quantized model q_scale tensor to verify static attention scales were collected', 'test that FP8 static attention dtype produces non-zero q_scale values on HPU devices']
```

Usage

```
{'run_opt_125m_on_hpu': 'run the opt-125m model quantization on HPU using AutoRound with 4-bit weights and group size 128', 'test_opt_125m_lazy_mode': 'test the opt-125m model quantization on HPU in lazy mode using pytest', 'test_opt_125m_compile_mode': 'test the opt-125m model quantization on HPU in compile mode using pytest', 'test_w4a8': 'test the w4a8 mixed precision quantization with fp8 activations and int4 weights using AutoRound', 'review_run_opt_125m_on_hpu': 'review the run_opt_125m_on_hpu function that loads opt-125m and quantizes it with AutoRound on HPU'}
```

## File: intel_auto-round/test/test_hpu/test_inference.py

Prompts

```
['run the opt-125m model quantization on HPU using AutoRound with 4-bit weights and group size 128', 'test the opt-125m model quantization on HPU in lazy mode using pytest', 'test the opt-125m model quantization on HPU in compile mode using pytest', 'test the w4a8 mixed precision quantization with fp8 activations and int4 weights using AutoRound', 'review the run_opt_125m_on_hpu function that loads opt-125m and quantizes it with AutoRound on HPU', 'check if habana frameworks torch core is available for hpu inference', 'review the is_hpex_available function that checks for habana frameworks availability', 'test auto_gptq format quantized model inference on habana hpu devices', 'test auto_round format quantized model inference on habana hpu devices', 'refactor the commented out TestAutoRound class into proper pytest format', 'test AutoRound FP8 static quantization on Qwen3-0.6B model and verify FP8 linear layers', 'run the rtn generation test that quantizes a model to FP8 and saves with llm_compressor format', 'test the check_nan_inf_in_tensor method to detect NaN or Inf values in a PyTorch tensor', 'review the TestAutoRound class and its FP8 quantization test parametrized over Qwen3 model variants', 'summarize how AutoRound quantize_and_save converts model linears to FP8QLinear with float8_e4m3fn weights', 'test DeepSeek-V2 model quantization with FP8 static attention on HPU using AutoRound', 'create a pytest fixture that loads DeepSeek-V2 model, tokenizer, and config with reduced layers', 'run AutoRound quantize_and_save with FP8_STATIC scheme and llm_compressor format for a model', 'review the quantized model q_scale tensor to verify static attention scales were collected', 'test that FP8 static attention dtype produces non-zero q_scale values on HPU devices']
```

Usage

```
{'check_is_hpex_available': 'check if habana frameworks torch core is available for hpu inference', 'review_is_hpex_available': 'review the is_hpex_available function that checks for habana frameworks availability', 'test_hpu_inference_autogptq': 'test auto_gptq format quantized model inference on habana hpu devices', 'test_hpu_inference_autoround': 'test auto_round format quantized model inference on habana hpu devices', 'refactor_test_autoround_class': 'refactor the commented out TestAutoRound class into proper pytest format'}
```

## File: intel_auto-round/test/test_hpu/test_quant_fp8.py

Prompts

```
['run the opt-125m model quantization on HPU using AutoRound with 4-bit weights and group size 128', 'test the opt-125m model quantization on HPU in lazy mode using pytest', 'test the opt-125m model quantization on HPU in compile mode using pytest', 'test the w4a8 mixed precision quantization with fp8 activations and int4 weights using AutoRound', 'review the run_opt_125m_on_hpu function that loads opt-125m and quantizes it with AutoRound on HPU', 'check if habana frameworks torch core is available for hpu inference', 'review the is_hpex_available function that checks for habana frameworks availability', 'test auto_gptq format quantized model inference on habana hpu devices', 'test auto_round format quantized model inference on habana hpu devices', 'refactor the commented out TestAutoRound class into proper pytest format', 'test AutoRound FP8 static quantization on Qwen3-0.6B model and verify FP8 linear layers', 'run the rtn generation test that quantizes a model to FP8 and saves with llm_compressor format', 'test the check_nan_inf_in_tensor method to detect NaN or Inf values in a PyTorch tensor', 'review the TestAutoRound class and its FP8 quantization test parametrized over Qwen3 model variants', 'summarize how AutoRound quantize_and_save converts model linears to FP8QLinear with float8_e4m3fn weights', 'test DeepSeek-V2 model quantization with FP8 static attention on HPU using AutoRound', 'create a pytest fixture that loads DeepSeek-V2 model, tokenizer, and config with reduced layers', 'run AutoRound quantize_and_save with FP8_STATIC scheme and llm_compressor format for a model', 'review the quantized model q_scale tensor to verify static attention scales were collected', 'test that FP8 static attention dtype produces non-zero q_scale values on HPU devices']
```

Usage

```
{'test_autoround_fp8_quantization': 'test AutoRound FP8 static quantization on Qwen3-0.6B model and verify FP8 linear layers', 'run_rtn_generation_test': 'run the rtn generation test that quantizes a model to FP8 and saves with llm_compressor format', 'test_check_nan_inf_in_tensor': 'test the check_nan_inf_in_tensor method to detect NaN or Inf values in a PyTorch tensor', 'review_test_autoround_class': 'review the TestAutoRound class and its FP8 quantization test parametrized over Qwen3 model variants', 'summarize_autoround_quantize_and_save': 'summarize how AutoRound quantize_and_save converts model linears to FP8QLinear with float8_e4m3fn weights'}
```

## File: intel_auto-round/test/test_hpu/test_statc_attn.py

Prompts

```
['run the opt-125m model quantization on HPU using AutoRound with 4-bit weights and group size 128', 'test the opt-125m model quantization on HPU in lazy mode using pytest', 'test the opt-125m model quantization on HPU in compile mode using pytest', 'test the w4a8 mixed precision quantization with fp8 activations and int4 weights using AutoRound', 'review the run_opt_125m_on_hpu function that loads opt-125m and quantizes it with AutoRound on HPU', 'check if habana frameworks torch core is available for hpu inference', 'review the is_hpex_available function that checks for habana frameworks availability', 'test auto_gptq format quantized model inference on habana hpu devices', 'test auto_round format quantized model inference on habana hpu devices', 'refactor the commented out TestAutoRound class into proper pytest format', 'test AutoRound FP8 static quantization on Qwen3-0.6B model and verify FP8 linear layers', 'run the rtn generation test that quantizes a model to FP8 and saves with llm_compressor format', 'test the check_nan_inf_in_tensor method to detect NaN or Inf values in a PyTorch tensor', 'review the TestAutoRound class and its FP8 quantization test parametrized over Qwen3 model variants', 'summarize how AutoRound quantize_and_save converts model linears to FP8QLinear with float8_e4m3fn weights', 'test DeepSeek-V2 model quantization with FP8 static attention on HPU using AutoRound', 'create a pytest fixture that loads DeepSeek-V2 model, tokenizer, and config with reduced layers', 'run AutoRound quantize_and_save with FP8_STATIC scheme and llm_compressor format for a model', 'review the quantized model q_scale tensor to verify static attention scales were collected', 'test that FP8 static attention dtype produces non-zero q_scale values on HPU devices']
```

Usage

```
{'test_deepseek_v2_on_hpu': 'test DeepSeek-V2 model quantization with FP8 static attention on HPU using AutoRound', 'setup_deepseekv2_fixture': 'create a pytest fixture that loads DeepSeek-V2 model, tokenizer, and config with reduced layers', 'autoround_quantize_and_save': 'run AutoRound quantize_and_save with FP8_STATIC scheme and llm_compressor format for a model', 'check_q_scale_collection': 'review the quantized model q_scale tensor to verify static attention scales were collected', 'verify_fp8_static_attention': 'test that FP8 static attention dtype produces non-zero q_scale values on HPU devices'}
```

