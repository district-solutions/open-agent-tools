# Agent Python Tools

- repo: facebookresearch/ava-256
- repo_uri: https://github.com/facebookresearch/ava-256

## File: facebookresearch_ava-256/models/raymarchers/mvpraymarcher.py

Prompts

```
['build a python module that instantiates a Raymarcher with a given volume radius and step size', 'create a function that runs Raymarcher forward pass with ray positions, directions, and decoded output tensors', 'test the Raymarcher class initialization with a volume radius and default dt step size', 'review the Raymarcher forward method integration with the mvpraymarch CUDA extension for volumetric rendering', 'summarize the Raymarcher forward method that returns RGB, alpha, RGBA tensors from ray marching', 'create a Raymarcher instance with a given volume radius for pure PyTorch raymarching', 'run the Raymarcher forward pass with ray positions, directions, tminmax, decoder output, and render options', 'run raymarching using multiplicative accumulation mode by setting multaccum to true in render options', 'use grid sampling on warp and template decoder outputs to sample RGB and alpha along rays', 'render RGBA output by accumulating sample colors and alpha values along ray steps']
```

Usage

```
{'build_raymarcher_module': 'build a python module that instantiates a Raymarcher with a given volume radius and step size', 'create_raymarcher_forward': 'create a function that runs Raymarcher forward pass with ray positions, directions, and decoded output tensors', 'test_raymarcher_class': 'test the Raymarcher class initialization with a volume radius and default dt step size', 'review_mvpraymarch_integration': 'review the Raymarcher forward method integration with the mvpraymarch CUDA extension for volumetric rendering', 'summarize_rayrgba_output': 'summarize the Raymarcher forward method that returns RGB, alpha, RGBA tensors from ray marching'}
```

## File: facebookresearch_ava-256/models/raymarchers/stepraymarcher.py

Prompts

```
['build a python module that instantiates a Raymarcher with a given volume radius and step size', 'create a function that runs Raymarcher forward pass with ray positions, directions, and decoded output tensors', 'test the Raymarcher class initialization with a volume radius and default dt step size', 'review the Raymarcher forward method integration with the mvpraymarch CUDA extension for volumetric rendering', 'summarize the Raymarcher forward method that returns RGB, alpha, RGBA tensors from ray marching', 'create a Raymarcher instance with a given volume radius for pure PyTorch raymarching', 'run the Raymarcher forward pass with ray positions, directions, tminmax, decoder output, and render options', 'run raymarching using multiplicative accumulation mode by setting multaccum to true in render options', 'use grid sampling on warp and template decoder outputs to sample RGB and alpha along rays', 'render RGBA output by accumulating sample colors and alpha values along ray steps']
```

Usage

```
{'init_Raymarcher': 'create a Raymarcher instance with a given volume radius for pure PyTorch raymarching', 'forward_Raymarcher': 'run the Raymarcher forward pass with ray positions, directions, tminmax, decoder output, and render options', 'raymarch_with_multaccum': 'run raymarching using multiplicative accumulation mode by setting multaccum to true in render options', 'raymarch_with_grid_sample': 'use grid sampling on warp and template decoder outputs to sample RGB and alpha along rays', 'render_rgba_output': 'render RGBA output by accumulating sample colors and alpha values along ray steps'}
```

