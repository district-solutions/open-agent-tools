# Agent Python Tools

- repo: facebookresearch/icgan
- repo_uri: https://github.com/facebookresearch/ic_gan

## File: facebookresearch_icgan/stylegan2_ada_pytorch/training/dataset.py

Prompts

```
['create an ImageFolderDataset from a directory of images for StyleGAN2 training', 'create an ImageFolderDataset from a zip file containing images and optional labels', 'create an ImageFolderDataset from an HDF5 file with preloaded image data', 'load an image and its label from a Dataset by index using getitem', 'get a one-hot encoded label for a given index from the Dataset', 'build a StyleGAN2 generator network with MappingNetwork and SynthesisNetwork for image generation', 'build a StyleGAN2 discriminator network with multi-resolution blocks and minibatch standard deviation', 'create a modulated convolution operation with style-based weight modulation and demodulation', 'create a mapping network that transforms input latent Z to intermediate latent W space', 'create a synthesis network that generates images from W-space latents through progressive resolution blocks', 'run the StyleGAN2-ADA training loop with multi-GPU support, ADA augmentation, and checkpointing', 'setup a snapshot image grid from a training dataset for visualization', 'save a numpy image array as a grid PNG file with specified dynamic range', 'resume GAN training from a saved network pickle and optimizer checkpoint', 'evaluate FID metric during training and save the best network snapshot']
```

Usage

```
{'create_ImageFolderDataset_from_directory': 'create an ImageFolderDataset from a directory of images for StyleGAN2 training', 'create_ImageFolderDataset_from_zip': 'create an ImageFolderDataset from a zip file containing images and optional labels', 'create_ImageFolderDataset_from_hdf5': 'create an ImageFolderDataset from an HDF5 file with preloaded image data', 'load_image_with_Dataset_getitem': 'load an image and its label from a Dataset by index using getitem', 'get_label_onehot_from_Dataset': 'get a one-hot encoded label for a given index from the Dataset'}
```

## File: facebookresearch_icgan/stylegan2_ada_pytorch/training/networks.py

Prompts

```
['create an ImageFolderDataset from a directory of images for StyleGAN2 training', 'create an ImageFolderDataset from a zip file containing images and optional labels', 'create an ImageFolderDataset from an HDF5 file with preloaded image data', 'load an image and its label from a Dataset by index using getitem', 'get a one-hot encoded label for a given index from the Dataset', 'build a StyleGAN2 generator network with MappingNetwork and SynthesisNetwork for image generation', 'build a StyleGAN2 discriminator network with multi-resolution blocks and minibatch standard deviation', 'create a modulated convolution operation with style-based weight modulation and demodulation', 'create a mapping network that transforms input latent Z to intermediate latent W space', 'create a synthesis network that generates images from W-space latents through progressive resolution blocks', 'run the StyleGAN2-ADA training loop with multi-GPU support, ADA augmentation, and checkpointing', 'setup a snapshot image grid from a training dataset for visualization', 'save a numpy image array as a grid PNG file with specified dynamic range', 'resume GAN training from a saved network pickle and optimizer checkpoint', 'evaluate FID metric during training and save the best network snapshot']
```

Usage

```
{'build_Generator': 'build a StyleGAN2 generator network with MappingNetwork and SynthesisNetwork for image generation', 'build_Discriminator': 'build a StyleGAN2 discriminator network with multi-resolution blocks and minibatch standard deviation', 'create_modulated_conv2d': 'create a modulated convolution operation with style-based weight modulation and demodulation', 'create_MappingNetwork': 'create a mapping network that transforms input latent Z to intermediate latent W space', 'create_SynthesisNetwork': 'create a synthesis network that generates images from W-space latents through progressive resolution blocks'}
```

## File: facebookresearch_icgan/stylegan2_ada_pytorch/training/training_loop.py

Prompts

```
['create an ImageFolderDataset from a directory of images for StyleGAN2 training', 'create an ImageFolderDataset from a zip file containing images and optional labels', 'create an ImageFolderDataset from an HDF5 file with preloaded image data', 'load an image and its label from a Dataset by index using getitem', 'get a one-hot encoded label for a given index from the Dataset', 'build a StyleGAN2 generator network with MappingNetwork and SynthesisNetwork for image generation', 'build a StyleGAN2 discriminator network with multi-resolution blocks and minibatch standard deviation', 'create a modulated convolution operation with style-based weight modulation and demodulation', 'create a mapping network that transforms input latent Z to intermediate latent W space', 'create a synthesis network that generates images from W-space latents through progressive resolution blocks', 'run the StyleGAN2-ADA training loop with multi-GPU support, ADA augmentation, and checkpointing', 'setup a snapshot image grid from a training dataset for visualization', 'save a numpy image array as a grid PNG file with specified dynamic range', 'resume GAN training from a saved network pickle and optimizer checkpoint', 'evaluate FID metric during training and save the best network snapshot']
```

Usage

```
{'run_training_loop': 'run the StyleGAN2-ADA training loop with multi-GPU support, ADA augmentation, and checkpointing', 'setup_snapshot_image_grid': 'setup a snapshot image grid from a training dataset for visualization', 'save_image_grid': 'save a numpy image array as a grid PNG file with specified dynamic range', 'resume_training_from_checkpoint': 'resume GAN training from a saved network pickle and optimizer checkpoint', 'evaluate_fid_metric': 'evaluate FID metric during training and save the best network snapshot'}
```

