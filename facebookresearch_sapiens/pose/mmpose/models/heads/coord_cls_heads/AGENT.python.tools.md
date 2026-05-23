# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pose/mmpose/models/heads/coord_cls_heads/rtmcc_head.py

Prompts

```
['build an RTMCCHead instance with in_channels, out_channels, input_size, and gau_cfg for pose estimation', 'run the forward pass of RTMCCHead on feature maps to get SimCC x and y predictions', 'predict keypoints from feature maps using RTMCCHead with optional flip test TTA and heatmap output', 'calculate keypoint loss and pose accuracy using RTMCCHead loss method with ground truth SimCC labels', 'review the RTMCCHead default_init_cfg property that returns Normal and Constant initialization configs for Conv2d, BatchNorm2d, and Linear layers', 'build a SimCCHead instance with deconvolutional layers and MLP heads for 1D SimCC keypoint representation', 'forward feature maps through SimCCHead to get 1D x and y SimCC predictions', 'predict keypoint coordinates and scores from features using SimCCHead with optional flip test TTA', 'calculate KL divergence loss and PCK accuracy for SimCC predictions against ground truth labels', 'create deconvolutional layers using HeatmapHead or ViPNASHead architecture for feature map upsampling']
```

Usage

```
{'build_RTMCCHead': 'build an RTMCCHead instance with in_channels, out_channels, input_size, and gau_cfg for pose estimation', 'run_forward_RTMCCHead': 'run the forward pass of RTMCCHead on feature maps to get SimCC x and y predictions', 'predict_RTMCCHead': 'predict keypoints from feature maps using RTMCCHead with optional flip test TTA and heatmap output', 'calculate_loss_RTMCCHead': 'calculate keypoint loss and pose accuracy using RTMCCHead loss method with ground truth SimCC labels', 'review_RTMCCHead_default_init_cfg': 'review the RTMCCHead default_init_cfg property that returns Normal and Constant initialization configs for Conv2d, BatchNorm2d, and Linear layers'}
```

## File: facebookresearch_sapiens/pose/mmpose/models/heads/coord_cls_heads/simcc_head.py

Prompts

```
['build an RTMCCHead instance with in_channels, out_channels, input_size, and gau_cfg for pose estimation', 'run the forward pass of RTMCCHead on feature maps to get SimCC x and y predictions', 'predict keypoints from feature maps using RTMCCHead with optional flip test TTA and heatmap output', 'calculate keypoint loss and pose accuracy using RTMCCHead loss method with ground truth SimCC labels', 'review the RTMCCHead default_init_cfg property that returns Normal and Constant initialization configs for Conv2d, BatchNorm2d, and Linear layers', 'build a SimCCHead instance with deconvolutional layers and MLP heads for 1D SimCC keypoint representation', 'forward feature maps through SimCCHead to get 1D x and y SimCC predictions', 'predict keypoint coordinates and scores from features using SimCCHead with optional flip test TTA', 'calculate KL divergence loss and PCK accuracy for SimCC predictions against ground truth labels', 'create deconvolutional layers using HeatmapHead or ViPNASHead architecture for feature map upsampling']
```

Usage

```
{'build_SimCCHead': 'build a SimCCHead instance with deconvolutional layers and MLP heads for 1D SimCC keypoint representation', 'forward_SimCCHead': 'forward feature maps through SimCCHead to get 1D x and y SimCC predictions', 'predict_SimCCHead': 'predict keypoint coordinates and scores from features using SimCCHead with optional flip test TTA', 'loss_SimCCHead': 'calculate KL divergence loss and PCK accuracy for SimCC predictions against ground truth labels', 'make_deconv_head_SimCCHead': 'create deconvolutional layers using HeatmapHead or ViPNASHead architecture for feature map upsampling'}
```

