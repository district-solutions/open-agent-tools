# Agent Python Tools

- repo: roboflow/supervision
- repo_uri: https://github.com/roboflow/supervision

## File: roboflow_supervision/src/supervision/annotators/base.py

Prompts

```
['review the python class BaseAnnotator and its abstract annotate method for subclassing patterns', 'create a subclass of BaseAnnotator that implements the annotate method for drawing detection boxes on scenes', 'create a BoxAnnotator to draw bounding boxes on an image using provided object detections', 'create a LabelAnnotator to draw text labels with colored backgrounds on detected objects in an image', 'create a MaskAnnotator to draw semi-transparent colored mask overlays on detected objects', 'create a TraceAnnotator to draw smooth trace paths showing object movement across video frames', 'create a ComparisonAnnotator to highlight differences between two sets of object detections with colored overlays', 'test the resolve_color function to map detection indices to colors using index, class, or track strategies', 'build bounding boxes snapped into frame boundaries so they are fully contained within a given resolution', 'create a Trace object to record and retrieve detection anchor coordinates across frames by tracker id', 'test the wrap_text function to wrap text to a specified maximum line length respecting existing newlines', 'review the hex_to_rgba and rgba_to_hex functions for converting between hex color strings and RGBA tuples']
```

Usage

```
{'review_BaseAnnotator': 'review the python class BaseAnnotator and its abstract annotate method for subclassing patterns', 'create_BaseAnnotator_subclass': 'create a subclass of BaseAnnotator that implements the annotate method for drawing detection boxes on scenes'}
```

## File: roboflow_supervision/src/supervision/annotators/core.py

Prompts

```
['review the python class BaseAnnotator and its abstract annotate method for subclassing patterns', 'create a subclass of BaseAnnotator that implements the annotate method for drawing detection boxes on scenes', 'create a BoxAnnotator to draw bounding boxes on an image using provided object detections', 'create a LabelAnnotator to draw text labels with colored backgrounds on detected objects in an image', 'create a MaskAnnotator to draw semi-transparent colored mask overlays on detected objects', 'create a TraceAnnotator to draw smooth trace paths showing object movement across video frames', 'create a ComparisonAnnotator to highlight differences between two sets of object detections with colored overlays', 'test the resolve_color function to map detection indices to colors using index, class, or track strategies', 'build bounding boxes snapped into frame boundaries so they are fully contained within a given resolution', 'create a Trace object to record and retrieve detection anchor coordinates across frames by tracker id', 'test the wrap_text function to wrap text to a specified maximum line length respecting existing newlines', 'review the hex_to_rgba and rgba_to_hex functions for converting between hex color strings and RGBA tuples']
```

Usage

```
{'create_BoxAnnotator': 'create a BoxAnnotator to draw bounding boxes on an image using provided object detections', 'create_LabelAnnotator': 'create a LabelAnnotator to draw text labels with colored backgrounds on detected objects in an image', 'create_MaskAnnotator': 'create a MaskAnnotator to draw semi-transparent colored mask overlays on detected objects', 'create_TraceAnnotator': 'create a TraceAnnotator to draw smooth trace paths showing object movement across video frames', 'create_ComparisonAnnotator': 'create a ComparisonAnnotator to highlight differences between two sets of object detections with colored overlays'}
```

## File: roboflow_supervision/src/supervision/annotators/utils.py

Prompts

```
['review the python class BaseAnnotator and its abstract annotate method for subclassing patterns', 'create a subclass of BaseAnnotator that implements the annotate method for drawing detection boxes on scenes', 'create a BoxAnnotator to draw bounding boxes on an image using provided object detections', 'create a LabelAnnotator to draw text labels with colored backgrounds on detected objects in an image', 'create a MaskAnnotator to draw semi-transparent colored mask overlays on detected objects', 'create a TraceAnnotator to draw smooth trace paths showing object movement across video frames', 'create a ComparisonAnnotator to highlight differences between two sets of object detections with colored overlays', 'test the resolve_color function to map detection indices to colors using index, class, or track strategies', 'build bounding boxes snapped into frame boundaries so they are fully contained within a given resolution', 'create a Trace object to record and retrieve detection anchor coordinates across frames by tracker id', 'test the wrap_text function to wrap text to a specified maximum line length respecting existing newlines', 'review the hex_to_rgba and rgba_to_hex functions for converting between hex color strings and RGBA tuples']
```

Usage

```
{'test_resolve_color': 'test the resolve_color function to map detection indices to colors using index, class, or track strategies', 'build_snap_boxes': 'build bounding boxes snapped into frame boundaries so they are fully contained within a given resolution', 'create_trace_tracking': 'create a Trace object to record and retrieve detection anchor coordinates across frames by tracker id', 'test_wrap_text': 'test the wrap_text function to wrap text to a specified maximum line length respecting existing newlines', 'review_hex_rgba_conversion': 'review the hex_to_rgba and rgba_to_hex functions for converting between hex color strings and RGBA tuples'}
```

