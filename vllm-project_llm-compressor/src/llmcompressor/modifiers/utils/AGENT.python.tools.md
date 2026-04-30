# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/src/llmcompressor/modifiers/utils/helpers.py

Prompts

```
['update fused layer weight global scales for NVFP4 quantization on qkv and gate_up_proj layers', 'test the update_fused_layer_weight_global_scales function with a submodule containing q_proj, k_proj, and v_proj layers', 'review the update_fused_layer_weight_global_scales function to ensure global scales are fused for tensor group quantized layers', 'refactor the update_fused_layer_weight_global_scales function to support additional fused layer patterns', 'summarize the update_fused_layer_weight_global_scales function that aligns global scales for fused attention and MLP layers', 'create a HooksMixin instance to manage PyTorch hook registration, disabling, and removal on modules or parameters', 'register a forward hook on a PyTorch module or parameter via HooksMixin with disable support', 'register a query, key, or value hook on a PyTorch module using compressed_tensors hook functions', 'disable all registered hooks across modifiers temporarily using the HooksMixin.disable_hooks context manager', 'remove all or specific registered hooks from a HooksMixin instance by calling remove_hooks on handles', 'run apply_pad_mask_to_batch to zero out padding tokens from input_ids using the attention_mask in a batch', 'test is_moe_model to detect if a PyTorch model is a mixture of experts model by checking module names and config attributes', 'refactor apply_pad_mask_to_batch to support additional tensor keys beyond input_ids and decoder_input_ids', 'review is_moe_model to verify MoE detection covers all transformer-based MoE architectures', 'create a wrapper around apply_pad_mask_to_batch that processes a list of batches for GPTQ hessian calculation']
```

Usage

```
{'update_fused_layer_weight_global_scales': 'update fused layer weight global scales for NVFP4 quantization on qkv and gate_up_proj layers', 'test_update_fused_layer_weight_global_scales': 'test the update_fused_layer_weight_global_scales function with a submodule containing q_proj, k_proj, and v_proj layers', 'review_update_fused_layer_weight_global_scales': 'review the update_fused_layer_weight_global_scales function to ensure global scales are fused for tensor group quantized layers', 'refactor_update_fused_layer_weight_global_scales': 'refactor the update_fused_layer_weight_global_scales function to support additional fused layer patterns', 'summarize_update_fused_layer_weight_global_scales': 'summarize the update_fused_layer_weight_global_scales function that aligns global scales for fused attention and MLP layers'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/modifiers/utils/hooks.py

Prompts

```
['update fused layer weight global scales for NVFP4 quantization on qkv and gate_up_proj layers', 'test the update_fused_layer_weight_global_scales function with a submodule containing q_proj, k_proj, and v_proj layers', 'review the update_fused_layer_weight_global_scales function to ensure global scales are fused for tensor group quantized layers', 'refactor the update_fused_layer_weight_global_scales function to support additional fused layer patterns', 'summarize the update_fused_layer_weight_global_scales function that aligns global scales for fused attention and MLP layers', 'create a HooksMixin instance to manage PyTorch hook registration, disabling, and removal on modules or parameters', 'register a forward hook on a PyTorch module or parameter via HooksMixin with disable support', 'register a query, key, or value hook on a PyTorch module using compressed_tensors hook functions', 'disable all registered hooks across modifiers temporarily using the HooksMixin.disable_hooks context manager', 'remove all or specific registered hooks from a HooksMixin instance by calling remove_hooks on handles', 'run apply_pad_mask_to_batch to zero out padding tokens from input_ids using the attention_mask in a batch', 'test is_moe_model to detect if a PyTorch model is a mixture of experts model by checking module names and config attributes', 'refactor apply_pad_mask_to_batch to support additional tensor keys beyond input_ids and decoder_input_ids', 'review is_moe_model to verify MoE detection covers all transformer-based MoE architectures', 'create a wrapper around apply_pad_mask_to_batch that processes a list of batches for GPTQ hessian calculation']
```

Usage

```
{'create_hooks_mixin': 'create a HooksMixin instance to manage PyTorch hook registration, disabling, and removal on modules or parameters', 'register_hook_forward': 'register a forward hook on a PyTorch module or parameter via HooksMixin with disable support', 'register_hook_query_key_value': 'register a query, key, or value hook on a PyTorch module using compressed_tensors hook functions', 'disable_hooks_context': 'disable all registered hooks across modifiers temporarily using the HooksMixin.disable_hooks context manager', 'remove_hooks': 'remove all or specific registered hooks from a HooksMixin instance by calling remove_hooks on handles'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/modifiers/utils/pytorch_helpers.py

Prompts

```
['update fused layer weight global scales for NVFP4 quantization on qkv and gate_up_proj layers', 'test the update_fused_layer_weight_global_scales function with a submodule containing q_proj, k_proj, and v_proj layers', 'review the update_fused_layer_weight_global_scales function to ensure global scales are fused for tensor group quantized layers', 'refactor the update_fused_layer_weight_global_scales function to support additional fused layer patterns', 'summarize the update_fused_layer_weight_global_scales function that aligns global scales for fused attention and MLP layers', 'create a HooksMixin instance to manage PyTorch hook registration, disabling, and removal on modules or parameters', 'register a forward hook on a PyTorch module or parameter via HooksMixin with disable support', 'register a query, key, or value hook on a PyTorch module using compressed_tensors hook functions', 'disable all registered hooks across modifiers temporarily using the HooksMixin.disable_hooks context manager', 'remove all or specific registered hooks from a HooksMixin instance by calling remove_hooks on handles', 'run apply_pad_mask_to_batch to zero out padding tokens from input_ids using the attention_mask in a batch', 'test is_moe_model to detect if a PyTorch model is a mixture of experts model by checking module names and config attributes', 'refactor apply_pad_mask_to_batch to support additional tensor keys beyond input_ids and decoder_input_ids', 'review is_moe_model to verify MoE detection covers all transformer-based MoE architectures', 'create a wrapper around apply_pad_mask_to_batch that processes a list of batches for GPTQ hessian calculation']
```

Usage

```
{'run_apply_pad_mask_to_batch': 'run apply_pad_mask_to_batch to zero out padding tokens from input_ids using the attention_mask in a batch', 'test_is_moe_model': 'test is_moe_model to detect if a PyTorch model is a mixture of experts model by checking module names and config attributes', 'refactor_apply_pad_mask_to_batch': 'refactor apply_pad_mask_to_batch to support additional tensor keys beyond input_ids and decoder_input_ids', 'review_is_moe_model': 'review is_moe_model to verify MoE detection covers all transformer-based MoE architectures', 'create_apply_pad_mask_to_batch': 'create a wrapper around apply_pad_mask_to_batch that processes a list of batches for GPTQ hessian calculation'}
```

