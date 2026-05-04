# Agent Python Tools

- repo: facebookresearch/4dgt
- repo_uri: https://github.com/facebookresearch/4dgt

## File: facebookresearch_4dgt/tlod/splatsviewer/_renderer.py

Prompts

```
['create a Renderer background thread to render 3D images for a viser viewer client', 'submit a RenderTask with action move static update or rerender to the Renderer queue', 'define the state machine transitions between low_move low_static and high render states', 'get the width and height for rendering based on camera aspect ratio and max resolution', 'create a set_trace_context to enable line-level tracing for interrupting long-running renders', 'create a CameraPath instance with a ViserServer and duration element to manage camera keyframes and spline interpolation', 'add a Keyframe to the CameraPath using add_camera to set a new camera position and orientation in the render trajectory', 'interpolate camera pose and FOV at a normalized time using CameraPath.interpolate_pose_and_fov_rad for smooth camera animation', 'apply a colormap like viridis or turbo to a single channel tensor image using apply_float_colormap to produce an RGB tensor', 'populate a Viser GUI render tab with controls for keyframes, FOV, resolution, spline tension, and video export using populate_general_render_tab', 'create a Viewer instance bound to a viser server with a render function in rendering or training mode', 'get the CameraState including fov, aspect ratio, and camera-to-world matrix from a viser client handle', 'compute the 3x3 camera intrinsic matrix K from a CameraState given an image width and height tuple', 'trigger a rerender task for all connected clients by submitting RenderTask with current camera states', 'update the training viewer at a given step with the number of training rays per step to balance train and view throughput']
```

Usage

```
{'create_renderer_thread': 'create a Renderer background thread to render 3D images for a viser viewer client', 'submit_render_task': 'submit a RenderTask with action move static update or rerender to the Renderer queue', 'define_render_transitions': 'define the state machine transitions between low_move low_static and high render states', 'get_image_dimensions': 'get the width and height for rendering based on camera aspect ratio and max resolution', 'create_interrupt_trace_context': 'create a set_trace_context to enable line-level tracing for interrupting long-running renders'}
```

## File: facebookresearch_4dgt/tlod/splatsviewer/render_panel.py

Prompts

```
['create a Renderer background thread to render 3D images for a viser viewer client', 'submit a RenderTask with action move static update or rerender to the Renderer queue', 'define the state machine transitions between low_move low_static and high render states', 'get the width and height for rendering based on camera aspect ratio and max resolution', 'create a set_trace_context to enable line-level tracing for interrupting long-running renders', 'create a CameraPath instance with a ViserServer and duration element to manage camera keyframes and spline interpolation', 'add a Keyframe to the CameraPath using add_camera to set a new camera position and orientation in the render trajectory', 'interpolate camera pose and FOV at a normalized time using CameraPath.interpolate_pose_and_fov_rad for smooth camera animation', 'apply a colormap like viridis or turbo to a single channel tensor image using apply_float_colormap to produce an RGB tensor', 'populate a Viser GUI render tab with controls for keyframes, FOV, resolution, spline tension, and video export using populate_general_render_tab', 'create a Viewer instance bound to a viser server with a render function in rendering or training mode', 'get the CameraState including fov, aspect ratio, and camera-to-world matrix from a viser client handle', 'compute the 3x3 camera intrinsic matrix K from a CameraState given an image width and height tuple', 'trigger a rerender task for all connected clients by submitting RenderTask with current camera states', 'update the training viewer at a given step with the number of training rays per step to balance train and view throughput']
```

Usage

```
{'create_camera_path': 'create a CameraPath instance with a ViserServer and duration element to manage camera keyframes and spline interpolation', 'add_camera_keyframe': 'add a Keyframe to the CameraPath using add_camera to set a new camera position and orientation in the render trajectory', 'interpolate_pose_and_fov': 'interpolate camera pose and FOV at a normalized time using CameraPath.interpolate_pose_and_fov_rad for smooth camera animation', 'apply_float_colormap': 'apply a colormap like viridis or turbo to a single channel tensor image using apply_float_colormap to produce an RGB tensor', 'populate_general_render_tab': 'populate a Viser GUI render tab with controls for keyframes, FOV, resolution, spline tension, and video export using populate_general_render_tab'}
```

## File: facebookresearch_4dgt/tlod/splatsviewer/viewer.py

Prompts

```
['create a Renderer background thread to render 3D images for a viser viewer client', 'submit a RenderTask with action move static update or rerender to the Renderer queue', 'define the state machine transitions between low_move low_static and high render states', 'get the width and height for rendering based on camera aspect ratio and max resolution', 'create a set_trace_context to enable line-level tracing for interrupting long-running renders', 'create a CameraPath instance with a ViserServer and duration element to manage camera keyframes and spline interpolation', 'add a Keyframe to the CameraPath using add_camera to set a new camera position and orientation in the render trajectory', 'interpolate camera pose and FOV at a normalized time using CameraPath.interpolate_pose_and_fov_rad for smooth camera animation', 'apply a colormap like viridis or turbo to a single channel tensor image using apply_float_colormap to produce an RGB tensor', 'populate a Viser GUI render tab with controls for keyframes, FOV, resolution, spline tension, and video export using populate_general_render_tab', 'create a Viewer instance bound to a viser server with a render function in rendering or training mode', 'get the CameraState including fov, aspect ratio, and camera-to-world matrix from a viser client handle', 'compute the 3x3 camera intrinsic matrix K from a CameraState given an image width and height tuple', 'trigger a rerender task for all connected clients by submitting RenderTask with current camera states', 'update the training viewer at a given step with the number of training rays per step to balance train and view throughput']
```

Usage

```
{'create_viewer_instance': 'create a Viewer instance bound to a viser server with a render function in rendering or training mode', 'get_camera_state': 'get the CameraState including fov, aspect ratio, and camera-to-world matrix from a viser client handle', 'compute_camera_intrinsics': 'compute the 3x3 camera intrinsic matrix K from a CameraState given an image width and height tuple', 'rerender_all_clients': 'trigger a rerender task for all connected clients by submitting RenderTask with current camera states', 'update_training_viewer': 'update the training viewer at a given step with the number of training rays per step to balance train and view throughput'}
```

