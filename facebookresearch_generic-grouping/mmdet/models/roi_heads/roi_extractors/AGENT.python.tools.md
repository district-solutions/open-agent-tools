# Agent Python Tools

- repo: facebookresearch/generic-grouping
- repo_uri: https://github.com/facebookresearch/generic-grouping

## File: facebookresearch_generic-grouping/mmdet/models/roi_heads/roi_extractors/base_roi_extractor.py

Prompts

```
['build a BaseRoIExtractor with roi_layer config, out_channels, and featmap_strides for feature extraction', 'build RoI operator layers from a layer_cfg dict and featmap_strides using mmcv ops like RoIAlign', 'rescale RoI coordinates by a given scale factor and return the new scaled RoI tensor', 'initialize the weights of a BaseRoIExtractor instance', 'review the abstract forward method signature that takes feats, rois, and an optional roi_scale_factor', 'build a GenericRoIExtractor with sum aggregation to extract RoI features from multi-level feature maps', 'build a GenericRoIExtractor with concat aggregation to concatenate RoI features from multiple feature map levels', 'build a GenericRoIExtractor with pre and post processing modules for RoI feature extraction', 'forward multi-level feature maps and RoIs through the GenericRoIExtractor to extract aggregated RoI features', 'forward feature maps and RoIs with a scale factor to rescale RoIs before extraction', 'build a SingleRoIExtractor with roi_layer config, out_channels, and featmap_strides for FPN feature extraction', 'create a function that maps RoIs to feature pyramid levels based on their spatial scale', 'test the forward pass of SingleRoIExtractor with multi-level feature maps and RoI tensors', 'refactor map_roi_levels to support custom scale thresholds instead of the default finest_scale of 56', 'review the SingleRoIExtractor forward method for ONNX export compatibility and multi-level RoI alignment logic']
```

Usage

```
{'build_BaseRoIExtractor': 'build a BaseRoIExtractor with roi_layer config, out_channels, and featmap_strides for feature extraction', 'build_roi_layers': 'build RoI operator layers from a layer_cfg dict and featmap_strides using mmcv ops like RoIAlign', 'roi_rescale': 'rescale RoI coordinates by a given scale factor and return the new scaled RoI tensor', 'init_weights_BaseRoIExtractor': 'initialize the weights of a BaseRoIExtractor instance', 'review_BaseRoIExtractor_forward': 'review the abstract forward method signature that takes feats, rois, and an optional roi_scale_factor'}
```

## File: facebookresearch_generic-grouping/mmdet/models/roi_heads/roi_extractors/generic_roi_extractor.py

Prompts

```
['build a BaseRoIExtractor with roi_layer config, out_channels, and featmap_strides for feature extraction', 'build RoI operator layers from a layer_cfg dict and featmap_strides using mmcv ops like RoIAlign', 'rescale RoI coordinates by a given scale factor and return the new scaled RoI tensor', 'initialize the weights of a BaseRoIExtractor instance', 'review the abstract forward method signature that takes feats, rois, and an optional roi_scale_factor', 'build a GenericRoIExtractor with sum aggregation to extract RoI features from multi-level feature maps', 'build a GenericRoIExtractor with concat aggregation to concatenate RoI features from multiple feature map levels', 'build a GenericRoIExtractor with pre and post processing modules for RoI feature extraction', 'forward multi-level feature maps and RoIs through the GenericRoIExtractor to extract aggregated RoI features', 'forward feature maps and RoIs with a scale factor to rescale RoIs before extraction', 'build a SingleRoIExtractor with roi_layer config, out_channels, and featmap_strides for FPN feature extraction', 'create a function that maps RoIs to feature pyramid levels based on their spatial scale', 'test the forward pass of SingleRoIExtractor with multi-level feature maps and RoI tensors', 'refactor map_roi_levels to support custom scale thresholds instead of the default finest_scale of 56', 'review the SingleRoIExtractor forward method for ONNX export compatibility and multi-level RoI alignment logic']
```

Usage

```
{'build_GenericRoIExtractor': 'build a GenericRoIExtractor with sum aggregation to extract RoI features from multi-level feature maps', 'build_GenericRoIExtractor_concat': 'build a GenericRoIExtractor with concat aggregation to concatenate RoI features from multiple feature map levels', 'build_GenericRoIExtractor_with_pre_post': 'build a GenericRoIExtractor with pre and post processing modules for RoI feature extraction', 'forward_GenericRoIExtractor': 'forward multi-level feature maps and RoIs through the GenericRoIExtractor to extract aggregated RoI features', 'forward_GenericRoIExtractor_with_scale': 'forward feature maps and RoIs with a scale factor to rescale RoIs before extraction'}
```

## File: facebookresearch_generic-grouping/mmdet/models/roi_heads/roi_extractors/single_level_roi_extractor.py

Prompts

```
['build a BaseRoIExtractor with roi_layer config, out_channels, and featmap_strides for feature extraction', 'build RoI operator layers from a layer_cfg dict and featmap_strides using mmcv ops like RoIAlign', 'rescale RoI coordinates by a given scale factor and return the new scaled RoI tensor', 'initialize the weights of a BaseRoIExtractor instance', 'review the abstract forward method signature that takes feats, rois, and an optional roi_scale_factor', 'build a GenericRoIExtractor with sum aggregation to extract RoI features from multi-level feature maps', 'build a GenericRoIExtractor with concat aggregation to concatenate RoI features from multiple feature map levels', 'build a GenericRoIExtractor with pre and post processing modules for RoI feature extraction', 'forward multi-level feature maps and RoIs through the GenericRoIExtractor to extract aggregated RoI features', 'forward feature maps and RoIs with a scale factor to rescale RoIs before extraction', 'build a SingleRoIExtractor with roi_layer config, out_channels, and featmap_strides for FPN feature extraction', 'create a function that maps RoIs to feature pyramid levels based on their spatial scale', 'test the forward pass of SingleRoIExtractor with multi-level feature maps and RoI tensors', 'refactor map_roi_levels to support custom scale thresholds instead of the default finest_scale of 56', 'review the SingleRoIExtractor forward method for ONNX export compatibility and multi-level RoI alignment logic']
```

Usage

```
{'build_SingleRoIExtractor': 'build a SingleRoIExtractor with roi_layer config, out_channels, and featmap_strides for FPN feature extraction', 'create_map_roi_levels': 'create a function that maps RoIs to feature pyramid levels based on their spatial scale', 'test_forward_roi_extraction': 'test the forward pass of SingleRoIExtractor with multi-level feature maps and RoI tensors', 'refactor_map_roi_levels': 'refactor map_roi_levels to support custom scale thresholds instead of the default finest_scale of 56', 'review_SingleRoIExtractor_forward': 'review the SingleRoIExtractor forward method for ONNX export compatibility and multi-level RoI alignment logic'}
```

