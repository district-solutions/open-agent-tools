# Agent Python Tools

- repo: facebookresearch/pytouch
- repo_uri: https://github.com/facebookresearch/pytouch

## File: facebookresearch_pytouch/pytouch/models/pix2pix/thirdparty/pix2pix/models/base_model.py

Prompts

```
['create a subclass of BaseModel that implements set_input, forward, and optimize_parameters methods', 'save all model networks to disk as checkpoint files for a given epoch number', 'load all model networks from disk checkpoint files for a given epoch or iteration', 'update learning rates for all optimizers using their associated schedulers at the end of each epoch', 'set requires_grad to True or False for all parameters in a list of networks', 'create a ResNet or U-Net generator network for image-to-image translation using define_G', 'create a PatchGAN or PixelGAN discriminator network for adversarial training using define_D', "initialize a PyTorch network's weights using normal, xavier, kaiming, or orthogonal methods", 'create a learning rate scheduler with linear, step, plateau, or cosine decay policy', 'compute GAN adversarial loss using vanilla, LSGAN, or WGAN-GP objectives', 'initialize a Pix2PixModel with opt flags to set up generator, discriminator, and optimizers', 'modify the argparse parser to set pix2pix defaults like unet_256 generator and vanilla GAN mode', 'set input data from the dataloader dict into real_A and real_B tensors on the device', 'run a forward pass through the generator netG to produce fake_B from real_A', 'optimize both discriminator and generator parameters in one training step with forward and backward passes']
```

Usage

```
{'create_subclass_BaseModel': 'create a subclass of BaseModel that implements set_input, forward, and optimize_parameters methods', 'save_networks_epoch': 'save all model networks to disk as checkpoint files for a given epoch number', 'load_networks_epoch': 'load all model networks from disk checkpoint files for a given epoch or iteration', 'update_learning_rate': 'update learning rates for all optimizers using their associated schedulers at the end of each epoch', 'set_requires_grad': 'set requires_grad to True or False for all parameters in a list of networks'}
```

## File: facebookresearch_pytouch/pytouch/models/pix2pix/thirdparty/pix2pix/models/networks.py

Prompts

```
['create a subclass of BaseModel that implements set_input, forward, and optimize_parameters methods', 'save all model networks to disk as checkpoint files for a given epoch number', 'load all model networks from disk checkpoint files for a given epoch or iteration', 'update learning rates for all optimizers using their associated schedulers at the end of each epoch', 'set requires_grad to True or False for all parameters in a list of networks', 'create a ResNet or U-Net generator network for image-to-image translation using define_G', 'create a PatchGAN or PixelGAN discriminator network for adversarial training using define_D', "initialize a PyTorch network's weights using normal, xavier, kaiming, or orthogonal methods", 'create a learning rate scheduler with linear, step, plateau, or cosine decay policy', 'compute GAN adversarial loss using vanilla, LSGAN, or WGAN-GP objectives', 'initialize a Pix2PixModel with opt flags to set up generator, discriminator, and optimizers', 'modify the argparse parser to set pix2pix defaults like unet_256 generator and vanilla GAN mode', 'set input data from the dataloader dict into real_A and real_B tensors on the device', 'run a forward pass through the generator netG to produce fake_B from real_A', 'optimize both discriminator and generator parameters in one training step with forward and backward passes']
```

Usage

```
{'define_G_generator': 'create a ResNet or U-Net generator network for image-to-image translation using define_G', 'define_D_discriminator': 'create a PatchGAN or PixelGAN discriminator network for adversarial training using define_D', 'init_net_weights': "initialize a PyTorch network's weights using normal, xavier, kaiming, or orthogonal methods", 'get_scheduler_lr': 'create a learning rate scheduler with linear, step, plateau, or cosine decay policy', 'GANLoss_compute': 'compute GAN adversarial loss using vanilla, LSGAN, or WGAN-GP objectives'}
```

## File: facebookresearch_pytouch/pytouch/models/pix2pix/thirdparty/pix2pix/models/pix2pix_model.py

Prompts

```
['create a subclass of BaseModel that implements set_input, forward, and optimize_parameters methods', 'save all model networks to disk as checkpoint files for a given epoch number', 'load all model networks from disk checkpoint files for a given epoch or iteration', 'update learning rates for all optimizers using their associated schedulers at the end of each epoch', 'set requires_grad to True or False for all parameters in a list of networks', 'create a ResNet or U-Net generator network for image-to-image translation using define_G', 'create a PatchGAN or PixelGAN discriminator network for adversarial training using define_D', "initialize a PyTorch network's weights using normal, xavier, kaiming, or orthogonal methods", 'create a learning rate scheduler with linear, step, plateau, or cosine decay policy', 'compute GAN adversarial loss using vanilla, LSGAN, or WGAN-GP objectives', 'initialize a Pix2PixModel with opt flags to set up generator, discriminator, and optimizers', 'modify the argparse parser to set pix2pix defaults like unet_256 generator and vanilla GAN mode', 'set input data from the dataloader dict into real_A and real_B tensors on the device', 'run a forward pass through the generator netG to produce fake_B from real_A', 'optimize both discriminator and generator parameters in one training step with forward and backward passes']
```

Usage

```
{'initialize_pix2pix_model': 'initialize a Pix2PixModel with opt flags to set up generator, discriminator, and optimizers', 'modify_commandline_options': 'modify the argparse parser to set pix2pix defaults like unet_256 generator and vanilla GAN mode', 'set_input': 'set input data from the dataloader dict into real_A and real_B tensors on the device', 'forward_pass': 'run a forward pass through the generator netG to produce fake_B from real_A', 'optimize_parameters': 'optimize both discriminator and generator parameters in one training step with forward and backward passes'}
```

