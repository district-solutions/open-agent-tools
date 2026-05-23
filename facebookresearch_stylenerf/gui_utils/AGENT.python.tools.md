# Agent Python Tools

- repo: facebookresearch/stylenerf
- repo_uri: https://github.com/facebookresearch/stylenerf

## File: facebookresearch_stylenerf/gui_utils/gl_utils.py

Prompts

```
['initialize an EGL display and OpenGL context for headless GPU rendering without a window server', 'create a GPU texture from a numpy image array with optional bilinear filtering and mipmapping', 'create an offscreen framebuffer with optional MSAA multisampling and a depth stencil buffer', 'draw raw pixel data from a numpy array onto the OpenGL canvas at a given position and zoom', 'draw a colored rectangle with optional rounded corners at a specified position and size on the canvas', 'create a GlfwWindow instance with custom title, width, and height for OpenGL rendering', 'override draw_frame in a subclass to render OpenGL content between begin_frame and end_frame calls', 'call capture_next_frame then pop_captured_frame to grab the rendered frame as pixel data', 'use set_window_size to resize the window and center to position it on the monitor', 'use skip_frames to pause rendering and set_fps_limit to cap the frame rate', 'set the default imgui style with a dark color scheme, custom spacing, and scrollbar size', 'use the grayed_out context manager to disable and gray out imgui UI elements conditionally', 'create an imgui button that supports an enabled flag to gray out and disable clicks', 'build a collapsible header section with optional default open, enabled, and visibility flags', 'create a draggable imgui button that returns click state, drag state, and mouse drag delta', 'create an ImguiWindow instance with a custom title and font sizes for a Dear ImGui GUI', 'close the ImguiWindow and shut down the ImGui renderer and context cleanly', 'set the font size on an ImguiWindow to the nearest available size applied on next frame', 'begin a new ImGui frame by processing inputs and pushing the current font and style', 'end the current ImGui frame by rendering draw data and swapping the GLFW buffer', 'render a text string into a numpy array with optional dropshadow and size constraints', 'create a GL texture from a text string with bilinear filtering and mipmap support', 'load a PIL TrueType font with a specified size or use the default Open Sans font', 'download and return the default Open Sans font file from Google Fonts', 'render text with an outline effect using gaussian blur and configurable outline parameters']
```

Usage

```
{'init_egl': 'initialize an EGL display and OpenGL context for headless GPU rendering without a window server', 'create_Texture': 'create a GPU texture from a numpy image array with optional bilinear filtering and mipmapping', 'create_Framebuffer': 'create an offscreen framebuffer with optional MSAA multisampling and a depth stencil buffer', 'draw_pixels': 'draw raw pixel data from a numpy array onto the OpenGL canvas at a given position and zoom', 'draw_rect': 'draw a colored rectangle with optional rounded corners at a specified position and size on the canvas'}
```

## File: facebookresearch_stylenerf/gui_utils/glfw_window.py

Prompts

```
['initialize an EGL display and OpenGL context for headless GPU rendering without a window server', 'create a GPU texture from a numpy image array with optional bilinear filtering and mipmapping', 'create an offscreen framebuffer with optional MSAA multisampling and a depth stencil buffer', 'draw raw pixel data from a numpy array onto the OpenGL canvas at a given position and zoom', 'draw a colored rectangle with optional rounded corners at a specified position and size on the canvas', 'create a GlfwWindow instance with custom title, width, and height for OpenGL rendering', 'override draw_frame in a subclass to render OpenGL content between begin_frame and end_frame calls', 'call capture_next_frame then pop_captured_frame to grab the rendered frame as pixel data', 'use set_window_size to resize the window and center to position it on the monitor', 'use skip_frames to pause rendering and set_fps_limit to cap the frame rate', 'set the default imgui style with a dark color scheme, custom spacing, and scrollbar size', 'use the grayed_out context manager to disable and gray out imgui UI elements conditionally', 'create an imgui button that supports an enabled flag to gray out and disable clicks', 'build a collapsible header section with optional default open, enabled, and visibility flags', 'create a draggable imgui button that returns click state, drag state, and mouse drag delta', 'create an ImguiWindow instance with a custom title and font sizes for a Dear ImGui GUI', 'close the ImguiWindow and shut down the ImGui renderer and context cleanly', 'set the font size on an ImguiWindow to the nearest available size applied on next frame', 'begin a new ImGui frame by processing inputs and pushing the current font and style', 'end the current ImGui frame by rendering draw data and swapping the GLFW buffer', 'render a text string into a numpy array with optional dropshadow and size constraints', 'create a GL texture from a text string with bilinear filtering and mipmap support', 'load a PIL TrueType font with a specified size or use the default Open Sans font', 'download and return the default Open Sans font file from Google Fonts', 'render text with an outline effect using gaussian blur and configurable outline parameters']
```

Usage

```
{'create_glfw_window': 'create a GlfwWindow instance with custom title, width, and height for OpenGL rendering', 'draw_frame_begin_end': 'override draw_frame in a subclass to render OpenGL content between begin_frame and end_frame calls', 'capture_next_frame': 'call capture_next_frame then pop_captured_frame to grab the rendered frame as pixel data', 'set_window_size_and_center': 'use set_window_size to resize the window and center to position it on the monitor', 'skip_frames_and_set_fps_limit': 'use skip_frames to pause rendering and set_fps_limit to cap the frame rate'}
```

## File: facebookresearch_stylenerf/gui_utils/imgui_utils.py

Prompts

```
['initialize an EGL display and OpenGL context for headless GPU rendering without a window server', 'create a GPU texture from a numpy image array with optional bilinear filtering and mipmapping', 'create an offscreen framebuffer with optional MSAA multisampling and a depth stencil buffer', 'draw raw pixel data from a numpy array onto the OpenGL canvas at a given position and zoom', 'draw a colored rectangle with optional rounded corners at a specified position and size on the canvas', 'create a GlfwWindow instance with custom title, width, and height for OpenGL rendering', 'override draw_frame in a subclass to render OpenGL content between begin_frame and end_frame calls', 'call capture_next_frame then pop_captured_frame to grab the rendered frame as pixel data', 'use set_window_size to resize the window and center to position it on the monitor', 'use skip_frames to pause rendering and set_fps_limit to cap the frame rate', 'set the default imgui style with a dark color scheme, custom spacing, and scrollbar size', 'use the grayed_out context manager to disable and gray out imgui UI elements conditionally', 'create an imgui button that supports an enabled flag to gray out and disable clicks', 'build a collapsible header section with optional default open, enabled, and visibility flags', 'create a draggable imgui button that returns click state, drag state, and mouse drag delta', 'create an ImguiWindow instance with a custom title and font sizes for a Dear ImGui GUI', 'close the ImguiWindow and shut down the ImGui renderer and context cleanly', 'set the font size on an ImguiWindow to the nearest available size applied on next frame', 'begin a new ImGui frame by processing inputs and pushing the current font and style', 'end the current ImGui frame by rendering draw data and swapping the GLFW buffer', 'render a text string into a numpy array with optional dropshadow and size constraints', 'create a GL texture from a text string with bilinear filtering and mipmap support', 'load a PIL TrueType font with a specified size or use the default Open Sans font', 'download and return the default Open Sans font file from Google Fonts', 'render text with an outline effect using gaussian blur and configurable outline parameters']
```

Usage

```
{'set_default_style': 'set the default imgui style with a dark color scheme, custom spacing, and scrollbar size', 'grayed_out_context_manager': 'use the grayed_out context manager to disable and gray out imgui UI elements conditionally', 'button_with_enabled': 'create an imgui button that supports an enabled flag to gray out and disable clicks', 'collapsing_header_with_flags': 'build a collapsible header section with optional default open, enabled, and visibility flags', 'drag_button_with_delta': 'create a draggable imgui button that returns click state, drag state, and mouse drag delta'}
```

## File: facebookresearch_stylenerf/gui_utils/imgui_window.py

Prompts

```
['initialize an EGL display and OpenGL context for headless GPU rendering without a window server', 'create a GPU texture from a numpy image array with optional bilinear filtering and mipmapping', 'create an offscreen framebuffer with optional MSAA multisampling and a depth stencil buffer', 'draw raw pixel data from a numpy array onto the OpenGL canvas at a given position and zoom', 'draw a colored rectangle with optional rounded corners at a specified position and size on the canvas', 'create a GlfwWindow instance with custom title, width, and height for OpenGL rendering', 'override draw_frame in a subclass to render OpenGL content between begin_frame and end_frame calls', 'call capture_next_frame then pop_captured_frame to grab the rendered frame as pixel data', 'use set_window_size to resize the window and center to position it on the monitor', 'use skip_frames to pause rendering and set_fps_limit to cap the frame rate', 'set the default imgui style with a dark color scheme, custom spacing, and scrollbar size', 'use the grayed_out context manager to disable and gray out imgui UI elements conditionally', 'create an imgui button that supports an enabled flag to gray out and disable clicks', 'build a collapsible header section with optional default open, enabled, and visibility flags', 'create a draggable imgui button that returns click state, drag state, and mouse drag delta', 'create an ImguiWindow instance with a custom title and font sizes for a Dear ImGui GUI', 'close the ImguiWindow and shut down the ImGui renderer and context cleanly', 'set the font size on an ImguiWindow to the nearest available size applied on next frame', 'begin a new ImGui frame by processing inputs and pushing the current font and style', 'end the current ImGui frame by rendering draw data and swapping the GLFW buffer', 'render a text string into a numpy array with optional dropshadow and size constraints', 'create a GL texture from a text string with bilinear filtering and mipmap support', 'load a PIL TrueType font with a specified size or use the default Open Sans font', 'download and return the default Open Sans font file from Google Fonts', 'render text with an outline effect using gaussian blur and configurable outline parameters']
```

Usage

```
{'create_ImguiWindow': 'create an ImguiWindow instance with a custom title and font sizes for a Dear ImGui GUI', 'close_ImguiWindow': 'close the ImguiWindow and shut down the ImGui renderer and context cleanly', 'set_font_size_ImguiWindow': 'set the font size on an ImguiWindow to the nearest available size applied on next frame', 'begin_frame_ImguiWindow': 'begin a new ImGui frame by processing inputs and pushing the current font and style', 'end_frame_ImguiWindow': 'end the current ImGui frame by rendering draw data and swapping the GLFW buffer'}
```

## File: facebookresearch_stylenerf/gui_utils/text_utils.py

Prompts

```
['initialize an EGL display and OpenGL context for headless GPU rendering without a window server', 'create a GPU texture from a numpy image array with optional bilinear filtering and mipmapping', 'create an offscreen framebuffer with optional MSAA multisampling and a depth stencil buffer', 'draw raw pixel data from a numpy array onto the OpenGL canvas at a given position and zoom', 'draw a colored rectangle with optional rounded corners at a specified position and size on the canvas', 'create a GlfwWindow instance with custom title, width, and height for OpenGL rendering', 'override draw_frame in a subclass to render OpenGL content between begin_frame and end_frame calls', 'call capture_next_frame then pop_captured_frame to grab the rendered frame as pixel data', 'use set_window_size to resize the window and center to position it on the monitor', 'use skip_frames to pause rendering and set_fps_limit to cap the frame rate', 'set the default imgui style with a dark color scheme, custom spacing, and scrollbar size', 'use the grayed_out context manager to disable and gray out imgui UI elements conditionally', 'create an imgui button that supports an enabled flag to gray out and disable clicks', 'build a collapsible header section with optional default open, enabled, and visibility flags', 'create a draggable imgui button that returns click state, drag state, and mouse drag delta', 'create an ImguiWindow instance with a custom title and font sizes for a Dear ImGui GUI', 'close the ImguiWindow and shut down the ImGui renderer and context cleanly', 'set the font size on an ImguiWindow to the nearest available size applied on next frame', 'begin a new ImGui frame by processing inputs and pushing the current font and style', 'end the current ImGui frame by rendering draw data and swapping the GLFW buffer', 'render a text string into a numpy array with optional dropshadow and size constraints', 'create a GL texture from a text string with bilinear filtering and mipmap support', 'load a PIL TrueType font with a specified size or use the default Open Sans font', 'download and return the default Open Sans font file from Google Fonts', 'render text with an outline effect using gaussian blur and configurable outline parameters']
```

Usage

```
{'get_array_render_text': 'render a text string into a numpy array with optional dropshadow and size constraints', 'get_texture_create_text_texture': 'create a GL texture from a text string with bilinear filtering and mipmap support', 'get_pil_font_load_font': 'load a PIL TrueType font with a specified size or use the default Open Sans font', 'get_default_font_download_font': 'download and return the default Open Sans font file from Google Fonts', 'get_array_outline_text': 'render text with an outline effect using gaussian blur and configurable outline parameters'}
```

