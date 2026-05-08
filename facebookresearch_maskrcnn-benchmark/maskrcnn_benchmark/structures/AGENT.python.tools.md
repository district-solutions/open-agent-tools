# Agent Python Tools

- repo: facebookresearch/maskrcnn-benchmark
- repo_uri: https://github.com/facebookresearch/maskrcnn-benchmark

## File: facebookresearch_maskrcnn-benchmark/maskrcnn_benchmark/structures/bounding_box.py

Prompts

```
['create a BoxList from a list of bounding box coordinates and image size', 'resize a BoxList bounding box set to a new image width and height', 'transpose a BoxList by flipping it left-right or top-bottom', 'convert a BoxList between xyxy and xywh coordinate modes', 'crop a rectangular region from a BoxList bounding box set', 'build a python module that performs non-maximum suppression on a BoxList with a configurable threshold and max proposals', 'create a function that filters a BoxList to keep only boxes with both sides greater than or equal to a minimum size', 'compute the intersection over union between two BoxLists and return an N by M tensor of IoU values', 'concatenate a list of BoxList objects with the same image size and mode into a single BoxList', 'review the boxlist_ops module functions for NMS, small box removal, IoU computation, and box list concatenation', 'create an ImageList object from a batched tensor and a list of original image sizes', 'move an ImageList tensor to a specified device using the to method', 'convert a single 3D or 4D torch tensor into an ImageList with inferred image sizes', 'batch a list of variable-sized image tensors into a padded ImageList with zero padding', 'batch variable-sized images into an ImageList padded to a size divisible by a given stride', 'create a PersonKeypoints object with 17 COCO keypoints and image size', 'resize Keypoints coordinates proportionally to a new image width and height', 'transpose Keypoints using FLIP_LEFT_RIGHT to mirror x coordinates across image width', 'convert keypoints and ROIs into a heatmap tensor with a given heatmap size', 'create flip indices tensor from a list of keypoint names and a left-right flip map', 'create a BinaryMaskList from a torch tensor of shape num_instances by H by W', 'create a PolygonList from a list of polygon coordinate lists for each instance', 'convert a PolygonList of polygon instances into a BinaryMaskList using pycocotools mask utilities', 'crop a SegmentationMask to a bounding box region in xyxy format and return the cropped mask', 'transpose a BinaryMaskList by flipping masks left-right or top-bottom using the transpose method']
```

Usage

```
{'create_boxlist': 'create a BoxList from a list of bounding box coordinates and image size', 'resize_boxlist': 'resize a BoxList bounding box set to a new image width and height', 'transpose_boxlist': 'transpose a BoxList by flipping it left-right or top-bottom', 'convert_boxlist_mode': 'convert a BoxList between xyxy and xywh coordinate modes', 'crop_boxlist': 'crop a rectangular region from a BoxList bounding box set'}
```

## File: facebookresearch_maskrcnn-benchmark/maskrcnn_benchmark/structures/boxlist_ops.py

Prompts

```
['create a BoxList from a list of bounding box coordinates and image size', 'resize a BoxList bounding box set to a new image width and height', 'transpose a BoxList by flipping it left-right or top-bottom', 'convert a BoxList between xyxy and xywh coordinate modes', 'crop a rectangular region from a BoxList bounding box set', 'build a python module that performs non-maximum suppression on a BoxList with a configurable threshold and max proposals', 'create a function that filters a BoxList to keep only boxes with both sides greater than or equal to a minimum size', 'compute the intersection over union between two BoxLists and return an N by M tensor of IoU values', 'concatenate a list of BoxList objects with the same image size and mode into a single BoxList', 'review the boxlist_ops module functions for NMS, small box removal, IoU computation, and box list concatenation', 'create an ImageList object from a batched tensor and a list of original image sizes', 'move an ImageList tensor to a specified device using the to method', 'convert a single 3D or 4D torch tensor into an ImageList with inferred image sizes', 'batch a list of variable-sized image tensors into a padded ImageList with zero padding', 'batch variable-sized images into an ImageList padded to a size divisible by a given stride', 'create a PersonKeypoints object with 17 COCO keypoints and image size', 'resize Keypoints coordinates proportionally to a new image width and height', 'transpose Keypoints using FLIP_LEFT_RIGHT to mirror x coordinates across image width', 'convert keypoints and ROIs into a heatmap tensor with a given heatmap size', 'create flip indices tensor from a list of keypoint names and a left-right flip map', 'create a BinaryMaskList from a torch tensor of shape num_instances by H by W', 'create a PolygonList from a list of polygon coordinate lists for each instance', 'convert a PolygonList of polygon instances into a BinaryMaskList using pycocotools mask utilities', 'crop a SegmentationMask to a bounding box region in xyxy format and return the cropped mask', 'transpose a BinaryMaskList by flipping masks left-right or top-bottom using the transpose method']
```

Usage

```
{'build_boxlist_nms': 'build a python module that performs non-maximum suppression on a BoxList with a configurable threshold and max proposals', 'create_remove_small_boxes': 'create a function that filters a BoxList to keep only boxes with both sides greater than or equal to a minimum size', 'compute_boxlist_iou': 'compute the intersection over union between two BoxLists and return an N by M tensor of IoU values', 'concatenate_boxlists': 'concatenate a list of BoxList objects with the same image size and mode into a single BoxList', 'review_boxlist_ops': 'review the boxlist_ops module functions for NMS, small box removal, IoU computation, and box list concatenation'}
```

## File: facebookresearch_maskrcnn-benchmark/maskrcnn_benchmark/structures/image_list.py

Prompts

```
['create a BoxList from a list of bounding box coordinates and image size', 'resize a BoxList bounding box set to a new image width and height', 'transpose a BoxList by flipping it left-right or top-bottom', 'convert a BoxList between xyxy and xywh coordinate modes', 'crop a rectangular region from a BoxList bounding box set', 'build a python module that performs non-maximum suppression on a BoxList with a configurable threshold and max proposals', 'create a function that filters a BoxList to keep only boxes with both sides greater than or equal to a minimum size', 'compute the intersection over union between two BoxLists and return an N by M tensor of IoU values', 'concatenate a list of BoxList objects with the same image size and mode into a single BoxList', 'review the boxlist_ops module functions for NMS, small box removal, IoU computation, and box list concatenation', 'create an ImageList object from a batched tensor and a list of original image sizes', 'move an ImageList tensor to a specified device using the to method', 'convert a single 3D or 4D torch tensor into an ImageList with inferred image sizes', 'batch a list of variable-sized image tensors into a padded ImageList with zero padding', 'batch variable-sized images into an ImageList padded to a size divisible by a given stride', 'create a PersonKeypoints object with 17 COCO keypoints and image size', 'resize Keypoints coordinates proportionally to a new image width and height', 'transpose Keypoints using FLIP_LEFT_RIGHT to mirror x coordinates across image width', 'convert keypoints and ROIs into a heatmap tensor with a given heatmap size', 'create flip indices tensor from a list of keypoint names and a left-right flip map', 'create a BinaryMaskList from a torch tensor of shape num_instances by H by W', 'create a PolygonList from a list of polygon coordinate lists for each instance', 'convert a PolygonList of polygon instances into a BinaryMaskList using pycocotools mask utilities', 'crop a SegmentationMask to a bounding box region in xyxy format and return the cropped mask', 'transpose a BinaryMaskList by flipping masks left-right or top-bottom using the transpose method']
```

Usage

```
{'create_ImageList': 'create an ImageList object from a batched tensor and a list of original image sizes', 'move_ImageList_to_device': 'move an ImageList tensor to a specified device using the to method', 'convert_tensor_to_image_list': 'convert a single 3D or 4D torch tensor into an ImageList with inferred image sizes', 'batch_images_to_image_list': 'batch a list of variable-sized image tensors into a padded ImageList with zero padding', 'batch_images_with_stride': 'batch variable-sized images into an ImageList padded to a size divisible by a given stride'}
```

## File: facebookresearch_maskrcnn-benchmark/maskrcnn_benchmark/structures/keypoint.py

Prompts

```
['create a BoxList from a list of bounding box coordinates and image size', 'resize a BoxList bounding box set to a new image width and height', 'transpose a BoxList by flipping it left-right or top-bottom', 'convert a BoxList between xyxy and xywh coordinate modes', 'crop a rectangular region from a BoxList bounding box set', 'build a python module that performs non-maximum suppression on a BoxList with a configurable threshold and max proposals', 'create a function that filters a BoxList to keep only boxes with both sides greater than or equal to a minimum size', 'compute the intersection over union between two BoxLists and return an N by M tensor of IoU values', 'concatenate a list of BoxList objects with the same image size and mode into a single BoxList', 'review the boxlist_ops module functions for NMS, small box removal, IoU computation, and box list concatenation', 'create an ImageList object from a batched tensor and a list of original image sizes', 'move an ImageList tensor to a specified device using the to method', 'convert a single 3D or 4D torch tensor into an ImageList with inferred image sizes', 'batch a list of variable-sized image tensors into a padded ImageList with zero padding', 'batch variable-sized images into an ImageList padded to a size divisible by a given stride', 'create a PersonKeypoints object with 17 COCO keypoints and image size', 'resize Keypoints coordinates proportionally to a new image width and height', 'transpose Keypoints using FLIP_LEFT_RIGHT to mirror x coordinates across image width', 'convert keypoints and ROIs into a heatmap tensor with a given heatmap size', 'create flip indices tensor from a list of keypoint names and a left-right flip map', 'create a BinaryMaskList from a torch tensor of shape num_instances by H by W', 'create a PolygonList from a list of polygon coordinate lists for each instance', 'convert a PolygonList of polygon instances into a BinaryMaskList using pycocotools mask utilities', 'crop a SegmentationMask to a bounding box region in xyxy format and return the cropped mask', 'transpose a BinaryMaskList by flipping masks left-right or top-bottom using the transpose method']
```

Usage

```
{'create_person_keypoints': 'create a PersonKeypoints object with 17 COCO keypoints and image size', 'resize_keypoints': 'resize Keypoints coordinates proportionally to a new image width and height', 'transpose_keypoints_flip': 'transpose Keypoints using FLIP_LEFT_RIGHT to mirror x coordinates across image width', 'convert_keypoints_to_heatmap': 'convert keypoints and ROIs into a heatmap tensor with a given heatmap size', 'create_flip_indices': 'create flip indices tensor from a list of keypoint names and a left-right flip map'}
```

## File: facebookresearch_maskrcnn-benchmark/maskrcnn_benchmark/structures/segmentation_mask.py

Prompts

```
['create a BoxList from a list of bounding box coordinates and image size', 'resize a BoxList bounding box set to a new image width and height', 'transpose a BoxList by flipping it left-right or top-bottom', 'convert a BoxList between xyxy and xywh coordinate modes', 'crop a rectangular region from a BoxList bounding box set', 'build a python module that performs non-maximum suppression on a BoxList with a configurable threshold and max proposals', 'create a function that filters a BoxList to keep only boxes with both sides greater than or equal to a minimum size', 'compute the intersection over union between two BoxLists and return an N by M tensor of IoU values', 'concatenate a list of BoxList objects with the same image size and mode into a single BoxList', 'review the boxlist_ops module functions for NMS, small box removal, IoU computation, and box list concatenation', 'create an ImageList object from a batched tensor and a list of original image sizes', 'move an ImageList tensor to a specified device using the to method', 'convert a single 3D or 4D torch tensor into an ImageList with inferred image sizes', 'batch a list of variable-sized image tensors into a padded ImageList with zero padding', 'batch variable-sized images into an ImageList padded to a size divisible by a given stride', 'create a PersonKeypoints object with 17 COCO keypoints and image size', 'resize Keypoints coordinates proportionally to a new image width and height', 'transpose Keypoints using FLIP_LEFT_RIGHT to mirror x coordinates across image width', 'convert keypoints and ROIs into a heatmap tensor with a given heatmap size', 'create flip indices tensor from a list of keypoint names and a left-right flip map', 'create a BinaryMaskList from a torch tensor of shape num_instances by H by W', 'create a PolygonList from a list of polygon coordinate lists for each instance', 'convert a PolygonList of polygon instances into a BinaryMaskList using pycocotools mask utilities', 'crop a SegmentationMask to a bounding box region in xyxy format and return the cropped mask', 'transpose a BinaryMaskList by flipping masks left-right or top-bottom using the transpose method']
```

Usage

```
{'create_BinaryMaskList_from_tensors': 'create a BinaryMaskList from a torch tensor of shape num_instances by H by W', 'create_PolygonList_from_polygons': 'create a PolygonList from a list of polygon coordinate lists for each instance', 'convert_PolygonList_to_binarymask': 'convert a PolygonList of polygon instances into a BinaryMaskList using pycocotools mask utilities', 'crop_SegmentationMask_by_box': 'crop a SegmentationMask to a bounding box region in xyxy format and return the cropped mask', 'transpose_BinaryMaskList_flip': 'transpose a BinaryMaskList by flipping masks left-right or top-bottom using the transpose method'}
```

