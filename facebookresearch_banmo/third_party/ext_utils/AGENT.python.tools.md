# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/ext_utils/flowlib.py

Prompts

```
['warp an image using an optical flow field with optional normalized coordinates', 'concatenate an image with its optical flow visualization as colored arrows', 'draw arrow vectors on an image to visualize optical flow direction and magnitude', 'convert an optical flow map into a Middlebury color-coded image for visualization', 'compute a color-coded optical flow image from horizontal and vertical flow components', 'read a PFM file and return the numpy array data and scale factor', 'write a numpy array as a PFM file to the given path with optional scale', 'read a color PFM file with PF header and return height width 3 data', 'read a grayscale PFM file with Pf header and return height width data', 'write a 2 channel flow field as a PFM file by padding to 3 channels']
```

Usage

```
{'warp_flow': 'warp an image using an optical flow field with optional normalized coordinates', 'cat_imgflo': 'concatenate an image with its optical flow visualization as colored arrows', 'point_vec': 'draw arrow vectors on an image to visualize optical flow direction and magnitude', 'flow_to_image': 'convert an optical flow map into a Middlebury color-coded image for visualization', 'compute_color': 'compute a color-coded optical flow image from horizontal and vertical flow components'}
```

## File: facebookresearch_banmo/third_party/ext_utils/util_flow.py

Prompts

```
['warp an image using an optical flow field with optional normalized coordinates', 'concatenate an image with its optical flow visualization as colored arrows', 'draw arrow vectors on an image to visualize optical flow direction and magnitude', 'convert an optical flow map into a Middlebury color-coded image for visualization', 'compute a color-coded optical flow image from horizontal and vertical flow components', 'read a PFM file and return the numpy array data and scale factor', 'write a numpy array as a PFM file to the given path with optional scale', 'read a color PFM file with PF header and return height width 3 data', 'read a grayscale PFM file with Pf header and return height width data', 'write a 2 channel flow field as a PFM file by padding to 3 channels']
```

Usage

```
{'readPFM': 'read a PFM file and return the numpy array data and scale factor', 'write_pfm': 'write a numpy array as a PFM file to the given path with optional scale', 'readPFM_color': 'read a color PFM file with PF header and return height width 3 data', 'readPFM_grayscale': 'read a grayscale PFM file with Pf header and return height width data', 'write_pfm_flow': 'write a 2 channel flow field as a PFM file by padding to 3 channels'}
```

