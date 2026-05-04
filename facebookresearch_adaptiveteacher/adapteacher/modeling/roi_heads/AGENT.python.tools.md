# Agent Python Tools

- repo: facebookresearch/adaptiveteacher
- repo_uri: https://github.com/facebookresearch/adaptive_teacher

## File: facebookresearch_adaptiveteacher/adapteacher/modeling/roi_heads/fast_rcnn.py

Prompts

```
['build a FocalLoss nn.Module that computes focal loss with configurable gamma and num_classes parameters', 'create a FastRCNNFocalLoss instance to compute classification and box regression losses for ROI proposals', 'review the FastRCNNFocaltLossOutputLayers class that extends FastRCNNOutputLayers with focal loss support', 'test the FocalLoss forward method by passing input logits and target class labels', 'refactor the FastRCNNFocalLoss losses method to customize classification and box regression loss computation', 'build a StandardROIHeadsPseudoLab ROI head for pseudo labeling in Detectron2 object detection models', 'initialize a box head with CrossEntropy or FocalLoss predictor using _init_box_head class method', 'run the forward pass of StandardROIHeadsPseudoLab with training loss computation and proposal sampling', 'run the forward pass of StandardROIHeadsPseudoLab for inference to get predicted instances and predictions', 'label and sample proposals by matching against ground truth boxes using pairwise IoU and proposal matcher']
```

Usage

```
{'build_focal_loss_module': 'build a FocalLoss nn.Module that computes focal loss with configurable gamma and num_classes parameters', 'create_fast_rcnn_focal_loss': 'create a FastRCNNFocalLoss instance to compute classification and box regression losses for ROI proposals', 'review_fast_rcnn_focal_loss_output_layers': 'review the FastRCNNFocaltLossOutputLayers class that extends FastRCNNOutputLayers with focal loss support', 'test_focal_loss_forward': 'test the FocalLoss forward method by passing input logits and target class labels', 'refactor_fast_rcnn_loss_computation': 'refactor the FastRCNNFocalLoss losses method to customize classification and box regression loss computation'}
```

## File: facebookresearch_adaptiveteacher/adapteacher/modeling/roi_heads/roi_heads.py

Prompts

```
['build a FocalLoss nn.Module that computes focal loss with configurable gamma and num_classes parameters', 'create a FastRCNNFocalLoss instance to compute classification and box regression losses for ROI proposals', 'review the FastRCNNFocaltLossOutputLayers class that extends FastRCNNOutputLayers with focal loss support', 'test the FocalLoss forward method by passing input logits and target class labels', 'refactor the FastRCNNFocalLoss losses method to customize classification and box regression loss computation', 'build a StandardROIHeadsPseudoLab ROI head for pseudo labeling in Detectron2 object detection models', 'initialize a box head with CrossEntropy or FocalLoss predictor using _init_box_head class method', 'run the forward pass of StandardROIHeadsPseudoLab with training loss computation and proposal sampling', 'run the forward pass of StandardROIHeadsPseudoLab for inference to get predicted instances and predictions', 'label and sample proposals by matching against ground truth boxes using pairwise IoU and proposal matcher']
```

Usage

```
{'build_roi_heads_pseudo_lab': 'build a StandardROIHeadsPseudoLab ROI head for pseudo labeling in Detectron2 object detection models', 'init_box_head_with_loss': 'initialize a box head with CrossEntropy or FocalLoss predictor using _init_box_head class method', 'forward_roi_heads_training': 'run the forward pass of StandardROIHeadsPseudoLab with training loss computation and proposal sampling', 'forward_roi_heads_inference': 'run the forward pass of StandardROIHeadsPseudoLab for inference to get predicted instances and predictions', 'label_and_sample_proposals': 'label and sample proposals by matching against ground truth boxes using pairwise IoU and proposal matcher'}
```

