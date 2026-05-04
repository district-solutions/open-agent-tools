# Agent Python Tools

- repo: facebookresearch/egg
- repo_uri: https://github.com/facebookresearch/egg

## File: facebookresearch_egg/egg/zoo/emcom_as_ssl/scripts/gaussian_noise_analysis.py

Prompts

```
['run the gaussian noise analysis script to evaluate a trained model on random noise data', 'create a dataloader that generates random Gaussian noise images with optional augmentations for evaluation', 'review the GaussianNoiseDataset class that generates random tensor samples with configurable size and transformations', 'review the TransformsGaussianNoise class that applies normalization and optional augmentations to generate image pairs', 'test the get_random_noise_dataloader function to verify it returns a DataLoader with Gaussian noise samples', 'run k-means clustering on ResNet sender outputs to analyze learned representations in EmCom-AS-SSL models', 'assign k-means cluster labels to ResNet sender outputs from an Interaction object with configurable cluster count', 'evaluate a game model on a test dataloader using precomputed k-means clusters and return loss and accuracy metrics', 'review the assign_kmeans_labels function that fits a KMeans model on the first 100k ResNet sender outputs', 'review the evaluate_test_set function that predicts k-means labels and computes soft and game accuracy per batch', 'add CLI arguments for SimCLR sender, shared vision, loss type, checkpoint path, and pdb to an argparse parser', 'build an argparse Namespace with fixed and configurable parameters for the EmCom SSL game including random seed initialization', 'build a game module from params and load its state dict from a checkpoint file path', 'save an Interaction object to a Torch pickle file in the specified log directory path', 'create a PyTorch DataLoader from an ImageFolder dataset with configurable image size, batch size, and augmentations']
```

Usage

```
{'run_gaussian_noise_evaluation': 'run the gaussian noise analysis script to evaluate a trained model on random noise data', 'create_gaussian_noise_dataloader': 'create a dataloader that generates random Gaussian noise images with optional augmentations for evaluation', 'review_GaussianNoiseDataset': 'review the GaussianNoiseDataset class that generates random tensor samples with configurable size and transformations', 'review_TransformsGaussianNoise': 'review the TransformsGaussianNoise class that applies normalization and optional augmentations to generate image pairs', 'test_get_random_noise_dataloader': 'test the get_random_noise_dataloader function to verify it returns a DataLoader with Gaussian noise samples'}
```

## File: facebookresearch_egg/egg/zoo/emcom_as_ssl/scripts/kmeans_analysis.py

Prompts

```
['run the gaussian noise analysis script to evaluate a trained model on random noise data', 'create a dataloader that generates random Gaussian noise images with optional augmentations for evaluation', 'review the GaussianNoiseDataset class that generates random tensor samples with configurable size and transformations', 'review the TransformsGaussianNoise class that applies normalization and optional augmentations to generate image pairs', 'test the get_random_noise_dataloader function to verify it returns a DataLoader with Gaussian noise samples', 'run k-means clustering on ResNet sender outputs to analyze learned representations in EmCom-AS-SSL models', 'assign k-means cluster labels to ResNet sender outputs from an Interaction object with configurable cluster count', 'evaluate a game model on a test dataloader using precomputed k-means clusters and return loss and accuracy metrics', 'review the assign_kmeans_labels function that fits a KMeans model on the first 100k ResNet sender outputs', 'review the evaluate_test_set function that predicts k-means labels and computes soft and game accuracy per batch', 'add CLI arguments for SimCLR sender, shared vision, loss type, checkpoint path, and pdb to an argparse parser', 'build an argparse Namespace with fixed and configurable parameters for the EmCom SSL game including random seed initialization', 'build a game module from params and load its state dict from a checkpoint file path', 'save an Interaction object to a Torch pickle file in the specified log directory path', 'create a PyTorch DataLoader from an ImageFolder dataset with configurable image size, batch size, and augmentations']
```

Usage

```
{'run_kmeans_analysis': 'run k-means clustering on ResNet sender outputs to analyze learned representations in EmCom-AS-SSL models', 'assign_kmeans_labels': 'assign k-means cluster labels to ResNet sender outputs from an Interaction object with configurable cluster count', 'evaluate_test_set': 'evaluate a game model on a test dataloader using precomputed k-means clusters and return loss and accuracy metrics', 'review_assign_kmeans_labels': 'review the assign_kmeans_labels function that fits a KMeans model on the first 100k ResNet sender outputs', 'review_evaluate_test_set': 'review the evaluate_test_set function that predicts k-means labels and computes soft and game accuracy per batch'}
```

## File: facebookresearch_egg/egg/zoo/emcom_as_ssl/scripts/utils.py

Prompts

```
['run the gaussian noise analysis script to evaluate a trained model on random noise data', 'create a dataloader that generates random Gaussian noise images with optional augmentations for evaluation', 'review the GaussianNoiseDataset class that generates random tensor samples with configurable size and transformations', 'review the TransformsGaussianNoise class that applies normalization and optional augmentations to generate image pairs', 'test the get_random_noise_dataloader function to verify it returns a DataLoader with Gaussian noise samples', 'run k-means clustering on ResNet sender outputs to analyze learned representations in EmCom-AS-SSL models', 'assign k-means cluster labels to ResNet sender outputs from an Interaction object with configurable cluster count', 'evaluate a game model on a test dataloader using precomputed k-means clusters and return loss and accuracy metrics', 'review the assign_kmeans_labels function that fits a KMeans model on the first 100k ResNet sender outputs', 'review the evaluate_test_set function that predicts k-means labels and computes soft and game accuracy per batch', 'add CLI arguments for SimCLR sender, shared vision, loss type, checkpoint path, and pdb to an argparse parser', 'build an argparse Namespace with fixed and configurable parameters for the EmCom SSL game including random seed initialization', 'build a game module from params and load its state dict from a checkpoint file path', 'save an Interaction object to a Torch pickle file in the specified log directory path', 'create a PyTorch DataLoader from an ImageFolder dataset with configurable image size, batch size, and augmentations']
```

Usage

```
{'add_common_cli_args': 'add CLI arguments for SimCLR sender, shared vision, loss type, checkpoint path, and pdb to an argparse parser', 'get_params': 'build an argparse Namespace with fixed and configurable parameters for the EmCom SSL game including random seed initialization', 'get_game': 'build a game module from params and load its state dict from a checkpoint file path', 'save_interaction': 'save an Interaction object to a Torch pickle file in the specified log directory path', 'get_dataloader': 'create a PyTorch DataLoader from an ImageFolder dataset with configurable image size, batch size, and augmentations'}
```

