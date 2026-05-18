# Agent Python Tools

- repo: facebookresearch/meshtalk
- repo_uri: https://github.com/facebookresearch/meshtalk

## File: facebookresearch_meshtalk/training/forwarder.py

Prompts

```
['quantize logprobs tensors using Gumbel-Softmax sampling to produce one-hot vectors and class labels', 'sample discrete latent codes from logprobs using the Gumbel-Softmax reparameterization trick with temperature', 'train expression codes using DiscreteExpressionForwarder with reconstruction, landmark, and modality crossing losses', 'train the autoregressive context model using CategoricalAutoregressiveForwarder with cross-entropy loss on quantized codes', 'reconstruct 3D facial geometry from expression and audio codes using the geom_unet and encoder', 'create a Trainer instance with config, forwarder, train_dataset, and val_dataset to prepare for training', 'run the Trainer train method to execute training iterations with learning rate scheduling and validation', 'run a single training step that performs forward pass, computes weighted loss, and backpropagates gradients', 'run a validation step that evaluates models on a random batch from the validation dataset', 'run the cycle function to create an infinite iterator over a PyTorch DataLoader for continuous training']
```

Usage

```
{'quantize_logprobs': 'quantize logprobs tensors using Gumbel-Softmax sampling to produce one-hot vectors and class labels', 'gumbel_softmax_sample': 'sample discrete latent codes from logprobs using the Gumbel-Softmax reparameterization trick with temperature', 'train_expression_codes': 'train expression codes using DiscreteExpressionForwarder with reconstruction, landmark, and modality crossing losses', 'train_autoregressive_model': 'train the autoregressive context model using CategoricalAutoregressiveForwarder with cross-entropy loss on quantized codes', 'reconstruct_geometry': 'reconstruct 3D facial geometry from expression and audio codes using the geom_unet and encoder'}
```

## File: facebookresearch_meshtalk/training/trainer.py

Prompts

```
['quantize logprobs tensors using Gumbel-Softmax sampling to produce one-hot vectors and class labels', 'sample discrete latent codes from logprobs using the Gumbel-Softmax reparameterization trick with temperature', 'train expression codes using DiscreteExpressionForwarder with reconstruction, landmark, and modality crossing losses', 'train the autoregressive context model using CategoricalAutoregressiveForwarder with cross-entropy loss on quantized codes', 'reconstruct 3D facial geometry from expression and audio codes using the geom_unet and encoder', 'create a Trainer instance with config, forwarder, train_dataset, and val_dataset to prepare for training', 'run the Trainer train method to execute training iterations with learning rate scheduling and validation', 'run a single training step that performs forward pass, computes weighted loss, and backpropagates gradients', 'run a validation step that evaluates models on a random batch from the validation dataset', 'run the cycle function to create an infinite iterator over a PyTorch DataLoader for continuous training']
```

Usage

```
{'create_Trainer': 'create a Trainer instance with config, forwarder, train_dataset, and val_dataset to prepare for training', 'run_Trainer_train': 'run the Trainer train method to execute training iterations with learning rate scheduling and validation', 'run_Trainer_training_step': 'run a single training step that performs forward pass, computes weighted loss, and backpropagates gradients', 'run_Trainer_validation_step': 'run a validation step that evaluates models on a random batch from the validation dataset', 'run_cycle_dataloader': 'run the cycle function to create an infinite iterator over a PyTorch DataLoader for continuous training'}
```

