# Agent Python Tools

- repo: google-deepmind/deepmind-research
- repo_uri: https://github.com/google-deepmind/deepmind-research

## File: google-deepmind_deepmind-research/hierarchical_probabilistic_unet/geco_utils.py

Prompts

```
['build a MovingAverage Sonnet module with configurable decay and differentiable flag for VAE training', 'build a LagrangeMultiplier Sonnet module to enforce GECO constraints during variational autoencoder optimization', 'compute cross-entropy loss with optional top-k pixel masking for image segmentation logits and labels', 'review the ce_loss function to understand deterministic versus stochastic top-k pixel selection behavior', 'refactor the MovingAverage module to toggle gradient flow through the most recent input element', 'build a HierarchicalProbUNet model with default latent dimensions and channel configuration for medical image segmentation', 'sample a segmentation from the prior given an input image tensor using the HPUNet sample method', 'reconstruct a segmentation using the posterior by passing segmentation and image tensors to the reconstruct method', 'compute the KL divergence between posterior and prior distributions at each hierarchical level using the kl method', 'compute the full ELBO or GECO training loss by passing segmentation, image, and mask tensors to the loss method', 'test the HierarchicalProbUNet sample method to verify output segmentation shape matches expected dimensions', 'test the HierarchicalProbUNet reconstruct method to verify reconstruction output shape matches segmentation shape', 'test the HierarchicalProbUNet prior method to verify latent distributions and encoder decoder feature shapes', 'test the HierarchicalProbUNet kl method to verify KL divergence dictionary has correct number of entries', 'run the HierarchicalProbUNetTest test suite to validate all shape assertions for the model', 'build a pre-activated residual block with configurable convolutions and channel dimensions for U-Net', 'create a nearest neighbor upsampling operation that scales tensor spatial dimensions by a factor', 'create an average pooling downsampling operation that reduces tensor spatial dimensions by a factor', 'review the res_block function to understand its pre-activation residual architecture and skip connection logic', 'summarize the resize_up and resize_down functions for U-Net encoder decoder spatial scaling']
```

Usage

```
{'build_moving_average_module': 'build a MovingAverage Sonnet module with configurable decay and differentiable flag for VAE training', 'build_lagrange_multiplier_module': 'build a LagrangeMultiplier Sonnet module to enforce GECO constraints during variational autoencoder optimization', 'compute_ce_loss': 'compute cross-entropy loss with optional top-k pixel masking for image segmentation logits and labels', 'review_ce_loss_topk': 'review the ce_loss function to understand deterministic versus stochastic top-k pixel selection behavior', 'refactor_moving_average_differentiable': 'refactor the MovingAverage module to toggle gradient flow through the most recent input element'}
```

## File: google-deepmind_deepmind-research/hierarchical_probabilistic_unet/model.py

Prompts

```
['build a MovingAverage Sonnet module with configurable decay and differentiable flag for VAE training', 'build a LagrangeMultiplier Sonnet module to enforce GECO constraints during variational autoencoder optimization', 'compute cross-entropy loss with optional top-k pixel masking for image segmentation logits and labels', 'review the ce_loss function to understand deterministic versus stochastic top-k pixel selection behavior', 'refactor the MovingAverage module to toggle gradient flow through the most recent input element', 'build a HierarchicalProbUNet model with default latent dimensions and channel configuration for medical image segmentation', 'sample a segmentation from the prior given an input image tensor using the HPUNet sample method', 'reconstruct a segmentation using the posterior by passing segmentation and image tensors to the reconstruct method', 'compute the KL divergence between posterior and prior distributions at each hierarchical level using the kl method', 'compute the full ELBO or GECO training loss by passing segmentation, image, and mask tensors to the loss method', 'test the HierarchicalProbUNet sample method to verify output segmentation shape matches expected dimensions', 'test the HierarchicalProbUNet reconstruct method to verify reconstruction output shape matches segmentation shape', 'test the HierarchicalProbUNet prior method to verify latent distributions and encoder decoder feature shapes', 'test the HierarchicalProbUNet kl method to verify KL divergence dictionary has correct number of entries', 'run the HierarchicalProbUNetTest test suite to validate all shape assertions for the model', 'build a pre-activated residual block with configurable convolutions and channel dimensions for U-Net', 'create a nearest neighbor upsampling operation that scales tensor spatial dimensions by a factor', 'create an average pooling downsampling operation that reduces tensor spatial dimensions by a factor', 'review the res_block function to understand its pre-activation residual architecture and skip connection logic', 'summarize the resize_up and resize_down functions for U-Net encoder decoder spatial scaling']
```

Usage

```
{'build_hpu_net': 'build a HierarchicalProbUNet model with default latent dimensions and channel configuration for medical image segmentation', 'sample_segmentation': 'sample a segmentation from the prior given an input image tensor using the HPUNet sample method', 'reconstruct_segmentation': 'reconstruct a segmentation using the posterior by passing segmentation and image tensors to the reconstruct method', 'compute_kl_divergence': 'compute the KL divergence between posterior and prior distributions at each hierarchical level using the kl method', 'compute_training_loss': 'compute the full ELBO or GECO training loss by passing segmentation, image, and mask tensors to the loss method'}
```

## File: google-deepmind_deepmind-research/hierarchical_probabilistic_unet/model_test.py

Prompts

```
['build a MovingAverage Sonnet module with configurable decay and differentiable flag for VAE training', 'build a LagrangeMultiplier Sonnet module to enforce GECO constraints during variational autoencoder optimization', 'compute cross-entropy loss with optional top-k pixel masking for image segmentation logits and labels', 'review the ce_loss function to understand deterministic versus stochastic top-k pixel selection behavior', 'refactor the MovingAverage module to toggle gradient flow through the most recent input element', 'build a HierarchicalProbUNet model with default latent dimensions and channel configuration for medical image segmentation', 'sample a segmentation from the prior given an input image tensor using the HPUNet sample method', 'reconstruct a segmentation using the posterior by passing segmentation and image tensors to the reconstruct method', 'compute the KL divergence between posterior and prior distributions at each hierarchical level using the kl method', 'compute the full ELBO or GECO training loss by passing segmentation, image, and mask tensors to the loss method', 'test the HierarchicalProbUNet sample method to verify output segmentation shape matches expected dimensions', 'test the HierarchicalProbUNet reconstruct method to verify reconstruction output shape matches segmentation shape', 'test the HierarchicalProbUNet prior method to verify latent distributions and encoder decoder feature shapes', 'test the HierarchicalProbUNet kl method to verify KL divergence dictionary has correct number of entries', 'run the HierarchicalProbUNetTest test suite to validate all shape assertions for the model', 'build a pre-activated residual block with configurable convolutions and channel dimensions for U-Net', 'create a nearest neighbor upsampling operation that scales tensor spatial dimensions by a factor', 'create an average pooling downsampling operation that reduces tensor spatial dimensions by a factor', 'review the res_block function to understand its pre-activation residual architecture and skip connection logic', 'summarize the resize_up and resize_down functions for U-Net encoder decoder spatial scaling']
```

Usage

```
{'test_HierarchicalProbUNet_sample': 'test the HierarchicalProbUNet sample method to verify output segmentation shape matches expected dimensions', 'test_HierarchicalProbUNet_reconstruct': 'test the HierarchicalProbUNet reconstruct method to verify reconstruction output shape matches segmentation shape', 'test_HierarchicalProbUNet_prior': 'test the HierarchicalProbUNet prior method to verify latent distributions and encoder decoder feature shapes', 'test_HierarchicalProbUNet_kl': 'test the HierarchicalProbUNet kl method to verify KL divergence dictionary has correct number of entries', 'run_HierarchicalProbUNetTest': 'run the HierarchicalProbUNetTest test suite to validate all shape assertions for the model'}
```

## File: google-deepmind_deepmind-research/hierarchical_probabilistic_unet/unet_utils.py

Prompts

```
['build a MovingAverage Sonnet module with configurable decay and differentiable flag for VAE training', 'build a LagrangeMultiplier Sonnet module to enforce GECO constraints during variational autoencoder optimization', 'compute cross-entropy loss with optional top-k pixel masking for image segmentation logits and labels', 'review the ce_loss function to understand deterministic versus stochastic top-k pixel selection behavior', 'refactor the MovingAverage module to toggle gradient flow through the most recent input element', 'build a HierarchicalProbUNet model with default latent dimensions and channel configuration for medical image segmentation', 'sample a segmentation from the prior given an input image tensor using the HPUNet sample method', 'reconstruct a segmentation using the posterior by passing segmentation and image tensors to the reconstruct method', 'compute the KL divergence between posterior and prior distributions at each hierarchical level using the kl method', 'compute the full ELBO or GECO training loss by passing segmentation, image, and mask tensors to the loss method', 'test the HierarchicalProbUNet sample method to verify output segmentation shape matches expected dimensions', 'test the HierarchicalProbUNet reconstruct method to verify reconstruction output shape matches segmentation shape', 'test the HierarchicalProbUNet prior method to verify latent distributions and encoder decoder feature shapes', 'test the HierarchicalProbUNet kl method to verify KL divergence dictionary has correct number of entries', 'run the HierarchicalProbUNetTest test suite to validate all shape assertions for the model', 'build a pre-activated residual block with configurable convolutions and channel dimensions for U-Net', 'create a nearest neighbor upsampling operation that scales tensor spatial dimensions by a factor', 'create an average pooling downsampling operation that reduces tensor spatial dimensions by a factor', 'review the res_block function to understand its pre-activation residual architecture and skip connection logic', 'summarize the resize_up and resize_down functions for U-Net encoder decoder spatial scaling']
```

Usage

```
{'build_res_block': 'build a pre-activated residual block with configurable convolutions and channel dimensions for U-Net', 'create_resize_up': 'create a nearest neighbor upsampling operation that scales tensor spatial dimensions by a factor', 'create_resize_down': 'create an average pooling downsampling operation that reduces tensor spatial dimensions by a factor', 'review_res_block': 'review the res_block function to understand its pre-activation residual architecture and skip connection logic', 'summarize_resize_functions': 'summarize the resize_up and resize_down functions for U-Net encoder decoder spatial scaling'}
```

