# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/projects/offline_mapping/build_map.py

Prompts

```
['build a 2D semantic map from a robot trajectory by running the click CLI with input trajectory pickle files', 'run the offline mapping script to generate visualization images and a video from robot observation trajectory files', 'create a visualization image combining semantic segmentation, depth, and predicted semantic map using get_semantic_map_vis', 'create an mp4 video from a list of numpy image arrays using the create_video function with a specified fps', 'preprocess home robot observations into tensors with RGB, depth, semantic, and instance channels for map building']
```

Usage

```
{'build_semantic_map_from_trajectory': 'build a 2D semantic map from a robot trajectory by running the click CLI with input trajectory pickle files', 'run_semantic_map_visualization': 'run the offline mapping script to generate visualization images and a video from robot observation trajectory files', 'create_semantic_map_vis': 'create a visualization image combining semantic segmentation, depth, and predicted semantic map using get_semantic_map_vis', 'create_video_from_images': 'create an mp4 video from a list of numpy image arrays using the create_video function with a specified fps', 'preprocess_robot_observations': 'preprocess home robot observations into tensors with RGB, depth, semantic, and instance channels for map building'}
```

