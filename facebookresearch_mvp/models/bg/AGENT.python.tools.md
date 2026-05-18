# Agent Python Tools

- repo: facebookresearch/mvp
- repo_uri: https://github.com/facebookresearch/mvp

## File: facebookresearch_mvp/models/bg/lap.py

Prompts

```
['create an ImageMod module that samples a learnable image tensor using grid_sample with sample coordinates', 'create a LapImage Laplacian pyramid module that stacks multiple ImageMod layers at different resolutions', 'create a BGModel background model that renders camera-specific background images using a Laplacian pyramid', 'review the ImageMod forward method that expands and grid-samples the image tensor by sample coordinates', 'review the BGModel forward method that combines sample coordinates with camera index for background rendering', 'build a forward pass through BGModel using ray positions, directions, and camera indices', 'review the BGModel forward method and its sinusoidal positional encoding for ray positions', 'test the BGModel mlp1 and mlp2 decoder layers with Conv2dELR and LeakyReLU activations', 'refactor the BGModel background sampling logic to use grid_sample for coordinate-based lookups']
```

Usage

```
{'create_ImageMod': 'create an ImageMod module that samples a learnable image tensor using grid_sample with sample coordinates', 'create_LapImage': 'create a LapImage Laplacian pyramid module that stacks multiple ImageMod layers at different resolutions', 'create_BGModel': 'create a BGModel background model that renders camera-specific background images using a Laplacian pyramid', 'review_ImageMod_forward': 'review the ImageMod forward method that expands and grid-samples the image tensor by sample coordinates', 'review_BGModel_forward': 'review the BGModel forward method that combines sample coordinates with camera index for background rendering'}
```

## File: facebookresearch_mvp/models/bg/mlp.py

Prompts

```
['create an ImageMod module that samples a learnable image tensor using grid_sample with sample coordinates', 'create a LapImage Laplacian pyramid module that stacks multiple ImageMod layers at different resolutions', 'create a BGModel background model that renders camera-specific background images using a Laplacian pyramid', 'review the ImageMod forward method that expands and grid-samples the image tensor by sample coordinates', 'review the BGModel forward method that combines sample coordinates with camera index for background rendering', 'build a forward pass through BGModel using ray positions, directions, and camera indices', 'review the BGModel forward method and its sinusoidal positional encoding for ray positions', 'test the BGModel mlp1 and mlp2 decoder layers with Conv2dELR and LeakyReLU activations', 'refactor the BGModel background sampling logic to use grid_sample for coordinate-based lookups']
```

Usage

```
{'create_BGModel': 'create a BGModel instance with width, height, and allcameras for background rendering', 'build_BGModel_forward': 'build a forward pass through BGModel using ray positions, directions, and camera indices', 'review_BGModel_positional_encoding': 'review the BGModel forward method and its sinusoidal positional encoding for ray positions', 'test_BGModel_mlp_layers': 'test the BGModel mlp1 and mlp2 decoder layers with Conv2dELR and LeakyReLU activations', 'refactor_BGModel_bg_sampling': 'refactor the BGModel background sampling logic to use grid_sample for coordinate-based lookups'}
```

