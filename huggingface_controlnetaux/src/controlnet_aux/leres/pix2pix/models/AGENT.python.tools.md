# Agent Python Tools

- repo: huggingface/controlnetaux
- repo_uri: https://github.com/huggingface/controlnet_aux

## File: huggingface_controlnetaux/src/controlnet_aux/leres/pix2pix/models/base_model.py

Prompts

```
['create a subclass of BaseModel implementing set_input, forward, and optimize_parameters methods', 'save all network state dicts to disk using save_networks with the current epoch number', 'load all network state dicts from disk using load_networks with the given epoch suffix', 'update learning rates for all optimizers by stepping through each scheduler in the model', 'set requires_grad to true or false for all parameters in a list of networks', 'initialize a BaseModelHG instance with training options including GPU IDs and checkpoint directory', 'save a PyTorch network state dict to a .pth file using save_network helper method', 'load a PyTorch network state dict from a .pth file using load_network helper method', 'set the input data for the BaseModelHG instance using the set_input method', 'run the BaseModelHG test method for inference without backpropagation', 'create a pix2pix generator network using define_G with resnet_9blocks or unet_256 architecture', 'create a PatchGAN or PixelGAN discriminator using define_D with n_layers configuration', 'build a GAN loss function using GANLoss class with vanilla, lsgan, or wgangp mode', 'setup a learning rate scheduler using get_scheduler with linear, step, plateau, or cosine policy', 'calculate the WGAN-GP gradient penalty using cal_gradient_penalty for discriminator training', 'build a pix2pix depth estimation model with UNet generator and PatchGAN discriminator', 'create a training pipeline that optimizes both generator and discriminator with GAN and L1 loss', 'run a forward pass through the generator network to produce fake depth output images', 'refactor the set_input method to preprocess and normalize outer and inner input tensors', 'review the backward_D and backward_G methods for GAN discriminator and generator gradient computation']
```

Usage

```
{'create_subclass_BaseModel': 'create a subclass of BaseModel implementing set_input, forward, and optimize_parameters methods', 'save_networks_by_epoch': 'save all network state dicts to disk using save_networks with the current epoch number', 'load_networks_by_epoch': 'load all network state dicts from disk using load_networks with the given epoch suffix', 'update_learning_rate_schedulers': 'update learning rates for all optimizers by stepping through each scheduler in the model', 'set_requires_grad_for_nets': 'set requires_grad to true or false for all parameters in a list of networks'}
```

## File: huggingface_controlnetaux/src/controlnet_aux/leres/pix2pix/models/base_model_hg.py

Prompts

```
['create a subclass of BaseModel implementing set_input, forward, and optimize_parameters methods', 'save all network state dicts to disk using save_networks with the current epoch number', 'load all network state dicts from disk using load_networks with the given epoch suffix', 'update learning rates for all optimizers by stepping through each scheduler in the model', 'set requires_grad to true or false for all parameters in a list of networks', 'initialize a BaseModelHG instance with training options including GPU IDs and checkpoint directory', 'save a PyTorch network state dict to a .pth file using save_network helper method', 'load a PyTorch network state dict from a .pth file using load_network helper method', 'set the input data for the BaseModelHG instance using the set_input method', 'run the BaseModelHG test method for inference without backpropagation', 'create a pix2pix generator network using define_G with resnet_9blocks or unet_256 architecture', 'create a PatchGAN or PixelGAN discriminator using define_D with n_layers configuration', 'build a GAN loss function using GANLoss class with vanilla, lsgan, or wgangp mode', 'setup a learning rate scheduler using get_scheduler with linear, step, plateau, or cosine policy', 'calculate the WGAN-GP gradient penalty using cal_gradient_penalty for discriminator training', 'build a pix2pix depth estimation model with UNet generator and PatchGAN discriminator', 'create a training pipeline that optimizes both generator and discriminator with GAN and L1 loss', 'run a forward pass through the generator network to produce fake depth output images', 'refactor the set_input method to preprocess and normalize outer and inner input tensors', 'review the backward_D and backward_G methods for GAN discriminator and generator gradient computation']
```

Usage

```
{'initialize_BaseModelHG': 'initialize a BaseModelHG instance with training options including GPU IDs and checkpoint directory', 'save_network_BaseModelHG': 'save a PyTorch network state dict to a .pth file using save_network helper method', 'load_network_BaseModelHG': 'load a PyTorch network state dict from a .pth file using load_network helper method', 'set_input_BaseModelHG': 'set the input data for the BaseModelHG instance using the set_input method', 'test_BaseModelHG': 'run the BaseModelHG test method for inference without backpropagation'}
```

## File: huggingface_controlnetaux/src/controlnet_aux/leres/pix2pix/models/networks.py

Prompts

```
['create a subclass of BaseModel implementing set_input, forward, and optimize_parameters methods', 'save all network state dicts to disk using save_networks with the current epoch number', 'load all network state dicts from disk using load_networks with the given epoch suffix', 'update learning rates for all optimizers by stepping through each scheduler in the model', 'set requires_grad to true or false for all parameters in a list of networks', 'initialize a BaseModelHG instance with training options including GPU IDs and checkpoint directory', 'save a PyTorch network state dict to a .pth file using save_network helper method', 'load a PyTorch network state dict from a .pth file using load_network helper method', 'set the input data for the BaseModelHG instance using the set_input method', 'run the BaseModelHG test method for inference without backpropagation', 'create a pix2pix generator network using define_G with resnet_9blocks or unet_256 architecture', 'create a PatchGAN or PixelGAN discriminator using define_D with n_layers configuration', 'build a GAN loss function using GANLoss class with vanilla, lsgan, or wgangp mode', 'setup a learning rate scheduler using get_scheduler with linear, step, plateau, or cosine policy', 'calculate the WGAN-GP gradient penalty using cal_gradient_penalty for discriminator training', 'build a pix2pix depth estimation model with UNet generator and PatchGAN discriminator', 'create a training pipeline that optimizes both generator and discriminator with GAN and L1 loss', 'run a forward pass through the generator network to produce fake depth output images', 'refactor the set_input method to preprocess and normalize outer and inner input tensors', 'review the backward_D and backward_G methods for GAN discriminator and generator gradient computation']
```

Usage

```
{'create_generator_network': 'create a pix2pix generator network using define_G with resnet_9blocks or unet_256 architecture', 'create_discriminator_network': 'create a PatchGAN or PixelGAN discriminator using define_D with n_layers configuration', 'build_gan_loss': 'build a GAN loss function using GANLoss class with vanilla, lsgan, or wgangp mode', 'setup_lr_scheduler': 'setup a learning rate scheduler using get_scheduler with linear, step, plateau, or cosine policy', 'calculate_gradient_penalty': 'calculate the WGAN-GP gradient penalty using cal_gradient_penalty for discriminator training'}
```

## File: huggingface_controlnetaux/src/controlnet_aux/leres/pix2pix/models/pix2pix4depth_model.py

Prompts

```
['create a subclass of BaseModel implementing set_input, forward, and optimize_parameters methods', 'save all network state dicts to disk using save_networks with the current epoch number', 'load all network state dicts from disk using load_networks with the given epoch suffix', 'update learning rates for all optimizers by stepping through each scheduler in the model', 'set requires_grad to true or false for all parameters in a list of networks', 'initialize a BaseModelHG instance with training options including GPU IDs and checkpoint directory', 'save a PyTorch network state dict to a .pth file using save_network helper method', 'load a PyTorch network state dict from a .pth file using load_network helper method', 'set the input data for the BaseModelHG instance using the set_input method', 'run the BaseModelHG test method for inference without backpropagation', 'create a pix2pix generator network using define_G with resnet_9blocks or unet_256 architecture', 'create a PatchGAN or PixelGAN discriminator using define_D with n_layers configuration', 'build a GAN loss function using GANLoss class with vanilla, lsgan, or wgangp mode', 'setup a learning rate scheduler using get_scheduler with linear, step, plateau, or cosine policy', 'calculate the WGAN-GP gradient penalty using cal_gradient_penalty for discriminator training', 'build a pix2pix depth estimation model with UNet generator and PatchGAN discriminator', 'create a training pipeline that optimizes both generator and discriminator with GAN and L1 loss', 'run a forward pass through the generator network to produce fake depth output images', 'refactor the set_input method to preprocess and normalize outer and inner input tensors', 'review the backward_D and backward_G methods for GAN discriminator and generator gradient computation']
```

Usage

```
{'build_pix2pix_depth_model': 'build a pix2pix depth estimation model with UNet generator and PatchGAN discriminator', 'create_training_pipeline': 'create a training pipeline that optimizes both generator and discriminator with GAN and L1 loss', 'run_forward_pass': 'run a forward pass through the generator network to produce fake depth output images', 'refactor_set_input': 'refactor the set_input method to preprocess and normalize outer and inner input tensors', 'review_backward_passes': 'review the backward_D and backward_G methods for GAN discriminator and generator gradient computation'}
```

