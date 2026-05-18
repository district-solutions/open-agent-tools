# Agent Python Tools

- repo: facebookresearch/minimax
- repo_uri: https://github.com/facebookresearch/minimax

## File: facebookresearch_minimax/src/minimax/envs/viz/grid_rendering.py

Prompts

```
['downsample a numpy image array by a given factor along both dimensions using mean pooling', 'fill pixels of an image with a color where coordinates match a filter function like a circle or line', 'rotate a coordinate filter function around a center point by a given theta angle in radians', 'create a predicate function that tests if a point lies inside a line, circle, rectangle, or triangle', 'add a semi-transparent color highlight overlay to a numpy image array with configurable alpha blending', 'render an EnvState instance to a window with optional highlight mask and tile size', 'render a numpy grid array to a window with optional rotation and agent direction', 'render a single grid tile image with caching and optional highlight overlay', 'render a full grid numpy array to an image with highlight mask and agent direction', 'save a screenshot of the current grid visualization window to a file path', 'create a Window instance with a title to draw a gridworld using Matplotlib', 'show or update an image in the Window using show_img with a numpy array', 'save the current Window image to a file path using save_img', 'set or update the caption text below the Window image using set_caption', 'register a keyboard event handler callback function with reg_key_handler on the Window']
```

Usage

```
{'downsample_image': 'downsample a numpy image array by a given factor along both dimensions using mean pooling', 'fill_coords_with_shape': 'fill pixels of an image with a color where coordinates match a filter function like a circle or line', 'rotate_filter_function': 'rotate a coordinate filter function around a center point by a given theta angle in radians', 'create_point_in_shape_fn': 'create a predicate function that tests if a point lies inside a line, circle, rectangle, or triangle', 'highlight_image': 'add a semi-transparent color highlight overlay to a numpy image array with configurable alpha blending'}
```

## File: facebookresearch_minimax/src/minimax/envs/viz/grid_viz.py

Prompts

```
['downsample a numpy image array by a given factor along both dimensions using mean pooling', 'fill pixels of an image with a color where coordinates match a filter function like a circle or line', 'rotate a coordinate filter function around a center point by a given theta angle in radians', 'create a predicate function that tests if a point lies inside a line, circle, rectangle, or triangle', 'add a semi-transparent color highlight overlay to a numpy image array with configurable alpha blending', 'render an EnvState instance to a window with optional highlight mask and tile size', 'render a numpy grid array to a window with optional rotation and agent direction', 'render a single grid tile image with caching and optional highlight overlay', 'render a full grid numpy array to an image with highlight mask and agent direction', 'save a screenshot of the current grid visualization window to a file path', 'create a Window instance with a title to draw a gridworld using Matplotlib', 'show or update an image in the Window using show_img with a numpy array', 'save the current Window image to a file path using save_img', 'set or update the caption text below the Window image using set_caption', 'register a keyboard event handler callback function with reg_key_handler on the Window']
```

Usage

```
{'render_env_state': 'render an EnvState instance to a window with optional highlight mask and tile size', 'render_grid_to_window': 'render a numpy grid array to a window with optional rotation and agent direction', 'render_tile_cached': 'render a single grid tile image with caching and optional highlight overlay', 'render_full_grid': 'render a full grid numpy array to an image with highlight mask and agent direction', 'take_screenshot': 'save a screenshot of the current grid visualization window to a file path'}
```

## File: facebookresearch_minimax/src/minimax/envs/viz/window.py

Prompts

```
['downsample a numpy image array by a given factor along both dimensions using mean pooling', 'fill pixels of an image with a color where coordinates match a filter function like a circle or line', 'rotate a coordinate filter function around a center point by a given theta angle in radians', 'create a predicate function that tests if a point lies inside a line, circle, rectangle, or triangle', 'add a semi-transparent color highlight overlay to a numpy image array with configurable alpha blending', 'render an EnvState instance to a window with optional highlight mask and tile size', 'render a numpy grid array to a window with optional rotation and agent direction', 'render a single grid tile image with caching and optional highlight overlay', 'render a full grid numpy array to an image with highlight mask and agent direction', 'save a screenshot of the current grid visualization window to a file path', 'create a Window instance with a title to draw a gridworld using Matplotlib', 'show or update an image in the Window using show_img with a numpy array', 'save the current Window image to a file path using save_img', 'set or update the caption text below the Window image using set_caption', 'register a keyboard event handler callback function with reg_key_handler on the Window']
```

Usage

```
{'create_Window': 'create a Window instance with a title to draw a gridworld using Matplotlib', 'show_img_Window': 'show or update an image in the Window using show_img with a numpy array', 'save_img_Window': 'save the current Window image to a file path using save_img', 'set_caption_Window': 'set or update the caption text below the Window image using set_caption', 'reg_key_handler_Window': 'register a keyboard event handler callback function with reg_key_handler on the Window'}
```

