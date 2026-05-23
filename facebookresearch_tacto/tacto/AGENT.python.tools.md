# Agent Python Tools

- repo: facebookresearch/tacto
- repo_uri: https://github.com/facebookresearch/tacto

## File: facebookresearch_tacto/tacto/random_normal_generator.py

Prompts

```
['create a RandomNormalGenerator process that pre-generates normal distribution noise with configurable mean, std, and size', 'sample pre-generated normal distribution noise from a background RandomNormalGenerator process using the sample method', 'run a daemon process that continuously generates numpy normal distribution arrays and queues them for consumption', 'review the RandomNormalGenerator class that uses multiprocessing to prefetch random normal samples in a background thread', 'refactor the RandomNormalGenerator to adjust the prefetch queue size for controlling how many samples are pre-generated', 'create a Renderer instance with width, height, background image, and config path for offscreen rendering', 'render color and depth images from object poses and normal forces with noise and calibration', 'render color and depth images from a depth map with configurable noise and calibration', 'add a trimesh object to the rendering scene with a name, position, and orientation', 'update the camera, lighting, and gel surface pose with new position and orientation', 'create a Sensor instance with custom width, height, and config path for tactile rendering', 'add a camera to the Sensor by providing obj_id and link_ids for tactile observation', 'add an object URDF to the Sensor scene with global scaling for rendering', 'render tactile color and depth images from each camera view using Sensor.render()', 'get accumulated normal contact forces for a camera using Sensor.get_force(cam_name)', 'create a function decorated with @timeit to measure and track its execution time', 'create a function that calls timeit.summarize to print average elapsed time for all tracked functions', 'test the timeit decorator by wrapping a function and checking elapsed time is recorded', 'review the timeit module and its summarize method that prints mean execution time per function', 'refactor the timeit decorator to change the WINDOW_SIZE constant for tracking more or fewer samples']
```

Usage

```
{'create_random_normal_generator': 'create a RandomNormalGenerator process that pre-generates normal distribution noise with configurable mean, std, and size', 'sample_random_normal_noise': 'sample pre-generated normal distribution noise from a background RandomNormalGenerator process using the sample method', 'run_random_normal_generator': 'run a daemon process that continuously generates numpy normal distribution arrays and queues them for consumption', 'review_random_normal_generator_class': 'review the RandomNormalGenerator class that uses multiprocessing to prefetch random normal samples in a background thread', 'refactor_random_normal_generator_prefetch': 'refactor the RandomNormalGenerator to adjust the prefetch queue size for controlling how many samples are pre-generated'}
```

## File: facebookresearch_tacto/tacto/renderer.py

Prompts

```
['create a RandomNormalGenerator process that pre-generates normal distribution noise with configurable mean, std, and size', 'sample pre-generated normal distribution noise from a background RandomNormalGenerator process using the sample method', 'run a daemon process that continuously generates numpy normal distribution arrays and queues them for consumption', 'review the RandomNormalGenerator class that uses multiprocessing to prefetch random normal samples in a background thread', 'refactor the RandomNormalGenerator to adjust the prefetch queue size for controlling how many samples are pre-generated', 'create a Renderer instance with width, height, background image, and config path for offscreen rendering', 'render color and depth images from object poses and normal forces with noise and calibration', 'render color and depth images from a depth map with configurable noise and calibration', 'add a trimesh object to the rendering scene with a name, position, and orientation', 'update the camera, lighting, and gel surface pose with new position and orientation', 'create a Sensor instance with custom width, height, and config path for tactile rendering', 'add a camera to the Sensor by providing obj_id and link_ids for tactile observation', 'add an object URDF to the Sensor scene with global scaling for rendering', 'render tactile color and depth images from each camera view using Sensor.render()', 'get accumulated normal contact forces for a camera using Sensor.get_force(cam_name)', 'create a function decorated with @timeit to measure and track its execution time', 'create a function that calls timeit.summarize to print average elapsed time for all tracked functions', 'test the timeit decorator by wrapping a function and checking elapsed time is recorded', 'review the timeit module and its summarize method that prints mean execution time per function', 'refactor the timeit decorator to change the WINDOW_SIZE constant for tracking more or fewer samples']
```

Usage

```
{'create_Renderer_instance': 'create a Renderer instance with width, height, background image, and config path for offscreen rendering', 'render_object_poses_with_force': 'render color and depth images from object poses and normal forces with noise and calibration', 'render_from_depth_map': 'render color and depth images from a depth map with configurable noise and calibration', 'add_object_to_scene': 'add a trimesh object to the rendering scene with a name, position, and orientation', 'update_camera_pose': 'update the camera, lighting, and gel surface pose with new position and orientation'}
```

## File: facebookresearch_tacto/tacto/sensor.py

Prompts

```
['create a RandomNormalGenerator process that pre-generates normal distribution noise with configurable mean, std, and size', 'sample pre-generated normal distribution noise from a background RandomNormalGenerator process using the sample method', 'run a daemon process that continuously generates numpy normal distribution arrays and queues them for consumption', 'review the RandomNormalGenerator class that uses multiprocessing to prefetch random normal samples in a background thread', 'refactor the RandomNormalGenerator to adjust the prefetch queue size for controlling how many samples are pre-generated', 'create a Renderer instance with width, height, background image, and config path for offscreen rendering', 'render color and depth images from object poses and normal forces with noise and calibration', 'render color and depth images from a depth map with configurable noise and calibration', 'add a trimesh object to the rendering scene with a name, position, and orientation', 'update the camera, lighting, and gel surface pose with new position and orientation', 'create a Sensor instance with custom width, height, and config path for tactile rendering', 'add a camera to the Sensor by providing obj_id and link_ids for tactile observation', 'add an object URDF to the Sensor scene with global scaling for rendering', 'render tactile color and depth images from each camera view using Sensor.render()', 'get accumulated normal contact forces for a camera using Sensor.get_force(cam_name)', 'create a function decorated with @timeit to measure and track its execution time', 'create a function that calls timeit.summarize to print average elapsed time for all tracked functions', 'test the timeit decorator by wrapping a function and checking elapsed time is recorded', 'review the timeit module and its summarize method that prints mean execution time per function', 'refactor the timeit decorator to change the WINDOW_SIZE constant for tracking more or fewer samples']
```

Usage

```
{'create_Sensor_instance': 'create a Sensor instance with custom width, height, and config path for tactile rendering', 'add_camera_to_Sensor': 'add a camera to the Sensor by providing obj_id and link_ids for tactile observation', 'add_object_to_Sensor': 'add an object URDF to the Sensor scene with global scaling for rendering', 'render_tacto_images': 'render tactile color and depth images from each camera view using Sensor.render()', 'get_contact_force': 'get accumulated normal contact forces for a camera using Sensor.get_force(cam_name)'}
```

## File: facebookresearch_tacto/tacto/timeit.py

Prompts

```
['create a RandomNormalGenerator process that pre-generates normal distribution noise with configurable mean, std, and size', 'sample pre-generated normal distribution noise from a background RandomNormalGenerator process using the sample method', 'run a daemon process that continuously generates numpy normal distribution arrays and queues them for consumption', 'review the RandomNormalGenerator class that uses multiprocessing to prefetch random normal samples in a background thread', 'refactor the RandomNormalGenerator to adjust the prefetch queue size for controlling how many samples are pre-generated', 'create a Renderer instance with width, height, background image, and config path for offscreen rendering', 'render color and depth images from object poses and normal forces with noise and calibration', 'render color and depth images from a depth map with configurable noise and calibration', 'add a trimesh object to the rendering scene with a name, position, and orientation', 'update the camera, lighting, and gel surface pose with new position and orientation', 'create a Sensor instance with custom width, height, and config path for tactile rendering', 'add a camera to the Sensor by providing obj_id and link_ids for tactile observation', 'add an object URDF to the Sensor scene with global scaling for rendering', 'render tactile color and depth images from each camera view using Sensor.render()', 'get accumulated normal contact forces for a camera using Sensor.get_force(cam_name)', 'create a function decorated with @timeit to measure and track its execution time', 'create a function that calls timeit.summarize to print average elapsed time for all tracked functions', 'test the timeit decorator by wrapping a function and checking elapsed time is recorded', 'review the timeit module and its summarize method that prints mean execution time per function', 'refactor the timeit decorator to change the WINDOW_SIZE constant for tracking more or fewer samples']
```

Usage

```
{'create_function_timeit': 'create a function decorated with @timeit to measure and track its execution time', 'create_function_timeit_summarize': 'create a function that calls timeit.summarize to print average elapsed time for all tracked functions', 'test_timeit_decorator': 'test the timeit decorator by wrapping a function and checking elapsed time is recorded', 'review_timeit_summarize': 'review the timeit module and its summarize method that prints mean execution time per function', 'refactor_timeit_window': 'refactor the timeit decorator to change the WINDOW_SIZE constant for tracking more or fewer samples'}
```

