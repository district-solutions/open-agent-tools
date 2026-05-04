# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/habitat-lab/habitat_baselines/utils/common.py

Prompts

```
['batch a list of observation dicts into a TensorDict for GPU transfer in RL training', 'build a CategoricalNet module that maps inputs to a categorical action distribution for discrete RL', 'build a GaussianNet module that maps inputs to a normal action distribution for continuous RL', 'generate a video from a list of numpy images and save to disk or TensorBoard', 'resize an image tensor so its shortest edge matches a target size while preserving aspect ratio', 'create a Habitat environment instance from a Config object and env class using make_env_fn', 'construct a VectorEnv with multiple parallel environments split across scenes using construct_envs', 'split dataset scenes across multiple worker environments for parallel simulation using construct_envs', 'review the make_env_fn function to understand how it creates individual Habitat environments with dataset and seed', 'review the construct_envs function to understand scene splitting and per-worker config cloning logic', 'wrap a Habitat RLEnv into an OpenAI Gym compatible environment using HabGymWrapper', 'create a function that recursively flattens a nested dictionary into a single level with concatenated keys', 'build a gym Box space by smashing together multiple 1D observation spaces into one flattened space', 'run a step on the Gym-wrapped Habitat environment with a numpy array action and get observations', 'render the last Habitat observation as an RGB array image using the HabGymWrapper render method', 'append lines of text underneath a numpy image array using OpenCV putText', 'overlay flattened info dictionary values as text lines on a rendered frame image', 'create a HabRenderWrapper gym wrapper that overlays measure values on rendered frames', 'step the wrapped gym environment while tracking accumulated reward and step count', 'render the wrapped environment frame with overlaid step count and total reward text']
```

Usage

```
{'batch_observations_for_rl': 'batch a list of observation dicts into a TensorDict for GPU transfer in RL training', 'create_categorical_policy_head': 'build a CategoricalNet module that maps inputs to a categorical action distribution for discrete RL', 'create_gaussian_policy_head': 'build a GaussianNet module that maps inputs to a normal action distribution for continuous RL', 'generate_video_from_images': 'generate a video from a list of numpy images and save to disk or TensorBoard', 'resize_image_shortest_edge': 'resize an image tensor so its shortest edge matches a target size while preserving aspect ratio'}
```

## File: facebookresearch_eai-vc/third_party/habitat-lab/habitat_baselines/utils/env_utils.py

Prompts

```
['batch a list of observation dicts into a TensorDict for GPU transfer in RL training', 'build a CategoricalNet module that maps inputs to a categorical action distribution for discrete RL', 'build a GaussianNet module that maps inputs to a normal action distribution for continuous RL', 'generate a video from a list of numpy images and save to disk or TensorBoard', 'resize an image tensor so its shortest edge matches a target size while preserving aspect ratio', 'create a Habitat environment instance from a Config object and env class using make_env_fn', 'construct a VectorEnv with multiple parallel environments split across scenes using construct_envs', 'split dataset scenes across multiple worker environments for parallel simulation using construct_envs', 'review the make_env_fn function to understand how it creates individual Habitat environments with dataset and seed', 'review the construct_envs function to understand scene splitting and per-worker config cloning logic', 'wrap a Habitat RLEnv into an OpenAI Gym compatible environment using HabGymWrapper', 'create a function that recursively flattens a nested dictionary into a single level with concatenated keys', 'build a gym Box space by smashing together multiple 1D observation spaces into one flattened space', 'run a step on the Gym-wrapped Habitat environment with a numpy array action and get observations', 'render the last Habitat observation as an RGB array image using the HabGymWrapper render method', 'append lines of text underneath a numpy image array using OpenCV putText', 'overlay flattened info dictionary values as text lines on a rendered frame image', 'create a HabRenderWrapper gym wrapper that overlays measure values on rendered frames', 'step the wrapped gym environment while tracking accumulated reward and step count', 'render the wrapped environment frame with overlaid step count and total reward text']
```

Usage

```
{'create_env_from_config': 'create a Habitat environment instance from a Config object and env class using make_env_fn', 'construct_vector_envs': 'construct a VectorEnv with multiple parallel environments split across scenes using construct_envs', 'split_scenes_across_workers': 'split dataset scenes across multiple worker environments for parallel simulation using construct_envs', 'review_make_env_fn': 'review the make_env_fn function to understand how it creates individual Habitat environments with dataset and seed', 'review_construct_envs': 'review the construct_envs function to understand scene splitting and per-worker config cloning logic'}
```

## File: facebookresearch_eai-vc/third_party/habitat-lab/habitat_baselines/utils/gym_adapter.py

Prompts

```
['batch a list of observation dicts into a TensorDict for GPU transfer in RL training', 'build a CategoricalNet module that maps inputs to a categorical action distribution for discrete RL', 'build a GaussianNet module that maps inputs to a normal action distribution for continuous RL', 'generate a video from a list of numpy images and save to disk or TensorBoard', 'resize an image tensor so its shortest edge matches a target size while preserving aspect ratio', 'create a Habitat environment instance from a Config object and env class using make_env_fn', 'construct a VectorEnv with multiple parallel environments split across scenes using construct_envs', 'split dataset scenes across multiple worker environments for parallel simulation using construct_envs', 'review the make_env_fn function to understand how it creates individual Habitat environments with dataset and seed', 'review the construct_envs function to understand scene splitting and per-worker config cloning logic', 'wrap a Habitat RLEnv into an OpenAI Gym compatible environment using HabGymWrapper', 'create a function that recursively flattens a nested dictionary into a single level with concatenated keys', 'build a gym Box space by smashing together multiple 1D observation spaces into one flattened space', 'run a step on the Gym-wrapped Habitat environment with a numpy array action and get observations', 'render the last Habitat observation as an RGB array image using the HabGymWrapper render method', 'append lines of text underneath a numpy image array using OpenCV putText', 'overlay flattened info dictionary values as text lines on a rendered frame image', 'create a HabRenderWrapper gym wrapper that overlays measure values on rendered frames', 'step the wrapped gym environment while tracking accumulated reward and step count', 'render the wrapped environment frame with overlaid step count and total reward text']
```

Usage

```
{'wrap_habitat_env_as_gym': 'wrap a Habitat RLEnv into an OpenAI Gym compatible environment using HabGymWrapper', 'flatten_nested_dict': 'create a function that recursively flattens a nested dictionary into a single level with concatenated keys', 'smash_observation_space': 'build a gym Box space by smashing together multiple 1D observation spaces into one flattened space', 'step_gym_wrapped_env': 'run a step on the Gym-wrapped Habitat environment with a numpy array action and get observations', 'render_habitat_observation': 'render the last Habitat observation as an RGB array image using the HabGymWrapper render method'}
```

## File: facebookresearch_eai-vc/third_party/habitat-lab/habitat_baselines/utils/render_wrapper.py

Prompts

```
['batch a list of observation dicts into a TensorDict for GPU transfer in RL training', 'build a CategoricalNet module that maps inputs to a categorical action distribution for discrete RL', 'build a GaussianNet module that maps inputs to a normal action distribution for continuous RL', 'generate a video from a list of numpy images and save to disk or TensorBoard', 'resize an image tensor so its shortest edge matches a target size while preserving aspect ratio', 'create a Habitat environment instance from a Config object and env class using make_env_fn', 'construct a VectorEnv with multiple parallel environments split across scenes using construct_envs', 'split dataset scenes across multiple worker environments for parallel simulation using construct_envs', 'review the make_env_fn function to understand how it creates individual Habitat environments with dataset and seed', 'review the construct_envs function to understand scene splitting and per-worker config cloning logic', 'wrap a Habitat RLEnv into an OpenAI Gym compatible environment using HabGymWrapper', 'create a function that recursively flattens a nested dictionary into a single level with concatenated keys', 'build a gym Box space by smashing together multiple 1D observation spaces into one flattened space', 'run a step on the Gym-wrapped Habitat environment with a numpy array action and get observations', 'render the last Habitat observation as an RGB array image using the HabGymWrapper render method', 'append lines of text underneath a numpy image array using OpenCV putText', 'overlay flattened info dictionary values as text lines on a rendered frame image', 'create a HabRenderWrapper gym wrapper that overlays measure values on rendered frames', 'step the wrapped gym environment while tracking accumulated reward and step count', 'render the wrapped environment frame with overlaid step count and total reward text']
```

Usage

```
{'append_text_to_image': 'append lines of text underneath a numpy image array using OpenCV putText', 'overlay_frame': 'overlay flattened info dictionary values as text lines on a rendered frame image', 'HabRenderWrapper_init': 'create a HabRenderWrapper gym wrapper that overlays measure values on rendered frames', 'HabRenderWrapper_step': 'step the wrapped gym environment while tracking accumulated reward and step count', 'HabRenderWrapper_render': 'render the wrapped environment frame with overlaid step count and total reward text'}
```

