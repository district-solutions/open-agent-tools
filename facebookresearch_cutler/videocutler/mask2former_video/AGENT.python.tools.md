# Agent Python Tools

- repo: facebookresearch/cutler
- repo_uri: https://github.com/facebookresearch/cutler

## File: facebookresearch_cutler/videocutler/mask2former_video/config.py

Prompts

```
['add video segmentation config defaults to a detectron2 CfgNode for frame sampling, copy-paste augmentation, and solver settings', 'review the add_maskformer2_video_config function to understand default video input and dataloader config options', 'refactor add_maskformer2_video_config to add new config fields for custom video augmentation pipelines', 'summarize the add_maskformer2_video_config function and its detectron2 CfgNode default settings', 'test the add_maskformer2_video_config function by passing a CfgNode and verifying all config fields are set', 'build a VideoMaskFormer model from a detectron2 config with backbone, head, and criterion', 'run the VideoMaskFormer forward pass on batched video inputs for training or inference', 'review the inference_video method that post-processes predicted masks and scores for video output', 'test the prepare_targets method that assembles ground truth masks and labels for training', 'refactor the VideoMaskFormer constructor to add new configurable parameters for video segmentation']
```

Usage

```
{'add_maskformer2_video_config': 'add video segmentation config defaults to a detectron2 CfgNode for frame sampling, copy-paste augmentation, and solver settings', 'review_add_maskformer2_video_config': 'review the add_maskformer2_video_config function to understand default video input and dataloader config options', 'refactor_add_maskformer2_video_config': 'refactor add_maskformer2_video_config to add new config fields for custom video augmentation pipelines', 'summarize_add_maskformer2_video_config': 'summarize the add_maskformer2_video_config function and its detectron2 CfgNode default settings', 'test_add_maskformer2_video_config': 'test the add_maskformer2_video_config function by passing a CfgNode and verifying all config fields are set'}
```

## File: facebookresearch_cutler/videocutler/mask2former_video/video_maskformer_model.py

Prompts

```
['add video segmentation config defaults to a detectron2 CfgNode for frame sampling, copy-paste augmentation, and solver settings', 'review the add_maskformer2_video_config function to understand default video input and dataloader config options', 'refactor add_maskformer2_video_config to add new config fields for custom video augmentation pipelines', 'summarize the add_maskformer2_video_config function and its detectron2 CfgNode default settings', 'test the add_maskformer2_video_config function by passing a CfgNode and verifying all config fields are set', 'build a VideoMaskFormer model from a detectron2 config with backbone, head, and criterion', 'run the VideoMaskFormer forward pass on batched video inputs for training or inference', 'review the inference_video method that post-processes predicted masks and scores for video output', 'test the prepare_targets method that assembles ground truth masks and labels for training', 'refactor the VideoMaskFormer constructor to add new configurable parameters for video segmentation']
```

Usage

```
{'build_VideoMaskFormer_from_config': 'build a VideoMaskFormer model from a detectron2 config with backbone, head, and criterion', 'run_VideoMaskFormer_forward': 'run the VideoMaskFormer forward pass on batched video inputs for training or inference', 'review_VideoMaskFormer_inference_video': 'review the inference_video method that post-processes predicted masks and scores for video output', 'test_VideoMaskFormer_prepare_targets': 'test the prepare_targets method that assembles ground truth masks and labels for training', 'refactor_VideoMaskFormer_init': 'refactor the VideoMaskFormer constructor to add new configurable parameters for video segmentation'}
```

