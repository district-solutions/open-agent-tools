# Agent Python Tools

- repo: facebookresearch/map-anything
- repo_uri: https://github.com/facebookresearch/map-anything

## File: facebookresearch_map-anything/mapanything/models/external/vggt/models/aggregator.py

Prompts

```
['build an Aggregator model with DINOv2 patch embed and alternating frame-global attention blocks', 'run the Aggregator forward pass on a batch of images with shape B,S,3,H,W', 'build the Aggregator with a conv patch embed instead of DINOv2 pretrained weights', 'test the slice_expand_and_flatten function to expand camera tokens for batch and sequence dimensions', 'review the Aggregator alternating attention mechanism that alternates between frame and global attention blocks', 'build a VGGT model instance with configurable image size, patch size, embed dim, depth, and num heads', 'run a forward pass of the VGGT model on input images to get depth, pose, and world point predictions', 'run a forward pass of the VGGT model with query points to get point tracking predictions', 'review the VGGT forward pass that returns camera pose encoding, depth maps, world points, and optional tracks', 'summarize the VGGT class that combines an Aggregator with CameraHead, DPTHead, and TrackHead for vision geometry tasks']
```

Usage

```
{'build_aggregator_model': 'build an Aggregator model with DINOv2 patch embed and alternating frame-global attention blocks', 'run_aggregator_forward': 'run the Aggregator forward pass on a batch of images with shape B,S,3,H,W', 'build_patch_embed_conv': 'build the Aggregator with a conv patch embed instead of DINOv2 pretrained weights', 'test_slice_expand_and_flatten': 'test the slice_expand_and_flatten function to expand camera tokens for batch and sequence dimensions', 'review_aggregator_alternating_attention': 'review the Aggregator alternating attention mechanism that alternates between frame and global attention blocks'}
```

## File: facebookresearch_map-anything/mapanything/models/external/vggt/models/vggt.py

Prompts

```
['build an Aggregator model with DINOv2 patch embed and alternating frame-global attention blocks', 'run the Aggregator forward pass on a batch of images with shape B,S,3,H,W', 'build the Aggregator with a conv patch embed instead of DINOv2 pretrained weights', 'test the slice_expand_and_flatten function to expand camera tokens for batch and sequence dimensions', 'review the Aggregator alternating attention mechanism that alternates between frame and global attention blocks', 'build a VGGT model instance with configurable image size, patch size, embed dim, depth, and num heads', 'run a forward pass of the VGGT model on input images to get depth, pose, and world point predictions', 'run a forward pass of the VGGT model with query points to get point tracking predictions', 'review the VGGT forward pass that returns camera pose encoding, depth maps, world points, and optional tracks', 'summarize the VGGT class that combines an Aggregator with CameraHead, DPTHead, and TrackHead for vision geometry tasks']
```

Usage

```
{'build_VGGT_model': 'build a VGGT model instance with configurable image size, patch size, embed dim, depth, and num heads', 'run_VGGT_forward': 'run a forward pass of the VGGT model on input images to get depth, pose, and world point predictions', 'run_VGGT_forward_with_tracking': 'run a forward pass of the VGGT model with query points to get point tracking predictions', 'review_VGGT_forward': 'review the VGGT forward pass that returns camera pose encoding, depth maps, world points, and optional tracks', 'summarize_VGGT_class': 'summarize the VGGT class that combines an Aggregator with CameraHead, DPTHead, and TrackHead for vision geometry tasks'}
```

