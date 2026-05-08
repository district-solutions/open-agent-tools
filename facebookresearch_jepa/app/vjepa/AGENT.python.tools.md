# Agent Python Tools

- repo: facebookresearch/jepa
- repo_uri: https://github.com/facebookresearch/jepa

## File: facebookresearch_jepa/app/vjepa/train.py

Prompts

```
['run the main training loop for video JEPa with a config dict containing model, data, and optimization settings', 'review the main function that orchestrates distributed video JEPa training with encoder, predictor, and target encoder', 'create a checkpoint saving function that stores encoder, predictor, optimizer, and scaler state dicts to disk', 'build the forward target pass that encodes video clips through the target encoder with layer norm and masking', 'test the JEPa loss function that computes Lp prediction loss between predictor output and target encoder output', 'create a VideoTransform instance to apply augmentation and normalization to video frame buffers', 'build a video transforms pipeline using make_transforms with configurable flip, resize, and crop options', 'normalize a PyTorch tensor by subtracting mean and dividing by standard deviation', 'normalize a C T H W tensor in-place by subtracting mean and dividing by std', 'review the VideoTransform call method that applies spatial transforms, flips, and erasing to video buffers', 'init a video masked autoencoder ViT encoder and predictor model with configurable patch size and frames', 'init an AdamW optimizer with warmup cosine LR schedule and cosine weight decay schedule for V-JEPA training', 'load a checkpoint file to restore encoder, predictor, target encoder, optimizer, and scaler state', 'review the init_video_model function to understand mask token configuration and model initialization', 'review the init_opt function to understand parameter grouping for weight decay exclusion on bias and norm layers']
```

Usage

```
{'run_vjepa_training': 'run the main training loop for video JEPa with a config dict containing model, data, and optimization settings', 'review_main_training_loop': 'review the main function that orchestrates distributed video JEPa training with encoder, predictor, and target encoder', 'create_checkpoint_saving': 'create a checkpoint saving function that stores encoder, predictor, optimizer, and scaler state dicts to disk', 'build_forward_target_pass': 'build the forward target pass that encodes video clips through the target encoder with layer norm and masking', 'test_loss_computation': 'test the JEPa loss function that computes Lp prediction loss between predictor output and target encoder output'}
```

## File: facebookresearch_jepa/app/vjepa/transforms.py

Prompts

```
['run the main training loop for video JEPa with a config dict containing model, data, and optimization settings', 'review the main function that orchestrates distributed video JEPa training with encoder, predictor, and target encoder', 'create a checkpoint saving function that stores encoder, predictor, optimizer, and scaler state dicts to disk', 'build the forward target pass that encodes video clips through the target encoder with layer norm and masking', 'test the JEPa loss function that computes Lp prediction loss between predictor output and target encoder output', 'create a VideoTransform instance to apply augmentation and normalization to video frame buffers', 'build a video transforms pipeline using make_transforms with configurable flip, resize, and crop options', 'normalize a PyTorch tensor by subtracting mean and dividing by standard deviation', 'normalize a C T H W tensor in-place by subtracting mean and dividing by std', 'review the VideoTransform call method that applies spatial transforms, flips, and erasing to video buffers', 'init a video masked autoencoder ViT encoder and predictor model with configurable patch size and frames', 'init an AdamW optimizer with warmup cosine LR schedule and cosine weight decay schedule for V-JEPA training', 'load a checkpoint file to restore encoder, predictor, target encoder, optimizer, and scaler state', 'review the init_video_model function to understand mask token configuration and model initialization', 'review the init_opt function to understand parameter grouping for weight decay exclusion on bias and norm layers']
```

Usage

```
{'create_video_transform': 'create a VideoTransform instance to apply augmentation and normalization to video frame buffers', 'build_transforms_pipeline': 'build a video transforms pipeline using make_transforms with configurable flip, resize, and crop options', 'normalize_tensor': 'normalize a PyTorch tensor by subtracting mean and dividing by standard deviation', 'normalize_tensor_inplace': 'normalize a C T H W tensor in-place by subtracting mean and dividing by std', 'review_VideoTransform_call': 'review the VideoTransform call method that applies spatial transforms, flips, and erasing to video buffers'}
```

## File: facebookresearch_jepa/app/vjepa/utils.py

Prompts

```
['run the main training loop for video JEPa with a config dict containing model, data, and optimization settings', 'review the main function that orchestrates distributed video JEPa training with encoder, predictor, and target encoder', 'create a checkpoint saving function that stores encoder, predictor, optimizer, and scaler state dicts to disk', 'build the forward target pass that encodes video clips through the target encoder with layer norm and masking', 'test the JEPa loss function that computes Lp prediction loss between predictor output and target encoder output', 'create a VideoTransform instance to apply augmentation and normalization to video frame buffers', 'build a video transforms pipeline using make_transforms with configurable flip, resize, and crop options', 'normalize a PyTorch tensor by subtracting mean and dividing by standard deviation', 'normalize a C T H W tensor in-place by subtracting mean and dividing by std', 'review the VideoTransform call method that applies spatial transforms, flips, and erasing to video buffers', 'init a video masked autoencoder ViT encoder and predictor model with configurable patch size and frames', 'init an AdamW optimizer with warmup cosine LR schedule and cosine weight decay schedule for V-JEPA training', 'load a checkpoint file to restore encoder, predictor, target encoder, optimizer, and scaler state', 'review the init_video_model function to understand mask token configuration and model initialization', 'review the init_opt function to understand parameter grouping for weight decay exclusion on bias and norm layers']
```

Usage

```
{'init_video_model_ViTEncoderPredictor': 'init a video masked autoencoder ViT encoder and predictor model with configurable patch size and frames', 'init_opt_AdamW_schedulers': 'init an AdamW optimizer with warmup cosine LR schedule and cosine weight decay schedule for V-JEPA training', 'load_checkpoint_resume_training': 'load a checkpoint file to restore encoder, predictor, target encoder, optimizer, and scaler state', 'review_init_video_model_mask_tokens': 'review the init_video_model function to understand mask token configuration and model initialization', 'review_init_opt_param_groups': 'review the init_opt function to understand parameter grouping for weight decay exclusion on bias and norm layers'}
```

