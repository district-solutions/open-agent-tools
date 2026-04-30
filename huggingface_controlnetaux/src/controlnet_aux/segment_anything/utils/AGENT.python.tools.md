# Agent Python Tools

- repo: huggingface/controlnetaux
- repo_uri: https://github.com/huggingface/controlnet_aux

## File: huggingface_controlnetaux/src/controlnet_aux/segment_anything/utils/amg.py

Prompts

```
['build a MaskData object to store and filter batched mask data with tensors and numpy arrays', 'generate a list of crop boxes at multiple layers with configurable overlap ratio for image segmentation', 'calculate the stability score IoU between high and low thresholded binary masks for a batch', 'remove small disconnected regions or holes from a binary mask using connected components analysis', 'calculate bounding boxes in XYXY format around a batch of binary masks returning zero boxes for empty masks', 'build a SamOnnxModel wrapping a SAM model for ONNX export with configurable mask output', 'run resize_longest_image_size to scale an image tensor so its longest side matches a target size', 'test the _embed_points method to encode point coordinates and labels into sparse embeddings', 'review the mask_postprocessing method that upscales and crops masks back to original image size', 'summarize the select_masks method that picks the best mask from multiple candidates using IOU scores', 'resize a numpy image array to a target longest side length using ResizeLongestSide', 'resize 2D numpy coordinates to match the new image dimensions after resizing', 'resize bounding box coordinates to match the new image dimensions after resizing', 'resize batched torch tensor images using bilinear interpolation to a target longest side', 'compute the output height and width given an input size and target long side length']
```

Usage

```
{'build_MaskData': 'build a MaskData object to store and filter batched mask data with tensors and numpy arrays', 'generate_crop_boxes': 'generate a list of crop boxes at multiple layers with configurable overlap ratio for image segmentation', 'calculate_stability_score': 'calculate the stability score IoU between high and low thresholded binary masks for a batch', 'remove_small_regions': 'remove small disconnected regions or holes from a binary mask using connected components analysis', 'batched_mask_to_box': 'calculate bounding boxes in XYXY format around a batch of binary masks returning zero boxes for empty masks'}
```

## File: huggingface_controlnetaux/src/controlnet_aux/segment_anything/utils/onnx.py

Prompts

```
['build a MaskData object to store and filter batched mask data with tensors and numpy arrays', 'generate a list of crop boxes at multiple layers with configurable overlap ratio for image segmentation', 'calculate the stability score IoU between high and low thresholded binary masks for a batch', 'remove small disconnected regions or holes from a binary mask using connected components analysis', 'calculate bounding boxes in XYXY format around a batch of binary masks returning zero boxes for empty masks', 'build a SamOnnxModel wrapping a SAM model for ONNX export with configurable mask output', 'run resize_longest_image_size to scale an image tensor so its longest side matches a target size', 'test the _embed_points method to encode point coordinates and labels into sparse embeddings', 'review the mask_postprocessing method that upscales and crops masks back to original image size', 'summarize the select_masks method that picks the best mask from multiple candidates using IOU scores', 'resize a numpy image array to a target longest side length using ResizeLongestSide', 'resize 2D numpy coordinates to match the new image dimensions after resizing', 'resize bounding box coordinates to match the new image dimensions after resizing', 'resize batched torch tensor images using bilinear interpolation to a target longest side', 'compute the output height and width given an input size and target long side length']
```

Usage

```
{'build_sam_onnx_model': 'build a SamOnnxModel wrapping a SAM model for ONNX export with configurable mask output', 'run_resize_longest_image_size': 'run resize_longest_image_size to scale an image tensor so its longest side matches a target size', 'test_embed_points': 'test the _embed_points method to encode point coordinates and labels into sparse embeddings', 'review_mask_postprocessing': 'review the mask_postprocessing method that upscales and crops masks back to original image size', 'summarize_select_masks': 'summarize the select_masks method that picks the best mask from multiple candidates using IOU scores'}
```

## File: huggingface_controlnetaux/src/controlnet_aux/segment_anything/utils/transforms.py

Prompts

```
['build a MaskData object to store and filter batched mask data with tensors and numpy arrays', 'generate a list of crop boxes at multiple layers with configurable overlap ratio for image segmentation', 'calculate the stability score IoU between high and low thresholded binary masks for a batch', 'remove small disconnected regions or holes from a binary mask using connected components analysis', 'calculate bounding boxes in XYXY format around a batch of binary masks returning zero boxes for empty masks', 'build a SamOnnxModel wrapping a SAM model for ONNX export with configurable mask output', 'run resize_longest_image_size to scale an image tensor so its longest side matches a target size', 'test the _embed_points method to encode point coordinates and labels into sparse embeddings', 'review the mask_postprocessing method that upscales and crops masks back to original image size', 'summarize the select_masks method that picks the best mask from multiple candidates using IOU scores', 'resize a numpy image array to a target longest side length using ResizeLongestSide', 'resize 2D numpy coordinates to match the new image dimensions after resizing', 'resize bounding box coordinates to match the new image dimensions after resizing', 'resize batched torch tensor images using bilinear interpolation to a target longest side', 'compute the output height and width given an input size and target long side length']
```

Usage

```
{'apply_image_resize': 'resize a numpy image array to a target longest side length using ResizeLongestSide', 'apply_coords_resize': 'resize 2D numpy coordinates to match the new image dimensions after resizing', 'apply_boxes_resize': 'resize bounding box coordinates to match the new image dimensions after resizing', 'apply_image_torch_resize': 'resize batched torch tensor images using bilinear interpolation to a target longest side', 'get_preprocess_shape_compute': 'compute the output height and width given an input size and target long side length'}
```

