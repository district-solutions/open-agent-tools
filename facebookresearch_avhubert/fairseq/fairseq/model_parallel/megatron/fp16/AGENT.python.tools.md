# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/fairseq/model_parallel/megatron/fp16/fp16.py

Prompts

```
['create an FP16_Optimizer wrapping a PyTorch optimizer with static or dynamic loss scaling', 'wrap a PyTorch nn.Module with FP16_Module to automatically cast inputs and outputs between fp16 and fp32', 'convert fp32 tensors or nested tuples and lists of tensors to fp16 using fp32_to_fp16', 'convert fp16 tensors or nested tuples and lists of tensors to fp32 using fp16_to_fp32', 'clip fp32 master gradients by max norm using FP16_Optimizer clip_master_grads method', 'wrap a PyTorch network in FP16Model to convert it to half precision safely', 'convert a PyTorch network parameters and buffers to a specified dtype using convert_network', 'create FP32 master parameters from a model using prep_param_lists for mixed precision training', 'copy model gradients to master gradients using model_grads_to_master_grads for mixed precision', 'copy master parameters back to model parameters using master_params_to_model_params', 'create a DynamicLossScaler instance with custom init_scale, scale_factor, and scale_window for FP16 training', 'create a static LossScaler instance with a fixed loss scale value for FP16 training', 'test the DynamicLossScaler has_overflow method to detect inf or nan in model parameters across GPUs', 'review the DynamicLossScaler update_scale method to understand how loss scale adjusts on overflow or stable iterations', 'summarize the to_python_float helper function that safely extracts a Python float from a torch tensor']
```

Usage

```
{'create_fp16_optimizer': 'create an FP16_Optimizer wrapping a PyTorch optimizer with static or dynamic loss scaling', 'wrap_module_fp16': 'wrap a PyTorch nn.Module with FP16_Module to automatically cast inputs and outputs between fp16 and fp32', 'convert_fp32_to_fp16': 'convert fp32 tensors or nested tuples and lists of tensors to fp16 using fp32_to_fp16', 'convert_fp16_to_fp32': 'convert fp16 tensors or nested tuples and lists of tensors to fp32 using fp16_to_fp32', 'clip_master_grads': 'clip fp32 master gradients by max norm using FP16_Optimizer clip_master_grads method'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/model_parallel/megatron/fp16/fp16util.py

Prompts

```
['create an FP16_Optimizer wrapping a PyTorch optimizer with static or dynamic loss scaling', 'wrap a PyTorch nn.Module with FP16_Module to automatically cast inputs and outputs between fp16 and fp32', 'convert fp32 tensors or nested tuples and lists of tensors to fp16 using fp32_to_fp16', 'convert fp16 tensors or nested tuples and lists of tensors to fp32 using fp16_to_fp32', 'clip fp32 master gradients by max norm using FP16_Optimizer clip_master_grads method', 'wrap a PyTorch network in FP16Model to convert it to half precision safely', 'convert a PyTorch network parameters and buffers to a specified dtype using convert_network', 'create FP32 master parameters from a model using prep_param_lists for mixed precision training', 'copy model gradients to master gradients using model_grads_to_master_grads for mixed precision', 'copy master parameters back to model parameters using master_params_to_model_params', 'create a DynamicLossScaler instance with custom init_scale, scale_factor, and scale_window for FP16 training', 'create a static LossScaler instance with a fixed loss scale value for FP16 training', 'test the DynamicLossScaler has_overflow method to detect inf or nan in model parameters across GPUs', 'review the DynamicLossScaler update_scale method to understand how loss scale adjusts on overflow or stable iterations', 'summarize the to_python_float helper function that safely extracts a Python float from a torch tensor']
```

Usage

```
{'create_fp16_model': 'wrap a PyTorch network in FP16Model to convert it to half precision safely', 'convert_network_dtype': 'convert a PyTorch network parameters and buffers to a specified dtype using convert_network', 'prep_param_lists_fp32': 'create FP32 master parameters from a model using prep_param_lists for mixed precision training', 'copy_model_grads_to_master': 'copy model gradients to master gradients using model_grads_to_master_grads for mixed precision', 'copy_master_params_to_model': 'copy master parameters back to model parameters using master_params_to_model_params'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/model_parallel/megatron/fp16/loss_scaler.py

Prompts

```
['create an FP16_Optimizer wrapping a PyTorch optimizer with static or dynamic loss scaling', 'wrap a PyTorch nn.Module with FP16_Module to automatically cast inputs and outputs between fp16 and fp32', 'convert fp32 tensors or nested tuples and lists of tensors to fp16 using fp32_to_fp16', 'convert fp16 tensors or nested tuples and lists of tensors to fp32 using fp16_to_fp32', 'clip fp32 master gradients by max norm using FP16_Optimizer clip_master_grads method', 'wrap a PyTorch network in FP16Model to convert it to half precision safely', 'convert a PyTorch network parameters and buffers to a specified dtype using convert_network', 'create FP32 master parameters from a model using prep_param_lists for mixed precision training', 'copy model gradients to master gradients using model_grads_to_master_grads for mixed precision', 'copy master parameters back to model parameters using master_params_to_model_params', 'create a DynamicLossScaler instance with custom init_scale, scale_factor, and scale_window for FP16 training', 'create a static LossScaler instance with a fixed loss scale value for FP16 training', 'test the DynamicLossScaler has_overflow method to detect inf or nan in model parameters across GPUs', 'review the DynamicLossScaler update_scale method to understand how loss scale adjusts on overflow or stable iterations', 'summarize the to_python_float helper function that safely extracts a Python float from a torch tensor']
```

Usage

```
{'create_DynamicLossScaler': 'create a DynamicLossScaler instance with custom init_scale, scale_factor, and scale_window for FP16 training', 'create_LossScaler': 'create a static LossScaler instance with a fixed loss scale value for FP16 training', 'test_has_overflow': 'test the DynamicLossScaler has_overflow method to detect inf or nan in model parameters across GPUs', 'review_update_scale': 'review the DynamicLossScaler update_scale method to understand how loss scale adjusts on overflow or stable iterations', 'summarize_to_python_float': 'summarize the to_python_float helper function that safely extracts a Python float from a torch tensor'}
```

