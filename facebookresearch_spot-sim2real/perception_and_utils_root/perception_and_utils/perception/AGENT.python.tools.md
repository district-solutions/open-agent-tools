# Agent Python Tools

- repo: facebookresearch/spot-sim2real
- repo_uri: https://github.com/facebookresearch/spot-sim2real

## File: facebookresearch_spot-sim2real/perception_and_utils_root/perception_and_utils/perception/april_tag_pose_estimator.py

Prompts

```
['create an AprilTagPoseEstimator instance with camera intrinsics and default marker length', 'register a list of marker IDs with the AprilTagPoseEstimator for detection', 'detect AprilTag markers in an image and estimate their SE3 pose in camera frame', 'validate that a camera intrinsics dictionary contains all required keys like fx fy ppx ppy coeffs', 'summarize the AprilTagPoseEstimator class that detects markers and estimates pose using fairotag and sophus', 'initialize a Detectron2HODetector with a model path and config file for hand-object detection', 'process a DataFrame frame through the Detectron2HODetector to detect left hand, right hand, and objects', 'enable the Detectron2HODetector before processing frames to activate hand-object detection', 'review the Detectron2HODetector class and its process_frame method for hand-object detection logic', 'refactor the Detectron2HODetector to support configurable score thresholds and class metadata', 'create a HARStateMachine instance with model path and config path for hand object detection', 'process a DataFrame frame through the HARStateMachine to detect holding or not holding state', 'review the holding_state_tick method that transitions to not_holding state after N consecutive hand-only frames', 'review the not_holding_state_tick method that transitions to holding state after N consecutive object frames', 'refactor the toggle_state method to support additional states beyond holding and not_holding']
```

Usage

```
{'create_april_tag_pose_estimator': 'create an AprilTagPoseEstimator instance with camera intrinsics and default marker length', 'register_marker_ids': 'register a list of marker IDs with the AprilTagPoseEstimator for detection', 'detect_markers_and_estimate_pose': 'detect AprilTag markers in an image and estimate their SE3 pose in camera frame', 'validate_camera_intrinsics': 'validate that a camera intrinsics dictionary contains all required keys like fx fy ppx ppy coeffs', 'summarize_april_tag_pose_estimator': 'summarize the AprilTagPoseEstimator class that detects markers and estimates pose using fairotag and sophus'}
```

## File: facebookresearch_spot-sim2real/perception_and_utils_root/perception_and_utils/perception/detectron2_ho_detector.py

Prompts

```
['create an AprilTagPoseEstimator instance with camera intrinsics and default marker length', 'register a list of marker IDs with the AprilTagPoseEstimator for detection', 'detect AprilTag markers in an image and estimate their SE3 pose in camera frame', 'validate that a camera intrinsics dictionary contains all required keys like fx fy ppx ppy coeffs', 'summarize the AprilTagPoseEstimator class that detects markers and estimates pose using fairotag and sophus', 'initialize a Detectron2HODetector with a model path and config file for hand-object detection', 'process a DataFrame frame through the Detectron2HODetector to detect left hand, right hand, and objects', 'enable the Detectron2HODetector before processing frames to activate hand-object detection', 'review the Detectron2HODetector class and its process_frame method for hand-object detection logic', 'refactor the Detectron2HODetector to support configurable score thresholds and class metadata', 'create a HARStateMachine instance with model path and config path for hand object detection', 'process a DataFrame frame through the HARStateMachine to detect holding or not holding state', 'review the holding_state_tick method that transitions to not_holding state after N consecutive hand-only frames', 'review the not_holding_state_tick method that transitions to holding state after N consecutive object frames', 'refactor the toggle_state method to support additional states beyond holding and not_holding']
```

Usage

```
{'init_detectron2_ho_detector': 'initialize a Detectron2HODetector with a model path and config file for hand-object detection', 'process_frame_with_detector': 'process a DataFrame frame through the Detectron2HODetector to detect left hand, right hand, and objects', 'enable_detector': 'enable the Detectron2HODetector before processing frames to activate hand-object detection', 'review_detectron2_ho_detector': 'review the Detectron2HODetector class and its process_frame method for hand-object detection logic', 'refactor_detectron2_ho_detector': 'refactor the Detectron2HODetector to support configurable score thresholds and class metadata'}
```

## File: facebookresearch_spot-sim2real/perception_and_utils_root/perception_and_utils/perception/human_action_recognition_state_machine.py

Prompts

```
['create an AprilTagPoseEstimator instance with camera intrinsics and default marker length', 'register a list of marker IDs with the AprilTagPoseEstimator for detection', 'detect AprilTag markers in an image and estimate their SE3 pose in camera frame', 'validate that a camera intrinsics dictionary contains all required keys like fx fy ppx ppy coeffs', 'summarize the AprilTagPoseEstimator class that detects markers and estimates pose using fairotag and sophus', 'initialize a Detectron2HODetector with a model path and config file for hand-object detection', 'process a DataFrame frame through the Detectron2HODetector to detect left hand, right hand, and objects', 'enable the Detectron2HODetector before processing frames to activate hand-object detection', 'review the Detectron2HODetector class and its process_frame method for hand-object detection logic', 'refactor the Detectron2HODetector to support configurable score thresholds and class metadata', 'create a HARStateMachine instance with model path and config path for hand object detection', 'process a DataFrame frame through the HARStateMachine to detect holding or not holding state', 'review the holding_state_tick method that transitions to not_holding state after N consecutive hand-only frames', 'review the not_holding_state_tick method that transitions to holding state after N consecutive object frames', 'refactor the toggle_state method to support additional states beyond holding and not_holding']
```

Usage

```
{'create_HARStateMachine': 'create a HARStateMachine instance with model path and config path for hand object detection', 'process_frame_HARStateMachine': 'process a DataFrame frame through the HARStateMachine to detect holding or not holding state', 'review_holding_state_tick': 'review the holding_state_tick method that transitions to not_holding state after N consecutive hand-only frames', 'review_not_holding_state_tick': 'review the not_holding_state_tick method that transitions to holding state after N consecutive object frames', 'refactor_toggle_state': 'refactor the toggle_state method to support additional states beyond holding and not_holding'}
```

