# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/test/test_xpu/test_autoround.py

Prompts

```
['quantize a causal LM model using AutoRound with GPTQ format and save to disk', 'quantize a causal LM model using AutoRound with AWQ format and save to disk', 'quantize a model using AutoRound with schemes like W4A16, W8A16, MXFP4, or NVFP4', 'quantize a vision language model like Qwen2-VL using AutoRound with W4A16 scheme', 'quantize the lm_head layer of a model using AutoRound with custom layer_config settings', 'test applying AutoRound quantization recipes to a TinyLlama model on Intel XPU via oneshot', 'test oneshot quantization across multiple Intel XPU devices using device_ids parameter', 'test round-to-none quantization with w8a8 dynamic and static recipes on Intel XPU', 'create an AutoRoundModifier recipe with 4-bit group-wise weight quantization and lm_head ignored', 'run oneshot quantization on a HuggingFace model using a calibration dataset and AutoRound recipe', 'test that patch_xpu_sdpa_drop_causal_mask correctly identifies and replaces causal masks on XPU devices', 'run the XPU SDPA patch test to verify causal mask replacement produces correct attention output', 'test scaled dot product attention with a causal mask on XPU and compare to is_causal=True output', 'test scaled dot product attention with a non-causal mask on XPU to verify it is not patched', 'verify that torch XPU is available before running the SDPA patch test']
```

Usage

```
{'quantize_model_gptq_format': 'quantize a causal LM model using AutoRound with GPTQ format and save to disk', 'quantize_model_awq_format': 'quantize a causal LM model using AutoRound with AWQ format and save to disk', 'quantize_model_scheme': 'quantize a model using AutoRound with schemes like W4A16, W8A16, MXFP4, or NVFP4', 'quantize_vlm_model': 'quantize a vision language model like Qwen2-VL using AutoRound with W4A16 scheme', 'quantize_lm_head': 'quantize the lm_head layer of a model using AutoRound with custom layer_config settings'}
```

## File: intel_auto-round/test/test_xpu/test_llmc_integration.py

Prompts

```
['quantize a causal LM model using AutoRound with GPTQ format and save to disk', 'quantize a causal LM model using AutoRound with AWQ format and save to disk', 'quantize a model using AutoRound with schemes like W4A16, W8A16, MXFP4, or NVFP4', 'quantize a vision language model like Qwen2-VL using AutoRound with W4A16 scheme', 'quantize the lm_head layer of a model using AutoRound with custom layer_config settings', 'test applying AutoRound quantization recipes to a TinyLlama model on Intel XPU via oneshot', 'test oneshot quantization across multiple Intel XPU devices using device_ids parameter', 'test round-to-none quantization with w8a8 dynamic and static recipes on Intel XPU', 'create an AutoRoundModifier recipe with 4-bit group-wise weight quantization and lm_head ignored', 'run oneshot quantization on a HuggingFace model using a calibration dataset and AutoRound recipe', 'test that patch_xpu_sdpa_drop_causal_mask correctly identifies and replaces causal masks on XPU devices', 'run the XPU SDPA patch test to verify causal mask replacement produces correct attention output', 'test scaled dot product attention with a causal mask on XPU and compare to is_causal=True output', 'test scaled dot product attention with a non-causal mask on XPU to verify it is not patched', 'verify that torch XPU is available before running the SDPA patch test']
```

Usage

```
{'test_oneshot_application': 'test applying AutoRound quantization recipes to a TinyLlama model on Intel XPU via oneshot', 'test_oneshot_with_device_ids': 'test oneshot quantization across multiple Intel XPU devices using device_ids parameter', 'test_rtn_oneshot': 'test round-to-none quantization with w8a8 dynamic and static recipes on Intel XPU', 'create_autoround_modifier_recipe': 'create an AutoRoundModifier recipe with 4-bit group-wise weight quantization and lm_head ignored', 'run_oneshot_quantization': 'run oneshot quantization on a HuggingFace model using a calibration dataset and AutoRound recipe'}
```

## File: intel_auto-round/test/test_xpu/test_xpu_sdpa_patch.py

Prompts

```
['quantize a causal LM model using AutoRound with GPTQ format and save to disk', 'quantize a causal LM model using AutoRound with AWQ format and save to disk', 'quantize a model using AutoRound with schemes like W4A16, W8A16, MXFP4, or NVFP4', 'quantize a vision language model like Qwen2-VL using AutoRound with W4A16 scheme', 'quantize the lm_head layer of a model using AutoRound with custom layer_config settings', 'test applying AutoRound quantization recipes to a TinyLlama model on Intel XPU via oneshot', 'test oneshot quantization across multiple Intel XPU devices using device_ids parameter', 'test round-to-none quantization with w8a8 dynamic and static recipes on Intel XPU', 'create an AutoRoundModifier recipe with 4-bit group-wise weight quantization and lm_head ignored', 'run oneshot quantization on a HuggingFace model using a calibration dataset and AutoRound recipe', 'test that patch_xpu_sdpa_drop_causal_mask correctly identifies and replaces causal masks on XPU devices', 'run the XPU SDPA patch test to verify causal mask replacement produces correct attention output', 'test scaled dot product attention with a causal mask on XPU and compare to is_causal=True output', 'test scaled dot product attention with a non-causal mask on XPU to verify it is not patched', 'verify that torch XPU is available before running the SDPA patch test']
```

Usage

```
{'test_patch_xpu_sdpa_drop_causal_mask': 'test that patch_xpu_sdpa_drop_causal_mask correctly identifies and replaces causal masks on XPU devices', 'run_xpu_sdpa_patch_test': 'run the XPU SDPA patch test to verify causal mask replacement produces correct attention output', 'test_scaled_dot_product_attention_with_causal_mask': 'test scaled dot product attention with a causal mask on XPU and compare to is_causal=True output', 'test_scaled_dot_product_attention_with_non_causal_mask': 'test scaled dot product attention with a non-causal mask on XPU to verify it is not patched', 'verify_xpu_availability': 'verify that torch XPU is available before running the SDPA patch test'}
```

