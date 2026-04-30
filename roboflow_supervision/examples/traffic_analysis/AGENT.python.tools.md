# Agent Python Tools

- repo: roboflow/supervision
- repo_uri: https://github.com/roboflow/supervision

## File: roboflow_supervision/examples/traffic_analysis/inference_example.py

Prompts

```
['run traffic flow analysis on a drone video using Roboflow inference and ByteTrack tracking', 'create polygon zones from lists of numpy arrays for vehicle in and out detection regions', 'build a video processor that runs object detection, tracking, and zone-based counting on video frames', 'manage tracker-to-zone mapping and count vehicles entering and exiting defined polygon zones', 'annotate video frames with bounding boxes, traces, labels, and zone crossing counts']
```

Usage

```
{'run_traffic_analysis': 'run traffic flow analysis on a drone video using Roboflow inference and ByteTrack tracking', 'create_polygon_zones': 'create polygon zones from lists of numpy arrays for vehicle in and out detection regions', 'build_video_processor': 'build a video processor that runs object detection, tracking, and zone-based counting on video frames', 'manage_detections': 'manage tracker-to-zone mapping and count vehicles entering and exiting defined polygon zones', 'annotate_video_frames': 'annotate video frames with bounding boxes, traces, labels, and zone crossing counts'}
```

## File: roboflow_supervision/examples/traffic_analysis/ultralytics_example.py

Prompts

```
['run traffic flow analysis on a drone video using Roboflow inference and ByteTrack tracking', 'create polygon zones from lists of numpy arrays for vehicle in and out detection regions', 'build a video processor that runs object detection, tracking, and zone-based counting on video frames', 'manage tracker-to-zone mapping and count vehicles entering and exiting defined polygon zones', 'annotate video frames with bounding boxes, traces, labels, and zone crossing counts']
```

Usage

```
{'run_traffic_analysis': 'run traffic flow analysis on a video using YOLO detection, ByteTrack tracking, and polygon zone counting', 'create_polygon_zones': 'create polygon zones from numpy arrays for detecting objects entering or exiting defined areas', 'build_video_processor': 'build a video processor that annotates frames with bounding boxes, traces, and labels while tracking objects across zones', 'manage_detections': 'manage detection counts by tracking objects entering and exiting polygon zones with unique tracker IDs', 'annotate_video_frames': 'annotate video frames with polygon zones, bounding boxes, traces, and zone crossing counts'}
```

