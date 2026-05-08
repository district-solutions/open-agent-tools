# Agent Python Tools

- repo: facebookresearch/ov-seg
- repo_uri: https://github.com/facebookresearch/ov-seg

## File: facebookresearch_ov-seg/open_vocab_seg/config.py

Prompts

```
['add open vocabulary segmentation config to a detectron2 CfgNode by calling add_ovseg_config', 'add mask former default config including transformer, loss, and swin backbone settings to a cfg node', 'add custom config for CLIP adapter, embedding head, sliding window, and wandb to a cfg node', 'configure the mask former transformer heads, layers, dropout, and hidden dim via add_mask_former_default_config', 'configure the CLIP adapter model name, prompt templates, mask settings, and ensemble weight via add_our_config', 'build a MaskFormer model instance from a detectron2 config object using the from_config class method', 'run the MaskFormer forward pass on batched image inputs to get semantic or panoptic segmentation results', 'review the MaskFormer semantic_inference method that combines mask classification logits with predicted masks via einsum', 'refactor the MaskFormer prepare_targets method that pads ground truth masks to match image tensor dimensions', 'test the MaskFormer SetCriterion loss computation with HungarianMatcher bipartite matching for labels and masks', 'build a zero-shot semantic segmentation model using OVSeg with a CLIP adapter and detectron2 backbone', 'run semantic segmentation inference on images using the OVSeg forward method with batched inputs', 'build a demo zero-shot segmentation model using OVSegDEMO with custom class names for inference', 'review the OVSeg semantic_inference method that combines mask classification with CLIP ensemble predictions', 'refactor the OVSeg clip ensemble logic to adjust the ensemble weight between mask former and CLIP predictions']
```

Usage

```
{'add_ovseg_config': 'add open vocabulary segmentation config to a detectron2 CfgNode by calling add_ovseg_config', 'add_mask_former_default_config': 'add mask former default config including transformer, loss, and swin backbone settings to a cfg node', 'add_our_config': 'add custom config for CLIP adapter, embedding head, sliding window, and wandb to a cfg node', 'configure_mask_former_transformer': 'configure the mask former transformer heads, layers, dropout, and hidden dim via add_mask_former_default_config', 'configure_clip_adapter': 'configure the CLIP adapter model name, prompt templates, mask settings, and ensemble weight via add_our_config'}
```

## File: facebookresearch_ov-seg/open_vocab_seg/mask_former_model.py

Prompts

```
['add open vocabulary segmentation config to a detectron2 CfgNode by calling add_ovseg_config', 'add mask former default config including transformer, loss, and swin backbone settings to a cfg node', 'add custom config for CLIP adapter, embedding head, sliding window, and wandb to a cfg node', 'configure the mask former transformer heads, layers, dropout, and hidden dim via add_mask_former_default_config', 'configure the CLIP adapter model name, prompt templates, mask settings, and ensemble weight via add_our_config', 'build a MaskFormer model instance from a detectron2 config object using the from_config class method', 'run the MaskFormer forward pass on batched image inputs to get semantic or panoptic segmentation results', 'review the MaskFormer semantic_inference method that combines mask classification logits with predicted masks via einsum', 'refactor the MaskFormer prepare_targets method that pads ground truth masks to match image tensor dimensions', 'test the MaskFormer SetCriterion loss computation with HungarianMatcher bipartite matching for labels and masks', 'build a zero-shot semantic segmentation model using OVSeg with a CLIP adapter and detectron2 backbone', 'run semantic segmentation inference on images using the OVSeg forward method with batched inputs', 'build a demo zero-shot segmentation model using OVSegDEMO with custom class names for inference', 'review the OVSeg semantic_inference method that combines mask classification with CLIP ensemble predictions', 'refactor the OVSeg clip ensemble logic to adjust the ensemble weight between mask former and CLIP predictions']
```

Usage

```
{'build_MaskFormer_from_config': 'build a MaskFormer model instance from a detectron2 config object using the from_config class method', 'run_MaskFormer_forward': 'run the MaskFormer forward pass on batched image inputs to get semantic or panoptic segmentation results', 'review_MaskFormer_semantic_inference': 'review the MaskFormer semantic_inference method that combines mask classification logits with predicted masks via einsum', 'refactor_MaskFormer_prepare_targets': 'refactor the MaskFormer prepare_targets method that pads ground truth masks to match image tensor dimensions', 'test_MaskFormer_criterion': 'test the MaskFormer SetCriterion loss computation with HungarianMatcher bipartite matching for labels and masks'}
```

## File: facebookresearch_ov-seg/open_vocab_seg/ovseg_model.py

Prompts

```
['add open vocabulary segmentation config to a detectron2 CfgNode by calling add_ovseg_config', 'add mask former default config including transformer, loss, and swin backbone settings to a cfg node', 'add custom config for CLIP adapter, embedding head, sliding window, and wandb to a cfg node', 'configure the mask former transformer heads, layers, dropout, and hidden dim via add_mask_former_default_config', 'configure the CLIP adapter model name, prompt templates, mask settings, and ensemble weight via add_our_config', 'build a MaskFormer model instance from a detectron2 config object using the from_config class method', 'run the MaskFormer forward pass on batched image inputs to get semantic or panoptic segmentation results', 'review the MaskFormer semantic_inference method that combines mask classification logits with predicted masks via einsum', 'refactor the MaskFormer prepare_targets method that pads ground truth masks to match image tensor dimensions', 'test the MaskFormer SetCriterion loss computation with HungarianMatcher bipartite matching for labels and masks', 'build a zero-shot semantic segmentation model using OVSeg with a CLIP adapter and detectron2 backbone', 'run semantic segmentation inference on images using the OVSeg forward method with batched inputs', 'build a demo zero-shot segmentation model using OVSegDEMO with custom class names for inference', 'review the OVSeg semantic_inference method that combines mask classification with CLIP ensemble predictions', 'refactor the OVSeg clip ensemble logic to adjust the ensemble weight between mask former and CLIP predictions']
```

Usage

```
{'build_ovseg_model': 'build a zero-shot semantic segmentation model using OVSeg with a CLIP adapter and detectron2 backbone', 'run_ovseg_inference': 'run semantic segmentation inference on images using the OVSeg forward method with batched inputs', 'build_ovsegdemo_model': 'build a demo zero-shot segmentation model using OVSegDEMO with custom class names for inference', 'review_ovseg_semantic_inference': 'review the OVSeg semantic_inference method that combines mask classification with CLIP ensemble predictions', 'refactor_ovseg_clip_ensemble': 'refactor the OVSeg clip ensemble logic to adjust the ensemble weight between mask former and CLIP predictions'}
```

