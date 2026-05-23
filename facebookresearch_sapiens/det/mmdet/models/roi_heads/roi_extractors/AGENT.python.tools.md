# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/det/mmdet/models/roi_heads/roi_extractors/base_roi_extractor.py

Prompts

```
['build a BaseRoIExtractor instance with RoI layer config, output channels, and feature map strides', 'build RoI operator modules for each level feature map using a layer config and strides', 'test the roi_rescale method to scale RoI coordinates by a given scale factor', 'review the abstract forward method signature for extracting RoI features from multi-scale feature maps', 'summarize the num_inputs property that returns the number of input feature maps', 'build a GenericRoIExtractor with sum aggregation to extract multi-scale RoI features from feature maps', 'build a GenericRoIExtractor with concat aggregation to concatenate RoI features across all feature map levels', 'run the forward pass of GenericRoIExtractor with multi-scale features and RoIs to extract region features', 'review the GenericRoIExtractor class and its pre-processing and post-processing module configuration options', 'test the GenericRoIExtractor forward method with an empty RoI tensor to verify it returns zeros', 'build a SingleRoIExtractor instance with roi_layer config, out_channels, and featmap_strides for FPN feature extraction', 'review the map_roi_levels method that maps RoIs to feature pyramid levels by computing scale via log2', 'test the forward method to extract RoI features from multi-scale feature maps using roi_scale_factor', 'refactor map_roi_levels to support custom scale thresholds instead of the default finest_scale of 56', 'summarize the SingleRoIExtractor class that extracts RoI features from single level feature maps using FPN mapping']
```

Usage

```
{'build_BaseRoIExtractor': 'build a BaseRoIExtractor instance with RoI layer config, output channels, and feature map strides', 'build_build_roi_layers': 'build RoI operator modules for each level feature map using a layer config and strides', 'test_roi_rescale': 'test the roi_rescale method to scale RoI coordinates by a given scale factor', 'review_forward': 'review the abstract forward method signature for extracting RoI features from multi-scale feature maps', 'summarize_num_inputs': 'summarize the num_inputs property that returns the number of input feature maps'}
```

## File: facebookresearch_sapiens/det/mmdet/models/roi_heads/roi_extractors/generic_roi_extractor.py

Prompts

```
['build a BaseRoIExtractor instance with RoI layer config, output channels, and feature map strides', 'build RoI operator modules for each level feature map using a layer config and strides', 'test the roi_rescale method to scale RoI coordinates by a given scale factor', 'review the abstract forward method signature for extracting RoI features from multi-scale feature maps', 'summarize the num_inputs property that returns the number of input feature maps', 'build a GenericRoIExtractor with sum aggregation to extract multi-scale RoI features from feature maps', 'build a GenericRoIExtractor with concat aggregation to concatenate RoI features across all feature map levels', 'run the forward pass of GenericRoIExtractor with multi-scale features and RoIs to extract region features', 'review the GenericRoIExtractor class and its pre-processing and post-processing module configuration options', 'test the GenericRoIExtractor forward method with an empty RoI tensor to verify it returns zeros', 'build a SingleRoIExtractor instance with roi_layer config, out_channels, and featmap_strides for FPN feature extraction', 'review the map_roi_levels method that maps RoIs to feature pyramid levels by computing scale via log2', 'test the forward method to extract RoI features from multi-scale feature maps using roi_scale_factor', 'refactor map_roi_levels to support custom scale thresholds instead of the default finest_scale of 56', 'summarize the SingleRoIExtractor class that extracts RoI features from single level feature maps using FPN mapping']
```

Usage

```
{'build_GenericRoIExtractor_sum_aggregation': 'build a GenericRoIExtractor with sum aggregation to extract multi-scale RoI features from feature maps', 'build_GenericRoIExtractor_concat_aggregation': 'build a GenericRoIExtractor with concat aggregation to concatenate RoI features across all feature map levels', 'forward_GenericRoIExtractor': 'run the forward pass of GenericRoIExtractor with multi-scale features and RoIs to extract region features', 'review_GenericRoIExtractor_pre_post_modules': 'review the GenericRoIExtractor class and its pre-processing and post-processing module configuration options', 'test_GenericRoIExtractor_empty_rois': 'test the GenericRoIExtractor forward method with an empty RoI tensor to verify it returns zeros'}
```

## File: facebookresearch_sapiens/det/mmdet/models/roi_heads/roi_extractors/single_level_roi_extractor.py

Prompts

```
['build a BaseRoIExtractor instance with RoI layer config, output channels, and feature map strides', 'build RoI operator modules for each level feature map using a layer config and strides', 'test the roi_rescale method to scale RoI coordinates by a given scale factor', 'review the abstract forward method signature for extracting RoI features from multi-scale feature maps', 'summarize the num_inputs property that returns the number of input feature maps', 'build a GenericRoIExtractor with sum aggregation to extract multi-scale RoI features from feature maps', 'build a GenericRoIExtractor with concat aggregation to concatenate RoI features across all feature map levels', 'run the forward pass of GenericRoIExtractor with multi-scale features and RoIs to extract region features', 'review the GenericRoIExtractor class and its pre-processing and post-processing module configuration options', 'test the GenericRoIExtractor forward method with an empty RoI tensor to verify it returns zeros', 'build a SingleRoIExtractor instance with roi_layer config, out_channels, and featmap_strides for FPN feature extraction', 'review the map_roi_levels method that maps RoIs to feature pyramid levels by computing scale via log2', 'test the forward method to extract RoI features from multi-scale feature maps using roi_scale_factor', 'refactor map_roi_levels to support custom scale thresholds instead of the default finest_scale of 56', 'summarize the SingleRoIExtractor class that extracts RoI features from single level feature maps using FPN mapping']
```

Usage

```
{'build_SingleRoIExtractor': 'build a SingleRoIExtractor instance with roi_layer config, out_channels, and featmap_strides for FPN feature extraction', 'review_map_roi_levels': 'review the map_roi_levels method that maps RoIs to feature pyramid levels by computing scale via log2', 'test_forward_extraction': 'test the forward method to extract RoI features from multi-scale feature maps using roi_scale_factor', 'refactor_map_roi_levels': 'refactor map_roi_levels to support custom scale thresholds instead of the default finest_scale of 56', 'summarize_SingleRoIExtractor': 'summarize the SingleRoIExtractor class that extracts RoI features from single level feature maps using FPN mapping'}
```

