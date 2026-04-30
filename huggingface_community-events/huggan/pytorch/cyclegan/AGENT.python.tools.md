# Agent Python Tools

- repo: huggingface/community-events
- repo_uri: https://github.com/huggingface/community-events

## File: huggingface_community-events/huggan/pytorch/cyclegan/modeling_cyclegan.py

Prompts

```
['build a GeneratorResNet model with a given input shape and number of residual blocks for CycleGAN image translation', 'build a PatchGAN Discriminator model with a specified number of channels for CycleGAN adversarial training', 'build a ResidualBlock with two convolution layers and instance normalization for use in the generator network', 'run a forward pass through the GeneratorResNet model to translate an input image to the target domain', 'run a forward pass through the Discriminator model to produce a real or fake prediction for an image', 'run cyclegan training on a dataset using the argparse CLI with configurable epochs and batch size', 'run cyclegan training with fp16 or bf16 mixed precision for faster GPU training', 'resume cyclegan training from a saved checkpoint at a specific epoch', 'run cyclegan training and push the trained generator model to the HuggingFace hub', 'run cyclegan training on CPU instead of GPU for testing or limited hardware', 'create a ReplayBuffer with a specified max size for storing GAN training samples', 'push new data into the ReplayBuffer and pop either new or cached samples randomly', 'create a LambdaLR scheduler with n_epochs, offset, and decay_start_epoch parameters', 'compute the learning rate multiplier for a given epoch using the LambdaLR step method', 'review the ReplayBuffer class and its push_and_pop method for GAN training usage']
```

Usage

```
{'build_generator_resnet': 'build a GeneratorResNet model with a given input shape and number of residual blocks for CycleGAN image translation', 'build_discriminator': 'build a PatchGAN Discriminator model with a specified number of channels for CycleGAN adversarial training', 'build_residual_block': 'build a ResidualBlock with two convolution layers and instance normalization for use in the generator network', 'run_generator_forward': 'run a forward pass through the GeneratorResNet model to translate an input image to the target domain', 'run_discriminator_forward': 'run a forward pass through the Discriminator model to produce a real or fake prediction for an image'}
```

## File: huggingface_community-events/huggan/pytorch/cyclegan/train.py

Prompts

```
['build a GeneratorResNet model with a given input shape and number of residual blocks for CycleGAN image translation', 'build a PatchGAN Discriminator model with a specified number of channels for CycleGAN adversarial training', 'build a ResidualBlock with two convolution layers and instance normalization for use in the generator network', 'run a forward pass through the GeneratorResNet model to translate an input image to the target domain', 'run a forward pass through the Discriminator model to produce a real or fake prediction for an image', 'run cyclegan training on a dataset using the argparse CLI with configurable epochs and batch size', 'run cyclegan training with fp16 or bf16 mixed precision for faster GPU training', 'resume cyclegan training from a saved checkpoint at a specific epoch', 'run cyclegan training and push the trained generator model to the HuggingFace hub', 'run cyclegan training on CPU instead of GPU for testing or limited hardware', 'create a ReplayBuffer with a specified max size for storing GAN training samples', 'push new data into the ReplayBuffer and pop either new or cached samples randomly', 'create a LambdaLR scheduler with n_epochs, offset, and decay_start_epoch parameters', 'compute the learning rate multiplier for a given epoch using the LambdaLR step method', 'review the ReplayBuffer class and its push_and_pop method for GAN training usage']
```

Usage

```
{'run_cyclegan_training': 'run cyclegan training on a dataset using the argparse CLI with configurable epochs and batch size', 'run_training_with_mixed_precision': 'run cyclegan training with fp16 or bf16 mixed precision for faster GPU training', 'run_training_resume_checkpoint': 'resume cyclegan training from a saved checkpoint at a specific epoch', 'run_training_push_to_hub': 'run cyclegan training and push the trained generator model to the HuggingFace hub', 'run_training_cpu_mode': 'run cyclegan training on CPU instead of GPU for testing or limited hardware'}
```

## File: huggingface_community-events/huggan/pytorch/cyclegan/utils.py

Prompts

```
['build a GeneratorResNet model with a given input shape and number of residual blocks for CycleGAN image translation', 'build a PatchGAN Discriminator model with a specified number of channels for CycleGAN adversarial training', 'build a ResidualBlock with two convolution layers and instance normalization for use in the generator network', 'run a forward pass through the GeneratorResNet model to translate an input image to the target domain', 'run a forward pass through the Discriminator model to produce a real or fake prediction for an image', 'run cyclegan training on a dataset using the argparse CLI with configurable epochs and batch size', 'run cyclegan training with fp16 or bf16 mixed precision for faster GPU training', 'resume cyclegan training from a saved checkpoint at a specific epoch', 'run cyclegan training and push the trained generator model to the HuggingFace hub', 'run cyclegan training on CPU instead of GPU for testing or limited hardware', 'create a ReplayBuffer with a specified max size for storing GAN training samples', 'push new data into the ReplayBuffer and pop either new or cached samples randomly', 'create a LambdaLR scheduler with n_epochs, offset, and decay_start_epoch parameters', 'compute the learning rate multiplier for a given epoch using the LambdaLR step method', 'review the ReplayBuffer class and its push_and_pop method for GAN training usage']
```

Usage

```
{'create_replay_buffer': 'create a ReplayBuffer with a specified max size for storing GAN training samples', 'push_and_pop_replay_buffer': 'push new data into the ReplayBuffer and pop either new or cached samples randomly', 'create_lambda_lr_scheduler': 'create a LambdaLR scheduler with n_epochs, offset, and decay_start_epoch parameters', 'compute_lr_step': 'compute the learning rate multiplier for a given epoch using the LambdaLR step method', 'review_replay_buffer_class': 'review the ReplayBuffer class and its push_and_pop method for GAN training usage'}
```

