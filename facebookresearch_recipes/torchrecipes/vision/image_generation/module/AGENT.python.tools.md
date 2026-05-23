# Agent Python Tools

- repo: facebookresearch/recipes
- repo_uri: https://github.com/facebookresearch/recipes

## File: facebookresearch_recipes/torchrecipes/vision/image_generation/module/gan.py

Prompts

```
['build a PyTorch Lightning GAN module with generator, discriminator, and adversarial loss criterion', 'train the GAN generator by computing generator loss against discriminator output', 'train the GAN discriminator by computing loss on real and fake images', 'configure Adam optimizers for both generator and discriminator with shared learning rate', 'initialize Conv and BatchNorm layer weights using normal distribution', 'build a PyTorch Lightning InfoGAN module with generator, discriminator, and optimizer configs', 'train the InfoGAN generator by calling generator_step to fool the discriminator', 'train the InfoGAN discriminator by calling discriminator_step to classify real and fake images', 'compute the InfoGAN information loss using categorical and continuous code prediction losses', 'generate sample images with varied latent codes using generate_sample_image method']
```

Usage

```
{'build_GAN_module': 'build a PyTorch Lightning GAN module with generator, discriminator, and adversarial loss criterion', 'train_GAN_generator': 'train the GAN generator by computing generator loss against discriminator output', 'train_GAN_discriminator': 'train the GAN discriminator by computing loss on real and fake images', 'configure_GAN_optimizers': 'configure Adam optimizers for both generator and discriminator with shared learning rate', 'initialize_GAN_weights': 'initialize Conv and BatchNorm layer weights using normal distribution'}
```

## File: facebookresearch_recipes/torchrecipes/vision/image_generation/module/infogan.py

Prompts

```
['build a PyTorch Lightning GAN module with generator, discriminator, and adversarial loss criterion', 'train the GAN generator by computing generator loss against discriminator output', 'train the GAN discriminator by computing loss on real and fake images', 'configure Adam optimizers for both generator and discriminator with shared learning rate', 'initialize Conv and BatchNorm layer weights using normal distribution', 'build a PyTorch Lightning InfoGAN module with generator, discriminator, and optimizer configs', 'train the InfoGAN generator by calling generator_step to fool the discriminator', 'train the InfoGAN discriminator by calling discriminator_step to classify real and fake images', 'compute the InfoGAN information loss using categorical and continuous code prediction losses', 'generate sample images with varied latent codes using generate_sample_image method']
```

Usage

```
{'build_infogan_module': 'build a PyTorch Lightning InfoGAN module with generator, discriminator, and optimizer configs', 'train_infogan_generator': 'train the InfoGAN generator by calling generator_step to fool the discriminator', 'train_infogan_discriminator': 'train the InfoGAN discriminator by calling discriminator_step to classify real and fake images', 'compute_info_loss': 'compute the InfoGAN information loss using categorical and continuous code prediction losses', 'generate_sample_images': 'generate sample images with varied latent codes using generate_sample_image method'}
```

