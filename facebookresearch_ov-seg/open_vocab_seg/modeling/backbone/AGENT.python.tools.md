# Agent Python Tools

- repo: facebookresearch/ov-seg
- repo_uri: https://github.com/facebookresearch/ov-seg

## File: facebookresearch_ov-seg/open_vocab_seg/modeling/backbone/clip_resnet.py

Prompts

```
['build a ModifiedResNet backbone with custom layer depths, width, strides, and multi-grid dilation settings', 'create a Bottleneck block with configurable inplanes, planes, stride, and dilation for residual connections', 'register a D2ModifiedResNet backbone in Detectron2 using config depth, groups, and stem type settings', 'run a forward pass through ModifiedResNet to extract multi-scale feature maps res2 through res5', 'review the Bottleneck class downsample logic that uses avgpool and 1x1 conv for stride or channel mismatch', 'build a SwinTransformer backbone with configurable depths, num_heads, and window_size for semantic segmentation', 'create a D2SwinTransformer registered in Detectron2 BACKBONE_REGISTRY using config MODEL.SWIN settings', 'review the WindowAttention class for multi-head self-attention with relative position bias in shifted windows', 'refactor the SwinTransformerBlock to adjust window_size, shift_size, or mlp_ratio parameters', 'test the PatchMerging layer that reduces spatial resolution by half and doubles channel dimension']
```

Usage

```
{'build_modified_resnet_backbone': 'build a ModifiedResNet backbone with custom layer depths, width, strides, and multi-grid dilation settings', 'create_bottleneck_block': 'create a Bottleneck block with configurable inplanes, planes, stride, and dilation for residual connections', 'register_d2_modified_resnet': 'register a D2ModifiedResNet backbone in Detectron2 using config depth, groups, and stem type settings', 'forward_modified_resnet_features': 'run a forward pass through ModifiedResNet to extract multi-scale feature maps res2 through res5', 'review_bottleneck_downsample': 'review the Bottleneck class downsample logic that uses avgpool and 1x1 conv for stride or channel mismatch'}
```

## File: facebookresearch_ov-seg/open_vocab_seg/modeling/backbone/swin.py

Prompts

```
['build a ModifiedResNet backbone with custom layer depths, width, strides, and multi-grid dilation settings', 'create a Bottleneck block with configurable inplanes, planes, stride, and dilation for residual connections', 'register a D2ModifiedResNet backbone in Detectron2 using config depth, groups, and stem type settings', 'run a forward pass through ModifiedResNet to extract multi-scale feature maps res2 through res5', 'review the Bottleneck class downsample logic that uses avgpool and 1x1 conv for stride or channel mismatch', 'build a SwinTransformer backbone with configurable depths, num_heads, and window_size for semantic segmentation', 'create a D2SwinTransformer registered in Detectron2 BACKBONE_REGISTRY using config MODEL.SWIN settings', 'review the WindowAttention class for multi-head self-attention with relative position bias in shifted windows', 'refactor the SwinTransformerBlock to adjust window_size, shift_size, or mlp_ratio parameters', 'test the PatchMerging layer that reduces spatial resolution by half and doubles channel dimension']
```

Usage

```
{'build_swin_transformer_backbone': 'build a SwinTransformer backbone with configurable depths, num_heads, and window_size for semantic segmentation', 'create_d2swin_transformer': 'create a D2SwinTransformer registered in Detectron2 BACKBONE_REGISTRY using config MODEL.SWIN settings', 'review_window_attention': 'review the WindowAttention class for multi-head self-attention with relative position bias in shifted windows', 'refactor_swin_transformer_block': 'refactor the SwinTransformerBlock to adjust window_size, shift_size, or mlp_ratio parameters', 'test_patch_merging': 'test the PatchMerging layer that reduces spatial resolution by half and doubles channel dimension'}
```

