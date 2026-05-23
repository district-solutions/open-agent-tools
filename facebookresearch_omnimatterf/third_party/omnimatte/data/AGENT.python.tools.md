# Agent Python Tools

- repo: facebookresearch/omnimatterf
- repo_uri: https://github.com/facebookresearch/omnimatterf

## File: facebookresearch_omnimatterf/third_party/omnimatte/data/omnimatte_dataset.py

Prompts

```
['create an OmnimatteDataset instance from dataroot with rgb, mask, flow, and confidence directories', 'load an image file and return it as a normalized tensor in range [-1, 1]', 'apply jitter and crop transforms to a data tensor using interpolation parameters', 'compute background optical flow between two frames using homography matrices and scale factors', 'convert a binary mask into a trimap with foreground, background, and unknown regions']
```

Usage

```
{'create_OmnimatteDataset': 'create an OmnimatteDataset instance from dataroot with rgb, mask, flow, and confidence directories', 'load_and_process_image': 'load an image file and return it as a normalized tensor in range [-1, 1]', 'apply_transform': 'apply jitter and crop transforms to a data tensor using interpolation parameters', 'get_background_flow': 'compute background optical flow between two frames using homography matrices and scale factors', 'mask2trimap': 'convert a binary mask into a trimap with foreground, background, and unknown regions'}
```

