# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/models/utils/ckpt_convert.py

Prompts

```
['convert a Swin Transformer checkpoint state dict to the expected key naming convention', 'convert a Vision Transformer checkpoint state dict to the expected key naming convention', 'review the swin_convert function and its key remapping logic for attention and MLP layers', 'review the vit_convert function and its key remapping logic for blocks and attention layers', 'test the swin_convert function with a sample checkpoint dict containing layers and patch_embed keys', 'build a python module that applies a clipped sigmoid to a PyTorch tensor with configurable epsilon bounds', 'create a function that computes sigmoid on a tensor and clamps output between eps and 1 minus eps', 'test the clip_sigmoid function with a random tensor and verify output values stay within the clamped range', 'refactor the clip_sigmoid function to use a non-inplace sigmoid to avoid modifying the input tensor', 'summarize the clip_sigmoid function which applies sigmoid activation with clamping to prevent extreme values', 'build a PatchEmbed module that converts an image tensor into patch embeddings using a 2D convolution layer', 'create a PatchEmbed instance with LayerNorm normalization applied after the projection convolution layer', 'test the PatchEmbed forward pass by passing a 4D image tensor and verifying output shape', 'refactor the PatchEmbed class to support custom padding strategies beyond pad_to_patch_size', 'review the PatchEmbed constructor to understand how kernel_size, stride, and embed_dims configure the projection conv', 'build a module that initializes PyTorch layer weights with a constant value using ConstantInit', 'build a module that initializes PyTorch layer weights using Xavier normal or uniform distribution', 'build a module that initializes PyTorch layer weights using Kaiming He initialization with relu nonlinearity', 'build a module that initializes a PyTorch model by loading weights from a pretrained checkpoint file', 'build a module that initializes PyTorch layer weights using truncated normal distribution with configurable bounds']
```

Usage

```
{'convert_swin_checkpoint': 'convert a Swin Transformer checkpoint state dict to the expected key naming convention', 'convert_vit_checkpoint': 'convert a Vision Transformer checkpoint state dict to the expected key naming convention', 'review_swin_convert': 'review the swin_convert function and its key remapping logic for attention and MLP layers', 'review_vit_convert': 'review the vit_convert function and its key remapping logic for blocks and attention layers', 'test_swin_convert': 'test the swin_convert function with a sample checkpoint dict containing layers and patch_embed keys'}
```

## File: facebookresearch_nerf-det/mmdet3d/models/utils/clip_sigmoid.py

Prompts

```
['convert a Swin Transformer checkpoint state dict to the expected key naming convention', 'convert a Vision Transformer checkpoint state dict to the expected key naming convention', 'review the swin_convert function and its key remapping logic for attention and MLP layers', 'review the vit_convert function and its key remapping logic for blocks and attention layers', 'test the swin_convert function with a sample checkpoint dict containing layers and patch_embed keys', 'build a python module that applies a clipped sigmoid to a PyTorch tensor with configurable epsilon bounds', 'create a function that computes sigmoid on a tensor and clamps output between eps and 1 minus eps', 'test the clip_sigmoid function with a random tensor and verify output values stay within the clamped range', 'refactor the clip_sigmoid function to use a non-inplace sigmoid to avoid modifying the input tensor', 'summarize the clip_sigmoid function which applies sigmoid activation with clamping to prevent extreme values', 'build a PatchEmbed module that converts an image tensor into patch embeddings using a 2D convolution layer', 'create a PatchEmbed instance with LayerNorm normalization applied after the projection convolution layer', 'test the PatchEmbed forward pass by passing a 4D image tensor and verifying output shape', 'refactor the PatchEmbed class to support custom padding strategies beyond pad_to_patch_size', 'review the PatchEmbed constructor to understand how kernel_size, stride, and embed_dims configure the projection conv', 'build a module that initializes PyTorch layer weights with a constant value using ConstantInit', 'build a module that initializes PyTorch layer weights using Xavier normal or uniform distribution', 'build a module that initializes PyTorch layer weights using Kaiming He initialization with relu nonlinearity', 'build a module that initializes a PyTorch model by loading weights from a pretrained checkpoint file', 'build a module that initializes PyTorch layer weights using truncated normal distribution with configurable bounds']
```

Usage

```
{'build_clip_sigmoid': 'build a python module that applies a clipped sigmoid to a PyTorch tensor with configurable epsilon bounds', 'create_clip_sigmoid': 'create a function that computes sigmoid on a tensor and clamps output between eps and 1 minus eps', 'test_clip_sigmoid': 'test the clip_sigmoid function with a random tensor and verify output values stay within the clamped range', 'refactor_clip_sigmoid': 'refactor the clip_sigmoid function to use a non-inplace sigmoid to avoid modifying the input tensor', 'summarize_clip_sigmoid': 'summarize the clip_sigmoid function which applies sigmoid activation with clamping to prevent extreme values'}
```

## File: facebookresearch_nerf-det/mmdet3d/models/utils/embed.py

Prompts

```
['convert a Swin Transformer checkpoint state dict to the expected key naming convention', 'convert a Vision Transformer checkpoint state dict to the expected key naming convention', 'review the swin_convert function and its key remapping logic for attention and MLP layers', 'review the vit_convert function and its key remapping logic for blocks and attention layers', 'test the swin_convert function with a sample checkpoint dict containing layers and patch_embed keys', 'build a python module that applies a clipped sigmoid to a PyTorch tensor with configurable epsilon bounds', 'create a function that computes sigmoid on a tensor and clamps output between eps and 1 minus eps', 'test the clip_sigmoid function with a random tensor and verify output values stay within the clamped range', 'refactor the clip_sigmoid function to use a non-inplace sigmoid to avoid modifying the input tensor', 'summarize the clip_sigmoid function which applies sigmoid activation with clamping to prevent extreme values', 'build a PatchEmbed module that converts an image tensor into patch embeddings using a 2D convolution layer', 'create a PatchEmbed instance with LayerNorm normalization applied after the projection convolution layer', 'test the PatchEmbed forward pass by passing a 4D image tensor and verifying output shape', 'refactor the PatchEmbed class to support custom padding strategies beyond pad_to_patch_size', 'review the PatchEmbed constructor to understand how kernel_size, stride, and embed_dims configure the projection conv', 'build a module that initializes PyTorch layer weights with a constant value using ConstantInit', 'build a module that initializes PyTorch layer weights using Xavier normal or uniform distribution', 'build a module that initializes PyTorch layer weights using Kaiming He initialization with relu nonlinearity', 'build a module that initializes a PyTorch model by loading weights from a pretrained checkpoint file', 'build a module that initializes PyTorch layer weights using truncated normal distribution with configurable bounds']
```

Usage

```
{'build_PatchEmbed_module': 'build a PatchEmbed module that converts an image tensor into patch embeddings using a 2D convolution layer', 'create_PatchEmbed_with_norm': 'create a PatchEmbed instance with LayerNorm normalization applied after the projection convolution layer', 'test_PatchEmbed_forward': 'test the PatchEmbed forward pass by passing a 4D image tensor and verifying output shape', 'refactor_PatchEmbed_padding': 'refactor the PatchEmbed class to support custom padding strategies beyond pad_to_patch_size', 'review_PatchEmbed_init': 'review the PatchEmbed constructor to understand how kernel_size, stride, and embed_dims configure the projection conv'}
```

## File: facebookresearch_nerf-det/mmdet3d/models/utils/weight_init.py

Prompts

```
['convert a Swin Transformer checkpoint state dict to the expected key naming convention', 'convert a Vision Transformer checkpoint state dict to the expected key naming convention', 'review the swin_convert function and its key remapping logic for attention and MLP layers', 'review the vit_convert function and its key remapping logic for blocks and attention layers', 'test the swin_convert function with a sample checkpoint dict containing layers and patch_embed keys', 'build a python module that applies a clipped sigmoid to a PyTorch tensor with configurable epsilon bounds', 'create a function that computes sigmoid on a tensor and clamps output between eps and 1 minus eps', 'test the clip_sigmoid function with a random tensor and verify output values stay within the clamped range', 'refactor the clip_sigmoid function to use a non-inplace sigmoid to avoid modifying the input tensor', 'summarize the clip_sigmoid function which applies sigmoid activation with clamping to prevent extreme values', 'build a PatchEmbed module that converts an image tensor into patch embeddings using a 2D convolution layer', 'create a PatchEmbed instance with LayerNorm normalization applied after the projection convolution layer', 'test the PatchEmbed forward pass by passing a 4D image tensor and verifying output shape', 'refactor the PatchEmbed class to support custom padding strategies beyond pad_to_patch_size', 'review the PatchEmbed constructor to understand how kernel_size, stride, and embed_dims configure the projection conv', 'build a module that initializes PyTorch layer weights with a constant value using ConstantInit', 'build a module that initializes PyTorch layer weights using Xavier normal or uniform distribution', 'build a module that initializes PyTorch layer weights using Kaiming He initialization with relu nonlinearity', 'build a module that initializes a PyTorch model by loading weights from a pretrained checkpoint file', 'build a module that initializes PyTorch layer weights using truncated normal distribution with configurable bounds']
```

Usage

```
{'build_constant_init': 'build a module that initializes PyTorch layer weights with a constant value using ConstantInit', 'build_xavier_init': 'build a module that initializes PyTorch layer weights using Xavier normal or uniform distribution', 'build_kaiming_init': 'build a module that initializes PyTorch layer weights using Kaiming He initialization with relu nonlinearity', 'build_pretrained_init': 'build a module that initializes a PyTorch model by loading weights from a pretrained checkpoint file', 'build_trunc_normal_init': 'build a module that initializes PyTorch layer weights using truncated normal distribution with configurable bounds'}
```

