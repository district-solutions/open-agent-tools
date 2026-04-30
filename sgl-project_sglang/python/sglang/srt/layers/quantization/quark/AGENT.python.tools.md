# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/layers/quantization/quark/quark.py

Prompts

```
['create a QuarkConfig from a quantization config dict with kv_cache_group and pack_method parameters', 'get a QuarkLinearMethod instance for applying Quark quantization to linear layers', 'get a QuarkFusedMoEMethod instance for applying Quark quantization to fused MoE layers', 'apply QuarkLinearMethod forward pass to a quantized linear layer with input tensor and optional bias', 'create a QuarkKVCacheMethod to load kv-cache scaling factors from Quark checkpoints with fp8_e4m3 per_tensor quantization', 'test the deep_compare function to compare two nested dicts or lists for equality', 'test the should_ignore_layer function to check if a layer name matches ignore patterns or fused shard mappings', 'test the check_equal_or_regex_match function to match layer names against exact strings or re: regex targets', 'run mxfp4_to_f32 to unpack packed uint8 mxfp4 tensor values back to float32', 'run quark_post_load_weights to split and quantize bf16 or uint8 weight tensors into mxfp4 w_kc and w_vc shards']
```

Usage

```
{'create_QuarkConfig': 'create a QuarkConfig from a quantization config dict with kv_cache_group and pack_method parameters', 'get_QuarkLinearMethod': 'get a QuarkLinearMethod instance for applying Quark quantization to linear layers', 'get_QuarkFusedMoEMethod': 'get a QuarkFusedMoEMethod instance for applying Quark quantization to fused MoE layers', 'apply_QuarkLinearMethod': 'apply QuarkLinearMethod forward pass to a quantized linear layer with input tensor and optional bias', 'create_QuarkKVCacheMethod': 'create a QuarkKVCacheMethod to load kv-cache scaling factors from Quark checkpoints with fp8_e4m3 per_tensor quantization'}
```

## File: sgl-project_sglang/python/sglang/srt/layers/quantization/quark/utils.py

Prompts

```
['create a QuarkConfig from a quantization config dict with kv_cache_group and pack_method parameters', 'get a QuarkLinearMethod instance for applying Quark quantization to linear layers', 'get a QuarkFusedMoEMethod instance for applying Quark quantization to fused MoE layers', 'apply QuarkLinearMethod forward pass to a quantized linear layer with input tensor and optional bias', 'create a QuarkKVCacheMethod to load kv-cache scaling factors from Quark checkpoints with fp8_e4m3 per_tensor quantization', 'test the deep_compare function to compare two nested dicts or lists for equality', 'test the should_ignore_layer function to check if a layer name matches ignore patterns or fused shard mappings', 'test the check_equal_or_regex_match function to match layer names against exact strings or re: regex targets', 'run mxfp4_to_f32 to unpack packed uint8 mxfp4 tensor values back to float32', 'run quark_post_load_weights to split and quantize bf16 or uint8 weight tensors into mxfp4 w_kc and w_vc shards']
```

Usage

```
{'test_deep_compare': 'test the deep_compare function to compare two nested dicts or lists for equality', 'test_should_ignore_layer': 'test the should_ignore_layer function to check if a layer name matches ignore patterns or fused shard mappings', 'test_check_equal_or_regex_match': 'test the check_equal_or_regex_match function to match layer names against exact strings or re: regex targets', 'run_mxfp4_to_f32': 'run mxfp4_to_f32 to unpack packed uint8 mxfp4 tensor values back to float32', 'run_quark_post_load_weights': 'run quark_post_load_weights to split and quantize bf16 or uint8 weight tensors into mxfp4 w_kc and w_vc shards'}
```

