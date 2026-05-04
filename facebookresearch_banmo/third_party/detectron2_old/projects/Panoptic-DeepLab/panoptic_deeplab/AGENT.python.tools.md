# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2_old/projects/Panoptic-DeepLab/panoptic_deeplab/config.py

Prompts

```
['add Panoptic-DeepLab configuration options to a Detectron2 CfgNode for model training and inference', 'review the add_panoptic_deeplab_config function to understand target generation and post-processing parameters', 'summarize the INS_EMBED_HEAD configuration including ASPP channels, dilations, and loss weights', 'summarize the PANOPTIC_DEEPLAB post-processing settings including NMS kernel and center threshold', 'refactor add_panoptic_deeplab_config to customize default optimizer or loss weight values', 'create a PanopticDeeplabDatasetMapper with augmentations, image format, and a panoptic target generator callable', 'build a PanopticDeeplabDatasetMapper from a Detectron2 config with resize, crop, and flip augmentations', 'run the dataset mapper on a dataset dict to load, augment, and generate panoptic training targets', 'review the PanopticDeeplabDatasetMapper augmentations pipeline that applies resize, crop, and flip to images and labels', 'summarize how the dataset mapper generates panoptic training targets using rgb2id and the target generator', 'build a PanopticDeepLab model from a Detectron2 config to perform panoptic segmentation on images', 'run the PanopticDeepLab forward pass on batched inputs to get panoptic and semantic segmentation results', 'build a PanopticDeepLabSemSegHead with configurable loss types including cross entropy and hard pixel mining', 'build an instance embedding branch using build_ins_embed_branch from the INS_EMBED_BRANCHES_REGISTRY', 'review the PanopticDeepLabInsEmbedHead center and offset loss computation methods for instance embedding training', 'find instance center points from a center heatmap using thresholding and non-maximum suppression', 'group image pixels into instance IDs by assigning each pixel to its nearest detected center point', 'get class-agnostic instance segmentation masks from semantic labels, center heatmap, and offset predictions', 'merge semantic segmentation labels with instance segmentation to produce panoptic segmentation output', 'compute panoptic segmentation by combining semantic labels, center heatmap, and offsets into a unified prediction']
```

Usage

```
{'add_panoptic_deeplab_config': 'add Panoptic-DeepLab configuration options to a Detectron2 CfgNode for model training and inference', 'review_add_panoptic_deeplab_config': 'review the add_panoptic_deeplab_config function to understand target generation and post-processing parameters', 'summarize_ins_embed_head_config': 'summarize the INS_EMBED_HEAD configuration including ASPP channels, dilations, and loss weights', 'summarize_panoptic_deeplab_postprocessing': 'summarize the PANOPTIC_DEEPLAB post-processing settings including NMS kernel and center threshold', 'refactor_add_panoptic_deeplab_config': 'refactor add_panoptic_deeplab_config to customize default optimizer or loss weight values'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/projects/Panoptic-DeepLab/panoptic_deeplab/dataset_mapper.py

Prompts

```
['add Panoptic-DeepLab configuration options to a Detectron2 CfgNode for model training and inference', 'review the add_panoptic_deeplab_config function to understand target generation and post-processing parameters', 'summarize the INS_EMBED_HEAD configuration including ASPP channels, dilations, and loss weights', 'summarize the PANOPTIC_DEEPLAB post-processing settings including NMS kernel and center threshold', 'refactor add_panoptic_deeplab_config to customize default optimizer or loss weight values', 'create a PanopticDeeplabDatasetMapper with augmentations, image format, and a panoptic target generator callable', 'build a PanopticDeeplabDatasetMapper from a Detectron2 config with resize, crop, and flip augmentations', 'run the dataset mapper on a dataset dict to load, augment, and generate panoptic training targets', 'review the PanopticDeeplabDatasetMapper augmentations pipeline that applies resize, crop, and flip to images and labels', 'summarize how the dataset mapper generates panoptic training targets using rgb2id and the target generator', 'build a PanopticDeepLab model from a Detectron2 config to perform panoptic segmentation on images', 'run the PanopticDeepLab forward pass on batched inputs to get panoptic and semantic segmentation results', 'build a PanopticDeepLabSemSegHead with configurable loss types including cross entropy and hard pixel mining', 'build an instance embedding branch using build_ins_embed_branch from the INS_EMBED_BRANCHES_REGISTRY', 'review the PanopticDeepLabInsEmbedHead center and offset loss computation methods for instance embedding training', 'find instance center points from a center heatmap using thresholding and non-maximum suppression', 'group image pixels into instance IDs by assigning each pixel to its nearest detected center point', 'get class-agnostic instance segmentation masks from semantic labels, center heatmap, and offset predictions', 'merge semantic segmentation labels with instance segmentation to produce panoptic segmentation output', 'compute panoptic segmentation by combining semantic labels, center heatmap, and offsets into a unified prediction']
```

Usage

```
{'create_PanopticDeeplabDatasetMapper': 'create a PanopticDeeplabDatasetMapper with augmentations, image format, and a panoptic target generator callable', 'build_from_config': 'build a PanopticDeeplabDatasetMapper from a Detectron2 config with resize, crop, and flip augmentations', 'run_dataset_mapper_call': 'run the dataset mapper on a dataset dict to load, augment, and generate panoptic training targets', 'review_PanopticDeeplabDatasetMapper_augmentations': 'review the PanopticDeeplabDatasetMapper augmentations pipeline that applies resize, crop, and flip to images and labels', 'summarize_panoptic_target_generation': 'summarize how the dataset mapper generates panoptic training targets using rgb2id and the target generator'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/projects/Panoptic-DeepLab/panoptic_deeplab/panoptic_seg.py

Prompts

```
['add Panoptic-DeepLab configuration options to a Detectron2 CfgNode for model training and inference', 'review the add_panoptic_deeplab_config function to understand target generation and post-processing parameters', 'summarize the INS_EMBED_HEAD configuration including ASPP channels, dilations, and loss weights', 'summarize the PANOPTIC_DEEPLAB post-processing settings including NMS kernel and center threshold', 'refactor add_panoptic_deeplab_config to customize default optimizer or loss weight values', 'create a PanopticDeeplabDatasetMapper with augmentations, image format, and a panoptic target generator callable', 'build a PanopticDeeplabDatasetMapper from a Detectron2 config with resize, crop, and flip augmentations', 'run the dataset mapper on a dataset dict to load, augment, and generate panoptic training targets', 'review the PanopticDeeplabDatasetMapper augmentations pipeline that applies resize, crop, and flip to images and labels', 'summarize how the dataset mapper generates panoptic training targets using rgb2id and the target generator', 'build a PanopticDeepLab model from a Detectron2 config to perform panoptic segmentation on images', 'run the PanopticDeepLab forward pass on batched inputs to get panoptic and semantic segmentation results', 'build a PanopticDeepLabSemSegHead with configurable loss types including cross entropy and hard pixel mining', 'build an instance embedding branch using build_ins_embed_branch from the INS_EMBED_BRANCHES_REGISTRY', 'review the PanopticDeepLabInsEmbedHead center and offset loss computation methods for instance embedding training', 'find instance center points from a center heatmap using thresholding and non-maximum suppression', 'group image pixels into instance IDs by assigning each pixel to its nearest detected center point', 'get class-agnostic instance segmentation masks from semantic labels, center heatmap, and offset predictions', 'merge semantic segmentation labels with instance segmentation to produce panoptic segmentation output', 'compute panoptic segmentation by combining semantic labels, center heatmap, and offsets into a unified prediction']
```

Usage

```
{'build_panoptic_deeplab_model': 'build a PanopticDeepLab model from a Detectron2 config to perform panoptic segmentation on images', 'run_panoptic_segmentation_forward': 'run the PanopticDeepLab forward pass on batched inputs to get panoptic and semantic segmentation results', 'build_sem_seg_head': 'build a PanopticDeepLabSemSegHead with configurable loss types including cross entropy and hard pixel mining', 'build_ins_embed_branch': 'build an instance embedding branch using build_ins_embed_branch from the INS_EMBED_BRANCHES_REGISTRY', 'review_ins_embed_head_losses': 'review the PanopticDeepLabInsEmbedHead center and offset loss computation methods for instance embedding training'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/projects/Panoptic-DeepLab/panoptic_deeplab/post_processing.py

Prompts

```
['add Panoptic-DeepLab configuration options to a Detectron2 CfgNode for model training and inference', 'review the add_panoptic_deeplab_config function to understand target generation and post-processing parameters', 'summarize the INS_EMBED_HEAD configuration including ASPP channels, dilations, and loss weights', 'summarize the PANOPTIC_DEEPLAB post-processing settings including NMS kernel and center threshold', 'refactor add_panoptic_deeplab_config to customize default optimizer or loss weight values', 'create a PanopticDeeplabDatasetMapper with augmentations, image format, and a panoptic target generator callable', 'build a PanopticDeeplabDatasetMapper from a Detectron2 config with resize, crop, and flip augmentations', 'run the dataset mapper on a dataset dict to load, augment, and generate panoptic training targets', 'review the PanopticDeeplabDatasetMapper augmentations pipeline that applies resize, crop, and flip to images and labels', 'summarize how the dataset mapper generates panoptic training targets using rgb2id and the target generator', 'build a PanopticDeepLab model from a Detectron2 config to perform panoptic segmentation on images', 'run the PanopticDeepLab forward pass on batched inputs to get panoptic and semantic segmentation results', 'build a PanopticDeepLabSemSegHead with configurable loss types including cross entropy and hard pixel mining', 'build an instance embedding branch using build_ins_embed_branch from the INS_EMBED_BRANCHES_REGISTRY', 'review the PanopticDeepLabInsEmbedHead center and offset loss computation methods for instance embedding training', 'find instance center points from a center heatmap using thresholding and non-maximum suppression', 'group image pixels into instance IDs by assigning each pixel to its nearest detected center point', 'get class-agnostic instance segmentation masks from semantic labels, center heatmap, and offset predictions', 'merge semantic segmentation labels with instance segmentation to produce panoptic segmentation output', 'compute panoptic segmentation by combining semantic labels, center heatmap, and offsets into a unified prediction']
```

Usage

```
{'find_instance_center': 'find instance center points from a center heatmap using thresholding and non-maximum suppression', 'group_pixels': 'group image pixels into instance IDs by assigning each pixel to its nearest detected center point', 'get_instance_segmentation': 'get class-agnostic instance segmentation masks from semantic labels, center heatmap, and offset predictions', 'merge_semantic_and_instance': 'merge semantic segmentation labels with instance segmentation to produce panoptic segmentation output', 'get_panoptic_segmentation': 'compute panoptic segmentation by combining semantic labels, center heatmap, and offsets into a unified prediction'}
```

