# Agent Python Tools

- repo: facebookresearch/openlth
- repo_uri: https://github.com/facebookresearch/open_lth

## File: facebookresearch_openlth/datasets/test/test_cifar10.py

Prompts

```
['get the CIFAR-10 test dataset using cifar10.Dataset.get_test_set()', 'get the CIFAR-10 training dataset with or without augmentation using cifar10.Dataset.get_train_set()', 'get the number of CIFAR-10 classes using cifar10.Dataset.num_classes()', 'randomize a fraction of dataset labels using dataset.randomize_labels(seed, fraction)', 'subsample the dataset to a fraction of its size using dataset.subsample(seed, fraction)', 'test the ImageDataset and DataLoader classes for CIFAR-10 training set loading and iteration', 'run the test to verify CIFAR-10 data loading with and without augmentation and blur', 'run the test to verify DataLoader shuffling produces deterministic label order per seed', 'run the test to verify blur augmentation preserves dataset size and original labels', 'run the test to verify unsupervised rotation transforms labels into 4 rotation classes', 'test the mnist Dataset class to verify num_classes, num_train_examples, and num_test_examples return correct values', 'test the mnist Dataset randomize_labels method to verify partial and full label randomization with a given seed', 'test the mnist Dataset subsample method to verify it reduces dataset size by the specified fraction with a given seed', 'test that calling subsample twice on the same mnist Dataset instance raises a ValueError', 'test that mnist Dataset get_test_set and get_train_set return non-None dataset objects', 'test the registry.get function to retrieve a CIFAR-10 DataLoader for training or evaluation', 'test the registry.get function with do_not_augment set to True to skip data augmentation', 'test the registry.get function with subsample_fraction to load a subset of the dataset', 'test the registry.get function with random_labels_fraction to corrupt all labels with random noise', 'test the registry.get function with unsupervised_labels set to rotation for self-supervised learning']
```

Usage

```
{'get_test_set': 'get the CIFAR-10 test dataset using cifar10.Dataset.get_test_set()', 'get_train_set': 'get the CIFAR-10 training dataset with or without augmentation using cifar10.Dataset.get_train_set()', 'num_classes': 'get the number of CIFAR-10 classes using cifar10.Dataset.num_classes()', 'randomize_labels': 'randomize a fraction of dataset labels using dataset.randomize_labels(seed, fraction)', 'subsample': 'subsample the dataset to a fraction of its size using dataset.subsample(seed, fraction)'}
```

## File: facebookresearch_openlth/datasets/test/test_imagedataset_and_dataloader.py

Prompts

```
['get the CIFAR-10 test dataset using cifar10.Dataset.get_test_set()', 'get the CIFAR-10 training dataset with or without augmentation using cifar10.Dataset.get_train_set()', 'get the number of CIFAR-10 classes using cifar10.Dataset.num_classes()', 'randomize a fraction of dataset labels using dataset.randomize_labels(seed, fraction)', 'subsample the dataset to a fraction of its size using dataset.subsample(seed, fraction)', 'test the ImageDataset and DataLoader classes for CIFAR-10 training set loading and iteration', 'run the test to verify CIFAR-10 data loading with and without augmentation and blur', 'run the test to verify DataLoader shuffling produces deterministic label order per seed', 'run the test to verify blur augmentation preserves dataset size and original labels', 'run the test to verify unsupervised rotation transforms labels into 4 rotation classes', 'test the mnist Dataset class to verify num_classes, num_train_examples, and num_test_examples return correct values', 'test the mnist Dataset randomize_labels method to verify partial and full label randomization with a given seed', 'test the mnist Dataset subsample method to verify it reduces dataset size by the specified fraction with a given seed', 'test that calling subsample twice on the same mnist Dataset instance raises a ValueError', 'test that mnist Dataset get_test_set and get_train_set return non-None dataset objects', 'test the registry.get function to retrieve a CIFAR-10 DataLoader for training or evaluation', 'test the registry.get function with do_not_augment set to True to skip data augmentation', 'test the registry.get function with subsample_fraction to load a subset of the dataset', 'test the registry.get function with random_labels_fraction to corrupt all labels with random noise', 'test the registry.get function with unsupervised_labels set to rotation for self-supervised learning']
```

Usage

```
{'test_ImageDataset_and_DataLoader': 'test the ImageDataset and DataLoader classes for CIFAR-10 training set loading and iteration', 'run_test_data_loading': 'run the test to verify CIFAR-10 data loading with and without augmentation and blur', 'run_test_shuffling_dataloader': 'run the test to verify DataLoader shuffling produces deterministic label order per seed', 'run_test_blur_augmentation': 'run the test to verify blur augmentation preserves dataset size and original labels', 'run_test_unsupervised_rotation': 'run the test to verify unsupervised rotation transforms labels into 4 rotation classes'}
```

## File: facebookresearch_openlth/datasets/test/test_mnist.py

Prompts

```
['get the CIFAR-10 test dataset using cifar10.Dataset.get_test_set()', 'get the CIFAR-10 training dataset with or without augmentation using cifar10.Dataset.get_train_set()', 'get the number of CIFAR-10 classes using cifar10.Dataset.num_classes()', 'randomize a fraction of dataset labels using dataset.randomize_labels(seed, fraction)', 'subsample the dataset to a fraction of its size using dataset.subsample(seed, fraction)', 'test the ImageDataset and DataLoader classes for CIFAR-10 training set loading and iteration', 'run the test to verify CIFAR-10 data loading with and without augmentation and blur', 'run the test to verify DataLoader shuffling produces deterministic label order per seed', 'run the test to verify blur augmentation preserves dataset size and original labels', 'run the test to verify unsupervised rotation transforms labels into 4 rotation classes', 'test the mnist Dataset class to verify num_classes, num_train_examples, and num_test_examples return correct values', 'test the mnist Dataset randomize_labels method to verify partial and full label randomization with a given seed', 'test the mnist Dataset subsample method to verify it reduces dataset size by the specified fraction with a given seed', 'test that calling subsample twice on the same mnist Dataset instance raises a ValueError', 'test that mnist Dataset get_test_set and get_train_set return non-None dataset objects', 'test the registry.get function to retrieve a CIFAR-10 DataLoader for training or evaluation', 'test the registry.get function with do_not_augment set to True to skip data augmentation', 'test the registry.get function with subsample_fraction to load a subset of the dataset', 'test the registry.get function with random_labels_fraction to corrupt all labels with random noise', 'test the registry.get function with unsupervised_labels set to rotation for self-supervised learning']
```

Usage

```
{'test_mnist_dataset_sizes': 'test the mnist Dataset class to verify num_classes, num_train_examples, and num_test_examples return correct values', 'test_mnist_randomize_labels': 'test the mnist Dataset randomize_labels method to verify partial and full label randomization with a given seed', 'test_mnist_subsample': 'test the mnist Dataset subsample method to verify it reduces dataset size by the specified fraction with a given seed', 'test_mnist_subsample_twice_error': 'test that calling subsample twice on the same mnist Dataset instance raises a ValueError', 'test_mnist_get_sets': 'test that mnist Dataset get_test_set and get_train_set return non-None dataset objects'}
```

## File: facebookresearch_openlth/datasets/test/test_registry.py

Prompts

```
['get the CIFAR-10 test dataset using cifar10.Dataset.get_test_set()', 'get the CIFAR-10 training dataset with or without augmentation using cifar10.Dataset.get_train_set()', 'get the number of CIFAR-10 classes using cifar10.Dataset.num_classes()', 'randomize a fraction of dataset labels using dataset.randomize_labels(seed, fraction)', 'subsample the dataset to a fraction of its size using dataset.subsample(seed, fraction)', 'test the ImageDataset and DataLoader classes for CIFAR-10 training set loading and iteration', 'run the test to verify CIFAR-10 data loading with and without augmentation and blur', 'run the test to verify DataLoader shuffling produces deterministic label order per seed', 'run the test to verify blur augmentation preserves dataset size and original labels', 'run the test to verify unsupervised rotation transforms labels into 4 rotation classes', 'test the mnist Dataset class to verify num_classes, num_train_examples, and num_test_examples return correct values', 'test the mnist Dataset randomize_labels method to verify partial and full label randomization with a given seed', 'test the mnist Dataset subsample method to verify it reduces dataset size by the specified fraction with a given seed', 'test that calling subsample twice on the same mnist Dataset instance raises a ValueError', 'test that mnist Dataset get_test_set and get_train_set return non-None dataset objects', 'test the registry.get function to retrieve a CIFAR-10 DataLoader for training or evaluation', 'test the registry.get function with do_not_augment set to True to skip data augmentation', 'test the registry.get function with subsample_fraction to load a subset of the dataset', 'test the registry.get function with random_labels_fraction to corrupt all labels with random noise', 'test the registry.get function with unsupervised_labels set to rotation for self-supervised learning']
```

Usage

```
{'test_registry_get_dataloader': 'test the registry.get function to retrieve a CIFAR-10 DataLoader for training or evaluation', 'test_registry_no_augmentation': 'test the registry.get function with do_not_augment set to True to skip data augmentation', 'test_registry_subsample': 'test the registry.get function with subsample_fraction to load a subset of the dataset', 'test_registry_random_labels': 'test the registry.get function with random_labels_fraction to corrupt all labels with random noise', 'test_registry_unsupervised_labels': 'test the registry.get function with unsupervised_labels set to rotation for self-supervised learning'}
```

