# Agent Python Tools

- repo: facebookresearch/deepbisim4control
- repo_uri: https://github.com/facebookresearch/deep_bisim4control

## File: facebookresearch_deepbisim4control/dmc2gym/natural_imgsource.py

Prompts

```
['create a FixedColorSource that returns a solid color RGB image of a given shape', 'create a RandomColorSource that generates a random solid color image and resets color each episode', 'create a NoiseSource that generates Gaussian noise images with configurable strength for a given shape', 'create a RandomImageSource that loads images from a file list and returns random frames on each call', 'create a RandomVideoSource that loads video frames from files and returns sequential frames on each call', 'create a DMCWrapper Gym environment from a DeepMind Control Suite domain and task name', 'run a step on the DMCWrapper environment with a normalized action and collect reward', 'reset the DMCWrapper environment and return the initial observation', 'render the DMCWrapper environment as an RGB array with configurable height, width, and camera', 'convert a DeepMind env observation or action spec into a Gym Box space']
```

Usage

```
{'create_fixed_color_image_source': 'create a FixedColorSource that returns a solid color RGB image of a given shape', 'create_random_color_image_source': 'create a RandomColorSource that generates a random solid color image and resets color each episode', 'create_noise_image_source': 'create a NoiseSource that generates Gaussian noise images with configurable strength for a given shape', 'create_random_image_source': 'create a RandomImageSource that loads images from a file list and returns random frames on each call', 'create_random_video_source': 'create a RandomVideoSource that loads video frames from files and returns sequential frames on each call'}
```

## File: facebookresearch_deepbisim4control/dmc2gym/wrappers.py

Prompts

```
['create a FixedColorSource that returns a solid color RGB image of a given shape', 'create a RandomColorSource that generates a random solid color image and resets color each episode', 'create a NoiseSource that generates Gaussian noise images with configurable strength for a given shape', 'create a RandomImageSource that loads images from a file list and returns random frames on each call', 'create a RandomVideoSource that loads video frames from files and returns sequential frames on each call', 'create a DMCWrapper Gym environment from a DeepMind Control Suite domain and task name', 'run a step on the DMCWrapper environment with a normalized action and collect reward', 'reset the DMCWrapper environment and return the initial observation', 'render the DMCWrapper environment as an RGB array with configurable height, width, and camera', 'convert a DeepMind env observation or action spec into a Gym Box space']
```

Usage

```
{'create_DMCWrapper_env': 'create a DMCWrapper Gym environment from a DeepMind Control Suite domain and task name', 'run_DMCWrapper_step': 'run a step on the DMCWrapper environment with a normalized action and collect reward', 'reset_DMCWrapper': 'reset the DMCWrapper environment and return the initial observation', 'render_DMCWrapper_rgb': 'render the DMCWrapper environment as an RGB array with configurable height, width, and camera', 'convert_spec_to_box': 'convert a DeepMind env observation or action spec into a Gym Box space'}
```

