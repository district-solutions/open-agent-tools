# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/lowlevel/hello_robot/data_compression.py

Prompts

```
['encode an RGB image array to a JPEG-compressed byte buffer using OpenCV', 'decode a JPEG-compressed byte buffer back into an RGB image array using OpenCV', 'compress a depth array into a Blosc-packed byte buffer using the zstd codec', 'decompress a Blosc-packed byte buffer back into the original depth array', 'summarize the data_compression module functions for JPEG image encoding/decoding and Blosc depth array compression', 'create a HelloRobotMover instance connected to a robot by its IP address', 'move the robot to an absolute position in canonical world coordinates', 'command the robot to look at a target by adjusting camera pan and tilt', 'fetch RGB, depth, and point cloud data from the robot camera', 'get obstacle positions in canonical coordinates from the robot SLAM map']
```

Usage

```
{'jpg_encode_rgb': 'encode an RGB image array to a JPEG-compressed byte buffer using OpenCV', 'jpg_decode_rgb': 'decode a JPEG-compressed byte buffer back into an RGB image array using OpenCV', 'blosc_encode_depth': 'compress a depth array into a Blosc-packed byte buffer using the zstd codec', 'blosc_decode_depth': 'decompress a Blosc-packed byte buffer back into the original depth array', 'summarize_data_compression': 'summarize the data_compression module functions for JPEG image encoding/decoding and Blosc depth array compression'}
```

## File: facebookresearch_fairo/droidlet/lowlevel/hello_robot/hello_robot_mover.py

Prompts

```
['encode an RGB image array to a JPEG-compressed byte buffer using OpenCV', 'decode a JPEG-compressed byte buffer back into an RGB image array using OpenCV', 'compress a depth array into a Blosc-packed byte buffer using the zstd codec', 'decompress a Blosc-packed byte buffer back into the original depth array', 'summarize the data_compression module functions for JPEG image encoding/decoding and Blosc depth array compression', 'create a HelloRobotMover instance connected to a robot by its IP address', 'move the robot to an absolute position in canonical world coordinates', 'command the robot to look at a target by adjusting camera pan and tilt', 'fetch RGB, depth, and point cloud data from the robot camera', 'get obstacle positions in canonical coordinates from the robot SLAM map']
```

Usage

```
{'create_HelloRobotMover': 'create a HelloRobotMover instance connected to a robot by its IP address', 'move_absolute_HelloRobotMover': 'move the robot to an absolute position in canonical world coordinates', 'look_at_HelloRobotMover': 'command the robot to look at a target by adjusting camera pan and tilt', 'get_rgb_depth_HelloRobotMover': 'fetch RGB, depth, and point cloud data from the robot camera', 'get_obstacles_HelloRobotMover': 'get obstacle positions in canonical coordinates from the robot SLAM map'}
```

