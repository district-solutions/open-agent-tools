# Agent Python Tools

- repo: facebookresearch/jepa
- repo_uri: https://github.com/facebookresearch/jepa

## File: facebookresearch_jepa/src/datasets/utils/video/functional.py

Prompts

```
['crop a list of numpy arrays or PIL images to a specified rectangular region', 'resize a list of numpy arrays or PIL images to a target size with bilinear interpolation', 'compute the new height and width for resizing an image while preserving aspect ratio', 'normalize a 4D torch tensor video clip using mean and standard deviation values', 'check if a given object is a 4D torch tensor representing a video clip', "create a RandAugment transform from a config string like 'rand-m9-n3-mstd0.5' using rand_augment_transform", 'build an AugmentOp instance to apply a single named augmentation like Rotate or ShearX to a PIL image', 'create a list of AugmentOp instances with a given magnitude using rand_augment_ops', 'apply a RandAugment transform to a PIL image by calling it with the image as input', 'review the rotate function that handles PIL version compatibility for rotating images by degrees', 'create a random augmentation transform for video data using randaugment parameters and interpolation method', 'randomly crop and resize video frames to a target height and width with configurable scale and ratio', 'crop video frames with linearly interpolated shifting crop boxes across frames for temporal augmentation', 'perform Inception-style random sized cropping on a single image with configurable scale and aspect ratio jitter', 'apply random brightness, contrast, and saturation jitter to video frames with configurable jitter ratios', 'convert a numpy image array from HWC format to CHW format using convert_img', 'create a ClipToTensor callable to convert a list of image frames to a normalized tensor', 'create a ClipToTensor_K callable to convert image frames to a tensor normalized to -1 to 1', 'convert a numpy array to a PyTorch tensor using the ToTensor callable class', 'summarize the video volume transform utilities for image clip to tensor conversion']
```

Usage

```
{'crop_clip': 'crop a list of numpy arrays or PIL images to a specified rectangular region', 'resize_clip': 'resize a list of numpy arrays or PIL images to a target size with bilinear interpolation', 'get_resize_sizes': 'compute the new height and width for resizing an image while preserving aspect ratio', 'normalize': 'normalize a 4D torch tensor video clip using mean and standard deviation values', 'is_tensor_clip': 'check if a given object is a 4D torch tensor representing a video clip'}
```

## File: facebookresearch_jepa/src/datasets/utils/video/randaugment.py

Prompts

```
['crop a list of numpy arrays or PIL images to a specified rectangular region', 'resize a list of numpy arrays or PIL images to a target size with bilinear interpolation', 'compute the new height and width for resizing an image while preserving aspect ratio', 'normalize a 4D torch tensor video clip using mean and standard deviation values', 'check if a given object is a 4D torch tensor representing a video clip', "create a RandAugment transform from a config string like 'rand-m9-n3-mstd0.5' using rand_augment_transform", 'build an AugmentOp instance to apply a single named augmentation like Rotate or ShearX to a PIL image', 'create a list of AugmentOp instances with a given magnitude using rand_augment_ops', 'apply a RandAugment transform to a PIL image by calling it with the image as input', 'review the rotate function that handles PIL version compatibility for rotating images by degrees', 'create a random augmentation transform for video data using randaugment parameters and interpolation method', 'randomly crop and resize video frames to a target height and width with configurable scale and ratio', 'crop video frames with linearly interpolated shifting crop boxes across frames for temporal augmentation', 'perform Inception-style random sized cropping on a single image with configurable scale and aspect ratio jitter', 'apply random brightness, contrast, and saturation jitter to video frames with configurable jitter ratios', 'convert a numpy image array from HWC format to CHW format using convert_img', 'create a ClipToTensor callable to convert a list of image frames to a normalized tensor', 'create a ClipToTensor_K callable to convert image frames to a tensor normalized to -1 to 1', 'convert a numpy array to a PyTorch tensor using the ToTensor callable class', 'summarize the video volume transform utilities for image clip to tensor conversion']
```

Usage

```
{'create_randaugment_transform': "create a RandAugment transform from a config string like 'rand-m9-n3-mstd0.5' using rand_augment_transform", 'build_augmentop_for_image': 'build an AugmentOp instance to apply a single named augmentation like Rotate or ShearX to a PIL image', 'create_rand_augment_ops_list': 'create a list of AugmentOp instances with a given magnitude using rand_augment_ops', 'apply_randaugment_to_image': 'apply a RandAugment transform to a PIL image by calling it with the image as input', 'review_rotate_function': 'review the rotate function that handles PIL version compatibility for rotating images by degrees'}
```

## File: facebookresearch_jepa/src/datasets/utils/video/transforms.py

Prompts

```
['crop a list of numpy arrays or PIL images to a specified rectangular region', 'resize a list of numpy arrays or PIL images to a target size with bilinear interpolation', 'compute the new height and width for resizing an image while preserving aspect ratio', 'normalize a 4D torch tensor video clip using mean and standard deviation values', 'check if a given object is a 4D torch tensor representing a video clip', "create a RandAugment transform from a config string like 'rand-m9-n3-mstd0.5' using rand_augment_transform", 'build an AugmentOp instance to apply a single named augmentation like Rotate or ShearX to a PIL image', 'create a list of AugmentOp instances with a given magnitude using rand_augment_ops', 'apply a RandAugment transform to a PIL image by calling it with the image as input', 'review the rotate function that handles PIL version compatibility for rotating images by degrees', 'create a random augmentation transform for video data using randaugment parameters and interpolation method', 'randomly crop and resize video frames to a target height and width with configurable scale and ratio', 'crop video frames with linearly interpolated shifting crop boxes across frames for temporal augmentation', 'perform Inception-style random sized cropping on a single image with configurable scale and aspect ratio jitter', 'apply random brightness, contrast, and saturation jitter to video frames with configurable jitter ratios', 'convert a numpy image array from HWC format to CHW format using convert_img', 'create a ClipToTensor callable to convert a list of image frames to a normalized tensor', 'create a ClipToTensor_K callable to convert image frames to a tensor normalized to -1 to 1', 'convert a numpy array to a PyTorch tensor using the ToTensor callable class', 'summarize the video volume transform utilities for image clip to tensor conversion']
```

Usage

```
{'create_random_augment': 'create a random augmentation transform for video data using randaugment parameters and interpolation method', 'random_resized_crop': 'randomly crop and resize video frames to a target height and width with configurable scale and ratio', 'random_resized_crop_with_shift': 'crop video frames with linearly interpolated shifting crop boxes across frames for temporal augmentation', 'random_sized_crop_img': 'perform Inception-style random sized cropping on a single image with configurable scale and aspect ratio jitter', 'color_jitter': 'apply random brightness, contrast, and saturation jitter to video frames with configurable jitter ratios'}
```

## File: facebookresearch_jepa/src/datasets/utils/video/volume_transforms.py

Prompts

```
['crop a list of numpy arrays or PIL images to a specified rectangular region', 'resize a list of numpy arrays or PIL images to a target size with bilinear interpolation', 'compute the new height and width for resizing an image while preserving aspect ratio', 'normalize a 4D torch tensor video clip using mean and standard deviation values', 'check if a given object is a 4D torch tensor representing a video clip', "create a RandAugment transform from a config string like 'rand-m9-n3-mstd0.5' using rand_augment_transform", 'build an AugmentOp instance to apply a single named augmentation like Rotate or ShearX to a PIL image', 'create a list of AugmentOp instances with a given magnitude using rand_augment_ops', 'apply a RandAugment transform to a PIL image by calling it with the image as input', 'review the rotate function that handles PIL version compatibility for rotating images by degrees', 'create a random augmentation transform for video data using randaugment parameters and interpolation method', 'randomly crop and resize video frames to a target height and width with configurable scale and ratio', 'crop video frames with linearly interpolated shifting crop boxes across frames for temporal augmentation', 'perform Inception-style random sized cropping on a single image with configurable scale and aspect ratio jitter', 'apply random brightness, contrast, and saturation jitter to video frames with configurable jitter ratios', 'convert a numpy image array from HWC format to CHW format using convert_img', 'create a ClipToTensor callable to convert a list of image frames to a normalized tensor', 'create a ClipToTensor_K callable to convert image frames to a tensor normalized to -1 to 1', 'convert a numpy array to a PyTorch tensor using the ToTensor callable class', 'summarize the video volume transform utilities for image clip to tensor conversion']
```

Usage

```
{'convert_image_array': 'convert a numpy image array from HWC format to CHW format using convert_img', 'create_clip_to_tensor': 'create a ClipToTensor callable to convert a list of image frames to a normalized tensor', 'create_clip_to_tensor_k': 'create a ClipToTensor_K callable to convert image frames to a tensor normalized to -1 to 1', 'convert_numpy_to_tensor': 'convert a numpy array to a PyTorch tensor using the ToTensor callable class', 'summarize_volume_transforms': 'summarize the video volume transform utilities for image clip to tensor conversion'}
```

