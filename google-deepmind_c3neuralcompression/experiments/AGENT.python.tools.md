# Agent Python Tools

- repo: google-deepmind/c3neuralcompression
- repo_uri: https://github.com/google-deepmind/c3_neural_compression

## File: google-deepmind_c3neuralcompression/experiments/base.py

Prompts

```
['build a C3 compression experiment optimizer with Adam and optional cosine decay schedule', 'create latent grids for neural compression using configurable quantization type and input resolution', 'synthesize an image or video reconstruction from upsampled latent grids using the synthesis model', 'count multiply-accumulate operations per pixel for the C3 synthesis and entropy model architecture', 'review the C3 base experiment class abstract methods and concrete utility methods for neural compression', 'run the C3 per data-point image compression experiment via jaxline platform with a config file', 'train C3 model parameters on a single image using noise quantization followed by STE refinement', 'evaluate a trained C3 model on an image and return PSNR, SSIM, distortion, and rate metrics', 'search over quantization step values for weights and biases to find the best rate-distortion tradeoff', 'count the total number of latent variables for a given input resolution using the Experiment class', 'run the C3 video compression experiment using Jaxline platform with a config file', 'fit a single video datum through noise quantization and STE training phases', 'evaluate video reconstruction quality computing PSNR SSIM and rate metrics', 'create a custom mask for the entropy model previous latent frame context']
```

Usage

```
{'build_experiment_optimizer': 'build a C3 compression experiment optimizer with Adam and optional cosine decay schedule', 'create_latent_grids': 'create latent grids for neural compression using configurable quantization type and input resolution', 'synthesize_from_latents': 'synthesize an image or video reconstruction from upsampled latent grids using the synthesis model', 'count_macs_per_pixel': 'count multiply-accumulate operations per pixel for the C3 synthesis and entropy model architecture', 'review_experiment_base_class': 'review the C3 base experiment class abstract methods and concrete utility methods for neural compression'}
```

## File: google-deepmind_c3neuralcompression/experiments/image.py

Prompts

```
['build a C3 compression experiment optimizer with Adam and optional cosine decay schedule', 'create latent grids for neural compression using configurable quantization type and input resolution', 'synthesize an image or video reconstruction from upsampled latent grids using the synthesis model', 'count multiply-accumulate operations per pixel for the C3 synthesis and entropy model architecture', 'review the C3 base experiment class abstract methods and concrete utility methods for neural compression', 'run the C3 per data-point image compression experiment via jaxline platform with a config file', 'train C3 model parameters on a single image using noise quantization followed by STE refinement', 'evaluate a trained C3 model on an image and return PSNR, SSIM, distortion, and rate metrics', 'search over quantization step values for weights and biases to find the best rate-distortion tradeoff', 'count the total number of latent variables for a given input resolution using the Experiment class', 'run the C3 video compression experiment using Jaxline platform with a config file', 'fit a single video datum through noise quantization and STE training phases', 'evaluate video reconstruction quality computing PSNR SSIM and rate metrics', 'create a custom mask for the entropy model previous latent frame context']
```

Usage

```
{'run_c3_image_experiment': 'run the C3 per data-point image compression experiment via jaxline platform with a config file', 'fit_datum_train_params': 'train C3 model parameters on a single image using noise quantization followed by STE refinement', 'eval_image_compression_metrics': 'evaluate a trained C3 model on an image and return PSNR, SSIM, distortion, and rate metrics', 'search_quantization_steps': 'search over quantization step values for weights and biases to find the best rate-distortion tradeoff', 'count_latent_variables': 'count the total number of latent variables for a given input resolution using the Experiment class'}
```

## File: google-deepmind_c3neuralcompression/experiments/video.py

Prompts

```
['build a C3 compression experiment optimizer with Adam and optional cosine decay schedule', 'create latent grids for neural compression using configurable quantization type and input resolution', 'synthesize an image or video reconstruction from upsampled latent grids using the synthesis model', 'count multiply-accumulate operations per pixel for the C3 synthesis and entropy model architecture', 'review the C3 base experiment class abstract methods and concrete utility methods for neural compression', 'run the C3 per data-point image compression experiment via jaxline platform with a config file', 'train C3 model parameters on a single image using noise quantization followed by STE refinement', 'evaluate a trained C3 model on an image and return PSNR, SSIM, distortion, and rate metrics', 'search over quantization step values for weights and biases to find the best rate-distortion tradeoff', 'count the total number of latent variables for a given input resolution using the Experiment class', 'run the C3 video compression experiment using Jaxline platform with a config file', 'fit a single video datum through noise quantization and STE training phases', 'evaluate video reconstruction quality computing PSNR SSIM and rate metrics', 'create a custom mask for the entropy model previous latent frame context']
```

Usage

```
{'run_video_compression_experiment': 'run the C3 video compression experiment using Jaxline platform with a config file', 'fit_video_datum': 'fit a single video datum through noise quantization and STE training phases', 'evaluate_video_reconstruction': 'evaluate video reconstruction quality computing PSNR SSIM and rate metrics', 'search_quantization_steps': 'search for optimal weight and bias quantization step sizes for the model', 'create_custom_entropy_mask': 'create a custom mask for the entropy model previous latent frame context'}
```

