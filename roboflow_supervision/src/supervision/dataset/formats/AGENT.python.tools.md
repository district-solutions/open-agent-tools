# Agent Python Tools

- repo: roboflow/supervision
- repo_uri: https://github.com/roboflow/supervision

## File: roboflow_supervision/src/supervision/dataset/formats/coco.py

Prompts

```
['load COCO annotations from a JSON file and convert them to Detections objects with optional masks', 'save a DetectionDataset to COCO format JSON annotations file with configurable mask approximation', 'convert COCO annotation dictionaries for an image into Detections objects with optional masks', 'convert Detections objects into COCO-formatted annotation dictionaries with polygon or RLE segmentation', 'generate a mapping from sequential class indices to original COCO category ids from an annotations file', 'build a function that converts Detections objects to Pascal VOC XML format for export', 'create a function that loads PASCAL VOC XML annotations and returns image paths with Detections instances', 'create a function that builds a Pascal VOC XML object element from xyxy coordinates and an optional polygon', 'summarize the function that converts Pascal VOC XML objects to Detections instances', 'review the function that parses polygon coordinate elements from Pascal VOC XML into numpy arrays', 'load YOLO annotations from image and annotation directories with optional mask support and OBB format', 'save a DetectionDataset as YOLO-format annotation text files to a specified directory', 'convert YOLO annotation lines into Detections objects with optional masks and oriented bounding boxes', 'convert Detections objects into YOLO-format annotation strings with optional polygon approximation from masks', 'save a data.yaml file containing number of classes and class names for YOLO dataset configuration']
```

Usage

```
{'load_coco_annotations': 'load COCO annotations from a JSON file and convert them to Detections objects with optional masks', 'save_coco_annotations': 'save a DetectionDataset to COCO format JSON annotations file with configurable mask approximation', 'coco_annotations_to_detections': 'convert COCO annotation dictionaries for an image into Detections objects with optional masks', 'detections_to_coco_annotations': 'convert Detections objects into COCO-formatted annotation dictionaries with polygon or RLE segmentation', 'get_coco_class_index_mapping': 'generate a mapping from sequential class indices to original COCO category ids from an annotations file'}
```

## File: roboflow_supervision/src/supervision/dataset/formats/pascal_voc.py

Prompts

```
['load COCO annotations from a JSON file and convert them to Detections objects with optional masks', 'save a DetectionDataset to COCO format JSON annotations file with configurable mask approximation', 'convert COCO annotation dictionaries for an image into Detections objects with optional masks', 'convert Detections objects into COCO-formatted annotation dictionaries with polygon or RLE segmentation', 'generate a mapping from sequential class indices to original COCO category ids from an annotations file', 'build a function that converts Detections objects to Pascal VOC XML format for export', 'create a function that loads PASCAL VOC XML annotations and returns image paths with Detections instances', 'create a function that builds a Pascal VOC XML object element from xyxy coordinates and an optional polygon', 'summarize the function that converts Pascal VOC XML objects to Detections instances', 'review the function that parses polygon coordinate elements from Pascal VOC XML into numpy arrays', 'load YOLO annotations from image and annotation directories with optional mask support and OBB format', 'save a DetectionDataset as YOLO-format annotation text files to a specified directory', 'convert YOLO annotation lines into Detections objects with optional masks and oriented bounding boxes', 'convert Detections objects into YOLO-format annotation strings with optional polygon approximation from masks', 'save a data.yaml file containing number of classes and class names for YOLO dataset configuration']
```

Usage

```
{'build_detections_to_pascal_voc': 'build a function that converts Detections objects to Pascal VOC XML format for export', 'create_load_pascal_voc_annotations': 'create a function that loads PASCAL VOC XML annotations and returns image paths with Detections instances', 'create_object_to_pascal_voc': 'create a function that builds a Pascal VOC XML object element from xyxy coordinates and an optional polygon', 'summarize_detections_from_xml_obj': 'summarize the function that converts Pascal VOC XML objects to Detections instances', 'review_parse_polygon_points': 'review the function that parses polygon coordinate elements from Pascal VOC XML into numpy arrays'}
```

## File: roboflow_supervision/src/supervision/dataset/formats/yolo.py

Prompts

```
['load COCO annotations from a JSON file and convert them to Detections objects with optional masks', 'save a DetectionDataset to COCO format JSON annotations file with configurable mask approximation', 'convert COCO annotation dictionaries for an image into Detections objects with optional masks', 'convert Detections objects into COCO-formatted annotation dictionaries with polygon or RLE segmentation', 'generate a mapping from sequential class indices to original COCO category ids from an annotations file', 'build a function that converts Detections objects to Pascal VOC XML format for export', 'create a function that loads PASCAL VOC XML annotations and returns image paths with Detections instances', 'create a function that builds a Pascal VOC XML object element from xyxy coordinates and an optional polygon', 'summarize the function that converts Pascal VOC XML objects to Detections instances', 'review the function that parses polygon coordinate elements from Pascal VOC XML into numpy arrays', 'load YOLO annotations from image and annotation directories with optional mask support and OBB format', 'save a DetectionDataset as YOLO-format annotation text files to a specified directory', 'convert YOLO annotation lines into Detections objects with optional masks and oriented bounding boxes', 'convert Detections objects into YOLO-format annotation strings with optional polygon approximation from masks', 'save a data.yaml file containing number of classes and class names for YOLO dataset configuration']
```

Usage

```
{'load_yolo_annotations': 'load YOLO annotations from image and annotation directories with optional mask support and OBB format', 'save_yolo_annotations': 'save a DetectionDataset as YOLO-format annotation text files to a specified directory', 'yolo_annotations_to_detections': 'convert YOLO annotation lines into Detections objects with optional masks and oriented bounding boxes', 'detections_to_yolo_annotations': 'convert Detections objects into YOLO-format annotation strings with optional polygon approximation from masks', 'save_data_yaml': 'save a data.yaml file containing number of classes and class names for YOLO dataset configuration'}
```

