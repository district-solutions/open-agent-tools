# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/superpoint/convert_superpoint_to_pytorch.py

Prompts

```
['convert a SuperPoint PyTorch checkpoint from a URL to HuggingFace Transformers format', 'get a SuperPointConfig with encoder, decoder, and keypoint detection hyperparameters', 'create a mapping of original checkpoint keys to HuggingFace SuperPoint model keys', 'load sample COCO images from URLs for testing the converted model', 'test the SuperPoint checkpoint conversion with expected output shape and value assertions', 'test the is_grayscale function that checks if an image is grayscale', 'create a grayscale image from an RGB numpy array using the NTSC formula', 'build a SuperPointImageProcessorPil instance for resizing, rescaling, and preprocessing images for SuperPoint keypoint detection', 'test the _preprocess method that resizes, rescales, and optionally converts images to grayscale', 'run post_process_keypoint_detection to convert raw SuperPoint keypoints to absolute coordinates on the original image', 'preprocess a batch of images for SuperPoint keypoint detection with grayscale conversion and resizing', 'post-process SuperPoint model outputs to extract keypoints, scores, and descriptors in original image coordinates', 'convert RGB images to 3-channel grayscale format using the NTSC formula', 'check if a torch.Tensor image has identical RGB channels indicating grayscale', 'group images by their spatial dimensions for efficient batched processing in SuperPoint preprocessing', 'create a SuperPointForKeypointDetection model to extract keypoints and descriptors from images', 'run SuperPointForKeypointDetection forward pass on pixel values to get keypoints, scores, and descriptors', 'apply non-maximum suppression on score maps using simple_nms with a given radius', 'filter and keep top-k keypoints with highest scores using top_k_keypoints', 'remove keypoints too close to image borders using remove_keypoints_from_borders', 'sample and interpolate descriptors at keypoint locations using SuperPointDescriptorDecoder']
```

Usage

```
{'convert_superpoint_checkpoint': 'convert a SuperPoint PyTorch checkpoint from a URL to HuggingFace Transformers format', 'get_superpoint_config': 'get a SuperPointConfig with encoder, decoder, and keypoint detection hyperparameters', 'create_rename_keys': 'create a mapping of original checkpoint keys to HuggingFace SuperPoint model keys', 'prepare_imgs': 'load sample COCO images from URLs for testing the converted model', 'test_convert_superpoint_checkpoint': 'test the SuperPoint checkpoint conversion with expected output shape and value assertions'}
```

## File: huggingface_transformers/src/transformers/models/superpoint/image_processing_pil_superpoint.py

Prompts

```
['convert a SuperPoint PyTorch checkpoint from a URL to HuggingFace Transformers format', 'get a SuperPointConfig with encoder, decoder, and keypoint detection hyperparameters', 'create a mapping of original checkpoint keys to HuggingFace SuperPoint model keys', 'load sample COCO images from URLs for testing the converted model', 'test the SuperPoint checkpoint conversion with expected output shape and value assertions', 'test the is_grayscale function that checks if an image is grayscale', 'create a grayscale image from an RGB numpy array using the NTSC formula', 'build a SuperPointImageProcessorPil instance for resizing, rescaling, and preprocessing images for SuperPoint keypoint detection', 'test the _preprocess method that resizes, rescales, and optionally converts images to grayscale', 'run post_process_keypoint_detection to convert raw SuperPoint keypoints to absolute coordinates on the original image', 'preprocess a batch of images for SuperPoint keypoint detection with grayscale conversion and resizing', 'post-process SuperPoint model outputs to extract keypoints, scores, and descriptors in original image coordinates', 'convert RGB images to 3-channel grayscale format using the NTSC formula', 'check if a torch.Tensor image has identical RGB channels indicating grayscale', 'group images by their spatial dimensions for efficient batched processing in SuperPoint preprocessing', 'create a SuperPointForKeypointDetection model to extract keypoints and descriptors from images', 'run SuperPointForKeypointDetection forward pass on pixel values to get keypoints, scores, and descriptors', 'apply non-maximum suppression on score maps using simple_nms with a given radius', 'filter and keep top-k keypoints with highest scores using top_k_keypoints', 'remove keypoints too close to image borders using remove_keypoints_from_borders', 'sample and interpolate descriptors at keypoint locations using SuperPointDescriptorDecoder']
```

Usage

```
{'test_is_grayscale': 'test the is_grayscale function that checks if an image is grayscale', 'create_convert_to_grayscale': 'create a grayscale image from an RGB numpy array using the NTSC formula', 'build_superpoint_image_processor': 'build a SuperPointImageProcessorPil instance for resizing, rescaling, and preprocessing images for SuperPoint keypoint detection', 'test_preprocess_images': 'test the _preprocess method that resizes, rescales, and optionally converts images to grayscale', 'run_post_process_keypoint_detection': 'run post_process_keypoint_detection to convert raw SuperPoint keypoints to absolute coordinates on the original image'}
```

## File: huggingface_transformers/src/transformers/models/superpoint/image_processing_superpoint.py

Prompts

```
['convert a SuperPoint PyTorch checkpoint from a URL to HuggingFace Transformers format', 'get a SuperPointConfig with encoder, decoder, and keypoint detection hyperparameters', 'create a mapping of original checkpoint keys to HuggingFace SuperPoint model keys', 'load sample COCO images from URLs for testing the converted model', 'test the SuperPoint checkpoint conversion with expected output shape and value assertions', 'test the is_grayscale function that checks if an image is grayscale', 'create a grayscale image from an RGB numpy array using the NTSC formula', 'build a SuperPointImageProcessorPil instance for resizing, rescaling, and preprocessing images for SuperPoint keypoint detection', 'test the _preprocess method that resizes, rescales, and optionally converts images to grayscale', 'run post_process_keypoint_detection to convert raw SuperPoint keypoints to absolute coordinates on the original image', 'preprocess a batch of images for SuperPoint keypoint detection with grayscale conversion and resizing', 'post-process SuperPoint model outputs to extract keypoints, scores, and descriptors in original image coordinates', 'convert RGB images to 3-channel grayscale format using the NTSC formula', 'check if a torch.Tensor image has identical RGB channels indicating grayscale', 'group images by their spatial dimensions for efficient batched processing in SuperPoint preprocessing', 'create a SuperPointForKeypointDetection model to extract keypoints and descriptors from images', 'run SuperPointForKeypointDetection forward pass on pixel values to get keypoints, scores, and descriptors', 'apply non-maximum suppression on score maps using simple_nms with a given radius', 'filter and keep top-k keypoints with highest scores using top_k_keypoints', 'remove keypoints too close to image borders using remove_keypoints_from_borders', 'sample and interpolate descriptors at keypoint locations using SuperPointDescriptorDecoder']
```

Usage

```
{'preprocess_superpoint_images': 'preprocess a batch of images for SuperPoint keypoint detection with grayscale conversion and resizing', 'post_process_keypoint_detection': 'post-process SuperPoint model outputs to extract keypoints, scores, and descriptors in original image coordinates', 'convert_to_grayscale': 'convert RGB images to 3-channel grayscale format using the NTSC formula', 'is_grayscale': 'check if a torch.Tensor image has identical RGB channels indicating grayscale', 'group_images_by_shape': 'group images by their spatial dimensions for efficient batched processing in SuperPoint preprocessing'}
```

## File: huggingface_transformers/src/transformers/models/superpoint/modeling_superpoint.py

Prompts

```
['convert a SuperPoint PyTorch checkpoint from a URL to HuggingFace Transformers format', 'get a SuperPointConfig with encoder, decoder, and keypoint detection hyperparameters', 'create a mapping of original checkpoint keys to HuggingFace SuperPoint model keys', 'load sample COCO images from URLs for testing the converted model', 'test the SuperPoint checkpoint conversion with expected output shape and value assertions', 'test the is_grayscale function that checks if an image is grayscale', 'create a grayscale image from an RGB numpy array using the NTSC formula', 'build a SuperPointImageProcessorPil instance for resizing, rescaling, and preprocessing images for SuperPoint keypoint detection', 'test the _preprocess method that resizes, rescales, and optionally converts images to grayscale', 'run post_process_keypoint_detection to convert raw SuperPoint keypoints to absolute coordinates on the original image', 'preprocess a batch of images for SuperPoint keypoint detection with grayscale conversion and resizing', 'post-process SuperPoint model outputs to extract keypoints, scores, and descriptors in original image coordinates', 'convert RGB images to 3-channel grayscale format using the NTSC formula', 'check if a torch.Tensor image has identical RGB channels indicating grayscale', 'group images by their spatial dimensions for efficient batched processing in SuperPoint preprocessing', 'create a SuperPointForKeypointDetection model to extract keypoints and descriptors from images', 'run SuperPointForKeypointDetection forward pass on pixel values to get keypoints, scores, and descriptors', 'apply non-maximum suppression on score maps using simple_nms with a given radius', 'filter and keep top-k keypoints with highest scores using top_k_keypoints', 'remove keypoints too close to image borders using remove_keypoints_from_borders', 'sample and interpolate descriptors at keypoint locations using SuperPointDescriptorDecoder']
```

Usage

```
{'create_superpoint_keypoint_detector': 'create a SuperPointForKeypointDetection model to extract keypoints and descriptors from images', 'run_superpoint_forward_pass': 'run SuperPointForKeypointDetection forward pass on pixel values to get keypoints, scores, and descriptors', 'apply_non_maximum_suppression': 'apply non-maximum suppression on score maps using simple_nms with a given radius', 'filter_keypoints_by_score': 'filter and keep top-k keypoints with highest scores using top_k_keypoints', 'remove_border_keypoints': 'remove keypoints too close to image borders using remove_keypoints_from_borders', 'sample_descriptors_at_keypoints': 'sample and interpolate descriptors at keypoint locations using SuperPointDescriptorDecoder'}
```

