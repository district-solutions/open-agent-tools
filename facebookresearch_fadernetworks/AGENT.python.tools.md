# Agent Python Tools

- repo: facebookresearch/fadernetworks
- repo_uri: https://github.com/facebookresearch/fadernetworks

## File: facebookresearch_fadernetworks/classifier.py

Prompts

```
['run the classifier training loop for image attribute classification over multiple epochs', 'save the trained classifier model to a .pth file in the experiment dump path', 'build a Classifier model with configurable image size, filters, and hidden dimension parameters', 'compute accuracy on validation and test datasets for each attribute being classified', 'reload a pretrained classifier model from a saved .pth checkpoint file', 'run the interpolate script with --model_path to generate attribute interpolation grids for a trained autoencoder', 'run get_interpolations to encode images and decode them along a latent attribute interpolation path', 'run get_grid to flatten and normalize interpolated image tensors into a torchvision make_grid layout', 'review get_interpolations to understand how alpha values are interpolated between two attribute classes', 'review get_grid to understand how row-wise or column-wise image grids are assembled for visualization']
```

Usage

```
{'run_classifier_training': 'run the classifier training loop for image attribute classification over multiple epochs', 'save_model': 'save the trained classifier model to a .pth file in the experiment dump path', 'build_classifier': 'build a Classifier model with configurable image size, filters, and hidden dimension parameters', 'compute_accuracy': 'compute accuracy on validation and test datasets for each attribute being classified', 'reload_classifier': 'reload a pretrained classifier model from a saved .pth checkpoint file'}
```

## File: facebookresearch_fadernetworks/interpolate.py

Prompts

```
['run the classifier training loop for image attribute classification over multiple epochs', 'save the trained classifier model to a .pth file in the experiment dump path', 'build a Classifier model with configurable image size, filters, and hidden dimension parameters', 'compute accuracy on validation and test datasets for each attribute being classified', 'reload a pretrained classifier model from a saved .pth checkpoint file', 'run the interpolate script with --model_path to generate attribute interpolation grids for a trained autoencoder', 'run get_interpolations to encode images and decode them along a latent attribute interpolation path', 'run get_grid to flatten and normalize interpolated image tensors into a torchvision make_grid layout', 'review get_interpolations to understand how alpha values are interpolated between two attribute classes', 'review get_grid to understand how row-wise or column-wise image grids are assembled for visualization']
```

Usage

```
{'run_interpolate_cli': 'run the interpolate script with --model_path to generate attribute interpolation grids for a trained autoencoder', 'run_get_interpolations': 'run get_interpolations to encode images and decode them along a latent attribute interpolation path', 'run_get_grid': 'run get_grid to flatten and normalize interpolated image tensors into a torchvision make_grid layout', 'review_get_interpolations': 'review get_interpolations to understand how alpha values are interpolated between two attribute classes', 'review_get_grid': 'review get_grid to understand how row-wise or column-wise image grids are assembled for visualization'}
```

