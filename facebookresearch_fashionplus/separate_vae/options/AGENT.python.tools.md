# Agent Python Tools

- repo: facebookresearch/fashionplus
- repo_uri: https://github.com/facebookresearch/fashionplus

## File: facebookresearch_fashionplus/separate_vae/options/base_options.py

Prompts

```
['initialize the BaseOptions class to register all training and model arguments for the fashion VAE', 'parse command line arguments and save experiment options to a text file in the checkpoints directory', 'get parsed options with GPU device setup without saving to disk for quick access', 'configure the generator network architecture using which_model_netG, ngf, and n_downsample_global arguments', 'configure encoder and decoder weight sharing using share_encoder and share_decoder flags', 'run test inference on fashion VAE model using TestOptions with custom results directory and epoch', 'parse command line arguments for the fashion VAE test phase using TestOptions parser', 'export the fashion VAE model to ONNX format using the export_onnx argument in TestOptions', 'swap clothing pieces between reference and condition images using swap_piece reference_idx and condition_idx', 'load pre-computed clustered features from a numpy file using cluster_path and load_feat_dir arguments']
```

Usage

```
{'initialize_base_options_parser': 'initialize the BaseOptions class to register all training and model arguments for the fashion VAE', 'parse_base_options': 'parse command line arguments and save experiment options to a text file in the checkpoints directory', 'get_opt_base_options': 'get parsed options with GPU device setup without saving to disk for quick access', 'configure_generator_model': 'configure the generator network architecture using which_model_netG, ngf, and n_downsample_global arguments', 'configure_encoder_decoder_sharing': 'configure encoder and decoder weight sharing using share_encoder and share_decoder flags'}
```

## File: facebookresearch_fashionplus/separate_vae/options/test_options.py

Prompts

```
['initialize the BaseOptions class to register all training and model arguments for the fashion VAE', 'parse command line arguments and save experiment options to a text file in the checkpoints directory', 'get parsed options with GPU device setup without saving to disk for quick access', 'configure the generator network architecture using which_model_netG, ngf, and n_downsample_global arguments', 'configure encoder and decoder weight sharing using share_encoder and share_decoder flags', 'run test inference on fashion VAE model using TestOptions with custom results directory and epoch', 'parse command line arguments for the fashion VAE test phase using TestOptions parser', 'export the fashion VAE model to ONNX format using the export_onnx argument in TestOptions', 'swap clothing pieces between reference and condition images using swap_piece reference_idx and condition_idx', 'load pre-computed clustered features from a numpy file using cluster_path and load_feat_dir arguments']
```

Usage

```
{'run_test_inference': 'run test inference on fashion VAE model using TestOptions with custom results directory and epoch', 'parse_test_arguments': 'parse command line arguments for the fashion VAE test phase using TestOptions parser', 'export_onnx_model': 'export the fashion VAE model to ONNX format using the export_onnx argument in TestOptions', 'swap_clothing_pieces': 'swap clothing pieces between reference and condition images using swap_piece reference_idx and condition_idx', 'load_clustered_features': 'load pre-computed clustered features from a numpy file using cluster_path and load_feat_dir arguments'}
```

