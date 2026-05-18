# Agent Python Tools

- repo: facebookresearch/mobile-vision
- repo_uri: https://github.com/facebookresearch/mobile-vision

## File: facebookresearch_mobile-vision/mobile_cv/lut/tests/test_flops_utils.py

Prompts

```
['test FlopsEstimation to compute num_params and num_flops of a PyTorch model using enable context manager', 'test FlopsEstimation add_flops_info to annotate model string representation with input output shapes and flop counts', 'test FlopsEstimation set_callback to register a callback invoked after each forward pass with flop data', 'test print_model_flops to print per-layer shapes and total flops for a PyTorch model given input args', 'test get_model_flops to return num_params and num_flops for a PyTorch model given a tuple of inputs', 'test Conv2d to compute parameter count and FLOPs for a given input shape', 'test ConvTranspose2d to compute the output tensor shape from a given input shape', 'test MultiheadAttention to compute FLOPs and parameter count for attention layers', 'test chained Linear ops to compute output shapes and total FLOPs across layers', 'test MatMul to compute the output shape and FLOPs for matrix multiplication', 'create a LutItem with a Conv2d op and input shapes for a 224x224 image', 'create a LutItem with a ConvTranspose2d op and grouped channels for upsampling', 'build a LutTable and extend it with multiple LutItem entries', 'save a LutTable to a file and load it back for equality verification', 'test that a LutTable saves and loads with identical content', 'test the ModuleHook class to register and remove forward hooks on a PyTorch nn.Module', 'test the NestedModuleHook class to apply forward hooks to all leaf modules in a model', 'test convert_to_lut_ops to extract Conv2d and ConvTranspose2d ops from a PyTorch model', 'refactor ModuleHook to limit hook callbacks to a specified number of forward passes', 'review the collect_op_shape function that extracts input and output tensor shapes from a module hook']
```

Usage

```
{'test_FlopsEstimation_get_flops': 'test FlopsEstimation to compute num_params and num_flops of a PyTorch model using enable context manager', 'test_FlopsEstimation_add_flops_info': 'test FlopsEstimation add_flops_info to annotate model string representation with input output shapes and flop counts', 'test_FlopsEstimation_callback': 'test FlopsEstimation set_callback to register a callback invoked after each forward pass with flop data', 'test_print_model_flops': 'test print_model_flops to print per-layer shapes and total flops for a PyTorch model given input args', 'test_get_model_flops': 'test get_model_flops to return num_params and num_flops for a PyTorch model given a tuple of inputs'}
```

## File: facebookresearch_mobile-vision/mobile_cv/lut/tests/test_lut_ops.py

Prompts

```
['test FlopsEstimation to compute num_params and num_flops of a PyTorch model using enable context manager', 'test FlopsEstimation add_flops_info to annotate model string representation with input output shapes and flop counts', 'test FlopsEstimation set_callback to register a callback invoked after each forward pass with flop data', 'test print_model_flops to print per-layer shapes and total flops for a PyTorch model given input args', 'test get_model_flops to return num_params and num_flops for a PyTorch model given a tuple of inputs', 'test Conv2d to compute parameter count and FLOPs for a given input shape', 'test ConvTranspose2d to compute the output tensor shape from a given input shape', 'test MultiheadAttention to compute FLOPs and parameter count for attention layers', 'test chained Linear ops to compute output shapes and total FLOPs across layers', 'test MatMul to compute the output shape and FLOPs for matrix multiplication', 'create a LutItem with a Conv2d op and input shapes for a 224x224 image', 'create a LutItem with a ConvTranspose2d op and grouped channels for upsampling', 'build a LutTable and extend it with multiple LutItem entries', 'save a LutTable to a file and load it back for equality verification', 'test that a LutTable saves and loads with identical content', 'test the ModuleHook class to register and remove forward hooks on a PyTorch nn.Module', 'test the NestedModuleHook class to apply forward hooks to all leaf modules in a model', 'test convert_to_lut_ops to extract Conv2d and ConvTranspose2d ops from a PyTorch model', 'refactor ModuleHook to limit hook callbacks to a specified number of forward passes', 'review the collect_op_shape function that extracts input and output tensor shapes from a module hook']
```

Usage

```
{'test_conv2d_nparams_flops': 'test Conv2d to compute parameter count and FLOPs for a given input shape', 'test_conv_transpose2d_output_shape': 'test ConvTranspose2d to compute the output tensor shape from a given input shape', 'test_multiheadattention_flops': 'test MultiheadAttention to compute FLOPs and parameter count for attention layers', 'test_linear_chain_shapes': 'test chained Linear ops to compute output shapes and total FLOPs across layers', 'test_matmul_output_shape': 'test MatMul to compute the output shape and FLOPs for matrix multiplication'}
```

## File: facebookresearch_mobile-vision/mobile_cv/lut/tests/test_lut_schema.py

Prompts

```
['test FlopsEstimation to compute num_params and num_flops of a PyTorch model using enable context manager', 'test FlopsEstimation add_flops_info to annotate model string representation with input output shapes and flop counts', 'test FlopsEstimation set_callback to register a callback invoked after each forward pass with flop data', 'test print_model_flops to print per-layer shapes and total flops for a PyTorch model given input args', 'test get_model_flops to return num_params and num_flops for a PyTorch model given a tuple of inputs', 'test Conv2d to compute parameter count and FLOPs for a given input shape', 'test ConvTranspose2d to compute the output tensor shape from a given input shape', 'test MultiheadAttention to compute FLOPs and parameter count for attention layers', 'test chained Linear ops to compute output shapes and total FLOPs across layers', 'test MatMul to compute the output shape and FLOPs for matrix multiplication', 'create a LutItem with a Conv2d op and input shapes for a 224x224 image', 'create a LutItem with a ConvTranspose2d op and grouped channels for upsampling', 'build a LutTable and extend it with multiple LutItem entries', 'save a LutTable to a file and load it back for equality verification', 'test that a LutTable saves and loads with identical content', 'test the ModuleHook class to register and remove forward hooks on a PyTorch nn.Module', 'test the NestedModuleHook class to apply forward hooks to all leaf modules in a model', 'test convert_to_lut_ops to extract Conv2d and ConvTranspose2d ops from a PyTorch model', 'refactor ModuleHook to limit hook callbacks to a specified number of forward passes', 'review the collect_op_shape function that extracts input and output tensor shapes from a module hook']
```

Usage

```
{'create_lut_item_conv2d': 'create a LutItem with a Conv2d op and input shapes for a 224x224 image', 'create_lut_item_convtranspose2d': 'create a LutItem with a ConvTranspose2d op and grouped channels for upsampling', 'build_lut_table': 'build a LutTable and extend it with multiple LutItem entries', 'save_and_load_lut_table': 'save a LutTable to a file and load it back for equality verification', 'test_lut_table_roundtrip': 'test that a LutTable saves and loads with identical content'}
```

## File: facebookresearch_mobile-vision/mobile_cv/lut/tests/test_pt_utils.py

Prompts

```
['test FlopsEstimation to compute num_params and num_flops of a PyTorch model using enable context manager', 'test FlopsEstimation add_flops_info to annotate model string representation with input output shapes and flop counts', 'test FlopsEstimation set_callback to register a callback invoked after each forward pass with flop data', 'test print_model_flops to print per-layer shapes and total flops for a PyTorch model given input args', 'test get_model_flops to return num_params and num_flops for a PyTorch model given a tuple of inputs', 'test Conv2d to compute parameter count and FLOPs for a given input shape', 'test ConvTranspose2d to compute the output tensor shape from a given input shape', 'test MultiheadAttention to compute FLOPs and parameter count for attention layers', 'test chained Linear ops to compute output shapes and total FLOPs across layers', 'test MatMul to compute the output shape and FLOPs for matrix multiplication', 'create a LutItem with a Conv2d op and input shapes for a 224x224 image', 'create a LutItem with a ConvTranspose2d op and grouped channels for upsampling', 'build a LutTable and extend it with multiple LutItem entries', 'save a LutTable to a file and load it back for equality verification', 'test that a LutTable saves and loads with identical content', 'test the ModuleHook class to register and remove forward hooks on a PyTorch nn.Module', 'test the NestedModuleHook class to apply forward hooks to all leaf modules in a model', 'test convert_to_lut_ops to extract Conv2d and ConvTranspose2d ops from a PyTorch model', 'refactor ModuleHook to limit hook callbacks to a specified number of forward passes', 'review the collect_op_shape function that extracts input and output tensor shapes from a module hook']
```

Usage

```
{'test_ModuleHook': 'test the ModuleHook class to register and remove forward hooks on a PyTorch nn.Module', 'test_NestedModuleHook': 'test the NestedModuleHook class to apply forward hooks to all leaf modules in a model', 'test_convert_to_lut_ops': 'test convert_to_lut_ops to extract Conv2d and ConvTranspose2d ops from a PyTorch model', 'refactor_ModuleHook_life_count': 'refactor ModuleHook to limit hook callbacks to a specified number of forward passes', 'review_collect_op_shape': 'review the collect_op_shape function that extracts input and output tensor shapes from a module hook'}
```

