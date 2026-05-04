# Agent Python Tools

- repo: facebookresearch/generic-grouping
- repo_uri: https://github.com/facebookresearch/generic-grouping

## File: facebookresearch_generic-grouping/mmdet/core/anchor/anchor_generator.py

Prompts

```
['create an AnchorGenerator with strides, ratios, and scales for 2D anchor-based object detection', 'generate grid anchors across multiple feature levels using grid_anchors with featmap sizes', 'generate valid flags for anchors in multiple feature levels using valid_flags method', 'create an SSDAnchorGenerator with strides, ratios, and basesize_ratio_range for SSD detection', 'create a YOLOAnchorGenerator with strides and base_sizes for YOLO object detection', 'build an anchor generator from a config dict using the ANCHOR_GENERATORS registry', 'register a custom anchor generator class under the ANCHOR_GENERATORS registry', 'build an anchor generator from config with default arguments via build_anchor_generator', 'review the ANCHOR_GENERATORS registry to see all registered anchor generator types', 'summarize how build_anchor_generator uses MMCV build_from_cfg to instantiate anchor generators', 'build a python module to generate grid points for a feature map with a given stride using PointGenerator', 'create a function that generates validity flags for anchor points within a specified valid region size', 'test the PointGenerator _meshgrid method to verify it correctly interleaves x and y coordinate tensors', 'refactor the PointGenerator grid_points method to support configurable stride values per feature map level', 'review the PointGenerator class and its methods for generating anchor points and validity flags in object detection', 'convert a list of per-image target tensors into per-feature-level tensors using images_to_levels', 'check which anchor boxes fall inside the valid image border using anchor_inside_flags', 'calculate a proportional bounding box region from a given ratio using calc_region', 'filter anchor boxes by valid flags and allowed border tolerance using anchor_inside_flags', 'clamp a proportional bbox region to feature map boundaries using calc_region with featmap_size']
```

Usage

```
{'create_anchor_generator': 'create an AnchorGenerator with strides, ratios, and scales for 2D anchor-based object detection', 'generate_grid_anchors': 'generate grid anchors across multiple feature levels using grid_anchors with featmap sizes', 'generate_valid_flags': 'generate valid flags for anchors in multiple feature levels using valid_flags method', 'create_ssd_anchor_generator': 'create an SSDAnchorGenerator with strides, ratios, and basesize_ratio_range for SSD detection', 'create_yolo_anchor_generator': 'create a YOLOAnchorGenerator with strides and base_sizes for YOLO object detection'}
```

## File: facebookresearch_generic-grouping/mmdet/core/anchor/builder.py

Prompts

```
['create an AnchorGenerator with strides, ratios, and scales for 2D anchor-based object detection', 'generate grid anchors across multiple feature levels using grid_anchors with featmap sizes', 'generate valid flags for anchors in multiple feature levels using valid_flags method', 'create an SSDAnchorGenerator with strides, ratios, and basesize_ratio_range for SSD detection', 'create a YOLOAnchorGenerator with strides and base_sizes for YOLO object detection', 'build an anchor generator from a config dict using the ANCHOR_GENERATORS registry', 'register a custom anchor generator class under the ANCHOR_GENERATORS registry', 'build an anchor generator from config with default arguments via build_anchor_generator', 'review the ANCHOR_GENERATORS registry to see all registered anchor generator types', 'summarize how build_anchor_generator uses MMCV build_from_cfg to instantiate anchor generators', 'build a python module to generate grid points for a feature map with a given stride using PointGenerator', 'create a function that generates validity flags for anchor points within a specified valid region size', 'test the PointGenerator _meshgrid method to verify it correctly interleaves x and y coordinate tensors', 'refactor the PointGenerator grid_points method to support configurable stride values per feature map level', 'review the PointGenerator class and its methods for generating anchor points and validity flags in object detection', 'convert a list of per-image target tensors into per-feature-level tensors using images_to_levels', 'check which anchor boxes fall inside the valid image border using anchor_inside_flags', 'calculate a proportional bounding box region from a given ratio using calc_region', 'filter anchor boxes by valid flags and allowed border tolerance using anchor_inside_flags', 'clamp a proportional bbox region to feature map boundaries using calc_region with featmap_size']
```

Usage

```
{'build_anchor_generator_from_cfg': 'build an anchor generator from a config dict using the ANCHOR_GENERATORS registry', 'register_custom_anchor_generator': 'register a custom anchor generator class under the ANCHOR_GENERATORS registry', 'build_anchor_generator_with_defaults': 'build an anchor generator from config with default arguments via build_anchor_generator', 'review_anchor_generator_registry': 'review the ANCHOR_GENERATORS registry to see all registered anchor generator types', 'summarize_build_anchor_generator': 'summarize how build_anchor_generator uses MMCV build_from_cfg to instantiate anchor generators'}
```

## File: facebookresearch_generic-grouping/mmdet/core/anchor/point_generator.py

Prompts

```
['create an AnchorGenerator with strides, ratios, and scales for 2D anchor-based object detection', 'generate grid anchors across multiple feature levels using grid_anchors with featmap sizes', 'generate valid flags for anchors in multiple feature levels using valid_flags method', 'create an SSDAnchorGenerator with strides, ratios, and basesize_ratio_range for SSD detection', 'create a YOLOAnchorGenerator with strides and base_sizes for YOLO object detection', 'build an anchor generator from a config dict using the ANCHOR_GENERATORS registry', 'register a custom anchor generator class under the ANCHOR_GENERATORS registry', 'build an anchor generator from config with default arguments via build_anchor_generator', 'review the ANCHOR_GENERATORS registry to see all registered anchor generator types', 'summarize how build_anchor_generator uses MMCV build_from_cfg to instantiate anchor generators', 'build a python module to generate grid points for a feature map with a given stride using PointGenerator', 'create a function that generates validity flags for anchor points within a specified valid region size', 'test the PointGenerator _meshgrid method to verify it correctly interleaves x and y coordinate tensors', 'refactor the PointGenerator grid_points method to support configurable stride values per feature map level', 'review the PointGenerator class and its methods for generating anchor points and validity flags in object detection', 'convert a list of per-image target tensors into per-feature-level tensors using images_to_levels', 'check which anchor boxes fall inside the valid image border using anchor_inside_flags', 'calculate a proportional bounding box region from a given ratio using calc_region', 'filter anchor boxes by valid flags and allowed border tolerance using anchor_inside_flags', 'clamp a proportional bbox region to feature map boundaries using calc_region with featmap_size']
```

Usage

```
{'build_grid_points': 'build a python module to generate grid points for a feature map with a given stride using PointGenerator', 'create_valid_flags': 'create a function that generates validity flags for anchor points within a specified valid region size', 'test_meshgrid': 'test the PointGenerator _meshgrid method to verify it correctly interleaves x and y coordinate tensors', 'refactor_grid_points': 'refactor the PointGenerator grid_points method to support configurable stride values per feature map level', 'review_PointGenerator': 'review the PointGenerator class and its methods for generating anchor points and validity flags in object detection'}
```

## File: facebookresearch_generic-grouping/mmdet/core/anchor/utils.py

Prompts

```
['create an AnchorGenerator with strides, ratios, and scales for 2D anchor-based object detection', 'generate grid anchors across multiple feature levels using grid_anchors with featmap sizes', 'generate valid flags for anchors in multiple feature levels using valid_flags method', 'create an SSDAnchorGenerator with strides, ratios, and basesize_ratio_range for SSD detection', 'create a YOLOAnchorGenerator with strides and base_sizes for YOLO object detection', 'build an anchor generator from a config dict using the ANCHOR_GENERATORS registry', 'register a custom anchor generator class under the ANCHOR_GENERATORS registry', 'build an anchor generator from config with default arguments via build_anchor_generator', 'review the ANCHOR_GENERATORS registry to see all registered anchor generator types', 'summarize how build_anchor_generator uses MMCV build_from_cfg to instantiate anchor generators', 'build a python module to generate grid points for a feature map with a given stride using PointGenerator', 'create a function that generates validity flags for anchor points within a specified valid region size', 'test the PointGenerator _meshgrid method to verify it correctly interleaves x and y coordinate tensors', 'refactor the PointGenerator grid_points method to support configurable stride values per feature map level', 'review the PointGenerator class and its methods for generating anchor points and validity flags in object detection', 'convert a list of per-image target tensors into per-feature-level tensors using images_to_levels', 'check which anchor boxes fall inside the valid image border using anchor_inside_flags', 'calculate a proportional bounding box region from a given ratio using calc_region', 'filter anchor boxes by valid flags and allowed border tolerance using anchor_inside_flags', 'clamp a proportional bbox region to feature map boundaries using calc_region with featmap_size']
```

Usage

```
{'convert_targets_by_image_to_feature_levels': 'convert a list of per-image target tensors into per-feature-level tensors using images_to_levels', 'check_anchors_inside_image_border': 'check which anchor boxes fall inside the valid image border using anchor_inside_flags', 'calculate_proportional_bbox_region': 'calculate a proportional bounding box region from a given ratio using calc_region', 'filter_valid_anchors_with_border_tolerance': 'filter anchor boxes by valid flags and allowed border tolerance using anchor_inside_flags', 'clamp_bbox_region_to_feature_map': 'clamp a proportional bbox region to feature map boundaries using calc_region with featmap_size'}
```

