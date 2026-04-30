# Agent Python Tools

- repo: roboflow/supervision
- repo_uri: https://github.com/roboflow/supervision

## File: roboflow_supervision/examples/speed_estimation/inference_example.py

Prompts

```
['run vehicle speed estimation on a video using YOLOv8 detection, ByteTrack tracking, and perspective transform', 'create a ViewTransformer that converts real-world coordinates to image plane coordinates via perspective transform', 'test filtering detections within a polygon zone using PolygonZone.trigger on Detections objects', 'build a ByteTrack tracker to maintain object identities across video frames with configurable confidence threshold', 'summarize the annotation pipeline using BoxAnnotator, LabelAnnotator, and TraceAnnotator on video frames', 'build a PolygonZone filter to restrict detections to a defined region of interest in the video frame', 'create a ByteTrack tracker to assign persistent IDs to detected objects across video frames', 'annotate a video frame with bounding boxes, labels, and motion traces using BoxAnnotator, LabelAnnotator, and TraceAnnotator', "transform detection anchor coordinates from camera view to a bird's-eye view coordinate system", 'build a ByteTrack tracker with frame rate and confidence threshold for vehicle tracking across video frames']
```

Usage

```
{'run_speed_estimation': 'run vehicle speed estimation on a video using YOLOv8 detection, ByteTrack tracking, and perspective transform', 'create_view_transformer': 'create a ViewTransformer that converts real-world coordinates to image plane coordinates via perspective transform', 'test_polygon_zone_filtering': 'test filtering detections within a polygon zone using PolygonZone.trigger on Detections objects', 'build_byte_tracker': 'build a ByteTrack tracker to maintain object identities across video frames with configurable confidence threshold', 'summarize_annotation_pipeline': 'summarize the annotation pipeline using BoxAnnotator, LabelAnnotator, and TraceAnnotator on video frames'}
```

## File: roboflow_supervision/examples/speed_estimation/ultralytics_example.py

Prompts

```
['run vehicle speed estimation on a video using YOLOv8 detection, ByteTrack tracking, and perspective transform', 'create a ViewTransformer that converts real-world coordinates to image plane coordinates via perspective transform', 'test filtering detections within a polygon zone using PolygonZone.trigger on Detections objects', 'build a ByteTrack tracker to maintain object identities across video frames with configurable confidence threshold', 'summarize the annotation pipeline using BoxAnnotator, LabelAnnotator, and TraceAnnotator on video frames', 'build a PolygonZone filter to restrict detections to a defined region of interest in the video frame', 'create a ByteTrack tracker to assign persistent IDs to detected objects across video frames', 'annotate a video frame with bounding boxes, labels, and motion traces using BoxAnnotator, LabelAnnotator, and TraceAnnotator', "transform detection anchor coordinates from camera view to a bird's-eye view coordinate system", 'build a ByteTrack tracker with frame rate and confidence threshold for vehicle tracking across video frames']
```

Usage

```
{'run_speed_estimation': 'run vehicle speed estimation on a video using YOLO detection, ByteTrack tracking, and perspective-transformed coordinate analysis', 'create_view_transformer': 'create a ViewTransformer class that applies perspective transform to map source video coordinates to a target plane', 'build_polygon_zone_filter': 'build a PolygonZone filter to restrict detections to a defined region of interest in the video frame', 'create_byte_track_tracker': 'create a ByteTrack tracker to assign persistent IDs to detected objects across video frames', 'annotate_video_frame': 'annotate a video frame with bounding boxes, labels, and motion traces using BoxAnnotator, LabelAnnotator, and TraceAnnotator'}
```

## File: roboflow_supervision/examples/speed_estimation/yolo_nas_example.py

Prompts

```
['run vehicle speed estimation on a video using YOLOv8 detection, ByteTrack tracking, and perspective transform', 'create a ViewTransformer that converts real-world coordinates to image plane coordinates via perspective transform', 'test filtering detections within a polygon zone using PolygonZone.trigger on Detections objects', 'build a ByteTrack tracker to maintain object identities across video frames with configurable confidence threshold', 'summarize the annotation pipeline using BoxAnnotator, LabelAnnotator, and TraceAnnotator on video frames', 'build a PolygonZone filter to restrict detections to a defined region of interest in the video frame', 'create a ByteTrack tracker to assign persistent IDs to detected objects across video frames', 'annotate a video frame with bounding boxes, labels, and motion traces using BoxAnnotator, LabelAnnotator, and TraceAnnotator', "transform detection anchor coordinates from camera view to a bird's-eye view coordinate system", 'build a ByteTrack tracker with frame rate and confidence threshold for vehicle tracking across video frames']
```

Usage

```
{'run_speed_estimation': 'run vehicle speed estimation using YOLO-NAS and supervision with configurable confidence and IOU thresholds', 'create_view_transformer': 'create a ViewTransformer instance that applies perspective transform from source to target coordinate space', 'transform_coordinates': "transform detection anchor coordinates from camera view to a bird's-eye view coordinate system", 'build_byte_track_tracker': 'build a ByteTrack tracker with frame rate and confidence threshold for vehicle tracking across video frames', 'annotate_video_frame': 'annotate video frames with bounding boxes, labels, and motion traces for detected vehicles'}
```

