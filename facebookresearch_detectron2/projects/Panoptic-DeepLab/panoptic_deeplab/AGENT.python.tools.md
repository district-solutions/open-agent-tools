# Agent Python Tools

- repo: facebookresearch/detectron2
- repo_uri: https://github.com/facebookresearch/detectron2.git

## File: facebookresearch_detectron2/projects/Panoptic-DeepLab/panoptic_deeplab/config.py

Prompts

```
['add Panoptic-DeepLab configuration options to a Detectron2 CfgNode for model training', 'configure the instance embedding head with ASPP channels, dilations, and loss weights', 'set the semantic segmentation head channels and loss top-k parameters', 'configure Panoptic-DeepLab post-processing settings like center threshold and NMS kernel size', 'set the solver optimizer to ADAM and configure input target generation parameters', 'create a PanopticDeeplabDatasetMapper instance with augmentations, image format, and a panoptic target generator callable', 'build a PanopticDeeplabDatasetMapper from a Detectron2 config object with resize, crop, and flip augmentations', 'run the dataset mapper on a dataset dict to load images, apply augmentations, and generate training targets', 'review the augmentation pipeline including ResizeShortestEdge, RandomCrop, and RandomFlip transforms applied to images and labels', 'summarize how panoptic segmentation targets are generated from RGB-encoded labels using rgb2id and the target generator', 'build a PanopticDeepLab model from a detectron2 config for panoptic segmentation inference', 'run the PanopticDeepLab forward pass on batched image inputs to get panoptic segmentation results', 'build a PanopticDeepLabSemSegHead with configurable loss type and depthwise separable conv options', 'build an instance embedding branch using build_ins_embed_branch from the INS_EMBED_BRANCHES_REGISTRY', 'review the PanopticDeepLabInsEmbedHead center and offset prediction layers and loss computation', 'find instance center points from a center heatmap using thresholding and NMS', 'assign each pixel an instance id by computing nearest center point distance', 'compute class agnostic instance segmentation from semantic labels, center heatmap, and offsets', 'merge semantic segmentation labels with instance segmentation to produce panoptic segmentation', 'run full panoptic segmentation post-processing from semantic labels, center heatmap, and offsets']
```

Usage

```
{'add_panoptic_deeplab_config': 'add Panoptic-DeepLab configuration options to a Detectron2 CfgNode for model training', 'configure_ins_embed_head': 'configure the instance embedding head with ASPP channels, dilations, and loss weights', 'set_semantic_seg_head': 'set the semantic segmentation head channels and loss top-k parameters', 'configure_post_processing': 'configure Panoptic-DeepLab post-processing settings like center threshold and NMS kernel size', 'set_optimizer_and_input': 'set the solver optimizer to ADAM and configure input target generation parameters'}
```

## File: facebookresearch_detectron2/projects/Panoptic-DeepLab/panoptic_deeplab/dataset_mapper.py

Prompts

```
['add Panoptic-DeepLab configuration options to a Detectron2 CfgNode for model training', 'configure the instance embedding head with ASPP channels, dilations, and loss weights', 'set the semantic segmentation head channels and loss top-k parameters', 'configure Panoptic-DeepLab post-processing settings like center threshold and NMS kernel size', 'set the solver optimizer to ADAM and configure input target generation parameters', 'create a PanopticDeeplabDatasetMapper instance with augmentations, image format, and a panoptic target generator callable', 'build a PanopticDeeplabDatasetMapper from a Detectron2 config object with resize, crop, and flip augmentations', 'run the dataset mapper on a dataset dict to load images, apply augmentations, and generate training targets', 'review the augmentation pipeline including ResizeShortestEdge, RandomCrop, and RandomFlip transforms applied to images and labels', 'summarize how panoptic segmentation targets are generated from RGB-encoded labels using rgb2id and the target generator', 'build a PanopticDeepLab model from a detectron2 config for panoptic segmentation inference', 'run the PanopticDeepLab forward pass on batched image inputs to get panoptic segmentation results', 'build a PanopticDeepLabSemSegHead with configurable loss type and depthwise separable conv options', 'build an instance embedding branch using build_ins_embed_branch from the INS_EMBED_BRANCHES_REGISTRY', 'review the PanopticDeepLabInsEmbedHead center and offset prediction layers and loss computation', 'find instance center points from a center heatmap using thresholding and NMS', 'assign each pixel an instance id by computing nearest center point distance', 'compute class agnostic instance segmentation from semantic labels, center heatmap, and offsets', 'merge semantic segmentation labels with instance segmentation to produce panoptic segmentation', 'run full panoptic segmentation post-processing from semantic labels, center heatmap, and offsets']
```

Usage

```
{'create_PanopticDeeplabDatasetMapper': 'create a PanopticDeeplabDatasetMapper instance with augmentations, image format, and a panoptic target generator callable', 'build_from_config': 'build a PanopticDeeplabDatasetMapper from a Detectron2 config object with resize, crop, and flip augmentations', 'run_dataset_mapper_call': 'run the dataset mapper on a dataset dict to load images, apply augmentations, and generate training targets', 'review_augmentation_pipeline': 'review the augmentation pipeline including ResizeShortestEdge, RandomCrop, and RandomFlip transforms applied to images and labels', 'summarize_target_generation': 'summarize how panoptic segmentation targets are generated from RGB-encoded labels using rgb2id and the target generator'}
```

## File: facebookresearch_detectron2/projects/Panoptic-DeepLab/panoptic_deeplab/panoptic_seg.py

Prompts

```
['add Panoptic-DeepLab configuration options to a Detectron2 CfgNode for model training', 'configure the instance embedding head with ASPP channels, dilations, and loss weights', 'set the semantic segmentation head channels and loss top-k parameters', 'configure Panoptic-DeepLab post-processing settings like center threshold and NMS kernel size', 'set the solver optimizer to ADAM and configure input target generation parameters', 'create a PanopticDeeplabDatasetMapper instance with augmentations, image format, and a panoptic target generator callable', 'build a PanopticDeeplabDatasetMapper from a Detectron2 config object with resize, crop, and flip augmentations', 'run the dataset mapper on a dataset dict to load images, apply augmentations, and generate training targets', 'review the augmentation pipeline including ResizeShortestEdge, RandomCrop, and RandomFlip transforms applied to images and labels', 'summarize how panoptic segmentation targets are generated from RGB-encoded labels using rgb2id and the target generator', 'build a PanopticDeepLab model from a detectron2 config for panoptic segmentation inference', 'run the PanopticDeepLab forward pass on batched image inputs to get panoptic segmentation results', 'build a PanopticDeepLabSemSegHead with configurable loss type and depthwise separable conv options', 'build an instance embedding branch using build_ins_embed_branch from the INS_EMBED_BRANCHES_REGISTRY', 'review the PanopticDeepLabInsEmbedHead center and offset prediction layers and loss computation', 'find instance center points from a center heatmap using thresholding and NMS', 'assign each pixel an instance id by computing nearest center point distance', 'compute class agnostic instance segmentation from semantic labels, center heatmap, and offsets', 'merge semantic segmentation labels with instance segmentation to produce panoptic segmentation', 'run full panoptic segmentation post-processing from semantic labels, center heatmap, and offsets']
```

Usage

```
{'build_panoptic_deeplab_model': 'build a PanopticDeepLab model from a detectron2 config for panoptic segmentation inference', 'run_panoptic_deeplab_forward': 'run the PanopticDeepLab forward pass on batched image inputs to get panoptic segmentation results', 'build_sem_seg_head': 'build a PanopticDeepLabSemSegHead with configurable loss type and depthwise separable conv options', 'build_ins_embed_branch': 'build an instance embedding branch using build_ins_embed_branch from the INS_EMBED_BRANCHES_REGISTRY', 'review_ins_embed_head': 'review the PanopticDeepLabInsEmbedHead center and offset prediction layers and loss computation'}
```

## File: facebookresearch_detectron2/projects/Panoptic-DeepLab/panoptic_deeplab/post_processing.py

Prompts

```
['add Panoptic-DeepLab configuration options to a Detectron2 CfgNode for model training', 'configure the instance embedding head with ASPP channels, dilations, and loss weights', 'set the semantic segmentation head channels and loss top-k parameters', 'configure Panoptic-DeepLab post-processing settings like center threshold and NMS kernel size', 'set the solver optimizer to ADAM and configure input target generation parameters', 'create a PanopticDeeplabDatasetMapper instance with augmentations, image format, and a panoptic target generator callable', 'build a PanopticDeeplabDatasetMapper from a Detectron2 config object with resize, crop, and flip augmentations', 'run the dataset mapper on a dataset dict to load images, apply augmentations, and generate training targets', 'review the augmentation pipeline including ResizeShortestEdge, RandomCrop, and RandomFlip transforms applied to images and labels', 'summarize how panoptic segmentation targets are generated from RGB-encoded labels using rgb2id and the target generator', 'build a PanopticDeepLab model from a detectron2 config for panoptic segmentation inference', 'run the PanopticDeepLab forward pass on batched image inputs to get panoptic segmentation results', 'build a PanopticDeepLabSemSegHead with configurable loss type and depthwise separable conv options', 'build an instance embedding branch using build_ins_embed_branch from the INS_EMBED_BRANCHES_REGISTRY', 'review the PanopticDeepLabInsEmbedHead center and offset prediction layers and loss computation', 'find instance center points from a center heatmap using thresholding and NMS', 'assign each pixel an instance id by computing nearest center point distance', 'compute class agnostic instance segmentation from semantic labels, center heatmap, and offsets', 'merge semantic segmentation labels with instance segmentation to produce panoptic segmentation', 'run full panoptic segmentation post-processing from semantic labels, center heatmap, and offsets']
```

Usage

```
{'find_instance_center': 'find instance center points from a center heatmap using thresholding and NMS', 'group_pixels': 'assign each pixel an instance id by computing nearest center point distance', 'get_instance_segmentation': 'compute class agnostic instance segmentation from semantic labels, center heatmap, and offsets', 'merge_semantic_and_instance': 'merge semantic segmentation labels with instance segmentation to produce panoptic segmentation', 'get_panoptic_segmentation': 'run full panoptic segmentation post-processing from semantic labels, center heatmap, and offsets'}
```

