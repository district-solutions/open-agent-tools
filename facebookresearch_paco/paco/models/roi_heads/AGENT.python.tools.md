# Agent Python Tools

- repo: facebookresearch/paco
- repo_uri: https://github.com/facebookresearch/paco

## File: facebookresearch_paco/paco/models/roi_heads/attribute_head.py

Prompts

```
['run attribute inference to compute softmax probabilities and attach them to predicted instances', 'compute the cross-entropy attribute prediction loss per attribute type for training', 'create an AttributeOutputLayers module with one linear layer per attribute type for prediction', 'forward feature tensors through attribute output layers to get predictions or training loss', 'review the attribute_head module for attribute inference, loss computation, and output layer design', 'build a PACOCascadeROIHeads model with multiple cascade stages for object detection using detectron2 config', 'review the PACOCascadeROIHeads forward method that handles training and inference with cascade box head stages', 'refactor the PACOCascadeROIHeads _init_box_head class method to customize cascade stage IoU thresholds and bbox regression weights', 'test the _ScaleGradient autograd function that scales gradients by a factor during backpropagation for cascade head training', 'summarize the PACOCascadeROIHeads _match_and_label_boxes method that matches proposals with ground truth using pairwise IoU', 'build a PACOROIHeads instance with attribute prediction support using detectron2 config', 'create a filter to select proposals with at least one non-ignored attribute label', 'review the PACOROIHeads forward method that adds attribute head calls to ROI training', 'refactor the PACOROIHeads _forward_attributes method to pool and predict attributes from features', 'summarize the PACOROIHeads _init_attribute_head classmethod that builds the attribute pooler, head, and predictor']
```

Usage

```
{'run_attribute_inference': 'run attribute inference to compute softmax probabilities and attach them to predicted instances', 'compute_attribute_loss': 'compute the cross-entropy attribute prediction loss per attribute type for training', 'create_attribute_output_layers': 'create an AttributeOutputLayers module with one linear layer per attribute type for prediction', 'forward_attribute_head': 'forward feature tensors through attribute output layers to get predictions or training loss', 'review_attribute_head': 'review the attribute_head module for attribute inference, loss computation, and output layer design'}
```

## File: facebookresearch_paco/paco/models/roi_heads/cascade_rcnn.py

Prompts

```
['run attribute inference to compute softmax probabilities and attach them to predicted instances', 'compute the cross-entropy attribute prediction loss per attribute type for training', 'create an AttributeOutputLayers module with one linear layer per attribute type for prediction', 'forward feature tensors through attribute output layers to get predictions or training loss', 'review the attribute_head module for attribute inference, loss computation, and output layer design', 'build a PACOCascadeROIHeads model with multiple cascade stages for object detection using detectron2 config', 'review the PACOCascadeROIHeads forward method that handles training and inference with cascade box head stages', 'refactor the PACOCascadeROIHeads _init_box_head class method to customize cascade stage IoU thresholds and bbox regression weights', 'test the _ScaleGradient autograd function that scales gradients by a factor during backpropagation for cascade head training', 'summarize the PACOCascadeROIHeads _match_and_label_boxes method that matches proposals with ground truth using pairwise IoU', 'build a PACOROIHeads instance with attribute prediction support using detectron2 config', 'create a filter to select proposals with at least one non-ignored attribute label', 'review the PACOROIHeads forward method that adds attribute head calls to ROI training', 'refactor the PACOROIHeads _forward_attributes method to pool and predict attributes from features', 'summarize the PACOROIHeads _init_attribute_head classmethod that builds the attribute pooler, head, and predictor']
```

Usage

```
{'build_PACOCascadeROIHeads': 'build a PACOCascadeROIHeads model with multiple cascade stages for object detection using detectron2 config', 'review_PACOCascadeROIHeads_forward': 'review the PACOCascadeROIHeads forward method that handles training and inference with cascade box head stages', 'refactor_PACOCascadeROIHeads_init_box_head': 'refactor the PACOCascadeROIHeads _init_box_head class method to customize cascade stage IoU thresholds and bbox regression weights', 'test_ScaleGradient': 'test the _ScaleGradient autograd function that scales gradients by a factor during backpropagation for cascade head training', 'summarize_PACOCascadeROIHeads_match_and_label': 'summarize the PACOCascadeROIHeads _match_and_label_boxes method that matches proposals with ground truth using pairwise IoU'}
```

## File: facebookresearch_paco/paco/models/roi_heads/roi_heads.py

Prompts

```
['run attribute inference to compute softmax probabilities and attach them to predicted instances', 'compute the cross-entropy attribute prediction loss per attribute type for training', 'create an AttributeOutputLayers module with one linear layer per attribute type for prediction', 'forward feature tensors through attribute output layers to get predictions or training loss', 'review the attribute_head module for attribute inference, loss computation, and output layer design', 'build a PACOCascadeROIHeads model with multiple cascade stages for object detection using detectron2 config', 'review the PACOCascadeROIHeads forward method that handles training and inference with cascade box head stages', 'refactor the PACOCascadeROIHeads _init_box_head class method to customize cascade stage IoU thresholds and bbox regression weights', 'test the _ScaleGradient autograd function that scales gradients by a factor during backpropagation for cascade head training', 'summarize the PACOCascadeROIHeads _match_and_label_boxes method that matches proposals with ground truth using pairwise IoU', 'build a PACOROIHeads instance with attribute prediction support using detectron2 config', 'create a filter to select proposals with at least one non-ignored attribute label', 'review the PACOROIHeads forward method that adds attribute head calls to ROI training', 'refactor the PACOROIHeads _forward_attributes method to pool and predict attributes from features', 'summarize the PACOROIHeads _init_attribute_head classmethod that builds the attribute pooler, head, and predictor']
```

Usage

```
{'build_PACOROIHeads': 'build a PACOROIHeads instance with attribute prediction support using detectron2 config', 'create_select_proposals_with_attributes': 'create a filter to select proposals with at least one non-ignored attribute label', 'review_PACOROIHeads_forward': 'review the PACOROIHeads forward method that adds attribute head calls to ROI training', 'refactor_PACOROIHeads_forward_attributes': 'refactor the PACOROIHeads _forward_attributes method to pool and predict attributes from features', 'summarize_PACOROIHeads_init_attribute_head': 'summarize the PACOROIHeads _init_attribute_head classmethod that builds the attribute pooler, head, and predictor'}
```

