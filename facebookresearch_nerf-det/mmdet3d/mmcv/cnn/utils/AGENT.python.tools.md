# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/mmcv/cnn/utils/flops_counter.py

Prompts

```
['get the FLOPs and parameter count of a PyTorch model given an input shape', 'print a PyTorch model with per-layer FLOPs and parameter statistics to stdout', 'calculate the total number of trainable parameters in a PyTorch model', 'convert a raw FLOPs number into a human-readable string with units like GFLOPs', 'convert a raw parameter count into a human-readable string with units like M or K', 'recursively fuse conv2d and batch norm layers in a PyTorch module to save computations during inference', 'fuse a single conv layer and batch norm layer into one module by merging weights and biases', 'optimize a PyTorch neural network for inference by fusing consecutive conv and batch norm layers', 'review the fuse_conv_bn function to understand how it recursively fuses conv and batch norm in a module', 'refactor the fuse_conv_bn function to support additional normalization layer types beyond batch norm', 'convert all SyncBatchNorm layers in a PyTorch model to regular BatchNormXd layers', 'revert SyncBatchNorm and MMSyncBN layers in an nn.Module to dimension-agnostic BatchNormXd layers', 'create a BatchNorm layer that bypasses input dimension checks for flexible tensor shapes', 'review the _BatchNormXd class that extends _BatchNorm with a no-op _check_input_dim method', 'test the revert_sync_batchnorm function on a model with SyncBatchNorm layers to verify conversion', 'initialize a PyTorch nn.Module using an init_cfg dict with type, layer, and override keys', "initialize a PyTorch module's weights and bias to constant values with constant_init", "initialize a PyTorch module's weights with Xavier normal or uniform distribution via xavier_init", "initialize a PyTorch module's weights with Kaiming normal or uniform distribution via kaiming_init", 'fill a PyTorch tensor with truncated normal distribution values using trunc_normal_']
```

Usage

```
{'get_model_complexity_info': 'get the FLOPs and parameter count of a PyTorch model given an input shape', 'print_model_with_flops': 'print a PyTorch model with per-layer FLOPs and parameter statistics to stdout', 'get_model_parameters_number': 'calculate the total number of trainable parameters in a PyTorch model', 'flops_to_string': 'convert a raw FLOPs number into a human-readable string with units like GFLOPs', 'params_to_string': 'convert a raw parameter count into a human-readable string with units like M or K'}
```

## File: facebookresearch_nerf-det/mmdet3d/mmcv/cnn/utils/fuse_conv_bn.py

Prompts

```
['get the FLOPs and parameter count of a PyTorch model given an input shape', 'print a PyTorch model with per-layer FLOPs and parameter statistics to stdout', 'calculate the total number of trainable parameters in a PyTorch model', 'convert a raw FLOPs number into a human-readable string with units like GFLOPs', 'convert a raw parameter count into a human-readable string with units like M or K', 'recursively fuse conv2d and batch norm layers in a PyTorch module to save computations during inference', 'fuse a single conv layer and batch norm layer into one module by merging weights and biases', 'optimize a PyTorch neural network for inference by fusing consecutive conv and batch norm layers', 'review the fuse_conv_bn function to understand how it recursively fuses conv and batch norm in a module', 'refactor the fuse_conv_bn function to support additional normalization layer types beyond batch norm', 'convert all SyncBatchNorm layers in a PyTorch model to regular BatchNormXd layers', 'revert SyncBatchNorm and MMSyncBN layers in an nn.Module to dimension-agnostic BatchNormXd layers', 'create a BatchNorm layer that bypasses input dimension checks for flexible tensor shapes', 'review the _BatchNormXd class that extends _BatchNorm with a no-op _check_input_dim method', 'test the revert_sync_batchnorm function on a model with SyncBatchNorm layers to verify conversion', 'initialize a PyTorch nn.Module using an init_cfg dict with type, layer, and override keys', "initialize a PyTorch module's weights and bias to constant values with constant_init", "initialize a PyTorch module's weights with Xavier normal or uniform distribution via xavier_init", "initialize a PyTorch module's weights with Kaiming normal or uniform distribution via kaiming_init", 'fill a PyTorch tensor with truncated normal distribution values using trunc_normal_']
```

Usage

```
{'fuse_conv_bn_module': 'recursively fuse conv2d and batch norm layers in a PyTorch module to save computations during inference', 'fuse_single_conv_bn': 'fuse a single conv layer and batch norm layer into one module by merging weights and biases', 'optimize_inference_network': 'optimize a PyTorch neural network for inference by fusing consecutive conv and batch norm layers', 'review_fuse_conv_bn': 'review the fuse_conv_bn function to understand how it recursively fuses conv and batch norm in a module', 'refactor_fuse_conv_bn': 'refactor the fuse_conv_bn function to support additional normalization layer types beyond batch norm'}
```

## File: facebookresearch_nerf-det/mmdet3d/mmcv/cnn/utils/sync_bn.py

Prompts

```
['get the FLOPs and parameter count of a PyTorch model given an input shape', 'print a PyTorch model with per-layer FLOPs and parameter statistics to stdout', 'calculate the total number of trainable parameters in a PyTorch model', 'convert a raw FLOPs number into a human-readable string with units like GFLOPs', 'convert a raw parameter count into a human-readable string with units like M or K', 'recursively fuse conv2d and batch norm layers in a PyTorch module to save computations during inference', 'fuse a single conv layer and batch norm layer into one module by merging weights and biases', 'optimize a PyTorch neural network for inference by fusing consecutive conv and batch norm layers', 'review the fuse_conv_bn function to understand how it recursively fuses conv and batch norm in a module', 'refactor the fuse_conv_bn function to support additional normalization layer types beyond batch norm', 'convert all SyncBatchNorm layers in a PyTorch model to regular BatchNormXd layers', 'revert SyncBatchNorm and MMSyncBN layers in an nn.Module to dimension-agnostic BatchNormXd layers', 'create a BatchNorm layer that bypasses input dimension checks for flexible tensor shapes', 'review the _BatchNormXd class that extends _BatchNorm with a no-op _check_input_dim method', 'test the revert_sync_batchnorm function on a model with SyncBatchNorm layers to verify conversion', 'initialize a PyTorch nn.Module using an init_cfg dict with type, layer, and override keys', "initialize a PyTorch module's weights and bias to constant values with constant_init", "initialize a PyTorch module's weights with Xavier normal or uniform distribution via xavier_init", "initialize a PyTorch module's weights with Kaiming normal or uniform distribution via kaiming_init", 'fill a PyTorch tensor with truncated normal distribution values using trunc_normal_']
```

Usage

```
{'convert_sync_batchnorm_to_batchnorm': 'convert all SyncBatchNorm layers in a PyTorch model to regular BatchNormXd layers', 'revert_sync_batchnorm_module': 'revert SyncBatchNorm and MMSyncBN layers in an nn.Module to dimension-agnostic BatchNormXd layers', 'create_batchnorm_without_dim_check': 'create a BatchNorm layer that bypasses input dimension checks for flexible tensor shapes', 'review_BatchNormXd_class': 'review the _BatchNormXd class that extends _BatchNorm with a no-op _check_input_dim method', 'test_revert_sync_batchnorm': 'test the revert_sync_batchnorm function on a model with SyncBatchNorm layers to verify conversion'}
```

## File: facebookresearch_nerf-det/mmdet3d/mmcv/cnn/utils/weight_init.py

Prompts

```
['get the FLOPs and parameter count of a PyTorch model given an input shape', 'print a PyTorch model with per-layer FLOPs and parameter statistics to stdout', 'calculate the total number of trainable parameters in a PyTorch model', 'convert a raw FLOPs number into a human-readable string with units like GFLOPs', 'convert a raw parameter count into a human-readable string with units like M or K', 'recursively fuse conv2d and batch norm layers in a PyTorch module to save computations during inference', 'fuse a single conv layer and batch norm layer into one module by merging weights and biases', 'optimize a PyTorch neural network for inference by fusing consecutive conv and batch norm layers', 'review the fuse_conv_bn function to understand how it recursively fuses conv and batch norm in a module', 'refactor the fuse_conv_bn function to support additional normalization layer types beyond batch norm', 'convert all SyncBatchNorm layers in a PyTorch model to regular BatchNormXd layers', 'revert SyncBatchNorm and MMSyncBN layers in an nn.Module to dimension-agnostic BatchNormXd layers', 'create a BatchNorm layer that bypasses input dimension checks for flexible tensor shapes', 'review the _BatchNormXd class that extends _BatchNorm with a no-op _check_input_dim method', 'test the revert_sync_batchnorm function on a model with SyncBatchNorm layers to verify conversion', 'initialize a PyTorch nn.Module using an init_cfg dict with type, layer, and override keys', "initialize a PyTorch module's weights and bias to constant values with constant_init", "initialize a PyTorch module's weights with Xavier normal or uniform distribution via xavier_init", "initialize a PyTorch module's weights with Kaiming normal or uniform distribution via kaiming_init", 'fill a PyTorch tensor with truncated normal distribution values using trunc_normal_']
```

Usage

```
{'initialize_module_with_cfg': 'initialize a PyTorch nn.Module using an init_cfg dict with type, layer, and override keys', 'constant_init_module': "initialize a PyTorch module's weights and bias to constant values with constant_init", 'xavier_init_module': "initialize a PyTorch module's weights with Xavier normal or uniform distribution via xavier_init", 'kaiming_init_module': "initialize a PyTorch module's weights with Kaiming normal or uniform distribution via kaiming_init", 'trunc_normal_init_tensor': 'fill a PyTorch tensor with truncated normal distribution values using trunc_normal_'}
```

