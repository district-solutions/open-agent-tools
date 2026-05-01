# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/vaultgemma/test_modeling_vaultgemma.py

Prompts

```
['test the VaultGemma model by generating text in bf16 precision using AutoModelForCausalLM and model.generate', 'test the VaultGemma model using the HuggingFace pipeline API for text generation with bf16 precision', 'test VaultGemma generation beyond the sliding window using hybrid cache with multiple attention implementations', 'test VaultGemma generation with dynamic cache implementation and verify DynamicSlidingWindowLayer and DynamicLayer types', 'test exporting VaultGemma with static cache using TorchExportableModuleForDecoderOnlyLM for ExecuTorch deployment']
```

Usage

```
{'test_vaultgemma_model_bf16': 'test the VaultGemma model by generating text in bf16 precision using AutoModelForCausalLM and model.generate', 'test_vaultgemma_pipeline_bf16': 'test the VaultGemma model using the HuggingFace pipeline API for text generation with bf16 precision', 'test_vaultgemma_sliding_window': 'test VaultGemma generation beyond the sliding window using hybrid cache with multiple attention implementations', 'test_vaultgemma_dynamic_cache': 'test VaultGemma generation with dynamic cache implementation and verify DynamicSlidingWindowLayer and DynamicLayer types', 'test_vaultgemma_static_cache_export': 'test exporting VaultGemma with static cache using TorchExportableModuleForDecoderOnlyLM for ExecuTorch deployment'}
```

