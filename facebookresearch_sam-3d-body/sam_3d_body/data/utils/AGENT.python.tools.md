# Agent Python Tools

- repo: facebookresearch/sam-3d-body
- repo_uri: https://github.com/facebookresearch/sam-3d-body

## File: facebookresearch_sam-3d-body/sam_3d_body/data/utils/io.py

Prompts

```
['load an image from a file path using the PIL backend with automatic retry on failure', 'load an image from a file path using the cv2 backend and convert to RGB format', 'load an image from a data_info dict and populate img, img_shape, and ori_shape fields', 'resize an image to a target square size while maintaining aspect ratio and padding with white', 'expand brace-notation URL patterns into a list of resolved file paths with environment variables', 'prepare a batch of image data with bounding boxes and masks for SAM 3D Body model inference', 'use the NoCollate class to wrap data that should not be collated during batch processing', 'handle camera intrinsics by providing custom values or using default values based on image dimensions', 'process optional masks and mask scores for each bounding box in the batch preparation', 'transform individual data samples and collate them into a batch tensor for model input']
```

Usage

```
{'load_image_pil': 'load an image from a file path using the PIL backend with automatic retry on failure', 'load_image_cv2': 'load an image from a file path using the cv2 backend and convert to RGB format', 'load_image_from_file': 'load an image from a data_info dict and populate img, img_shape, and ori_shape fields', 'resize_image': 'resize an image to a target square size while maintaining aspect ratio and padding with white', 'expand_urls': 'expand brace-notation URL patterns into a list of resolved file paths with environment variables'}
```

## File: facebookresearch_sam-3d-body/sam_3d_body/data/utils/prepare_batch.py

Prompts

```
['load an image from a file path using the PIL backend with automatic retry on failure', 'load an image from a file path using the cv2 backend and convert to RGB format', 'load an image from a data_info dict and populate img, img_shape, and ori_shape fields', 'resize an image to a target square size while maintaining aspect ratio and padding with white', 'expand brace-notation URL patterns into a list of resolved file paths with environment variables', 'prepare a batch of image data with bounding boxes and masks for SAM 3D Body model inference', 'use the NoCollate class to wrap data that should not be collated during batch processing', 'handle camera intrinsics by providing custom values or using default values based on image dimensions', 'process optional masks and mask scores for each bounding box in the batch preparation', 'transform individual data samples and collate them into a batch tensor for model input']
```

Usage

```
{'prepare_batch_for_inference': 'prepare a batch of image data with bounding boxes and masks for SAM 3D Body model inference', 'use_nocollate_class': 'use the NoCollate class to wrap data that should not be collated during batch processing', 'handle_camera_intrinsics': 'handle camera intrinsics by providing custom values or using default values based on image dimensions', 'process_masks_and_scores': 'process optional masks and mask scores for each bounding box in the batch preparation', 'transform_and_collate_data': 'transform individual data samples and collate them into a batch tensor for model input'}
```

