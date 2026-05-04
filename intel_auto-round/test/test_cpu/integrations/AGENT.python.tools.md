# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/test/test_cpu/integrations/test_llmc_integration.py

Prompts

```
['test applying oneshot quantization to a tiny llama model with various AutoRoundModifier recipes', 'test oneshot quantization across multiple GPU device IDs using AutoRoundModifier', 'test round-to-nearest oneshot quantization with w8a8 dynamic and static recipes', 'create an AutoRoundModifier recipe with 4-bit group-wise weight quantization ignoring lm_head', 'create a w8a8 quantization recipe with channel-wise weights and token-wise dynamic activations']
```

Usage

```
{'test_oneshot_application': 'test applying oneshot quantization to a tiny llama model with various AutoRoundModifier recipes', 'test_oneshot_with_device_ids': 'test oneshot quantization across multiple GPU device IDs using AutoRoundModifier', 'test_rtn_oneshot': 'test round-to-nearest oneshot quantization with w8a8 dynamic and static recipes', 'create_autoround_modifier_recipe': 'create an AutoRoundModifier recipe with 4-bit group-wise weight quantization ignoring lm_head', 'create_w8a8_quantization_recipe': 'create a w8a8 quantization recipe with channel-wise weights and token-wise dynamic activations'}
```

