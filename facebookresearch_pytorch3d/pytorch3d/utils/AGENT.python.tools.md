# Agent Python Tools

- repo: facebookresearch/pytorch3d
- repo_uri: https://github.com/facebookresearch/pytorch3d.git

## File: facebookresearch_pytorch3d/pytorch3d/utils/camera_conversions.py

Prompts

```
['convert OpenCV rotation matrices, translation vectors, and camera calibration matrices to PyTorch3D PerspectiveCameras', 'convert PyTorch3D PerspectiveCameras back to OpenCV rotation matrices, translation vectors, and camera calibration matrices', 'convert OpenCV camera parameters to Pulsar style camera vectors with translation, rotation, focal length, and sensor width', 'convert PyTorch3D PerspectiveCameras to Pulsar style camera vectors with translation, rotation, focal length, and sensor width', 'review the camera_conversions module for OpenCV, PyTorch3D, and Pulsar camera convention conversion utilities', 'create a checkerboard mesh in the xy-plane with default black and white colors using pytorch3d', 'create a checkerboard mesh with custom foreground and background colors for visualization testing', 'create a checkerboard mesh with a custom radius to control the number of squares from the origin', 'create a checkerboard mesh on a specific GPU device for accelerated rendering in pytorch3d', 'review the checkerboard function to understand how it constructs vertices, faces, and texture atlas for mesh generation', 'create a level 0 icosphere mesh with 12 vertices and 20 triangular faces on CPU', 'create a subdivided icosphere mesh by specifying a subdivision level greater than zero', 'create an icosphere mesh allocated on a specific torch device such as CUDA', 'review the ico_sphere function recursive subdivision logic and vertex normalization approach', 'summarize the ico_sphere function which generates unit icosphere meshes with consistent face orientation', 'create a torus mesh with specified inner radius, outer radius, sides, and rings divisions', 'create a torus mesh allocated on a specific GPU device using the device parameter', 'review the torus function validation logic that checks sides and rings must be greater than zero', 'summarize the _make_pair_range helper function that generates adjacent index pairs for face construction', 'test the torus mesh generation by verifying vertex count equals sides multiplied by rings']
```

Usage

```
{'convert_opencv_to_pytorch3d_cameras': 'convert OpenCV rotation matrices, translation vectors, and camera calibration matrices to PyTorch3D PerspectiveCameras', 'convert_pytorch3d_to_opencv_cameras': 'convert PyTorch3D PerspectiveCameras back to OpenCV rotation matrices, translation vectors, and camera calibration matrices', 'convert_opencv_to_pulsar_cameras': 'convert OpenCV camera parameters to Pulsar style camera vectors with translation, rotation, focal length, and sensor width', 'convert_pytorch3d_to_pulsar_cameras': 'convert PyTorch3D PerspectiveCameras to Pulsar style camera vectors with translation, rotation, focal length, and sensor width', 'review_camera_conversions_module': 'review the camera_conversions module for OpenCV, PyTorch3D, and Pulsar camera convention conversion utilities'}
```

## File: facebookresearch_pytorch3d/pytorch3d/utils/checkerboard.py

Prompts

```
['convert OpenCV rotation matrices, translation vectors, and camera calibration matrices to PyTorch3D PerspectiveCameras', 'convert PyTorch3D PerspectiveCameras back to OpenCV rotation matrices, translation vectors, and camera calibration matrices', 'convert OpenCV camera parameters to Pulsar style camera vectors with translation, rotation, focal length, and sensor width', 'convert PyTorch3D PerspectiveCameras to Pulsar style camera vectors with translation, rotation, focal length, and sensor width', 'review the camera_conversions module for OpenCV, PyTorch3D, and Pulsar camera convention conversion utilities', 'create a checkerboard mesh in the xy-plane with default black and white colors using pytorch3d', 'create a checkerboard mesh with custom foreground and background colors for visualization testing', 'create a checkerboard mesh with a custom radius to control the number of squares from the origin', 'create a checkerboard mesh on a specific GPU device for accelerated rendering in pytorch3d', 'review the checkerboard function to understand how it constructs vertices, faces, and texture atlas for mesh generation', 'create a level 0 icosphere mesh with 12 vertices and 20 triangular faces on CPU', 'create a subdivided icosphere mesh by specifying a subdivision level greater than zero', 'create an icosphere mesh allocated on a specific torch device such as CUDA', 'review the ico_sphere function recursive subdivision logic and vertex normalization approach', 'summarize the ico_sphere function which generates unit icosphere meshes with consistent face orientation', 'create a torus mesh with specified inner radius, outer radius, sides, and rings divisions', 'create a torus mesh allocated on a specific GPU device using the device parameter', 'review the torus function validation logic that checks sides and rings must be greater than zero', 'summarize the _make_pair_range helper function that generates adjacent index pairs for face construction', 'test the torus mesh generation by verifying vertex count equals sides multiplied by rings']
```

Usage

```
{'create_checkerboard_mesh': 'create a checkerboard mesh in the xy-plane with default black and white colors using pytorch3d', 'create_checkerboard_custom_colors': 'create a checkerboard mesh with custom foreground and background colors for visualization testing', 'create_checkerboard_custom_radius': 'create a checkerboard mesh with a custom radius to control the number of squares from the origin', 'create_checkerboard_gpu': 'create a checkerboard mesh on a specific GPU device for accelerated rendering in pytorch3d', 'review_checkerboard_function': 'review the checkerboard function to understand how it constructs vertices, faces, and texture atlas for mesh generation'}
```

## File: facebookresearch_pytorch3d/pytorch3d/utils/ico_sphere.py

Prompts

```
['convert OpenCV rotation matrices, translation vectors, and camera calibration matrices to PyTorch3D PerspectiveCameras', 'convert PyTorch3D PerspectiveCameras back to OpenCV rotation matrices, translation vectors, and camera calibration matrices', 'convert OpenCV camera parameters to Pulsar style camera vectors with translation, rotation, focal length, and sensor width', 'convert PyTorch3D PerspectiveCameras to Pulsar style camera vectors with translation, rotation, focal length, and sensor width', 'review the camera_conversions module for OpenCV, PyTorch3D, and Pulsar camera convention conversion utilities', 'create a checkerboard mesh in the xy-plane with default black and white colors using pytorch3d', 'create a checkerboard mesh with custom foreground and background colors for visualization testing', 'create a checkerboard mesh with a custom radius to control the number of squares from the origin', 'create a checkerboard mesh on a specific GPU device for accelerated rendering in pytorch3d', 'review the checkerboard function to understand how it constructs vertices, faces, and texture atlas for mesh generation', 'create a level 0 icosphere mesh with 12 vertices and 20 triangular faces on CPU', 'create a subdivided icosphere mesh by specifying a subdivision level greater than zero', 'create an icosphere mesh allocated on a specific torch device such as CUDA', 'review the ico_sphere function recursive subdivision logic and vertex normalization approach', 'summarize the ico_sphere function which generates unit icosphere meshes with consistent face orientation', 'create a torus mesh with specified inner radius, outer radius, sides, and rings divisions', 'create a torus mesh allocated on a specific GPU device using the device parameter', 'review the torus function validation logic that checks sides and rings must be greater than zero', 'summarize the _make_pair_range helper function that generates adjacent index pairs for face construction', 'test the torus mesh generation by verifying vertex count equals sides multiplied by rings']
```

Usage

```
{'create_icosphere_level0': 'create a level 0 icosphere mesh with 12 vertices and 20 triangular faces on CPU', 'create_icosphere_subdivided': 'create a subdivided icosphere mesh by specifying a subdivision level greater than zero', 'create_icosphere_gpu': 'create an icosphere mesh allocated on a specific torch device such as CUDA', 'review_ico_sphere_subdivision': 'review the ico_sphere function recursive subdivision logic and vertex normalization approach', 'summarize_ico_sphere': 'summarize the ico_sphere function which generates unit icosphere meshes with consistent face orientation'}
```

## File: facebookresearch_pytorch3d/pytorch3d/utils/torus.py

Prompts

```
['convert OpenCV rotation matrices, translation vectors, and camera calibration matrices to PyTorch3D PerspectiveCameras', 'convert PyTorch3D PerspectiveCameras back to OpenCV rotation matrices, translation vectors, and camera calibration matrices', 'convert OpenCV camera parameters to Pulsar style camera vectors with translation, rotation, focal length, and sensor width', 'convert PyTorch3D PerspectiveCameras to Pulsar style camera vectors with translation, rotation, focal length, and sensor width', 'review the camera_conversions module for OpenCV, PyTorch3D, and Pulsar camera convention conversion utilities', 'create a checkerboard mesh in the xy-plane with default black and white colors using pytorch3d', 'create a checkerboard mesh with custom foreground and background colors for visualization testing', 'create a checkerboard mesh with a custom radius to control the number of squares from the origin', 'create a checkerboard mesh on a specific GPU device for accelerated rendering in pytorch3d', 'review the checkerboard function to understand how it constructs vertices, faces, and texture atlas for mesh generation', 'create a level 0 icosphere mesh with 12 vertices and 20 triangular faces on CPU', 'create a subdivided icosphere mesh by specifying a subdivision level greater than zero', 'create an icosphere mesh allocated on a specific torch device such as CUDA', 'review the ico_sphere function recursive subdivision logic and vertex normalization approach', 'summarize the ico_sphere function which generates unit icosphere meshes with consistent face orientation', 'create a torus mesh with specified inner radius, outer radius, sides, and rings divisions', 'create a torus mesh allocated on a specific GPU device using the device parameter', 'review the torus function validation logic that checks sides and rings must be greater than zero', 'summarize the _make_pair_range helper function that generates adjacent index pairs for face construction', 'test the torus mesh generation by verifying vertex count equals sides multiplied by rings']
```

Usage

```
{'create_torus_mesh': 'create a torus mesh with specified inner radius, outer radius, sides, and rings divisions', 'create_torus_on_gpu': 'create a torus mesh allocated on a specific GPU device using the device parameter', 'review_torus_validation': 'review the torus function validation logic that checks sides and rings must be greater than zero', 'summarize_make_pair_range': 'summarize the _make_pair_range helper function that generates adjacent index pairs for face construction', 'test_torus_geometry': 'test the torus mesh generation by verifying vertex count equals sides multiplied by rings'}
```

