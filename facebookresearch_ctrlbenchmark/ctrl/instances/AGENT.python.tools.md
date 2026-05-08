# Agent Python Tools

- repo: facebookresearch/ctrlbenchmark
- repo_uri: https://github.com/facebookresearch/ctrlbenchmark

## File: facebookresearch_ctrlbenchmark/ctrl/instances/DTD.py

Prompts

```
['download the DTD dataset from the Oxford VGG URL and save to a specified root directory', 'extract the DTD tar.gz archive to its parent directory using the untar function', 'apply a center crop to a PIL image to resize it to a specified width and height tuple', 'prepare the DTD dataset by loading images, resizing, center cropping, and saving as a PyTorch tensor file', 'instantiate the DTD VisionDataset class with a root path, split, image size, and optional transforms', 'build an ImageDatasetTree for cifar10 with a specified image size and validation split ratio', 'create an ImageConcept with train and test samples and a random state for splitting', 'build a concept tree from a taxonomy by loading dataset samples and creating ComposedConcept nodes', 'format a torchvision dataset into unified tensor samples and targets with consistent shape and size', 'plot leaf concept images as grids using torchvision utils and a visdom visualization object', 'build a MultiDomainDatasetTree by passing child concept trees as keyword arguments', 'build the concept tree by composing child trees under a ComposedConcept root node', 'format a torchvision dataset into torch tensors with proper channel dimensions', 'get train and test samples for a given concept by class index', 'plot leaf concept images as grids using a visdom visualization object']
```

Usage

```
{'download_dtd_dataset': 'download the DTD dataset from the Oxford VGG URL and save to a specified root directory', 'untar_dtd_archive': 'extract the DTD tar.gz archive to its parent directory using the untar function', 'center_crop_image': 'apply a center crop to a PIL image to resize it to a specified width and height tuple', 'prepare_dtd_dataset': 'prepare the DTD dataset by loading images, resizing, center cropping, and saving as a PyTorch tensor file', 'load_dtd_vision_dataset': 'instantiate the DTD VisionDataset class with a root path, split, image size, and optional transforms'}
```

## File: facebookresearch_ctrlbenchmark/ctrl/instances/image_dataset_tree.py

Prompts

```
['download the DTD dataset from the Oxford VGG URL and save to a specified root directory', 'extract the DTD tar.gz archive to its parent directory using the untar function', 'apply a center crop to a PIL image to resize it to a specified width and height tuple', 'prepare the DTD dataset by loading images, resizing, center cropping, and saving as a PyTorch tensor file', 'instantiate the DTD VisionDataset class with a root path, split, image size, and optional transforms', 'build an ImageDatasetTree for cifar10 with a specified image size and validation split ratio', 'create an ImageConcept with train and test samples and a random state for splitting', 'build a concept tree from a taxonomy by loading dataset samples and creating ComposedConcept nodes', 'format a torchvision dataset into unified tensor samples and targets with consistent shape and size', 'plot leaf concept images as grids using torchvision utils and a visdom visualization object', 'build a MultiDomainDatasetTree by passing child concept trees as keyword arguments', 'build the concept tree by composing child trees under a ComposedConcept root node', 'format a torchvision dataset into torch tensors with proper channel dimensions', 'get train and test samples for a given concept by class index', 'plot leaf concept images as grids using a visdom visualization object']
```

Usage

```
{'build_ImageDatasetTree': 'build an ImageDatasetTree for cifar10 with a specified image size and validation split ratio', 'create_ImageConcept': 'create an ImageConcept with train and test samples and a random state for splitting', 'build_concept_tree': 'build a concept tree from a taxonomy by loading dataset samples and creating ComposedConcept nodes', 'format_dataset_samples': 'format a torchvision dataset into unified tensor samples and targets with consistent shape and size', 'plot_leaf_concepts': 'plot leaf concept images as grids using torchvision utils and a visdom visualization object'}
```

## File: facebookresearch_ctrlbenchmark/ctrl/instances/md_tree.py

Prompts

```
['download the DTD dataset from the Oxford VGG URL and save to a specified root directory', 'extract the DTD tar.gz archive to its parent directory using the untar function', 'apply a center crop to a PIL image to resize it to a specified width and height tuple', 'prepare the DTD dataset by loading images, resizing, center cropping, and saving as a PyTorch tensor file', 'instantiate the DTD VisionDataset class with a root path, split, image size, and optional transforms', 'build an ImageDatasetTree for cifar10 with a specified image size and validation split ratio', 'create an ImageConcept with train and test samples and a random state for splitting', 'build a concept tree from a taxonomy by loading dataset samples and creating ComposedConcept nodes', 'format a torchvision dataset into unified tensor samples and targets with consistent shape and size', 'plot leaf concept images as grids using torchvision utils and a visdom visualization object', 'build a MultiDomainDatasetTree by passing child concept trees as keyword arguments', 'build the concept tree by composing child trees under a ComposedConcept root node', 'format a torchvision dataset into torch tensors with proper channel dimensions', 'get train and test samples for a given concept by class index', 'plot leaf concept images as grids using a visdom visualization object']
```

Usage

```
{'build_MultiDomainDatasetTree': 'build a MultiDomainDatasetTree by passing child concept trees as keyword arguments', 'build_tree_MultiDomainDatasetTree': 'build the concept tree by composing child trees under a ComposedConcept root node', 'format_dataset_MultiDomainDatasetTree': 'format a torchvision dataset into torch tensors with proper channel dimensions', 'get_samples_MultiDomainDatasetTree': 'get train and test samples for a given concept by class index', 'plot_concepts_MultiDomainDatasetTree': 'plot leaf concept images as grids using a visdom visualization object'}
```

