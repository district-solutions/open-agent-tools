# Agent Python Tools

- repo: roboflow/supervision
- repo_uri: https://github.com/roboflow/supervision

## File: roboflow_supervision/src/supervision/detection/compact_mask.py

Prompts

```
['create a CompactMask from dense (N,H,W) boolean masks and xyxy bounding boxes for memory-efficient storage', 'build a run-length encoded int32 array from a 2D boolean mask in row-major order', 'test the CompactMask class by converting compact RLE storage back to a dense (N,H,W) boolean array', 'refactor a CompactMask to re-encode all masks using tight bounding boxes that minimize crop area', 'review the CompactMask.merge static method that concatenates multiple CompactMask objects into one', 'create a Detections object from Ultralytics YOLOv8 inference results with bounding boxes and masks', 'create a Detections object from Roboflow API inference results including bounding boxes and class IDs', 'merge a list of Detections objects into a single Detections object combining all bounding boxes', 'run non-maximum suppression on Detections with configurable IoU threshold and class-agnostic mode', 'create a Detections object from Vision Language Model results like PaliGemma or Gemini 2.5', 'create a LineZone to count objects crossing a predefined line between two Points', 'run LineZone.trigger to detect which detections crossed the line in the current frame', 'build a LineZoneAnnotator to draw the line and in/out counts on a video frame', 'build a LineZoneAnnotatorMulticlass to draw a table of per-class crossing counts for multiple line zones', 'test LineZone crossing detection with tracker_id-based object tracking across frames', 'parse bounding boxes from PaliGemma VLM output and scale to specified resolution with optional class filtering', 'parse Florence 2 multi-task VLM results including bounding boxes, labels, masks, and oriented bounding boxes', 'parse Google Gemini 2.5 VLM output extracting bounding boxes, class labels, confidence scores, and base64-encoded segmentation masks', 'parse DeepSeek-VL2 text output with ref and det tags to extract bounding boxes and class labels', 'validate VLM enum value, result type, and keyword arguments against required and allowed parameter lists']
```

Usage

```
{'create_compact_mask_from_dense': 'create a CompactMask from dense (N,H,W) boolean masks and xyxy bounding boxes for memory-efficient storage', 'build_compact_mask_rle_encode': 'build a run-length encoded int32 array from a 2D boolean mask in row-major order', 'test_compact_mask_to_dense': 'test the CompactMask class by converting compact RLE storage back to a dense (N,H,W) boolean array', 'refactor_compact_mask_repack': 'refactor a CompactMask to re-encode all masks using tight bounding boxes that minimize crop area', 'review_compact_mask_merge': 'review the CompactMask.merge static method that concatenates multiple CompactMask objects into one'}
```

## File: roboflow_supervision/src/supervision/detection/core.py

Prompts

```
['create a CompactMask from dense (N,H,W) boolean masks and xyxy bounding boxes for memory-efficient storage', 'build a run-length encoded int32 array from a 2D boolean mask in row-major order', 'test the CompactMask class by converting compact RLE storage back to a dense (N,H,W) boolean array', 'refactor a CompactMask to re-encode all masks using tight bounding boxes that minimize crop area', 'review the CompactMask.merge static method that concatenates multiple CompactMask objects into one', 'create a Detections object from Ultralytics YOLOv8 inference results with bounding boxes and masks', 'create a Detections object from Roboflow API inference results including bounding boxes and class IDs', 'merge a list of Detections objects into a single Detections object combining all bounding boxes', 'run non-maximum suppression on Detections with configurable IoU threshold and class-agnostic mode', 'create a Detections object from Vision Language Model results like PaliGemma or Gemini 2.5', 'create a LineZone to count objects crossing a predefined line between two Points', 'run LineZone.trigger to detect which detections crossed the line in the current frame', 'build a LineZoneAnnotator to draw the line and in/out counts on a video frame', 'build a LineZoneAnnotatorMulticlass to draw a table of per-class crossing counts for multiple line zones', 'test LineZone crossing detection with tracker_id-based object tracking across frames', 'parse bounding boxes from PaliGemma VLM output and scale to specified resolution with optional class filtering', 'parse Florence 2 multi-task VLM results including bounding boxes, labels, masks, and oriented bounding boxes', 'parse Google Gemini 2.5 VLM output extracting bounding boxes, class labels, confidence scores, and base64-encoded segmentation masks', 'parse DeepSeek-VL2 text output with ref and det tags to extract bounding boxes and class labels', 'validate VLM enum value, result type, and keyword arguments against required and allowed parameter lists']
```

Usage

```
{'create_detections_from_ultralytics': 'create a Detections object from Ultralytics YOLOv8 inference results with bounding boxes and masks', 'create_detections_from_inference': 'create a Detections object from Roboflow API inference results including bounding boxes and class IDs', 'merge_detections_objects': 'merge a list of Detections objects into a single Detections object combining all bounding boxes', 'run_nms_on_detections': 'run non-maximum suppression on Detections with configurable IoU threshold and class-agnostic mode', 'create_detections_from_vlm': 'create a Detections object from Vision Language Model results like PaliGemma or Gemini 2.5'}
```

## File: roboflow_supervision/src/supervision/detection/line_zone.py

Prompts

```
['create a CompactMask from dense (N,H,W) boolean masks and xyxy bounding boxes for memory-efficient storage', 'build a run-length encoded int32 array from a 2D boolean mask in row-major order', 'test the CompactMask class by converting compact RLE storage back to a dense (N,H,W) boolean array', 'refactor a CompactMask to re-encode all masks using tight bounding boxes that minimize crop area', 'review the CompactMask.merge static method that concatenates multiple CompactMask objects into one', 'create a Detections object from Ultralytics YOLOv8 inference results with bounding boxes and masks', 'create a Detections object from Roboflow API inference results including bounding boxes and class IDs', 'merge a list of Detections objects into a single Detections object combining all bounding boxes', 'run non-maximum suppression on Detections with configurable IoU threshold and class-agnostic mode', 'create a Detections object from Vision Language Model results like PaliGemma or Gemini 2.5', 'create a LineZone to count objects crossing a predefined line between two Points', 'run LineZone.trigger to detect which detections crossed the line in the current frame', 'build a LineZoneAnnotator to draw the line and in/out counts on a video frame', 'build a LineZoneAnnotatorMulticlass to draw a table of per-class crossing counts for multiple line zones', 'test LineZone crossing detection with tracker_id-based object tracking across frames', 'parse bounding boxes from PaliGemma VLM output and scale to specified resolution with optional class filtering', 'parse Florence 2 multi-task VLM results including bounding boxes, labels, masks, and oriented bounding boxes', 'parse Google Gemini 2.5 VLM output extracting bounding boxes, class labels, confidence scores, and base64-encoded segmentation masks', 'parse DeepSeek-VL2 text output with ref and det tags to extract bounding boxes and class labels', 'validate VLM enum value, result type, and keyword arguments against required and allowed parameter lists']
```

Usage

```
{'create_line_zone': 'create a LineZone to count objects crossing a predefined line between two Points', 'run_line_zone_trigger': 'run LineZone.trigger to detect which detections crossed the line in the current frame', 'build_line_zone_annotator': 'build a LineZoneAnnotator to draw the line and in/out counts on a video frame', 'build_line_zone_annotator_multiclass': 'build a LineZoneAnnotatorMulticlass to draw a table of per-class crossing counts for multiple line zones', 'test_line_zone_crossing': 'test LineZone crossing detection with tracker_id-based object tracking across frames'}
```

## File: roboflow_supervision/src/supervision/detection/vlm.py

Prompts

```
['create a CompactMask from dense (N,H,W) boolean masks and xyxy bounding boxes for memory-efficient storage', 'build a run-length encoded int32 array from a 2D boolean mask in row-major order', 'test the CompactMask class by converting compact RLE storage back to a dense (N,H,W) boolean array', 'refactor a CompactMask to re-encode all masks using tight bounding boxes that minimize crop area', 'review the CompactMask.merge static method that concatenates multiple CompactMask objects into one', 'create a Detections object from Ultralytics YOLOv8 inference results with bounding boxes and masks', 'create a Detections object from Roboflow API inference results including bounding boxes and class IDs', 'merge a list of Detections objects into a single Detections object combining all bounding boxes', 'run non-maximum suppression on Detections with configurable IoU threshold and class-agnostic mode', 'create a Detections object from Vision Language Model results like PaliGemma or Gemini 2.5', 'create a LineZone to count objects crossing a predefined line between two Points', 'run LineZone.trigger to detect which detections crossed the line in the current frame', 'build a LineZoneAnnotator to draw the line and in/out counts on a video frame', 'build a LineZoneAnnotatorMulticlass to draw a table of per-class crossing counts for multiple line zones', 'test LineZone crossing detection with tracker_id-based object tracking across frames', 'parse bounding boxes from PaliGemma VLM output and scale to specified resolution with optional class filtering', 'parse Florence 2 multi-task VLM results including bounding boxes, labels, masks, and oriented bounding boxes', 'parse Google Gemini 2.5 VLM output extracting bounding boxes, class labels, confidence scores, and base64-encoded segmentation masks', 'parse DeepSeek-VL2 text output with ref and det tags to extract bounding boxes and class labels', 'validate VLM enum value, result type, and keyword arguments against required and allowed parameter lists']
```

Usage

```
{'parse_paligemma_bounding_boxes': 'parse bounding boxes from PaliGemma VLM output and scale to specified resolution with optional class filtering', 'parse_florence_2_detection_results': 'parse Florence 2 multi-task VLM results including bounding boxes, labels, masks, and oriented bounding boxes', 'parse_gemini_2_5_bounding_boxes_with_masks': 'parse Google Gemini 2.5 VLM output extracting bounding boxes, class labels, confidence scores, and base64-encoded segmentation masks', 'parse_deepseek_vl_2_bounding_boxes': 'parse DeepSeek-VL2 text output with ref and det tags to extract bounding boxes and class labels', 'validate_vlm_parameters': 'validate VLM enum value, result type, and keyword arguments against required and allowed parameter lists'}
```

