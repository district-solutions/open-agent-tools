# Agent Python Tools

- repo: facebookresearch/audio2photoreal
- repo_uri: https://github.com/facebookresearch/audio2photoreal

## File: facebookresearch_audio2photoreal/train/train_guide.py

Prompts

```
['run the GuideTransformer training loop with audio conditioned motion prediction on a dataset', 'validate the trained GuideTransformer model on a validation dataset and save prediction results', 'save a training checkpoint with model state dict and optimizer state to disk', 'load and prepare train and validation data loaders from a local data root directory', 'prepare input and target token sequences from mesh data using the VQ-VAE tokenizer', 'create a ClearmlPlatform instance to log training metrics to ClearML', 'create a TensorboardPlatform instance to log training metrics to TensorBoard', 'report a scalar value to ClearML using the ClearmlPlatform report_scalar method', 'report a scalar value to TensorBoard using the TensorboardPlatform report_scalar method', 'close a TrainPlatform instance to clean up logging resources', 'train a TemporalVertexCodec VQ-VAE model for motion data with configurable learning rate and loss weights', 'run a single training step for the VQ-VAE model with ground truth motion and conditioning data', 'evaluate the trained VQ-VAE model on validation data and log perplexity, commit, and reconstruction losses', 'run warmup training steps with linear learning rate scheduling before main training loop', 'save or load model checkpoints including network state, optimizer, and scheduler for resuming training', 'run the TrainLoop class to train a diffusion model with AdamW optimizer and checkpointing', 'run a single training step with forward pass, backward pass, and optimizer update', 'save the model checkpoint and optimizer state to disk excluding CLIP weights', 'parse the resume step number from a model checkpoint filename like model000123456.pt', 'log loss values and their quantiles across diffusion timesteps to the training logger']
```

Usage

```
{'train_guide_model': 'run the GuideTransformer training loop with audio conditioned motion prediction on a dataset', 'validate_guide_model': 'validate the trained GuideTransformer model on a validation dataset and save prediction results', 'save_checkpoint': 'save a training checkpoint with model state dict and optimizer state to disk', 'load_data_info': 'load and prepare train and validation data loaders from a local data root directory', 'prepare_tokens': 'prepare input and target token sequences from mesh data using the VQ-VAE tokenizer'}
```

## File: facebookresearch_audio2photoreal/train/train_platforms.py

Prompts

```
['run the GuideTransformer training loop with audio conditioned motion prediction on a dataset', 'validate the trained GuideTransformer model on a validation dataset and save prediction results', 'save a training checkpoint with model state dict and optimizer state to disk', 'load and prepare train and validation data loaders from a local data root directory', 'prepare input and target token sequences from mesh data using the VQ-VAE tokenizer', 'create a ClearmlPlatform instance to log training metrics to ClearML', 'create a TensorboardPlatform instance to log training metrics to TensorBoard', 'report a scalar value to ClearML using the ClearmlPlatform report_scalar method', 'report a scalar value to TensorBoard using the TensorboardPlatform report_scalar method', 'close a TrainPlatform instance to clean up logging resources', 'train a TemporalVertexCodec VQ-VAE model for motion data with configurable learning rate and loss weights', 'run a single training step for the VQ-VAE model with ground truth motion and conditioning data', 'evaluate the trained VQ-VAE model on validation data and log perplexity, commit, and reconstruction losses', 'run warmup training steps with linear learning rate scheduling before main training loop', 'save or load model checkpoints including network state, optimizer, and scheduler for resuming training', 'run the TrainLoop class to train a diffusion model with AdamW optimizer and checkpointing', 'run a single training step with forward pass, backward pass, and optimizer update', 'save the model checkpoint and optimizer state to disk excluding CLIP weights', 'parse the resume step number from a model checkpoint filename like model000123456.pt', 'log loss values and their quantiles across diffusion timesteps to the training logger']
```

Usage

```
{'create_clearml_platform': 'create a ClearmlPlatform instance to log training metrics to ClearML', 'create_tensorboard_platform': 'create a TensorboardPlatform instance to log training metrics to TensorBoard', 'report_scalar_clearml': 'report a scalar value to ClearML using the ClearmlPlatform report_scalar method', 'report_scalar_tensorboard': 'report a scalar value to TensorBoard using the TensorboardPlatform report_scalar method', 'close_platform': 'close a TrainPlatform instance to clean up logging resources'}
```

## File: facebookresearch_audio2photoreal/train/train_vq.py

Prompts

```
['run the GuideTransformer training loop with audio conditioned motion prediction on a dataset', 'validate the trained GuideTransformer model on a validation dataset and save prediction results', 'save a training checkpoint with model state dict and optimizer state to disk', 'load and prepare train and validation data loaders from a local data root directory', 'prepare input and target token sequences from mesh data using the VQ-VAE tokenizer', 'create a ClearmlPlatform instance to log training metrics to ClearML', 'create a TensorboardPlatform instance to log training metrics to TensorBoard', 'report a scalar value to ClearML using the ClearmlPlatform report_scalar method', 'report a scalar value to TensorBoard using the TensorboardPlatform report_scalar method', 'close a TrainPlatform instance to clean up logging resources', 'train a TemporalVertexCodec VQ-VAE model for motion data with configurable learning rate and loss weights', 'run a single training step for the VQ-VAE model with ground truth motion and conditioning data', 'evaluate the trained VQ-VAE model on validation data and log perplexity, commit, and reconstruction losses', 'run warmup training steps with linear learning rate scheduling before main training loop', 'save or load model checkpoints including network state, optimizer, and scheduler for resuming training', 'run the TrainLoop class to train a diffusion model with AdamW optimizer and checkpointing', 'run a single training step with forward pass, backward pass, and optimizer update', 'save the model checkpoint and optimizer state to disk excluding CLIP weights', 'parse the resume step number from a model checkpoint filename like model000123456.pt', 'log loss values and their quantiles across diffusion timesteps to the training logger']
```

Usage

```
{'train_vqvae_model': 'train a TemporalVertexCodec VQ-VAE model for motion data with configurable learning rate and loss weights', 'run_train_step': 'run a single training step for the VQ-VAE model with ground truth motion and conditioning data', 'evaluate_vqvae_model': 'evaluate the trained VQ-VAE model on validation data and log perplexity, commit, and reconstruction losses', 'run_warmup_steps': 'run warmup training steps with linear learning rate scheduling before main training loop', 'save_load_checkpoint': 'save or load model checkpoints including network state, optimizer, and scheduler for resuming training'}
```

## File: facebookresearch_audio2photoreal/train/training_loop.py

Prompts

```
['run the GuideTransformer training loop with audio conditioned motion prediction on a dataset', 'validate the trained GuideTransformer model on a validation dataset and save prediction results', 'save a training checkpoint with model state dict and optimizer state to disk', 'load and prepare train and validation data loaders from a local data root directory', 'prepare input and target token sequences from mesh data using the VQ-VAE tokenizer', 'create a ClearmlPlatform instance to log training metrics to ClearML', 'create a TensorboardPlatform instance to log training metrics to TensorBoard', 'report a scalar value to ClearML using the ClearmlPlatform report_scalar method', 'report a scalar value to TensorBoard using the TensorboardPlatform report_scalar method', 'close a TrainPlatform instance to clean up logging resources', 'train a TemporalVertexCodec VQ-VAE model for motion data with configurable learning rate and loss weights', 'run a single training step for the VQ-VAE model with ground truth motion and conditioning data', 'evaluate the trained VQ-VAE model on validation data and log perplexity, commit, and reconstruction losses', 'run warmup training steps with linear learning rate scheduling before main training loop', 'save or load model checkpoints including network state, optimizer, and scheduler for resuming training', 'run the TrainLoop class to train a diffusion model with AdamW optimizer and checkpointing', 'run a single training step with forward pass, backward pass, and optimizer update', 'save the model checkpoint and optimizer state to disk excluding CLIP weights', 'parse the resume step number from a model checkpoint filename like model000123456.pt', 'log loss values and their quantiles across diffusion timesteps to the training logger']
```

Usage

```
{'run_TrainLoop': 'run the TrainLoop class to train a diffusion model with AdamW optimizer and checkpointing', 'run_TrainLoop_run_step': 'run a single training step with forward pass, backward pass, and optimizer update', 'run_TrainLoop_save': 'save the model checkpoint and optimizer state to disk excluding CLIP weights', 'parse_parse_resume_step_from_filename': 'parse the resume step number from a model checkpoint filename like model000123456.pt', 'log_log_loss_dict': 'log loss values and their quantiles across diffusion timesteps to the training logger'}
```

