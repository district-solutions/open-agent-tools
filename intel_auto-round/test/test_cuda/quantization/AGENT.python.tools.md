# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/test/test_cuda/quantization/test_asym.py

Prompts

```
['test asymmetric quantization with group sizes 32, 64, and 128 using AutoRound on a tiny OPT model', 'test asymmetric quantization with bit widths 2, 3, and 8 using AutoRound on a tiny OPT model', 'test asymmetric quantization export formats auto_round, auto_gptq, and gptqmodel using AutoRound on a tiny OPT model', 'run AutoRound to quantize a model with asymmetric settings and save to an output directory', 'review the TestAutoRoundAsym class that tests asymmetric quantization with varying group sizes, bits, and export formats', 'test end-to-end quantization and inference with MXFP8, MXFP4, or NVFP4 schemes on a Qwen model', 'test NVFP4 quantization with rtn on a DeepSeek V2 MoE model using AutoRound', 'test NVFP4 quantization with auto-round iterations on a DeepSeek V2 MoE model', 'test NVFP4 quantization and accuracy evaluation on a Qwen MoE model with layer config', 'review the TestAutoRound class and its NVFP4 MoE quantization test methods for correctness', 'test the pack_fp4_to_uint8 function by comparing output against the reference implementation', 'create a random tensor with E2M1 FP4 values sampled from the FLOAT_TO_E2M1 lookup table', 'pack a tensor of FP4 values into uint8 by mapping each value to its 4-bit index', 'check if the current CUDA device has more than 40 GB of total memory', 'review the parametrized test_packing_fp4 test that validates FP4 packing across Qwen weight shapes', 'test GGUF Q2_K_S quantization with torch compile enabled on a Qwen model', 'test GGUF Q2_K_S quantization with torch compile in RTN mode using iters zero', 'run AutoRound quantization with torch compile enabled and save the quantized model to a directory', 'run AutoRound quantize and save in one step with GGUF format and torch compile enabled', 'review the TestTorchCompile class that tests GGUF quantization with torch compile for correctness']
```

Usage

```
{'test_asym_group_size_with_tuning': 'test asymmetric quantization with group sizes 32, 64, and 128 using AutoRound on a tiny OPT model', 'test_asym_bits_with_tuning': 'test asymmetric quantization with bit widths 2, 3, and 8 using AutoRound on a tiny OPT model', 'test_asym_format_with_tuning': 'test asymmetric quantization export formats auto_round, auto_gptq, and gptqmodel using AutoRound on a tiny OPT model', 'run_AutoRound_quantize_and_save': 'run AutoRound to quantize a model with asymmetric settings and save to an output directory', 'review_TestAutoRoundAsym': 'review the TestAutoRoundAsym class that tests asymmetric quantization with varying group sizes, bits, and export formats'}
```

## File: intel_auto-round/test/test_cuda/quantization/test_mxfp_nvfp.py

Prompts

```
['test asymmetric quantization with group sizes 32, 64, and 128 using AutoRound on a tiny OPT model', 'test asymmetric quantization with bit widths 2, 3, and 8 using AutoRound on a tiny OPT model', 'test asymmetric quantization export formats auto_round, auto_gptq, and gptqmodel using AutoRound on a tiny OPT model', 'run AutoRound to quantize a model with asymmetric settings and save to an output directory', 'review the TestAutoRoundAsym class that tests asymmetric quantization with varying group sizes, bits, and export formats', 'test end-to-end quantization and inference with MXFP8, MXFP4, or NVFP4 schemes on a Qwen model', 'test NVFP4 quantization with rtn on a DeepSeek V2 MoE model using AutoRound', 'test NVFP4 quantization with auto-round iterations on a DeepSeek V2 MoE model', 'test NVFP4 quantization and accuracy evaluation on a Qwen MoE model with layer config', 'review the TestAutoRound class and its NVFP4 MoE quantization test methods for correctness', 'test the pack_fp4_to_uint8 function by comparing output against the reference implementation', 'create a random tensor with E2M1 FP4 values sampled from the FLOAT_TO_E2M1 lookup table', 'pack a tensor of FP4 values into uint8 by mapping each value to its 4-bit index', 'check if the current CUDA device has more than 40 GB of total memory', 'review the parametrized test_packing_fp4 test that validates FP4 packing across Qwen weight shapes', 'test GGUF Q2_K_S quantization with torch compile enabled on a Qwen model', 'test GGUF Q2_K_S quantization with torch compile in RTN mode using iters zero', 'run AutoRound quantization with torch compile enabled and save the quantized model to a directory', 'run AutoRound quantize and save in one step with GGUF format and torch compile enabled', 'review the TestTorchCompile class that tests GGUF quantization with torch compile for correctness']
```

Usage

```
{'test_e2e_quant_and_infer': 'test end-to-end quantization and inference with MXFP8, MXFP4, or NVFP4 schemes on a Qwen model', 'test_nvfp4_moe_actmax_rtn': 'test NVFP4 quantization with rtn on a DeepSeek V2 MoE model using AutoRound', 'test_nvfp4_moe_actmax_ar': 'test NVFP4 quantization with auto-round iterations on a DeepSeek V2 MoE model', 'test_qwen_moe_quant_infer': 'test NVFP4 quantization and accuracy evaluation on a Qwen MoE model with layer config', 'review_TestAutoRound': 'review the TestAutoRound class and its NVFP4 MoE quantization test methods for correctness'}
```

## File: intel_auto-round/test/test_cuda/quantization/test_packing.py

Prompts

```
['test asymmetric quantization with group sizes 32, 64, and 128 using AutoRound on a tiny OPT model', 'test asymmetric quantization with bit widths 2, 3, and 8 using AutoRound on a tiny OPT model', 'test asymmetric quantization export formats auto_round, auto_gptq, and gptqmodel using AutoRound on a tiny OPT model', 'run AutoRound to quantize a model with asymmetric settings and save to an output directory', 'review the TestAutoRoundAsym class that tests asymmetric quantization with varying group sizes, bits, and export formats', 'test end-to-end quantization and inference with MXFP8, MXFP4, or NVFP4 schemes on a Qwen model', 'test NVFP4 quantization with rtn on a DeepSeek V2 MoE model using AutoRound', 'test NVFP4 quantization with auto-round iterations on a DeepSeek V2 MoE model', 'test NVFP4 quantization and accuracy evaluation on a Qwen MoE model with layer config', 'review the TestAutoRound class and its NVFP4 MoE quantization test methods for correctness', 'test the pack_fp4_to_uint8 function by comparing output against the reference implementation', 'create a random tensor with E2M1 FP4 values sampled from the FLOAT_TO_E2M1 lookup table', 'pack a tensor of FP4 values into uint8 by mapping each value to its 4-bit index', 'check if the current CUDA device has more than 40 GB of total memory', 'review the parametrized test_packing_fp4 test that validates FP4 packing across Qwen weight shapes', 'test GGUF Q2_K_S quantization with torch compile enabled on a Qwen model', 'test GGUF Q2_K_S quantization with torch compile in RTN mode using iters zero', 'run AutoRound quantization with torch compile enabled and save the quantized model to a directory', 'run AutoRound quantize and save in one step with GGUF format and torch compile enabled', 'review the TestTorchCompile class that tests GGUF quantization with torch compile for correctness']
```

Usage

```
{'test_pack_fp4_to_uint8': 'test the pack_fp4_to_uint8 function by comparing output against the reference implementation', 'create_random_e2m1_tensor': 'create a random tensor with E2M1 FP4 values sampled from the FLOAT_TO_E2M1 lookup table', 'pack_fp4_to_uint8_old': 'pack a tensor of FP4 values into uint8 by mapping each value to its 4-bit index', 'check_cuda_memory': 'check if the current CUDA device has more than 40 GB of total memory', 'review_test_packing_fp4': 'review the parametrized test_packing_fp4 test that validates FP4 packing across Qwen weight shapes'}
```

## File: intel_auto-round/test/test_cuda/quantization/test_torch_compile.py

Prompts

```
['test asymmetric quantization with group sizes 32, 64, and 128 using AutoRound on a tiny OPT model', 'test asymmetric quantization with bit widths 2, 3, and 8 using AutoRound on a tiny OPT model', 'test asymmetric quantization export formats auto_round, auto_gptq, and gptqmodel using AutoRound on a tiny OPT model', 'run AutoRound to quantize a model with asymmetric settings and save to an output directory', 'review the TestAutoRoundAsym class that tests asymmetric quantization with varying group sizes, bits, and export formats', 'test end-to-end quantization and inference with MXFP8, MXFP4, or NVFP4 schemes on a Qwen model', 'test NVFP4 quantization with rtn on a DeepSeek V2 MoE model using AutoRound', 'test NVFP4 quantization with auto-round iterations on a DeepSeek V2 MoE model', 'test NVFP4 quantization and accuracy evaluation on a Qwen MoE model with layer config', 'review the TestAutoRound class and its NVFP4 MoE quantization test methods for correctness', 'test the pack_fp4_to_uint8 function by comparing output against the reference implementation', 'create a random tensor with E2M1 FP4 values sampled from the FLOAT_TO_E2M1 lookup table', 'pack a tensor of FP4 values into uint8 by mapping each value to its 4-bit index', 'check if the current CUDA device has more than 40 GB of total memory', 'review the parametrized test_packing_fp4 test that validates FP4 packing across Qwen weight shapes', 'test GGUF Q2_K_S quantization with torch compile enabled on a Qwen model', 'test GGUF Q2_K_S quantization with torch compile in RTN mode using iters zero', 'run AutoRound quantization with torch compile enabled and save the quantized model to a directory', 'run AutoRound quantize and save in one step with GGUF format and torch compile enabled', 'review the TestTorchCompile class that tests GGUF quantization with torch compile for correctness']
```

Usage

```
{'test_gguf_q2ks_torch_compile': 'test GGUF Q2_K_S quantization with torch compile enabled on a Qwen model', 'test_gguf_q2ks_torch_compile_iters0': 'test GGUF Q2_K_S quantization with torch compile in RTN mode using iters zero', 'run_autoround_quantize': 'run AutoRound quantization with torch compile enabled and save the quantized model to a directory', 'run_autoround_quantize_and_save': 'run AutoRound quantize and save in one step with GGUF format and torch compile enabled', 'review_test_torch_compile': 'review the TestTorchCompile class that tests GGUF quantization with torch compile for correctness'}
```

