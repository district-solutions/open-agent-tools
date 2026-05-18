# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/core/bbox/coders/anchor_free_bbox_coder.py

Prompts

```
['encode ground truth 3D bounding boxes and labels into center, size, and direction targets', 'decode predicted center, direction class, direction residual, and size into 3D bounding boxes', 'split classification and regression predictions into center offset, size, direction class, and direction residual', 'review the AnchorFreeBBoxCoder class and its encode, decode, and split_pred methods for 3D box coding', 'test the AnchorFreeBBoxCoder encode and decode roundtrip for 3D bounding box predictions', 'decode 3D bounding boxes from CenterPoint heatmap, rotation, height, dimension, and velocity tensors', 'get top-K scoring predictions from a CenterPoint heatmap tensor with class and coordinate info', 'gather feature tensor values at specified index positions for batched data', 'transpose BEV feature tensor from BCHW to BHWC format and gather by index', 'create a CenterPointBBoxCoder instance with pc_range, voxel_size, and output size factor config', 'encode source 3D boxes into transformation deltas relative to ground truth boxes', 'decode transformation deltas back into 3D box coordinates from anchor boxes', 'create a DeltaXYZWLHRBBoxCoder instance with a configurable code size for 3D box encoding', 'encode 3D boxes with extra dimensions beyond the standard 7 parameters', 'decode 3D box deltas that include extra dimensions beyond the standard 7 parameters', 'decode center, size residuals, and size class into axis-aligned bounding box corners', 'split class and regression predicted features into center, direction, size, and objectness components', 'convert continuous yaw angles to discrete direction bins and residuals for encoding']
```

Usage

```
{'encode_gt_bboxes': 'encode ground truth 3D bounding boxes and labels into center, size, and direction targets', 'decode_bbox_predictions': 'decode predicted center, direction class, direction residual, and size into 3D bounding boxes', 'split_predictions': 'split classification and regression predictions into center offset, size, direction class, and direction residual', 'review_AnchorFreeBBoxCoder': 'review the AnchorFreeBBoxCoder class and its encode, decode, and split_pred methods for 3D box coding', 'test_AnchorFreeBBoxCoder': 'test the AnchorFreeBBoxCoder encode and decode roundtrip for 3D bounding box predictions'}
```

## File: facebookresearch_nerf-det/mmdet3d/core/bbox/coders/centerpoint_bbox_coders.py

Prompts

```
['encode ground truth 3D bounding boxes and labels into center, size, and direction targets', 'decode predicted center, direction class, direction residual, and size into 3D bounding boxes', 'split classification and regression predictions into center offset, size, direction class, and direction residual', 'review the AnchorFreeBBoxCoder class and its encode, decode, and split_pred methods for 3D box coding', 'test the AnchorFreeBBoxCoder encode and decode roundtrip for 3D bounding box predictions', 'decode 3D bounding boxes from CenterPoint heatmap, rotation, height, dimension, and velocity tensors', 'get top-K scoring predictions from a CenterPoint heatmap tensor with class and coordinate info', 'gather feature tensor values at specified index positions for batched data', 'transpose BEV feature tensor from BCHW to BHWC format and gather by index', 'create a CenterPointBBoxCoder instance with pc_range, voxel_size, and output size factor config', 'encode source 3D boxes into transformation deltas relative to ground truth boxes', 'decode transformation deltas back into 3D box coordinates from anchor boxes', 'create a DeltaXYZWLHRBBoxCoder instance with a configurable code size for 3D box encoding', 'encode 3D boxes with extra dimensions beyond the standard 7 parameters', 'decode 3D box deltas that include extra dimensions beyond the standard 7 parameters', 'decode center, size residuals, and size class into axis-aligned bounding box corners', 'split class and regression predicted features into center, direction, size, and objectness components', 'convert continuous yaw angles to discrete direction bins and residuals for encoding']
```

Usage

```
{'decode_3d_bboxes_from_centerpoint_outputs': 'decode 3D bounding boxes from CenterPoint heatmap, rotation, height, dimension, and velocity tensors', 'topk_scores_from_heatmap': 'get top-K scoring predictions from a CenterPoint heatmap tensor with class and coordinate info', 'gather_features_by_index': 'gather feature tensor values at specified index positions for batched data', 'transpose_and_gather_bev_features': 'transpose BEV feature tensor from BCHW to BHWC format and gather by index', 'create_centerpoint_bbox_coder': 'create a CenterPointBBoxCoder instance with pc_range, voxel_size, and output size factor config'}
```

## File: facebookresearch_nerf-det/mmdet3d/core/bbox/coders/delta_xyzwhlr_bbox_coder.py

Prompts

```
['encode ground truth 3D bounding boxes and labels into center, size, and direction targets', 'decode predicted center, direction class, direction residual, and size into 3D bounding boxes', 'split classification and regression predictions into center offset, size, direction class, and direction residual', 'review the AnchorFreeBBoxCoder class and its encode, decode, and split_pred methods for 3D box coding', 'test the AnchorFreeBBoxCoder encode and decode roundtrip for 3D bounding box predictions', 'decode 3D bounding boxes from CenterPoint heatmap, rotation, height, dimension, and velocity tensors', 'get top-K scoring predictions from a CenterPoint heatmap tensor with class and coordinate info', 'gather feature tensor values at specified index positions for batched data', 'transpose BEV feature tensor from BCHW to BHWC format and gather by index', 'create a CenterPointBBoxCoder instance with pc_range, voxel_size, and output size factor config', 'encode source 3D boxes into transformation deltas relative to ground truth boxes', 'decode transformation deltas back into 3D box coordinates from anchor boxes', 'create a DeltaXYZWLHRBBoxCoder instance with a configurable code size for 3D box encoding', 'encode 3D boxes with extra dimensions beyond the standard 7 parameters', 'decode 3D box deltas that include extra dimensions beyond the standard 7 parameters', 'decode center, size residuals, and size class into axis-aligned bounding box corners', 'split class and regression predicted features into center, direction, size, and objectness components', 'convert continuous yaw angles to discrete direction bins and residuals for encoding']
```

Usage

```
{'encode_3d_bbox_deltas': 'encode source 3D boxes into transformation deltas relative to ground truth boxes', 'decode_3d_bbox_deltas': 'decode transformation deltas back into 3D box coordinates from anchor boxes', 'create_bbox_coder': 'create a DeltaXYZWLHRBBoxCoder instance with a configurable code size for 3D box encoding', 'encode_extra_dimensions': 'encode 3D boxes with extra dimensions beyond the standard 7 parameters', 'decode_extra_dimensions': 'decode 3D box deltas that include extra dimensions beyond the standard 7 parameters'}
```

## File: facebookresearch_nerf-det/mmdet3d/core/bbox/coders/partial_bin_based_bbox_coder.py

Prompts

```
['encode ground truth 3D bounding boxes and labels into center, size, and direction targets', 'decode predicted center, direction class, direction residual, and size into 3D bounding boxes', 'split classification and regression predictions into center offset, size, direction class, and direction residual', 'review the AnchorFreeBBoxCoder class and its encode, decode, and split_pred methods for 3D box coding', 'test the AnchorFreeBBoxCoder encode and decode roundtrip for 3D bounding box predictions', 'decode 3D bounding boxes from CenterPoint heatmap, rotation, height, dimension, and velocity tensors', 'get top-K scoring predictions from a CenterPoint heatmap tensor with class and coordinate info', 'gather feature tensor values at specified index positions for batched data', 'transpose BEV feature tensor from BCHW to BHWC format and gather by index', 'create a CenterPointBBoxCoder instance with pc_range, voxel_size, and output size factor config', 'encode source 3D boxes into transformation deltas relative to ground truth boxes', 'decode transformation deltas back into 3D box coordinates from anchor boxes', 'create a DeltaXYZWLHRBBoxCoder instance with a configurable code size for 3D box encoding', 'encode 3D boxes with extra dimensions beyond the standard 7 parameters', 'decode 3D box deltas that include extra dimensions beyond the standard 7 parameters', 'decode center, size residuals, and size class into axis-aligned bounding box corners', 'split class and regression predicted features into center, direction, size, and objectness components', 'convert continuous yaw angles to discrete direction bins and residuals for encoding']
```

Usage

```
{'encode_gt_bboxes': 'encode ground truth 3D bounding boxes and labels into center, size, and direction targets', 'decode_bbox_predictions': 'decode predicted center, direction class, direction residual, size class, and size residual into 3D bboxes', 'decode_bbox_corners': 'decode center, size residuals, and size class into axis-aligned bounding box corners', 'split_regression_predictions': 'split class and regression predicted features into center, direction, size, and objectness components', 'convert_angle_to_class': 'convert continuous yaw angles to discrete direction bins and residuals for encoding'}
```

