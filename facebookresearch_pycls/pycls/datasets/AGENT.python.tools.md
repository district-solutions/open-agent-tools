# Agent Python Tools

- repo: facebookresearch/pycls
- repo_uri: https://github.com/facebookresearch/pycls

## File: facebookresearch_pycls/pycls/datasets/augment.py

Prompts

```
['apply a single augmentation operation like rotate or shear to a PIL image with a given magnitude', 'apply random augmentation to a PIL image using a configurable number of ops and magnitude', 'apply auto augmentation to a PIL image using the predefined AutoAugment policy', 'generate an augmentation function from a parameter string like RandAugment_N2_M0.5', 'visualize all augmentation operations applied at varying magnitudes across a PIL image', 'create an ImageNet dataset instance from a data path and train or val split', 'review the ImageNet _prepare_im method that applies random crop, flip, lighting, and color normalization', 'build the ImageNet image database by scanning class subdirectories and mapping class IDs to contiguous indices', 'create FFCV image and label pipelines with RandomResizedCrop, AutoAugment, or RandAugment for fast data loading', 'test the ImageNet __getitem__ method to verify it returns a prepared image tensor and class label', 'construct a PyTorch training data loader with shuffling and drop_last enabled for cifar10 or imagenet', 'construct a PyTorch test data loader without shuffling for cifar10 or imagenet evaluation', 'shuffle a data loader by setting the epoch on its DistributedSampler for multi-process training', 'construct a standard PyTorch DataLoader for a given dataset name, split, and batch size', 'construct an FFCV-based data loader for fast image loading on imagenet with configurable pipelines', 'scale an image to a target size and extract a centered crop of the specified dimensions', 'perform Inception-style random sized cropping on an image with configurable area fraction and aspect ratio', 'randomly flip an image horizontally with a configurable probability for data augmentation', 'apply a named augmentation strategy to an image using the make_augment factory function', 'apply AlexNet-style PCA color jitter to an image using eigenvalues and eigenvectors']
```

Usage

```
{'apply_single_augment_op': 'apply a single augmentation operation like rotate or shear to a PIL image with a given magnitude', 'rand_augment_image': 'apply random augmentation to a PIL image using a configurable number of ops and magnitude', 'auto_augment_image': 'apply auto augmentation to a PIL image using the predefined AutoAugment policy', 'make_augment_from_string': 'generate an augmentation function from a parameter string like RandAugment_N2_M0.5', 'visualize_augment_ops': 'visualize all augmentation operations applied at varying magnitudes across a PIL image'}
```

## File: facebookresearch_pycls/pycls/datasets/imagenet.py

Prompts

```
['apply a single augmentation operation like rotate or shear to a PIL image with a given magnitude', 'apply random augmentation to a PIL image using a configurable number of ops and magnitude', 'apply auto augmentation to a PIL image using the predefined AutoAugment policy', 'generate an augmentation function from a parameter string like RandAugment_N2_M0.5', 'visualize all augmentation operations applied at varying magnitudes across a PIL image', 'create an ImageNet dataset instance from a data path and train or val split', 'review the ImageNet _prepare_im method that applies random crop, flip, lighting, and color normalization', 'build the ImageNet image database by scanning class subdirectories and mapping class IDs to contiguous indices', 'create FFCV image and label pipelines with RandomResizedCrop, AutoAugment, or RandAugment for fast data loading', 'test the ImageNet __getitem__ method to verify it returns a prepared image tensor and class label', 'construct a PyTorch training data loader with shuffling and drop_last enabled for cifar10 or imagenet', 'construct a PyTorch test data loader without shuffling for cifar10 or imagenet evaluation', 'shuffle a data loader by setting the epoch on its DistributedSampler for multi-process training', 'construct a standard PyTorch DataLoader for a given dataset name, split, and batch size', 'construct an FFCV-based data loader for fast image loading on imagenet with configurable pipelines', 'scale an image to a target size and extract a centered crop of the specified dimensions', 'perform Inception-style random sized cropping on an image with configurable area fraction and aspect ratio', 'randomly flip an image horizontally with a configurable probability for data augmentation', 'apply a named augmentation strategy to an image using the make_augment factory function', 'apply AlexNet-style PCA color jitter to an image using eigenvalues and eigenvectors']
```

Usage

```
{'create_IMAGENET_DATASET': 'create an ImageNet dataset instance from a data path and train or val split', 'review_IMAGENET_prepare_im': 'review the ImageNet _prepare_im method that applies random crop, flip, lighting, and color normalization', 'build_IMAGENET_imdb': 'build the ImageNet image database by scanning class subdirectories and mapping class IDs to contiguous indices', 'create_IMAGENET_FFCV_PIPES': 'create FFCV image and label pipelines with RandomResizedCrop, AutoAugment, or RandAugment for fast data loading', 'test_IMAGENET_getitem': 'test the ImageNet __getitem__ method to verify it returns a prepared image tensor and class label'}
```

## File: facebookresearch_pycls/pycls/datasets/loader.py

Prompts

```
['apply a single augmentation operation like rotate or shear to a PIL image with a given magnitude', 'apply random augmentation to a PIL image using a configurable number of ops and magnitude', 'apply auto augmentation to a PIL image using the predefined AutoAugment policy', 'generate an augmentation function from a parameter string like RandAugment_N2_M0.5', 'visualize all augmentation operations applied at varying magnitudes across a PIL image', 'create an ImageNet dataset instance from a data path and train or val split', 'review the ImageNet _prepare_im method that applies random crop, flip, lighting, and color normalization', 'build the ImageNet image database by scanning class subdirectories and mapping class IDs to contiguous indices', 'create FFCV image and label pipelines with RandomResizedCrop, AutoAugment, or RandAugment for fast data loading', 'test the ImageNet __getitem__ method to verify it returns a prepared image tensor and class label', 'construct a PyTorch training data loader with shuffling and drop_last enabled for cifar10 or imagenet', 'construct a PyTorch test data loader without shuffling for cifar10 or imagenet evaluation', 'shuffle a data loader by setting the epoch on its DistributedSampler for multi-process training', 'construct a standard PyTorch DataLoader for a given dataset name, split, and batch size', 'construct an FFCV-based data loader for fast image loading on imagenet with configurable pipelines', 'scale an image to a target size and extract a centered crop of the specified dimensions', 'perform Inception-style random sized cropping on an image with configurable area fraction and aspect ratio', 'randomly flip an image horizontally with a configurable probability for data augmentation', 'apply a named augmentation strategy to an image using the make_augment factory function', 'apply AlexNet-style PCA color jitter to an image using eigenvalues and eigenvectors']
```

Usage

```
{'construct_train_loader': 'construct a PyTorch training data loader with shuffling and drop_last enabled for cifar10 or imagenet', 'construct_test_loader': 'construct a PyTorch test data loader without shuffling for cifar10 or imagenet evaluation', 'shuffle_loader_epoch': 'shuffle a data loader by setting the epoch on its DistributedSampler for multi-process training', 'construct_loader_standard': 'construct a standard PyTorch DataLoader for a given dataset name, split, and batch size', 'construct_loader_ffcv': 'construct an FFCV-based data loader for fast image loading on imagenet with configurable pipelines'}
```

## File: facebookresearch_pycls/pycls/datasets/transforms.py

Prompts

```
['apply a single augmentation operation like rotate or shear to a PIL image with a given magnitude', 'apply random augmentation to a PIL image using a configurable number of ops and magnitude', 'apply auto augmentation to a PIL image using the predefined AutoAugment policy', 'generate an augmentation function from a parameter string like RandAugment_N2_M0.5', 'visualize all augmentation operations applied at varying magnitudes across a PIL image', 'create an ImageNet dataset instance from a data path and train or val split', 'review the ImageNet _prepare_im method that applies random crop, flip, lighting, and color normalization', 'build the ImageNet image database by scanning class subdirectories and mapping class IDs to contiguous indices', 'create FFCV image and label pipelines with RandomResizedCrop, AutoAugment, or RandAugment for fast data loading', 'test the ImageNet __getitem__ method to verify it returns a prepared image tensor and class label', 'construct a PyTorch training data loader with shuffling and drop_last enabled for cifar10 or imagenet', 'construct a PyTorch test data loader without shuffling for cifar10 or imagenet evaluation', 'shuffle a data loader by setting the epoch on its DistributedSampler for multi-process training', 'construct a standard PyTorch DataLoader for a given dataset name, split, and batch size', 'construct an FFCV-based data loader for fast image loading on imagenet with configurable pipelines', 'scale an image to a target size and extract a centered crop of the specified dimensions', 'perform Inception-style random sized cropping on an image with configurable area fraction and aspect ratio', 'randomly flip an image horizontally with a configurable probability for data augmentation', 'apply a named augmentation strategy to an image using the make_augment factory function', 'apply AlexNet-style PCA color jitter to an image using eigenvalues and eigenvectors']
```

Usage

```
{'scale_and_center_crop': 'scale an image to a target size and extract a centered crop of the specified dimensions', 'random_sized_crop': 'perform Inception-style random sized cropping on an image with configurable area fraction and aspect ratio', 'horizontal_flip': 'randomly flip an image horizontally with a configurable probability for data augmentation', 'augment': 'apply a named augmentation strategy to an image using the make_augment factory function', 'lighting': 'apply AlexNet-style PCA color jitter to an image using eigenvalues and eigenvectors'}
```

