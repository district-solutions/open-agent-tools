# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/det/mmdet/models/seg_heads/base_semantic_head.py

Prompts

```
['build a BaseSemanticHead subclass with num_classes and CrossEntropyLoss for semantic segmentation', 'review the abstract forward method that returns seg_preds and feats from feature maps', 'review the abstract loss method that computes semantic segmentation loss from feature maps and data samples', 'test the predict method to get semantic segmentation logits with optional rescaling to original image shape', 'refactor the BaseSemanticHead constructor to customize seg_rescale_factor and loss_seg configuration', 'build a PanopticFPNHead model for panoptic segmentation with configurable thing and stuff classes', 'run forward pass on multi-scale feature maps to get semantic segmentation predictions', 'compute segmentation loss by comparing predictions against ground truth semantic segmentation labels', 'merge thing classes into a single void class for panoptic segmentation ground truth labels', 'initialize PanopticFPNHead convolution logits weights with normal distribution and zero bias']
```

Usage

```
{'build_BaseSemanticHead': 'build a BaseSemanticHead subclass with num_classes and CrossEntropyLoss for semantic segmentation', 'review_BaseSemanticHead_forward': 'review the abstract forward method that returns seg_preds and feats from feature maps', 'review_BaseSemanticHead_loss': 'review the abstract loss method that computes semantic segmentation loss from feature maps and data samples', 'test_BaseSemanticHead_predict': 'test the predict method to get semantic segmentation logits with optional rescaling to original image shape', 'refactor_BaseSemanticHead_init': 'refactor the BaseSemanticHead constructor to customize seg_rescale_factor and loss_seg configuration'}
```

## File: facebookresearch_sapiens/det/mmdet/models/seg_heads/panoptic_fpn_head.py

Prompts

```
['build a BaseSemanticHead subclass with num_classes and CrossEntropyLoss for semantic segmentation', 'review the abstract forward method that returns seg_preds and feats from feature maps', 'review the abstract loss method that computes semantic segmentation loss from feature maps and data samples', 'test the predict method to get semantic segmentation logits with optional rescaling to original image shape', 'refactor the BaseSemanticHead constructor to customize seg_rescale_factor and loss_seg configuration', 'build a PanopticFPNHead model for panoptic segmentation with configurable thing and stuff classes', 'run forward pass on multi-scale feature maps to get semantic segmentation predictions', 'compute segmentation loss by comparing predictions against ground truth semantic segmentation labels', 'merge thing classes into a single void class for panoptic segmentation ground truth labels', 'initialize PanopticFPNHead convolution logits weights with normal distribution and zero bias']
```

Usage

```
{'build_panoptic_fpn_head': 'build a PanopticFPNHead model for panoptic segmentation with configurable thing and stuff classes', 'forward_panoptic_fpn_head': 'run forward pass on multi-scale feature maps to get semantic segmentation predictions', 'loss_panoptic_fpn_head': 'compute segmentation loss by comparing predictions against ground truth semantic segmentation labels', 'set_things_to_void': 'merge thing classes into a single void class for panoptic segmentation ground truth labels', 'init_weights_panoptic_fpn_head': 'initialize PanopticFPNHead convolution logits weights with normal distribution and zero bias'}
```

