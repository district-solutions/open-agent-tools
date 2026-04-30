# Agent Python Tools

- repo: huggingface/accelerate
- repo_uri: https://github.com/huggingface/accelerate.git

## File: huggingface_accelerate/tests/deepspeed/test_alst_ulysses_sp.py

Prompts

```
['test the DeepSpeedALSTUlyssesSPTest class to run DeepSpeed ALST Ulysses sequence parallel tests with Zero stage 2 or 3', 'run accelerate launch with deepspeed zero stage and bf16 mixed precision for sequence parallel training', 'execute an accelerate launch subprocess command asynchronously with environment variable patches for OMP threads', 'review the DeepSpeedALSTUlyssesSPTest class and its parameterized test methods for DeepSpeed integration', 'summarize the test_deepspeed_alst_ulysses_sp method that runs parameterized DeepSpeed Zero stage tests', 'test the DeepSpeedPlugin class with ZeRO stage 2 and 3 configuration options', 'test the Accelerator class integration with DeepSpeed plugin and mixed precision settings', 'test preparing a model with DeepSpeed optimizer and scheduler wrappers', 'test saving and loading DeepSpeed ZeRO stage 3 checkpoints with 16bit weights', 'test preparing a Qwen MoE model with DeepSpeed ZeRO-3 leaf module configuration', 'test that gradient accumulation boundaries are automatically handled by DeepSpeed integration with four micro steps', 'test that clip_grad_norm returns the gradient norm value when using DeepSpeed with ZeRO stage 2', 'test that Accelerator backward passes sync_gradients correctly to the DeepSpeed wrapper during accumulation steps', 'review the DeepSpeedGradientAccumulationTest class and its three test methods for gradient accumulation behavior with DeepSpeed', 'refactor the DeepSpeedPlugin configuration to adjust gradient accumulation steps, zero stage, or offload device settings', 'test selecting between zero2 and zero3 DeepSpeed plugins on an Accelerator instance', 'test that transformers deepspeed config weakref updates when switching between DeepSpeed plugins', 'test preparing multiple models with zero3 inference plugin and verify warning on tied engine', 'test training multiple models simultaneously using DeepSpeed zero2 and zero3 plugins on multi-device', 'review the DeepSpeedConfigIntegration test class for multiple DeepSpeed plugin configuration and selection patterns']
```

Usage

```
{'test_deepspeed_alst_ulysses_sp': 'test the DeepSpeedALSTUlyssesSPTest class to run DeepSpeed ALST Ulysses sequence parallel tests with Zero stage 2 or 3', 'run_accelerate_launch_deepspeed': 'run accelerate launch with deepspeed zero stage and bf16 mixed precision for sequence parallel training', 'execute_subprocess_async_cmd': 'execute an accelerate launch subprocess command asynchronously with environment variable patches for OMP threads', 'review_DeepSpeedALSTUlyssesSPTest': 'review the DeepSpeedALSTUlyssesSPTest class and its parameterized test methods for DeepSpeed integration', 'summarize_test_deepspeed_alst_ulysses_sp': 'summarize the test_deepspeed_alst_ulysses_sp method that runs parameterized DeepSpeed Zero stage tests'}
```

## File: huggingface_accelerate/tests/deepspeed/test_deepspeed.py

Prompts

```
['test the DeepSpeedALSTUlyssesSPTest class to run DeepSpeed ALST Ulysses sequence parallel tests with Zero stage 2 or 3', 'run accelerate launch with deepspeed zero stage and bf16 mixed precision for sequence parallel training', 'execute an accelerate launch subprocess command asynchronously with environment variable patches for OMP threads', 'review the DeepSpeedALSTUlyssesSPTest class and its parameterized test methods for DeepSpeed integration', 'summarize the test_deepspeed_alst_ulysses_sp method that runs parameterized DeepSpeed Zero stage tests', 'test the DeepSpeedPlugin class with ZeRO stage 2 and 3 configuration options', 'test the Accelerator class integration with DeepSpeed plugin and mixed precision settings', 'test preparing a model with DeepSpeed optimizer and scheduler wrappers', 'test saving and loading DeepSpeed ZeRO stage 3 checkpoints with 16bit weights', 'test preparing a Qwen MoE model with DeepSpeed ZeRO-3 leaf module configuration', 'test that gradient accumulation boundaries are automatically handled by DeepSpeed integration with four micro steps', 'test that clip_grad_norm returns the gradient norm value when using DeepSpeed with ZeRO stage 2', 'test that Accelerator backward passes sync_gradients correctly to the DeepSpeed wrapper during accumulation steps', 'review the DeepSpeedGradientAccumulationTest class and its three test methods for gradient accumulation behavior with DeepSpeed', 'refactor the DeepSpeedPlugin configuration to adjust gradient accumulation steps, zero stage, or offload device settings', 'test selecting between zero2 and zero3 DeepSpeed plugins on an Accelerator instance', 'test that transformers deepspeed config weakref updates when switching between DeepSpeed plugins', 'test preparing multiple models with zero3 inference plugin and verify warning on tied engine', 'test training multiple models simultaneously using DeepSpeed zero2 and zero3 plugins on multi-device', 'review the DeepSpeedConfigIntegration test class for multiple DeepSpeed plugin configuration and selection patterns']
```

Usage

```
{'test_deepspeed_plugin_config': 'test the DeepSpeedPlugin class with ZeRO stage 2 and 3 configuration options', 'test_accelerator_deepspeed_integration': 'test the Accelerator class integration with DeepSpeed plugin and mixed precision settings', 'test_prepare_deepspeed_model': 'test preparing a model with DeepSpeed optimizer and scheduler wrappers', 'test_deepspeed_checkpointing': 'test saving and loading DeepSpeed ZeRO stage 3 checkpoints with 16bit weights', 'test_deepspeed_moe_model': 'test preparing a Qwen MoE model with DeepSpeed ZeRO-3 leaf module configuration'}
```

## File: huggingface_accelerate/tests/deepspeed/test_deepspeed_gradient_accumulation.py

Prompts

```
['test the DeepSpeedALSTUlyssesSPTest class to run DeepSpeed ALST Ulysses sequence parallel tests with Zero stage 2 or 3', 'run accelerate launch with deepspeed zero stage and bf16 mixed precision for sequence parallel training', 'execute an accelerate launch subprocess command asynchronously with environment variable patches for OMP threads', 'review the DeepSpeedALSTUlyssesSPTest class and its parameterized test methods for DeepSpeed integration', 'summarize the test_deepspeed_alst_ulysses_sp method that runs parameterized DeepSpeed Zero stage tests', 'test the DeepSpeedPlugin class with ZeRO stage 2 and 3 configuration options', 'test the Accelerator class integration with DeepSpeed plugin and mixed precision settings', 'test preparing a model with DeepSpeed optimizer and scheduler wrappers', 'test saving and loading DeepSpeed ZeRO stage 3 checkpoints with 16bit weights', 'test preparing a Qwen MoE model with DeepSpeed ZeRO-3 leaf module configuration', 'test that gradient accumulation boundaries are automatically handled by DeepSpeed integration with four micro steps', 'test that clip_grad_norm returns the gradient norm value when using DeepSpeed with ZeRO stage 2', 'test that Accelerator backward passes sync_gradients correctly to the DeepSpeed wrapper during accumulation steps', 'review the DeepSpeedGradientAccumulationTest class and its three test methods for gradient accumulation behavior with DeepSpeed', 'refactor the DeepSpeedPlugin configuration to adjust gradient accumulation steps, zero stage, or offload device settings', 'test selecting between zero2 and zero3 DeepSpeed plugins on an Accelerator instance', 'test that transformers deepspeed config weakref updates when switching between DeepSpeed plugins', 'test preparing multiple models with zero3 inference plugin and verify warning on tied engine', 'test training multiple models simultaneously using DeepSpeed zero2 and zero3 plugins on multi-device', 'review the DeepSpeedConfigIntegration test class for multiple DeepSpeed plugin configuration and selection patterns']
```

Usage

```
{'test_gradient_accumulation_boundary': 'test that gradient accumulation boundaries are automatically handled by DeepSpeed integration with four micro steps', 'test_clip_grad_norm_deepspeed': 'test that clip_grad_norm returns the gradient norm value when using DeepSpeed with ZeRO stage 2', 'test_backward_sync_gradients': 'test that Accelerator backward passes sync_gradients correctly to the DeepSpeed wrapper during accumulation steps', 'review_DeepSpeedGradientAccumulationTest': 'review the DeepSpeedGradientAccumulationTest class and its three test methods for gradient accumulation behavior with DeepSpeed', 'refactor_DeepSpeedPlugin': 'refactor the DeepSpeedPlugin configuration to adjust gradient accumulation steps, zero stage, or offload device settings'}
```

## File: huggingface_accelerate/tests/deepspeed/test_deepspeed_multiple_model.py

Prompts

```
['test the DeepSpeedALSTUlyssesSPTest class to run DeepSpeed ALST Ulysses sequence parallel tests with Zero stage 2 or 3', 'run accelerate launch with deepspeed zero stage and bf16 mixed precision for sequence parallel training', 'execute an accelerate launch subprocess command asynchronously with environment variable patches for OMP threads', 'review the DeepSpeedALSTUlyssesSPTest class and its parameterized test methods for DeepSpeed integration', 'summarize the test_deepspeed_alst_ulysses_sp method that runs parameterized DeepSpeed Zero stage tests', 'test the DeepSpeedPlugin class with ZeRO stage 2 and 3 configuration options', 'test the Accelerator class integration with DeepSpeed plugin and mixed precision settings', 'test preparing a model with DeepSpeed optimizer and scheduler wrappers', 'test saving and loading DeepSpeed ZeRO stage 3 checkpoints with 16bit weights', 'test preparing a Qwen MoE model with DeepSpeed ZeRO-3 leaf module configuration', 'test that gradient accumulation boundaries are automatically handled by DeepSpeed integration with four micro steps', 'test that clip_grad_norm returns the gradient norm value when using DeepSpeed with ZeRO stage 2', 'test that Accelerator backward passes sync_gradients correctly to the DeepSpeed wrapper during accumulation steps', 'review the DeepSpeedGradientAccumulationTest class and its three test methods for gradient accumulation behavior with DeepSpeed', 'refactor the DeepSpeedPlugin configuration to adjust gradient accumulation steps, zero stage, or offload device settings', 'test selecting between zero2 and zero3 DeepSpeed plugins on an Accelerator instance', 'test that transformers deepspeed config weakref updates when switching between DeepSpeed plugins', 'test preparing multiple models with zero3 inference plugin and verify warning on tied engine', 'test training multiple models simultaneously using DeepSpeed zero2 and zero3 plugins on multi-device', 'review the DeepSpeedConfigIntegration test class for multiple DeepSpeed plugin configuration and selection patterns']
```

Usage

```
{'test_select_deepspeed_plugin': 'test selecting between zero2 and zero3 DeepSpeed plugins on an Accelerator instance', 'test_config_reference_update': 'test that transformers deepspeed config weakref updates when switching between DeepSpeed plugins', 'test_prepare_multiple_models_zero3': 'test preparing multiple models with zero3 inference plugin and verify warning on tied engine', 'test_train_multiple_models': 'test training multiple models simultaneously using DeepSpeed zero2 and zero3 plugins on multi-device', 'review_DeepSpeedConfigIntegration': 'review the DeepSpeedConfigIntegration test class for multiple DeepSpeed plugin configuration and selection patterns'}
```

