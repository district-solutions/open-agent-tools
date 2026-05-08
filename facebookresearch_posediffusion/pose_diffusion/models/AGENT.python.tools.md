# Agent Python Tools

- repo: facebookresearch/posediffusion
- repo_uri: https://github.com/facebookresearch/posediffusion

## File: facebookresearch_posediffusion/pose_diffusion/models/denoiser.py

Prompts

```
['build a Denoiser model with a transformer trunk for pose diffusion denoising', 'run the Denoiser forward pass with pose, timestep, and condition tensors', 'create a TransformerEncoder with configurable layers, heads, and feedforward dimensions', 'build an MLP module with configurable hidden layers, normalization, and dropout', 'review the Denoiser forward method to understand pose embedding and feature concatenation', 'create a GaussianDiffusion model with custom timesteps, beta schedule, and loss type for pose diffusion', 'sample a pose from random noise using the GaussianDiffusion sample method with conditioning tensor z', 'compute p_losses for training by passing noisy pose data, timestep, and conditioning tensor to the model', 'configure a linear, cosine, or custom beta schedule for the diffusion process via init_diff_hyper', 'predict the original pose x_start from a noisy sample x_t and predicted noise using predict_start_from_noise', 'create a MultiScaleImageFeatureExtractor using a DINO model to extract features from RGB images', 'create a MultiScaleImageFeatureExtractor using a ResNet model to extract features from RGB images', 'extract averaged multi-scale image features by passing an RGB tensor through the forward method', 'freeze all parameters of a MultiScaleImageFeatureExtractor by setting freeze to True during initialization', 'get the output dimension of the feature extractor using the get_output_dim method', 'build a PoseDiffusionModel with image feature extractor, diffuser, and denoiser config dicts', 'run the PoseDiffusionModel forward pass in training mode with ground truth cameras and image tensor', 'run the PoseDiffusionModel forward pass in inference mode to sample predicted cameras from images', 'review the PoseDiffusionModel _init_weights method that initializes Linear and LayerNorm layers', 'summarize how PoseDiffusionModel uses absT_quaR_logFL pose encoding for camera extrinsics and intrinsics']
```

Usage

```
{'build_denoiser_model': 'build a Denoiser model with a transformer trunk for pose diffusion denoising', 'run_denoiser_forward': 'run the Denoiser forward pass with pose, timestep, and condition tensors', 'create_transformer_encoder': 'create a TransformerEncoder with configurable layers, heads, and feedforward dimensions', 'build_mlp_module': 'build an MLP module with configurable hidden layers, normalization, and dropout', 'review_denoiser_forward': 'review the Denoiser forward method to understand pose embedding and feature concatenation'}
```

## File: facebookresearch_posediffusion/pose_diffusion/models/gaussian_diffuser.py

Prompts

```
['build a Denoiser model with a transformer trunk for pose diffusion denoising', 'run the Denoiser forward pass with pose, timestep, and condition tensors', 'create a TransformerEncoder with configurable layers, heads, and feedforward dimensions', 'build an MLP module with configurable hidden layers, normalization, and dropout', 'review the Denoiser forward method to understand pose embedding and feature concatenation', 'create a GaussianDiffusion model with custom timesteps, beta schedule, and loss type for pose diffusion', 'sample a pose from random noise using the GaussianDiffusion sample method with conditioning tensor z', 'compute p_losses for training by passing noisy pose data, timestep, and conditioning tensor to the model', 'configure a linear, cosine, or custom beta schedule for the diffusion process via init_diff_hyper', 'predict the original pose x_start from a noisy sample x_t and predicted noise using predict_start_from_noise', 'create a MultiScaleImageFeatureExtractor using a DINO model to extract features from RGB images', 'create a MultiScaleImageFeatureExtractor using a ResNet model to extract features from RGB images', 'extract averaged multi-scale image features by passing an RGB tensor through the forward method', 'freeze all parameters of a MultiScaleImageFeatureExtractor by setting freeze to True during initialization', 'get the output dimension of the feature extractor using the get_output_dim method', 'build a PoseDiffusionModel with image feature extractor, diffuser, and denoiser config dicts', 'run the PoseDiffusionModel forward pass in training mode with ground truth cameras and image tensor', 'run the PoseDiffusionModel forward pass in inference mode to sample predicted cameras from images', 'review the PoseDiffusionModel _init_weights method that initializes Linear and LayerNorm layers', 'summarize how PoseDiffusionModel uses absT_quaR_logFL pose encoding for camera extrinsics and intrinsics']
```

Usage

```
{'create_gaussian_diffusion_model': 'create a GaussianDiffusion model with custom timesteps, beta schedule, and loss type for pose diffusion', 'sample_pose_from_noise': 'sample a pose from random noise using the GaussianDiffusion sample method with conditioning tensor z', 'compute_diffusion_losses': 'compute p_losses for training by passing noisy pose data, timestep, and conditioning tensor to the model', 'configure_beta_schedule': 'configure a linear, cosine, or custom beta schedule for the diffusion process via init_diff_hyper', 'predict_start_from_noise': 'predict the original pose x_start from a noisy sample x_t and predicted noise using predict_start_from_noise'}
```

## File: facebookresearch_posediffusion/pose_diffusion/models/image_feature_extractor.py

Prompts

```
['build a Denoiser model with a transformer trunk for pose diffusion denoising', 'run the Denoiser forward pass with pose, timestep, and condition tensors', 'create a TransformerEncoder with configurable layers, heads, and feedforward dimensions', 'build an MLP module with configurable hidden layers, normalization, and dropout', 'review the Denoiser forward method to understand pose embedding and feature concatenation', 'create a GaussianDiffusion model with custom timesteps, beta schedule, and loss type for pose diffusion', 'sample a pose from random noise using the GaussianDiffusion sample method with conditioning tensor z', 'compute p_losses for training by passing noisy pose data, timestep, and conditioning tensor to the model', 'configure a linear, cosine, or custom beta schedule for the diffusion process via init_diff_hyper', 'predict the original pose x_start from a noisy sample x_t and predicted noise using predict_start_from_noise', 'create a MultiScaleImageFeatureExtractor using a DINO model to extract features from RGB images', 'create a MultiScaleImageFeatureExtractor using a ResNet model to extract features from RGB images', 'extract averaged multi-scale image features by passing an RGB tensor through the forward method', 'freeze all parameters of a MultiScaleImageFeatureExtractor by setting freeze to True during initialization', 'get the output dimension of the feature extractor using the get_output_dim method', 'build a PoseDiffusionModel with image feature extractor, diffuser, and denoiser config dicts', 'run the PoseDiffusionModel forward pass in training mode with ground truth cameras and image tensor', 'run the PoseDiffusionModel forward pass in inference mode to sample predicted cameras from images', 'review the PoseDiffusionModel _init_weights method that initializes Linear and LayerNorm layers', 'summarize how PoseDiffusionModel uses absT_quaR_logFL pose encoding for camera extrinsics and intrinsics']
```

Usage

```
{'create_multiscale_extractor_dino': 'create a MultiScaleImageFeatureExtractor using a DINO model to extract features from RGB images', 'create_multiscale_extractor_resnet': 'create a MultiScaleImageFeatureExtractor using a ResNet model to extract features from RGB images', 'extract_multiscale_features': 'extract averaged multi-scale image features by passing an RGB tensor through the forward method', 'freeze_extractor_weights': 'freeze all parameters of a MultiScaleImageFeatureExtractor by setting freeze to True during initialization', 'get_output_dimension': 'get the output dimension of the feature extractor using the get_output_dim method'}
```

## File: facebookresearch_posediffusion/pose_diffusion/models/pose_diffusion_model.py

Prompts

```
['build a Denoiser model with a transformer trunk for pose diffusion denoising', 'run the Denoiser forward pass with pose, timestep, and condition tensors', 'create a TransformerEncoder with configurable layers, heads, and feedforward dimensions', 'build an MLP module with configurable hidden layers, normalization, and dropout', 'review the Denoiser forward method to understand pose embedding and feature concatenation', 'create a GaussianDiffusion model with custom timesteps, beta schedule, and loss type for pose diffusion', 'sample a pose from random noise using the GaussianDiffusion sample method with conditioning tensor z', 'compute p_losses for training by passing noisy pose data, timestep, and conditioning tensor to the model', 'configure a linear, cosine, or custom beta schedule for the diffusion process via init_diff_hyper', 'predict the original pose x_start from a noisy sample x_t and predicted noise using predict_start_from_noise', 'create a MultiScaleImageFeatureExtractor using a DINO model to extract features from RGB images', 'create a MultiScaleImageFeatureExtractor using a ResNet model to extract features from RGB images', 'extract averaged multi-scale image features by passing an RGB tensor through the forward method', 'freeze all parameters of a MultiScaleImageFeatureExtractor by setting freeze to True during initialization', 'get the output dimension of the feature extractor using the get_output_dim method', 'build a PoseDiffusionModel with image feature extractor, diffuser, and denoiser config dicts', 'run the PoseDiffusionModel forward pass in training mode with ground truth cameras and image tensor', 'run the PoseDiffusionModel forward pass in inference mode to sample predicted cameras from images', 'review the PoseDiffusionModel _init_weights method that initializes Linear and LayerNorm layers', 'summarize how PoseDiffusionModel uses absT_quaR_logFL pose encoding for camera extrinsics and intrinsics']
```

Usage

```
{'build_pose_diffusion_model': 'build a PoseDiffusionModel with image feature extractor, diffuser, and denoiser config dicts', 'run_forward_training': 'run the PoseDiffusionModel forward pass in training mode with ground truth cameras and image tensor', 'run_forward_sampling': 'run the PoseDiffusionModel forward pass in inference mode to sample predicted cameras from images', 'review_init_weights': 'review the PoseDiffusionModel _init_weights method that initializes Linear and LayerNorm layers', 'summarize_pose_encoding': 'summarize how PoseDiffusionModel uses absT_quaR_logFL pose encoding for camera extrinsics and intrinsics'}
```

