# Agent Python Tools

- repo: facebookresearch/synsin
- repo_uri: https://github.com/facebookresearch/synsin

## File: facebookresearch_synsin/models/losses/gan_loss.py

Prompts

```
['create a GANLoss instance with ls, original, hinge, or w gan_mode for adversarial training', 'compute GAN loss by calling GANLoss with discriminator output tensor and target_is_real flag', 'create a BaseDiscriminator with pix2pixHD network and GAN loss for image discrimination', 'compute discriminator loss by calling compute_discrimator_loss with fake and real image tensors', 'compute generator GAN and feature matching loss using compute_generator_loss with fake and real images', 'create a SSIM loss module with window_size 11 for comparing two images', 'compute the SSIM similarity score between two image tensors using default parameters', 'create a 2D Gaussian window kernel for SSIM calculation with specified window size', 'compute the SSIM score between two images using a mask to ignore certain regions', 'use the SSIM class as a PyTorch nn.Module for differentiable image similarity loss', 'build a SynthesisLoss module that combines L1, perceptual, PSNR, and SSIM losses with configurable weights', 'create a PerceptualLoss module using a frozen VGG19 network to compute multi-layer feature matching loss', 'test the PSNR class to compute peak signal-to-noise ratio between predicted and ground truth images', 'test the SSIM class to compute structural similarity index between predicted and ground truth images', 'review the L1LossWrapper class that wraps nn.L1Loss to return a dictionary with L1 and Total Loss keys']
```

Usage

```
{'create_GANLoss': 'create a GANLoss instance with ls, original, hinge, or w gan_mode for adversarial training', 'compute_GANLoss_call': 'compute GAN loss by calling GANLoss with discriminator output tensor and target_is_real flag', 'create_BaseDiscriminator': 'create a BaseDiscriminator with pix2pixHD network and GAN loss for image discrimination', 'compute_discriminator_loss': 'compute discriminator loss by calling compute_discrimator_loss with fake and real image tensors', 'compute_generator_loss': 'compute generator GAN and feature matching loss using compute_generator_loss with fake and real images'}
```

## File: facebookresearch_synsin/models/losses/ssim.py

Prompts

```
['create a GANLoss instance with ls, original, hinge, or w gan_mode for adversarial training', 'compute GAN loss by calling GANLoss with discriminator output tensor and target_is_real flag', 'create a BaseDiscriminator with pix2pixHD network and GAN loss for image discrimination', 'compute discriminator loss by calling compute_discrimator_loss with fake and real image tensors', 'compute generator GAN and feature matching loss using compute_generator_loss with fake and real images', 'create a SSIM loss module with window_size 11 for comparing two images', 'compute the SSIM similarity score between two image tensors using default parameters', 'create a 2D Gaussian window kernel for SSIM calculation with specified window size', 'compute the SSIM score between two images using a mask to ignore certain regions', 'use the SSIM class as a PyTorch nn.Module for differentiable image similarity loss', 'build a SynthesisLoss module that combines L1, perceptual, PSNR, and SSIM losses with configurable weights', 'create a PerceptualLoss module using a frozen VGG19 network to compute multi-layer feature matching loss', 'test the PSNR class to compute peak signal-to-noise ratio between predicted and ground truth images', 'test the SSIM class to compute structural similarity index between predicted and ground truth images', 'review the L1LossWrapper class that wraps nn.L1Loss to return a dictionary with L1 and Total Loss keys']
```

Usage

```
{'create_ssim_loss_module': 'create a SSIM loss module with window_size 11 for comparing two images', 'compute_ssim_between_images': 'compute the SSIM similarity score between two image tensors using default parameters', 'create_gaussian_window': 'create a 2D Gaussian window kernel for SSIM calculation with specified window size', 'compute_masked_ssim': 'compute the SSIM score between two images using a mask to ignore certain regions', 'use_ssim_as_nn_module': 'use the SSIM class as a PyTorch nn.Module for differentiable image similarity loss'}
```

## File: facebookresearch_synsin/models/losses/synthesis.py

Prompts

```
['create a GANLoss instance with ls, original, hinge, or w gan_mode for adversarial training', 'compute GAN loss by calling GANLoss with discriminator output tensor and target_is_real flag', 'create a BaseDiscriminator with pix2pixHD network and GAN loss for image discrimination', 'compute discriminator loss by calling compute_discrimator_loss with fake and real image tensors', 'compute generator GAN and feature matching loss using compute_generator_loss with fake and real images', 'create a SSIM loss module with window_size 11 for comparing two images', 'compute the SSIM similarity score between two image tensors using default parameters', 'create a 2D Gaussian window kernel for SSIM calculation with specified window size', 'compute the SSIM score between two images using a mask to ignore certain regions', 'use the SSIM class as a PyTorch nn.Module for differentiable image similarity loss', 'build a SynthesisLoss module that combines L1, perceptual, PSNR, and SSIM losses with configurable weights', 'create a PerceptualLoss module using a frozen VGG19 network to compute multi-layer feature matching loss', 'test the PSNR class to compute peak signal-to-noise ratio between predicted and ground truth images', 'test the SSIM class to compute structural similarity index between predicted and ground truth images', 'review the L1LossWrapper class that wraps nn.L1Loss to return a dictionary with L1 and Total Loss keys']
```

Usage

```
{'build_synthesis_loss': 'build a SynthesisLoss module that combines L1, perceptual, PSNR, and SSIM losses with configurable weights', 'create_perceptual_loss': 'create a PerceptualLoss module using a frozen VGG19 network to compute multi-layer feature matching loss', 'test_psnr': 'test the PSNR class to compute peak signal-to-noise ratio between predicted and ground truth images', 'test_ssim': 'test the SSIM class to compute structural similarity index between predicted and ground truth images', 'review_l1losswrapper': 'review the L1LossWrapper class that wraps nn.L1Loss to return a dictionary with L1 and Total Loss keys'}
```

