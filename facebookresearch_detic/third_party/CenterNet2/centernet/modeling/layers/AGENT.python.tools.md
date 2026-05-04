# Agent Python Tools

- repo: facebookresearch/detic
- repo_uri: https://github.com/facebookresearch/detic

## File: facebookresearch_detic/third_party/CenterNet2/centernet/modeling/layers/deform_conv.py

Prompts

```
['create a DFConv2d layer with modulated deformable convolution for feature extraction in object detection', 'create a DFConv2d layer with standard deformable convolution without modulation for spatial feature learning', 'build a forward pass through DFConv2d that applies deformable convolution to input feature maps', 'test the DFConv2d forward method with return_offset to inspect learned spatial offsets', 'review the _NewEmptyTensorOp autograd function that handles empty tensor shape propagation during backprop', 'build a RetinaNet-style focal loss for multi-class heatmap predictions with configurable alpha, beta, and gamma parameters', 'run a binary focal loss computation for single-channel heatmap predictions with positive and negative loss separation', 'test the TorchScript-compiled version of heatmap focal loss for optimized inference performance', 'refactor heatmap_focal_loss and binary_heatmap_focal_loss into a single unified function as noted in the TODO comment', 'review the ignore_high_fp parameter that filters high false positive predictions from the negative loss calculation', 'build a PyTorch module using IOULoss to compute IoU loss between predicted and target bounding boxes', 'create a function call to giou_loss that computes generalized IoU loss between two sets of XYXY format boxes', 'test the IOULoss forward pass with predicted and target bounding box tensors and optional weights', 'refactor the IOULoss class to support additional reduction modes beyond sum, batch, and none', 'review the giou_loss function implementation for numerical stability and correct handling of non-overlapping boxes', 'run non-maximum suppression on a boxlist with a specified IoU threshold', 'test ml_nms with a boxlist containing pred_boxes and pred_classes fields', 'refactor ml_nms to cap results with max_proposals after suppression', 'review ml_nms which uses detectron2 batched_nms for multi-label NMS', 'summarize ml_nms that filters overlapping boxes by score and label using batched NMS']
```

Usage

```
{'create_DFConv2d_modulated': 'create a DFConv2d layer with modulated deformable convolution for feature extraction in object detection', 'create_DFConv2d_standard': 'create a DFConv2d layer with standard deformable convolution without modulation for spatial feature learning', 'build_DFConv2d_forward': 'build a forward pass through DFConv2d that applies deformable convolution to input feature maps', 'test_DFConv2d_offset': 'test the DFConv2d forward method with return_offset to inspect learned spatial offsets', 'review_NewEmptyTensorOp': 'review the _NewEmptyTensorOp autograd function that handles empty tensor shape propagation during backprop'}
```

## File: facebookresearch_detic/third_party/CenterNet2/centernet/modeling/layers/heatmap_focal_loss.py

Prompts

```
['create a DFConv2d layer with modulated deformable convolution for feature extraction in object detection', 'create a DFConv2d layer with standard deformable convolution without modulation for spatial feature learning', 'build a forward pass through DFConv2d that applies deformable convolution to input feature maps', 'test the DFConv2d forward method with return_offset to inspect learned spatial offsets', 'review the _NewEmptyTensorOp autograd function that handles empty tensor shape propagation during backprop', 'build a RetinaNet-style focal loss for multi-class heatmap predictions with configurable alpha, beta, and gamma parameters', 'run a binary focal loss computation for single-channel heatmap predictions with positive and negative loss separation', 'test the TorchScript-compiled version of heatmap focal loss for optimized inference performance', 'refactor heatmap_focal_loss and binary_heatmap_focal_loss into a single unified function as noted in the TODO comment', 'review the ignore_high_fp parameter that filters high false positive predictions from the negative loss calculation', 'build a PyTorch module using IOULoss to compute IoU loss between predicted and target bounding boxes', 'create a function call to giou_loss that computes generalized IoU loss between two sets of XYXY format boxes', 'test the IOULoss forward pass with predicted and target bounding box tensors and optional weights', 'refactor the IOULoss class to support additional reduction modes beyond sum, batch, and none', 'review the giou_loss function implementation for numerical stability and correct handling of non-overlapping boxes', 'run non-maximum suppression on a boxlist with a specified IoU threshold', 'test ml_nms with a boxlist containing pred_boxes and pred_classes fields', 'refactor ml_nms to cap results with max_proposals after suppression', 'review ml_nms which uses detectron2 batched_nms for multi-label NMS', 'summarize ml_nms that filters overlapping boxes by score and label using batched NMS']
```

Usage

```
{'build_heatmap_focal_loss': 'build a RetinaNet-style focal loss for multi-class heatmap predictions with configurable alpha, beta, and gamma parameters', 'run_binary_heatmap_focal_loss': 'run a binary focal loss computation for single-channel heatmap predictions with positive and negative loss separation', 'test_heatmap_focal_loss_jit': 'test the TorchScript-compiled version of heatmap focal loss for optimized inference performance', 'refactor_heatmap_focal_loss': 'refactor heatmap_focal_loss and binary_heatmap_focal_loss into a single unified function as noted in the TODO comment', 'review_ignore_high_fp': 'review the ignore_high_fp parameter that filters high false positive predictions from the negative loss calculation'}
```

## File: facebookresearch_detic/third_party/CenterNet2/centernet/modeling/layers/iou_loss.py

Prompts

```
['create a DFConv2d layer with modulated deformable convolution for feature extraction in object detection', 'create a DFConv2d layer with standard deformable convolution without modulation for spatial feature learning', 'build a forward pass through DFConv2d that applies deformable convolution to input feature maps', 'test the DFConv2d forward method with return_offset to inspect learned spatial offsets', 'review the _NewEmptyTensorOp autograd function that handles empty tensor shape propagation during backprop', 'build a RetinaNet-style focal loss for multi-class heatmap predictions with configurable alpha, beta, and gamma parameters', 'run a binary focal loss computation for single-channel heatmap predictions with positive and negative loss separation', 'test the TorchScript-compiled version of heatmap focal loss for optimized inference performance', 'refactor heatmap_focal_loss and binary_heatmap_focal_loss into a single unified function as noted in the TODO comment', 'review the ignore_high_fp parameter that filters high false positive predictions from the negative loss calculation', 'build a PyTorch module using IOULoss to compute IoU loss between predicted and target bounding boxes', 'create a function call to giou_loss that computes generalized IoU loss between two sets of XYXY format boxes', 'test the IOULoss forward pass with predicted and target bounding box tensors and optional weights', 'refactor the IOULoss class to support additional reduction modes beyond sum, batch, and none', 'review the giou_loss function implementation for numerical stability and correct handling of non-overlapping boxes', 'run non-maximum suppression on a boxlist with a specified IoU threshold', 'test ml_nms with a boxlist containing pred_boxes and pred_classes fields', 'refactor ml_nms to cap results with max_proposals after suppression', 'review ml_nms which uses detectron2 batched_nms for multi-label NMS', 'summarize ml_nms that filters overlapping boxes by score and label using batched NMS']
```

Usage

```
{'build_iou_loss_module': 'build a PyTorch module using IOULoss to compute IoU loss between predicted and target bounding boxes', 'create_giou_loss_function': 'create a function call to giou_loss that computes generalized IoU loss between two sets of XYXY format boxes', 'test_IOULoss_forward': 'test the IOULoss forward pass with predicted and target bounding box tensors and optional weights', 'refactor_IOULoss_reduction': 'refactor the IOULoss class to support additional reduction modes beyond sum, batch, and none', 'review_giou_loss_implementation': 'review the giou_loss function implementation for numerical stability and correct handling of non-overlapping boxes'}
```

## File: facebookresearch_detic/third_party/CenterNet2/centernet/modeling/layers/ml_nms.py

Prompts

```
['create a DFConv2d layer with modulated deformable convolution for feature extraction in object detection', 'create a DFConv2d layer with standard deformable convolution without modulation for spatial feature learning', 'build a forward pass through DFConv2d that applies deformable convolution to input feature maps', 'test the DFConv2d forward method with return_offset to inspect learned spatial offsets', 'review the _NewEmptyTensorOp autograd function that handles empty tensor shape propagation during backprop', 'build a RetinaNet-style focal loss for multi-class heatmap predictions with configurable alpha, beta, and gamma parameters', 'run a binary focal loss computation for single-channel heatmap predictions with positive and negative loss separation', 'test the TorchScript-compiled version of heatmap focal loss for optimized inference performance', 'refactor heatmap_focal_loss and binary_heatmap_focal_loss into a single unified function as noted in the TODO comment', 'review the ignore_high_fp parameter that filters high false positive predictions from the negative loss calculation', 'build a PyTorch module using IOULoss to compute IoU loss between predicted and target bounding boxes', 'create a function call to giou_loss that computes generalized IoU loss between two sets of XYXY format boxes', 'test the IOULoss forward pass with predicted and target bounding box tensors and optional weights', 'refactor the IOULoss class to support additional reduction modes beyond sum, batch, and none', 'review the giou_loss function implementation for numerical stability and correct handling of non-overlapping boxes', 'run non-maximum suppression on a boxlist with a specified IoU threshold', 'test ml_nms with a boxlist containing pred_boxes and pred_classes fields', 'refactor ml_nms to cap results with max_proposals after suppression', 'review ml_nms which uses detectron2 batched_nms for multi-label NMS', 'summarize ml_nms that filters overlapping boxes by score and label using batched NMS']
```

Usage

```
{'run_ml_nms': 'run non-maximum suppression on a boxlist with a specified IoU threshold', 'test_ml_nms': 'test ml_nms with a boxlist containing pred_boxes and pred_classes fields', 'refactor_ml_nms': 'refactor ml_nms to cap results with max_proposals after suppression', 'review_ml_nms': 'review ml_nms which uses detectron2 batched_nms for multi-label NMS', 'summarize_ml_nms': 'summarize ml_nms that filters overlapping boxes by score and label using batched NMS'}
```

