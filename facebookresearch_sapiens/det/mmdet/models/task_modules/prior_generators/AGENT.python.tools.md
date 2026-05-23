# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/det/mmdet/models/task_modules/prior_generators/anchor_generator.py

Prompts

```
['generate grid anchors across multiple feature levels using AnchorGenerator.grid_priors with given featmap sizes', 'generate sparse anchors for specific prior indices using AnchorGenerator.sparse_priors on a single feature level', 'generate SSD-style anchors with min/max sizes and ratios using SSDAnchorGenerator for object detection', 'generate YOLO-style anchors with predefined base sizes per level using YOLOAnchorGenerator for detection', 'generate valid flags for anchors within padded image bounds using AnchorGenerator.valid_flags to filter out-of-bounds anchors', 'build a multi-level point generator to generate grid priors for feature maps with configurable strides', 'create a single-level point generator to generate grid points for a feature map with a given stride', 'test the multi-level point generator valid flags method to filter points within padded image shape', 'refactor the sparse priors method to generate points from prior indices for a specific feature level', 'review the single level grid priors method that generates points with optional stride concatenation', 'check whether anchors are inside the image border using anchor_inside_flags with flat_anchors and valid_flags', 'filter anchors by allowed border using anchor_inside_flags with a custom allowed_border value', 'calculate a proportional bounding box region using calc_region with a given ratio and bbox tensor', 'calculate a proportional bbox region clipped to feature map size using calc_region with featmap_size', 'review the anchor_inside_flags and calc_region utility functions for object detection prior generation']
```

Usage

```
{'generate_grid_anchors': 'generate grid anchors across multiple feature levels using AnchorGenerator.grid_priors with given featmap sizes', 'generate_sparse_anchors': 'generate sparse anchors for specific prior indices using AnchorGenerator.sparse_priors on a single feature level', 'generate_ssd_anchors': 'generate SSD-style anchors with min/max sizes and ratios using SSDAnchorGenerator for object detection', 'generate_yolo_anchors': 'generate YOLO-style anchors with predefined base sizes per level using YOLOAnchorGenerator for detection', 'generate_valid_flags': 'generate valid flags for anchors within padded image bounds using AnchorGenerator.valid_flags to filter out-of-bounds anchors'}
```

## File: facebookresearch_sapiens/det/mmdet/models/task_modules/prior_generators/point_generator.py

Prompts

```
['generate grid anchors across multiple feature levels using AnchorGenerator.grid_priors with given featmap sizes', 'generate sparse anchors for specific prior indices using AnchorGenerator.sparse_priors on a single feature level', 'generate SSD-style anchors with min/max sizes and ratios using SSDAnchorGenerator for object detection', 'generate YOLO-style anchors with predefined base sizes per level using YOLOAnchorGenerator for detection', 'generate valid flags for anchors within padded image bounds using AnchorGenerator.valid_flags to filter out-of-bounds anchors', 'build a multi-level point generator to generate grid priors for feature maps with configurable strides', 'create a single-level point generator to generate grid points for a feature map with a given stride', 'test the multi-level point generator valid flags method to filter points within padded image shape', 'refactor the sparse priors method to generate points from prior indices for a specific feature level', 'review the single level grid priors method that generates points with optional stride concatenation', 'check whether anchors are inside the image border using anchor_inside_flags with flat_anchors and valid_flags', 'filter anchors by allowed border using anchor_inside_flags with a custom allowed_border value', 'calculate a proportional bounding box region using calc_region with a given ratio and bbox tensor', 'calculate a proportional bbox region clipped to feature map size using calc_region with featmap_size', 'review the anchor_inside_flags and calc_region utility functions for object detection prior generation']
```

Usage

```
{'build_MlvlPointGenerator_grid_priors': 'build a multi-level point generator to generate grid priors for feature maps with configurable strides', 'create_PointGenerator_grid_points': 'create a single-level point generator to generate grid points for a feature map with a given stride', 'test_MlvlPointGenerator_valid_flags': 'test the multi-level point generator valid flags method to filter points within padded image shape', 'refactor_MlvlPointGenerator_sparse_priors': 'refactor the sparse priors method to generate points from prior indices for a specific feature level', 'review_MlvlPointGenerator_single_level_grid_priors': 'review the single level grid priors method that generates points with optional stride concatenation'}
```

## File: facebookresearch_sapiens/det/mmdet/models/task_modules/prior_generators/utils.py

Prompts

```
['generate grid anchors across multiple feature levels using AnchorGenerator.grid_priors with given featmap sizes', 'generate sparse anchors for specific prior indices using AnchorGenerator.sparse_priors on a single feature level', 'generate SSD-style anchors with min/max sizes and ratios using SSDAnchorGenerator for object detection', 'generate YOLO-style anchors with predefined base sizes per level using YOLOAnchorGenerator for detection', 'generate valid flags for anchors within padded image bounds using AnchorGenerator.valid_flags to filter out-of-bounds anchors', 'build a multi-level point generator to generate grid priors for feature maps with configurable strides', 'create a single-level point generator to generate grid points for a feature map with a given stride', 'test the multi-level point generator valid flags method to filter points within padded image shape', 'refactor the sparse priors method to generate points from prior indices for a specific feature level', 'review the single level grid priors method that generates points with optional stride concatenation', 'check whether anchors are inside the image border using anchor_inside_flags with flat_anchors and valid_flags', 'filter anchors by allowed border using anchor_inside_flags with a custom allowed_border value', 'calculate a proportional bounding box region using calc_region with a given ratio and bbox tensor', 'calculate a proportional bbox region clipped to feature map size using calc_region with featmap_size', 'review the anchor_inside_flags and calc_region utility functions for object detection prior generation']
```

Usage

```
{'check_anchor_inside_flags': 'check whether anchors are inside the image border using anchor_inside_flags with flat_anchors and valid_flags', 'filter_anchors_by_border': 'filter anchors by allowed border using anchor_inside_flags with a custom allowed_border value', 'calculate_proportional_bbox_region': 'calculate a proportional bounding box region using calc_region with a given ratio and bbox tensor', 'calculate_region_with_clipping': 'calculate a proportional bbox region clipped to feature map size using calc_region with featmap_size', 'review_anchor_utils': 'review the anchor_inside_flags and calc_region utility functions for object detection prior generation'}
```

