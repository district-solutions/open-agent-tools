# Agent Python Tools

- repo: facebookresearch/mask2former
- repo_uri: https://github.com/facebookresearch/mask2former

## File: facebookresearch_mask2former/mask2former/config.py

Prompts

```
['add Mask2Former config options to a Detectron2 CfgNode for semantic segmentation model setup', 'review the add_maskformer2_config function to understand all Mask2Former config defaults it registers', 'summarize the add_maskformer2_config function and list all config keys it sets on the CfgNode', 'refactor add_maskformer2_config to add new transformer decoder or loss weight config options', 'test that add_maskformer2_config correctly registers all expected Mask2Former config fields on a CfgNode', 'build a MaskFormer model from a detectron2 config with backbone, head, and HungarianMatcher criterion', 'run the MaskFormer forward pass on batched inputs to compute segmentation losses or predictions', 'review the MaskFormer panoptic_inference method that merges stuff regions and assigns segment IDs', 'test the MaskFormer instance_inference method that returns top-k predicted instances with scores and masks', 'summarize the MaskFormer semantic_inference method that computes per-pixel class logits via einsum']
```

Usage

```
{'add_maskformer2_config': 'add Mask2Former config options to a Detectron2 CfgNode for semantic segmentation model setup', 'review_add_maskformer2_config': 'review the add_maskformer2_config function to understand all Mask2Former config defaults it registers', 'summarize_add_maskformer2_config': 'summarize the add_maskformer2_config function and list all config keys it sets on the CfgNode', 'refactor_add_maskformer2_config': 'refactor add_maskformer2_config to add new transformer decoder or loss weight config options', 'test_add_maskformer2_config': 'test that add_maskformer2_config correctly registers all expected Mask2Former config fields on a CfgNode'}
```

## File: facebookresearch_mask2former/mask2former/maskformer_model.py

Prompts

```
['add Mask2Former config options to a Detectron2 CfgNode for semantic segmentation model setup', 'review the add_maskformer2_config function to understand all Mask2Former config defaults it registers', 'summarize the add_maskformer2_config function and list all config keys it sets on the CfgNode', 'refactor add_maskformer2_config to add new transformer decoder or loss weight config options', 'test that add_maskformer2_config correctly registers all expected Mask2Former config fields on a CfgNode', 'build a MaskFormer model from a detectron2 config with backbone, head, and HungarianMatcher criterion', 'run the MaskFormer forward pass on batched inputs to compute segmentation losses or predictions', 'review the MaskFormer panoptic_inference method that merges stuff regions and assigns segment IDs', 'test the MaskFormer instance_inference method that returns top-k predicted instances with scores and masks', 'summarize the MaskFormer semantic_inference method that computes per-pixel class logits via einsum']
```

Usage

```
{'build_MaskFormer_from_config': 'build a MaskFormer model from a detectron2 config with backbone, head, and HungarianMatcher criterion', 'run_MaskFormer_forward': 'run the MaskFormer forward pass on batched inputs to compute segmentation losses or predictions', 'review_MaskFormer_panoptic_inference': 'review the MaskFormer panoptic_inference method that merges stuff regions and assigns segment IDs', 'test_MaskFormer_instance_inference': 'test the MaskFormer instance_inference method that returns top-k predicted instances with scores and masks', 'summarize_MaskFormer_semantic_inference': 'summarize the MaskFormer semantic_inference method that computes per-pixel class logits via einsum'}
```

