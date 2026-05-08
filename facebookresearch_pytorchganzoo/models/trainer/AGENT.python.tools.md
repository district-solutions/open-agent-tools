# Agent Python Tools

- repo: facebookresearch/pytorchganzoo
- repo_uri: https://github.com/facebookresearch/pytorch_gan_zoo

## File: facebookresearch_pytorchganzoo/models/trainer/DCGAN_trainer.py

Prompts

```
['train a DCGAN model for the specified number of epochs and save a checkpoint', 'initialize a product GAN by loading pretrained discriminator and generator networks from .pt files', 'create a DCGANTrainer instance with a dataset path and optional GANTrainer kwargs', "initialize the DCGAN model using the trainer's model config and GPU setting", 'get the default configuration for the DCGANTrainer from the class-level _defaultConfig', 'create a GANTrainer instance with a dataset path, GPU flag, visualization module, and training config', 'train the GAN model on one epoch using a DataLoader, tracking losses and saving checkpoints', 'load a saved checkpoint to resume GAN training from a specific scale and iteration', 'save the GAN model weights, temporary config, loss logs, and reference vectors to disk', 'get a DataLoader for the training dataset at a given resolution scale with proper transforms', 'create a ProgressiveGANTrainer instance with a dataset path, mini batch scheduler, and config scheduler', 'run progressive GAN training across multiple resolution scales with alpha blending and checkpoint saving', "build a ProgressiveGAN model from the trainer's configuration and GPU settings", 'compute alpha jump iteration schedules and values for each resolution scale', 'add new resolution scales with custom or linear alpha jump configuration to the trainer', 'create a StyleGANTrainer instance with a dataset path and optional keyword arguments', 'initialize a StyleGAN model with depth scales and GPU settings via initModel', 'get the default StyleGAN configuration object from the trainer class', 'review the StyleGANTrainer class that extends ProgressiveGANTrainer for StyleGAN training', 'run progressive StyleGAN training using the StyleGANTrainer with a dataset path']
```

Usage

```
{'train_DCGAN_model': 'train a DCGAN model for the specified number of epochs and save a checkpoint', 'initialize_DCGAN_with_pretrained_networks': 'initialize a product GAN by loading pretrained discriminator and generator networks from .pt files', 'create_DCGAN_trainer': 'create a DCGANTrainer instance with a dataset path and optional GANTrainer kwargs', 'init_DCGAN_model': "initialize the DCGAN model using the trainer's model config and GPU setting", 'get_DCGAN_default_config': 'get the default configuration for the DCGANTrainer from the class-level _defaultConfig'}
```

## File: facebookresearch_pytorchganzoo/models/trainer/gan_trainer.py

Prompts

```
['train a DCGAN model for the specified number of epochs and save a checkpoint', 'initialize a product GAN by loading pretrained discriminator and generator networks from .pt files', 'create a DCGANTrainer instance with a dataset path and optional GANTrainer kwargs', "initialize the DCGAN model using the trainer's model config and GPU setting", 'get the default configuration for the DCGANTrainer from the class-level _defaultConfig', 'create a GANTrainer instance with a dataset path, GPU flag, visualization module, and training config', 'train the GAN model on one epoch using a DataLoader, tracking losses and saving checkpoints', 'load a saved checkpoint to resume GAN training from a specific scale and iteration', 'save the GAN model weights, temporary config, loss logs, and reference vectors to disk', 'get a DataLoader for the training dataset at a given resolution scale with proper transforms', 'create a ProgressiveGANTrainer instance with a dataset path, mini batch scheduler, and config scheduler', 'run progressive GAN training across multiple resolution scales with alpha blending and checkpoint saving', "build a ProgressiveGAN model from the trainer's configuration and GPU settings", 'compute alpha jump iteration schedules and values for each resolution scale', 'add new resolution scales with custom or linear alpha jump configuration to the trainer', 'create a StyleGANTrainer instance with a dataset path and optional keyword arguments', 'initialize a StyleGAN model with depth scales and GPU settings via initModel', 'get the default StyleGAN configuration object from the trainer class', 'review the StyleGANTrainer class that extends ProgressiveGANTrainer for StyleGAN training', 'run progressive StyleGAN training using the StyleGANTrainer with a dataset path']
```

Usage

```
{'init_GANTrainer': 'create a GANTrainer instance with a dataset path, GPU flag, visualization module, and training config', 'trainOnEpoch_GANTrainer': 'train the GAN model on one epoch using a DataLoader, tracking losses and saving checkpoints', 'loadSavedTraining_GANTrainer': 'load a saved checkpoint to resume GAN training from a specific scale and iteration', 'saveCheckpoint_GANTrainer': 'save the GAN model weights, temporary config, loss logs, and reference vectors to disk', 'getDBLoader_GANTrainer': 'get a DataLoader for the training dataset at a given resolution scale with proper transforms'}
```

## File: facebookresearch_pytorchganzoo/models/trainer/progressive_gan_trainer.py

Prompts

```
['train a DCGAN model for the specified number of epochs and save a checkpoint', 'initialize a product GAN by loading pretrained discriminator and generator networks from .pt files', 'create a DCGANTrainer instance with a dataset path and optional GANTrainer kwargs', "initialize the DCGAN model using the trainer's model config and GPU setting", 'get the default configuration for the DCGANTrainer from the class-level _defaultConfig', 'create a GANTrainer instance with a dataset path, GPU flag, visualization module, and training config', 'train the GAN model on one epoch using a DataLoader, tracking losses and saving checkpoints', 'load a saved checkpoint to resume GAN training from a specific scale and iteration', 'save the GAN model weights, temporary config, loss logs, and reference vectors to disk', 'get a DataLoader for the training dataset at a given resolution scale with proper transforms', 'create a ProgressiveGANTrainer instance with a dataset path, mini batch scheduler, and config scheduler', 'run progressive GAN training across multiple resolution scales with alpha blending and checkpoint saving', "build a ProgressiveGAN model from the trainer's configuration and GPU settings", 'compute alpha jump iteration schedules and values for each resolution scale', 'add new resolution scales with custom or linear alpha jump configuration to the trainer', 'create a StyleGANTrainer instance with a dataset path and optional keyword arguments', 'initialize a StyleGAN model with depth scales and GPU settings via initModel', 'get the default StyleGAN configuration object from the trainer class', 'review the StyleGANTrainer class that extends ProgressiveGANTrainer for StyleGAN training', 'run progressive StyleGAN training using the StyleGANTrainer with a dataset path']
```

Usage

```
{'init_ProgressiveGANTrainer': 'create a ProgressiveGANTrainer instance with a dataset path, mini batch scheduler, and config scheduler', 'train_ProgressiveGANTrainer': 'run progressive GAN training across multiple resolution scales with alpha blending and checkpoint saving', 'initModel_ProgressiveGANTrainer': "build a ProgressiveGAN model from the trainer's configuration and GPU settings", 'updateAlphaJumps_ProgressiveGANTrainer': 'compute alpha jump iteration schedules and values for each resolution scale', 'addNewScales_ProgressiveGANTrainer': 'add new resolution scales with custom or linear alpha jump configuration to the trainer'}
```

## File: facebookresearch_pytorchganzoo/models/trainer/styleGAN_trainer.py

Prompts

```
['train a DCGAN model for the specified number of epochs and save a checkpoint', 'initialize a product GAN by loading pretrained discriminator and generator networks from .pt files', 'create a DCGANTrainer instance with a dataset path and optional GANTrainer kwargs', "initialize the DCGAN model using the trainer's model config and GPU setting", 'get the default configuration for the DCGANTrainer from the class-level _defaultConfig', 'create a GANTrainer instance with a dataset path, GPU flag, visualization module, and training config', 'train the GAN model on one epoch using a DataLoader, tracking losses and saving checkpoints', 'load a saved checkpoint to resume GAN training from a specific scale and iteration', 'save the GAN model weights, temporary config, loss logs, and reference vectors to disk', 'get a DataLoader for the training dataset at a given resolution scale with proper transforms', 'create a ProgressiveGANTrainer instance with a dataset path, mini batch scheduler, and config scheduler', 'run progressive GAN training across multiple resolution scales with alpha blending and checkpoint saving', "build a ProgressiveGAN model from the trainer's configuration and GPU settings", 'compute alpha jump iteration schedules and values for each resolution scale', 'add new resolution scales with custom or linear alpha jump configuration to the trainer', 'create a StyleGANTrainer instance with a dataset path and optional keyword arguments', 'initialize a StyleGAN model with depth scales and GPU settings via initModel', 'get the default StyleGAN configuration object from the trainer class', 'review the StyleGANTrainer class that extends ProgressiveGANTrainer for StyleGAN training', 'run progressive StyleGAN training using the StyleGANTrainer with a dataset path']
```

Usage

```
{'init_StyleGANTrainer': 'create a StyleGANTrainer instance with a dataset path and optional keyword arguments', 'initModel_StyleGANTrainer': 'initialize a StyleGAN model with depth scales and GPU settings via initModel', 'getDefaultConfig_StyleGANTrainer': 'get the default StyleGAN configuration object from the trainer class', 'review_StyleGANTrainer_class': 'review the StyleGANTrainer class that extends ProgressiveGANTrainer for StyleGAN training', 'run_StyleGAN_training': 'run progressive StyleGAN training using the StyleGANTrainer with a dataset path'}
```

