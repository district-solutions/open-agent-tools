# Agent Python Tools

- repo: facebookresearch/icgan
- repo_uri: https://github.com/facebookresearch/ic_gan

## File: facebookresearch_icgan/inference/generate_images.py

Prompts

```
['run the script to generate images using a pre-trained IC-GAN or CC-IC-GAN model with instance conditioning', 'run get_data to load k-means instance features and image transforms from a stored dataset', 'run get_model to load a pre-trained BigGAN or StyleGAN2 generator from experiment config', 'run get_conditionings to prepare noise vectors, instance features, and class labels for generation', 'run main to generate a grid of conditioned images and save as a high-resolution PNG figure', 'load a BigGAN or StyleGAN2 generator network from checkpoint weights for inference', 'sample generated images from a BigGAN or StyleGAN2 generator given noise and conditioning', 'prepare a sampling function and inception moments filename for FID metric computation', 'add a --model_backbone CLI argument to an argparse parser with biggan or stylegan2 choices', 'configure class label sampling with long-tail distribution weights for generator inference']
```

Usage

```
{'run_generate_images': 'run the script to generate images using a pre-trained IC-GAN or CC-IC-GAN model with instance conditioning', 'run_get_data': 'run get_data to load k-means instance features and image transforms from a stored dataset', 'run_get_model': 'run get_model to load a pre-trained BigGAN or StyleGAN2 generator from experiment config', 'run_get_conditionings': 'run get_conditionings to prepare noise vectors, instance features, and class labels for generation', 'run_main': 'run main to generate a grid of conditioned images and save as a high-resolution PNG figure'}
```

## File: facebookresearch_icgan/inference/utils.py

Prompts

```
['run the script to generate images using a pre-trained IC-GAN or CC-IC-GAN model with instance conditioning', 'run get_data to load k-means instance features and image transforms from a stored dataset', 'run get_model to load a pre-trained BigGAN or StyleGAN2 generator from experiment config', 'run get_conditionings to prepare noise vectors, instance features, and class labels for generation', 'run main to generate a grid of conditioned images and save as a high-resolution PNG figure', 'load a BigGAN or StyleGAN2 generator network from checkpoint weights for inference', 'sample generated images from a BigGAN or StyleGAN2 generator given noise and conditioning', 'prepare a sampling function and inception moments filename for FID metric computation', 'add a --model_backbone CLI argument to an argparse parser with biggan or stylegan2 choices', 'configure class label sampling with long-tail distribution weights for generator inference']
```

Usage

```
{'load_generator_for_inference': 'load a BigGAN or StyleGAN2 generator network from checkpoint weights for inference', 'sample_generated_images': 'sample generated images from a BigGAN or StyleGAN2 generator given noise and conditioning', 'prepare_sampling_function': 'prepare a sampling function and inception moments filename for FID metric computation', 'add_backbone_cli_argument': 'add a --model_backbone CLI argument to an argparse parser with biggan or stylegan2 choices', 'configure_longtail_sampling': 'configure class label sampling with long-tail distribution weights for generator inference'}
```

