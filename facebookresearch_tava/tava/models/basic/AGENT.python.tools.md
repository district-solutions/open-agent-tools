# Agent Python Tools

- repo: facebookresearch/tava
- repo_uri: https://github.com/facebookresearch/tava

## File: facebookresearch_tava/tava/models/basic/mipnerf.py

Prompts

```
['build a MipNerfModel with an MLP, positional encoding, and view encoding for NeRF rendering', 'run volumetric rendering on RGB, density, and t_vals to compute composite color and depth', 'create a Gaussian approximation from a conical frustum with stable mean and variance computation', 'sample points along camera rays using stratified sampling with near and far clipping planes', 'resample points along rays using a piecewise constant PDF weighted by coarse level importance', 'build a NeRF MLP model with configurable depth, width, skip connections, and conditional branches for RGB and sigma prediction', 'create a linear dense layer with Xavier uniform weight initialization and zero bias', 'query the sigma values and hidden features from an MLP for points in canonical space with optional masking', 'query view-dependent RGB colors from an MLP using interpolated features and optional view direction conditions', 'build a simplified StraightMLP subclass that outputs only sigma channels without RGB or conditional branches', 'build a NeRF model with coarse and fine MLPs for volumetric scene rendering', 'create stratified samples along camera rays between near and far clipping planes', 'test piecewise constant PDF sampling for hierarchical NeRF ray sampling', 'review the hierarchical PDF sampling function that combines coarse and fine samples', 'build a PositionalEncoder to encode 3D coordinates using sinusoidal features with configurable frequency bands', 'create an IntegratedPositionalEncoder to encode coordinates with covariance-aware sinusoidal features', 'test the WindowedPositionalEncoder forward pass with an alpha annealing parameter for frequency band scheduling', 'review the IntegratedPositionalEncoder _expected_sin method that estimates mean and variance of sin under Gaussian noise', 'summarize the WindowedPositionalEncoder cosine_easing_window method that generates a cosine-based annealing schedule for frequency bands']
```

Usage

```
{'build_MipNerfModel': 'build a MipNerfModel with an MLP, positional encoding, and view encoding for NeRF rendering', 'run_volumetric_rendering': 'run volumetric rendering on RGB, density, and t_vals to compute composite color and depth', 'create_conical_frustum_to_gaussian': 'create a Gaussian approximation from a conical frustum with stable mean and variance computation', 'sample_along_rays': 'sample points along camera rays using stratified sampling with near and far clipping planes', 'resample_along_rays': 'resample points along rays using a piecewise constant PDF weighted by coarse level importance'}
```

## File: facebookresearch_tava/tava/models/basic/mlp.py

Prompts

```
['build a MipNerfModel with an MLP, positional encoding, and view encoding for NeRF rendering', 'run volumetric rendering on RGB, density, and t_vals to compute composite color and depth', 'create a Gaussian approximation from a conical frustum with stable mean and variance computation', 'sample points along camera rays using stratified sampling with near and far clipping planes', 'resample points along rays using a piecewise constant PDF weighted by coarse level importance', 'build a NeRF MLP model with configurable depth, width, skip connections, and conditional branches for RGB and sigma prediction', 'create a linear dense layer with Xavier uniform weight initialization and zero bias', 'query the sigma values and hidden features from an MLP for points in canonical space with optional masking', 'query view-dependent RGB colors from an MLP using interpolated features and optional view direction conditions', 'build a simplified StraightMLP subclass that outputs only sigma channels without RGB or conditional branches', 'build a NeRF model with coarse and fine MLPs for volumetric scene rendering', 'create stratified samples along camera rays between near and far clipping planes', 'test piecewise constant PDF sampling for hierarchical NeRF ray sampling', 'review the hierarchical PDF sampling function that combines coarse and fine samples', 'build a PositionalEncoder to encode 3D coordinates using sinusoidal features with configurable frequency bands', 'create an IntegratedPositionalEncoder to encode coordinates with covariance-aware sinusoidal features', 'test the WindowedPositionalEncoder forward pass with an alpha annealing parameter for frequency band scheduling', 'review the IntegratedPositionalEncoder _expected_sin method that estimates mean and variance of sin under Gaussian noise', 'summarize the WindowedPositionalEncoder cosine_easing_window method that generates a cosine-based annealing schedule for frequency bands']
```

Usage

```
{'build_MLP_for_NeRF': 'build a NeRF MLP model with configurable depth, width, skip connections, and conditional branches for RGB and sigma prediction', 'create_dense_layer': 'create a linear dense layer with Xavier uniform weight initialization and zero bias', 'query_sigma_from_MLP': 'query the sigma values and hidden features from an MLP for points in canonical space with optional masking', 'query_rgb_from_MLP': 'query view-dependent RGB colors from an MLP using interpolated features and optional view direction conditions', 'build_StraightMLP': 'build a simplified StraightMLP subclass that outputs only sigma channels without RGB or conditional branches'}
```

## File: facebookresearch_tava/tava/models/basic/nerf.py

Prompts

```
['build a MipNerfModel with an MLP, positional encoding, and view encoding for NeRF rendering', 'run volumetric rendering on RGB, density, and t_vals to compute composite color and depth', 'create a Gaussian approximation from a conical frustum with stable mean and variance computation', 'sample points along camera rays using stratified sampling with near and far clipping planes', 'resample points along rays using a piecewise constant PDF weighted by coarse level importance', 'build a NeRF MLP model with configurable depth, width, skip connections, and conditional branches for RGB and sigma prediction', 'create a linear dense layer with Xavier uniform weight initialization and zero bias', 'query the sigma values and hidden features from an MLP for points in canonical space with optional masking', 'query view-dependent RGB colors from an MLP using interpolated features and optional view direction conditions', 'build a simplified StraightMLP subclass that outputs only sigma channels without RGB or conditional branches', 'build a NeRF model with coarse and fine MLPs for volumetric scene rendering', 'create stratified samples along camera rays between near and far clipping planes', 'test piecewise constant PDF sampling for hierarchical NeRF ray sampling', 'review the hierarchical PDF sampling function that combines coarse and fine samples', 'build a PositionalEncoder to encode 3D coordinates using sinusoidal features with configurable frequency bands', 'create an IntegratedPositionalEncoder to encode coordinates with covariance-aware sinusoidal features', 'test the WindowedPositionalEncoder forward pass with an alpha annealing parameter for frequency band scheduling', 'review the IntegratedPositionalEncoder _expected_sin method that estimates mean and variance of sin under Gaussian noise', 'summarize the WindowedPositionalEncoder cosine_easing_window method that generates a cosine-based annealing schedule for frequency bands']
```

Usage

```
{'build_NerfModel': 'build a NeRF model with coarse and fine MLPs for volumetric scene rendering', 'run_volumetric_rendering': 'run volumetric rendering on RGB and density samples along camera rays', 'create_sample_along_rays': 'create stratified samples along camera rays between near and far clipping planes', 'test_piecewise_constant_pdf': 'test piecewise constant PDF sampling for hierarchical NeRF ray sampling', 'review_sample_pdf': 'review the hierarchical PDF sampling function that combines coarse and fine samples'}
```

## File: facebookresearch_tava/tava/models/basic/posi_enc.py

Prompts

```
['build a MipNerfModel with an MLP, positional encoding, and view encoding for NeRF rendering', 'run volumetric rendering on RGB, density, and t_vals to compute composite color and depth', 'create a Gaussian approximation from a conical frustum with stable mean and variance computation', 'sample points along camera rays using stratified sampling with near and far clipping planes', 'resample points along rays using a piecewise constant PDF weighted by coarse level importance', 'build a NeRF MLP model with configurable depth, width, skip connections, and conditional branches for RGB and sigma prediction', 'create a linear dense layer with Xavier uniform weight initialization and zero bias', 'query the sigma values and hidden features from an MLP for points in canonical space with optional masking', 'query view-dependent RGB colors from an MLP using interpolated features and optional view direction conditions', 'build a simplified StraightMLP subclass that outputs only sigma channels without RGB or conditional branches', 'build a NeRF model with coarse and fine MLPs for volumetric scene rendering', 'create stratified samples along camera rays between near and far clipping planes', 'test piecewise constant PDF sampling for hierarchical NeRF ray sampling', 'review the hierarchical PDF sampling function that combines coarse and fine samples', 'build a PositionalEncoder to encode 3D coordinates using sinusoidal features with configurable frequency bands', 'create an IntegratedPositionalEncoder to encode coordinates with covariance-aware sinusoidal features', 'test the WindowedPositionalEncoder forward pass with an alpha annealing parameter for frequency band scheduling', 'review the IntegratedPositionalEncoder _expected_sin method that estimates mean and variance of sin under Gaussian noise', 'summarize the WindowedPositionalEncoder cosine_easing_window method that generates a cosine-based annealing schedule for frequency bands']
```

Usage

```
{'build_positional_encoder': 'build a PositionalEncoder to encode 3D coordinates using sinusoidal features with configurable frequency bands', 'create_integrated_positional_encoder': 'create an IntegratedPositionalEncoder to encode coordinates with covariance-aware sinusoidal features', 'test_windowed_positional_encoder': 'test the WindowedPositionalEncoder forward pass with an alpha annealing parameter for frequency band scheduling', 'review_expected_sin': 'review the IntegratedPositionalEncoder _expected_sin method that estimates mean and variance of sin under Gaussian noise', 'summarize_cosine_easing_window': 'summarize the WindowedPositionalEncoder cosine_easing_window method that generates a cosine-based annealing schedule for frequency bands'}
```

