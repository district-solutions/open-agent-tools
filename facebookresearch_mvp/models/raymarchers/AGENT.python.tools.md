# Agent Python Tools

- repo: facebookresearch/mvp
- repo_uri: https://github.com/facebookresearch/mvp

## File: facebookresearch_mvp/models/raymarchers/mvpraymarcher.py

Prompts

```
['create a Raymarcher instance with a given volumetric radius for raymarching volumetric primitives', 'run the Raymarcher forward pass with ray positions, directions, bounds, and decoded primitive outputs', 'review the Raymarcher class that wraps mvpraymarch for rendering mixtures of volumetric primitives', 'refactor the Raymarcher forward method to support additional render options or primitive types', 'summarize how Raymarcher rescales world coordinates and delegates raymarching to the mvpraymarch extension', 'build a Raymarcher instance with a given volume radius for PyTorch-based raymarching', 'create a raymarching render by passing ray positions, directions, tminmax bounds, and decoder output through Raymarcher', 'test the Raymarcher forward pass with multaccum render option enabled for multiplicative alpha accumulation', 'review the Raymarcher forward method that uses F.grid_sample to warp and sample template features along rays']
```

Usage

```
{'create_Raymarcher_instance': 'create a Raymarcher instance with a given volumetric radius for raymarching volumetric primitives', 'run_Raymarcher_forward': 'run the Raymarcher forward pass with ray positions, directions, bounds, and decoded primitive outputs', 'review_Raymarcher_class': 'review the Raymarcher class that wraps mvpraymarch for rendering mixtures of volumetric primitives', 'refactor_Raymarcher_forward': 'refactor the Raymarcher forward method to support additional render options or primitive types', 'summarize_Raymarcher_usage': 'summarize how Raymarcher rescales world coordinates and delegates raymarching to the mvpraymarch extension'}
```

## File: facebookresearch_mvp/models/raymarchers/stepraymarcher.py

Prompts

```
['create a Raymarcher instance with a given volumetric radius for raymarching volumetric primitives', 'run the Raymarcher forward pass with ray positions, directions, bounds, and decoded primitive outputs', 'review the Raymarcher class that wraps mvpraymarch for rendering mixtures of volumetric primitives', 'refactor the Raymarcher forward method to support additional render options or primitive types', 'summarize how Raymarcher rescales world coordinates and delegates raymarching to the mvpraymarch extension', 'build a Raymarcher instance with a given volume radius for PyTorch-based raymarching', 'create a raymarching render by passing ray positions, directions, tminmax bounds, and decoder output through Raymarcher', 'test the Raymarcher forward pass with multaccum render option enabled for multiplicative alpha accumulation', 'review the Raymarcher forward method that uses F.grid_sample to warp and sample template features along rays']
```

Usage

```
{'build_Raymarcher': 'build a Raymarcher instance with a given volume radius for PyTorch-based raymarching', 'run_Raymarcher_forward': 'run the Raymarcher forward pass with ray positions, directions, and decoder output to render RGBA', 'create_raymarching_render': 'create a raymarching render by passing ray positions, directions, tminmax bounds, and decoder output through Raymarcher', 'test_Raymarcher_multaccum': 'test the Raymarcher forward pass with multaccum render option enabled for multiplicative alpha accumulation', 'review_Raymarcher_grid_sample': 'review the Raymarcher forward method that uses F.grid_sample to warp and sample template features along rays'}
```

