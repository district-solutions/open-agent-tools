# Agent Python Tools

- repo: huggingface/trl
- repo_uri: https://github.com/huggingface/trl.git

## File: huggingface_trl/trl/models/activation_offloading.py

Prompts

```
['create a context manager that offloads activation tensors to CPU during forward pass and restores them during backward pass', 'get an activation offloading context manager for a model with automatic output head detection and exclusion', 'update the parameter storage pointers in an OffloadActivations manager to filter out model parameters during offloading', 'create a no-op saved tensors hook manager to disable activation offloading for a local region of code', 'get a unique key for a tensor based on its storage pointer and dtype for storage deduplication', 'unwrap a distributed model for generation with optional DeepSpeed ZeRO-3 parameter gathering and generation config override', 'prepare a model for DeepSpeed inference by initializing it with ZeRO optimization configuration from the accelerator', 'prepare a model for FSDP inference by wrapping it with FSDP version 1 or 2 sharding policy from the accelerator', 'temporarily disable gradient checkpointing on a pretrained model and restore it afterward', 'create a frozen reference model for KL-divergence regularization during RLHF training']
```

Usage

```
{'create_context_manager_offload_activations': 'create a context manager that offloads activation tensors to CPU during forward pass and restores them during backward pass', 'get_context_manager_activation_offloading': 'get an activation offloading context manager for a model with automatic output head detection and exclusion', 'update_model_params_offload_activations': 'update the parameter storage pointers in an OffloadActivations manager to filter out model parameters during offloading', 'create_no_op_manager': 'create a no-op saved tensors hook manager to disable activation offloading for a local region of code', 'get_unique_tensor_key': 'get a unique key for a tensor based on its storage pointer and dtype for storage deduplication'}
```

## File: huggingface_trl/trl/models/utils.py

Prompts

```
['create a context manager that offloads activation tensors to CPU during forward pass and restores them during backward pass', 'get an activation offloading context manager for a model with automatic output head detection and exclusion', 'update the parameter storage pointers in an OffloadActivations manager to filter out model parameters during offloading', 'create a no-op saved tensors hook manager to disable activation offloading for a local region of code', 'get a unique key for a tensor based on its storage pointer and dtype for storage deduplication', 'unwrap a distributed model for generation with optional DeepSpeed ZeRO-3 parameter gathering and generation config override', 'prepare a model for DeepSpeed inference by initializing it with ZeRO optimization configuration from the accelerator', 'prepare a model for FSDP inference by wrapping it with FSDP version 1 or 2 sharding policy from the accelerator', 'temporarily disable gradient checkpointing on a pretrained model and restore it afterward', 'create a frozen reference model for KL-divergence regularization during RLHF training']
```

Usage

```
{'unwrap_model_for_generation': 'unwrap a distributed model for generation with optional DeepSpeed ZeRO-3 parameter gathering and generation config override', 'prepare_deepspeed': 'prepare a model for DeepSpeed inference by initializing it with ZeRO optimization configuration from the accelerator', 'prepare_fsdp': 'prepare a model for FSDP inference by wrapping it with FSDP version 1 or 2 sharding policy from the accelerator', 'disable_gradient_checkpointing': 'temporarily disable gradient checkpointing on a pretrained model and restore it afterward', 'create_reference_model': 'create a frozen reference model for KL-divergence regularization during RLHF training'}
```

