# Agent Python Tools

- repo: facebookresearch/adversarial-continual-learning
- repo_uri: https://github.com/facebookresearch/adversarial-continual-learning

## File: facebookresearch_adversarial-continual-learning/ACL-resnet/src/dataloaders/cifar100.py

Prompts

```
['create an iCIFAR10 dataset with specified classes, memory, and task number for incremental learning', 'create an iCIFAR100 dataset subclass with CIFAR-100 specific URLs and metadata for continual learning', 'create a DatasetGen instance to manage CIFAR100 dataloaders split across incremental learning tasks', 'get train, validation, and test dataloaders for a specific task ID from DatasetGen', 'update the task memory buffer by sampling images from the current task training split', 'create a CIFAR10_ dataset instance with task_num and num_samples_per_class for continual learning', 'create a CIFAR100_ dataset instance subclassing CIFAR10_ with 100 classes for continual learning', 'create a SVHN_ dataset instance that loads Stanford house number images with task annotations', 'create a MNIST_RGB dataset instance that converts grayscale MNIST images to RGB format', 'create a notMNIST_ dataset instance that downloads and loads notMNIST images from A-J folders', 'create a MiniImageNet dataset from a pickle file at the given root directory for training or testing', 'create an iMiniImageNet incremental dataset with class filtering, memory replay, and task labels for continual learning', 'get train, validation, test, and t-SNE dataloaders for a specific task ID from the DatasetGen', 'download a file from a URL to a local directory with optional MD5 checksum verification', 'extract a tar, tar.gz, gzip, or zip archive to a specified directory', 'download a file from a URL and extract the archive to a target directory', 'calculate the MD5 checksum of a file for integrity verification', 'read a SN3 Pascal Vincent format tensor file and return a PyTorch tensor']
```

Usage

```
{'create_iCIFAR10_dataset': 'create an iCIFAR10 dataset with specified classes, memory, and task number for incremental learning', 'create_iCIFAR100_dataset': 'create an iCIFAR100 dataset subclass with CIFAR-100 specific URLs and metadata for continual learning', 'create_DatasetGen': 'create a DatasetGen instance to manage CIFAR100 dataloaders split across incremental learning tasks', 'get_task_dataloaders': 'get train, validation, and test dataloaders for a specific task ID from DatasetGen', 'update_task_memory': 'update the task memory buffer by sampling images from the current task training split'}
```

## File: facebookresearch_adversarial-continual-learning/ACL-resnet/src/dataloaders/datasets_utils.py

Prompts

```
['create an iCIFAR10 dataset with specified classes, memory, and task number for incremental learning', 'create an iCIFAR100 dataset subclass with CIFAR-100 specific URLs and metadata for continual learning', 'create a DatasetGen instance to manage CIFAR100 dataloaders split across incremental learning tasks', 'get train, validation, and test dataloaders for a specific task ID from DatasetGen', 'update the task memory buffer by sampling images from the current task training split', 'create a CIFAR10_ dataset instance with task_num and num_samples_per_class for continual learning', 'create a CIFAR100_ dataset instance subclassing CIFAR10_ with 100 classes for continual learning', 'create a SVHN_ dataset instance that loads Stanford house number images with task annotations', 'create a MNIST_RGB dataset instance that converts grayscale MNIST images to RGB format', 'create a notMNIST_ dataset instance that downloads and loads notMNIST images from A-J folders', 'create a MiniImageNet dataset from a pickle file at the given root directory for training or testing', 'create an iMiniImageNet incremental dataset with class filtering, memory replay, and task labels for continual learning', 'get train, validation, test, and t-SNE dataloaders for a specific task ID from the DatasetGen', 'download a file from a URL to a local directory with optional MD5 checksum verification', 'extract a tar, tar.gz, gzip, or zip archive to a specified directory', 'download a file from a URL and extract the archive to a target directory', 'calculate the MD5 checksum of a file for integrity verification', 'read a SN3 Pascal Vincent format tensor file and return a PyTorch tensor']
```

Usage

```
{'create_CIFAR10_dataset': 'create a CIFAR10_ dataset instance with task_num and num_samples_per_class for continual learning', 'create_CIFAR100_dataset': 'create a CIFAR100_ dataset instance subclassing CIFAR10_ with 100 classes for continual learning', 'create_SVHN_dataset': 'create a SVHN_ dataset instance that loads Stanford house number images with task annotations', 'create_MNIST_RGB_dataset': 'create a MNIST_RGB dataset instance that converts grayscale MNIST images to RGB format', 'create_notMNIST_dataset': 'create a notMNIST_ dataset instance that downloads and loads notMNIST images from A-J folders'}
```

## File: facebookresearch_adversarial-continual-learning/ACL-resnet/src/dataloaders/miniimagenet.py

Prompts

```
['create an iCIFAR10 dataset with specified classes, memory, and task number for incremental learning', 'create an iCIFAR100 dataset subclass with CIFAR-100 specific URLs and metadata for continual learning', 'create a DatasetGen instance to manage CIFAR100 dataloaders split across incremental learning tasks', 'get train, validation, and test dataloaders for a specific task ID from DatasetGen', 'update the task memory buffer by sampling images from the current task training split', 'create a CIFAR10_ dataset instance with task_num and num_samples_per_class for continual learning', 'create a CIFAR100_ dataset instance subclassing CIFAR10_ with 100 classes for continual learning', 'create a SVHN_ dataset instance that loads Stanford house number images with task annotations', 'create a MNIST_RGB dataset instance that converts grayscale MNIST images to RGB format', 'create a notMNIST_ dataset instance that downloads and loads notMNIST images from A-J folders', 'create a MiniImageNet dataset from a pickle file at the given root directory for training or testing', 'create an iMiniImageNet incremental dataset with class filtering, memory replay, and task labels for continual learning', 'get train, validation, test, and t-SNE dataloaders for a specific task ID from the DatasetGen', 'download a file from a URL to a local directory with optional MD5 checksum verification', 'extract a tar, tar.gz, gzip, or zip archive to a specified directory', 'download a file from a URL and extract the archive to a target directory', 'calculate the MD5 checksum of a file for integrity verification', 'read a SN3 Pascal Vincent format tensor file and return a PyTorch tensor']
```

Usage

```
{'create_MiniImageNet_dataset': 'create a MiniImageNet dataset from a pickle file at the given root directory for training or testing', 'create_iMiniImageNet_dataset': 'create an iMiniImageNet incremental dataset with class filtering, memory replay, and task labels for continual learning', 'create_DatasetGen': 'create a DatasetGen instance that manages task splits, dataloaders, and memory for incremental MiniImageNet continual learning', 'get_dataloaders_for_task': 'get train, validation, test, and t-SNE dataloaders for a specific task ID from the DatasetGen', 'update_task_memory': 'update the replay memory buffer by randomly sampling images from the current task training split'}
```

## File: facebookresearch_adversarial-continual-learning/ACL-resnet/src/dataloaders/utils.py

Prompts

```
['create an iCIFAR10 dataset with specified classes, memory, and task number for incremental learning', 'create an iCIFAR100 dataset subclass with CIFAR-100 specific URLs and metadata for continual learning', 'create a DatasetGen instance to manage CIFAR100 dataloaders split across incremental learning tasks', 'get train, validation, and test dataloaders for a specific task ID from DatasetGen', 'update the task memory buffer by sampling images from the current task training split', 'create a CIFAR10_ dataset instance with task_num and num_samples_per_class for continual learning', 'create a CIFAR100_ dataset instance subclassing CIFAR10_ with 100 classes for continual learning', 'create a SVHN_ dataset instance that loads Stanford house number images with task annotations', 'create a MNIST_RGB dataset instance that converts grayscale MNIST images to RGB format', 'create a notMNIST_ dataset instance that downloads and loads notMNIST images from A-J folders', 'create a MiniImageNet dataset from a pickle file at the given root directory for training or testing', 'create an iMiniImageNet incremental dataset with class filtering, memory replay, and task labels for continual learning', 'get train, validation, test, and t-SNE dataloaders for a specific task ID from the DatasetGen', 'download a file from a URL to a local directory with optional MD5 checksum verification', 'extract a tar, tar.gz, gzip, or zip archive to a specified directory', 'download a file from a URL and extract the archive to a target directory', 'calculate the MD5 checksum of a file for integrity verification', 'read a SN3 Pascal Vincent format tensor file and return a PyTorch tensor']
```

Usage

```
{'download_url': 'download a file from a URL to a local directory with optional MD5 checksum verification', 'extract_archive': 'extract a tar, tar.gz, gzip, or zip archive to a specified directory', 'download_and_extract_archive': 'download a file from a URL and extract the archive to a target directory', 'calculate_md5': 'calculate the MD5 checksum of a file for integrity verification', 'read_sn3_pascalvincent_tensor': 'read a SN3 Pascal Vincent format tensor file and return a PyTorch tensor'}
```

