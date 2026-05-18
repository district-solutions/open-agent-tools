# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/models/roi_heads/base_3droi_head.py

Prompts

```
['create a Base3DRoIHead subclass with bbox_head, mask_head, train_cfg, and test_cfg parameters', 'review the Base3DRoIHead forward_train method for training 3D RoI proposals with ground truth bboxes', 'implement the init_weights abstract method in a Base3DRoIHead subclass to load pretrained weights', 'test the Base3DRoIHead simple_test method for inference without augmentation on 3D proposals', 'refactor the Base3DRoIHead aug_test method to support test-time augmentations with rescaling', 'build an H3DRoIHead instance with three primitive heads and a bbox head config', 'test the H3DRoIHead forward_train method to compute primitive and bbox losses', 'test the H3DRoIHead simple_test method to get 3D bounding box predictions', 'refactor the H3DRoIHead init_bbox_head method to support additional head config options', 'review the H3DRoIHead class and its primitive z, xy, and line head pipeline', 'build a PartAggregationROIHead with semantic head, ROI extractors, and bbox head configs for PartA2 3D detection', 'review the PartAggregationROIHead _assign_and_sample method that assigns proposals to ground truth and samples for training', 'refactor the PartAggregationROIHead _bbox_forward method to pool semantic and part features through ROI extractors then predict bboxes']
```

Usage

```
{'init_Base3DRoIHead': 'create a Base3DRoIHead subclass with bbox_head, mask_head, train_cfg, and test_cfg parameters', 'review_Base3DRoIHead_forward_train': 'review the Base3DRoIHead forward_train method for training 3D RoI proposals with ground truth bboxes', 'implement_Base3DRoIHead_init_weights': 'implement the init_weights abstract method in a Base3DRoIHead subclass to load pretrained weights', 'test_Base3DRoIHead_simple_test': 'test the Base3DRoIHead simple_test method for inference without augmentation on 3D proposals', 'refactor_Base3DRoIHead_aug_test': 'refactor the Base3DRoIHead aug_test method to support test-time augmentations with rescaling'}
```

## File: facebookresearch_nerf-det/mmdet3d/models/roi_heads/h3d_roi_head.py

Prompts

```
['create a Base3DRoIHead subclass with bbox_head, mask_head, train_cfg, and test_cfg parameters', 'review the Base3DRoIHead forward_train method for training 3D RoI proposals with ground truth bboxes', 'implement the init_weights abstract method in a Base3DRoIHead subclass to load pretrained weights', 'test the Base3DRoIHead simple_test method for inference without augmentation on 3D proposals', 'refactor the Base3DRoIHead aug_test method to support test-time augmentations with rescaling', 'build an H3DRoIHead instance with three primitive heads and a bbox head config', 'test the H3DRoIHead forward_train method to compute primitive and bbox losses', 'test the H3DRoIHead simple_test method to get 3D bounding box predictions', 'refactor the H3DRoIHead init_bbox_head method to support additional head config options', 'review the H3DRoIHead class and its primitive z, xy, and line head pipeline', 'build a PartAggregationROIHead with semantic head, ROI extractors, and bbox head configs for PartA2 3D detection', 'review the PartAggregationROIHead _assign_and_sample method that assigns proposals to ground truth and samples for training', 'refactor the PartAggregationROIHead _bbox_forward method to pool semantic and part features through ROI extractors then predict bboxes']
```

Usage

```
{'build_H3DRoIHead': 'build an H3DRoIHead instance with three primitive heads and a bbox head config', 'test_forward_train': 'test the H3DRoIHead forward_train method to compute primitive and bbox losses', 'test_simple_test': 'test the H3DRoIHead simple_test method to get 3D bounding box predictions', 'refactor_init_bbox_head': 'refactor the H3DRoIHead init_bbox_head method to support additional head config options', 'review_H3DRoIHead': 'review the H3DRoIHead class and its primitive z, xy, and line head pipeline'}
```

## File: facebookresearch_nerf-det/mmdet3d/models/roi_heads/part_aggregation_roi_head.py

Prompts

```
['create a Base3DRoIHead subclass with bbox_head, mask_head, train_cfg, and test_cfg parameters', 'review the Base3DRoIHead forward_train method for training 3D RoI proposals with ground truth bboxes', 'implement the init_weights abstract method in a Base3DRoIHead subclass to load pretrained weights', 'test the Base3DRoIHead simple_test method for inference without augmentation on 3D proposals', 'refactor the Base3DRoIHead aug_test method to support test-time augmentations with rescaling', 'build an H3DRoIHead instance with three primitive heads and a bbox head config', 'test the H3DRoIHead forward_train method to compute primitive and bbox losses', 'test the H3DRoIHead simple_test method to get 3D bounding box predictions', 'refactor the H3DRoIHead init_bbox_head method to support additional head config options', 'review the H3DRoIHead class and its primitive z, xy, and line head pipeline', 'build a PartAggregationROIHead with semantic head, ROI extractors, and bbox head configs for PartA2 3D detection', 'review the PartAggregationROIHead _assign_and_sample method that assigns proposals to ground truth and samples for training', 'refactor the PartAggregationROIHead _bbox_forward method to pool semantic and part features through ROI extractors then predict bboxes']
```

Usage

```
{'build_PartAggregationROIHead': 'build a PartAggregationROIHead with semantic head, ROI extractors, and bbox head configs for PartA2 3D detection', 'test_forward_train': 'test the PartAggregationROIHead forward_train method with features dict, voxels dict, proposals, and ground truth 3D boxes', 'test_simple_test': 'test the PartAggregationROIHead simple_test method to get 3D bounding box predictions from proposals and features', 'review_assign_and_sample': 'review the PartAggregationROIHead _assign_and_sample method that assigns proposals to ground truth and samples for training', 'refactor_bbox_forward': 'refactor the PartAggregationROIHead _bbox_forward method to pool semantic and part features through ROI extractors then predict bboxes'}
```

