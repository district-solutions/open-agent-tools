# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/cv/mmcv/cnn/utils/flops_counter.py

Prompts

```
['get FLOPs and parameter counts for a PyTorch model with per-layer statistics printed to stdout', 'convert a raw FLOPs number into a human-readable string with units like GFLOPs or MFLOPs', 'convert a raw parameter count into a human-readable string with units like M or K', 'print a PyTorch model with per-layer FLOPs and parameter counts alongside each module', 'calculate the total number of trainable parameters in a PyTorch model', 'fuse conv and batch norm layers in a PyTorch module recursively to optimize inference', 'fuse a single conv layer and batch norm layer into one module using _fuse_conv_bn', 'optimize a PyTorch neural network for inference by fusing conv and batch norm layers', 'review the fuse_conv_bn function to understand how it recursively fuses conv and batch norm', 'refactor fuse_conv_bn to support additional batch norm variants beyond BatchNorm and SyncBatchNorm']
```

Usage

```
{'get_model_complexity_info': 'get FLOPs and parameter counts for a PyTorch model with per-layer statistics printed to stdout', 'flops_to_string': 'convert a raw FLOPs number into a human-readable string with units like GFLOPs or MFLOPs', 'params_to_string': 'convert a raw parameter count into a human-readable string with units like M or K', 'print_model_with_flops': 'print a PyTorch model with per-layer FLOPs and parameter counts alongside each module', 'get_model_parameters_number': 'calculate the total number of trainable parameters in a PyTorch model'}
```

## File: facebookresearch_sapiens/cv/mmcv/cnn/utils/fuse_conv_bn.py

Prompts

```
['get FLOPs and parameter counts for a PyTorch model with per-layer statistics printed to stdout', 'convert a raw FLOPs number into a human-readable string with units like GFLOPs or MFLOPs', 'convert a raw parameter count into a human-readable string with units like M or K', 'print a PyTorch model with per-layer FLOPs and parameter counts alongside each module', 'calculate the total number of trainable parameters in a PyTorch model', 'fuse conv and batch norm layers in a PyTorch module recursively to optimize inference', 'fuse a single conv layer and batch norm layer into one module using _fuse_conv_bn', 'optimize a PyTorch neural network for inference by fusing conv and batch norm layers', 'review the fuse_conv_bn function to understand how it recursively fuses conv and batch norm', 'refactor fuse_conv_bn to support additional batch norm variants beyond BatchNorm and SyncBatchNorm']
```

Usage

```
{'fuse_conv_bn_module': 'fuse conv and batch norm layers in a PyTorch module recursively to optimize inference', 'fuse_single_conv_bn': 'fuse a single conv layer and batch norm layer into one module using _fuse_conv_bn', 'optimize_inference_network': 'optimize a PyTorch neural network for inference by fusing conv and batch norm layers', 'review_fuse_conv_bn': 'review the fuse_conv_bn function to understand how it recursively fuses conv and batch norm', 'refactor_fuse_conv_bn': 'refactor fuse_conv_bn to support additional batch norm variants beyond BatchNorm and SyncBatchNorm'}
```

