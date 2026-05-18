# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/mmcv/image/colorspace.py

Prompts

```
['build a python module to convert an image from one colorspace to another using imconvert', 'create a function that converts a BGR image to grayscale with optional dimension keeping', 'test the rgb2ycbcr function to convert a RGB image to YCbCr using ITU-R BT.601', 'refactor the ycbcr2rgb function to convert a YCbCr image back to RGB colorspace', 'review the convert_color_factory function that generates colorspace conversion functions dynamically', 'build a python module that resizes an image to a target size using cv2 or pillow backend', 'create a function that rotates an image by a given angle with optional auto-bound adjustment', 'test the imcrop function to extract and pad image patches from bounding boxes', 'refactor the impad function to support constant edge reflect and symmetric padding modes', 'summarize the bbox_scaling function that scales bounding boxes relative to their center point', 'switch the global image decoding backend to turbojpeg for faster JPEG decoding', 'read an image from a file path or S3 URL into a numpy array with cv2 backend', 'decode image bytes from a buffer into a numpy array using the pillow backend', 'write a numpy array image to a local file or S3 path with automatic encoding', 'convert a PIL Image object to a BGR numpy array with EXIF orientation handling', 'convert a PyTorch tensor of shape (N, C, H, W) into a list of denormalized NumPy image arrays', 'denormalize a batch of normalized image tensors using custom mean and std values back to uint8', 'convert a batch of RGB-normalized tensors back to BGR uint8 images for OpenCV display', 'convert a single-channel grayscale tensor batch into a list of uint8 grayscale image arrays', 'review the tensor2imgs function that converts normalized PyTorch image tensors to denormalized NumPy arrays', 'build a python module to normalize an image array with given mean and std values', 'build a python module to adjust the brightness of an image by a given factor', 'build a python module to adjust the contrast of an image by a given factor', 'build a python module to auto adjust image contrast by removing cutoff percent of histogram', 'build a python module to adjust the hue of an image by shifting the HSV hue channel']
```

Usage

```
{'build_imconvert': 'build a python module to convert an image from one colorspace to another using imconvert', 'create_bgr2gray': 'create a function that converts a BGR image to grayscale with optional dimension keeping', 'test_rgb2ycbcr': 'test the rgb2ycbcr function to convert a RGB image to YCbCr using ITU-R BT.601', 'refactor_ycbcr2rgb': 'refactor the ycbcr2rgb function to convert a YCbCr image back to RGB colorspace', 'review_convert_color_factory': 'review the convert_color_factory function that generates colorspace conversion functions dynamically'}
```

## File: facebookresearch_nerf-det/mmdet3d/mmcv/image/geometric.py

Prompts

```
['build a python module to convert an image from one colorspace to another using imconvert', 'create a function that converts a BGR image to grayscale with optional dimension keeping', 'test the rgb2ycbcr function to convert a RGB image to YCbCr using ITU-R BT.601', 'refactor the ycbcr2rgb function to convert a YCbCr image back to RGB colorspace', 'review the convert_color_factory function that generates colorspace conversion functions dynamically', 'build a python module that resizes an image to a target size using cv2 or pillow backend', 'create a function that rotates an image by a given angle with optional auto-bound adjustment', 'test the imcrop function to extract and pad image patches from bounding boxes', 'refactor the impad function to support constant edge reflect and symmetric padding modes', 'summarize the bbox_scaling function that scales bounding boxes relative to their center point', 'switch the global image decoding backend to turbojpeg for faster JPEG decoding', 'read an image from a file path or S3 URL into a numpy array with cv2 backend', 'decode image bytes from a buffer into a numpy array using the pillow backend', 'write a numpy array image to a local file or S3 path with automatic encoding', 'convert a PIL Image object to a BGR numpy array with EXIF orientation handling', 'convert a PyTorch tensor of shape (N, C, H, W) into a list of denormalized NumPy image arrays', 'denormalize a batch of normalized image tensors using custom mean and std values back to uint8', 'convert a batch of RGB-normalized tensors back to BGR uint8 images for OpenCV display', 'convert a single-channel grayscale tensor batch into a list of uint8 grayscale image arrays', 'review the tensor2imgs function that converts normalized PyTorch image tensors to denormalized NumPy arrays', 'build a python module to normalize an image array with given mean and std values', 'build a python module to adjust the brightness of an image by a given factor', 'build a python module to adjust the contrast of an image by a given factor', 'build a python module to auto adjust image contrast by removing cutoff percent of histogram', 'build a python module to adjust the hue of an image by shifting the HSV hue channel']
```

Usage

```
{'build_imresize_backend': 'build a python module that resizes an image to a target size using cv2 or pillow backend', 'create_imrotate_affine': 'create a function that rotates an image by a given angle with optional auto-bound adjustment', 'test_imcrop_patches': 'test the imcrop function to extract and pad image patches from bounding boxes', 'refactor_impad_modes': 'refactor the impad function to support constant edge reflect and symmetric padding modes', 'summarize_bbox_scaling': 'summarize the bbox_scaling function that scales bounding boxes relative to their center point'}
```

## File: facebookresearch_nerf-det/mmdet3d/mmcv/image/io.py

Prompts

```
['build a python module to convert an image from one colorspace to another using imconvert', 'create a function that converts a BGR image to grayscale with optional dimension keeping', 'test the rgb2ycbcr function to convert a RGB image to YCbCr using ITU-R BT.601', 'refactor the ycbcr2rgb function to convert a YCbCr image back to RGB colorspace', 'review the convert_color_factory function that generates colorspace conversion functions dynamically', 'build a python module that resizes an image to a target size using cv2 or pillow backend', 'create a function that rotates an image by a given angle with optional auto-bound adjustment', 'test the imcrop function to extract and pad image patches from bounding boxes', 'refactor the impad function to support constant edge reflect and symmetric padding modes', 'summarize the bbox_scaling function that scales bounding boxes relative to their center point', 'switch the global image decoding backend to turbojpeg for faster JPEG decoding', 'read an image from a file path or S3 URL into a numpy array with cv2 backend', 'decode image bytes from a buffer into a numpy array using the pillow backend', 'write a numpy array image to a local file or S3 path with automatic encoding', 'convert a PIL Image object to a BGR numpy array with EXIF orientation handling', 'convert a PyTorch tensor of shape (N, C, H, W) into a list of denormalized NumPy image arrays', 'denormalize a batch of normalized image tensors using custom mean and std values back to uint8', 'convert a batch of RGB-normalized tensors back to BGR uint8 images for OpenCV display', 'convert a single-channel grayscale tensor batch into a list of uint8 grayscale image arrays', 'review the tensor2imgs function that converts normalized PyTorch image tensors to denormalized NumPy arrays', 'build a python module to normalize an image array with given mean and std values', 'build a python module to adjust the brightness of an image by a given factor', 'build a python module to adjust the contrast of an image by a given factor', 'build a python module to auto adjust image contrast by removing cutoff percent of histogram', 'build a python module to adjust the hue of an image by shifting the HSV hue channel']
```

Usage

```
{'use_backend': 'switch the global image decoding backend to turbojpeg for faster JPEG decoding', 'imread': 'read an image from a file path or S3 URL into a numpy array with cv2 backend', 'imfrombytes': 'decode image bytes from a buffer into a numpy array using the pillow backend', 'imwrite': 'write a numpy array image to a local file or S3 path with automatic encoding', 'pillow2array': 'convert a PIL Image object to a BGR numpy array with EXIF orientation handling'}
```

## File: facebookresearch_nerf-det/mmdet3d/mmcv/image/misc.py

Prompts

```
['build a python module to convert an image from one colorspace to another using imconvert', 'create a function that converts a BGR image to grayscale with optional dimension keeping', 'test the rgb2ycbcr function to convert a RGB image to YCbCr using ITU-R BT.601', 'refactor the ycbcr2rgb function to convert a YCbCr image back to RGB colorspace', 'review the convert_color_factory function that generates colorspace conversion functions dynamically', 'build a python module that resizes an image to a target size using cv2 or pillow backend', 'create a function that rotates an image by a given angle with optional auto-bound adjustment', 'test the imcrop function to extract and pad image patches from bounding boxes', 'refactor the impad function to support constant edge reflect and symmetric padding modes', 'summarize the bbox_scaling function that scales bounding boxes relative to their center point', 'switch the global image decoding backend to turbojpeg for faster JPEG decoding', 'read an image from a file path or S3 URL into a numpy array with cv2 backend', 'decode image bytes from a buffer into a numpy array using the pillow backend', 'write a numpy array image to a local file or S3 path with automatic encoding', 'convert a PIL Image object to a BGR numpy array with EXIF orientation handling', 'convert a PyTorch tensor of shape (N, C, H, W) into a list of denormalized NumPy image arrays', 'denormalize a batch of normalized image tensors using custom mean and std values back to uint8', 'convert a batch of RGB-normalized tensors back to BGR uint8 images for OpenCV display', 'convert a single-channel grayscale tensor batch into a list of uint8 grayscale image arrays', 'review the tensor2imgs function that converts normalized PyTorch image tensors to denormalized NumPy arrays', 'build a python module to normalize an image array with given mean and std values', 'build a python module to adjust the brightness of an image by a given factor', 'build a python module to adjust the contrast of an image by a given factor', 'build a python module to auto adjust image contrast by removing cutoff percent of histogram', 'build a python module to adjust the hue of an image by shifting the HSV hue channel']
```

Usage

```
{'convert_tensor_to_images': 'convert a PyTorch tensor of shape (N, C, H, W) into a list of denormalized NumPy image arrays', 'denormalize_batch_of_images': 'denormalize a batch of normalized image tensors using custom mean and std values back to uint8', 'convert_tensor_to_bgr_images': 'convert a batch of RGB-normalized tensors back to BGR uint8 images for OpenCV display', 'convert_grayscale_tensor_to_images': 'convert a single-channel grayscale tensor batch into a list of uint8 grayscale image arrays', 'review_tensor2imgs': 'review the tensor2imgs function that converts normalized PyTorch image tensors to denormalized NumPy arrays'}
```

## File: facebookresearch_nerf-det/mmdet3d/mmcv/image/photometric.py

Prompts

```
['build a python module to convert an image from one colorspace to another using imconvert', 'create a function that converts a BGR image to grayscale with optional dimension keeping', 'test the rgb2ycbcr function to convert a RGB image to YCbCr using ITU-R BT.601', 'refactor the ycbcr2rgb function to convert a YCbCr image back to RGB colorspace', 'review the convert_color_factory function that generates colorspace conversion functions dynamically', 'build a python module that resizes an image to a target size using cv2 or pillow backend', 'create a function that rotates an image by a given angle with optional auto-bound adjustment', 'test the imcrop function to extract and pad image patches from bounding boxes', 'refactor the impad function to support constant edge reflect and symmetric padding modes', 'summarize the bbox_scaling function that scales bounding boxes relative to their center point', 'switch the global image decoding backend to turbojpeg for faster JPEG decoding', 'read an image from a file path or S3 URL into a numpy array with cv2 backend', 'decode image bytes from a buffer into a numpy array using the pillow backend', 'write a numpy array image to a local file or S3 path with automatic encoding', 'convert a PIL Image object to a BGR numpy array with EXIF orientation handling', 'convert a PyTorch tensor of shape (N, C, H, W) into a list of denormalized NumPy image arrays', 'denormalize a batch of normalized image tensors using custom mean and std values back to uint8', 'convert a batch of RGB-normalized tensors back to BGR uint8 images for OpenCV display', 'convert a single-channel grayscale tensor batch into a list of uint8 grayscale image arrays', 'review the tensor2imgs function that converts normalized PyTorch image tensors to denormalized NumPy arrays', 'build a python module to normalize an image array with given mean and std values', 'build a python module to adjust the brightness of an image by a given factor', 'build a python module to adjust the contrast of an image by a given factor', 'build a python module to auto adjust image contrast by removing cutoff percent of histogram', 'build a python module to adjust the hue of an image by shifting the HSV hue channel']
```

Usage

```
{'build_imnormalize': 'build a python module to normalize an image array with given mean and std values', 'build_adjust_brightness': 'build a python module to adjust the brightness of an image by a given factor', 'build_adjust_contrast': 'build a python module to adjust the contrast of an image by a given factor', 'build_auto_contrast': 'build a python module to auto adjust image contrast by removing cutoff percent of histogram', 'build_adjust_hue': 'build a python module to adjust the hue of an image by shifting the HSV hue channel'}
```

