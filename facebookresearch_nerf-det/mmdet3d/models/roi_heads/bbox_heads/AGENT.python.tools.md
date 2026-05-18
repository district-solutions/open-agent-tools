# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/models/roi_heads/bbox_heads/h3d_bbox_head.py

Prompts

```
['build an H3DBboxHead instance with surface and line matching configs for 3D bbox refinement', 'run the H3DBboxHead forward pass to predict surface centers, line centers, and matching scores', 'compute the H3DBboxHead loss including primitive objectness, semantic, and centroid regression losses', 'generate 3D bounding boxes from H3DBboxHead predictions using multi-class NMS and score filtering', 'generate training targets for primitive cues including objectness labels and surface line centers', 'build a PartA2BboxHead instance with num_classes, seg_in_channels, part_in_channels, and conv channel configs', 'run forward pass on PartA2BboxHead with seg_feats and part_feats sparse tensors to get cls_score and bbox_pred', 'compute classification, bbox regression, and corner losses for PartA2BboxHead using rois, labels, and bbox targets', 'generate training targets including labels, bbox_targets, reg_mask, and weights from sampling results and rcnn config', 'decode and apply multi-class NMS to PartA2BboxHead predictions to return selected bboxes, scores, and labels']
```

Usage

```
{'build_H3DBboxHead': 'build an H3DBboxHead instance with surface and line matching configs for 3D bbox refinement', 'forward_H3DBboxHead': 'run the H3DBboxHead forward pass to predict surface centers, line centers, and matching scores', 'loss_H3DBboxHead': 'compute the H3DBboxHead loss including primitive objectness, semantic, and centroid regression losses', 'get_bboxes_H3DBboxHead': 'generate 3D bounding boxes from H3DBboxHead predictions using multi-class NMS and score filtering', 'get_targets_H3DBboxHead': 'generate training targets for primitive cues including objectness labels and surface line centers'}
```

## File: facebookresearch_nerf-det/mmdet3d/models/roi_heads/bbox_heads/parta2_bbox_head.py

Prompts

```
['build an H3DBboxHead instance with surface and line matching configs for 3D bbox refinement', 'run the H3DBboxHead forward pass to predict surface centers, line centers, and matching scores', 'compute the H3DBboxHead loss including primitive objectness, semantic, and centroid regression losses', 'generate 3D bounding boxes from H3DBboxHead predictions using multi-class NMS and score filtering', 'generate training targets for primitive cues including objectness labels and surface line centers', 'build a PartA2BboxHead instance with num_classes, seg_in_channels, part_in_channels, and conv channel configs', 'run forward pass on PartA2BboxHead with seg_feats and part_feats sparse tensors to get cls_score and bbox_pred', 'compute classification, bbox regression, and corner losses for PartA2BboxHead using rois, labels, and bbox targets', 'generate training targets including labels, bbox_targets, reg_mask, and weights from sampling results and rcnn config', 'decode and apply multi-class NMS to PartA2BboxHead predictions to return selected bboxes, scores, and labels']
```

Usage

```
{'build_PartA2BboxHead': 'build a PartA2BboxHead instance with num_classes, seg_in_channels, part_in_channels, and conv channel configs', 'forward_PartA2BboxHead': 'run forward pass on PartA2BboxHead with seg_feats and part_feats sparse tensors to get cls_score and bbox_pred', 'loss_PartA2BboxHead': 'compute classification, bbox regression, and corner losses for PartA2BboxHead using rois, labels, and bbox targets', 'get_targets_PartA2BboxHead': 'generate training targets including labels, bbox_targets, reg_mask, and weights from sampling results and rcnn config', 'get_bboxes_PartA2BboxHead': 'decode and apply multi-class NMS to PartA2BboxHead predictions to return selected bboxes, scores, and labels'}
```

