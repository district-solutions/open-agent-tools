# Agent Python Tools

- repo: facebookresearch/spider
- repo_uri: https://github.com/facebookresearch/spider

## File: facebookresearch_spider/spider/config.py

Prompts

```
['build a Config dataclass with robot type, embodiment, task, simulator, and optimizer settings for the MJWP planner', 'process a Config instance to compute timesteps, resolve model paths, load MuJoCo model, and set noise schedule', 'load a YAML config file into a plain dict using OmegaConf and strip the hydra key', 'get the noise scale tensor for sampling with per-component scaling for joint, position, and rotation DOFs', 'resolve object actuator IDs from a MuJoCo model by name with fallback to the last N actuators', 'build a torch tensor upsampler using zeroth-order hold nearest neighbor interpolation', 'build a torch tensor upsampler using first-order hold linear interpolation', 'build a torch tensor upsampler using second-order hold quadratic interpolation', 'test the interp function with zeroth first and second order hold interpolation modes', 'refactor the get_slice function to slice a tuple of torch tensors by start and end indices', 'load trajectory data from an NPZ file including qpos, qvel, ctrl, and contact arrays', 'get the processed data directory path for a specific robot task and data ID', 'get all available task names from a processed dataset directory for a given robot type', 'get the mesh asset directory path for a specific object in a processed dataset', 'review the load_data function to understand how it interpolates trajectory data to match simulation timestep', 'convert a PyTorch quaternion tensor from xyzw format to wxyz format', 'convert a PyTorch quaternion tensor from wxyz format to xyzw format', 'convert a quaternion tensor to angular velocity using axis-angle extraction', 'multiply two wxyz-format quaternion tensors and return the product quaternion', 'subtract one quaternion from another and return the angular difference as a 3D vector', 'get a MuJoCo passive viewer by calling get_viewer with show_viewer True and a model and data', 'get a DummyViewer context manager by calling get_viewer with show_viewer False for headless simulation', 'launch a MuJoCo passive viewer using the lambda returned by get_viewer with show_viewer set to True', 'use the DummyViewer context manager from get_viewer to simulate without a graphical viewer in headless mode', 'check if the viewer is running by calling the is_running method on the DummyViewer object']
```

Usage

```
{'build_Config': 'build a Config dataclass with robot type, embodiment, task, simulator, and optimizer settings for the MJWP planner', 'process_config': 'process a Config instance to compute timesteps, resolve model paths, load MuJoCo model, and set noise schedule', 'load_config_yaml': 'load a YAML config file into a plain dict using OmegaConf and strip the hydra key', 'get_noise_scale': 'get the noise scale tensor for sampling with per-component scaling for joint, position, and rotation DOFs', 'resolve_object_actuator_ids': 'resolve object actuator IDs from a MuJoCo model by name with fallback to the last N actuators'}
```

## File: facebookresearch_spider/spider/interp.py

Prompts

```
['build a Config dataclass with robot type, embodiment, task, simulator, and optimizer settings for the MJWP planner', 'process a Config instance to compute timesteps, resolve model paths, load MuJoCo model, and set noise schedule', 'load a YAML config file into a plain dict using OmegaConf and strip the hydra key', 'get the noise scale tensor for sampling with per-component scaling for joint, position, and rotation DOFs', 'resolve object actuator IDs from a MuJoCo model by name with fallback to the last N actuators', 'build a torch tensor upsampler using zeroth-order hold nearest neighbor interpolation', 'build a torch tensor upsampler using first-order hold linear interpolation', 'build a torch tensor upsampler using second-order hold quadratic interpolation', 'test the interp function with zeroth first and second order hold interpolation modes', 'refactor the get_slice function to slice a tuple of torch tensors by start and end indices', 'load trajectory data from an NPZ file including qpos, qvel, ctrl, and contact arrays', 'get the processed data directory path for a specific robot task and data ID', 'get all available task names from a processed dataset directory for a given robot type', 'get the mesh asset directory path for a specific object in a processed dataset', 'review the load_data function to understand how it interpolates trajectory data to match simulation timestep', 'convert a PyTorch quaternion tensor from xyzw format to wxyz format', 'convert a PyTorch quaternion tensor from wxyz format to xyzw format', 'convert a quaternion tensor to angular velocity using axis-angle extraction', 'multiply two wxyz-format quaternion tensors and return the product quaternion', 'subtract one quaternion from another and return the angular difference as a 3D vector', 'get a MuJoCo passive viewer by calling get_viewer with show_viewer True and a model and data', 'get a DummyViewer context manager by calling get_viewer with show_viewer False for headless simulation', 'launch a MuJoCo passive viewer using the lambda returned by get_viewer with show_viewer set to True', 'use the DummyViewer context manager from get_viewer to simulate without a graphical viewer in headless mode', 'check if the viewer is running by calling the is_running method on the DummyViewer object']
```

Usage

```
{'build_interp_zoh': 'build a torch tensor upsampler using zeroth-order hold nearest neighbor interpolation', 'build_interp_foh': 'build a torch tensor upsampler using first-order hold linear interpolation', 'build_interp_soh': 'build a torch tensor upsampler using second-order hold quadratic interpolation', 'test_interp': 'test the interp function with zeroth first and second order hold interpolation modes', 'refactor_get_slice': 'refactor the get_slice function to slice a tuple of torch tensors by start and end indices'}
```

## File: facebookresearch_spider/spider/io.py

Prompts

```
['build a Config dataclass with robot type, embodiment, task, simulator, and optimizer settings for the MJWP planner', 'process a Config instance to compute timesteps, resolve model paths, load MuJoCo model, and set noise schedule', 'load a YAML config file into a plain dict using OmegaConf and strip the hydra key', 'get the noise scale tensor for sampling with per-component scaling for joint, position, and rotation DOFs', 'resolve object actuator IDs from a MuJoCo model by name with fallback to the last N actuators', 'build a torch tensor upsampler using zeroth-order hold nearest neighbor interpolation', 'build a torch tensor upsampler using first-order hold linear interpolation', 'build a torch tensor upsampler using second-order hold quadratic interpolation', 'test the interp function with zeroth first and second order hold interpolation modes', 'refactor the get_slice function to slice a tuple of torch tensors by start and end indices', 'load trajectory data from an NPZ file including qpos, qvel, ctrl, and contact arrays', 'get the processed data directory path for a specific robot task and data ID', 'get all available task names from a processed dataset directory for a given robot type', 'get the mesh asset directory path for a specific object in a processed dataset', 'review the load_data function to understand how it interpolates trajectory data to match simulation timestep', 'convert a PyTorch quaternion tensor from xyzw format to wxyz format', 'convert a PyTorch quaternion tensor from wxyz format to xyzw format', 'convert a quaternion tensor to angular velocity using axis-angle extraction', 'multiply two wxyz-format quaternion tensors and return the product quaternion', 'subtract one quaternion from another and return the angular difference as a 3D vector', 'get a MuJoCo passive viewer by calling get_viewer with show_viewer True and a model and data', 'get a DummyViewer context manager by calling get_viewer with show_viewer False for headless simulation', 'launch a MuJoCo passive viewer using the lambda returned by get_viewer with show_viewer set to True', 'use the DummyViewer context manager from get_viewer to simulate without a graphical viewer in headless mode', 'check if the viewer is running by calling the is_running method on the DummyViewer object']
```

Usage

```
{'load_data_from_npz': 'load trajectory data from an NPZ file including qpos, qvel, ctrl, and contact arrays', 'get_processed_data_dir': 'get the processed data directory path for a specific robot task and data ID', 'get_all_tasks': 'get all available task names from a processed dataset directory for a given robot type', 'get_mesh_dir': 'get the mesh asset directory path for a specific object in a processed dataset', 'review_load_data': 'review the load_data function to understand how it interpolates trajectory data to match simulation timestep'}
```

## File: facebookresearch_spider/spider/math.py

Prompts

```
['build a Config dataclass with robot type, embodiment, task, simulator, and optimizer settings for the MJWP planner', 'process a Config instance to compute timesteps, resolve model paths, load MuJoCo model, and set noise schedule', 'load a YAML config file into a plain dict using OmegaConf and strip the hydra key', 'get the noise scale tensor for sampling with per-component scaling for joint, position, and rotation DOFs', 'resolve object actuator IDs from a MuJoCo model by name with fallback to the last N actuators', 'build a torch tensor upsampler using zeroth-order hold nearest neighbor interpolation', 'build a torch tensor upsampler using first-order hold linear interpolation', 'build a torch tensor upsampler using second-order hold quadratic interpolation', 'test the interp function with zeroth first and second order hold interpolation modes', 'refactor the get_slice function to slice a tuple of torch tensors by start and end indices', 'load trajectory data from an NPZ file including qpos, qvel, ctrl, and contact arrays', 'get the processed data directory path for a specific robot task and data ID', 'get all available task names from a processed dataset directory for a given robot type', 'get the mesh asset directory path for a specific object in a processed dataset', 'review the load_data function to understand how it interpolates trajectory data to match simulation timestep', 'convert a PyTorch quaternion tensor from xyzw format to wxyz format', 'convert a PyTorch quaternion tensor from wxyz format to xyzw format', 'convert a quaternion tensor to angular velocity using axis-angle extraction', 'multiply two wxyz-format quaternion tensors and return the product quaternion', 'subtract one quaternion from another and return the angular difference as a 3D vector', 'get a MuJoCo passive viewer by calling get_viewer with show_viewer True and a model and data', 'get a DummyViewer context manager by calling get_viewer with show_viewer False for headless simulation', 'launch a MuJoCo passive viewer using the lambda returned by get_viewer with show_viewer set to True', 'use the DummyViewer context manager from get_viewer to simulate without a graphical viewer in headless mode', 'check if the viewer is running by calling the is_running method on the DummyViewer object']
```

Usage

```
{'convert_quat_xyzw_to_wxyz': 'convert a PyTorch quaternion tensor from xyzw format to wxyz format', 'convert_quat_wxyz_to_xyzw': 'convert a PyTorch quaternion tensor from wxyz format to xyzw format', 'convert_quat_to_angular_velocity': 'convert a quaternion tensor to angular velocity using axis-angle extraction', 'multiply_two_quaternions': 'multiply two wxyz-format quaternion tensors and return the product quaternion', 'subtract_quaternions': 'subtract one quaternion from another and return the angular difference as a 3D vector'}
```

## File: facebookresearch_spider/spider/mujoco_utils.py

Prompts

```
['build a Config dataclass with robot type, embodiment, task, simulator, and optimizer settings for the MJWP planner', 'process a Config instance to compute timesteps, resolve model paths, load MuJoCo model, and set noise schedule', 'load a YAML config file into a plain dict using OmegaConf and strip the hydra key', 'get the noise scale tensor for sampling with per-component scaling for joint, position, and rotation DOFs', 'resolve object actuator IDs from a MuJoCo model by name with fallback to the last N actuators', 'build a torch tensor upsampler using zeroth-order hold nearest neighbor interpolation', 'build a torch tensor upsampler using first-order hold linear interpolation', 'build a torch tensor upsampler using second-order hold quadratic interpolation', 'test the interp function with zeroth first and second order hold interpolation modes', 'refactor the get_slice function to slice a tuple of torch tensors by start and end indices', 'load trajectory data from an NPZ file including qpos, qvel, ctrl, and contact arrays', 'get the processed data directory path for a specific robot task and data ID', 'get all available task names from a processed dataset directory for a given robot type', 'get the mesh asset directory path for a specific object in a processed dataset', 'review the load_data function to understand how it interpolates trajectory data to match simulation timestep', 'convert a PyTorch quaternion tensor from xyzw format to wxyz format', 'convert a PyTorch quaternion tensor from wxyz format to xyzw format', 'convert a quaternion tensor to angular velocity using axis-angle extraction', 'multiply two wxyz-format quaternion tensors and return the product quaternion', 'subtract one quaternion from another and return the angular difference as a 3D vector', 'get a MuJoCo passive viewer by calling get_viewer with show_viewer True and a model and data', 'get a DummyViewer context manager by calling get_viewer with show_viewer False for headless simulation', 'launch a MuJoCo passive viewer using the lambda returned by get_viewer with show_viewer set to True', 'use the DummyViewer context manager from get_viewer to simulate without a graphical viewer in headless mode', 'check if the viewer is running by calling the is_running method on the DummyViewer object']
```

Usage

```
{'get_viewer_passive': 'get a MuJoCo passive viewer by calling get_viewer with show_viewer True and a model and data', 'get_viewer_dummy': 'get a DummyViewer context manager by calling get_viewer with show_viewer False for headless simulation', 'launch_passive_viewer': 'launch a MuJoCo passive viewer using the lambda returned by get_viewer with show_viewer set to True', 'use_dummy_viewer_context': 'use the DummyViewer context manager from get_viewer to simulate without a graphical viewer in headless mode', 'check_viewer_is_running': 'check if the viewer is running by calling the is_running method on the DummyViewer object'}
```

