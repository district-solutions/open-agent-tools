# Agent Python Tools

- repo: facebookresearch/tacto
- repo_uri: https://github.com/facebookresearch/tacto

## File: facebookresearch_tacto/tests/benchmark.py

Prompts

```
['run the render function to benchmark sensor update and render performance over N iterations', 'run the test_rendering_fps function to benchmark Tacto sensor rendering FPS with a falling sphere simulation', 'run the benchmark script directly to render a color image and save it as color.jpg', 'review the render function that measures average time and FPS for sensor update and render cycles', 'review the test_rendering_fps function that sets up a Tacto sensor with pybulletX bodies and benchmarks rendering', 'test the numpy random normal generation performance with 100 iterations on a 320x240x3 image shape', 'test the RandomNormalGenerator multiprocess sampling performance with 100 iterations and prefetch of 100', 'run the pytest test that benchmarks standard numpy random normal generation speed', 'run the pytest test that benchmarks the multiprocess RandomNormalGenerator sampling speed', 'review the test file that compares numpy random normal generation against the multiprocess RandomNormalGenerator', 'test the OSMesa renderer by rendering from a depth map and comparing against ground truth color', 'run the tacto Renderer to render color and depth from a depth map with a given scale', 'create a tacto Renderer with specified width, height, config path, and background settings', 'get the default digit config path from the tacto library for renderer initialization', 'verify that OSMesa rendering is deterministic by fixing the numpy random seed and checking RMS', 'test the timeit decorator by running the test_timeit function that calls a decorated function 100 times', 'run the test_timeit function to benchmark a numpy random normal function wrapped with the timeit decorator', 'summarize the elapsed time for decorated functions by calling timeit.summarize after running test_timeit', 'create a function wrapped with the timeit decorator to measure execution time of numpy operations', 'review the test_timeit test file that validates the timeit decorator on a numpy-based function']
```

Usage

```
{'run_render_benchmark': 'run the render function to benchmark sensor update and render performance over N iterations', 'run_test_rendering_fps': 'run the test_rendering_fps function to benchmark Tacto sensor rendering FPS with a falling sphere simulation', 'run_benchmark_main': 'run the benchmark script directly to render a color image and save it as color.jpg', 'review_render_function': 'review the render function that measures average time and FPS for sensor update and render cycles', 'review_test_rendering_fps': 'review the test_rendering_fps function that sets up a Tacto sensor with pybulletX bodies and benchmarks rendering'}
```

## File: facebookresearch_tacto/tests/test_random_normal_generator.py

Prompts

```
['run the render function to benchmark sensor update and render performance over N iterations', 'run the test_rendering_fps function to benchmark Tacto sensor rendering FPS with a falling sphere simulation', 'run the benchmark script directly to render a color image and save it as color.jpg', 'review the render function that measures average time and FPS for sensor update and render cycles', 'review the test_rendering_fps function that sets up a Tacto sensor with pybulletX bodies and benchmarks rendering', 'test the numpy random normal generation performance with 100 iterations on a 320x240x3 image shape', 'test the RandomNormalGenerator multiprocess sampling performance with 100 iterations and prefetch of 100', 'run the pytest test that benchmarks standard numpy random normal generation speed', 'run the pytest test that benchmarks the multiprocess RandomNormalGenerator sampling speed', 'review the test file that compares numpy random normal generation against the multiprocess RandomNormalGenerator', 'test the OSMesa renderer by rendering from a depth map and comparing against ground truth color', 'run the tacto Renderer to render color and depth from a depth map with a given scale', 'create a tacto Renderer with specified width, height, config path, and background settings', 'get the default digit config path from the tacto library for renderer initialization', 'verify that OSMesa rendering is deterministic by fixing the numpy random seed and checking RMS', 'test the timeit decorator by running the test_timeit function that calls a decorated function 100 times', 'run the test_timeit function to benchmark a numpy random normal function wrapped with the timeit decorator', 'summarize the elapsed time for decorated functions by calling timeit.summarize after running test_timeit', 'create a function wrapped with the timeit decorator to measure execution time of numpy operations', 'review the test_timeit test file that validates the timeit decorator on a numpy-based function']
```

Usage

```
{'test_random_normal_generator': 'test the numpy random normal generation performance with 100 iterations on a 320x240x3 image shape', 'test_random_normal_generator_multiprocess': 'test the RandomNormalGenerator multiprocess sampling performance with 100 iterations and prefetch of 100', 'run_test_random_normal_generator': 'run the pytest test that benchmarks standard numpy random normal generation speed', 'run_test_random_normal_generator_multiprocess': 'run the pytest test that benchmarks the multiprocess RandomNormalGenerator sampling speed', 'review_test_random_normal_generator': 'review the test file that compares numpy random normal generation against the multiprocess RandomNormalGenerator'}
```

## File: facebookresearch_tacto/tests/test_render_from_depth_osmesa.py

Prompts

```
['run the render function to benchmark sensor update and render performance over N iterations', 'run the test_rendering_fps function to benchmark Tacto sensor rendering FPS with a falling sphere simulation', 'run the benchmark script directly to render a color image and save it as color.jpg', 'review the render function that measures average time and FPS for sensor update and render cycles', 'review the test_rendering_fps function that sets up a Tacto sensor with pybulletX bodies and benchmarks rendering', 'test the numpy random normal generation performance with 100 iterations on a 320x240x3 image shape', 'test the RandomNormalGenerator multiprocess sampling performance with 100 iterations and prefetch of 100', 'run the pytest test that benchmarks standard numpy random normal generation speed', 'run the pytest test that benchmarks the multiprocess RandomNormalGenerator sampling speed', 'review the test file that compares numpy random normal generation against the multiprocess RandomNormalGenerator', 'test the OSMesa renderer by rendering from a depth map and comparing against ground truth color', 'run the tacto Renderer to render color and depth from a depth map with a given scale', 'create a tacto Renderer with specified width, height, config path, and background settings', 'get the default digit config path from the tacto library for renderer initialization', 'verify that OSMesa rendering is deterministic by fixing the numpy random seed and checking RMS', 'test the timeit decorator by running the test_timeit function that calls a decorated function 100 times', 'run the test_timeit function to benchmark a numpy random normal function wrapped with the timeit decorator', 'summarize the elapsed time for decorated functions by calling timeit.summarize after running test_timeit', 'create a function wrapped with the timeit decorator to measure execution time of numpy operations', 'review the test_timeit test file that validates the timeit decorator on a numpy-based function']
```

Usage

```
{'test_render_from_depth_osmesa': 'test the OSMesa renderer by rendering from a depth map and comparing against ground truth color', 'run_tacto_renderer_from_depth': 'run the tacto Renderer to render color and depth from a depth map with a given scale', 'create_tacto_renderer': 'create a tacto Renderer with specified width, height, config path, and background settings', 'get_digit_config_path': 'get the default digit config path from the tacto library for renderer initialization', 'verify_render_determinism': 'verify that OSMesa rendering is deterministic by fixing the numpy random seed and checking RMS'}
```

## File: facebookresearch_tacto/tests/test_timeit.py

Prompts

```
['run the render function to benchmark sensor update and render performance over N iterations', 'run the test_rendering_fps function to benchmark Tacto sensor rendering FPS with a falling sphere simulation', 'run the benchmark script directly to render a color image and save it as color.jpg', 'review the render function that measures average time and FPS for sensor update and render cycles', 'review the test_rendering_fps function that sets up a Tacto sensor with pybulletX bodies and benchmarks rendering', 'test the numpy random normal generation performance with 100 iterations on a 320x240x3 image shape', 'test the RandomNormalGenerator multiprocess sampling performance with 100 iterations and prefetch of 100', 'run the pytest test that benchmarks standard numpy random normal generation speed', 'run the pytest test that benchmarks the multiprocess RandomNormalGenerator sampling speed', 'review the test file that compares numpy random normal generation against the multiprocess RandomNormalGenerator', 'test the OSMesa renderer by rendering from a depth map and comparing against ground truth color', 'run the tacto Renderer to render color and depth from a depth map with a given scale', 'create a tacto Renderer with specified width, height, config path, and background settings', 'get the default digit config path from the tacto library for renderer initialization', 'verify that OSMesa rendering is deterministic by fixing the numpy random seed and checking RMS', 'test the timeit decorator by running the test_timeit function that calls a decorated function 100 times', 'run the test_timeit function to benchmark a numpy random normal function wrapped with the timeit decorator', 'summarize the elapsed time for decorated functions by calling timeit.summarize after running test_timeit', 'create a function wrapped with the timeit decorator to measure execution time of numpy operations', 'review the test_timeit test file that validates the timeit decorator on a numpy-based function']
```

Usage

```
{'test_timeit_decorator': 'test the timeit decorator by running the test_timeit function that calls a decorated function 100 times', 'run_timeit_test': 'run the test_timeit function to benchmark a numpy random normal function wrapped with the timeit decorator', 'summarize_timeit_elapsed': 'summarize the elapsed time for decorated functions by calling timeit.summarize after running test_timeit', 'create_timeit_wrapped_function': 'create a function wrapped with the timeit decorator to measure execution time of numpy operations', 'review_timeit_test': 'review the test_timeit test file that validates the timeit decorator on a numpy-based function'}
```

