# Agent Python Tools

- repo: facebookresearch/house3d
- repo_uri: https://github.com/facebookresearch/house3d

## File: facebookresearch_house3d/tests/benchmark-env-multiprocess.py

Prompts

```
['run a multiprocess benchmark of House3D environment rendering across multiple GPUs', 'run the worker function that renders frames and moves forward in the House3D environment', 'test the Environment reset and move_forward methods in a rendering loop', 'review the worker function that benchmarks rendering speed with random movements', 'summarize the multiprocess benchmark script for House3D environment rendering performance', 'test the RenderAPI loadScene method by loading an OBJ with mapping and colormap files', 'test the RenderAPI setMode method by switching between RGB and SEMANTIC render modes', 'review the worker function and multiprocessing setup for GPU device distribution across processes', 'create a House object from OBJ and JSON files with an optional cached map and robot radius', 'get a random house from the config prefix that contains a living room', 'create a RenderAPI instance with 250x250 resolution on GPU device 0', 'reset the environment to a random location within a specified room type', 'run an interactive cubemap rendering loop with keyboard controls for camera yaw and render mode switching', 'create a RestrictedHouse object from house.obj and house.json files with a given robot radius', 'render RGB, depth, semantic, instance, and inverse depth cube map images for a robot location', 'run the multi-threaded pipeline to generate sample renders for all houses in the dataset', 'reset the robot environment to a random valid location within a specified room', 'get a list of rooms matching specified room types such as living_room from a house', 'run the TestCubeMap unit test to verify RGB, semantic, instance, depth, and inverse depth cube map rendering', 'create a House object from a house ID and config using the create_house helper function', 'find the first house in the config prefix directory that contains a kitchen room type', 'calculate float depth values from 16-bit inverse depth numpy arrays using depth_of_inverse_depth', 'render a cube map in RGB, semantic, instance, depth, or inverse depth mode using Environment and RenderMode']
```

Usage

```
{'run_benchmark_multiprocess': 'run a multiprocess benchmark of House3D environment rendering across multiple GPUs', 'run_worker_render_loop': 'run the worker function that renders frames and moves forward in the House3D environment', 'test_environment_reset_and_move': 'test the Environment reset and move_forward methods in a rendering loop', 'review_worker_function': 'review the worker function that benchmarks rendering speed with random movements', 'summarize_benchmark_script': 'summarize the multiprocess benchmark script for House3D environment rendering performance'}
```

## File: facebookresearch_house3d/tests/benchmark-rendering-multiprocess.py

Prompts

```
['run a multiprocess benchmark of House3D environment rendering across multiple GPUs', 'run the worker function that renders frames and moves forward in the House3D environment', 'test the Environment reset and move_forward methods in a rendering loop', 'review the worker function that benchmarks rendering speed with random movements', 'summarize the multiprocess benchmark script for House3D environment rendering performance', 'test the RenderAPI loadScene method by loading an OBJ with mapping and colormap files', 'test the RenderAPI setMode method by switching between RGB and SEMANTIC render modes', 'review the worker function and multiprocessing setup for GPU device distribution across processes', 'create a House object from OBJ and JSON files with an optional cached map and robot radius', 'get a random house from the config prefix that contains a living room', 'create a RenderAPI instance with 250x250 resolution on GPU device 0', 'reset the environment to a random location within a specified room type', 'run an interactive cubemap rendering loop with keyboard controls for camera yaw and render mode switching', 'create a RestrictedHouse object from house.obj and house.json files with a given robot radius', 'render RGB, depth, semantic, instance, and inverse depth cube map images for a robot location', 'run the multi-threaded pipeline to generate sample renders for all houses in the dataset', 'reset the robot environment to a random valid location within a specified room', 'get a list of rooms matching specified room types such as living_room from a house', 'run the TestCubeMap unit test to verify RGB, semantic, instance, depth, and inverse depth cube map rendering', 'create a House object from a house ID and config using the create_house helper function', 'find the first house in the config prefix directory that contains a kitchen room type', 'calculate float depth values from 16-bit inverse depth numpy arrays using depth_of_inverse_depth', 'render a cube map in RGB, semantic, instance, depth, or inverse depth mode using Environment and RenderMode']
```

Usage

```
{'run_benchmark_multiprocess': 'run the multiprocess rendering benchmark on an OBJ file with configurable GPU and process count', 'run_worker_render_loop': 'run the worker function to render frames alternating between RGB and semantic modes', 'test_renderapi_loadscene': 'test the RenderAPI loadScene method by loading an OBJ with mapping and colormap files', 'test_renderapi_setmode': 'test the RenderAPI setMode method by switching between RGB and SEMANTIC render modes', 'review_worker_multiprocessing': 'review the worker function and multiprocessing setup for GPU device distribution across processes'}
```

## File: facebookresearch_house3d/tests/test-cubemap.py

Prompts

```
['run a multiprocess benchmark of House3D environment rendering across multiple GPUs', 'run the worker function that renders frames and moves forward in the House3D environment', 'test the Environment reset and move_forward methods in a rendering loop', 'review the worker function that benchmarks rendering speed with random movements', 'summarize the multiprocess benchmark script for House3D environment rendering performance', 'test the RenderAPI loadScene method by loading an OBJ with mapping and colormap files', 'test the RenderAPI setMode method by switching between RGB and SEMANTIC render modes', 'review the worker function and multiprocessing setup for GPU device distribution across processes', 'create a House object from OBJ and JSON files with an optional cached map and robot radius', 'get a random house from the config prefix that contains a living room', 'create a RenderAPI instance with 250x250 resolution on GPU device 0', 'reset the environment to a random location within a specified room type', 'run an interactive cubemap rendering loop with keyboard controls for camera yaw and render mode switching', 'create a RestrictedHouse object from house.obj and house.json files with a given robot radius', 'render RGB, depth, semantic, instance, and inverse depth cube map images for a robot location', 'run the multi-threaded pipeline to generate sample renders for all houses in the dataset', 'reset the robot environment to a random valid location within a specified room', 'get a list of rooms matching specified room types such as living_room from a house', 'run the TestCubeMap unit test to verify RGB, semantic, instance, depth, and inverse depth cube map rendering', 'create a House object from a house ID and config using the create_house helper function', 'find the first house in the config prefix directory that contains a kitchen room type', 'calculate float depth values from 16-bit inverse depth numpy arrays using depth_of_inverse_depth', 'render a cube map in RGB, semantic, instance, depth, or inverse depth mode using Environment and RenderMode']
```

Usage

```
{'create_house_from_files': 'create a House object from OBJ and JSON files with an optional cached map and robot radius', 'get_rand_house_with_room_type': 'get a random house from the config prefix that contains a living room', 'create_render_api': 'create a RenderAPI instance with 250x250 resolution on GPU device 0', 'reset_environment_to_random_location': 'reset the environment to a random location within a specified room type', 'run_cubemap_rendering_loop': 'run an interactive cubemap rendering loop with keyboard controls for camera yaw and render mode switching'}
```

## File: facebookresearch_house3d/tests/test-samples.py

Prompts

```
['run a multiprocess benchmark of House3D environment rendering across multiple GPUs', 'run the worker function that renders frames and moves forward in the House3D environment', 'test the Environment reset and move_forward methods in a rendering loop', 'review the worker function that benchmarks rendering speed with random movements', 'summarize the multiprocess benchmark script for House3D environment rendering performance', 'test the RenderAPI loadScene method by loading an OBJ with mapping and colormap files', 'test the RenderAPI setMode method by switching between RGB and SEMANTIC render modes', 'review the worker function and multiprocessing setup for GPU device distribution across processes', 'create a House object from OBJ and JSON files with an optional cached map and robot radius', 'get a random house from the config prefix that contains a living room', 'create a RenderAPI instance with 250x250 resolution on GPU device 0', 'reset the environment to a random location within a specified room type', 'run an interactive cubemap rendering loop with keyboard controls for camera yaw and render mode switching', 'create a RestrictedHouse object from house.obj and house.json files with a given robot radius', 'render RGB, depth, semantic, instance, and inverse depth cube map images for a robot location', 'run the multi-threaded pipeline to generate sample renders for all houses in the dataset', 'reset the robot environment to a random valid location within a specified room', 'get a list of rooms matching specified room types such as living_room from a house', 'run the TestCubeMap unit test to verify RGB, semantic, instance, depth, and inverse depth cube map rendering', 'create a House object from a house ID and config using the create_house helper function', 'find the first house in the config prefix directory that contains a kitchen room type', 'calculate float depth values from 16-bit inverse depth numpy arrays using depth_of_inverse_depth', 'render a cube map in RGB, semantic, instance, depth, or inverse depth mode using Environment and RenderMode']
```

Usage

```
{'create_house_from_obj_json': 'create a RestrictedHouse object from house.obj and house.json files with a given robot radius', 'render_cube_map_for_location': 'render RGB, depth, semantic, instance, and inverse depth cube map images for a robot location', 'run_sample_generation_pipeline': 'run the multi-threaded pipeline to generate sample renders for all houses in the dataset', 'reset_robot_in_random_room_location': 'reset the robot environment to a random valid location within a specified room', 'get_valid_rooms_by_type': 'get a list of rooms matching specified room types such as living_room from a house'}
```

## File: facebookresearch_house3d/tests/unit-tests.py

Prompts

```
['run a multiprocess benchmark of House3D environment rendering across multiple GPUs', 'run the worker function that renders frames and moves forward in the House3D environment', 'test the Environment reset and move_forward methods in a rendering loop', 'review the worker function that benchmarks rendering speed with random movements', 'summarize the multiprocess benchmark script for House3D environment rendering performance', 'test the RenderAPI loadScene method by loading an OBJ with mapping and colormap files', 'test the RenderAPI setMode method by switching between RGB and SEMANTIC render modes', 'review the worker function and multiprocessing setup for GPU device distribution across processes', 'create a House object from OBJ and JSON files with an optional cached map and robot radius', 'get a random house from the config prefix that contains a living room', 'create a RenderAPI instance with 250x250 resolution on GPU device 0', 'reset the environment to a random location within a specified room type', 'run an interactive cubemap rendering loop with keyboard controls for camera yaw and render mode switching', 'create a RestrictedHouse object from house.obj and house.json files with a given robot radius', 'render RGB, depth, semantic, instance, and inverse depth cube map images for a robot location', 'run the multi-threaded pipeline to generate sample renders for all houses in the dataset', 'reset the robot environment to a random valid location within a specified room', 'get a list of rooms matching specified room types such as living_room from a house', 'run the TestCubeMap unit test to verify RGB, semantic, instance, depth, and inverse depth cube map rendering', 'create a House object from a house ID and config using the create_house helper function', 'find the first house in the config prefix directory that contains a kitchen room type', 'calculate float depth values from 16-bit inverse depth numpy arrays using depth_of_inverse_depth', 'render a cube map in RGB, semantic, instance, depth, or inverse depth mode using Environment and RenderMode']
```

Usage

```
{'run_cube_map_render_test': 'run the TestCubeMap unit test to verify RGB, semantic, instance, depth, and inverse depth cube map rendering', 'create_house_from_config': 'create a House object from a house ID and config using the create_house helper function', 'find_first_good_house': 'find the first house in the config prefix directory that contains a kitchen room type', 'calculate_depth_from_inverse_depth': 'calculate float depth values from 16-bit inverse depth numpy arrays using depth_of_inverse_depth', 'render_cube_map_with_modes': 'render a cube map in RGB, semantic, instance, depth, or inverse depth mode using Environment and RenderMode'}
```

