# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/cv/mmcv/image/colorspace.py

Prompts

```
['convert an image from one colorspace to another using imconvert with source and destination color names', 'convert a BGR image to grayscale using bgr2gray with optional keepdim to preserve 3D shape', 'convert a RGB image to YCbCr using rgb2ycbcr with optional y_only to extract just the luminance channel', 'convert a YCbCr image back to RGB using ycbcr2rgb with ITU-R BT.601 standard conversion', 'create a custom colorspace converter function using convert_color_factory with source and destination color names', 'resize a numpy array image to a target width and height using cv2 or pillow backend', 'rescale an image by a factor or max size while keeping the aspect ratio', 'rotate an image by a given angle with optional auto-bound and border mode settings', 'crop image patches from bounding boxes with optional scaling and padding', 'pad an image to a target shape or with specified padding values and mode', 'set the global image decoding backend to cv2, pillow, turbojpeg, or tifffile', 'read an image from a file path or URL and return it as a numpy array', 'decode image bytes into a numpy array using cv2, pillow, turbojpeg, or tifffile', 'write a numpy array image to a local file path or remote storage backend', 'convert a PIL Image to a numpy array with configurable color flag and channel order', 'convert a PyTorch tensor of shape N,C,H,W into a list of denormalized NumPy image arrays', 'denormalize a batch of 3-channel images using custom mean and std values', 'convert a normalized RGB tensor back to a list of BGR uint8 images', 'convert a 1-channel grayscale tensor into a list of denormalized NumPy arrays', 'review the tensor2imgs function that converts tensors to images with optional denormalization', 'build a python module to normalize an image using mean and std values', 'build a python module to adjust image brightness by a given factor using cv2 or pillow', 'build a python module to adjust image contrast by a given factor using cv2 or pillow', 'build a python module to auto adjust image contrast by removing cutoff percent of lightest and darkest pixels', 'build a python module to adjust image hue by cyclically shifting the HSV hue channel']
```

Usage

```
{'convert_image_colorspace': 'convert an image from one colorspace to another using imconvert with source and destination color names', 'convert_bgr_to_grayscale': 'convert a BGR image to grayscale using bgr2gray with optional keepdim to preserve 3D shape', 'convert_rgb_to_ycbcr': 'convert a RGB image to YCbCr using rgb2ycbcr with optional y_only to extract just the luminance channel', 'convert_ycbcr_to_rgb': 'convert a YCbCr image back to RGB using ycbcr2rgb with ITU-R BT.601 standard conversion', 'create_custom_converter': 'create a custom colorspace converter function using convert_color_factory with source and destination color names'}
```

## File: facebookresearch_sapiens/cv/mmcv/image/geometric.py

Prompts

```
['convert an image from one colorspace to another using imconvert with source and destination color names', 'convert a BGR image to grayscale using bgr2gray with optional keepdim to preserve 3D shape', 'convert a RGB image to YCbCr using rgb2ycbcr with optional y_only to extract just the luminance channel', 'convert a YCbCr image back to RGB using ycbcr2rgb with ITU-R BT.601 standard conversion', 'create a custom colorspace converter function using convert_color_factory with source and destination color names', 'resize a numpy array image to a target width and height using cv2 or pillow backend', 'rescale an image by a factor or max size while keeping the aspect ratio', 'rotate an image by a given angle with optional auto-bound and border mode settings', 'crop image patches from bounding boxes with optional scaling and padding', 'pad an image to a target shape or with specified padding values and mode', 'set the global image decoding backend to cv2, pillow, turbojpeg, or tifffile', 'read an image from a file path or URL and return it as a numpy array', 'decode image bytes into a numpy array using cv2, pillow, turbojpeg, or tifffile', 'write a numpy array image to a local file path or remote storage backend', 'convert a PIL Image to a numpy array with configurable color flag and channel order', 'convert a PyTorch tensor of shape N,C,H,W into a list of denormalized NumPy image arrays', 'denormalize a batch of 3-channel images using custom mean and std values', 'convert a normalized RGB tensor back to a list of BGR uint8 images', 'convert a 1-channel grayscale tensor into a list of denormalized NumPy arrays', 'review the tensor2imgs function that converts tensors to images with optional denormalization', 'build a python module to normalize an image using mean and std values', 'build a python module to adjust image brightness by a given factor using cv2 or pillow', 'build a python module to adjust image contrast by a given factor using cv2 or pillow', 'build a python module to auto adjust image contrast by removing cutoff percent of lightest and darkest pixels', 'build a python module to adjust image hue by cyclically shifting the HSV hue channel']
```

Usage

```
{'resize_image': 'resize a numpy array image to a target width and height using cv2 or pillow backend', 'rescale_image': 'rescale an image by a factor or max size while keeping the aspect ratio', 'rotate_image': 'rotate an image by a given angle with optional auto-bound and border mode settings', 'crop_image_patches': 'crop image patches from bounding boxes with optional scaling and padding', 'pad_image': 'pad an image to a target shape or with specified padding values and mode'}
```

## File: facebookresearch_sapiens/cv/mmcv/image/io.py

Prompts

```
['convert an image from one colorspace to another using imconvert with source and destination color names', 'convert a BGR image to grayscale using bgr2gray with optional keepdim to preserve 3D shape', 'convert a RGB image to YCbCr using rgb2ycbcr with optional y_only to extract just the luminance channel', 'convert a YCbCr image back to RGB using ycbcr2rgb with ITU-R BT.601 standard conversion', 'create a custom colorspace converter function using convert_color_factory with source and destination color names', 'resize a numpy array image to a target width and height using cv2 or pillow backend', 'rescale an image by a factor or max size while keeping the aspect ratio', 'rotate an image by a given angle with optional auto-bound and border mode settings', 'crop image patches from bounding boxes with optional scaling and padding', 'pad an image to a target shape or with specified padding values and mode', 'set the global image decoding backend to cv2, pillow, turbojpeg, or tifffile', 'read an image from a file path or URL and return it as a numpy array', 'decode image bytes into a numpy array using cv2, pillow, turbojpeg, or tifffile', 'write a numpy array image to a local file path or remote storage backend', 'convert a PIL Image to a numpy array with configurable color flag and channel order', 'convert a PyTorch tensor of shape N,C,H,W into a list of denormalized NumPy image arrays', 'denormalize a batch of 3-channel images using custom mean and std values', 'convert a normalized RGB tensor back to a list of BGR uint8 images', 'convert a 1-channel grayscale tensor into a list of denormalized NumPy arrays', 'review the tensor2imgs function that converts tensors to images with optional denormalization', 'build a python module to normalize an image using mean and std values', 'build a python module to adjust image brightness by a given factor using cv2 or pillow', 'build a python module to adjust image contrast by a given factor using cv2 or pillow', 'build a python module to auto adjust image contrast by removing cutoff percent of lightest and darkest pixels', 'build a python module to adjust image hue by cyclically shifting the HSV hue channel']
```

Usage

```
{'use_backend': 'set the global image decoding backend to cv2, pillow, turbojpeg, or tifffile', 'imread': 'read an image from a file path or URL and return it as a numpy array', 'imfrombytes': 'decode image bytes into a numpy array using cv2, pillow, turbojpeg, or tifffile', 'imwrite': 'write a numpy array image to a local file path or remote storage backend', 'pillow2array': 'convert a PIL Image to a numpy array with configurable color flag and channel order'}
```

## File: facebookresearch_sapiens/cv/mmcv/image/misc.py

Prompts

```
['convert an image from one colorspace to another using imconvert with source and destination color names', 'convert a BGR image to grayscale using bgr2gray with optional keepdim to preserve 3D shape', 'convert a RGB image to YCbCr using rgb2ycbcr with optional y_only to extract just the luminance channel', 'convert a YCbCr image back to RGB using ycbcr2rgb with ITU-R BT.601 standard conversion', 'create a custom colorspace converter function using convert_color_factory with source and destination color names', 'resize a numpy array image to a target width and height using cv2 or pillow backend', 'rescale an image by a factor or max size while keeping the aspect ratio', 'rotate an image by a given angle with optional auto-bound and border mode settings', 'crop image patches from bounding boxes with optional scaling and padding', 'pad an image to a target shape or with specified padding values and mode', 'set the global image decoding backend to cv2, pillow, turbojpeg, or tifffile', 'read an image from a file path or URL and return it as a numpy array', 'decode image bytes into a numpy array using cv2, pillow, turbojpeg, or tifffile', 'write a numpy array image to a local file path or remote storage backend', 'convert a PIL Image to a numpy array with configurable color flag and channel order', 'convert a PyTorch tensor of shape N,C,H,W into a list of denormalized NumPy image arrays', 'denormalize a batch of 3-channel images using custom mean and std values', 'convert a normalized RGB tensor back to a list of BGR uint8 images', 'convert a 1-channel grayscale tensor into a list of denormalized NumPy arrays', 'review the tensor2imgs function that converts tensors to images with optional denormalization', 'build a python module to normalize an image using mean and std values', 'build a python module to adjust image brightness by a given factor using cv2 or pillow', 'build a python module to adjust image contrast by a given factor using cv2 or pillow', 'build a python module to auto adjust image contrast by removing cutoff percent of lightest and darkest pixels', 'build a python module to adjust image hue by cyclically shifting the HSV hue channel']
```

Usage

```
{'convert_tensor_to_images': 'convert a PyTorch tensor of shape N,C,H,W into a list of denormalized NumPy image arrays', 'denormalize_batch_of_images': 'denormalize a batch of 3-channel images using custom mean and std values', 'convert_tensor_to_bgr_images': 'convert a normalized RGB tensor back to a list of BGR uint8 images', 'convert_grayscale_tensor_to_images': 'convert a 1-channel grayscale tensor into a list of denormalized NumPy arrays', 'review_tensor2imgs_function': 'review the tensor2imgs function that converts tensors to images with optional denormalization'}
```

## File: facebookresearch_sapiens/cv/mmcv/image/photometric.py

Prompts

```
['convert an image from one colorspace to another using imconvert with source and destination color names', 'convert a BGR image to grayscale using bgr2gray with optional keepdim to preserve 3D shape', 'convert a RGB image to YCbCr using rgb2ycbcr with optional y_only to extract just the luminance channel', 'convert a YCbCr image back to RGB using ycbcr2rgb with ITU-R BT.601 standard conversion', 'create a custom colorspace converter function using convert_color_factory with source and destination color names', 'resize a numpy array image to a target width and height using cv2 or pillow backend', 'rescale an image by a factor or max size while keeping the aspect ratio', 'rotate an image by a given angle with optional auto-bound and border mode settings', 'crop image patches from bounding boxes with optional scaling and padding', 'pad an image to a target shape or with specified padding values and mode', 'set the global image decoding backend to cv2, pillow, turbojpeg, or tifffile', 'read an image from a file path or URL and return it as a numpy array', 'decode image bytes into a numpy array using cv2, pillow, turbojpeg, or tifffile', 'write a numpy array image to a local file path or remote storage backend', 'convert a PIL Image to a numpy array with configurable color flag and channel order', 'convert a PyTorch tensor of shape N,C,H,W into a list of denormalized NumPy image arrays', 'denormalize a batch of 3-channel images using custom mean and std values', 'convert a normalized RGB tensor back to a list of BGR uint8 images', 'convert a 1-channel grayscale tensor into a list of denormalized NumPy arrays', 'review the tensor2imgs function that converts tensors to images with optional denormalization', 'build a python module to normalize an image using mean and std values', 'build a python module to adjust image brightness by a given factor using cv2 or pillow', 'build a python module to adjust image contrast by a given factor using cv2 or pillow', 'build a python module to auto adjust image contrast by removing cutoff percent of lightest and darkest pixels', 'build a python module to adjust image hue by cyclically shifting the HSV hue channel']
```

Usage

```
{'build_imnormalize': 'build a python module to normalize an image using mean and std values', 'build_adjust_brightness': 'build a python module to adjust image brightness by a given factor using cv2 or pillow', 'build_adjust_contrast': 'build a python module to adjust image contrast by a given factor using cv2 or pillow', 'build_auto_contrast': 'build a python module to auto adjust image contrast by removing cutoff percent of lightest and darkest pixels', 'build_adjust_hue': 'build a python module to adjust image hue by cyclically shifting the HSV hue channel'}
```

