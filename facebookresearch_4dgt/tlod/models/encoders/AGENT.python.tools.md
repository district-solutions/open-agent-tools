# Agent Python Tools

- repo: facebookresearch/4dgt
- repo_uri: https://github.com/facebookresearch/4dgt

## File: facebookresearch_4dgt/tlod/models/encoders/image_encoder.py

Prompts

```
['create a BaseImageEncoderConfig with custom hidden size, depth, and patch size for the image encoder', 'build a BaseImageEncoder transformer model from a BaseImageEncoderConfig with self-attention blocks and layer normalization', 'compute Plucker coordinates from camera intrinsics and extrinsics to get ray origins and directions', 'initialize the BaseImageEncoder model weights using normal distribution and truncation for positional embeddings', 'create a BaseImageEncoder-B factory instance with keyword arguments for hidden size, depth, and patch size', 'build a 4D Gaussian image encoder model using ImageEncoder4DG with a custom config for pixel-time aligned regression', 'create an ImageEncoder4DGConfig with custom hidden size, depth, patch size, and attention settings for the encoder', 'run a forward pass on the ImageEncoder4DG model with input images, timestamps, camera intrinsics, and extrinsics', 'decode geometry and appearance tokens into 4D Gaussian parameters including xyz, depth, opacity, scaling, and rotation', 'rescale raw Gaussian predictions for depth, opacity, scale, rotation, motion, and temporal covariance to valid ranges', 'build a Temporal Level of Detail image encoder model using TLoDConfig with custom hidden size and depth parameters', 'create a TLoDConfig instance with custom input size, patch size, and DINOv2 version for 4D Gaussian regression', 'run the forward pass of ImageEncoderTLoD with input images, timestamps, camera intrinsics, and camera-to-world matrices', 'review the rescale_predictions method that applies sigmoid activations and learned biases to raw Gaussian parameter predictions', 'summarize the magic_filter method that downsamples Gaussian parameters using magic pattern sampling or opacity-based top-k selection']
```

Usage

```
{'create_BaseImageEncoderConfig': 'create a BaseImageEncoderConfig with custom hidden size, depth, and patch size for the image encoder', 'build_BaseImageEncoder': 'build a BaseImageEncoder transformer model from a BaseImageEncoderConfig with self-attention blocks and layer normalization', 'compute_plucker_coordinates': 'compute Plucker coordinates from camera intrinsics and extrinsics to get ray origins and directions', 'initialize_BaseImageEncoder_weights': 'initialize the BaseImageEncoder model weights using normal distribution and truncation for positional embeddings', 'create_BaseImageEncoder_B': 'create a BaseImageEncoder-B factory instance with keyword arguments for hidden size, depth, and patch size'}
```

## File: facebookresearch_4dgt/tlod/models/encoders/image_encoder_4DG.py

Prompts

```
['create a BaseImageEncoderConfig with custom hidden size, depth, and patch size for the image encoder', 'build a BaseImageEncoder transformer model from a BaseImageEncoderConfig with self-attention blocks and layer normalization', 'compute Plucker coordinates from camera intrinsics and extrinsics to get ray origins and directions', 'initialize the BaseImageEncoder model weights using normal distribution and truncation for positional embeddings', 'create a BaseImageEncoder-B factory instance with keyword arguments for hidden size, depth, and patch size', 'build a 4D Gaussian image encoder model using ImageEncoder4DG with a custom config for pixel-time aligned regression', 'create an ImageEncoder4DGConfig with custom hidden size, depth, patch size, and attention settings for the encoder', 'run a forward pass on the ImageEncoder4DG model with input images, timestamps, camera intrinsics, and extrinsics', 'decode geometry and appearance tokens into 4D Gaussian parameters including xyz, depth, opacity, scaling, and rotation', 'rescale raw Gaussian predictions for depth, opacity, scale, rotation, motion, and temporal covariance to valid ranges', 'build a Temporal Level of Detail image encoder model using TLoDConfig with custom hidden size and depth parameters', 'create a TLoDConfig instance with custom input size, patch size, and DINOv2 version for 4D Gaussian regression', 'run the forward pass of ImageEncoderTLoD with input images, timestamps, camera intrinsics, and camera-to-world matrices', 'review the rescale_predictions method that applies sigmoid activations and learned biases to raw Gaussian parameter predictions', 'summarize the magic_filter method that downsamples Gaussian parameters using magic pattern sampling or opacity-based top-k selection']
```

Usage

```
{'build_4dgaussian_encoder': 'build a 4D Gaussian image encoder model using ImageEncoder4DG with a custom config for pixel-time aligned regression', 'create_encoder_config': 'create an ImageEncoder4DGConfig with custom hidden size, depth, patch size, and attention settings for the encoder', 'run_forward_pass': 'run a forward pass on the ImageEncoder4DG model with input images, timestamps, camera intrinsics, and extrinsics', 'decode_gaussian_params': 'decode geometry and appearance tokens into 4D Gaussian parameters including xyz, depth, opacity, scaling, and rotation', 'rescale_gaussian_predictions': 'rescale raw Gaussian predictions for depth, opacity, scale, rotation, motion, and temporal covariance to valid ranges'}
```

## File: facebookresearch_4dgt/tlod/models/encoders/image_encoder_TLoD.py

Prompts

```
['create a BaseImageEncoderConfig with custom hidden size, depth, and patch size for the image encoder', 'build a BaseImageEncoder transformer model from a BaseImageEncoderConfig with self-attention blocks and layer normalization', 'compute Plucker coordinates from camera intrinsics and extrinsics to get ray origins and directions', 'initialize the BaseImageEncoder model weights using normal distribution and truncation for positional embeddings', 'create a BaseImageEncoder-B factory instance with keyword arguments for hidden size, depth, and patch size', 'build a 4D Gaussian image encoder model using ImageEncoder4DG with a custom config for pixel-time aligned regression', 'create an ImageEncoder4DGConfig with custom hidden size, depth, patch size, and attention settings for the encoder', 'run a forward pass on the ImageEncoder4DG model with input images, timestamps, camera intrinsics, and extrinsics', 'decode geometry and appearance tokens into 4D Gaussian parameters including xyz, depth, opacity, scaling, and rotation', 'rescale raw Gaussian predictions for depth, opacity, scale, rotation, motion, and temporal covariance to valid ranges', 'build a Temporal Level of Detail image encoder model using TLoDConfig with custom hidden size and depth parameters', 'create a TLoDConfig instance with custom input size, patch size, and DINOv2 version for 4D Gaussian regression', 'run the forward pass of ImageEncoderTLoD with input images, timestamps, camera intrinsics, and camera-to-world matrices', 'review the rescale_predictions method that applies sigmoid activations and learned biases to raw Gaussian parameter predictions', 'summarize the magic_filter method that downsamples Gaussian parameters using magic pattern sampling or opacity-based top-k selection']
```

Usage

```
{'build_ImageEncoderTLoD': 'build a Temporal Level of Detail image encoder model using TLoDConfig with custom hidden size and depth parameters', 'create_TLoDConfig': 'create a TLoDConfig instance with custom input size, patch size, and DINOv2 version for 4D Gaussian regression', 'run_forward_ImageEncoderTLoD': 'run the forward pass of ImageEncoderTLoD with input images, timestamps, camera intrinsics, and camera-to-world matrices', 'review_rescale_predictions': 'review the rescale_predictions method that applies sigmoid activations and learned biases to raw Gaussian parameter predictions', 'summarize_magic_filter': 'summarize the magic_filter method that downsamples Gaussian parameters using magic pattern sampling or opacity-based top-k selection'}
```

