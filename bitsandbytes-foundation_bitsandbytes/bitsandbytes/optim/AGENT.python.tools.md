# Agent Python Tools

- repo: bitsandbytes-foundation/bitsandbytes
- repo_uri: https://github.com/bitsandbytes-foundation/bitsandbytes

## File: bitsandbytes-foundation_bitsandbytes/bitsandbytes/optim/ademamix.py

Prompts

```
['create an AdEMAMix optimizer for PyTorch model parameters with configurable learning rate and betas', 'create an 8-bit quantized AdEMAMix optimizer to reduce memory usage for large models', 'create a paged 8-bit AdEMAMix optimizer for GPU memory-efficient training of large models', 'create a paged 32-bit AdEMAMix optimizer with virtual memory swapping for large models', 'create a reference AdEMAMix optimizer for verifying bitsandbytes implementation correctness', 'create a LARS optimizer for PyTorch model parameters with momentum and weight decay', 'create an 8-bit LARS optimizer to reduce memory usage for large model parameters', 'create a 32-bit LARS optimizer with explicit precision for model training', 'create a pure PyTorch LARS optimizer with layer-wise adaptive rate scaling', 'configure LARS optimizer with custom max_unorm for gradient norm clipping', 'create an 8-bit Adam optimizer for memory-efficient deep learning training', 'override optimizer hyperparameters like optim_bits or betas for specific model parameters', 'register model parameters with the global optimizer manager before moving to GPU', 'build a paged 8-bit optimizer to reduce GPU memory usage for large models', 'save and load optimizer state with FSDP-compatible quantization state wrapping']
```

Usage

```
{'create_optimizer_ademamix': 'create an AdEMAMix optimizer for PyTorch model parameters with configurable learning rate and betas', 'create_optimizer_ademamix_8bit': 'create an 8-bit quantized AdEMAMix optimizer to reduce memory usage for large models', 'create_optimizer_paged_ademamix_8bit': 'create a paged 8-bit AdEMAMix optimizer for GPU memory-efficient training of large models', 'create_optimizer_paged_ademamix_32bit': 'create a paged 32-bit AdEMAMix optimizer with virtual memory swapping for large models', 'create_reference_ademamix': 'create a reference AdEMAMix optimizer for verifying bitsandbytes implementation correctness'}
```

## File: bitsandbytes-foundation_bitsandbytes/bitsandbytes/optim/lars.py

Prompts

```
['create an AdEMAMix optimizer for PyTorch model parameters with configurable learning rate and betas', 'create an 8-bit quantized AdEMAMix optimizer to reduce memory usage for large models', 'create a paged 8-bit AdEMAMix optimizer for GPU memory-efficient training of large models', 'create a paged 32-bit AdEMAMix optimizer with virtual memory swapping for large models', 'create a reference AdEMAMix optimizer for verifying bitsandbytes implementation correctness', 'create a LARS optimizer for PyTorch model parameters with momentum and weight decay', 'create an 8-bit LARS optimizer to reduce memory usage for large model parameters', 'create a 32-bit LARS optimizer with explicit precision for model training', 'create a pure PyTorch LARS optimizer with layer-wise adaptive rate scaling', 'configure LARS optimizer with custom max_unorm for gradient norm clipping', 'create an 8-bit Adam optimizer for memory-efficient deep learning training', 'override optimizer hyperparameters like optim_bits or betas for specific model parameters', 'register model parameters with the global optimizer manager before moving to GPU', 'build a paged 8-bit optimizer to reduce GPU memory usage for large models', 'save and load optimizer state with FSDP-compatible quantization state wrapping']
```

Usage

```
{'create_optimizer_lars': 'create a LARS optimizer for PyTorch model parameters with momentum and weight decay', 'create_optimizer_lars8bit': 'create an 8-bit LARS optimizer to reduce memory usage for large model parameters', 'create_optimizer_lars32bit': 'create a 32-bit LARS optimizer with explicit precision for model training', 'create_optimizer_pytorchlars': 'create a pure PyTorch LARS optimizer with layer-wise adaptive rate scaling', 'configure_lars_max_unorm': 'configure LARS optimizer with custom max_unorm for gradient norm clipping'}
```

## File: bitsandbytes-foundation_bitsandbytes/bitsandbytes/optim/optimizer.py

Prompts

```
['create an AdEMAMix optimizer for PyTorch model parameters with configurable learning rate and betas', 'create an 8-bit quantized AdEMAMix optimizer to reduce memory usage for large models', 'create a paged 8-bit AdEMAMix optimizer for GPU memory-efficient training of large models', 'create a paged 32-bit AdEMAMix optimizer with virtual memory swapping for large models', 'create a reference AdEMAMix optimizer for verifying bitsandbytes implementation correctness', 'create a LARS optimizer for PyTorch model parameters with momentum and weight decay', 'create an 8-bit LARS optimizer to reduce memory usage for large model parameters', 'create a 32-bit LARS optimizer with explicit precision for model training', 'create a pure PyTorch LARS optimizer with layer-wise adaptive rate scaling', 'configure LARS optimizer with custom max_unorm for gradient norm clipping', 'create an 8-bit Adam optimizer for memory-efficient deep learning training', 'override optimizer hyperparameters like optim_bits or betas for specific model parameters', 'register model parameters with the global optimizer manager before moving to GPU', 'build a paged 8-bit optimizer to reduce GPU memory usage for large models', 'save and load optimizer state with FSDP-compatible quantization state wrapping']
```

Usage

```
{'create_8bit_optimizer': 'create an 8-bit Adam optimizer for memory-efficient deep learning training', 'override_optimizer_config': 'override optimizer hyperparameters like optim_bits or betas for specific model parameters', 'register_model_parameters': 'register model parameters with the global optimizer manager before moving to GPU', 'build_paged_optimizer': 'build a paged 8-bit optimizer to reduce GPU memory usage for large models', 'save_load_optimizer_state': 'save and load optimizer state with FSDP-compatible quantization state wrapping'}
```

