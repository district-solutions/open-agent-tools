# Agent Python Tools

- repo: facebookresearch/fast3r
- repo_uri: https://github.com/facebookresearch/fast3r

## File: facebookresearch_fast3r/fast3r/dust3r/datasets/aria/camera_utils.py

Prompts

```
['undistort fisheye images and depth maps into pinhole camera images and depth using Fisheye624 and Pinhole parameters', 'apply vignette correction to an RGB image using a loaded vignette mask file', 'project 3D points to 2D image coordinates using the Fisheye624 camera model with radial tangential and thin prism distortion', "unproject 2D image pixels to 3D rays using Newton's method to invert the Fisheye624 camera model", 'unproject 2D pixel coordinates to 3D rays using the Pinhole linear camera model with focal length and principal point']
```

Usage

```
{'undistort_fisheye_to_pinhole_rgbd': 'undistort fisheye images and depth maps into pinhole camera images and depth using Fisheye624 and Pinhole parameters', 'VignetteCorrector_correct': 'apply vignette correction to an RGB image using a loaded vignette mask file', 'fisheye624_project': 'project 3D points to 2D image coordinates using the Fisheye624 camera model with radial tangential and thin prism distortion', 'fisheye624_unproject': "unproject 2D image pixels to 3D rays using Newton's method to invert the Fisheye624 camera model", 'pinhole_unproject': 'unproject 2D pixel coordinates to 3D rays using the Pinhole linear camera model with focal length and principal point'}
```

