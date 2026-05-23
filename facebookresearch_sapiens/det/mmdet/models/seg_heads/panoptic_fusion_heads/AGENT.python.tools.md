# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/det/mmdet/models/seg_heads/panoptic_fusion_heads/base_panoptic_fusion_head.py

Prompts

```
['build a panoptic fusion head with 80 thing classes and 53 stuff classes', 'create a panoptic fusion head with a custom panoptic loss function config', 'test the with_loss property to check if the panoptic head contains a loss function', 'review the abstract loss method that subclasses must implement for panoptic segmentation', 'review the abstract predict method that subclasses must implement for panoptic prediction', 'build a HeuristicFusionHead instance with 80 thing classes and 53 stuff classes for panoptic segmentation', 'create an id map by laying instance masks with a configurable overlap threshold', 'test the _predict_single method to fuse instance masks with semantic segmentation predictions', 'review the predict method that fuses instance and semantic segmentation results for a batch of images', 'summarize the loss method which returns an empty dict since HeuristicFusionHead has no training loss', 'postprocess mask classification and mask prediction tensors into panoptic segmentation PixelData results', 'postprocess mask classification and mask prediction tensors into instance segmentation InstanceData with scores and bboxes', 'predict panoptic and instance segmentation results from batched mask classification and mask prediction logits', 'review the MaskFormerFusionHead class and its panoptic segmentation postprocessing logic for things and stuff classes', 'refactor the panoptic_postprocess method to support configurable object mask threshold and IoU filtering']
```

Usage

```
{'build_BasePanopticFusionHead': 'build a panoptic fusion head with 80 thing classes and 53 stuff classes', 'create_BasePanopticFusionHead_with_loss': 'create a panoptic fusion head with a custom panoptic loss function config', 'test_BasePanopticFusionHead_with_loss': 'test the with_loss property to check if the panoptic head contains a loss function', 'review_BasePanopticFusionHead_loss': 'review the abstract loss method that subclasses must implement for panoptic segmentation', 'review_BasePanopticFusionHead_predict': 'review the abstract predict method that subclasses must implement for panoptic prediction'}
```

## File: facebookresearch_sapiens/det/mmdet/models/seg_heads/panoptic_fusion_heads/heuristic_fusion_head.py

Prompts

```
['build a panoptic fusion head with 80 thing classes and 53 stuff classes', 'create a panoptic fusion head with a custom panoptic loss function config', 'test the with_loss property to check if the panoptic head contains a loss function', 'review the abstract loss method that subclasses must implement for panoptic segmentation', 'review the abstract predict method that subclasses must implement for panoptic prediction', 'build a HeuristicFusionHead instance with 80 thing classes and 53 stuff classes for panoptic segmentation', 'create an id map by laying instance masks with a configurable overlap threshold', 'test the _predict_single method to fuse instance masks with semantic segmentation predictions', 'review the predict method that fuses instance and semantic segmentation results for a batch of images', 'summarize the loss method which returns an empty dict since HeuristicFusionHead has no training loss', 'postprocess mask classification and mask prediction tensors into panoptic segmentation PixelData results', 'postprocess mask classification and mask prediction tensors into instance segmentation InstanceData with scores and bboxes', 'predict panoptic and instance segmentation results from batched mask classification and mask prediction logits', 'review the MaskFormerFusionHead class and its panoptic segmentation postprocessing logic for things and stuff classes', 'refactor the panoptic_postprocess method to support configurable object mask threshold and IoU filtering']
```

Usage

```
{'build_heuristic_fusion_head': 'build a HeuristicFusionHead instance with 80 thing classes and 53 stuff classes for panoptic segmentation', 'create_lay_masks': 'create an id map by laying instance masks with a configurable overlap threshold', 'test_predict_single': 'test the _predict_single method to fuse instance masks with semantic segmentation predictions', 'review_predict_batch': 'review the predict method that fuses instance and semantic segmentation results for a batch of images', 'summarize_loss': 'summarize the loss method which returns an empty dict since HeuristicFusionHead has no training loss'}
```

## File: facebookresearch_sapiens/det/mmdet/models/seg_heads/panoptic_fusion_heads/maskformer_fusion_head.py

Prompts

```
['build a panoptic fusion head with 80 thing classes and 53 stuff classes', 'create a panoptic fusion head with a custom panoptic loss function config', 'test the with_loss property to check if the panoptic head contains a loss function', 'review the abstract loss method that subclasses must implement for panoptic segmentation', 'review the abstract predict method that subclasses must implement for panoptic prediction', 'build a HeuristicFusionHead instance with 80 thing classes and 53 stuff classes for panoptic segmentation', 'create an id map by laying instance masks with a configurable overlap threshold', 'test the _predict_single method to fuse instance masks with semantic segmentation predictions', 'review the predict method that fuses instance and semantic segmentation results for a batch of images', 'summarize the loss method which returns an empty dict since HeuristicFusionHead has no training loss', 'postprocess mask classification and mask prediction tensors into panoptic segmentation PixelData results', 'postprocess mask classification and mask prediction tensors into instance segmentation InstanceData with scores and bboxes', 'predict panoptic and instance segmentation results from batched mask classification and mask prediction logits', 'review the MaskFormerFusionHead class and its panoptic segmentation postprocessing logic for things and stuff classes', 'refactor the panoptic_postprocess method to support configurable object mask threshold and IoU filtering']
```

Usage

```
{'panoptic_postprocess': 'postprocess mask classification and mask prediction tensors into panoptic segmentation PixelData results', 'instance_postprocess': 'postprocess mask classification and mask prediction tensors into instance segmentation InstanceData with scores and bboxes', 'predict': 'predict panoptic and instance segmentation results from batched mask classification and mask prediction logits', 'review_MaskFormerFusionHead': 'review the MaskFormerFusionHead class and its panoptic segmentation postprocessing logic for things and stuff classes', 'refactor_panoptic_postprocess': 'refactor the panoptic_postprocess method to support configurable object mask threshold and IoU filtering'}
```

