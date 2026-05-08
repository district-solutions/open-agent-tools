# Agent Python Tools

- repo: facebookresearch/craftassist
- repo_uri: https://github.com/facebookresearch/craftassist

## File: facebookresearch_craftassist/python/craftassist/voxel_models/semantic_segmentation/data_loaders.py

Prompts

```
['create a SemSegData dataset from a pickle file with configurable sidelength and augmentation options', 'randomly rotate or flip a 3D voxel cube tensor and its labels for data augmentation', 'crop and pad a 3D voxel schematic to fit a fixed sidelength cube with random shifts', 'merge rare and plural semantic classes below a minimum occurrence threshold into a unified class map', 'pad a 3D voxel schematic tensor to a target sidelength using PyTorch functional padding', 'build a 3D convolutional semantic segmentation network for voxel block classification using SemSegNet', 'run the SemSegNet module via CLI with argparse to create a model with custom hidden and embedding dimensions', 'create a SemSegWrapper to load a trained model and segment voxel blocks into semantic object classes', 'test the SemSegWrapper segment_object method to classify 3D voxel blocks and return labeled locations', 'review the SemSegNet forward pass that embeds block IDs and runs them through stacked 3D conv layers', 'run the semantic segmentation training loop with configurable epochs, batch size, and learning rate via CLI args', 'validate a semantic segmentation model on a DataLoader and return per-batch losses and accuracies', 'compute masked NLL loss for semantic segmentation predictions sampling empty voxels with configurable probability', 'calculate classification accuracy by comparing predicted class indices against ground truth labels', 'train one epoch of a semantic segmentation model returning per-batch losses and accuracies']
```

Usage

```
{'create_semseg_dataset': 'create a SemSegData dataset from a pickle file with configurable sidelength and augmentation options', 'flip_rotate_voxel_cube': 'randomly rotate or flip a 3D voxel cube tensor and its labels for data augmentation', 'fit_schematic_in_sidelength': 'crop and pad a 3D voxel schematic to fit a fixed sidelength cube with random shifts', 'organize_semantic_classes': 'merge rare and plural semantic classes below a minimum occurrence threshold into a unified class map', 'pad_schematic_to_sidelength': 'pad a 3D voxel schematic tensor to a target sidelength using PyTorch functional padding'}
```

## File: facebookresearch_craftassist/python/craftassist/voxel_models/semantic_segmentation/semseg_models.py

Prompts

```
['create a SemSegData dataset from a pickle file with configurable sidelength and augmentation options', 'randomly rotate or flip a 3D voxel cube tensor and its labels for data augmentation', 'crop and pad a 3D voxel schematic to fit a fixed sidelength cube with random shifts', 'merge rare and plural semantic classes below a minimum occurrence threshold into a unified class map', 'pad a 3D voxel schematic tensor to a target sidelength using PyTorch functional padding', 'build a 3D convolutional semantic segmentation network for voxel block classification using SemSegNet', 'run the SemSegNet module via CLI with argparse to create a model with custom hidden and embedding dimensions', 'create a SemSegWrapper to load a trained model and segment voxel blocks into semantic object classes', 'test the SemSegWrapper segment_object method to classify 3D voxel blocks and return labeled locations', 'review the SemSegNet forward pass that embeds block IDs and runs them through stacked 3D conv layers', 'run the semantic segmentation training loop with configurable epochs, batch size, and learning rate via CLI args', 'validate a semantic segmentation model on a DataLoader and return per-batch losses and accuracies', 'compute masked NLL loss for semantic segmentation predictions sampling empty voxels with configurable probability', 'calculate classification accuracy by comparing predicted class indices against ground truth labels', 'train one epoch of a semantic segmentation model returning per-batch losses and accuracies']
```

Usage

```
{'build_semsegnet': 'build a 3D convolutional semantic segmentation network for voxel block classification using SemSegNet', 'run_semsegnet_cli': 'run the SemSegNet module via CLI with argparse to create a model with custom hidden and embedding dimensions', 'create_semsegwrapper': 'create a SemSegWrapper to load a trained model and segment voxel blocks into semantic object classes', 'test_segment_object': 'test the SemSegWrapper segment_object method to classify 3D voxel blocks and return labeled locations', 'review_semsegnet_forward': 'review the SemSegNet forward pass that embeds block IDs and runs them through stacked 3D conv layers'}
```

## File: facebookresearch_craftassist/python/craftassist/voxel_models/semantic_segmentation/train_semantic_segmentation.py

Prompts

```
['create a SemSegData dataset from a pickle file with configurable sidelength and augmentation options', 'randomly rotate or flip a 3D voxel cube tensor and its labels for data augmentation', 'crop and pad a 3D voxel schematic to fit a fixed sidelength cube with random shifts', 'merge rare and plural semantic classes below a minimum occurrence threshold into a unified class map', 'pad a 3D voxel schematic tensor to a target sidelength using PyTorch functional padding', 'build a 3D convolutional semantic segmentation network for voxel block classification using SemSegNet', 'run the SemSegNet module via CLI with argparse to create a model with custom hidden and embedding dimensions', 'create a SemSegWrapper to load a trained model and segment voxel blocks into semantic object classes', 'test the SemSegWrapper segment_object method to classify 3D voxel blocks and return labeled locations', 'review the SemSegNet forward pass that embeds block IDs and runs them through stacked 3D conv layers', 'run the semantic segmentation training loop with configurable epochs, batch size, and learning rate via CLI args', 'validate a semantic segmentation model on a DataLoader and return per-batch losses and accuracies', 'compute masked NLL loss for semantic segmentation predictions sampling empty voxels with configurable probability', 'calculate classification accuracy by comparing predicted class indices against ground truth labels', 'train one epoch of a semantic segmentation model returning per-batch losses and accuracies']
```

Usage

```
{'train_semantic_segmentation_model': 'run the semantic segmentation training loop with configurable epochs, batch size, and learning rate via CLI args', 'validate_semseg_model': 'validate a semantic segmentation model on a DataLoader and return per-batch losses and accuracies', 'get_loss': 'compute masked NLL loss for semantic segmentation predictions sampling empty voxels with configurable probability', 'get_accuracy': 'calculate classification accuracy by comparing predicted class indices against ground truth labels', 'train_epoch': 'train one epoch of a semantic segmentation model returning per-batch losses and accuracies'}
```

