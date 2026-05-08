# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/devices/webcam/pose_vis/gesture/hand/annotation.py

Prompts

```
['create an Annotation instance to track hand vertices and gesture labels for pose data', 'save hand gesture vertex data to a JSON file using the NumpyJSONEncoder for serialization', 'load previously saved gesture vertex data from a JSON file into the Annotation object', 'match tracked hand vertices against known gestures and return the closest label by difference value', 'plot hand vertex data in a 3D matplotlib axes with configurable drawing order and scaling', 'run hand tracking and gesture recognition on webcam or video sources with live visualization', 'run gesture recognition and export the annotated stream as an MP4 video file', 'run gesture data collection mode to label and save new hand gesture patterns', 'review the GestureVis on_key method that handles keyboard input for mode switching and gesture collection', 'review the GestureVis get_bounds_data method that extracts hand bounding boxes and world landmark vectors']
```

Usage

```
{'create_annotation_gesture_tracker': 'create an Annotation instance to track hand vertices and gesture labels for pose data', 'save_gestures_to_json': 'save hand gesture vertex data to a JSON file using the NumpyJSONEncoder for serialization', 'load_gestures_from_json': 'load previously saved gesture vertex data from a JSON file into the Annotation object', 'guess_annotations_match_gestures': 'match tracked hand vertices against known gestures and return the closest label by difference value', 'plot_hand_3d_visualization': 'plot hand vertex data in a 3D matplotlib axes with configurable drawing order and scaling'}
```

## File: facebookresearch_labgraph/devices/webcam/pose_vis/gesture/hand/gesture_vis.py

Prompts

```
['create an Annotation instance to track hand vertices and gesture labels for pose data', 'save hand gesture vertex data to a JSON file using the NumpyJSONEncoder for serialization', 'load previously saved gesture vertex data from a JSON file into the Annotation object', 'match tracked hand vertices against known gestures and return the closest label by difference value', 'plot hand vertex data in a 3D matplotlib axes with configurable drawing order and scaling', 'run hand tracking and gesture recognition on webcam or video sources with live visualization', 'run gesture recognition and export the annotated stream as an MP4 video file', 'run gesture data collection mode to label and save new hand gesture patterns', 'review the GestureVis on_key method that handles keyboard input for mode switching and gesture collection', 'review the GestureVis get_bounds_data method that extracts hand bounding boxes and world landmark vectors']
```

Usage

```
{'run_gesture_vis': 'run hand tracking and gesture recognition on webcam or video sources with live visualization', 'run_gesture_vis_export': 'run gesture recognition and export the annotated stream as an MP4 video file', 'run_gesture_vis_collect': 'run gesture data collection mode to label and save new hand gesture patterns', 'review_GestureVis_on_key': 'review the GestureVis on_key method that handles keyboard input for mode switching and gesture collection', 'review_GestureVis_get_bounds_data': 'review the GestureVis get_bounds_data method that extracts hand bounding boxes and world landmark vectors'}
```

