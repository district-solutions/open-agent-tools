# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/model_executor/warmup/deep_gemm_warmup.py

Prompts

```
['run deep_gemm_warmup to JIT-compile DeepGEMM kernels for a vLLM model before execution', 'run deepgemm_fp8_gemm_nt_warmup to warmup FP8 GEMM NT kernels on LinearBase modules in a model', 'run deepgemm_grouped_fp8_gemm_nt_contiguous_warmup to warmup grouped FP8 GEMM kernels on FusedMoE modules', 'test _fp8_linear_may_use_deep_gemm to check if a LinearBase module can use DeepGEMM', 'test _fused_moe_grouped_gemm_may_use_deep_gemm to check if a FusedMoE module can use DeepGEMM', 'run kernel_warmup to warm up Deep GEMM and FlashInfer kernels before model execution', 'run flashinfer_autotune to benchmark and cache best FlashInfer kernel implementations', 'build kernel warmup pipeline that runs deep_gemm_warmup when Deep GEMM is supported', 'test FlashInfer attention warmup with a dummy mixed batch on non-pooling models', 'review kernel_warmup to skip autotune when disabled and warm up only FlashInfer backends']
```

Usage

```
{'run_deep_gemm_warmup': 'run deep_gemm_warmup to JIT-compile DeepGEMM kernels for a vLLM model before execution', 'run_deepgemm_fp8_gemm_nt_warmup': 'run deepgemm_fp8_gemm_nt_warmup to warmup FP8 GEMM NT kernels on LinearBase modules in a model', 'run_deepgemm_grouped_fp8_gemm_nt_contiguous_warmup': 'run deepgemm_grouped_fp8_gemm_nt_contiguous_warmup to warmup grouped FP8 GEMM kernels on FusedMoE modules', 'test_deepgemm_fp8_linear_may_use_deep_gemm': 'test _fp8_linear_may_use_deep_gemm to check if a LinearBase module can use DeepGEMM', 'test_deepgemm_fused_moe_grouped_gemm_may_use_deep_gemm': 'test _fused_moe_grouped_gemm_may_use_deep_gemm to check if a FusedMoE module can use DeepGEMM'}
```

## File: vllm-project_vllm/vllm/model_executor/warmup/kernel_warmup.py

Prompts

```
['run deep_gemm_warmup to JIT-compile DeepGEMM kernels for a vLLM model before execution', 'run deepgemm_fp8_gemm_nt_warmup to warmup FP8 GEMM NT kernels on LinearBase modules in a model', 'run deepgemm_grouped_fp8_gemm_nt_contiguous_warmup to warmup grouped FP8 GEMM kernels on FusedMoE modules', 'test _fp8_linear_may_use_deep_gemm to check if a LinearBase module can use DeepGEMM', 'test _fused_moe_grouped_gemm_may_use_deep_gemm to check if a FusedMoE module can use DeepGEMM', 'run kernel_warmup to warm up Deep GEMM and FlashInfer kernels before model execution', 'run flashinfer_autotune to benchmark and cache best FlashInfer kernel implementations', 'build kernel warmup pipeline that runs deep_gemm_warmup when Deep GEMM is supported', 'test FlashInfer attention warmup with a dummy mixed batch on non-pooling models', 'review kernel_warmup to skip autotune when disabled and warm up only FlashInfer backends']
```

Usage

```
{'run_kernel_warmup': 'run kernel_warmup to warm up Deep GEMM and FlashInfer kernels before model execution', 'run_flashinfer_autotune': 'run flashinfer_autotune to benchmark and cache best FlashInfer kernel implementations', 'build_kernel_warmup_deep_gemm': 'build kernel warmup pipeline that runs deep_gemm_warmup when Deep GEMM is supported', 'test_flashinfer_attention_warmup': 'test FlashInfer attention warmup with a dummy mixed batch on non-pooling models', 'review_kernel_warmup_worker': 'review kernel_warmup to skip autotune when disabled and warm up only FlashInfer backends'}
```

