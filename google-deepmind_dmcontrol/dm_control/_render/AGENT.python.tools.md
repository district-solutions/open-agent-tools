# Agent Python Tools

- repo: google-deepmind/dmcontrol
- repo_uri: https://github.com/google-deepmind/dm_control

## File: google-deepmind_dmcontrol/dm_control/_render/base.py

Prompts

```
['create a ContextBase subclass to initialize an OpenGL rendering context with max width and height', 'use the make_current context manager to execute OpenGL calls on the dedicated rendering thread', 'free OpenGL context resources by calling free when the reference count reaches zero', 'convert a raw buffer to pixel format by calling to_pixels which flips the buffer vertically', 'manage context lifecycle with keep_alive and dont_keep_alive to track patient objects during rendering', 'test the ContextBase class initialization with max width and height parameters', 'test the ContextBase make_current context manager for activating a rendering context on the current thread', 'test that multiple ContextBase instances correctly track which context is current per thread', 'test the ContextBase free method to release the rendering context and clean up thread mappings', 'test the ContextBase increment_refcount and decrement_refcount methods to prevent premature context cleanup', 'test that _render.Renderer initializes with a mocked GLFW context correctly', 'test that renderer.make_current calls glfw.make_context_current with the context', 'test that renderer.free destroys the GLFW window and sets context to None', 'test repeatedly creating and destroying MjrContext with a Renderer in threaded mode', 'review the GLFWContextTest class and its four test methods for GLFW rendering']
```

Usage

```
{'create_opengl_context': 'create a ContextBase subclass to initialize an OpenGL rendering context with max width and height', 'use_make_current_context_manager': 'use the make_current context manager to execute OpenGL calls on the dedicated rendering thread', 'free_context_resources': 'free OpenGL context resources by calling free when the reference count reaches zero', 'convert_buffer_to_pixels': 'convert a raw buffer to pixel format by calling to_pixels which flips the buffer vertically', 'manage_context_lifecycle': 'manage context lifecycle with keep_alive and dont_keep_alive to track patient objects during rendering'}
```

## File: google-deepmind_dmcontrol/dm_control/_render/base_test.py

Prompts

```
['create a ContextBase subclass to initialize an OpenGL rendering context with max width and height', 'use the make_current context manager to execute OpenGL calls on the dedicated rendering thread', 'free OpenGL context resources by calling free when the reference count reaches zero', 'convert a raw buffer to pixel format by calling to_pixels which flips the buffer vertically', 'manage context lifecycle with keep_alive and dont_keep_alive to track patient objects during rendering', 'test the ContextBase class initialization with max width and height parameters', 'test the ContextBase make_current context manager for activating a rendering context on the current thread', 'test that multiple ContextBase instances correctly track which context is current per thread', 'test the ContextBase free method to release the rendering context and clean up thread mappings', 'test the ContextBase increment_refcount and decrement_refcount methods to prevent premature context cleanup', 'test that _render.Renderer initializes with a mocked GLFW context correctly', 'test that renderer.make_current calls glfw.make_context_current with the context', 'test that renderer.free destroys the GLFW window and sets context to None', 'test repeatedly creating and destroying MjrContext with a Renderer in threaded mode', 'review the GLFWContextTest class and its four test methods for GLFW rendering']
```

Usage

```
{'test_ContextBase_init': 'test the ContextBase class initialization with max width and height parameters', 'test_ContextBase_make_current': 'test the ContextBase make_current context manager for activating a rendering context on the current thread', 'test_ContextBase_thread_sharing': 'test that multiple ContextBase instances correctly track which context is current per thread', 'test_ContextBase_free': 'test the ContextBase free method to release the rendering context and clean up thread mappings', 'test_ContextBase_refcounting': 'test the ContextBase increment_refcount and decrement_refcount methods to prevent premature context cleanup'}
```

## File: google-deepmind_dmcontrol/dm_control/_render/glfw_renderer_test.py

Prompts

```
['create a ContextBase subclass to initialize an OpenGL rendering context with max width and height', 'use the make_current context manager to execute OpenGL calls on the dedicated rendering thread', 'free OpenGL context resources by calling free when the reference count reaches zero', 'convert a raw buffer to pixel format by calling to_pixels which flips the buffer vertically', 'manage context lifecycle with keep_alive and dont_keep_alive to track patient objects during rendering', 'test the ContextBase class initialization with max width and height parameters', 'test the ContextBase make_current context manager for activating a rendering context on the current thread', 'test that multiple ContextBase instances correctly track which context is current per thread', 'test the ContextBase free method to release the rendering context and clean up thread mappings', 'test the ContextBase increment_refcount and decrement_refcount methods to prevent premature context cleanup', 'test that _render.Renderer initializes with a mocked GLFW context correctly', 'test that renderer.make_current calls glfw.make_context_current with the context', 'test that renderer.free destroys the GLFW window and sets context to None', 'test repeatedly creating and destroying MjrContext with a Renderer in threaded mode', 'review the GLFWContextTest class and its four test methods for GLFW rendering']
```

Usage

```
{'test_renderer_init': 'test that _render.Renderer initializes with a mocked GLFW context correctly', 'test_renderer_make_current': 'test that renderer.make_current calls glfw.make_context_current with the context', 'test_renderer_freeing': 'test that renderer.free destroys the GLFW window and sets context to None', 'test_repeatedly_create_destroy_context': 'test repeatedly creating and destroying MjrContext with a Renderer in threaded mode', 'review_GLFWContextTest': 'review the GLFWContextTest class and its four test methods for GLFW rendering'}
```

