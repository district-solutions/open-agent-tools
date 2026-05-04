# Agent Python Tools

- repo: facebookresearch/animateddrawings
- repo_uri: https://github.com/facebookresearch/animateddrawings

## File: facebookresearch_animateddrawings/animated_drawings/controller/controller.py

Prompts

```
['create a Controller instance from a ControllerConfig, Scene, and View using create_controller factory method', 'run the Controller game loop that handles update, render, tick, and user input steps', 'set a new Scene on an existing Controller instance using the set_scene method', 'set a new View on an existing Controller instance using the set_view method', 'review the Controller abstract base class and its required subclass methods for the game loop', 'create a VideoRenderController to non-interactively render an animated drawing scene into a video file', 'create a VideoWriter instance via the factory method to write .gif or .mp4 output files', 'use GIFWriter to render animated frames into a transparent looping GIF with Pillow', 'use MP4Writer to render animated frames into an MP4 video file with cv2.VideoWriter', 'review the VideoRenderController run loop methods that update, render, and capture frames from OpenGL']
```

Usage

```
{'create_controller_from_config': 'create a Controller instance from a ControllerConfig, Scene, and View using create_controller factory method', 'run_controller_game_loop': 'run the Controller game loop that handles update, render, tick, and user input steps', 'set_controller_scene': 'set a new Scene on an existing Controller instance using the set_scene method', 'set_controller_view': 'set a new View on an existing Controller instance using the set_view method', 'review_controller_abstract_methods': 'review the Controller abstract base class and its required subclass methods for the game loop'}
```

## File: facebookresearch_animateddrawings/animated_drawings/controller/video_render_controller.py

Prompts

```
['create a Controller instance from a ControllerConfig, Scene, and View using create_controller factory method', 'run the Controller game loop that handles update, render, tick, and user input steps', 'set a new Scene on an existing Controller instance using the set_scene method', 'set a new View on an existing Controller instance using the set_view method', 'review the Controller abstract base class and its required subclass methods for the game loop', 'create a VideoRenderController to non-interactively render an animated drawing scene into a video file', 'create a VideoWriter instance via the factory method to write .gif or .mp4 output files', 'use GIFWriter to render animated frames into a transparent looping GIF with Pillow', 'use MP4Writer to render animated frames into an MP4 video file with cv2.VideoWriter', 'review the VideoRenderController run loop methods that update, render, and capture frames from OpenGL']
```

Usage

```
{'create_video_render_controller': 'create a VideoRenderController to non-interactively render an animated drawing scene into a video file', 'create_video_writer': 'create a VideoWriter instance via the factory method to write .gif or .mp4 output files', 'render_gif_with_gifwriter': 'use GIFWriter to render animated frames into a transparent looping GIF with Pillow', 'render_mp4_with_mp4writer': 'use MP4Writer to render animated frames into an MP4 video file with cv2.VideoWriter', 'review_video_render_controller_run_loop': 'review the VideoRenderController run loop methods that update, render, and capture frames from OpenGL'}
```

