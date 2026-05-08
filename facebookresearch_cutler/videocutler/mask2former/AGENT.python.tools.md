# Agent Python Tools

- repo: facebookresearch/cutler
- repo_uri: https://github.com/facebookresearch/cutler

## File: facebookresearch_cutler/videocutler/mask2former/config.py

Prompts

```
['add Mask2Former config options to a Detectron2 CfgNode for semantic segmentation model training', 'review the add_maskformer2_config function to understand all Mask2Former hyperparameters it registers', 'refactor add_maskformer2_config to add custom loss weight or transformer decoder settings', 'summarize the Mask2Former config options registered by add_maskformer2_config including transformer and backbone defaults', 'test that add_maskformer2_config correctly registers all expected cfg fields on a fresh CfgNode', 'build a MaskFormer model from a detectron2 config with backbone, sem_seg_head, and SetCriterion', 'run the MaskFormer forward pass on batched inputs to get semantic, panoptic, or instance segmentation results', 'test the panoptic_inference method to produce panoptic segmentation maps and segment info from mask predictions', 'review the instance_inference method that returns top-k detected instances with masks, scores, and class labels', 'summarize the semantic_inference method that computes per-pixel class logits using einsum over mask classification and mask predictions']
```

Usage

```
{'add_maskformer2_config': 'add Mask2Former config options to a Detectron2 CfgNode for semantic segmentation model training', 'review_add_maskformer2_config': 'review the add_maskformer2_config function to understand all Mask2Former hyperparameters it registers', 'refactor_add_maskformer2_config': 'refactor add_maskformer2_config to add custom loss weight or transformer decoder settings', 'summarize_add_maskformer2_config': 'summarize the Mask2Former config options registered by add_maskformer2_config including transformer and backbone defaults', 'test_add_maskformer2_config': 'test that add_maskformer2_config correctly registers all expected cfg fields on a fresh CfgNode'}
```

## File: facebookresearch_cutler/videocutler/mask2former/maskformer_model.py

Prompts

```
['add Mask2Former config options to a Detectron2 CfgNode for semantic segmentation model training', 'review the add_maskformer2_config function to understand all Mask2Former hyperparameters it registers', 'refactor add_maskformer2_config to add custom loss weight or transformer decoder settings', 'summarize the Mask2Former config options registered by add_maskformer2_config including transformer and backbone defaults', 'test that add_maskformer2_config correctly registers all expected cfg fields on a fresh CfgNode', 'build a MaskFormer model from a detectron2 config with backbone, sem_seg_head, and SetCriterion', 'run the MaskFormer forward pass on batched inputs to get semantic, panoptic, or instance segmentation results', 'test the panoptic_inference method to produce panoptic segmentation maps and segment info from mask predictions', 'review the instance_inference method that returns top-k detected instances with masks, scores, and class labels', 'summarize the semantic_inference method that computes per-pixel class logits using einsum over mask classification and mask predictions']
```

Usage

```
{'build_maskformer_model': 'build a MaskFormer model from a detectron2 config with backbone, sem_seg_head, and SetCriterion', 'run_maskformer_forward': 'run the MaskFormer forward pass on batched inputs to get semantic, panoptic, or instance segmentation results', 'test_panoptic_inference': 'test the panoptic_inference method to produce panoptic segmentation maps and segment info from mask predictions', 'review_instance_inference': 'review the instance_inference method that returns top-k detected instances with masks, scores, and class labels', 'summarize_semantic_inference': 'summarize the semantic_inference method that computes per-pixel class logits using einsum over mask classification and mask predictions'}
```

