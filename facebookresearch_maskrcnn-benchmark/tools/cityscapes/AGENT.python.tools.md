# Agent Python Tools

- repo: facebookresearch/maskrcnn-benchmark
- repo_uri: https://github.com/facebookresearch/maskrcnn-benchmark

## File: facebookresearch_maskrcnn-benchmark/tools/cityscapes/convert_cityscapes_to_coco.py

Prompts

```
['run the cityscapes to coco conversion tool with --dataset cityscapes_instance_only --datadir PATH --outdir PATH', 'run the cocostuff to coco conversion tool with --dataset cocostuff --datadir PATH --outdir PATH', 'convert a polygon contour into a tight xyxy bounding box', 'convert an xyxy bounding box into xywh format for COCO annotations', 'extract the label ID from a Cityscapes instance ID by dividing by 1000', 'run the instances2dict_with_polygons function to convert Cityscapes PNG instance images to a dictionary with polygon contours', 'build a Python module to parse Cityscapes instance PNG files and extract labeled object instances with polygon contours', 'test the instances2dict_with_polygons function with a list of Cityscapes instance PNG image files', 'refactor the instances2dict_with_polygons function to support additional contour approximation methods or output formats', 'review the instances2dict_with_polygons function and its use of cv2_util.findContours for polygon extraction from instance masks']
```

Usage

```
{'convert_cityscapes_to_coco': 'run the cityscapes to coco conversion tool with --dataset cityscapes_instance_only --datadir PATH --outdir PATH', 'convert_cocostuff_to_coco': 'run the cocostuff to coco conversion tool with --dataset cocostuff --datadir PATH --outdir PATH', 'poly_to_box': 'convert a polygon contour into a tight xyxy bounding box', 'xyxy_to_xywh': 'convert an xyxy bounding box into xywh format for COCO annotations', 'getLabelID': 'extract the label ID from a Cityscapes instance ID by dividing by 1000'}
```

## File: facebookresearch_maskrcnn-benchmark/tools/cityscapes/instances2dict_with_polygons.py

Prompts

```
['run the cityscapes to coco conversion tool with --dataset cityscapes_instance_only --datadir PATH --outdir PATH', 'run the cocostuff to coco conversion tool with --dataset cocostuff --datadir PATH --outdir PATH', 'convert a polygon contour into a tight xyxy bounding box', 'convert an xyxy bounding box into xywh format for COCO annotations', 'extract the label ID from a Cityscapes instance ID by dividing by 1000', 'run the instances2dict_with_polygons function to convert Cityscapes PNG instance images to a dictionary with polygon contours', 'build a Python module to parse Cityscapes instance PNG files and extract labeled object instances with polygon contours', 'test the instances2dict_with_polygons function with a list of Cityscapes instance PNG image files', 'refactor the instances2dict_with_polygons function to support additional contour approximation methods or output formats', 'review the instances2dict_with_polygons function and its use of cv2_util.findContours for polygon extraction from instance masks']
```

Usage

```
{'run_instances2dict_with_polygons': 'run the instances2dict_with_polygons function to convert Cityscapes PNG instance images to a dictionary with polygon contours', 'build_cityscapes_instance_parser': 'build a Python module to parse Cityscapes instance PNG files and extract labeled object instances with polygon contours', 'test_instances2dict_with_polygons': 'test the instances2dict_with_polygons function with a list of Cityscapes instance PNG image files', 'refactor_instances2dict_with_polygons': 'refactor the instances2dict_with_polygons function to support additional contour approximation methods or output formats', 'review_instances2dict_with_polygons': 'review the instances2dict_with_polygons function and its use of cv2_util.findContours for polygon extraction from instance masks'}
```

