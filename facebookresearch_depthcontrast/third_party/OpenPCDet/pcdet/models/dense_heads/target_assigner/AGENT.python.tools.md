# Agent Python Tools

- repo: facebookresearch/depthcontrast
- repo_uri: https://github.com/facebookresearch/depthcontrast

## File: facebookresearch_depthcontrast/third_party/OpenPCDet/pcdet/models/dense_heads/target_assigner/anchor_generator.py

Prompts

```
['generate 3D anchors for a given grid size using the AnchorGenerator class', 'create an AnchorGenerator with anchor sizes, rotations, and heights from a config list', 'review the AnchorGenerator anchor range parameters for x, y, and z bounding box limits', 'test the AnchorGenerator align_center option to shift anchor positions by half stride', 'summarize the AnchorGenerator output tensor shape of z, y, x, num_size, num_rot, 7', 'build an ATSSTargetAssigner instance with a topk value, box coder, and optional height matching flag', 'run assign_targets on a list of anchors and ground truth boxes to get classification labels and regression targets', 'run assign_targets_single on anchors and ground truth boxes to compute per-sample cls labels, reg targets, and reg weights', 'review the ATSSTargetAssigner class and its adaptive IoU thresholding logic using mean plus standard deviation per ground truth box', 'refactor the ATSSTargetAssigner assign_targets method to support multihead anchor permutation and flattened anchor processing', 'build an AxisAlignedTargetAssigner instance with model config, class names, and box coder for 3D anchor target assignment', 'assign classification labels and regression targets to anchors across a batch of ground truth 3D boxes', 'assign targets to anchors for a single sample using IoU thresholds and optional foreground sampling', 'review the AxisAlignedTargetAssigner match_height flag to toggle between 3D IoU and BEV nearest IoU matching', 'refactor the AxisAlignedTargetAssigner to enable or disable multihead and separate multihead RPN configurations']
```

Usage

```
{'generate_anchors_for_grid': 'generate 3D anchors for a given grid size using the AnchorGenerator class', 'create_anchor_generator_config': 'create an AnchorGenerator with anchor sizes, rotations, and heights from a config list', 'review_anchor_range_setup': 'review the AnchorGenerator anchor range parameters for x, y, and z bounding box limits', 'test_anchor_center_alignment': 'test the AnchorGenerator align_center option to shift anchor positions by half stride', 'summarize_anchor_tensor_shape': 'summarize the AnchorGenerator output tensor shape of z, y, x, num_size, num_rot, 7'}
```

## File: facebookresearch_depthcontrast/third_party/OpenPCDet/pcdet/models/dense_heads/target_assigner/atss_target_assigner.py

Prompts

```
['generate 3D anchors for a given grid size using the AnchorGenerator class', 'create an AnchorGenerator with anchor sizes, rotations, and heights from a config list', 'review the AnchorGenerator anchor range parameters for x, y, and z bounding box limits', 'test the AnchorGenerator align_center option to shift anchor positions by half stride', 'summarize the AnchorGenerator output tensor shape of z, y, x, num_size, num_rot, 7', 'build an ATSSTargetAssigner instance with a topk value, box coder, and optional height matching flag', 'run assign_targets on a list of anchors and ground truth boxes to get classification labels and regression targets', 'run assign_targets_single on anchors and ground truth boxes to compute per-sample cls labels, reg targets, and reg weights', 'review the ATSSTargetAssigner class and its adaptive IoU thresholding logic using mean plus standard deviation per ground truth box', 'refactor the ATSSTargetAssigner assign_targets method to support multihead anchor permutation and flattened anchor processing', 'build an AxisAlignedTargetAssigner instance with model config, class names, and box coder for 3D anchor target assignment', 'assign classification labels and regression targets to anchors across a batch of ground truth 3D boxes', 'assign targets to anchors for a single sample using IoU thresholds and optional foreground sampling', 'review the AxisAlignedTargetAssigner match_height flag to toggle between 3D IoU and BEV nearest IoU matching', 'refactor the AxisAlignedTargetAssigner to enable or disable multihead and separate multihead RPN configurations']
```

Usage

```
{'build_ATSSTargetAssigner': 'build an ATSSTargetAssigner instance with a topk value, box coder, and optional height matching flag', 'run_assign_targets': 'run assign_targets on a list of anchors and ground truth boxes to get classification labels and regression targets', 'run_assign_targets_single': 'run assign_targets_single on anchors and ground truth boxes to compute per-sample cls labels, reg targets, and reg weights', 'review_ATSSTargetAssigner_IOU_thresholding': 'review the ATSSTargetAssigner class and its adaptive IoU thresholding logic using mean plus standard deviation per ground truth box', 'refactor_ATSSTargetAssigner_multihead': 'refactor the ATSSTargetAssigner assign_targets method to support multihead anchor permutation and flattened anchor processing'}
```

## File: facebookresearch_depthcontrast/third_party/OpenPCDet/pcdet/models/dense_heads/target_assigner/axis_aligned_target_assigner.py

Prompts

```
['generate 3D anchors for a given grid size using the AnchorGenerator class', 'create an AnchorGenerator with anchor sizes, rotations, and heights from a config list', 'review the AnchorGenerator anchor range parameters for x, y, and z bounding box limits', 'test the AnchorGenerator align_center option to shift anchor positions by half stride', 'summarize the AnchorGenerator output tensor shape of z, y, x, num_size, num_rot, 7', 'build an ATSSTargetAssigner instance with a topk value, box coder, and optional height matching flag', 'run assign_targets on a list of anchors and ground truth boxes to get classification labels and regression targets', 'run assign_targets_single on anchors and ground truth boxes to compute per-sample cls labels, reg targets, and reg weights', 'review the ATSSTargetAssigner class and its adaptive IoU thresholding logic using mean plus standard deviation per ground truth box', 'refactor the ATSSTargetAssigner assign_targets method to support multihead anchor permutation and flattened anchor processing', 'build an AxisAlignedTargetAssigner instance with model config, class names, and box coder for 3D anchor target assignment', 'assign classification labels and regression targets to anchors across a batch of ground truth 3D boxes', 'assign targets to anchors for a single sample using IoU thresholds and optional foreground sampling', 'review the AxisAlignedTargetAssigner match_height flag to toggle between 3D IoU and BEV nearest IoU matching', 'refactor the AxisAlignedTargetAssigner to enable or disable multihead and separate multihead RPN configurations']
```

Usage

```
{'build_target_assigner': 'build an AxisAlignedTargetAssigner instance with model config, class names, and box coder for 3D anchor target assignment', 'assign_targets_batch': 'assign classification labels and regression targets to anchors across a batch of ground truth 3D boxes', 'assign_targets_single': 'assign targets to anchors for a single sample using IoU thresholds and optional foreground sampling', 'review_match_height': 'review the AxisAlignedTargetAssigner match_height flag to toggle between 3D IoU and BEV nearest IoU matching', 'refactor_multihead': 'refactor the AxisAlignedTargetAssigner to enable or disable multihead and separate multihead RPN configurations'}
```

