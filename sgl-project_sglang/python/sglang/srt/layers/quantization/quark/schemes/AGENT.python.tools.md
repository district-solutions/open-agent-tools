# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/layers/quantization/quark/schemes/quark_scheme.py

Prompts

```
['create weights for a Quark linear quantization scheme layer', 'create weights for a Quark MoE quantization scheme layer', 'apply weights to run the forward pass of a Quark linear quantization layer', 'apply weights to run the forward pass of a Quark MoE quantization layer', 'process and clean up weights after loading for a Quark linear quantization scheme', 'create weights for a Quark W4A4 MXFP4 quantized linear layer with per-group quantization', 'apply Quark W4A4 MXFP4 weights to perform quantized GEMM inference', 'process weights after loading for a Quark W4A4 MXFP4 quantization scheme', 'test the minimum GPU compute capability required for Quark W4A4 MXFP4', 'build a QuarkW4A4MXFP4 scheme instance with weight and input quantization specs', 'create a QuarkW4A4MXFp4MoE quantization scheme with per-group weight and input quantization configs', 'test the QuarkW4A4MXFp4MoE class method get_min_capability returns compute capability 70', 'build quantized MoE layer weights with create_weights for w13 and w2 parameters using uint8 MXFP4 storage', 'run process_weights_after_loading to shuffle weight scales and weights for MXFP4 fused MoE execution', 'run apply_weights to execute fused MoE inference with MXFP4 quantized weights and per_1x32 quantization', 'create weights for a Quark W8A8 FP8 quantized linear layer', 'apply FP8 quantized weights to run the forward pass of a Quark W8A8 linear layer', 'process and transpose FP8 weights after loading for a Quark W8A8 quantization scheme', 'get the minimum GPU compute capability required for Quark W8A8 FP8 quantization', 'initialize a Quark W8A8 FP8 quantization scheme with weight and input configurations', 'create a QuarkW8A8FP8MoE instance with weight and input config dicts for FP8 MoE quantization', 'create FP8 quantized MoE layer weights (w13, w2) and scales with per-tensor or per-channel quantization strategy', 'process and normalize MoE layer weights after loading, handling per-tensor scale merging and e4m3fnuz conversion', 'create an MoE runner with Triton backend and configured MoE runner settings for fused expert execution', 'apply quantized MoE weights to dispatched hidden states and top-k routing output for expert computation']
```

Usage

```
{'create_weights_QuarkLinearScheme': 'create weights for a Quark linear quantization scheme layer', 'create_weights_QuarkMoEScheme': 'create weights for a Quark MoE quantization scheme layer', 'apply_weights_QuarkLinearScheme': 'apply weights to run the forward pass of a Quark linear quantization layer', 'apply_weights_QuarkMoEScheme': 'apply weights to run the forward pass of a Quark MoE quantization layer', 'process_weights_after_loading_QuarkLinearScheme': 'process and clean up weights after loading for a Quark linear quantization scheme'}
```

## File: sgl-project_sglang/python/sglang/srt/layers/quantization/quark/schemes/quark_w4a4_mxfp4.py

Prompts

```
['create weights for a Quark linear quantization scheme layer', 'create weights for a Quark MoE quantization scheme layer', 'apply weights to run the forward pass of a Quark linear quantization layer', 'apply weights to run the forward pass of a Quark MoE quantization layer', 'process and clean up weights after loading for a Quark linear quantization scheme', 'create weights for a Quark W4A4 MXFP4 quantized linear layer with per-group quantization', 'apply Quark W4A4 MXFP4 weights to perform quantized GEMM inference', 'process weights after loading for a Quark W4A4 MXFP4 quantization scheme', 'test the minimum GPU compute capability required for Quark W4A4 MXFP4', 'build a QuarkW4A4MXFP4 scheme instance with weight and input quantization specs', 'create a QuarkW4A4MXFp4MoE quantization scheme with per-group weight and input quantization configs', 'test the QuarkW4A4MXFp4MoE class method get_min_capability returns compute capability 70', 'build quantized MoE layer weights with create_weights for w13 and w2 parameters using uint8 MXFP4 storage', 'run process_weights_after_loading to shuffle weight scales and weights for MXFP4 fused MoE execution', 'run apply_weights to execute fused MoE inference with MXFP4 quantized weights and per_1x32 quantization', 'create weights for a Quark W8A8 FP8 quantized linear layer', 'apply FP8 quantized weights to run the forward pass of a Quark W8A8 linear layer', 'process and transpose FP8 weights after loading for a Quark W8A8 quantization scheme', 'get the minimum GPU compute capability required for Quark W8A8 FP8 quantization', 'initialize a Quark W8A8 FP8 quantization scheme with weight and input configurations', 'create a QuarkW8A8FP8MoE instance with weight and input config dicts for FP8 MoE quantization', 'create FP8 quantized MoE layer weights (w13, w2) and scales with per-tensor or per-channel quantization strategy', 'process and normalize MoE layer weights after loading, handling per-tensor scale merging and e4m3fnuz conversion', 'create an MoE runner with Triton backend and configured MoE runner settings for fused expert execution', 'apply quantized MoE weights to dispatched hidden states and top-k routing output for expert computation']
```

Usage

```
{'create_weights_QuarkW4A4MXFP4': 'create weights for a Quark W4A4 MXFP4 quantized linear layer with per-group quantization', 'apply_weights_QuarkW4A4MXFP4': 'apply Quark W4A4 MXFP4 weights to perform quantized GEMM inference', 'process_weights_after_loading_QuarkW4A4MXFP4': 'process weights after loading for a Quark W4A4 MXFP4 quantization scheme', 'test_get_min_capability_QuarkW4A4MXFP4': 'test the minimum GPU compute capability required for Quark W4A4 MXFP4', 'build_QuarkW4A4MXFP4_instance': 'build a QuarkW4A4MXFP4 scheme instance with weight and input quantization specs'}
```

## File: sgl-project_sglang/python/sglang/srt/layers/quantization/quark/schemes/quark_w4a4_mxfp4_moe.py

Prompts

```
['create weights for a Quark linear quantization scheme layer', 'create weights for a Quark MoE quantization scheme layer', 'apply weights to run the forward pass of a Quark linear quantization layer', 'apply weights to run the forward pass of a Quark MoE quantization layer', 'process and clean up weights after loading for a Quark linear quantization scheme', 'create weights for a Quark W4A4 MXFP4 quantized linear layer with per-group quantization', 'apply Quark W4A4 MXFP4 weights to perform quantized GEMM inference', 'process weights after loading for a Quark W4A4 MXFP4 quantization scheme', 'test the minimum GPU compute capability required for Quark W4A4 MXFP4', 'build a QuarkW4A4MXFP4 scheme instance with weight and input quantization specs', 'create a QuarkW4A4MXFp4MoE quantization scheme with per-group weight and input quantization configs', 'test the QuarkW4A4MXFp4MoE class method get_min_capability returns compute capability 70', 'build quantized MoE layer weights with create_weights for w13 and w2 parameters using uint8 MXFP4 storage', 'run process_weights_after_loading to shuffle weight scales and weights for MXFP4 fused MoE execution', 'run apply_weights to execute fused MoE inference with MXFP4 quantized weights and per_1x32 quantization', 'create weights for a Quark W8A8 FP8 quantized linear layer', 'apply FP8 quantized weights to run the forward pass of a Quark W8A8 linear layer', 'process and transpose FP8 weights after loading for a Quark W8A8 quantization scheme', 'get the minimum GPU compute capability required for Quark W8A8 FP8 quantization', 'initialize a Quark W8A8 FP8 quantization scheme with weight and input configurations', 'create a QuarkW8A8FP8MoE instance with weight and input config dicts for FP8 MoE quantization', 'create FP8 quantized MoE layer weights (w13, w2) and scales with per-tensor or per-channel quantization strategy', 'process and normalize MoE layer weights after loading, handling per-tensor scale merging and e4m3fnuz conversion', 'create an MoE runner with Triton backend and configured MoE runner settings for fused expert execution', 'apply quantized MoE weights to dispatched hidden states and top-k routing output for expert computation']
```

Usage

```
{'create_class_quark_w4a4_mxfp4_moe': 'create a QuarkW4A4MXFp4MoE quantization scheme with per-group weight and input quantization configs', 'test_get_min_capability': 'test the QuarkW4A4MXFp4MoE class method get_min_capability returns compute capability 70', 'build_layer_create_weights': 'build quantized MoE layer weights with create_weights for w13 and w2 parameters using uint8 MXFP4 storage', 'run_process_weights_after_loading': 'run process_weights_after_loading to shuffle weight scales and weights for MXFP4 fused MoE execution', 'run_apply_weights_moe_inference': 'run apply_weights to execute fused MoE inference with MXFP4 quantized weights and per_1x32 quantization'}
```

## File: sgl-project_sglang/python/sglang/srt/layers/quantization/quark/schemes/quark_w8a8_fp8.py

Prompts

```
['create weights for a Quark linear quantization scheme layer', 'create weights for a Quark MoE quantization scheme layer', 'apply weights to run the forward pass of a Quark linear quantization layer', 'apply weights to run the forward pass of a Quark MoE quantization layer', 'process and clean up weights after loading for a Quark linear quantization scheme', 'create weights for a Quark W4A4 MXFP4 quantized linear layer with per-group quantization', 'apply Quark W4A4 MXFP4 weights to perform quantized GEMM inference', 'process weights after loading for a Quark W4A4 MXFP4 quantization scheme', 'test the minimum GPU compute capability required for Quark W4A4 MXFP4', 'build a QuarkW4A4MXFP4 scheme instance with weight and input quantization specs', 'create a QuarkW4A4MXFp4MoE quantization scheme with per-group weight and input quantization configs', 'test the QuarkW4A4MXFp4MoE class method get_min_capability returns compute capability 70', 'build quantized MoE layer weights with create_weights for w13 and w2 parameters using uint8 MXFP4 storage', 'run process_weights_after_loading to shuffle weight scales and weights for MXFP4 fused MoE execution', 'run apply_weights to execute fused MoE inference with MXFP4 quantized weights and per_1x32 quantization', 'create weights for a Quark W8A8 FP8 quantized linear layer', 'apply FP8 quantized weights to run the forward pass of a Quark W8A8 linear layer', 'process and transpose FP8 weights after loading for a Quark W8A8 quantization scheme', 'get the minimum GPU compute capability required for Quark W8A8 FP8 quantization', 'initialize a Quark W8A8 FP8 quantization scheme with weight and input configurations', 'create a QuarkW8A8FP8MoE instance with weight and input config dicts for FP8 MoE quantization', 'create FP8 quantized MoE layer weights (w13, w2) and scales with per-tensor or per-channel quantization strategy', 'process and normalize MoE layer weights after loading, handling per-tensor scale merging and e4m3fnuz conversion', 'create an MoE runner with Triton backend and configured MoE runner settings for fused expert execution', 'apply quantized MoE weights to dispatched hidden states and top-k routing output for expert computation']
```

Usage

```
{'create_weights_QuarkW8A8Fp8': 'create weights for a Quark W8A8 FP8 quantized linear layer', 'apply_weights_QuarkW8A8Fp8': 'apply FP8 quantized weights to run the forward pass of a Quark W8A8 linear layer', 'process_weights_after_loading_QuarkW8A8Fp8': 'process and transpose FP8 weights after loading for a Quark W8A8 quantization scheme', 'get_min_capability_QuarkW8A8Fp8': 'get the minimum GPU compute capability required for Quark W8A8 FP8 quantization', 'init_QuarkW8A8Fp8': 'initialize a Quark W8A8 FP8 quantization scheme with weight and input configurations'}
```

## File: sgl-project_sglang/python/sglang/srt/layers/quantization/quark/schemes/quark_w8a8_fp8_moe.py

Prompts

```
['create weights for a Quark linear quantization scheme layer', 'create weights for a Quark MoE quantization scheme layer', 'apply weights to run the forward pass of a Quark linear quantization layer', 'apply weights to run the forward pass of a Quark MoE quantization layer', 'process and clean up weights after loading for a Quark linear quantization scheme', 'create weights for a Quark W4A4 MXFP4 quantized linear layer with per-group quantization', 'apply Quark W4A4 MXFP4 weights to perform quantized GEMM inference', 'process weights after loading for a Quark W4A4 MXFP4 quantization scheme', 'test the minimum GPU compute capability required for Quark W4A4 MXFP4', 'build a QuarkW4A4MXFP4 scheme instance with weight and input quantization specs', 'create a QuarkW4A4MXFp4MoE quantization scheme with per-group weight and input quantization configs', 'test the QuarkW4A4MXFp4MoE class method get_min_capability returns compute capability 70', 'build quantized MoE layer weights with create_weights for w13 and w2 parameters using uint8 MXFP4 storage', 'run process_weights_after_loading to shuffle weight scales and weights for MXFP4 fused MoE execution', 'run apply_weights to execute fused MoE inference with MXFP4 quantized weights and per_1x32 quantization', 'create weights for a Quark W8A8 FP8 quantized linear layer', 'apply FP8 quantized weights to run the forward pass of a Quark W8A8 linear layer', 'process and transpose FP8 weights after loading for a Quark W8A8 quantization scheme', 'get the minimum GPU compute capability required for Quark W8A8 FP8 quantization', 'initialize a Quark W8A8 FP8 quantization scheme with weight and input configurations', 'create a QuarkW8A8FP8MoE instance with weight and input config dicts for FP8 MoE quantization', 'create FP8 quantized MoE layer weights (w13, w2) and scales with per-tensor or per-channel quantization strategy', 'process and normalize MoE layer weights after loading, handling per-tensor scale merging and e4m3fnuz conversion', 'create an MoE runner with Triton backend and configured MoE runner settings for fused expert execution', 'apply quantized MoE weights to dispatched hidden states and top-k routing output for expert computation']
```

Usage

```
{'create_class_quarkw8a8fp8moe': 'create a QuarkW8A8FP8MoE instance with weight and input config dicts for FP8 MoE quantization', 'create_method_create_weights': 'create FP8 quantized MoE layer weights (w13, w2) and scales with per-tensor or per-channel quantization strategy', 'create_method_process_weights_after_loading': 'process and normalize MoE layer weights after loading, handling per-tensor scale merging and e4m3fnuz conversion', 'create_method_create_moe_runner': 'create an MoE runner with Triton backend and configured MoE runner settings for fused expert execution', 'create_method_apply_weights': 'apply quantized MoE weights to dispatched hidden states and top-k routing output for expert computation'}
```

