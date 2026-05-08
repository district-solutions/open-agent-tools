# Agent Python Tools

- repo: facebookresearch/rcdm
- repo_uri: https://github.com/facebookresearch/rcdm

## File: facebookresearch_rcdm/scripts/image_sample.py

Prompts

```
['run the image_sample script to generate conditioned image samples using an RCDM diffusion model', 'run image sampling conditioned on SSL features from DINO or similar self-supervised models', 'run the image_sample script with DDIM sampling instead of standard p_sample_loop for faster generation', 'run image sampling using a custom trained model checkpoint loaded from a specified model path', 'run batch image generation with configurable batch size and save results as a JPEG grid', 'run image sample interpolation between two images using a diffusion model conditioned on SSL features', 'run the interpolation CLI with --first_image_path and --second_image_path to generate interpolated samples', 'create interpolated vectors between two points in latent space using linear interpolation with configurable steps', 'review the exclude_bias_and_norm function that filters parameters by checking if they are 1-dimensional', 'summarize the main function that loads SSL and diffusion models, computes feature embeddings, and generates interpolated images', 'run the image sample manipulation script to transfer attributes from one image to another using RCDM diffusion', 'generate normalized embeddings from a data loader using an SSL model and optional MLP projection', 'find the 20 nearest neighbors of a target embedding using FAISS with GPU or IVF index', 'compute squared L2 distance between an SSL model feature and a target tensor', 'create an argument parser with RCDM diffusion defaults and image manipulation specific flags', 'run a conditional representation-based diffusion model training loop on images using an SSL model', 'run a diffusion model training loop on images without an SSL conditioning model', 'create an argparse parser with defaults for RCDM image training including learning rate and batch size', 'create a data generator that extracts SSL features from images for conditional diffusion model training', 'review the main training flow that initializes distributed mode, loads SSL models, and runs the training loop']
```

Usage

```
{'run_image_sampling': 'run the image_sample script to generate conditioned image samples using an RCDM diffusion model', 'run_ssl_feature_conditioning': 'run image sampling conditioned on SSL features from DINO or similar self-supervised models', 'run_ddim_sampling': 'run the image_sample script with DDIM sampling instead of standard p_sample_loop for faster generation', 'run_custom_model_path': 'run image sampling using a custom trained model checkpoint loaded from a specified model path', 'run_batch_image_generation': 'run batch image generation with configurable batch size and save results as a JPEG grid'}
```

## File: facebookresearch_rcdm/scripts/image_sample_interpolation.py

Prompts

```
['run the image_sample script to generate conditioned image samples using an RCDM diffusion model', 'run image sampling conditioned on SSL features from DINO or similar self-supervised models', 'run the image_sample script with DDIM sampling instead of standard p_sample_loop for faster generation', 'run image sampling using a custom trained model checkpoint loaded from a specified model path', 'run batch image generation with configurable batch size and save results as a JPEG grid', 'run image sample interpolation between two images using a diffusion model conditioned on SSL features', 'run the interpolation CLI with --first_image_path and --second_image_path to generate interpolated samples', 'create interpolated vectors between two points in latent space using linear interpolation with configurable steps', 'review the exclude_bias_and_norm function that filters parameters by checking if they are 1-dimensional', 'summarize the main function that loads SSL and diffusion models, computes feature embeddings, and generates interpolated images', 'run the image sample manipulation script to transfer attributes from one image to another using RCDM diffusion', 'generate normalized embeddings from a data loader using an SSL model and optional MLP projection', 'find the 20 nearest neighbors of a target embedding using FAISS with GPU or IVF index', 'compute squared L2 distance between an SSL model feature and a target tensor', 'create an argument parser with RCDM diffusion defaults and image manipulation specific flags', 'run a conditional representation-based diffusion model training loop on images using an SSL model', 'run a diffusion model training loop on images without an SSL conditioning model', 'create an argparse parser with defaults for RCDM image training including learning rate and batch size', 'create a data generator that extracts SSL features from images for conditional diffusion model training', 'review the main training flow that initializes distributed mode, loads SSL models, and runs the training loop']
```

Usage

```
{'run_image_interpolation': 'run image sample interpolation between two images using a diffusion model conditioned on SSL features', 'run_interpolate_cli': 'run the interpolation CLI with --first_image_path and --second_image_path to generate interpolated samples', 'create_interpolate_points': 'create interpolated vectors between two points in latent space using linear interpolation with configurable steps', 'review_exclude_bias_and_norm': 'review the exclude_bias_and_norm function that filters parameters by checking if they are 1-dimensional', 'summarize_main': 'summarize the main function that loads SSL and diffusion models, computes feature embeddings, and generates interpolated images'}
```

## File: facebookresearch_rcdm/scripts/image_sample_manipulation.py

Prompts

```
['run the image_sample script to generate conditioned image samples using an RCDM diffusion model', 'run image sampling conditioned on SSL features from DINO or similar self-supervised models', 'run the image_sample script with DDIM sampling instead of standard p_sample_loop for faster generation', 'run image sampling using a custom trained model checkpoint loaded from a specified model path', 'run batch image generation with configurable batch size and save results as a JPEG grid', 'run image sample interpolation between two images using a diffusion model conditioned on SSL features', 'run the interpolation CLI with --first_image_path and --second_image_path to generate interpolated samples', 'create interpolated vectors between two points in latent space using linear interpolation with configurable steps', 'review the exclude_bias_and_norm function that filters parameters by checking if they are 1-dimensional', 'summarize the main function that loads SSL and diffusion models, computes feature embeddings, and generates interpolated images', 'run the image sample manipulation script to transfer attributes from one image to another using RCDM diffusion', 'generate normalized embeddings from a data loader using an SSL model and optional MLP projection', 'find the 20 nearest neighbors of a target embedding using FAISS with GPU or IVF index', 'compute squared L2 distance between an SSL model feature and a target tensor', 'create an argument parser with RCDM diffusion defaults and image manipulation specific flags', 'run a conditional representation-based diffusion model training loop on images using an SSL model', 'run a diffusion model training loop on images without an SSL conditioning model', 'create an argparse parser with defaults for RCDM image training including learning rate and batch size', 'create a data generator that extracts SSL features from images for conditional diffusion model training', 'review the main training flow that initializes distributed mode, loads SSL models, and runs the training loop']
```

Usage

```
{'run_image_sample_manipulation': 'run the image sample manipulation script to transfer attributes from one image to another using RCDM diffusion', 'generate_embeddings': 'generate normalized embeddings from a data loader using an SSL model and optional MLP projection', 'nearest_neighbors_faiss': 'find the 20 nearest neighbors of a target embedding using FAISS with GPU or IVF index', 'compute_dist_ssl': 'compute squared L2 distance between an SSL model feature and a target tensor', 'create_argparser': 'create an argument parser with RCDM diffusion defaults and image manipulation specific flags'}
```

## File: facebookresearch_rcdm/scripts/image_train.py

Prompts

```
['run the image_sample script to generate conditioned image samples using an RCDM diffusion model', 'run image sampling conditioned on SSL features from DINO or similar self-supervised models', 'run the image_sample script with DDIM sampling instead of standard p_sample_loop for faster generation', 'run image sampling using a custom trained model checkpoint loaded from a specified model path', 'run batch image generation with configurable batch size and save results as a JPEG grid', 'run image sample interpolation between two images using a diffusion model conditioned on SSL features', 'run the interpolation CLI with --first_image_path and --second_image_path to generate interpolated samples', 'create interpolated vectors between two points in latent space using linear interpolation with configurable steps', 'review the exclude_bias_and_norm function that filters parameters by checking if they are 1-dimensional', 'summarize the main function that loads SSL and diffusion models, computes feature embeddings, and generates interpolated images', 'run the image sample manipulation script to transfer attributes from one image to another using RCDM diffusion', 'generate normalized embeddings from a data loader using an SSL model and optional MLP projection', 'find the 20 nearest neighbors of a target embedding using FAISS with GPU or IVF index', 'compute squared L2 distance between an SSL model feature and a target tensor', 'create an argument parser with RCDM diffusion defaults and image manipulation specific flags', 'run a conditional representation-based diffusion model training loop on images using an SSL model', 'run a diffusion model training loop on images without an SSL conditioning model', 'create an argparse parser with defaults for RCDM image training including learning rate and batch size', 'create a data generator that extracts SSL features from images for conditional diffusion model training', 'review the main training flow that initializes distributed mode, loads SSL models, and runs the training loop']
```

Usage

```
{'run_train_rcdm': 'run a conditional representation-based diffusion model training loop on images using an SSL model', 'run_train_rcdm_no_ssl': 'run a diffusion model training loop on images without an SSL conditioning model', 'create_argparser_training': 'create an argparse parser with defaults for RCDM image training including learning rate and batch size', 'load_ssl_data_generator': 'create a data generator that extracts SSL features from images for conditional diffusion model training', 'review_main_training_flow': 'review the main training flow that initializes distributed mode, loads SSL models, and runs the training loop'}
```

