# Agent Python Tools

- repo: google-deepmind/c3neuralcompression
- repo_uri: https://github.com/google-deepmind/c3_neural_compression

## File: google-deepmind_c3neuralcompression/utils/data_loading.py

Prompts

```
['load the Kodak image dataset with automatic download and optional transform pipeline', 'load the CLIC2020 validation image dataset with automatic download and transform pipeline', 'load the UVG video dataset with configurable patch size and frame count', 'create a Kodak dataset instance with force download and custom transform callable', 'create a UVG dataset instance and load a single video patch by 3D index', 'log the number of parameters, byte size, and shapes for a Haiku model', 'partition Haiku parameters into two groups based on whether a key string appears in their name', 'partition Haiku parameters into two groups based on whether a key string appears in their module name', 'merge two sets of Haiku parameters into a single combined parameter set', 'create an optax optimizer with optional gradient clipping, cosine decay schedule, or fixed learning rate', 'compute MACs per pixel for a C3-like neural compression model given input shape and layer configs', 'calculate multiply-accumulate operations per output pixel for a multi-layer perceptron forward pass', 'calculate MACs per output pixel for a ConvND layer given kernel shape and channel counts', 'compute MACs per pixel for upsampling latent grids using bilinear interpolation for images or videos', 'estimate total MACs per pixel including entropy model, synthesis model, and interpolation for C3 compression']
```

Usage

```
{'load_dataset_kodak': 'load the Kodak image dataset with automatic download and optional transform pipeline', 'load_dataset_clic2020': 'load the CLIC2020 validation image dataset with automatic download and transform pipeline', 'load_dataset_uvg': 'load the UVG video dataset with configurable patch size and frame count', 'create_kodak_dataset': 'create a Kodak dataset instance with force download and custom transform callable', 'create_uvg_patch_loader': 'create a UVG dataset instance and load a single video patch by 3D index'}
```

## File: google-deepmind_c3neuralcompression/utils/experiment.py

Prompts

```
['load the Kodak image dataset with automatic download and optional transform pipeline', 'load the CLIC2020 validation image dataset with automatic download and transform pipeline', 'load the UVG video dataset with configurable patch size and frame count', 'create a Kodak dataset instance with force download and custom transform callable', 'create a UVG dataset instance and load a single video patch by 3D index', 'log the number of parameters, byte size, and shapes for a Haiku model', 'partition Haiku parameters into two groups based on whether a key string appears in their name', 'partition Haiku parameters into two groups based on whether a key string appears in their module name', 'merge two sets of Haiku parameters into a single combined parameter set', 'create an optax optimizer with optional gradient clipping, cosine decay schedule, or fixed learning rate', 'compute MACs per pixel for a C3-like neural compression model given input shape and layer configs', 'calculate multiply-accumulate operations per output pixel for a multi-layer perceptron forward pass', 'calculate MACs per output pixel for a ConvND layer given kernel shape and channel counts', 'compute MACs per pixel for upsampling latent grids using bilinear interpolation for images or videos', 'estimate total MACs per pixel including entropy model, synthesis model, and interpolation for C3 compression']
```

Usage

```
{'log_params_info': 'log the number of parameters, byte size, and shapes for a Haiku model', 'partition_params_by_name': 'partition Haiku parameters into two groups based on whether a key string appears in their name', 'partition_params_by_module_name': 'partition Haiku parameters into two groups based on whether a key string appears in their module name', 'merge_params': 'merge two sets of Haiku parameters into a single combined parameter set', 'make_opt': 'create an optax optimizer with optional gradient clipping, cosine decay schedule, or fixed learning rate'}
```

## File: google-deepmind_c3neuralcompression/utils/macs.py

Prompts

```
['load the Kodak image dataset with automatic download and optional transform pipeline', 'load the CLIC2020 validation image dataset with automatic download and transform pipeline', 'load the UVG video dataset with configurable patch size and frame count', 'create a Kodak dataset instance with force download and custom transform callable', 'create a UVG dataset instance and load a single video patch by 3D index', 'log the number of parameters, byte size, and shapes for a Haiku model', 'partition Haiku parameters into two groups based on whether a key string appears in their name', 'partition Haiku parameters into two groups based on whether a key string appears in their module name', 'merge two sets of Haiku parameters into a single combined parameter set', 'create an optax optimizer with optional gradient clipping, cosine decay schedule, or fixed learning rate', 'compute MACs per pixel for a C3-like neural compression model given input shape and layer configs', 'calculate multiply-accumulate operations per output pixel for a multi-layer perceptron forward pass', 'calculate MACs per output pixel for a ConvND layer given kernel shape and channel counts', 'compute MACs per pixel for upsampling latent grids using bilinear interpolation for images or videos', 'estimate total MACs per pixel including entropy model, synthesis model, and interpolation for C3 compression']
```

Usage

```
{'compute_macs_per_pixel': 'compute MACs per pixel for a C3-like neural compression model given input shape and layer configs', 'calculate_mlp_macs': 'calculate multiply-accumulate operations per output pixel for a multi-layer perceptron forward pass', 'calculate_conv_macs': 'calculate MACs per output pixel for a ConvND layer given kernel shape and channel counts', 'compute_upsampling_macs': 'compute MACs per pixel for upsampling latent grids using bilinear interpolation for images or videos', 'estimate_model_complexity': 'estimate total MACs per pixel including entropy model, synthesis model, and interpolation for C3 compression'}
```

