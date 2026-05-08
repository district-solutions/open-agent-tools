# Agent Python Tools

- repo: facebookresearch/hot3d
- repo_uri: https://github.com/facebookresearch/hot3d

## File: facebookresearch_hot3d/hot3d/clips/clip_util.py

Prompts

```
['load a 3D mesh from a file path, subdivide edges, and return a cleaned trimesh object', 'encode a binary numpy mask into a compact RLE dictionary with height, width, and runs', 'decode an RLE-encoded mask dictionary back into a 2D boolean numpy array', 'subdivide a trimesh mesh so all edges are shorter than a given maximum length in meters', 'horizontally stack a list of images into one, resizing to the smallest height if needed', 'run the vis_clips CLI to visualize hand and object models in GT poses for clips', 'run vis_clips with undistort flag to warp fisheye images to pinhole camera before visualization', 'run vis_clips with mano hand type to visualize MANO hand model annotations instead of umetrack', 'run vis_clips with amodal or modal mask visualization for object segmentation overlays', 'run vis_clips with clip_start and clip_end to visualize a specific range of clips']
```

Usage

```
{'load_mesh': 'load a 3D mesh from a file path, subdivide edges, and return a cleaned trimesh object', 'encode_binary_mask_rle': 'encode a binary numpy mask into a compact RLE dictionary with height, width, and runs', 'decode_binary_mask_rle': 'decode an RLE-encoded mask dictionary back into a 2D boolean numpy array', 'subdivide_mesh': 'subdivide a trimesh mesh so all edges are shorter than a given maximum length in meters', 'stack_images': 'horizontally stack a list of images into one, resizing to the smallest height if needed'}
```

## File: facebookresearch_hot3d/hot3d/clips/vis_clips.py

Prompts

```
['load a 3D mesh from a file path, subdivide edges, and return a cleaned trimesh object', 'encode a binary numpy mask into a compact RLE dictionary with height, width, and runs', 'decode an RLE-encoded mask dictionary back into a 2D boolean numpy array', 'subdivide a trimesh mesh so all edges are shorter than a given maximum length in meters', 'horizontally stack a list of images into one, resizing to the smallest height if needed', 'run the vis_clips CLI to visualize hand and object models in GT poses for clips', 'run vis_clips with undistort flag to warp fisheye images to pinhole camera before visualization', 'run vis_clips with mano hand type to visualize MANO hand model annotations instead of umetrack', 'run vis_clips with amodal or modal mask visualization for object segmentation overlays', 'run vis_clips with clip_start and clip_end to visualize a specific range of clips']
```

Usage

```
{'run_vis_clips_cli': 'run the vis_clips CLI to visualize hand and object models in GT poses for clips', 'run_vis_clips_undistort': 'run vis_clips with undistort flag to warp fisheye images to pinhole camera before visualization', 'run_vis_clips_mano': 'run vis_clips with mano hand type to visualize MANO hand model annotations instead of umetrack', 'run_vis_clips_masks': 'run vis_clips with amodal or modal mask visualization for object segmentation overlays', 'run_vis_clips_range': 'run vis_clips with clip_start and clip_end to visualize a specific range of clips'}
```

