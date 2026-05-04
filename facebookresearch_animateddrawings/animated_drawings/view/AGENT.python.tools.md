# Agent Python Tools

- repo: facebookresearch/animateddrawings
- repo_uri: https://github.com/facebookresearch/animateddrawings

## File: facebookresearch_animateddrawings/animated_drawings/view/mesa_view.py

Prompts

```
['create a MesaView instance with a ViewConfig for headless OpenGL rendering', 'render a Transform scene using MesaView with background image and shader support', 'initialize an OS Mesa context with RGBA buffer for offscreen rendering', 'prepare bvh, color, and texture shaders from GLSL source files for rendering', 'cleanup and destroy the OS Mesa context when rendering is complete', 'build a python module that computes a 4x4 perspective projection matrix given buffer width and height', 'create a function that generates a perspective projection matrix with a 35 degree FOV for 3D rendering', 'test the get_projection_matrix function by passing buffer dimensions and verifying the returned 4x4 numpy array', 'review the get_projection_matrix function to understand how it computes perspective projection with configurable buffer size', 'summarize the get_projection_matrix function that returns a numpy float32 4x4 perspective projection matrix', 'create a View instance from a ViewConfig using the create_view static factory method', 'render a scene by calling the render method on a View subclass instance', 'clear the previous render loop output by calling clear_window on a View instance', 'cleanup view resources after the render loop finishes by calling cleanup on a View instance', 'get the framebuffer width and height as a tuple by calling get_framebuffer_size on a View', 'create a WindowView instance with a ViewConfig to initialize an OpenGL rendering window', 'render a Transform scene into the WindowView with optional background image blitting', 'initialize bvh, color, and texture shader programs from GLSL vertex and fragment files', 'update all shader view matrices by inverting the camera world transform matrix', 'destroy the GLFW window and clean up OpenGL resources when rendering is complete']
```

Usage

```
{'create_mesa_view': 'create a MesaView instance with a ViewConfig for headless OpenGL rendering', 'render_scene_with_mesa': 'render a Transform scene using MesaView with background image and shader support', 'initialize_mesa_context': 'initialize an OS Mesa context with RGBA buffer for offscreen rendering', 'prepare_shaders_for_rendering': 'prepare bvh, color, and texture shaders from GLSL source files for rendering', 'cleanup_mesa_context': 'cleanup and destroy the OS Mesa context when rendering is complete'}
```

## File: facebookresearch_animateddrawings/animated_drawings/view/utils.py

Prompts

```
['create a MesaView instance with a ViewConfig for headless OpenGL rendering', 'render a Transform scene using MesaView with background image and shader support', 'initialize an OS Mesa context with RGBA buffer for offscreen rendering', 'prepare bvh, color, and texture shaders from GLSL source files for rendering', 'cleanup and destroy the OS Mesa context when rendering is complete', 'build a python module that computes a 4x4 perspective projection matrix given buffer width and height', 'create a function that generates a perspective projection matrix with a 35 degree FOV for 3D rendering', 'test the get_projection_matrix function by passing buffer dimensions and verifying the returned 4x4 numpy array', 'review the get_projection_matrix function to understand how it computes perspective projection with configurable buffer size', 'summarize the get_projection_matrix function that returns a numpy float32 4x4 perspective projection matrix', 'create a View instance from a ViewConfig using the create_view static factory method', 'render a scene by calling the render method on a View subclass instance', 'clear the previous render loop output by calling clear_window on a View instance', 'cleanup view resources after the render loop finishes by calling cleanup on a View instance', 'get the framebuffer width and height as a tuple by calling get_framebuffer_size on a View', 'create a WindowView instance with a ViewConfig to initialize an OpenGL rendering window', 'render a Transform scene into the WindowView with optional background image blitting', 'initialize bvh, color, and texture shader programs from GLSL vertex and fragment files', 'update all shader view matrices by inverting the camera world transform matrix', 'destroy the GLFW window and clean up OpenGL resources when rendering is complete']
```

Usage

```
{'build_perspective_projection_matrix': 'build a python module that computes a 4x4 perspective projection matrix given buffer width and height', 'create_projection_matrix_for_rendering': 'create a function that generates a perspective projection matrix with a 35 degree FOV for 3D rendering', 'test_get_projection_matrix': 'test the get_projection_matrix function by passing buffer dimensions and verifying the returned 4x4 numpy array', 'review_get_projection_matrix': 'review the get_projection_matrix function to understand how it computes perspective projection with configurable buffer size', 'summarize_get_projection_matrix': 'summarize the get_projection_matrix function that returns a numpy float32 4x4 perspective projection matrix'}
```

## File: facebookresearch_animateddrawings/animated_drawings/view/view.py

Prompts

```
['create a MesaView instance with a ViewConfig for headless OpenGL rendering', 'render a Transform scene using MesaView with background image and shader support', 'initialize an OS Mesa context with RGBA buffer for offscreen rendering', 'prepare bvh, color, and texture shaders from GLSL source files for rendering', 'cleanup and destroy the OS Mesa context when rendering is complete', 'build a python module that computes a 4x4 perspective projection matrix given buffer width and height', 'create a function that generates a perspective projection matrix with a 35 degree FOV for 3D rendering', 'test the get_projection_matrix function by passing buffer dimensions and verifying the returned 4x4 numpy array', 'review the get_projection_matrix function to understand how it computes perspective projection with configurable buffer size', 'summarize the get_projection_matrix function that returns a numpy float32 4x4 perspective projection matrix', 'create a View instance from a ViewConfig using the create_view static factory method', 'render a scene by calling the render method on a View subclass instance', 'clear the previous render loop output by calling clear_window on a View instance', 'cleanup view resources after the render loop finishes by calling cleanup on a View instance', 'get the framebuffer width and height as a tuple by calling get_framebuffer_size on a View', 'create a WindowView instance with a ViewConfig to initialize an OpenGL rendering window', 'render a Transform scene into the WindowView with optional background image blitting', 'initialize bvh, color, and texture shader programs from GLSL vertex and fragment files', 'update all shader view matrices by inverting the camera world transform matrix', 'destroy the GLFW window and clean up OpenGL resources when rendering is complete']
```

Usage

```
{'create_view_from_config': 'create a View instance from a ViewConfig using the create_view static factory method', 'render_scene_with_view': 'render a scene by calling the render method on a View subclass instance', 'clear_view_window': 'clear the previous render loop output by calling clear_window on a View instance', 'cleanup_view_resources': 'cleanup view resources after the render loop finishes by calling cleanup on a View instance', 'get_view_framebuffer_size': 'get the framebuffer width and height as a tuple by calling get_framebuffer_size on a View'}
```

## File: facebookresearch_animateddrawings/animated_drawings/view/window_view.py

Prompts

```
['create a MesaView instance with a ViewConfig for headless OpenGL rendering', 'render a Transform scene using MesaView with background image and shader support', 'initialize an OS Mesa context with RGBA buffer for offscreen rendering', 'prepare bvh, color, and texture shaders from GLSL source files for rendering', 'cleanup and destroy the OS Mesa context when rendering is complete', 'build a python module that computes a 4x4 perspective projection matrix given buffer width and height', 'create a function that generates a perspective projection matrix with a 35 degree FOV for 3D rendering', 'test the get_projection_matrix function by passing buffer dimensions and verifying the returned 4x4 numpy array', 'review the get_projection_matrix function to understand how it computes perspective projection with configurable buffer size', 'summarize the get_projection_matrix function that returns a numpy float32 4x4 perspective projection matrix', 'create a View instance from a ViewConfig using the create_view static factory method', 'render a scene by calling the render method on a View subclass instance', 'clear the previous render loop output by calling clear_window on a View instance', 'cleanup view resources after the render loop finishes by calling cleanup on a View instance', 'get the framebuffer width and height as a tuple by calling get_framebuffer_size on a View', 'create a WindowView instance with a ViewConfig to initialize an OpenGL rendering window', 'render a Transform scene into the WindowView with optional background image blitting', 'initialize bvh, color, and texture shader programs from GLSL vertex and fragment files', 'update all shader view matrices by inverting the camera world transform matrix', 'destroy the GLFW window and clean up OpenGL resources when rendering is complete']
```

Usage

```
{'create_windowview_instance': 'create a WindowView instance with a ViewConfig to initialize an OpenGL rendering window', 'render_scene_with_windowview': 'render a Transform scene into the WindowView with optional background image blitting', 'initiate_shader_programs': 'initialize bvh, color, and texture shader programs from GLSL vertex and fragment files', 'update_camera_view_transform': 'update all shader view matrices by inverting the camera world transform matrix', 'cleanup_windowview_resources': 'destroy the GLFW window and clean up OpenGL resources when rendering is complete'}
```

