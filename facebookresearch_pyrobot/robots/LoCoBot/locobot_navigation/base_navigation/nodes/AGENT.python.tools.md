# Agent Python Tools

- repo: facebookresearch/pyrobot
- repo_uri: https://github.com/facebookresearch/pyrobot

## File: facebookresearch_pyrobot/robots/LoCoBot/locobot_navigation/base_navigation/nodes/mapToGrid.py

Prompts

```
['run the PcdToOcGrid ROS node to convert point cloud data into an occupancy grid map', 'create a PcdToOcGrid instance with z thresholds and x/y bounding box parameters for map conversion', 'populate 3D map points and colors from the LoCoBot VSLAM system using populatePoints', 'populate the occupancy grid by filtering points by z threshold and mapping them to grid cells', 'update and publish the occupancy grid message with current map data to the ROS topic']
```

Usage

```
{'run_PcdToOcGrid_main': 'run the PcdToOcGrid ROS node to convert point cloud data into an occupancy grid map', 'create_PcdToOcGrid_instance': 'create a PcdToOcGrid instance with z thresholds and x/y bounding box parameters for map conversion', 'populatePoints_VSLAM': 'populate 3D map points and colors from the LoCoBot VSLAM system using populatePoints', 'populateMap_occupancy_grid': 'populate the occupancy grid by filtering points by z threshold and mapping them to grid cells', 'updateGrid_publish': 'update and publish the occupancy grid message with current map data to the ROS topic'}
```

