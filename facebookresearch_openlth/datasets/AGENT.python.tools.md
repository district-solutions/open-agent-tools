# Agent Python Tools

- repo: facebookresearch/openlth
- repo_uri: https://github.com/facebookresearch/open_lth

## File: facebookresearch_openlth/datasets/base.py

Prompts

```
['create a subclass of Dataset that implements num_classes, get_train_set, and get_test_set abstract methods', 'randomize a fraction of dataset labels using Dataset.randomize_labels with a seed and fraction', 'subsample a dataset to a fraction of its size using Dataset.subsample with a seed and fraction', 'create an ImageDataset subclass with image and tensor transforms for loading and transforming image examples', 'build a DataLoader with custom shuffle logic that supports both single and distributed training modes', 'get the CIFAR-10 training dataset with optional data augmentation transforms', 'get the CIFAR-10 test dataset for evaluation', 'get the number of classes in the CIFAR-10 dataset', 'get the number of training examples in the CIFAR-10 dataset', 'get the number of test examples in the CIFAR-10 dataset', 'build an ImageNet training dataset with optional augmentation transforms using Dataset.get_train_set', 'build an ImageNet test dataset with standard transforms using Dataset.get_test_set', 'create a data augmentation pipeline with random resized crop and horizontal flip via _augment_transforms', 'create standard image transforms with resize and center crop via _transforms', 'load an image file from a path and convert it to RGB using example_to_image', 'convert an MNIST example tensor to a PIL grayscale image using example_to_image()', 'get a training or test data loader for cifar10, mnist, or imagenet using DatasetHparams', 'get a training dataset loader with augmentation enabled based on DatasetHparams settings', 'calculate the number of iterations per training epoch given DatasetHparams and batch size', 'access the dictionary of registered datasets including cifar10, mnist, and imagenet modules']
```

Usage

```
{'create_dataset_subclass': 'create a subclass of Dataset that implements num_classes, get_train_set, and get_test_set abstract methods', 'randomize_dataset_labels': 'randomize a fraction of dataset labels using Dataset.randomize_labels with a seed and fraction', 'subsample_dataset': 'subsample a dataset to a fraction of its size using Dataset.subsample with a seed and fraction', 'create_imagedataset_with_transforms': 'create an ImageDataset subclass with image and tensor transforms for loading and transforming image examples', 'build_dataloader_with_shuffle': 'build a DataLoader with custom shuffle logic that supports both single and distributed training modes'}
```

## File: facebookresearch_openlth/datasets/cifar10.py

Prompts

```
['create a subclass of Dataset that implements num_classes, get_train_set, and get_test_set abstract methods', 'randomize a fraction of dataset labels using Dataset.randomize_labels with a seed and fraction', 'subsample a dataset to a fraction of its size using Dataset.subsample with a seed and fraction', 'create an ImageDataset subclass with image and tensor transforms for loading and transforming image examples', 'build a DataLoader with custom shuffle logic that supports both single and distributed training modes', 'get the CIFAR-10 training dataset with optional data augmentation transforms', 'get the CIFAR-10 test dataset for evaluation', 'get the number of classes in the CIFAR-10 dataset', 'get the number of training examples in the CIFAR-10 dataset', 'get the number of test examples in the CIFAR-10 dataset', 'build an ImageNet training dataset with optional augmentation transforms using Dataset.get_train_set', 'build an ImageNet test dataset with standard transforms using Dataset.get_test_set', 'create a data augmentation pipeline with random resized crop and horizontal flip via _augment_transforms', 'create standard image transforms with resize and center crop via _transforms', 'load an image file from a path and convert it to RGB using example_to_image', 'convert an MNIST example tensor to a PIL grayscale image using example_to_image()', 'get a training or test data loader for cifar10, mnist, or imagenet using DatasetHparams', 'get a training dataset loader with augmentation enabled based on DatasetHparams settings', 'calculate the number of iterations per training epoch given DatasetHparams and batch size', 'access the dictionary of registered datasets including cifar10, mnist, and imagenet modules']
```

Usage

```
{'get_train_set': 'get the CIFAR-10 training dataset with optional data augmentation transforms', 'get_test_set': 'get the CIFAR-10 test dataset for evaluation', 'num_classes': 'get the number of classes in the CIFAR-10 dataset', 'num_train_examples': 'get the number of training examples in the CIFAR-10 dataset', 'num_test_examples': 'get the number of test examples in the CIFAR-10 dataset'}
```

## File: facebookresearch_openlth/datasets/imagenet.py

Prompts

```
['create a subclass of Dataset that implements num_classes, get_train_set, and get_test_set abstract methods', 'randomize a fraction of dataset labels using Dataset.randomize_labels with a seed and fraction', 'subsample a dataset to a fraction of its size using Dataset.subsample with a seed and fraction', 'create an ImageDataset subclass with image and tensor transforms for loading and transforming image examples', 'build a DataLoader with custom shuffle logic that supports both single and distributed training modes', 'get the CIFAR-10 training dataset with optional data augmentation transforms', 'get the CIFAR-10 test dataset for evaluation', 'get the number of classes in the CIFAR-10 dataset', 'get the number of training examples in the CIFAR-10 dataset', 'get the number of test examples in the CIFAR-10 dataset', 'build an ImageNet training dataset with optional augmentation transforms using Dataset.get_train_set', 'build an ImageNet test dataset with standard transforms using Dataset.get_test_set', 'create a data augmentation pipeline with random resized crop and horizontal flip via _augment_transforms', 'create standard image transforms with resize and center crop via _transforms', 'load an image file from a path and convert it to RGB using example_to_image', 'convert an MNIST example tensor to a PIL grayscale image using example_to_image()', 'get a training or test data loader for cifar10, mnist, or imagenet using DatasetHparams', 'get a training dataset loader with augmentation enabled based on DatasetHparams settings', 'calculate the number of iterations per training epoch given DatasetHparams and batch size', 'access the dictionary of registered datasets including cifar10, mnist, and imagenet modules']
```

Usage

```
{'build_imagenet_train_dataset': 'build an ImageNet training dataset with optional augmentation transforms using Dataset.get_train_set', 'build_imagenet_test_dataset': 'build an ImageNet test dataset with standard transforms using Dataset.get_test_set', 'create_augmentation_pipeline': 'create a data augmentation pipeline with random resized crop and horizontal flip via _augment_transforms', 'create_standard_transforms': 'create standard image transforms with resize and center crop via _transforms', 'load_image_from_path': 'load an image file from a path and convert it to RGB using example_to_image'}
```

## File: facebookresearch_openlth/datasets/mnist.py

Prompts

```
['create a subclass of Dataset that implements num_classes, get_train_set, and get_test_set abstract methods', 'randomize a fraction of dataset labels using Dataset.randomize_labels with a seed and fraction', 'subsample a dataset to a fraction of its size using Dataset.subsample with a seed and fraction', 'create an ImageDataset subclass with image and tensor transforms for loading and transforming image examples', 'build a DataLoader with custom shuffle logic that supports both single and distributed training modes', 'get the CIFAR-10 training dataset with optional data augmentation transforms', 'get the CIFAR-10 test dataset for evaluation', 'get the number of classes in the CIFAR-10 dataset', 'get the number of training examples in the CIFAR-10 dataset', 'get the number of test examples in the CIFAR-10 dataset', 'build an ImageNet training dataset with optional augmentation transforms using Dataset.get_train_set', 'build an ImageNet test dataset with standard transforms using Dataset.get_test_set', 'create a data augmentation pipeline with random resized crop and horizontal flip via _augment_transforms', 'create standard image transforms with resize and center crop via _transforms', 'load an image file from a path and convert it to RGB using example_to_image', 'convert an MNIST example tensor to a PIL grayscale image using example_to_image()', 'get a training or test data loader for cifar10, mnist, or imagenet using DatasetHparams', 'get a training dataset loader with augmentation enabled based on DatasetHparams settings', 'calculate the number of iterations per training epoch given DatasetHparams and batch size', 'access the dictionary of registered datasets including cifar10, mnist, and imagenet modules']
```

Usage

```
{'get_train_set': 'get the MNIST training dataset with 60000 examples using Dataset.get_train_set()', 'get_test_set': 'get the MNIST test dataset with 10000 examples using Dataset.get_test_set()', 'num_train_examples': 'get the number of MNIST training examples using Dataset.num_train_examples()', 'num_test_examples': 'get the number of MNIST test examples using Dataset.num_test_examples()', 'example_to_image': 'convert an MNIST example tensor to a PIL grayscale image using example_to_image()'}
```

## File: facebookresearch_openlth/datasets/registry.py

Prompts

```
['create a subclass of Dataset that implements num_classes, get_train_set, and get_test_set abstract methods', 'randomize a fraction of dataset labels using Dataset.randomize_labels with a seed and fraction', 'subsample a dataset to a fraction of its size using Dataset.subsample with a seed and fraction', 'create an ImageDataset subclass with image and tensor transforms for loading and transforming image examples', 'build a DataLoader with custom shuffle logic that supports both single and distributed training modes', 'get the CIFAR-10 training dataset with optional data augmentation transforms', 'get the CIFAR-10 test dataset for evaluation', 'get the number of classes in the CIFAR-10 dataset', 'get the number of training examples in the CIFAR-10 dataset', 'get the number of test examples in the CIFAR-10 dataset', 'build an ImageNet training dataset with optional augmentation transforms using Dataset.get_train_set', 'build an ImageNet test dataset with standard transforms using Dataset.get_test_set', 'create a data augmentation pipeline with random resized crop and horizontal flip via _augment_transforms', 'create standard image transforms with resize and center crop via _transforms', 'load an image file from a path and convert it to RGB using example_to_image', 'convert an MNIST example tensor to a PIL grayscale image using example_to_image()', 'get a training or test data loader for cifar10, mnist, or imagenet using DatasetHparams', 'get a training dataset loader with augmentation enabled based on DatasetHparams settings', 'calculate the number of iterations per training epoch given DatasetHparams and batch size', 'access the dictionary of registered datasets including cifar10, mnist, and imagenet modules']
```

Usage

```
{'get_dataset_loader': 'get a training or test data loader for cifar10, mnist, or imagenet using DatasetHparams', 'get_dataset_with_augmentation': 'get a training dataset loader with augmentation enabled based on DatasetHparams settings', 'iterations_per_epoch': 'calculate the number of iterations per training epoch given DatasetHparams and batch size', 'num_classes': 'get the number of classes for a registered dataset or 4 for unsupervised rotation', 'registered_datasets': 'access the dictionary of registered datasets including cifar10, mnist, and imagenet modules'}
```

