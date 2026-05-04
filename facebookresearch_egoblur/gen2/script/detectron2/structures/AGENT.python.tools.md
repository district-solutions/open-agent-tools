# Agent Python Tools

- repo: facebookresearch/egoblur
- repo_uri: https://github.com/facebookresearch/egoblur

## File: facebookresearch_egoblur/gen2/script/detectron2/structures/boxes.py

Prompts

```
['create a Boxes object from a Nx4 tensor where each row is xmin, ymin, xmax, ymax', 'convert bounding boxes from XYWH_ABS format to XYXY_ABS format using BoxMode.convert', 'compute the intersection over union between all pairs of two Boxes sets', 'clip bounding box coordinates in place to stay within the image height and width', 'filter Boxes to keep only those with width and height larger than a threshold', 'create an Instances object with image size and fields like gt_boxes and pred_classes', 'index an Instances object with a boolean mask to filter instances by score threshold', 'concatenate a list of Instances objects from the same image using the cat static method', 'move all tensor fields of an Instances object to a specified device using the to method', 'check if a field exists in an Instances object and retrieve its value using has and get']
```

Usage

```
{'create_boxes_tensor': 'create a Boxes object from a Nx4 tensor where each row is xmin, ymin, xmax, ymax', 'convert_box_mode': 'convert bounding boxes from XYWH_ABS format to XYXY_ABS format using BoxMode.convert', 'compute_pairwise_iou': 'compute the intersection over union between all pairs of two Boxes sets', 'clip_boxes_to_image': 'clip bounding box coordinates in place to stay within the image height and width', 'filter_nonempty_boxes': 'filter Boxes to keep only those with width and height larger than a threshold'}
```

## File: facebookresearch_egoblur/gen2/script/detectron2/structures/instances.py

Prompts

```
['create a Boxes object from a Nx4 tensor where each row is xmin, ymin, xmax, ymax', 'convert bounding boxes from XYWH_ABS format to XYXY_ABS format using BoxMode.convert', 'compute the intersection over union between all pairs of two Boxes sets', 'clip bounding box coordinates in place to stay within the image height and width', 'filter Boxes to keep only those with width and height larger than a threshold', 'create an Instances object with image size and fields like gt_boxes and pred_classes', 'index an Instances object with a boolean mask to filter instances by score threshold', 'concatenate a list of Instances objects from the same image using the cat static method', 'move all tensor fields of an Instances object to a specified device using the to method', 'check if a field exists in an Instances object and retrieve its value using has and get']
```

Usage

```
{'create_Instances_with_fields': 'create an Instances object with image size and fields like gt_boxes and pred_classes', 'index_Instances_by_mask': 'index an Instances object with a boolean mask to filter instances by score threshold', 'concatenate_Instances_lists': 'concatenate a list of Instances objects from the same image using the cat static method', 'move_Instances_to_device': 'move all tensor fields of an Instances object to a specified device using the to method', 'check_and_get_Instances_field': 'check if a field exists in an Instances object and retrieve its value using has and get'}
```

