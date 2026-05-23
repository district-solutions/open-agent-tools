# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pose/mmpose/datasets/datasets/face/aflw_dataset.py

Prompts

```
['build a python module to create an AFLWDataset instance for face keypoint localization with annotation file', 'create a function that parses raw AFLW face annotation data and returns structured instance information', 'test the AFLWDataset class by instantiating with annotation file and verifying parse_data_info output', 'review the parse_data_info method to understand how it extracts keypoints and bounding boxes from AFLW annotations', 'summarize the AFLWDataset class which extends BaseCocoStyleDataset for 19-point facial landmark localization', 'parse raw CocoWholeBody face annotation data into structured instance info with keypoints and bounding box', 'build a CocoWholeBodyFaceDataset instance for face keypoint localization using COCO style annotations', 'register the CocoWholeBodyFaceDataset class in the mmpose DATASETS registry for face pose estimation', 'filter invalid face instances where face_valid is false or all keypoints are zero', 'extract face keypoints and visibility from raw annotations into numpy arrays with shape 1 K 2', 'build a Face300WDataset instance to load 300W face keypoint annotations for training', 'test the Face300WDataset class by instantiating it with a 300W annotation file', 'summarize the Face300WDataset class for 300W face keypoint localization dataset loading', 'build a WFLWDataset instance for face keypoint localization with 98 point annotations', 'test the WFLWDataset class by instantiating with an annotation file and data prefix', 'summarize the WFLWDataset class that extends BaseCocoStyleDataset for face alignment tasks']
```

Usage

```
{'build_aflw_dataset': 'build a python module to create an AFLWDataset instance for face keypoint localization with annotation file', 'create_parse_data_info': 'create a function that parses raw AFLW face annotation data and returns structured instance information', 'test_AFLWDataset': 'test the AFLWDataset class by instantiating with annotation file and verifying parse_data_info output', 'review_parse_data_info': 'review the parse_data_info method to understand how it extracts keypoints and bounding boxes from AFLW annotations', 'summarize_AFLWDataset': 'summarize the AFLWDataset class which extends BaseCocoStyleDataset for 19-point facial landmark localization'}
```

## File: facebookresearch_sapiens/pose/mmpose/datasets/datasets/face/coco_wholebody_face_dataset.py

Prompts

```
['build a python module to create an AFLWDataset instance for face keypoint localization with annotation file', 'create a function that parses raw AFLW face annotation data and returns structured instance information', 'test the AFLWDataset class by instantiating with annotation file and verifying parse_data_info output', 'review the parse_data_info method to understand how it extracts keypoints and bounding boxes from AFLW annotations', 'summarize the AFLWDataset class which extends BaseCocoStyleDataset for 19-point facial landmark localization', 'parse raw CocoWholeBody face annotation data into structured instance info with keypoints and bounding box', 'build a CocoWholeBodyFaceDataset instance for face keypoint localization using COCO style annotations', 'register the CocoWholeBodyFaceDataset class in the mmpose DATASETS registry for face pose estimation', 'filter invalid face instances where face_valid is false or all keypoints are zero', 'extract face keypoints and visibility from raw annotations into numpy arrays with shape 1 K 2', 'build a Face300WDataset instance to load 300W face keypoint annotations for training', 'test the Face300WDataset class by instantiating it with a 300W annotation file', 'summarize the Face300WDataset class for 300W face keypoint localization dataset loading', 'build a WFLWDataset instance for face keypoint localization with 98 point annotations', 'test the WFLWDataset class by instantiating with an annotation file and data prefix', 'summarize the WFLWDataset class that extends BaseCocoStyleDataset for face alignment tasks']
```

Usage

```
{'parse_face_annotation': 'parse raw CocoWholeBody face annotation data into structured instance info with keypoints and bounding box', 'build_face_dataset': 'build a CocoWholeBodyFaceDataset instance for face keypoint localization using COCO style annotations', 'register_face_dataset_module': 'register the CocoWholeBodyFaceDataset class in the mmpose DATASETS registry for face pose estimation', 'filter_invalid_face_instances': 'filter invalid face instances where face_valid is false or all keypoints are zero', 'extract_face_keypoints': 'extract face keypoints and visibility from raw annotations into numpy arrays with shape 1 K 2'}
```

## File: facebookresearch_sapiens/pose/mmpose/datasets/datasets/face/face_300w_dataset.py

Prompts

```
['build a python module to create an AFLWDataset instance for face keypoint localization with annotation file', 'create a function that parses raw AFLW face annotation data and returns structured instance information', 'test the AFLWDataset class by instantiating with annotation file and verifying parse_data_info output', 'review the parse_data_info method to understand how it extracts keypoints and bounding boxes from AFLW annotations', 'summarize the AFLWDataset class which extends BaseCocoStyleDataset for 19-point facial landmark localization', 'parse raw CocoWholeBody face annotation data into structured instance info with keypoints and bounding box', 'build a CocoWholeBodyFaceDataset instance for face keypoint localization using COCO style annotations', 'register the CocoWholeBodyFaceDataset class in the mmpose DATASETS registry for face pose estimation', 'filter invalid face instances where face_valid is false or all keypoints are zero', 'extract face keypoints and visibility from raw annotations into numpy arrays with shape 1 K 2', 'build a Face300WDataset instance to load 300W face keypoint annotations for training', 'test the Face300WDataset class by instantiating it with a 300W annotation file', 'summarize the Face300WDataset class for 300W face keypoint localization dataset loading', 'build a WFLWDataset instance for face keypoint localization with 98 point annotations', 'test the WFLWDataset class by instantiating with an annotation file and data prefix', 'summarize the WFLWDataset class that extends BaseCocoStyleDataset for face alignment tasks']
```

Usage

```
{'build_Face300WDataset': 'build a Face300WDataset instance to load 300W face keypoint annotations for training', 'create_parse_data_info': 'create a parse_data_info call to convert raw 300W annotations into structured data', 'test_Face300WDataset': 'test the Face300WDataset class by instantiating it with a 300W annotation file', 'review_parse_data_info': 'review the parse_data_info method that parses 68-point face landmarks and bbox data', 'summarize_Face300WDataset': 'summarize the Face300WDataset class for 300W face keypoint localization dataset loading'}
```

## File: facebookresearch_sapiens/pose/mmpose/datasets/datasets/face/wflw_dataset.py

Prompts

```
['build a python module to create an AFLWDataset instance for face keypoint localization with annotation file', 'create a function that parses raw AFLW face annotation data and returns structured instance information', 'test the AFLWDataset class by instantiating with annotation file and verifying parse_data_info output', 'review the parse_data_info method to understand how it extracts keypoints and bounding boxes from AFLW annotations', 'summarize the AFLWDataset class which extends BaseCocoStyleDataset for 19-point facial landmark localization', 'parse raw CocoWholeBody face annotation data into structured instance info with keypoints and bounding box', 'build a CocoWholeBodyFaceDataset instance for face keypoint localization using COCO style annotations', 'register the CocoWholeBodyFaceDataset class in the mmpose DATASETS registry for face pose estimation', 'filter invalid face instances where face_valid is false or all keypoints are zero', 'extract face keypoints and visibility from raw annotations into numpy arrays with shape 1 K 2', 'build a Face300WDataset instance to load 300W face keypoint annotations for training', 'test the Face300WDataset class by instantiating it with a 300W annotation file', 'summarize the Face300WDataset class for 300W face keypoint localization dataset loading', 'build a WFLWDataset instance for face keypoint localization with 98 point annotations', 'test the WFLWDataset class by instantiating with an annotation file and data prefix', 'summarize the WFLWDataset class that extends BaseCocoStyleDataset for face alignment tasks']
```

Usage

```
{'build_wflw_dataset': 'build a WFLWDataset instance for face keypoint localization with 98 point annotations', 'create_parse_data_info': 'create a function that parses raw WFLW face annotation into keypoints and bounding box data', 'test_WFLWDataset': 'test the WFLWDataset class by instantiating with an annotation file and data prefix', 'review_parse_data_info': 'review the parse_data_info method that converts WFLW center-scale bbox to xyxy format', 'summarize_WFLWDataset': 'summarize the WFLWDataset class that extends BaseCocoStyleDataset for face alignment tasks'}
```

