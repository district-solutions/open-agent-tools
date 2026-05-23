# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pose/mmpose/models/heads/hybrid_heads/dekr_head.py

Prompts

```
['build a DEKRHead instance with heatmap and displacement branches for bottom-up human pose estimation', 'create an AdaptiveActivationBlock with deformable convolution for adaptive feature activation in the displacement branch', 'create a RescoreNet to predict OKS scores from keypoints, keypoint scores, and skeleton links', 'test the DEKRHead forward pass to produce heatmap and displacement outputs from multi-scale feature maps', 'test the DEKRHead decode method to extract keypoints and scores from heatmap and displacement predictions', 'build a VisPredictHead with pose_cfg and BCELoss for joint keypoint visibility prediction', 'run vis_forward on multi-scale feature maps to predict keypoint coordinates visibility', 'test the forward method to get both pose coordinates and visibility predictions from features', 'review the integrate method that overwrites keypoint_scores with visibility predictions in pose instances', 'summarize the loss method that calculates visibility loss, accuracy, and keypoint losses together']
```

Usage

```
{'build_DEKRHead': 'build a DEKRHead instance with heatmap and displacement branches for bottom-up human pose estimation', 'create_AdaptiveActivationBlock': 'create an AdaptiveActivationBlock with deformable convolution for adaptive feature activation in the displacement branch', 'create_RescoreNet': 'create a RescoreNet to predict OKS scores from keypoints, keypoint scores, and skeleton links', 'test_DEKRHead_forward': 'test the DEKRHead forward pass to produce heatmap and displacement outputs from multi-scale feature maps', 'test_DEKRHead_decode': 'test the DEKRHead decode method to extract keypoints and scores from heatmap and displacement predictions'}
```

## File: facebookresearch_sapiens/pose/mmpose/models/heads/hybrid_heads/vis_head.py

Prompts

```
['build a DEKRHead instance with heatmap and displacement branches for bottom-up human pose estimation', 'create an AdaptiveActivationBlock with deformable convolution for adaptive feature activation in the displacement branch', 'create a RescoreNet to predict OKS scores from keypoints, keypoint scores, and skeleton links', 'test the DEKRHead forward pass to produce heatmap and displacement outputs from multi-scale feature maps', 'test the DEKRHead decode method to extract keypoints and scores from heatmap and displacement predictions', 'build a VisPredictHead with pose_cfg and BCELoss for joint keypoint visibility prediction', 'run vis_forward on multi-scale feature maps to predict keypoint coordinates visibility', 'test the forward method to get both pose coordinates and visibility predictions from features', 'review the integrate method that overwrites keypoint_scores with visibility predictions in pose instances', 'summarize the loss method that calculates visibility loss, accuracy, and keypoint losses together']
```

Usage

```
{'build_VisPredictHead': 'build a VisPredictHead with pose_cfg and BCELoss for joint keypoint visibility prediction', 'run_vis_forward': 'run vis_forward on multi-scale feature maps to predict keypoint coordinates visibility', 'test_forward': 'test the forward method to get both pose coordinates and visibility predictions from features', 'review_integrate': 'review the integrate method that overwrites keypoint_scores with visibility predictions in pose instances', 'summarize_loss': 'summarize the loss method that calculates visibility loss, accuracy, and keypoint losses together'}
```

