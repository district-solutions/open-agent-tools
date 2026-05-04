# Agent Python Tools

- repo: facebookresearch/geort
- repo_uri: https://github.com/facebookresearch/geort

## File: facebookresearch_geort/geort/mocap/manus_mocap.py

Prompts

```
['create a ManusMocap client that connects to a ZMQ broadcasted mocap data source on a specified port', 'get the latest mocap joint position data as a numpy array from the ManusMocap client', 'close the ManusMocap ZMQ socket and stop the background receive thread gracefully', 'review the ManusMocap _recv_loop method that continuously receives ZMQ messages and updates latest data', 'refactor the ManusMocap class to accept a configurable default port for the ZMQ SUB socket connection', 'run the Manus ROS2 node to broadcast hand keypoints via ZMQ on port 8765', 'run hand_to_canonical to transform 21 hand joint points into a canonical coordinate frame', 'run ManusForwardKinematicsSolver solve_keypoints to compute 3D hand joint positions from positions and quaternion orientations', 'run make_transformation_matrix to build a 4x4 transformation matrix from a position vector and quaternion', 'review the Manus ROS2 node class that subscribes to rotation topics and publishes hand keypoints via ZMQ', 'run the MediaPipeMocap CLI with --name flag to collect hand motion capture data via RealSense camera', 'create a MediaPipeHandDetector instance to detect hand landmarks and handedness from RGB images', 'process hand detection results through MediaPipeHandProcessor.forward to compute canonical coordinates with optional EMA smoothing', 'interpolate between two rotation quaternions using MediaPipeHandProcessor.slerp for smooth orientation transitions', 'detect hand landmarks from an RGB image using MediaPipeHandDetector.detect and return canonical and world coordinates', 'create a ReplayMocap instance that loads human motion capture data from a specified data path', 'run the ReplayMocap get method to retrieve the next frame of human motion capture points', 'build a loop that repeatedly calls ReplayMocap get to replay human motion data frame by frame', 'review the ReplayMocap class to understand how it loads and replays numpy motion capture arrays', 'test the ReplayMocap get method to verify it cycles back to the start after exhausting all frames']
```

Usage

```
{'create_manus_mocap_client': 'create a ManusMocap client that connects to a ZMQ broadcasted mocap data source on a specified port', 'get_latest_mocap_data': 'get the latest mocap joint position data as a numpy array from the ManusMocap client', 'close_mocap_connection': 'close the ManusMocap ZMQ socket and stop the background receive thread gracefully', 'review_recv_loop': 'review the ManusMocap _recv_loop method that continuously receives ZMQ messages and updates latest data', 'refactor_mocap_port_default': 'refactor the ManusMocap class to accept a configurable default port for the ZMQ SUB socket connection'}
```

## File: facebookresearch_geort/geort/mocap/manus_mocap_core.py

Prompts

```
['create a ManusMocap client that connects to a ZMQ broadcasted mocap data source on a specified port', 'get the latest mocap joint position data as a numpy array from the ManusMocap client', 'close the ManusMocap ZMQ socket and stop the background receive thread gracefully', 'review the ManusMocap _recv_loop method that continuously receives ZMQ messages and updates latest data', 'refactor the ManusMocap class to accept a configurable default port for the ZMQ SUB socket connection', 'run the Manus ROS2 node to broadcast hand keypoints via ZMQ on port 8765', 'run hand_to_canonical to transform 21 hand joint points into a canonical coordinate frame', 'run ManusForwardKinematicsSolver solve_keypoints to compute 3D hand joint positions from positions and quaternion orientations', 'run make_transformation_matrix to build a 4x4 transformation matrix from a position vector and quaternion', 'review the Manus ROS2 node class that subscribes to rotation topics and publishes hand keypoints via ZMQ', 'run the MediaPipeMocap CLI with --name flag to collect hand motion capture data via RealSense camera', 'create a MediaPipeHandDetector instance to detect hand landmarks and handedness from RGB images', 'process hand detection results through MediaPipeHandProcessor.forward to compute canonical coordinates with optional EMA smoothing', 'interpolate between two rotation quaternions using MediaPipeHandProcessor.slerp for smooth orientation transitions', 'detect hand landmarks from an RGB image using MediaPipeHandDetector.detect and return canonical and world coordinates', 'create a ReplayMocap instance that loads human motion capture data from a specified data path', 'run the ReplayMocap get method to retrieve the next frame of human motion capture points', 'build a loop that repeatedly calls ReplayMocap get to replay human motion data frame by frame', 'review the ReplayMocap class to understand how it loads and replays numpy motion capture arrays', 'test the ReplayMocap get method to verify it cycles back to the start after exhausting all frames']
```

Usage

```
{'run_manus_node': 'run the Manus ROS2 node to broadcast hand keypoints via ZMQ on port 8765', 'run_hand_to_canonical': 'run hand_to_canonical to transform 21 hand joint points into a canonical coordinate frame', 'run_solve_keypoints': 'run ManusForwardKinematicsSolver solve_keypoints to compute 3D hand joint positions from positions and quaternion orientations', 'run_make_transformation_matrix': 'run make_transformation_matrix to build a 4x4 transformation matrix from a position vector and quaternion', 'review_manus_class': 'review the Manus ROS2 node class that subscribes to rotation topics and publishes hand keypoints via ZMQ'}
```

## File: facebookresearch_geort/geort/mocap/mediapipe_mocap.py

Prompts

```
['create a ManusMocap client that connects to a ZMQ broadcasted mocap data source on a specified port', 'get the latest mocap joint position data as a numpy array from the ManusMocap client', 'close the ManusMocap ZMQ socket and stop the background receive thread gracefully', 'review the ManusMocap _recv_loop method that continuously receives ZMQ messages and updates latest data', 'refactor the ManusMocap class to accept a configurable default port for the ZMQ SUB socket connection', 'run the Manus ROS2 node to broadcast hand keypoints via ZMQ on port 8765', 'run hand_to_canonical to transform 21 hand joint points into a canonical coordinate frame', 'run ManusForwardKinematicsSolver solve_keypoints to compute 3D hand joint positions from positions and quaternion orientations', 'run make_transformation_matrix to build a 4x4 transformation matrix from a position vector and quaternion', 'review the Manus ROS2 node class that subscribes to rotation topics and publishes hand keypoints via ZMQ', 'run the MediaPipeMocap CLI with --name flag to collect hand motion capture data via RealSense camera', 'create a MediaPipeHandDetector instance to detect hand landmarks and handedness from RGB images', 'process hand detection results through MediaPipeHandProcessor.forward to compute canonical coordinates with optional EMA smoothing', 'interpolate between two rotation quaternions using MediaPipeHandProcessor.slerp for smooth orientation transitions', 'detect hand landmarks from an RGB image using MediaPipeHandDetector.detect and return canonical and world coordinates', 'create a ReplayMocap instance that loads human motion capture data from a specified data path', 'run the ReplayMocap get method to retrieve the next frame of human motion capture points', 'build a loop that repeatedly calls ReplayMocap get to replay human motion data frame by frame', 'review the ReplayMocap class to understand how it loads and replays numpy motion capture arrays', 'test the ReplayMocap get method to verify it cycles back to the start after exhausting all frames']
```

Usage

```
{'run_mediapipe_mocap_cli': 'run the MediaPipeMocap CLI with --name flag to collect hand motion capture data via RealSense camera', 'create_hand_detector': 'create a MediaPipeHandDetector instance to detect hand landmarks and handedness from RGB images', 'process_hand_landmarks': 'process hand detection results through MediaPipeHandProcessor.forward to compute canonical coordinates with optional EMA smoothing', 'interpolate_rotation_quaternions': 'interpolate between two rotation quaternions using MediaPipeHandProcessor.slerp for smooth orientation transitions', 'detect_hand_landmarks': 'detect hand landmarks from an RGB image using MediaPipeHandDetector.detect and return canonical and world coordinates'}
```

## File: facebookresearch_geort/geort/mocap/replay_mocap.py

Prompts

```
['create a ManusMocap client that connects to a ZMQ broadcasted mocap data source on a specified port', 'get the latest mocap joint position data as a numpy array from the ManusMocap client', 'close the ManusMocap ZMQ socket and stop the background receive thread gracefully', 'review the ManusMocap _recv_loop method that continuously receives ZMQ messages and updates latest data', 'refactor the ManusMocap class to accept a configurable default port for the ZMQ SUB socket connection', 'run the Manus ROS2 node to broadcast hand keypoints via ZMQ on port 8765', 'run hand_to_canonical to transform 21 hand joint points into a canonical coordinate frame', 'run ManusForwardKinematicsSolver solve_keypoints to compute 3D hand joint positions from positions and quaternion orientations', 'run make_transformation_matrix to build a 4x4 transformation matrix from a position vector and quaternion', 'review the Manus ROS2 node class that subscribes to rotation topics and publishes hand keypoints via ZMQ', 'run the MediaPipeMocap CLI with --name flag to collect hand motion capture data via RealSense camera', 'create a MediaPipeHandDetector instance to detect hand landmarks and handedness from RGB images', 'process hand detection results through MediaPipeHandProcessor.forward to compute canonical coordinates with optional EMA smoothing', 'interpolate between two rotation quaternions using MediaPipeHandProcessor.slerp for smooth orientation transitions', 'detect hand landmarks from an RGB image using MediaPipeHandDetector.detect and return canonical and world coordinates', 'create a ReplayMocap instance that loads human motion capture data from a specified data path', 'run the ReplayMocap get method to retrieve the next frame of human motion capture points', 'build a loop that repeatedly calls ReplayMocap get to replay human motion data frame by frame', 'review the ReplayMocap class to understand how it loads and replays numpy motion capture arrays', 'test the ReplayMocap get method to verify it cycles back to the start after exhausting all frames']
```

Usage

```
{'create_ReplayMocap_instance': 'create a ReplayMocap instance that loads human motion capture data from a specified data path', 'run_ReplayMocap_get': 'run the ReplayMocap get method to retrieve the next frame of human motion capture points', 'build_mocap_replay_loop': 'build a loop that repeatedly calls ReplayMocap get to replay human motion data frame by frame', 'review_ReplayMocap_class': 'review the ReplayMocap class to understand how it loads and replays numpy motion capture arrays', 'test_ReplayMocap_cycling': 'test the ReplayMocap get method to verify it cycles back to the start after exhausting all frames'}
```

