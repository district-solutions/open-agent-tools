# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/fairseq/model_parallel/megatron/fp16/fp16.py

Prompts

```
['create an FP16_Optimizer wrapping a PyTorch optimizer with static or dynamic loss scaling', 'wrap a PyTorch nn.Module with FP16_Module to automatically cast inputs to fp16 and outputs to fp32', 'run the FP16_Optimizer backward pass on a loss tensor with automatic loss scaling and gradient copying', 'convert fp32 tensors, parameters, or nested tuples and lists to fp16 using fp32_to_fp16', 'clip the fp32 master gradients of an FP16_Optimizer by a specified max norm', 'wrap a PyTorch model in FP16Model to convert it to half precision safely', "convert a PyTorch network's parameters and buffers to a specified dtype", 'create FP32 master parameters from a model for mixed precision training', 'copy model gradients to master gradients for mixed precision optimization', 'copy FP32 master parameters back to the FP16 model parameters', 'create a DynamicLossScaler instance with custom init_scale, scale_factor, and scale_window parameters', 'create a static LossScaler instance with a fixed loss scale value for FP16 training', 'test the has_overflow method to check if model parameters contain inf or nan gradients', 'test the update_scale method to adjust loss scale based on gradient overflow detection', 'review the DynamicLossScaler backward method that scales loss and calls backward for FP16 training']
```

Usage

```
{'create_FP16_Optimizer': 'create an FP16_Optimizer wrapping a PyTorch optimizer with static or dynamic loss scaling', 'wrap_model_with_FP16_Module': 'wrap a PyTorch nn.Module with FP16_Module to automatically cast inputs to fp16 and outputs to fp32', 'run_FP16_Optimizer_backward': 'run the FP16_Optimizer backward pass on a loss tensor with automatic loss scaling and gradient copying', 'convert_fp32_to_fp16': 'convert fp32 tensors, parameters, or nested tuples and lists to fp16 using fp32_to_fp16', 'clip_FP16_Optimizer_master_grads': 'clip the fp32 master gradients of an FP16_Optimizer by a specified max norm'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/model_parallel/megatron/fp16/fp16util.py

Prompts

```
['create an FP16_Optimizer wrapping a PyTorch optimizer with static or dynamic loss scaling', 'wrap a PyTorch nn.Module with FP16_Module to automatically cast inputs to fp16 and outputs to fp32', 'run the FP16_Optimizer backward pass on a loss tensor with automatic loss scaling and gradient copying', 'convert fp32 tensors, parameters, or nested tuples and lists to fp16 using fp32_to_fp16', 'clip the fp32 master gradients of an FP16_Optimizer by a specified max norm', 'wrap a PyTorch model in FP16Model to convert it to half precision safely', "convert a PyTorch network's parameters and buffers to a specified dtype", 'create FP32 master parameters from a model for mixed precision training', 'copy model gradients to master gradients for mixed precision optimization', 'copy FP32 master parameters back to the FP16 model parameters', 'create a DynamicLossScaler instance with custom init_scale, scale_factor, and scale_window parameters', 'create a static LossScaler instance with a fixed loss scale value for FP16 training', 'test the has_overflow method to check if model parameters contain inf or nan gradients', 'test the update_scale method to adjust loss scale based on gradient overflow detection', 'review the DynamicLossScaler backward method that scales loss and calls backward for FP16 training']
```

Usage

```
{'wrap_model_fp16': 'wrap a PyTorch model in FP16Model to convert it to half precision safely', 'convert_network_dtype': "convert a PyTorch network's parameters and buffers to a specified dtype", 'prep_param_lists_fp32': 'create FP32 master parameters from a model for mixed precision training', 'copy_model_grads_to_master': 'copy model gradients to master gradients for mixed precision optimization', 'copy_master_params_to_model': 'copy FP32 master parameters back to the FP16 model parameters'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/model_parallel/megatron/fp16/loss_scaler.py

Prompts

```
['create an FP16_Optimizer wrapping a PyTorch optimizer with static or dynamic loss scaling', 'wrap a PyTorch nn.Module with FP16_Module to automatically cast inputs to fp16 and outputs to fp32', 'run the FP16_Optimizer backward pass on a loss tensor with automatic loss scaling and gradient copying', 'convert fp32 tensors, parameters, or nested tuples and lists to fp16 using fp32_to_fp16', 'clip the fp32 master gradients of an FP16_Optimizer by a specified max norm', 'wrap a PyTorch model in FP16Model to convert it to half precision safely', "convert a PyTorch network's parameters and buffers to a specified dtype", 'create FP32 master parameters from a model for mixed precision training', 'copy model gradients to master gradients for mixed precision optimization', 'copy FP32 master parameters back to the FP16 model parameters', 'create a DynamicLossScaler instance with custom init_scale, scale_factor, and scale_window parameters', 'create a static LossScaler instance with a fixed loss scale value for FP16 training', 'test the has_overflow method to check if model parameters contain inf or nan gradients', 'test the update_scale method to adjust loss scale based on gradient overflow detection', 'review the DynamicLossScaler backward method that scales loss and calls backward for FP16 training']
```

Usage

```
{'create_DynamicLossScaler': 'create a DynamicLossScaler instance with custom init_scale, scale_factor, and scale_window parameters', 'create_LossScaler': 'create a static LossScaler instance with a fixed loss scale value for FP16 training', 'test_has_overflow': 'test the has_overflow method to check if model parameters contain inf or nan gradients', 'test_update_scale': 'test the update_scale method to adjust loss scale based on gradient overflow detection', 'review_DynamicLossScaler_backward': 'review the DynamicLossScaler backward method that scales loss and calls backward for FP16 training'}
```

