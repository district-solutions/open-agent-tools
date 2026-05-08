# Agent Python Tools

- repo: facebookresearch/mask2former
- repo_uri: https://github.com/facebookresearch/mask2former

## File: facebookresearch_mask2former/mask2former/modeling/meta_arch/mask_former_head.py

Prompts

```
['build a MaskFormerHead instance with pixel decoder and transformer predictor for semantic segmentation', 'create a MaskFormerHead from a detectron2 config object and input feature shape dictionary', 'run the MaskFormerHead forward pass on image features to get mask predictions', 'review the MaskFormerHead layers method to understand feature routing and predictor dispatch logic', 'refactor the MaskFormerHead state dict loading to handle weight format version migration', 'build a PerPixelBaselineHead for semantic segmentation using a pixel decoder and 1x1 conv predictor', 'build a PerPixelBaselinePlusHead with a transformer predictor and optional deep supervision for semantic segmentation', 'review the PerPixelBaselineHead forward method that returns logits during inference and losses during training', 'review the PerPixelBaselinePlusHead forward method with deep supervision that computes auxiliary losses per transformer layer', 'review the losses method that computes cross-entropy loss with bilinear interpolation and configurable ignore value']
```

Usage

```
{'build_maskformer_head': 'build a MaskFormerHead instance with pixel decoder and transformer predictor for semantic segmentation', 'create_maskformer_head_from_config': 'create a MaskFormerHead from a detectron2 config object and input feature shape dictionary', 'run_maskformer_forward': 'run the MaskFormerHead forward pass on image features to get mask predictions', 'review_maskformer_layers': 'review the MaskFormerHead layers method to understand feature routing and predictor dispatch logic', 'refactor_maskformer_state_dict': 'refactor the MaskFormerHead state dict loading to handle weight format version migration'}
```

## File: facebookresearch_mask2former/mask2former/modeling/meta_arch/per_pixel_baseline.py

Prompts

```
['build a MaskFormerHead instance with pixel decoder and transformer predictor for semantic segmentation', 'create a MaskFormerHead from a detectron2 config object and input feature shape dictionary', 'run the MaskFormerHead forward pass on image features to get mask predictions', 'review the MaskFormerHead layers method to understand feature routing and predictor dispatch logic', 'refactor the MaskFormerHead state dict loading to handle weight format version migration', 'build a PerPixelBaselineHead for semantic segmentation using a pixel decoder and 1x1 conv predictor', 'build a PerPixelBaselinePlusHead with a transformer predictor and optional deep supervision for semantic segmentation', 'review the PerPixelBaselineHead forward method that returns logits during inference and losses during training', 'review the PerPixelBaselinePlusHead forward method with deep supervision that computes auxiliary losses per transformer layer', 'review the losses method that computes cross-entropy loss with bilinear interpolation and configurable ignore value']
```

Usage

```
{'build_per_pixel_baseline_head': 'build a PerPixelBaselineHead for semantic segmentation using a pixel decoder and 1x1 conv predictor', 'build_per_pixel_baseline_plus_head': 'build a PerPixelBaselinePlusHead with a transformer predictor and optional deep supervision for semantic segmentation', 'review_forward_per_pixel_baseline': 'review the PerPixelBaselineHead forward method that returns logits during inference and losses during training', 'review_forward_per_pixel_baseline_plus': 'review the PerPixelBaselinePlusHead forward method with deep supervision that computes auxiliary losses per transformer layer', 'review_losses_method': 'review the losses method that computes cross-entropy loss with bilinear interpolation and configurable ignore value'}
```

