# Agent Python Tools

- repo: facebookresearch/fashionplus
- repo_uri: https://github.com/facebookresearch/fashionplus

## File: facebookresearch_fashionplus/generation/options/base_options.py

Prompts

```
['initialize a BaseOptions instance with argparse arguments for pix2pixHD model training and testing', 'parse command line arguments and save options to an opt.txt file in the experiment directory', 'get parsed options with GPU ID parsing and device selection without saving to disk', 'configure generator network options including filter count, downsampling layers, and residual blocks', 'configure data loading options including batch size, image dimensions, label channels, and dataset paths', 'run test inference on fashion images using TestOptions with --ntest and --how_many arguments', 'parse command line test options for fashion image generation using TestOptions.parse()', 'export the fashion generation model to ONNX format using the --export_onnx argument', 'run a serialized TensorRT engine for fashion image inference using the --engine argument', 'swap an outfit piece between reference and condition images using --reference_idx --condition_idx --swap_piece', 'parse command line arguments to get training options for the GAN model with all defaults applied', 'get parsed training options without printing or saving them to disk using get_opt method', 'configure the initial learning rate and decay schedule for the Adam optimizer during training', 'set loss function weights for feature matching, VGG perceptual, style, reconstruction, and KL divergence losses', 'configure the number of discriminators, layer count, and filter size for the discriminator network']
```

Usage

```
{'initialize_BaseOptions': 'initialize a BaseOptions instance with argparse arguments for pix2pixHD model training and testing', 'parse_BaseOptions': 'parse command line arguments and save options to an opt.txt file in the experiment directory', 'get_opt_BaseOptions': 'get parsed options with GPU ID parsing and device selection without saving to disk', 'configure_generator_options': 'configure generator network options including filter count, downsampling layers, and residual blocks', 'configure_data_options': 'configure data loading options including batch size, image dimensions, label channels, and dataset paths'}
```

## File: facebookresearch_fashionplus/generation/options/test_options.py

Prompts

```
['initialize a BaseOptions instance with argparse arguments for pix2pixHD model training and testing', 'parse command line arguments and save options to an opt.txt file in the experiment directory', 'get parsed options with GPU ID parsing and device selection without saving to disk', 'configure generator network options including filter count, downsampling layers, and residual blocks', 'configure data loading options including batch size, image dimensions, label channels, and dataset paths', 'run test inference on fashion images using TestOptions with --ntest and --how_many arguments', 'parse command line test options for fashion image generation using TestOptions.parse()', 'export the fashion generation model to ONNX format using the --export_onnx argument', 'run a serialized TensorRT engine for fashion image inference using the --engine argument', 'swap an outfit piece between reference and condition images using --reference_idx --condition_idx --swap_piece', 'parse command line arguments to get training options for the GAN model with all defaults applied', 'get parsed training options without printing or saving them to disk using get_opt method', 'configure the initial learning rate and decay schedule for the Adam optimizer during training', 'set loss function weights for feature matching, VGG perceptual, style, reconstruction, and KL divergence losses', 'configure the number of discriminators, layer count, and filter size for the discriminator network']
```

Usage

```
{'run_test_inference': 'run test inference on fashion images using TestOptions with --ntest and --how_many arguments', 'parse_test_options': 'parse command line test options for fashion image generation using TestOptions.parse()', 'export_onnx_model': 'export the fashion generation model to ONNX format using the --export_onnx argument', 'run_trt_engine': 'run a serialized TensorRT engine for fashion image inference using the --engine argument', 'swap_outfit_piece': 'swap an outfit piece between reference and condition images using --reference_idx --condition_idx --swap_piece'}
```

## File: facebookresearch_fashionplus/generation/options/train_options.py

Prompts

```
['initialize a BaseOptions instance with argparse arguments for pix2pixHD model training and testing', 'parse command line arguments and save options to an opt.txt file in the experiment directory', 'get parsed options with GPU ID parsing and device selection without saving to disk', 'configure generator network options including filter count, downsampling layers, and residual blocks', 'configure data loading options including batch size, image dimensions, label channels, and dataset paths', 'run test inference on fashion images using TestOptions with --ntest and --how_many arguments', 'parse command line test options for fashion image generation using TestOptions.parse()', 'export the fashion generation model to ONNX format using the --export_onnx argument', 'run a serialized TensorRT engine for fashion image inference using the --engine argument', 'swap an outfit piece between reference and condition images using --reference_idx --condition_idx --swap_piece', 'parse command line arguments to get training options for the GAN model with all defaults applied', 'get parsed training options without printing or saving them to disk using get_opt method', 'configure the initial learning rate and decay schedule for the Adam optimizer during training', 'set loss function weights for feature matching, VGG perceptual, style, reconstruction, and KL divergence losses', 'configure the number of discriminators, layer count, and filter size for the discriminator network']
```

Usage

```
{'parse_train_options': 'parse command line arguments to get training options for the GAN model with all defaults applied', 'get_train_opt': 'get parsed training options without printing or saving them to disk using get_opt method', 'configure_learning_rate': 'configure the initial learning rate and decay schedule for the Adam optimizer during training', 'set_loss_weights': 'set loss function weights for feature matching, VGG perceptual, style, reconstruction, and KL divergence losses', 'configure_discriminator': 'configure the number of discriminators, layer count, and filter size for the discriminator network'}
```

