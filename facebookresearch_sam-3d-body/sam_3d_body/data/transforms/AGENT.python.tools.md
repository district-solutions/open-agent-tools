# Agent Python Tools

- repo: facebookresearch/sam-3d-body
- repo_uri: https://github.com/facebookresearch/sam-3d-body

## File: facebookresearch_sam-3d-body/sam_3d_body/data/transforms/bbox_utils.py

Prompts

```
['convert bounding boxes from x1y1x2y2 format to xywh format using bbox_xyxy2xywh', 'convert bounding boxes from xywh format to x1y1x2y2 format using bbox_xywh2xyxy', 'transform bounding boxes from xyxy or xywh format into center and scale using bbox_xyxy2cs or bbox_xywh2cs', 'flip bounding boxes horizontally, vertically, or diagonally using flip_bbox with the image size', 'calculate an affine transformation matrix for warping a bbox region using get_warp_matrix with center, scale, and rotation', 'create a Compose pipeline to apply multiple image transforms sequentially on a data dict', 'build a VisionTransformWrapper to apply a torchvision transform to the img key in a results dict', 'build a TopdownAffine transform to crop and warp a bounding box region to a fixed input size using affine transform', 'create a NormalizeKeypoint transform to normalize 2D keypoints to the range [-0.5, 0.5] based on image size']
```

Usage

```
{'convert_bbox_xyxy_to_xywh': 'convert bounding boxes from x1y1x2y2 format to xywh format using bbox_xyxy2xywh', 'convert_bbox_xywh_to_xyxy': 'convert bounding boxes from xywh format to x1y1x2y2 format using bbox_xywh2xyxy', 'convert_bbox_to_center_scale': 'transform bounding boxes from xyxy or xywh format into center and scale using bbox_xyxy2cs or bbox_xywh2cs', 'flip_bbox_horizontal_vertical': 'flip bounding boxes horizontally, vertically, or diagonally using flip_bbox with the image size', 'compute_affine_warp_matrix': 'calculate an affine transformation matrix for warping a bbox region using get_warp_matrix with center, scale, and rotation'}
```

## File: facebookresearch_sam-3d-body/sam_3d_body/data/transforms/common.py

Prompts

```
['convert bounding boxes from x1y1x2y2 format to xywh format using bbox_xyxy2xywh', 'convert bounding boxes from xywh format to x1y1x2y2 format using bbox_xywh2xyxy', 'transform bounding boxes from xyxy or xywh format into center and scale using bbox_xyxy2cs or bbox_xywh2cs', 'flip bounding boxes horizontally, vertically, or diagonally using flip_bbox with the image size', 'calculate an affine transformation matrix for warping a bbox region using get_warp_matrix with center, scale, and rotation', 'create a Compose pipeline to apply multiple image transforms sequentially on a data dict', 'build a VisionTransformWrapper to apply a torchvision transform to the img key in a results dict', 'build a TopdownAffine transform to crop and warp a bounding box region to a fixed input size using affine transform', 'create a NormalizeKeypoint transform to normalize 2D keypoints to the range [-0.5, 0.5] based on image size']
```

Usage

```
{'compose_transforms': 'create a Compose pipeline to apply multiple image transforms sequentially on a data dict', 'wrap_torchvision_transform': 'build a VisionTransformWrapper to apply a torchvision transform to the img key in a results dict', 'convert_bbox_to_center_scale': 'create a GetBBoxCenterScale transform to convert xywh or xyxy bounding boxes to center and scale with padding', 'affine_crop_bbox': 'build a TopdownAffine transform to crop and warp a bounding box region to a fixed input size using affine transform', 'normalize_keypoints': 'create a NormalizeKeypoint transform to normalize 2D keypoints to the range [-0.5, 0.5] based on image size'}
```

