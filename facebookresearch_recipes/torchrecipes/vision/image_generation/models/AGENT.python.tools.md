# Agent Python Tools

- repo: facebookresearch/recipes
- repo_uri: https://github.com/facebookresearch/recipes

## File: facebookresearch_recipes/torchrecipes/vision/image_generation/models/dcgan.py

Prompts

```
['build a DCGAN Generator network from a latent dimension to generate fake images', 'build a DCGAN Discriminator network to classify real versus generated images', 'generate fake images by passing random noise through the DCGAN Generator forward pass', 'discriminate real from fake images by passing them through the DCGAN Discriminator forward pass', 'review the DCGAN Generator and Discriminator block architecture using transposed convolutions and batch normalization', 'create a Generator model with a given latent dimension and image shape for GAN training', 'create a Discriminator model with a given image shape for classifying real versus fake images', 'run the Generator forward pass to produce fake images from a latent noise tensor', 'run the Discriminator forward pass to classify images as real or fake with a sigmoid output', 'review the Generator class which uses four fully connected layers with leaky ReLU activations', 'build a Generator model that takes noise, labels, and code to generate images using upsampling conv blocks', 'build a Discriminator model that returns validity, label predictions, and latent codes from input images', 'review the discriminator_block helper function that builds Conv2d, LeakyReLU, Dropout2d, and optional BatchNorm2d layers']
```

Usage

```
{'build_dcgan_generator': 'build a DCGAN Generator network from a latent dimension to generate fake images', 'build_dcgan_discriminator': 'build a DCGAN Discriminator network to classify real versus generated images', 'generate_images_with_dcgan': 'generate fake images by passing random noise through the DCGAN Generator forward pass', 'discriminate_images_with_dcgan': 'discriminate real from fake images by passing them through the DCGAN Discriminator forward pass', 'review_dcgan_architecture': 'review the DCGAN Generator and Discriminator block architecture using transposed convolutions and batch normalization'}
```

## File: facebookresearch_recipes/torchrecipes/vision/image_generation/models/gan.py

Prompts

```
['build a DCGAN Generator network from a latent dimension to generate fake images', 'build a DCGAN Discriminator network to classify real versus generated images', 'generate fake images by passing random noise through the DCGAN Generator forward pass', 'discriminate real from fake images by passing them through the DCGAN Discriminator forward pass', 'review the DCGAN Generator and Discriminator block architecture using transposed convolutions and batch normalization', 'create a Generator model with a given latent dimension and image shape for GAN training', 'create a Discriminator model with a given image shape for classifying real versus fake images', 'run the Generator forward pass to produce fake images from a latent noise tensor', 'run the Discriminator forward pass to classify images as real or fake with a sigmoid output', 'review the Generator class which uses four fully connected layers with leaky ReLU activations', 'build a Generator model that takes noise, labels, and code to generate images using upsampling conv blocks', 'build a Discriminator model that returns validity, label predictions, and latent codes from input images', 'review the discriminator_block helper function that builds Conv2d, LeakyReLU, Dropout2d, and optional BatchNorm2d layers']
```

Usage

```
{'create_generator': 'create a Generator model with a given latent dimension and image shape for GAN training', 'create_discriminator': 'create a Discriminator model with a given image shape for classifying real versus fake images', 'run_generator_forward': 'run the Generator forward pass to produce fake images from a latent noise tensor', 'run_discriminator_forward': 'run the Discriminator forward pass to classify images as real or fake with a sigmoid output', 'review_generator_architecture': 'review the Generator class which uses four fully connected layers with leaky ReLU activations'}
```

## File: facebookresearch_recipes/torchrecipes/vision/image_generation/models/infogan.py

Prompts

```
['build a DCGAN Generator network from a latent dimension to generate fake images', 'build a DCGAN Discriminator network to classify real versus generated images', 'generate fake images by passing random noise through the DCGAN Generator forward pass', 'discriminate real from fake images by passing them through the DCGAN Discriminator forward pass', 'review the DCGAN Generator and Discriminator block architecture using transposed convolutions and batch normalization', 'create a Generator model with a given latent dimension and image shape for GAN training', 'create a Discriminator model with a given image shape for classifying real versus fake images', 'run the Generator forward pass to produce fake images from a latent noise tensor', 'run the Discriminator forward pass to classify images as real or fake with a sigmoid output', 'review the Generator class which uses four fully connected layers with leaky ReLU activations', 'build a Generator model that takes noise, labels, and code to generate images using upsampling conv blocks', 'build a Discriminator model that returns validity, label predictions, and latent codes from input images', 'review the discriminator_block helper function that builds Conv2d, LeakyReLU, Dropout2d, and optional BatchNorm2d layers']
```

Usage

```
{'build_generator': 'build a Generator model that takes noise, labels, and code to generate images using upsampling conv blocks', 'build_discriminator': 'build a Discriminator model that returns validity, label predictions, and latent codes from input images', 'run_generator_forward': 'run the Generator forward pass with noise, labels, and code tensors to produce generated images', 'run_discriminator_forward': 'run the Discriminator forward pass on an image tensor to get validity, label, and latent code outputs', 'review_discriminator_block': 'review the discriminator_block helper function that builds Conv2d, LeakyReLU, Dropout2d, and optional BatchNorm2d layers'}
```

