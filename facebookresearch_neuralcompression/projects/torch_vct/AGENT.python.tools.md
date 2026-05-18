# Agent Python Tools

- repo: facebookresearch/neuralcompression
- repo_uri: https://github.com/facebookresearch/neuralcompression

## File: facebookresearch_neuralcompression/projects/torch_vct/model_lightning.py

Prompts

```
['build a PyTorch Lightning module wrapping a VCTPipeline model with configurable optimizer and scheduler', 'run a training step computing weighted combined distortion and rate loss with PSNR metrics', 'run a validation step logging distortion loss, rate loss, and PSNR for video compression', 'run a test step that compresses and decompresses video then logs PSNR and bits per pixel', 'review the rate_loss method that computes bits per pixel from rate arguments for video frames', 'build a VCTPipeline with analysis and synthesis transforms for video compression', 'run compress_video on a VideoData batch to get compressed scenes and bit counts', 'run decompress_video with frames shape and bottleneck args to reconstruct video frames', 'run the VCTPipeline forward pass on a VideoData batch to get reconstructions and likelihoods', 'run compute_rate on scenes likelihoods tensor to calculate bits per frame or total', 'run the main training loop for a VCT video compression model using hydra config', 'create a WandbImageCallback to log compressed and original images at the end of each validation step', 'build a WandbImageCallback from a LightningDataModule by sampling train and validation batches', 'review the WandbImageCallback log_images method that logs image grids to wandb with global step tracking', 'test the main function checkpoint resume logic that checks for existing .ckpt files before training']
```

Usage

```
{'build_VCTModule': 'build a PyTorch Lightning module wrapping a VCTPipeline model with configurable optimizer and scheduler', 'run_training_step': 'run a training step computing weighted combined distortion and rate loss with PSNR metrics', 'run_validation_step': 'run a validation step logging distortion loss, rate loss, and PSNR for video compression', 'run_test_step': 'run a test step that compresses and decompresses video then logs PSNR and bits per pixel', 'review_rate_loss': 'review the rate_loss method that computes bits per pixel from rate arguments for video frames'}
```

## File: facebookresearch_neuralcompression/projects/torch_vct/model_pipeline.py

Prompts

```
['build a PyTorch Lightning module wrapping a VCTPipeline model with configurable optimizer and scheduler', 'run a training step computing weighted combined distortion and rate loss with PSNR metrics', 'run a validation step logging distortion loss, rate loss, and PSNR for video compression', 'run a test step that compresses and decompresses video then logs PSNR and bits per pixel', 'review the rate_loss method that computes bits per pixel from rate arguments for video frames', 'build a VCTPipeline with analysis and synthesis transforms for video compression', 'run compress_video on a VideoData batch to get compressed scenes and bit counts', 'run decompress_video with frames shape and bottleneck args to reconstruct video frames', 'run the VCTPipeline forward pass on a VideoData batch to get reconstructions and likelihoods', 'run compute_rate on scenes likelihoods tensor to calculate bits per frame or total', 'run the main training loop for a VCT video compression model using hydra config', 'create a WandbImageCallback to log compressed and original images at the end of each validation step', 'build a WandbImageCallback from a LightningDataModule by sampling train and validation batches', 'review the WandbImageCallback log_images method that logs image grids to wandb with global step tracking', 'test the main function checkpoint resume logic that checks for existing .ckpt files before training']
```

Usage

```
{'build_VCTPipeline': 'build a VCTPipeline with analysis and synthesis transforms for video compression', 'run_compress_video': 'run compress_video on a VideoData batch to get compressed scenes and bit counts', 'run_decompress_video': 'run decompress_video with frames shape and bottleneck args to reconstruct video frames', 'run_forward': 'run the VCTPipeline forward pass on a VideoData batch to get reconstructions and likelihoods', 'run_compute_rate': 'run compute_rate on scenes likelihoods tensor to calculate bits per frame or total'}
```

## File: facebookresearch_neuralcompression/projects/torch_vct/model_train.py

Prompts

```
['build a PyTorch Lightning module wrapping a VCTPipeline model with configurable optimizer and scheduler', 'run a training step computing weighted combined distortion and rate loss with PSNR metrics', 'run a validation step logging distortion loss, rate loss, and PSNR for video compression', 'run a test step that compresses and decompresses video then logs PSNR and bits per pixel', 'review the rate_loss method that computes bits per pixel from rate arguments for video frames', 'build a VCTPipeline with analysis and synthesis transforms for video compression', 'run compress_video on a VideoData batch to get compressed scenes and bit counts', 'run decompress_video with frames shape and bottleneck args to reconstruct video frames', 'run the VCTPipeline forward pass on a VideoData batch to get reconstructions and likelihoods', 'run compute_rate on scenes likelihoods tensor to calculate bits per frame or total', 'run the main training loop for a VCT video compression model using hydra config', 'create a WandbImageCallback to log compressed and original images at the end of each validation step', 'build a WandbImageCallback from a LightningDataModule by sampling train and validation batches', 'review the WandbImageCallback log_images method that logs image grids to wandb with global step tracking', 'test the main function checkpoint resume logic that checks for existing .ckpt files before training']
```

Usage

```
{'run_VCT_model_training': 'run the main training loop for a VCT video compression model using hydra config', 'create_WandbImageCallback': 'create a WandbImageCallback to log compressed and original images at the end of each validation step', 'build_image_logger': 'build a WandbImageCallback from a LightningDataModule by sampling train and validation batches', 'review_WandbImageCallback_log_images': 'review the WandbImageCallback log_images method that logs image grids to wandb with global step tracking', 'test_main_checkpoint_resume': 'test the main function checkpoint resume logic that checks for existing .ckpt files before training'}
```

