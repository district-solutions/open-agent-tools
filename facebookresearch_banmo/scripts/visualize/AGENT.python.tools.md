# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/scripts/visualize/match.py

Prompts

```
['run the match_frames function to find and visualize feature correspondences between pairs of video frames', 'run the construct_rays function to build camera rays from sampled pixel coordinates and extrinsics', 'run the main entry point to initialize a trainer and execute frame matching with absl flags', 'review the construct_rays function that assembles ray vectors and sampled features for NeRF rendering', 'review the match_frames function that performs feature matching, reprojection, and pose code visualization', 'run the NVS script to render novel view RGB, silhouette, and visibility images from camera trajectories', 'run the NVS script with bullet_time flag to render a frozen-frame bullet time effect across camera poses', 'construct camera rays for novel view synthesis given image size, camera poses, near-far bounds, and a render mask', 'render rays through the NeRF model to produce coarse RGB, depth, silhouette, and visibility predictions', 'save rendered RGB, silhouette, and visibility frames as MP4 videos using the save_vid utility', 'run the NVS script to render 120-frame bullet time videos with RGB, silhouette, visibility, and depth outputs', 'run construct_rays_nvs to build camera rays from rotation-translation matrices and a random mask for ray marching', 'run the v2s_trainer in eval mode to initialize the dataset, define the model, and load checkpoint parameters', 'run render_rays in chunked batches through coarse and fine NeRF models to produce RGB, depth, and silhouette predictions', 'run save_vid to compile rendered RGB, silhouette, visibility, and depth frames into MP4 video files']
```

Usage

```
{'run_match_frames': 'run the match_frames function to find and visualize feature correspondences between pairs of video frames', 'run_construct_rays': 'run the construct_rays function to build camera rays from sampled pixel coordinates and extrinsics', 'run_main': 'run the main entry point to initialize a trainer and execute frame matching with absl flags', 'review_construct_rays': 'review the construct_rays function that assembles ray vectors and sampled features for NeRF rendering', 'review_match_frames': 'review the match_frames function that performs feature matching, reprojection, and pose code visualization'}
```

## File: facebookresearch_banmo/scripts/visualize/nvs.py

Prompts

```
['run the match_frames function to find and visualize feature correspondences between pairs of video frames', 'run the construct_rays function to build camera rays from sampled pixel coordinates and extrinsics', 'run the main entry point to initialize a trainer and execute frame matching with absl flags', 'review the construct_rays function that assembles ray vectors and sampled features for NeRF rendering', 'review the match_frames function that performs feature matching, reprojection, and pose code visualization', 'run the NVS script to render novel view RGB, silhouette, and visibility images from camera trajectories', 'run the NVS script with bullet_time flag to render a frozen-frame bullet time effect across camera poses', 'construct camera rays for novel view synthesis given image size, camera poses, near-far bounds, and a render mask', 'render rays through the NeRF model to produce coarse RGB, depth, silhouette, and visibility predictions', 'save rendered RGB, silhouette, and visibility frames as MP4 videos using the save_vid utility', 'run the NVS script to render 120-frame bullet time videos with RGB, silhouette, visibility, and depth outputs', 'run construct_rays_nvs to build camera rays from rotation-translation matrices and a random mask for ray marching', 'run the v2s_trainer in eval mode to initialize the dataset, define the model, and load checkpoint parameters', 'run render_rays in chunked batches through coarse and fine NeRF models to produce RGB, depth, and silhouette predictions', 'run save_vid to compile rendered RGB, silhouette, visibility, and depth frames into MP4 video files']
```

Usage

```
{'run_nvs_rendering': 'run the NVS script to render novel view RGB, silhouette, and visibility images from camera trajectories', 'run_bullet_time_rendering': 'run the NVS script with bullet_time flag to render a frozen-frame bullet time effect across camera poses', 'construct_rays_nvs': 'construct camera rays for novel view synthesis given image size, camera poses, near-far bounds, and a render mask', 'render_nerf_rays': 'render rays through the NeRF model to produce coarse RGB, depth, silhouette, and visibility predictions', 'save_nvs_video': 'save rendered RGB, silhouette, and visibility frames as MP4 videos using the save_vid utility'}
```

## File: facebookresearch_banmo/scripts/visualize/nvs_iter.py

Prompts

```
['run the match_frames function to find and visualize feature correspondences between pairs of video frames', 'run the construct_rays function to build camera rays from sampled pixel coordinates and extrinsics', 'run the main entry point to initialize a trainer and execute frame matching with absl flags', 'review the construct_rays function that assembles ray vectors and sampled features for NeRF rendering', 'review the match_frames function that performs feature matching, reprojection, and pose code visualization', 'run the NVS script to render novel view RGB, silhouette, and visibility images from camera trajectories', 'run the NVS script with bullet_time flag to render a frozen-frame bullet time effect across camera poses', 'construct camera rays for novel view synthesis given image size, camera poses, near-far bounds, and a render mask', 'render rays through the NeRF model to produce coarse RGB, depth, silhouette, and visibility predictions', 'save rendered RGB, silhouette, and visibility frames as MP4 videos using the save_vid utility', 'run the NVS script to render 120-frame bullet time videos with RGB, silhouette, visibility, and depth outputs', 'run construct_rays_nvs to build camera rays from rotation-translation matrices and a random mask for ray marching', 'run the v2s_trainer in eval mode to initialize the dataset, define the model, and load checkpoint parameters', 'run render_rays in chunked batches through coarse and fine NeRF models to produce RGB, depth, and silhouette predictions', 'run save_vid to compile rendered RGB, silhouette, visibility, and depth frames into MP4 video files']
```

Usage

```
{'run_nvs_iter_rendering': 'run the NVS script to render 120-frame bullet time videos with RGB, silhouette, visibility, and depth outputs', 'run_construct_rays_nvs': 'run construct_rays_nvs to build camera rays from rotation-translation matrices and a random mask for ray marching', 'run_v2s_trainer_eval': 'run the v2s_trainer in eval mode to initialize the dataset, define the model, and load checkpoint parameters', 'run_render_rays_chunked': 'run render_rays in chunked batches through coarse and fine NeRF models to produce RGB, depth, and silhouette predictions', 'run_save_vid_outputs': 'run save_vid to compile rendered RGB, silhouette, visibility, and depth frames into MP4 video files'}
```

