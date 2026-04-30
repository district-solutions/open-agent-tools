# Agent Python Tools

- repo: roboflow/supervision
- repo_uri: https://github.com/roboflow/supervision

## File: roboflow_supervision/src/supervision/key_points/annotators.py

Prompts

```
['create a VertexAnnotator to draw colored circles at skeleton keypoint locations on an image', 'create an EdgeAnnotator to draw lines connecting skeleton keypoints into a skeleton structure on an image', 'create a VertexLabelAnnotator to draw labeled text boxes at each skeleton keypoint on an image', 'test VertexLabelAnnotator with smart_position to automatically spread out overlapping keypoint labels', 'review VertexLabelAnnotator per-keypoint color customization using a list of Color objects', 'create a KeyPoints object from Ultralytics YOLO pose inference results', 'create a KeyPoints object from MediaPipe pose or face landmark detection results', 'create a KeyPoints object from Roboflow Inference API pose prediction results', 'convert a KeyPoints object to Detections with bounding boxes computed from keypoint coordinates', 'filter and slice a KeyPoints object using integer, boolean mask, or 2D index indexing']
```

Usage

```
{'create_vertex_annotator': 'create a VertexAnnotator to draw colored circles at skeleton keypoint locations on an image', 'create_edge_annotator': 'create an EdgeAnnotator to draw lines connecting skeleton keypoints into a skeleton structure on an image', 'create_vertex_label_annotator': 'create a VertexLabelAnnotator to draw labeled text boxes at each skeleton keypoint on an image', 'test_vertex_label_smart_position': 'test VertexLabelAnnotator with smart_position to automatically spread out overlapping keypoint labels', 'review_vertex_label_colors': 'review VertexLabelAnnotator per-keypoint color customization using a list of Color objects'}
```

## File: roboflow_supervision/src/supervision/key_points/core.py

Prompts

```
['create a VertexAnnotator to draw colored circles at skeleton keypoint locations on an image', 'create an EdgeAnnotator to draw lines connecting skeleton keypoints into a skeleton structure on an image', 'create a VertexLabelAnnotator to draw labeled text boxes at each skeleton keypoint on an image', 'test VertexLabelAnnotator with smart_position to automatically spread out overlapping keypoint labels', 'review VertexLabelAnnotator per-keypoint color customization using a list of Color objects', 'create a KeyPoints object from Ultralytics YOLO pose inference results', 'create a KeyPoints object from MediaPipe pose or face landmark detection results', 'create a KeyPoints object from Roboflow Inference API pose prediction results', 'convert a KeyPoints object to Detections with bounding boxes computed from keypoint coordinates', 'filter and slice a KeyPoints object using integer, boolean mask, or 2D index indexing']
```

Usage

```
{'create_keypoints_from_ultralytics': 'create a KeyPoints object from Ultralytics YOLO pose inference results', 'create_keypoints_from_mediapipe': 'create a KeyPoints object from MediaPipe pose or face landmark detection results', 'create_keypoints_from_inference': 'create a KeyPoints object from Roboflow Inference API pose prediction results', 'convert_keypoints_to_detections': 'convert a KeyPoints object to Detections with bounding boxes computed from keypoint coordinates', 'filter_keypoints_by_index': 'filter and slice a KeyPoints object using integer, boolean mask, or 2D index indexing'}
```

