# Agent Python Tools

- repo: facebookresearch/omnimatterf
- repo_uri: https://github.com/facebookresearch/omnimatterf

## File: facebookresearch_omnimatterf/third_party/omnimatte/third_party/models/base_model.py

Prompts

```
['create a subclass of BaseModel that implements set_input, forward, and optimize_parameters methods', 'test the BaseModel forward pass by calling model.test() which runs forward under no_grad context', 'save all network checkpoints to disk by calling model.save_networks(epoch) with the current epoch number', 'load all network checkpoints from disk by calling model.load_networks(epoch) with the saved epoch suffix', 'update learning rates for all optimizers by calling model.update_learning_rate() at the end of each epoch', 'get a linear learning rate scheduler that decays the rate to zero over decay epochs', 'get a step learning rate scheduler that reduces the rate by a factor every N epochs', 'get a cosine annealing learning rate scheduler that smoothly decreases the learning rate', 'get a plateau learning rate scheduler that reduces the rate when validation loss stops improving', 'initialize a PyTorch network on specified GPUs with multi-GPU DataParallel support', 'create a LayeredNeuralRenderer model with configurable texture channels, resolution, and number of textures', 'create a keypoint-to-UV UNet model that predicts body part IDs and UV coordinates from keypoint images', 'calculate the alpha regularization loss using L1 and pseudo L0 terms on predicted alpha layers', 'compute the balanced L1 mask loss between predicted alpha matte and trimap targets', 'render layered RGBA output by sampling neural textures with UV maps and compositing through a UNet']
```

Usage

```
{'create_subclass_BaseModel': 'create a subclass of BaseModel that implements set_input, forward, and optimize_parameters methods', 'test_BaseModel_forward': 'test the BaseModel forward pass by calling model.test() which runs forward under no_grad context', 'save_networks_BaseModel': 'save all network checkpoints to disk by calling model.save_networks(epoch) with the current epoch number', 'load_networks_BaseModel': 'load all network checkpoints from disk by calling model.load_networks(epoch) with the saved epoch suffix', 'update_learning_rate_BaseModel': 'update learning rates for all optimizers by calling model.update_learning_rate() at the end of each epoch'}
```

## File: facebookresearch_omnimatterf/third_party/omnimatte/third_party/models/networks.py

Prompts

```
['create a subclass of BaseModel that implements set_input, forward, and optimize_parameters methods', 'test the BaseModel forward pass by calling model.test() which runs forward under no_grad context', 'save all network checkpoints to disk by calling model.save_networks(epoch) with the current epoch number', 'load all network checkpoints from disk by calling model.load_networks(epoch) with the saved epoch suffix', 'update learning rates for all optimizers by calling model.update_learning_rate() at the end of each epoch', 'get a linear learning rate scheduler that decays the rate to zero over decay epochs', 'get a step learning rate scheduler that reduces the rate by a factor every N epochs', 'get a cosine annealing learning rate scheduler that smoothly decreases the learning rate', 'get a plateau learning rate scheduler that reduces the rate when validation loss stops improving', 'initialize a PyTorch network on specified GPUs with multi-GPU DataParallel support', 'create a LayeredNeuralRenderer model with configurable texture channels, resolution, and number of textures', 'create a keypoint-to-UV UNet model that predicts body part IDs and UV coordinates from keypoint images', 'calculate the alpha regularization loss using L1 and pseudo L0 terms on predicted alpha layers', 'compute the balanced L1 mask loss between predicted alpha matte and trimap targets', 'render layered RGBA output by sampling neural textures with UV maps and compositing through a UNet']
```

Usage

```
{'get_scheduler_linear': 'get a linear learning rate scheduler that decays the rate to zero over decay epochs', 'get_scheduler_step': 'get a step learning rate scheduler that reduces the rate by a factor every N epochs', 'get_scheduler_cosine': 'get a cosine annealing learning rate scheduler that smoothly decreases the learning rate', 'get_scheduler_plateau': 'get a plateau learning rate scheduler that reduces the rate when validation loss stops improving', 'init_net_gpu': 'initialize a PyTorch network on specified GPUs with multi-GPU DataParallel support'}
```

## File: facebookresearch_omnimatterf/third_party/omnimatte/third_party/models/networks_lnr.py

Prompts

```
['create a subclass of BaseModel that implements set_input, forward, and optimize_parameters methods', 'test the BaseModel forward pass by calling model.test() which runs forward under no_grad context', 'save all network checkpoints to disk by calling model.save_networks(epoch) with the current epoch number', 'load all network checkpoints from disk by calling model.load_networks(epoch) with the saved epoch suffix', 'update learning rates for all optimizers by calling model.update_learning_rate() at the end of each epoch', 'get a linear learning rate scheduler that decays the rate to zero over decay epochs', 'get a step learning rate scheduler that reduces the rate by a factor every N epochs', 'get a cosine annealing learning rate scheduler that smoothly decreases the learning rate', 'get a plateau learning rate scheduler that reduces the rate when validation loss stops improving', 'initialize a PyTorch network on specified GPUs with multi-GPU DataParallel support', 'create a LayeredNeuralRenderer model with configurable texture channels, resolution, and number of textures', 'create a keypoint-to-UV UNet model that predicts body part IDs and UV coordinates from keypoint images', 'calculate the alpha regularization loss using L1 and pseudo L0 terms on predicted alpha layers', 'compute the balanced L1 mask loss between predicted alpha matte and trimap targets', 'render layered RGBA output by sampling neural textures with UV maps and compositing through a UNet']
```

Usage

```
{'create_LNR': 'create a LayeredNeuralRenderer model with configurable texture channels, resolution, and number of textures', 'create_kp2uv': 'create a keypoint-to-UV UNet model that predicts body part IDs and UV coordinates from keypoint images', 'calculate_alpha_regularization': 'calculate the alpha regularization loss using L1 and pseudo L0 terms on predicted alpha layers', 'compute_mask_loss': 'compute the balanced L1 mask loss between predicted alpha matte and trimap targets', 'render_layered_rgba': 'render layered RGBA output by sampling neural textures with UV maps and compositing through a UNet'}
```

