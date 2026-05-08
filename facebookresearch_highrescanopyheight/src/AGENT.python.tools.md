# Agent Python Tools

- repo: facebookresearch/highrescanopyheight
- repo_uri: https://github.com/facebookresearch/highrescanopyheight

## File: facebookresearch_highrescanopyheight/src/raster_utils.py

Prompts

```
['create a Gaussian-smoothed apodization weight array for a given window size and padding integer', 'create a stacked array of overlapping thumbnail blocks from a 2D raster using a specified block shape and step', 'reconstruct a full-size raster image from stacked thumbnail blocks using weighted coaddition and inverse blocking', 'review the blocking function to understand how overlapping window tiles are created from a 2D array', 'summarize the inverse_blocking function that merges weighted thumbnail blocks back into a full raster image', 'create an SSLNorm instance to get preconfigured image normalization transforms for self-supervised learning', 'build a Norm instance and call get_trans with custom mean and std values for image normalization', 'apply the Trans composed transform to convert and normalize an image tensor', 'apply the invTrans composed transform to denormalize a tensor back to original image values', 'review the Norm class and its get_trans method for configuring forward and inverse image normalization']
```

Usage

```
{'create_apodization_weight': 'create a Gaussian-smoothed apodization weight array for a given window size and padding integer', 'blocking_tile_raster': 'create a stacked array of overlapping thumbnail blocks from a 2D raster using a specified block shape and step', 'inverse_blocking_reconstruct': 'reconstruct a full-size raster image from stacked thumbnail blocks using weighted coaddition and inverse blocking', 'review_blocking_overlap': 'review the blocking function to understand how overlapping window tiles are created from a 2D array', 'summarize_inverse_blocking': 'summarize the inverse_blocking function that merges weighted thumbnail blocks back into a full raster image'}
```

## File: facebookresearch_highrescanopyheight/src/transforms.py

Prompts

```
['create a Gaussian-smoothed apodization weight array for a given window size and padding integer', 'create a stacked array of overlapping thumbnail blocks from a 2D raster using a specified block shape and step', 'reconstruct a full-size raster image from stacked thumbnail blocks using weighted coaddition and inverse blocking', 'review the blocking function to understand how overlapping window tiles are created from a 2D array', 'summarize the inverse_blocking function that merges weighted thumbnail blocks back into a full raster image', 'create an SSLNorm instance to get preconfigured image normalization transforms for self-supervised learning', 'build a Norm instance and call get_trans with custom mean and std values for image normalization', 'apply the Trans composed transform to convert and normalize an image tensor', 'apply the invTrans composed transform to denormalize a tensor back to original image values', 'review the Norm class and its get_trans method for configuring forward and inverse image normalization']
```

Usage

```
{'create_ssl_norm_transform': 'create an SSLNorm instance to get preconfigured image normalization transforms for self-supervised learning', 'build_custom_norm_transform': 'build a Norm instance and call get_trans with custom mean and std values for image normalization', 'apply_forward_transform': 'apply the Trans composed transform to convert and normalize an image tensor', 'apply_inverse_transform': 'apply the invTrans composed transform to denormalize a tensor back to original image values', 'review_norm_class': 'review the Norm class and its get_trans method for configuring forward and inverse image normalization'}
```

