# Agent Python Tools

- repo: facebookresearch/spot-sim2real
- repo_uri: https://github.com/facebookresearch/spot-sim2real

## File: facebookresearch_spot-sim2real/perception_and_utils_root/perception_and_utils/perception/detector_wrappers/april_tag_detector.py

Prompts

```
['initialize an AprilTag detector with camera focal lengths and principal point for QR code pose estimation', 'process an image frame to detect AprilTag markers and estimate their pose relative to the camera', 'retrieve decorated visualization images and SE3 pose data from AprilTag detection results', 'create an AprilTagDetectorWrapper instance to detect QR codes and estimate marker pose from camera frames', 'review the AprilTagDetectorWrapper class that wraps AprilTagPoseEstimator for dock marker detection and pose estimation', 'enable the GenericDetector by calling enable_detector to set is_enabled to True', 'disable the GenericDetector by calling disable_detector to set is_enabled to False', 'process a DataFrame frame with a subclass of GenericDetector to get detections and metadata', 'create a subclass of GenericDetector that implements process_frame for custom detection logic', 'review the GenericDetector class and its abstract process_frame interface for detector implementations', 'initialize the HumanMotionDetector with a custom velocity threshold and time horizon for motion detection', 'generate a visualized image with activity state, velocity, and FPS labels overlaid on the frame', 'append a new state change to the human motion history only when the state differs from the last recorded state', 'retrieve the full list of timestamped human motion state changes recorded by the detector', 'initialize an OwlVit object detector with custom labels and confidence threshold for GPU inference', 'process an image frame to detect objects and score them using a custom heuristic function', 'process image frames offline using demo heuristics to filter detections and update labels dynamically', 'score image frames based on pixel occupancy and center proximity for EMRoF algorithm compatibility']
```

Usage

```
{'init_april_tag_detector': 'initialize an AprilTag detector with camera focal lengths and principal point for QR code pose estimation', 'process_frame_detect_april_tag': 'process an image frame to detect AprilTag markers and estimate their pose relative to the camera', 'get_outputs_april_tag': 'retrieve decorated visualization images and SE3 pose data from AprilTag detection results', 'create_april_tag_detector_wrapper': 'create an AprilTagDetectorWrapper instance to detect QR codes and estimate marker pose from camera frames', 'review_AprilTagDetectorWrapper': 'review the AprilTagDetectorWrapper class that wraps AprilTagPoseEstimator for dock marker detection and pose estimation'}
```

## File: facebookresearch_spot-sim2real/perception_and_utils_root/perception_and_utils/perception/detector_wrappers/generic_detector_interface.py

Prompts

```
['initialize an AprilTag detector with camera focal lengths and principal point for QR code pose estimation', 'process an image frame to detect AprilTag markers and estimate their pose relative to the camera', 'retrieve decorated visualization images and SE3 pose data from AprilTag detection results', 'create an AprilTagDetectorWrapper instance to detect QR codes and estimate marker pose from camera frames', 'review the AprilTagDetectorWrapper class that wraps AprilTagPoseEstimator for dock marker detection and pose estimation', 'enable the GenericDetector by calling enable_detector to set is_enabled to True', 'disable the GenericDetector by calling disable_detector to set is_enabled to False', 'process a DataFrame frame with a subclass of GenericDetector to get detections and metadata', 'create a subclass of GenericDetector that implements process_frame for custom detection logic', 'review the GenericDetector class and its abstract process_frame interface for detector implementations', 'initialize the HumanMotionDetector with a custom velocity threshold and time horizon for motion detection', 'generate a visualized image with activity state, velocity, and FPS labels overlaid on the frame', 'append a new state change to the human motion history only when the state differs from the last recorded state', 'retrieve the full list of timestamped human motion state changes recorded by the detector', 'initialize an OwlVit object detector with custom labels and confidence threshold for GPU inference', 'process an image frame to detect objects and score them using a custom heuristic function', 'process image frames offline using demo heuristics to filter detections and update labels dynamically', 'score image frames based on pixel occupancy and center proximity for EMRoF algorithm compatibility']
```

Usage

```
{'enable_detector': 'enable the GenericDetector by calling enable_detector to set is_enabled to True', 'disable_detector': 'disable the GenericDetector by calling disable_detector to set is_enabled to False', 'process_frame': 'process a DataFrame frame with a subclass of GenericDetector to get detections and metadata', 'create_subclass': 'create a subclass of GenericDetector that implements process_frame for custom detection logic', 'review_GenericDetector': 'review the GenericDetector class and its abstract process_frame interface for detector implementations'}
```

## File: facebookresearch_spot-sim2real/perception_and_utils_root/perception_and_utils/perception/detector_wrappers/human_motion_detector.py

Prompts

```
['initialize an AprilTag detector with camera focal lengths and principal point for QR code pose estimation', 'process an image frame to detect AprilTag markers and estimate their pose relative to the camera', 'retrieve decorated visualization images and SE3 pose data from AprilTag detection results', 'create an AprilTagDetectorWrapper instance to detect QR codes and estimate marker pose from camera frames', 'review the AprilTagDetectorWrapper class that wraps AprilTagPoseEstimator for dock marker detection and pose estimation', 'enable the GenericDetector by calling enable_detector to set is_enabled to True', 'disable the GenericDetector by calling disable_detector to set is_enabled to False', 'process a DataFrame frame with a subclass of GenericDetector to get detections and metadata', 'create a subclass of GenericDetector that implements process_frame for custom detection logic', 'review the GenericDetector class and its abstract process_frame interface for detector implementations', 'initialize the HumanMotionDetector with a custom velocity threshold and time horizon for motion detection', 'generate a visualized image with activity state, velocity, and FPS labels overlaid on the frame', 'append a new state change to the human motion history only when the state differs from the last recorded state', 'retrieve the full list of timestamped human motion state changes recorded by the detector', 'initialize an OwlVit object detector with custom labels and confidence threshold for GPU inference', 'process an image frame to detect objects and score them using a custom heuristic function', 'process image frames offline using demo heuristics to filter detections and update labels dynamically', 'score image frames based on pixel occupancy and center proximity for EMRoF algorithm compatibility']
```

Usage

```
{'init_human_motion_detector': 'initialize the HumanMotionDetector with a custom velocity threshold and time horizon for motion detection', 'process_frame': 'process a DataFrame to detect human walking or standing activity based on camera velocity', 'get_outputs': 'generate a visualized image with activity state, velocity, and FPS labels overlaid on the frame', 'update_human_motion_history': 'append a new state change to the human motion history only when the state differs from the last recorded state', 'get_human_motion_history': 'retrieve the full list of timestamped human motion state changes recorded by the detector'}
```

## File: facebookresearch_spot-sim2real/perception_and_utils_root/perception_and_utils/perception/detector_wrappers/object_detector.py

Prompts

```
['initialize an AprilTag detector with camera focal lengths and principal point for QR code pose estimation', 'process an image frame to detect AprilTag markers and estimate their pose relative to the camera', 'retrieve decorated visualization images and SE3 pose data from AprilTag detection results', 'create an AprilTagDetectorWrapper instance to detect QR codes and estimate marker pose from camera frames', 'review the AprilTagDetectorWrapper class that wraps AprilTagPoseEstimator for dock marker detection and pose estimation', 'enable the GenericDetector by calling enable_detector to set is_enabled to True', 'disable the GenericDetector by calling disable_detector to set is_enabled to False', 'process a DataFrame frame with a subclass of GenericDetector to get detections and metadata', 'create a subclass of GenericDetector that implements process_frame for custom detection logic', 'review the GenericDetector class and its abstract process_frame interface for detector implementations', 'initialize the HumanMotionDetector with a custom velocity threshold and time horizon for motion detection', 'generate a visualized image with activity state, velocity, and FPS labels overlaid on the frame', 'append a new state change to the human motion history only when the state differs from the last recorded state', 'retrieve the full list of timestamped human motion state changes recorded by the detector', 'initialize an OwlVit object detector with custom labels and confidence threshold for GPU inference', 'process an image frame to detect objects and score them using a custom heuristic function', 'process image frames offline using demo heuristics to filter detections and update labels dynamically', 'score image frames based on pixel occupancy and center proximity for EMRoF algorithm compatibility']
```

Usage

```
{'init_object_detector': 'initialize an OwlVit object detector with custom labels and confidence threshold for GPU inference', 'process_frame_online': 'process an image frame to detect objects and score them using a custom heuristic function', 'process_frame_offline': 'process image frames offline using demo heuristics to filter detections and update labels dynamically', 'aria_online_heuristic': 'score image frames based on pixel occupancy and center proximity for EMRoF algorithm compatibility', 'get_outputs': 'update outputs dictionary with detected object images, scores, metadata, and segment IDs'}
```

