# Agent Python Tools

- repo: facebookresearch/pytorch3d
- repo_uri: https://github.com/facebookresearch/pytorch3d.git

## File: facebookresearch_pytorch3d/pytorch3d/renderer/opengl/opengl_utils.py

Prompts

```
['create an EGL context for headless OpenGL rendering on a specified CUDA device with given width and height', 'use the EGL context active_and_locked context manager to safely make the context current in the current thread', 'get or create a cached EGL context from the global device context store for a given CUDA device', 'get or create a cached pycuda CUDA context from the global device context store for a given device', 'release all cached CUDA and EGL contexts in the global device context store to free GPU resources', 'rasterize a batch of 3D meshes using OpenGL via MeshRasterizerOpenGL with FoVPerspectiveCameras', 'compile and link vertex, geometry, and fragment shaders into an OpenGL program for mesh rasterization', 'convert world-coordinate meshes to OpenGL NDC coordinates with proper aspect ratio scaling', 'initialize EGL context, CUDA context, and OpenGL buffer objects for a specific GPU device', 'release CUDA and OpenGL resources including framebuffers, buffers, and shader programs']
```

Usage

```
{'create_EGLContext': 'create an EGL context for headless OpenGL rendering on a specified CUDA device with given width and height', 'use_EGLContext_active_and_locked': 'use the EGL context active_and_locked context manager to safely make the context current in the current thread', 'get_EGLContext_from_store': 'get or create a cached EGL context from the global device context store for a given CUDA device', 'get_CUDA_context_from_store': 'get or create a cached pycuda CUDA context from the global device context store for a given device', 'release_device_context_store': 'release all cached CUDA and EGL contexts in the global device context store to free GPU resources'}
```

## File: facebookresearch_pytorch3d/pytorch3d/renderer/opengl/rasterizer_opengl.py

Prompts

```
['create an EGL context for headless OpenGL rendering on a specified CUDA device with given width and height', 'use the EGL context active_and_locked context manager to safely make the context current in the current thread', 'get or create a cached EGL context from the global device context store for a given CUDA device', 'get or create a cached pycuda CUDA context from the global device context store for a given device', 'release all cached CUDA and EGL contexts in the global device context store to free GPU resources', 'rasterize a batch of 3D meshes using OpenGL via MeshRasterizerOpenGL with FoVPerspectiveCameras', 'compile and link vertex, geometry, and fragment shaders into an OpenGL program for mesh rasterization', 'convert world-coordinate meshes to OpenGL NDC coordinates with proper aspect ratio scaling', 'initialize EGL context, CUDA context, and OpenGL buffer objects for a specific GPU device', 'release CUDA and OpenGL resources including framebuffers, buffers, and shader programs']
```

Usage

```
{'rasterize_meshes_opengl': 'rasterize a batch of 3D meshes using OpenGL via MeshRasterizerOpenGL with FoVPerspectiveCameras', 'compile_gl_program': 'compile and link vertex, geometry, and fragment shaders into an OpenGL program for mesh rasterization', 'convert_meshes_to_gl_ndc': 'convert world-coordinate meshes to OpenGL NDC coordinates with proper aspect ratio scaling', 'initialize_opengl_device_data': 'initialize EGL context, CUDA context, and OpenGL buffer objects for a specific GPU device', 'release_opengl_resources': 'release CUDA and OpenGL resources including framebuffers, buffers, and shader programs'}
```

