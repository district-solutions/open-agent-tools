# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/perception/robot/perception.py

Prompts

```
['initialize a Perception instance with a model_data_dir path for LocobotAgent perceptual modules', 'call perceive on a Perception instance with rgb_depth, xyz, and previous_objects to run perceptual models', 'call setup_vision_handlers on a Perception instance to create an AttributeDict of vision handlers including ObjectDeduplicator', 'call log on a Perception instance to emit rgb, depth, objects, and humans data to the dashboard via SocketIO', 'emit an update_image_settings SocketIO event to change image_resolution and image_quality log settings on the Perception instance', 'generate N visually distinct random colors in HSV space and convert them to RGB tuples', 'encode an image file from disk into a base64 string for storage or transmission', 'decode a base64 encoded string back into a PIL Image in RGB color mode', 'find the closest named CSS3 color for a given RGB color tuple by Euclidean distance', 'draw 3D coordinate labels and red marker points on a PIL image at specified centers', 'create a solid rectanguloid with specified width, height, and depth dimensions', 'create a hollow rectanguloid with configurable wall thickness and optional labels', 'create a solid sphere with a given radius and optional labeling', 'create a hollow spherical shell with configurable radius and wall thickness', 'arrange schematic shapes in a circle or line pattern with offsets']
```

Usage

```
{'init_perception': 'initialize a Perception instance with a model_data_dir path for LocobotAgent perceptual modules', 'run_perceive': 'call perceive on a Perception instance with rgb_depth, xyz, and previous_objects to run perceptual models', 'setup_vision_handlers': 'call setup_vision_handlers on a Perception instance to create an AttributeDict of vision handlers including ObjectDeduplicator', 'log_perception_data': 'call log on a Perception instance to emit rgb, depth, objects, and humans data to the dashboard via SocketIO', 'update_image_settings': 'emit an update_image_settings SocketIO event to change image_resolution and image_quality log settings on the Perception instance'}
```

## File: facebookresearch_fairo/droidlet/perception/robot/perception_util.py

Prompts

```
['initialize a Perception instance with a model_data_dir path for LocobotAgent perceptual modules', 'call perceive on a Perception instance with rgb_depth, xyz, and previous_objects to run perceptual models', 'call setup_vision_handlers on a Perception instance to create an AttributeDict of vision handlers including ObjectDeduplicator', 'call log on a Perception instance to emit rgb, depth, objects, and humans data to the dashboard via SocketIO', 'emit an update_image_settings SocketIO event to change image_resolution and image_quality log settings on the Perception instance', 'generate N visually distinct random colors in HSV space and convert them to RGB tuples', 'encode an image file from disk into a base64 string for storage or transmission', 'decode a base64 encoded string back into a PIL Image in RGB color mode', 'find the closest named CSS3 color for a given RGB color tuple by Euclidean distance', 'draw 3D coordinate labels and red marker points on a PIL image at specified centers', 'create a solid rectanguloid with specified width, height, and depth dimensions', 'create a hollow rectanguloid with configurable wall thickness and optional labels', 'create a solid sphere with a given radius and optional labeling', 'create a hollow spherical shell with configurable radius and wall thickness', 'arrange schematic shapes in a circle or line pattern with offsets']
```

Usage

```
{'generate_random_colors': 'generate N visually distinct random colors in HSV space and convert them to RGB tuples', 'encode_image_to_base64': 'encode an image file from disk into a base64 string for storage or transmission', 'decode_base64_to_image': 'decode a base64 encoded string back into a PIL Image in RGB color mode', 'find_closest_color_name': 'find the closest named CSS3 color for a given RGB color tuple by Euclidean distance', 'annotate_image_with_xyz_coords': 'draw 3D coordinate labels and red marker points on a PIL image at specified centers'}
```

## File: facebookresearch_fairo/droidlet/perception/robot/shapes.py

Prompts

```
['initialize a Perception instance with a model_data_dir path for LocobotAgent perceptual modules', 'call perceive on a Perception instance with rgb_depth, xyz, and previous_objects to run perceptual models', 'call setup_vision_handlers on a Perception instance to create an AttributeDict of vision handlers including ObjectDeduplicator', 'call log on a Perception instance to emit rgb, depth, objects, and humans data to the dashboard via SocketIO', 'emit an update_image_settings SocketIO event to change image_resolution and image_quality log settings on the Perception instance', 'generate N visually distinct random colors in HSV space and convert them to RGB tuples', 'encode an image file from disk into a base64 string for storage or transmission', 'decode a base64 encoded string back into a PIL Image in RGB color mode', 'find the closest named CSS3 color for a given RGB color tuple by Euclidean distance', 'draw 3D coordinate labels and red marker points on a PIL image at specified centers', 'create a solid rectanguloid with specified width, height, and depth dimensions', 'create a hollow rectanguloid with configurable wall thickness and optional labels', 'create a solid sphere with a given radius and optional labeling', 'create a hollow spherical shell with configurable radius and wall thickness', 'arrange schematic shapes in a circle or line pattern with offsets']
```

Usage

```
{'create_rectanguloid': 'create a solid rectanguloid with specified width, height, and depth dimensions', 'create_hollow_rectanguloid': 'create a hollow rectanguloid with configurable wall thickness and optional labels', 'create_sphere': 'create a solid sphere with a given radius and optional labeling', 'create_spherical_shell': 'create a hollow spherical shell with configurable radius and wall thickness', 'arrange_shapes': 'arrange schematic shapes in a circle or line pattern with offsets'}
```

