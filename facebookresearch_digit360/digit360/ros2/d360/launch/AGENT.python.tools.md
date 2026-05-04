# Agent Python Tools

- repo: facebookresearch/digit360
- repo_uri: https://github.com/facebookresearch/digit360

## File: facebookresearch_digit360/digit360/ros2/d360/launch/d360_hand_launch.py

Prompts

```
['run the ROS2 launch file to start DIGIT360 hand nodes for connected devices', 'generate a GroupAction with serial IO, image publisher, and audio nodes for a DIGIT360 device', 'load a YAML config file and return right and left hand finger serial mappings', 'enumerate connected DIGIT360 devices from a YAML config and launch matching hand node groups', 'generate a ROS2 LaunchDescription with image_pub_type and hand_config launch arguments', 'run generate_launch_description to start the d360 ROS 2 launch with foxglove bridge and d360_min', 'review generate_launch_description to understand the ROS 2 launch configuration for d360', 'summarize the image_pub_type_arg DeclareLaunchArgument that selects raw or encoded image publishing', 'review the foxglove Node configuration that starts foxglove_bridge on port 8766', 'review the d360_min IncludeLaunchDescription that includes d360_min_launch.py with image_pub_type argument', 'enumerate all connected Digit360 USB devices and create ROS2 node group actions for each one', 'review the Digit360Descriptor dataclass that holds serial, data, audio, ics, base_version, and ics_version fields', 'configure the image publisher type as raw or encoded via the image_pub_type launch argument']
```

Usage

```
{'run_d360_hand_launch': 'run the ROS2 launch file to start DIGIT360 hand nodes for connected devices', 'generate_d360_group_actions': 'generate a GroupAction with serial IO, image publisher, and audio nodes for a DIGIT360 device', 'load_hand_config': 'load a YAML config file and return right and left hand finger serial mappings', 'enumerate_d360_from_yaml': 'enumerate connected DIGIT360 devices from a YAML config and launch matching hand node groups', 'generate_launch_description': 'generate a ROS2 LaunchDescription with image_pub_type and hand_config launch arguments'}
```

## File: facebookresearch_digit360/digit360/ros2/d360/launch/d360_launch.py

Prompts

```
['run the ROS2 launch file to start DIGIT360 hand nodes for connected devices', 'generate a GroupAction with serial IO, image publisher, and audio nodes for a DIGIT360 device', 'load a YAML config file and return right and left hand finger serial mappings', 'enumerate connected DIGIT360 devices from a YAML config and launch matching hand node groups', 'generate a ROS2 LaunchDescription with image_pub_type and hand_config launch arguments', 'run generate_launch_description to start the d360 ROS 2 launch with foxglove bridge and d360_min', 'review generate_launch_description to understand the ROS 2 launch configuration for d360', 'summarize the image_pub_type_arg DeclareLaunchArgument that selects raw or encoded image publishing', 'review the foxglove Node configuration that starts foxglove_bridge on port 8766', 'review the d360_min IncludeLaunchDescription that includes d360_min_launch.py with image_pub_type argument', 'enumerate all connected Digit360 USB devices and create ROS2 node group actions for each one', 'review the Digit360Descriptor dataclass that holds serial, data, audio, ics, base_version, and ics_version fields', 'configure the image publisher type as raw or encoded via the image_pub_type launch argument']
```

Usage

```
{'run_generate_launch_description': 'run generate_launch_description to start the d360 ROS 2 launch with foxglove bridge and d360_min', 'review_generate_launch_description': 'review generate_launch_description to understand the ROS 2 launch configuration for d360', 'summarize_image_pub_type_arg': 'summarize the image_pub_type_arg DeclareLaunchArgument that selects raw or encoded image publishing', 'review_foxglove_node': 'review the foxglove Node configuration that starts foxglove_bridge on port 8766', 'review_d360_min_include': 'review the d360_min IncludeLaunchDescription that includes d360_min_launch.py with image_pub_type argument'}
```

## File: facebookresearch_digit360/digit360/ros2/d360/launch/d360_min_launch.py

Prompts

```
['run the ROS2 launch file to start DIGIT360 hand nodes for connected devices', 'generate a GroupAction with serial IO, image publisher, and audio nodes for a DIGIT360 device', 'load a YAML config file and return right and left hand finger serial mappings', 'enumerate connected DIGIT360 devices from a YAML config and launch matching hand node groups', 'generate a ROS2 LaunchDescription with image_pub_type and hand_config launch arguments', 'run generate_launch_description to start the d360 ROS 2 launch with foxglove bridge and d360_min', 'review generate_launch_description to understand the ROS 2 launch configuration for d360', 'summarize the image_pub_type_arg DeclareLaunchArgument that selects raw or encoded image publishing', 'review the foxglove Node configuration that starts foxglove_bridge on port 8766', 'review the d360_min IncludeLaunchDescription that includes d360_min_launch.py with image_pub_type argument', 'enumerate all connected Digit360 USB devices and create ROS2 node group actions for each one', 'review the Digit360Descriptor dataclass that holds serial, data, audio, ics, base_version, and ics_version fields', 'configure the image publisher type as raw or encoded via the image_pub_type launch argument']
```

Usage

```
{'generate_launch_description': 'generate a ROS2 launch description that declares image_pub_type argument and enumerates active Digit360 devices', 'generate_d360_group_actions': 'generate a GroupAction with serial IO, image publisher, and audio publisher nodes for a Digit360 device', 'enumerate_active_d360_actions': 'enumerate all connected Digit360 USB devices and create ROS2 node group actions for each one', 'Digit360Descriptor': 'review the Digit360Descriptor dataclass that holds serial, data, audio, ics, base_version, and ics_version fields', 'image_pub_type_configuration': 'configure the image publisher type as raw or encoded via the image_pub_type launch argument'}
```

