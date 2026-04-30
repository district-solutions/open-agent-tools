# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/model_executor/layers/quantization/quark/quark.py

Prompts

```
['create a QuarkConfig from a quantization config dict with kv_cache_group and pack_method parameters', 'build a QuarkLinearMethod to apply Quark quantization to linear layers in a vLLM model', 'test whether a weight and input config matches FP8 W8A8, INT8 W8A8, MXFP4 W4A8, or OCP-MX quantization scheme', 'run QuarkKVCacheMethod to load and validate FP8 per-tensor KV cache scaling factors from Quark checkpoints', 'summarize a Quark quantization config by matching layer names to weight and input tensor quantization settings', 'create a QuarkMoEMethod instance by selecting the appropriate quantization method from a QuarkConfig for a given module and layer name', 'create quantized MoE layer weights with FP8 or INT8 parameters, scales, input scales, zero points, and bias tensors', 'process and normalize MoE weights after loading by collapsing scales, shuffling for AITER, or preparing for Marlin kernel', 'apply a quantized MoE layer forward pass using fused experts with top-k routing, quantized weights, and activation scales', 'build a FusedMoEQuantConfig object with weight scales, input scales, biases, and quantization scheme flags for MoE execution', 'test the deep_compare function to recursively compare two dictionaries or lists', 'build a check to determine if a model layer should be ignored based on name patterns and fused mappings', 'test the check_equal_or_regex_match function with exact strings and regex targets prefixed with re:', 'run quark quantization on a bfloat16 torch tensor to produce MXFP4 quantized weights and scales', 'review the _is_equal_or_regex_match function that supports exact match, regex match, and substring containment']
```

Usage

```
{'create_quark_quantization_config': 'create a QuarkConfig from a quantization config dict with kv_cache_group and pack_method parameters', 'build_quantized_linear_method': 'build a QuarkLinearMethod to apply Quark quantization to linear layers in a vLLM model', 'test_quark_quantization_scheme': 'test whether a weight and input config matches FP8 W8A8, INT8 W8A8, MXFP4 W4A8, or OCP-MX quantization scheme', 'run_kv_cache_quantization': 'run QuarkKVCacheMethod to load and validate FP8 per-tensor KV cache scaling factors from Quark checkpoints', 'summarize_quantization_config': 'summarize a Quark quantization config by matching layer names to weight and input tensor quantization settings'}
```

## File: vllm-project_vllm/vllm/model_executor/layers/quantization/quark/quark_moe.py

Prompts

```
['create a QuarkConfig from a quantization config dict with kv_cache_group and pack_method parameters', 'build a QuarkLinearMethod to apply Quark quantization to linear layers in a vLLM model', 'test whether a weight and input config matches FP8 W8A8, INT8 W8A8, MXFP4 W4A8, or OCP-MX quantization scheme', 'run QuarkKVCacheMethod to load and validate FP8 per-tensor KV cache scaling factors from Quark checkpoints', 'summarize a Quark quantization config by matching layer names to weight and input tensor quantization settings', 'create a QuarkMoEMethod instance by selecting the appropriate quantization method from a QuarkConfig for a given module and layer name', 'create quantized MoE layer weights with FP8 or INT8 parameters, scales, input scales, zero points, and bias tensors', 'process and normalize MoE weights after loading by collapsing scales, shuffling for AITER, or preparing for Marlin kernel', 'apply a quantized MoE layer forward pass using fused experts with top-k routing, quantized weights, and activation scales', 'build a FusedMoEQuantConfig object with weight scales, input scales, biases, and quantization scheme flags for MoE execution', 'test the deep_compare function to recursively compare two dictionaries or lists', 'build a check to determine if a model layer should be ignored based on name patterns and fused mappings', 'test the check_equal_or_regex_match function with exact strings and regex targets prefixed with re:', 'run quark quantization on a bfloat16 torch tensor to produce MXFP4 quantized weights and scales', 'review the _is_equal_or_regex_match function that supports exact match, regex match, and substring containment']
```

Usage

```
{'create_function_get_moe_method': 'create a QuarkMoEMethod instance by selecting the appropriate quantization method from a QuarkConfig for a given module and layer name', 'create_function_create_weights': 'create quantized MoE layer weights with FP8 or INT8 parameters, scales, input scales, zero points, and bias tensors', 'create_function_process_weights_after_loading': 'process and normalize MoE weights after loading by collapsing scales, shuffling for AITER, or preparing for Marlin kernel', 'create_function_apply': 'apply a quantized MoE layer forward pass using fused experts with top-k routing, quantized weights, and activation scales', 'create_function_get_fused_moe_quant_config': 'build a FusedMoEQuantConfig object with weight scales, input scales, biases, and quantization scheme flags for MoE execution'}
```

## File: vllm-project_vllm/vllm/model_executor/layers/quantization/quark/utils.py

Prompts

```
['create a QuarkConfig from a quantization config dict with kv_cache_group and pack_method parameters', 'build a QuarkLinearMethod to apply Quark quantization to linear layers in a vLLM model', 'test whether a weight and input config matches FP8 W8A8, INT8 W8A8, MXFP4 W4A8, or OCP-MX quantization scheme', 'run QuarkKVCacheMethod to load and validate FP8 per-tensor KV cache scaling factors from Quark checkpoints', 'summarize a Quark quantization config by matching layer names to weight and input tensor quantization settings', 'create a QuarkMoEMethod instance by selecting the appropriate quantization method from a QuarkConfig for a given module and layer name', 'create quantized MoE layer weights with FP8 or INT8 parameters, scales, input scales, zero points, and bias tensors', 'process and normalize MoE weights after loading by collapsing scales, shuffling for AITER, or preparing for Marlin kernel', 'apply a quantized MoE layer forward pass using fused experts with top-k routing, quantized weights, and activation scales', 'build a FusedMoEQuantConfig object with weight scales, input scales, biases, and quantization scheme flags for MoE execution', 'test the deep_compare function to recursively compare two dictionaries or lists', 'build a check to determine if a model layer should be ignored based on name patterns and fused mappings', 'test the check_equal_or_regex_match function with exact strings and regex targets prefixed with re:', 'run quark quantization on a bfloat16 torch tensor to produce MXFP4 quantized weights and scales', 'review the _is_equal_or_regex_match function that supports exact match, regex match, and substring containment']
```

Usage

```
{'test_deep_compare': 'test the deep_compare function to recursively compare two dictionaries or lists', 'build_should_ignore_layer': 'build a check to determine if a model layer should be ignored based on name patterns and fused mappings', 'test_check_equal_or_regex_match': 'test the check_equal_or_regex_match function with exact strings and regex targets prefixed with re:', 'run_quark_quantize_weight_to_mxfp4': 'run quark quantization on a bfloat16 torch tensor to produce MXFP4 quantized weights and scales', 'review_is_equal_or_regex_match': 'review the _is_equal_or_regex_match function that supports exact match, regex match, and substring containment'}
```

