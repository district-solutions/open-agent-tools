# Agent Python Tools

- repo: facebookresearch/cutler
- repo_uri: https://github.com/facebookresearch/cutler

## File: facebookresearch_cutler/videocutler/mask2former/modeling/meta_arch/mask_former_head.py

Prompts

```
['build a MaskFormerHead instance with pixel decoder and transformer predictor for semantic segmentation', 'create a MaskFormerHead from a detectron2 config object and input feature shape dictionary', 'run the MaskFormerHead forward pass on image features to get mask predictions', 'review the MaskFormerHead layers method that routes features through the pixel decoder and transformer predictor', 'refactor the MaskFormerHead _load_from_state_dict method to handle weight format version migration', 'build a PerPixelBaselineHead for semantic segmentation using a pixel decoder and 1x1 conv predictor', 'build a PerPixelBaselinePlusHead with a transformer predictor and optional deep supervision for semantic segmentation', 'run the forward pass of PerPixelBaselineHead to get segmentation logits or training losses', 'run the forward pass of PerPixelBaselinePlusHead with deep supervision to compute auxiliary losses', 'compute cross-entropy semantic segmentation losses with interpolated predictions and configurable ignore value']
```

Usage

```
{'build_maskformer_head': 'build a MaskFormerHead instance with pixel decoder and transformer predictor for semantic segmentation', 'create_maskformer_head_from_config': 'create a MaskFormerHead from a detectron2 config object and input feature shape dictionary', 'run_maskformer_forward': 'run the MaskFormerHead forward pass on image features to get mask predictions', 'review_maskformer_head_layers': 'review the MaskFormerHead layers method that routes features through the pixel decoder and transformer predictor', 'refactor_maskformer_head_state_dict': 'refactor the MaskFormerHead _load_from_state_dict method to handle weight format version migration'}
```

## File: facebookresearch_cutler/videocutler/mask2former/modeling/meta_arch/per_pixel_baseline.py

Prompts

```
['build a MaskFormerHead instance with pixel decoder and transformer predictor for semantic segmentation', 'create a MaskFormerHead from a detectron2 config object and input feature shape dictionary', 'run the MaskFormerHead forward pass on image features to get mask predictions', 'review the MaskFormerHead layers method that routes features through the pixel decoder and transformer predictor', 'refactor the MaskFormerHead _load_from_state_dict method to handle weight format version migration', 'build a PerPixelBaselineHead for semantic segmentation using a pixel decoder and 1x1 conv predictor', 'build a PerPixelBaselinePlusHead with a transformer predictor and optional deep supervision for semantic segmentation', 'run the forward pass of PerPixelBaselineHead to get segmentation logits or training losses', 'run the forward pass of PerPixelBaselinePlusHead with deep supervision to compute auxiliary losses', 'compute cross-entropy semantic segmentation losses with interpolated predictions and configurable ignore value']
```

Usage

```
{'build_per_pixel_baseline_head': 'build a PerPixelBaselineHead for semantic segmentation using a pixel decoder and 1x1 conv predictor', 'build_per_pixel_baseline_plus_head': 'build a PerPixelBaselinePlusHead with a transformer predictor and optional deep supervision for semantic segmentation', 'run_forward_baseline_head': 'run the forward pass of PerPixelBaselineHead to get segmentation logits or training losses', 'run_forward_baseline_plus_head': 'run the forward pass of PerPixelBaselinePlusHead with deep supervision to compute auxiliary losses', 'compute_semantic_segmentation_losses': 'compute cross-entropy semantic segmentation losses with interpolated predictions and configurable ignore value'}
```

