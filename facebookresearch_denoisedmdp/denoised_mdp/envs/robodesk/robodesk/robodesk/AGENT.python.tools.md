# Agent Python Tools

- repo: facebookresearch/denoisedmdp
- repo_uri: https://github.com/facebookresearch/denoised_mdp

## File: facebookresearch_denoisedmdp/denoised_mdp/envs/robodesk/robodesk/robodesk/robodesk.py

Prompts

```
['create a RoboDesk gym environment with a specified task like open_slide or stack', 'create a RoboDeskWithTV gym environment that includes a TV playing video distractors', 'run a single step in the RoboDesk environment by passing an action and getting observations', 'reset the RoboDesk environment to a fresh state with randomized object positions', 'render the RoboDesk environment as an RGB array image at the configured size', 'create a NumPyRNGWrapper instance with a seed to manage random number generation across NumPy versions', 'build a function that converts a dm_control Pose object into a camera lookfrom position array', 'create a function that constructs a dm_control Pose from camera lookfrom and lookat position arrays', 'build a SmoothRandomWalker iterator that generates smooth random N-dimensional walk coordinates with configurable pull and decay', 'create a CameraManager instance to handle noisy camera rendering with jittering for a RoboDesk environment', 'create a RandomVideoSource that loads frames from video files with contrast and sharpening', 'process a video frame by resizing and applying contrast change and sharpening filters', 'seed a RandomVideoSource with a specific random seed for reproducible frame selection', 'create a ConcatRollingImageSource that concatenates multiple image sources along an axis', 'step a video source to advance to the next frame in the loaded frame buffer']
```

Usage

```
{'create_robodesk_env': 'create a RoboDesk gym environment with a specified task like open_slide or stack', 'create_robodesk_with_tv_env': 'create a RoboDeskWithTV gym environment that includes a TV playing video distractors', 'run_robodesk_step': 'run a single step in the RoboDesk environment by passing an action and getting observations', 'reset_robodesk_env': 'reset the RoboDesk environment to a fresh state with randomized object positions', 'render_robodesk_observation': 'render the RoboDesk environment as an RGB array image at the configured size'}
```

## File: facebookresearch_denoisedmdp/denoised_mdp/envs/robodesk/robodesk/robodesk/utils.py

Prompts

```
['create a RoboDesk gym environment with a specified task like open_slide or stack', 'create a RoboDeskWithTV gym environment that includes a TV playing video distractors', 'run a single step in the RoboDesk environment by passing an action and getting observations', 'reset the RoboDesk environment to a fresh state with randomized object positions', 'render the RoboDesk environment as an RGB array image at the configured size', 'create a NumPyRNGWrapper instance with a seed to manage random number generation across NumPy versions', 'build a function that converts a dm_control Pose object into a camera lookfrom position array', 'create a function that constructs a dm_control Pose from camera lookfrom and lookat position arrays', 'build a SmoothRandomWalker iterator that generates smooth random N-dimensional walk coordinates with configurable pull and decay', 'create a CameraManager instance to handle noisy camera rendering with jittering for a RoboDesk environment', 'create a RandomVideoSource that loads frames from video files with contrast and sharpening', 'process a video frame by resizing and applying contrast change and sharpening filters', 'seed a RandomVideoSource with a specific random seed for reproducible frame selection', 'create a ConcatRollingImageSource that concatenates multiple image sources along an axis', 'step a video source to advance to the next frame in the loaded frame buffer']
```

Usage

```
{'create_numpy_rng_wrapper': 'create a NumPyRNGWrapper instance with a seed to manage random number generation across NumPy versions', 'convert_pose_to_lookfrom': 'build a function that converts a dm_control Pose object into a camera lookfrom position array', 'convert_lookfrom_to_pose': 'create a function that constructs a dm_control Pose from camera lookfrom and lookat position arrays', 'create_smooth_random_walker': 'build a SmoothRandomWalker iterator that generates smooth random N-dimensional walk coordinates with configurable pull and decay', 'create_camera_manager': 'create a CameraManager instance to handle noisy camera rendering with jittering for a RoboDesk environment'}
```

## File: facebookresearch_denoisedmdp/denoised_mdp/envs/robodesk/robodesk/robodesk/video_source.py

Prompts

```
['create a RoboDesk gym environment with a specified task like open_slide or stack', 'create a RoboDeskWithTV gym environment that includes a TV playing video distractors', 'run a single step in the RoboDesk environment by passing an action and getting observations', 'reset the RoboDesk environment to a fresh state with randomized object positions', 'render the RoboDesk environment as an RGB array image at the configured size', 'create a NumPyRNGWrapper instance with a seed to manage random number generation across NumPy versions', 'build a function that converts a dm_control Pose object into a camera lookfrom position array', 'create a function that constructs a dm_control Pose from camera lookfrom and lookat position arrays', 'build a SmoothRandomWalker iterator that generates smooth random N-dimensional walk coordinates with configurable pull and decay', 'create a CameraManager instance to handle noisy camera rendering with jittering for a RoboDesk environment', 'create a RandomVideoSource that loads frames from video files with contrast and sharpening', 'process a video frame by resizing and applying contrast change and sharpening filters', 'seed a RandomVideoSource with a specific random seed for reproducible frame selection', 'create a ConcatRollingImageSource that concatenates multiple image sources along an axis', 'step a video source to advance to the next frame in the loaded frame buffer']
```

Usage

```
{'create_random_video_source': 'create a RandomVideoSource that loads frames from video files with contrast and sharpening', 'process_frame_resize_and_enhance': 'process a video frame by resizing and applying contrast change and sharpening filters', 'seed_random_video_source': 'seed a RandomVideoSource with a specific random seed for reproducible frame selection', 'concatenate_image_sources': 'create a ConcatRollingImageSource that concatenates multiple image sources along an axis', 'step_video_source_frames': 'step a video source to advance to the next frame in the loaded frame buffer'}
```

