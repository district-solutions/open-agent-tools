# Agent Python Tools

- repo: facebookresearch/sam-3d-objects
- repo_uri: https://github.com/facebookresearch/sam-3d-objects

## File: facebookresearch_sam-3d-objects/sam3d_objects/model/backbone/tdfy_dit/modules/norm.py

Prompts

```
['build a LayerNorm32 layer that normalizes tensors in float32 and casts back to original dtype', 'build a GroupNorm32 layer that applies group normalization in float32 and preserves input dtype', 'build a ChannelLayerNorm32 layer that normalizes along the channel dimension with float32 precision', 'test the LayerNorm32 forward pass preserves the input tensor dtype after normalization', 'review the ChannelLayerNorm32 class and its permute logic for channel-first tensor normalization', 'build a python module that performs 3D pixel shuffle on a torch tensor by a given scale factor', 'build a python module that patchifies a multi-dimensional torch tensor by reshaping spatial dims into patches', 'build a python module that unpatchifies a torch tensor by reversing the patchify operation', 'test the pixel_shuffle_3d function with a 5D tensor and verify output shape matches expected scale factor', 'test that patchify followed by unpatchify returns the original tensor unchanged', "convert a PyTorch module's parameters to float16 for memory-efficient training", "convert a PyTorch module's parameters back to float32 from float16", 'zero out all parameters of a PyTorch module and return it', 'scale all parameters of a PyTorch module by a given factor', 'apply shift and scale modulation to a tensor using element-wise operations']
```

Usage

```
{'build_LayerNorm32': 'build a LayerNorm32 layer that normalizes tensors in float32 and casts back to original dtype', 'build_GroupNorm32': 'build a GroupNorm32 layer that applies group normalization in float32 and preserves input dtype', 'build_ChannelLayerNorm32': 'build a ChannelLayerNorm32 layer that normalizes along the channel dimension with float32 precision', 'test_LayerNorm32_dtype_preservation': 'test the LayerNorm32 forward pass preserves the input tensor dtype after normalization', 'review_ChannelLayerNorm32_permute': 'review the ChannelLayerNorm32 class and its permute logic for channel-first tensor normalization'}
```

## File: facebookresearch_sam-3d-objects/sam3d_objects/model/backbone/tdfy_dit/modules/spatial.py

Prompts

```
['build a LayerNorm32 layer that normalizes tensors in float32 and casts back to original dtype', 'build a GroupNorm32 layer that applies group normalization in float32 and preserves input dtype', 'build a ChannelLayerNorm32 layer that normalizes along the channel dimension with float32 precision', 'test the LayerNorm32 forward pass preserves the input tensor dtype after normalization', 'review the ChannelLayerNorm32 class and its permute logic for channel-first tensor normalization', 'build a python module that performs 3D pixel shuffle on a torch tensor by a given scale factor', 'build a python module that patchifies a multi-dimensional torch tensor by reshaping spatial dims into patches', 'build a python module that unpatchifies a torch tensor by reversing the patchify operation', 'test the pixel_shuffle_3d function with a 5D tensor and verify output shape matches expected scale factor', 'test that patchify followed by unpatchify returns the original tensor unchanged', "convert a PyTorch module's parameters to float16 for memory-efficient training", "convert a PyTorch module's parameters back to float32 from float16", 'zero out all parameters of a PyTorch module and return it', 'scale all parameters of a PyTorch module by a given factor', 'apply shift and scale modulation to a tensor using element-wise operations']
```

Usage

```
{'build_pixel_shuffle_3d': 'build a python module that performs 3D pixel shuffle on a torch tensor by a given scale factor', 'build_patchify': 'build a python module that patchifies a multi-dimensional torch tensor by reshaping spatial dims into patches', 'build_unpatchify': 'build a python module that unpatchifies a torch tensor by reversing the patchify operation', 'test_pixel_shuffle_3d': 'test the pixel_shuffle_3d function with a 5D tensor and verify output shape matches expected scale factor', 'test_patchify_unpatchify_roundtrip': 'test that patchify followed by unpatchify returns the original tensor unchanged'}
```

## File: facebookresearch_sam-3d-objects/sam3d_objects/model/backbone/tdfy_dit/modules/utils.py

Prompts

```
['build a LayerNorm32 layer that normalizes tensors in float32 and casts back to original dtype', 'build a GroupNorm32 layer that applies group normalization in float32 and preserves input dtype', 'build a ChannelLayerNorm32 layer that normalizes along the channel dimension with float32 precision', 'test the LayerNorm32 forward pass preserves the input tensor dtype after normalization', 'review the ChannelLayerNorm32 class and its permute logic for channel-first tensor normalization', 'build a python module that performs 3D pixel shuffle on a torch tensor by a given scale factor', 'build a python module that patchifies a multi-dimensional torch tensor by reshaping spatial dims into patches', 'build a python module that unpatchifies a torch tensor by reversing the patchify operation', 'test the pixel_shuffle_3d function with a 5D tensor and verify output shape matches expected scale factor', 'test that patchify followed by unpatchify returns the original tensor unchanged', "convert a PyTorch module's parameters to float16 for memory-efficient training", "convert a PyTorch module's parameters back to float32 from float16", 'zero out all parameters of a PyTorch module and return it', 'scale all parameters of a PyTorch module by a given factor', 'apply shift and scale modulation to a tensor using element-wise operations']
```

Usage

```
{'convert_module_to_f16': "convert a PyTorch module's parameters to float16 for memory-efficient training", 'convert_module_to_f32': "convert a PyTorch module's parameters back to float32 from float16", 'zero_module': 'zero out all parameters of a PyTorch module and return it', 'scale_module': 'scale all parameters of a PyTorch module by a given factor', 'modulate': 'apply shift and scale modulation to a tensor using element-wise operations'}
```

