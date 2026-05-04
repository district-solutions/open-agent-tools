# Agent Python Tools

- repo: facebookresearch/dit
- repo_uri: https://github.com/facebookresearch/dit

## File: facebookresearch_dit/download.py

Prompts

```
['download a pre-trained DiT model checkpoint from the web using download_model', 'find and load a pre-trained DiT model or custom checkpoint using find_model', 'load a custom DiT checkpoint from a local file path using find_model', 'download all available pre-trained DiT models by running the script as main', 'list available pre-trained DiT model names from the pretrained_models set', 'build a DiT-XL/2 diffusion transformer model using the DiT_models factory dictionary', 'run a forward pass of the DiT model with image tensor, timesteps, and class labels', 'run a forward pass of DiT with classifier-free guidance using a cfg_scale parameter', 'create a TimestepEmbedder to embed scalar diffusion timesteps into sinusoidal vector representations', 'create a LabelEmbedder to embed class labels with dropout support for classifier-free guidance', 'run distributed DiT model sampling across multiple GPUs to generate image samples', 'run DiT sampling with a custom checkpoint path and classifier-free guidance scale', 'run DiT sampling to generate 50000 images for FID evaluation metrics', 'create an npz file from a folder of numbered PNG sample images', 'review the main sampling function that handles DDP setup, model loading, and image generation', 'run the DiT training script with a data path and optional model, image size, and batch size arguments', 'run the DiT training script using a custom model like DiT-XL/2 on a specified dataset path', 'run the DiT training script and save checkpoints every 50000 steps to the results directory', 'review the main training loop that handles DDP setup, VAE encoding, diffusion losses, and EMA updates', 'review the update_ema function that steps the EMA model weights toward the current model with configurable decay']
```

Usage

```
{'download_DiT_model': 'download a pre-trained DiT model checkpoint from the web using download_model', 'find_DiT_checkpoint': 'find and load a pre-trained DiT model or custom checkpoint using find_model', 'load_custom_DiT_checkpoint': 'load a custom DiT checkpoint from a local file path using find_model', 'download_all_DiT_models': 'download all available pre-trained DiT models by running the script as main', 'list_pretrained_DiT_models': 'list available pre-trained DiT model names from the pretrained_models set'}
```

## File: facebookresearch_dit/models.py

Prompts

```
['download a pre-trained DiT model checkpoint from the web using download_model', 'find and load a pre-trained DiT model or custom checkpoint using find_model', 'load a custom DiT checkpoint from a local file path using find_model', 'download all available pre-trained DiT models by running the script as main', 'list available pre-trained DiT model names from the pretrained_models set', 'build a DiT-XL/2 diffusion transformer model using the DiT_models factory dictionary', 'run a forward pass of the DiT model with image tensor, timesteps, and class labels', 'run a forward pass of DiT with classifier-free guidance using a cfg_scale parameter', 'create a TimestepEmbedder to embed scalar diffusion timesteps into sinusoidal vector representations', 'create a LabelEmbedder to embed class labels with dropout support for classifier-free guidance', 'run distributed DiT model sampling across multiple GPUs to generate image samples', 'run DiT sampling with a custom checkpoint path and classifier-free guidance scale', 'run DiT sampling to generate 50000 images for FID evaluation metrics', 'create an npz file from a folder of numbered PNG sample images', 'review the main sampling function that handles DDP setup, model loading, and image generation', 'run the DiT training script with a data path and optional model, image size, and batch size arguments', 'run the DiT training script using a custom model like DiT-XL/2 on a specified dataset path', 'run the DiT training script and save checkpoints every 50000 steps to the results directory', 'review the main training loop that handles DDP setup, VAE encoding, diffusion losses, and EMA updates', 'review the update_ema function that steps the EMA model weights toward the current model with configurable decay']
```

Usage

```
{'build_DiT_model': 'build a DiT-XL/2 diffusion transformer model using the DiT_models factory dictionary', 'run_DiT_forward': 'run a forward pass of the DiT model with image tensor, timesteps, and class labels', 'run_DiT_forward_with_cfg': 'run a forward pass of DiT with classifier-free guidance using a cfg_scale parameter', 'create_TimestepEmbedder': 'create a TimestepEmbedder to embed scalar diffusion timesteps into sinusoidal vector representations', 'create_LabelEmbedder': 'create a LabelEmbedder to embed class labels with dropout support for classifier-free guidance'}
```

## File: facebookresearch_dit/sample_ddp.py

Prompts

```
['download a pre-trained DiT model checkpoint from the web using download_model', 'find and load a pre-trained DiT model or custom checkpoint using find_model', 'load a custom DiT checkpoint from a local file path using find_model', 'download all available pre-trained DiT models by running the script as main', 'list available pre-trained DiT model names from the pretrained_models set', 'build a DiT-XL/2 diffusion transformer model using the DiT_models factory dictionary', 'run a forward pass of the DiT model with image tensor, timesteps, and class labels', 'run a forward pass of DiT with classifier-free guidance using a cfg_scale parameter', 'create a TimestepEmbedder to embed scalar diffusion timesteps into sinusoidal vector representations', 'create a LabelEmbedder to embed class labels with dropout support for classifier-free guidance', 'run distributed DiT model sampling across multiple GPUs to generate image samples', 'run DiT sampling with a custom checkpoint path and classifier-free guidance scale', 'run DiT sampling to generate 50000 images for FID evaluation metrics', 'create an npz file from a folder of numbered PNG sample images', 'review the main sampling function that handles DDP setup, model loading, and image generation', 'run the DiT training script with a data path and optional model, image size, and batch size arguments', 'run the DiT training script using a custom model like DiT-XL/2 on a specified dataset path', 'run the DiT training script and save checkpoints every 50000 steps to the results directory', 'review the main training loop that handles DDP setup, VAE encoding, diffusion losses, and EMA updates', 'review the update_ema function that steps the EMA model weights toward the current model with configurable decay']
```

Usage

```
{'run_DiT_DDP_sampling': 'run distributed DiT model sampling across multiple GPUs to generate image samples', 'run_sampling_with_custom_ckpt': 'run DiT sampling with a custom checkpoint path and classifier-free guidance scale', 'run_sampling_for_FID': 'run DiT sampling to generate 50000 images for FID evaluation metrics', 'create_npz_from_sample_folder': 'create an npz file from a folder of numbered PNG sample images', 'review_main_sampling_logic': 'review the main sampling function that handles DDP setup, model loading, and image generation'}
```

## File: facebookresearch_dit/train.py

Prompts

```
['download a pre-trained DiT model checkpoint from the web using download_model', 'find and load a pre-trained DiT model or custom checkpoint using find_model', 'load a custom DiT checkpoint from a local file path using find_model', 'download all available pre-trained DiT models by running the script as main', 'list available pre-trained DiT model names from the pretrained_models set', 'build a DiT-XL/2 diffusion transformer model using the DiT_models factory dictionary', 'run a forward pass of the DiT model with image tensor, timesteps, and class labels', 'run a forward pass of DiT with classifier-free guidance using a cfg_scale parameter', 'create a TimestepEmbedder to embed scalar diffusion timesteps into sinusoidal vector representations', 'create a LabelEmbedder to embed class labels with dropout support for classifier-free guidance', 'run distributed DiT model sampling across multiple GPUs to generate image samples', 'run DiT sampling with a custom checkpoint path and classifier-free guidance scale', 'run DiT sampling to generate 50000 images for FID evaluation metrics', 'create an npz file from a folder of numbered PNG sample images', 'review the main sampling function that handles DDP setup, model loading, and image generation', 'run the DiT training script with a data path and optional model, image size, and batch size arguments', 'run the DiT training script using a custom model like DiT-XL/2 on a specified dataset path', 'run the DiT training script and save checkpoints every 50000 steps to the results directory', 'review the main training loop that handles DDP setup, VAE encoding, diffusion losses, and EMA updates', 'review the update_ema function that steps the EMA model weights toward the current model with configurable decay']
```

Usage

```
{'run_DiT_training': 'run the DiT training script with a data path and optional model, image size, and batch size arguments', 'run_training_with_custom_model': 'run the DiT training script using a custom model like DiT-XL/2 on a specified dataset path', 'run_training_with_checkpoints': 'run the DiT training script and save checkpoints every 50000 steps to the results directory', 'review_main_training_loop': 'review the main training loop that handles DDP setup, VAE encoding, diffusion losses, and EMA updates', 'review_update_ema': 'review the update_ema function that steps the EMA model weights toward the current model with configurable decay'}
```

