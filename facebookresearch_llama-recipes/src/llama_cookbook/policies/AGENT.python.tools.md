# Agent Python Tools

- repo: facebookresearch/llama-recipes
- repo_uri: https://github.com/facebookresearch/llama-recipes.git

## File: facebookresearch_llama-recipes/src/llama_cookbook/policies/activation_checkpointing_functions.py

Prompts

```
['apply FSDP activation checkpointing to a Llama model to reduce memory usage during training', 'review the apply_fsdp_checkpointing function to understand how it wraps LlamaDecoderLayer modules with non-reentrant checkpointing', 'refactor apply_fsdp_checkpointing to support a different checkpoint implementation or model layer type', 'test apply_fsdp_checkpointing by applying it to a Llama model and verifying activation checkpointing is enabled', 'summarize the activation checkpointing functions module and its use of non-reentrant checkpoint wrapper for Llama models', 'create an AnyPrecisionAdamW optimizer with configurable momentum and variance dtypes for mixed precision training', 'create an AnyPrecisionAdamW optimizer with Kahan summation enabled for high precision weight updates', 'step the AnyPrecisionAdamW optimizer to perform a single optimization update on model parameters', 'review the AnyPrecisionAdamW class and its configurable dtype parameters for momentum, variance, and compensation buffers', 'refactor the AnyPrecisionAdamW step method to customize the Kahan summation or AdamW update logic', 'get a size-based FSDP auto wrap policy with a custom minimum parameter threshold', 'get a transformer auto wrap policy for Llama and Mllama decoder and vision encoder layers', 'review the get_size_policy function to understand how it configures FSDP size-based wrapping', 'review the get_llama_wrapper function to understand which transformer layer classes are registered for FSDP wrapping', 'refactor the get_llama_wrapper function to add or remove transformer layer classes from the wrap policy']
```

Usage

```
{'apply_fsdp_checkpointing': 'apply FSDP activation checkpointing to a Llama model to reduce memory usage during training', 'review_apply_fsdp_checkpointing': 'review the apply_fsdp_checkpointing function to understand how it wraps LlamaDecoderLayer modules with non-reentrant checkpointing', 'refactor_apply_fsdp_checkpointing': 'refactor apply_fsdp_checkpointing to support a different checkpoint implementation or model layer type', 'test_apply_fsdp_checkpointing': 'test apply_fsdp_checkpointing by applying it to a Llama model and verifying activation checkpointing is enabled', 'summarize_activation_checkpointing_functions': 'summarize the activation checkpointing functions module and its use of non-reentrant checkpoint wrapper for Llama models'}
```

## File: facebookresearch_llama-recipes/src/llama_cookbook/policies/anyprecision_optimizer.py

Prompts

```
['apply FSDP activation checkpointing to a Llama model to reduce memory usage during training', 'review the apply_fsdp_checkpointing function to understand how it wraps LlamaDecoderLayer modules with non-reentrant checkpointing', 'refactor apply_fsdp_checkpointing to support a different checkpoint implementation or model layer type', 'test apply_fsdp_checkpointing by applying it to a Llama model and verifying activation checkpointing is enabled', 'summarize the activation checkpointing functions module and its use of non-reentrant checkpoint wrapper for Llama models', 'create an AnyPrecisionAdamW optimizer with configurable momentum and variance dtypes for mixed precision training', 'create an AnyPrecisionAdamW optimizer with Kahan summation enabled for high precision weight updates', 'step the AnyPrecisionAdamW optimizer to perform a single optimization update on model parameters', 'review the AnyPrecisionAdamW class and its configurable dtype parameters for momentum, variance, and compensation buffers', 'refactor the AnyPrecisionAdamW step method to customize the Kahan summation or AdamW update logic', 'get a size-based FSDP auto wrap policy with a custom minimum parameter threshold', 'get a transformer auto wrap policy for Llama and Mllama decoder and vision encoder layers', 'review the get_size_policy function to understand how it configures FSDP size-based wrapping', 'review the get_llama_wrapper function to understand which transformer layer classes are registered for FSDP wrapping', 'refactor the get_llama_wrapper function to add or remove transformer layer classes from the wrap policy']
```

Usage

```
{'create_anyprecisionadamw_optimizer': 'create an AnyPrecisionAdamW optimizer with configurable momentum and variance dtypes for mixed precision training', 'create_anyprecisionadamw_with_kahan': 'create an AnyPrecisionAdamW optimizer with Kahan summation enabled for high precision weight updates', 'step_anyprecisionadamw_optimizer': 'step the AnyPrecisionAdamW optimizer to perform a single optimization update on model parameters', 'review_anyprecisionadamw_class': 'review the AnyPrecisionAdamW class and its configurable dtype parameters for momentum, variance, and compensation buffers', 'refactor_anyprecisionadamw_step': 'refactor the AnyPrecisionAdamW step method to customize the Kahan summation or AdamW update logic'}
```

## File: facebookresearch_llama-recipes/src/llama_cookbook/policies/wrapping.py

Prompts

```
['apply FSDP activation checkpointing to a Llama model to reduce memory usage during training', 'review the apply_fsdp_checkpointing function to understand how it wraps LlamaDecoderLayer modules with non-reentrant checkpointing', 'refactor apply_fsdp_checkpointing to support a different checkpoint implementation or model layer type', 'test apply_fsdp_checkpointing by applying it to a Llama model and verifying activation checkpointing is enabled', 'summarize the activation checkpointing functions module and its use of non-reentrant checkpoint wrapper for Llama models', 'create an AnyPrecisionAdamW optimizer with configurable momentum and variance dtypes for mixed precision training', 'create an AnyPrecisionAdamW optimizer with Kahan summation enabled for high precision weight updates', 'step the AnyPrecisionAdamW optimizer to perform a single optimization update on model parameters', 'review the AnyPrecisionAdamW class and its configurable dtype parameters for momentum, variance, and compensation buffers', 'refactor the AnyPrecisionAdamW step method to customize the Kahan summation or AdamW update logic', 'get a size-based FSDP auto wrap policy with a custom minimum parameter threshold', 'get a transformer auto wrap policy for Llama and Mllama decoder and vision encoder layers', 'review the get_size_policy function to understand how it configures FSDP size-based wrapping', 'review the get_llama_wrapper function to understand which transformer layer classes are registered for FSDP wrapping', 'refactor the get_llama_wrapper function to add or remove transformer layer classes from the wrap policy']
```

Usage

```
{'get_size_policy_custom_params': 'get a size-based FSDP auto wrap policy with a custom minimum parameter threshold', 'get_llama_wrapper_transformer_policy': 'get a transformer auto wrap policy for Llama and Mllama decoder and vision encoder layers', 'review_get_size_policy': 'review the get_size_policy function to understand how it configures FSDP size-based wrapping', 'review_get_llama_wrapper': 'review the get_llama_wrapper function to understand which transformer layer classes are registered for FSDP wrapping', 'refactor_get_llama_wrapper_layer_classes': 'refactor the get_llama_wrapper function to add or remove transformer layer classes from the wrap policy'}
```

