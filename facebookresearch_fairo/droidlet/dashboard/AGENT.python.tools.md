# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/dashboard/o3dviz.py

Prompts

```
['create an Open3D visualizer process with optional WebRTC streaming enabled on port 8889', 'add a robot base cylinder and orientation arrow mesh to the Open3D visualization scene', 'serialize an Open3D TriangleMesh, PointCloud, or OrientedBoundingBox into shared-memory pickle bytes', 'deserialize pickled shared-memory bytes back into an Open3D geometry object like TriangleMesh or PointCloud', 'send add, remove, or replace geometry commands to the background O3DVizProcess via serialized queue']
```

Usage

```
{'create_open3d_visualizer_with_webrtc': 'create an Open3D visualizer process with optional WebRTC streaming enabled on port 8889', 'add_robot_geometry_to_scene': 'add a robot base cylinder and orientation arrow mesh to the Open3D visualization scene', 'serialize_open3d_geometry_for_multiprocessing': 'serialize an Open3D TriangleMesh, PointCloud, or OrientedBoundingBox into shared-memory pickle bytes', 'deserialize_open3d_geometry_from_pickle': 'deserialize pickled shared-memory bytes back into an Open3D geometry object like TriangleMesh or PointCloud', 'send_geometry_commands_to_viz_process': 'send add, remove, or replace geometry commands to the background O3DVizProcess via serialized queue'}
```

