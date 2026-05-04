# Agent Python Tools

- repo: facebookresearch/fvcore
- repo_uri: https://github.com/facebookresearch/fvcore

## File: facebookresearch_fvcore/fvcore/transforms/transform.py

Prompts

```
['create an HFlipTransform to horizontally flip an image and its coordinates given the image width', 'create a VFlipTransform to vertically flip an image and its coordinates given the image height', 'create a ScaleTransform to resize an image from original height and width to new dimensions with interpolation', 'create a CropTransform to crop an image starting at x0,y0 with given width and height', 'create a TransformList to chain multiple transforms like HFlipTransform and ScaleTransform and apply them in sequence', 'convert a numpy array of shape HxWxC or NxHxWxC to a PyTorch float tensor with NxCxHxW dimensions', 'convert a PyTorch float tensor with NxCxHxW shape back to a numpy array with target shape and dtype', 'review the to_float_tensor function that handles uint8 to float conversion and negative stride resolution', 'review the to_numpy function that handles tensor to numpy conversion with rounding for uint8 output', 'test the to_float_tensor function with 2D, 3D, and 4D numpy arrays to verify correct NxCxHxW output']
```

Usage

```
{'create_hflip_transform': 'create an HFlipTransform to horizontally flip an image and its coordinates given the image width', 'create_vflip_transform': 'create a VFlipTransform to vertically flip an image and its coordinates given the image height', 'create_scale_transform': 'create a ScaleTransform to resize an image from original height and width to new dimensions with interpolation', 'create_crop_transform': 'create a CropTransform to crop an image starting at x0,y0 with given width and height', 'create_transform_list': 'create a TransformList to chain multiple transforms like HFlipTransform and ScaleTransform and apply them in sequence'}
```

## File: facebookresearch_fvcore/fvcore/transforms/transform_util.py

Prompts

```
['create an HFlipTransform to horizontally flip an image and its coordinates given the image width', 'create a VFlipTransform to vertically flip an image and its coordinates given the image height', 'create a ScaleTransform to resize an image from original height and width to new dimensions with interpolation', 'create a CropTransform to crop an image starting at x0,y0 with given width and height', 'create a TransformList to chain multiple transforms like HFlipTransform and ScaleTransform and apply them in sequence', 'convert a numpy array of shape HxWxC or NxHxWxC to a PyTorch float tensor with NxCxHxW dimensions', 'convert a PyTorch float tensor with NxCxHxW shape back to a numpy array with target shape and dtype', 'review the to_float_tensor function that handles uint8 to float conversion and negative stride resolution', 'review the to_numpy function that handles tensor to numpy conversion with rounding for uint8 output', 'test the to_float_tensor function with 2D, 3D, and 4D numpy arrays to verify correct NxCxHxW output']
```

Usage

```
{'convert_numpy_to_float_tensor': 'convert a numpy array of shape HxWxC or NxHxWxC to a PyTorch float tensor with NxCxHxW dimensions', 'convert_tensor_to_numpy': 'convert a PyTorch float tensor with NxCxHxW shape back to a numpy array with target shape and dtype', 'review_to_float_tensor': 'review the to_float_tensor function that handles uint8 to float conversion and negative stride resolution', 'review_to_numpy': 'review the to_numpy function that handles tensor to numpy conversion with rounding for uint8 output', 'test_to_float_tensor': 'test the to_float_tensor function with 2D, 3D, and 4D numpy arrays to verify correct NxCxHxW output'}
```

