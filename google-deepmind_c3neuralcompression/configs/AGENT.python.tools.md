# Agent Python Tools

- repo: google-deepmind/c3neuralcompression
- repo_uri: https://github.com/google-deepmind/c3_neural_compression

## File: google-deepmind_c3neuralcompression/configs/base.py

Prompts

```
['get the base config object for C3 neural compression training experiments', 'get a config dict with nested model sub-configs for synthesis latents entropy upsampling and quant', 'get the training loop config with steps interval type and checkpoint settings', 'get the config with per-datum metrics logging and gradient norm logging options', 'get the config with cudnn and cuda compress binary arguments for GPU training', 'get the CLIC2020 experiment config with dataset, optimizer, quantization, and model settings for C3 neural compression', 'configure the CLIC2020 dataset path, number of examples, and skip settings via the config object', 'configure the optimizer with cosine decay schedule, STE parameters, and gradient norm clipping for COOL-CHIC optimization', 'configure soft round quantization with Kumaraswamy noise distribution and STE quantization settings for the model', 'configure the synthesis network, latent grids, entropy model, and upsampling settings for the CLIC2020 experiment', 'get the config dict for training a C3 neural compression model on the KODAK dataset', 'customize the KODAK dataset root directory and number of examples in the config', 'tune the optimizer learning rate schedule and STE parameters for KODAK training', 'configure the noise quantization type and Kumaraswamy noise parameters for KODAK experiments', 'adjust the synthesis network layers and latent grid settings for the KODAK config', 'get the UVG video experiment config with dataset, optimizer, quantization, and model settings', 'compute the start patch index and number of patches for a given training worker', 'review the UVG config function to understand dataset, optimizer, and model hyperparameters', 'refactor the UVG config to change the spatial patch size or number of frames', 'summarize how worker_start_patch_idx_and_num_patches distributes video patches across training workers']
```

Usage

```
{'get_config_training': 'get the base config object for C3 neural compression training experiments', 'get_config_model_hierarchy': 'get a config dict with nested model sub-configs for synthesis latents entropy upsampling and quant', 'get_config_training_loop': 'get the training loop config with steps interval type and checkpoint settings', 'get_config_logging': 'get the config with per-datum metrics logging and gradient norm logging options', 'get_config_binary_args': 'get the config with cudnn and cuda compress binary arguments for GPU training'}
```

## File: google-deepmind_c3neuralcompression/configs/clic2020.py

Prompts

```
['get the base config object for C3 neural compression training experiments', 'get a config dict with nested model sub-configs for synthesis latents entropy upsampling and quant', 'get the training loop config with steps interval type and checkpoint settings', 'get the config with per-datum metrics logging and gradient norm logging options', 'get the config with cudnn and cuda compress binary arguments for GPU training', 'get the CLIC2020 experiment config with dataset, optimizer, quantization, and model settings for C3 neural compression', 'configure the CLIC2020 dataset path, number of examples, and skip settings via the config object', 'configure the optimizer with cosine decay schedule, STE parameters, and gradient norm clipping for COOL-CHIC optimization', 'configure soft round quantization with Kumaraswamy noise distribution and STE quantization settings for the model', 'configure the synthesis network, latent grids, entropy model, and upsampling settings for the CLIC2020 experiment', 'get the config dict for training a C3 neural compression model on the KODAK dataset', 'customize the KODAK dataset root directory and number of examples in the config', 'tune the optimizer learning rate schedule and STE parameters for KODAK training', 'configure the noise quantization type and Kumaraswamy noise parameters for KODAK experiments', 'adjust the synthesis network layers and latent grid settings for the KODAK config', 'get the UVG video experiment config with dataset, optimizer, quantization, and model settings', 'compute the start patch index and number of patches for a given training worker', 'review the UVG config function to understand dataset, optimizer, and model hyperparameters', 'refactor the UVG config to change the spatial patch size or number of frames', 'summarize how worker_start_patch_idx_and_num_patches distributes video patches across training workers']
```

Usage

```
{'get_config_CLIC2020': 'get the CLIC2020 experiment config with dataset, optimizer, quantization, and model settings for C3 neural compression', 'configure_dataset_CLIC2020': 'configure the CLIC2020 dataset path, number of examples, and skip settings via the config object', 'configure_optimizer_CLIC2020': 'configure the optimizer with cosine decay schedule, STE parameters, and gradient norm clipping for COOL-CHIC optimization', 'configure_quantization_CLIC2020': 'configure soft round quantization with Kumaraswamy noise distribution and STE quantization settings for the model', 'configure_model_architecture_CLIC2020': 'configure the synthesis network, latent grids, entropy model, and upsampling settings for the CLIC2020 experiment'}
```

## File: google-deepmind_c3neuralcompression/configs/kodak.py

Prompts

```
['get the base config object for C3 neural compression training experiments', 'get a config dict with nested model sub-configs for synthesis latents entropy upsampling and quant', 'get the training loop config with steps interval type and checkpoint settings', 'get the config with per-datum metrics logging and gradient norm logging options', 'get the config with cudnn and cuda compress binary arguments for GPU training', 'get the CLIC2020 experiment config with dataset, optimizer, quantization, and model settings for C3 neural compression', 'configure the CLIC2020 dataset path, number of examples, and skip settings via the config object', 'configure the optimizer with cosine decay schedule, STE parameters, and gradient norm clipping for COOL-CHIC optimization', 'configure soft round quantization with Kumaraswamy noise distribution and STE quantization settings for the model', 'configure the synthesis network, latent grids, entropy model, and upsampling settings for the CLIC2020 experiment', 'get the config dict for training a C3 neural compression model on the KODAK dataset', 'customize the KODAK dataset root directory and number of examples in the config', 'tune the optimizer learning rate schedule and STE parameters for KODAK training', 'configure the noise quantization type and Kumaraswamy noise parameters for KODAK experiments', 'adjust the synthesis network layers and latent grid settings for the KODAK config', 'get the UVG video experiment config with dataset, optimizer, quantization, and model settings', 'compute the start patch index and number of patches for a given training worker', 'review the UVG config function to understand dataset, optimizer, and model hyperparameters', 'refactor the UVG config to change the spatial patch size or number of frames', 'summarize how worker_start_patch_idx_and_num_patches distributes video patches across training workers']
```

Usage

```
{'get_config_kodak': 'get the config dict for training a C3 neural compression model on the KODAK dataset', 'customize_kodak_dataset_config': 'customize the KODAK dataset root directory and number of examples in the config', 'tune_optimizer_config': 'tune the optimizer learning rate schedule and STE parameters for KODAK training', 'configure_quantization': 'configure the noise quantization type and Kumaraswamy noise parameters for KODAK experiments', 'adjust_model_architecture': 'adjust the synthesis network layers and latent grid settings for the KODAK config'}
```

## File: google-deepmind_c3neuralcompression/configs/uvg.py

Prompts

```
['get the base config object for C3 neural compression training experiments', 'get a config dict with nested model sub-configs for synthesis latents entropy upsampling and quant', 'get the training loop config with steps interval type and checkpoint settings', 'get the config with per-datum metrics logging and gradient norm logging options', 'get the config with cudnn and cuda compress binary arguments for GPU training', 'get the CLIC2020 experiment config with dataset, optimizer, quantization, and model settings for C3 neural compression', 'configure the CLIC2020 dataset path, number of examples, and skip settings via the config object', 'configure the optimizer with cosine decay schedule, STE parameters, and gradient norm clipping for COOL-CHIC optimization', 'configure soft round quantization with Kumaraswamy noise distribution and STE quantization settings for the model', 'configure the synthesis network, latent grids, entropy model, and upsampling settings for the CLIC2020 experiment', 'get the config dict for training a C3 neural compression model on the KODAK dataset', 'customize the KODAK dataset root directory and number of examples in the config', 'tune the optimizer learning rate schedule and STE parameters for KODAK training', 'configure the noise quantization type and Kumaraswamy noise parameters for KODAK experiments', 'adjust the synthesis network layers and latent grid settings for the KODAK config', 'get the UVG video experiment config with dataset, optimizer, quantization, and model settings', 'compute the start patch index and number of patches for a given training worker', 'review the UVG config function to understand dataset, optimizer, and model hyperparameters', 'refactor the UVG config to change the spatial patch size or number of frames', 'summarize how worker_start_patch_idx_and_num_patches distributes video patches across training workers']
```

Usage

```
{'get_config_uvg': 'get the UVG video experiment config with dataset, optimizer, quantization, and model settings', 'worker_start_patch_idx_and_num_patches': 'compute the start patch index and number of patches for a given training worker', 'review_get_config': 'review the UVG config function to understand dataset, optimizer, and model hyperparameters', 'refactor_get_config': 'refactor the UVG config to change the spatial patch size or number of frames', 'summarize_worker_start_patch_idx_and_num_patches': 'summarize how worker_start_patch_idx_and_num_patches distributes video patches across training workers'}
```

