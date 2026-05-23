# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pretrain/mmpretrain/models/utils/batch_augments/cutmix.py

Prompts

```
['build a python module that applies CutMix batch augmentation to a batch of images and labels', 'create a CutMix instance with alpha parameter and optional cutmix_minmax bounds for data augmentation', 'test the rand_bbox_minmax method to generate random rectangular bounding boxes within min/max area ratios', 'test the rand_bbox method to generate random square bounding boxes based on a lambda value', 'test the mix method that cuts and pastes patches among training images and mixes labels proportionally', 'build a python module to apply mixup batch augmentation on image tensors and one-hot labels', 'create a Mixup instance with a beta distribution alpha parameter for mixing ratios', 'test the Mixup mix method to blend batch inputs and one-hot scores with a random lambda', 'test the Mixup call method to mix batch inputs and validate one-hot tensor shape', 'review the Mixup class and its mix method for batch augmentation of image data', 'build a ResizeMix data augmentation module that resizes and pastes image patches onto other images in a batch', 'create a ResizeMix instance with alpha, lam_min, and lam_max parameters for image mixing ratio control', 'test the ResizeMix mix method to verify it returns mixed image tensors and interpolated label scores', 'review the ResizeMix class that extends CutMix for random paste data augmentation with preserved object information', 'refactor the ResizeMix mix method to support configurable interpolation modes like bilinear or bicubic']
```

Usage

```
{'build_cutmix_augmentation': 'build a python module that applies CutMix batch augmentation to a batch of images and labels', 'create_cutmix_instance': 'create a CutMix instance with alpha parameter and optional cutmix_minmax bounds for data augmentation', 'test_rand_bbox_minmax': 'test the rand_bbox_minmax method to generate random rectangular bounding boxes within min/max area ratios', 'test_rand_bbox': 'test the rand_bbox method to generate random square bounding boxes based on a lambda value', 'test_mix': 'test the mix method that cuts and pastes patches among training images and mixes labels proportionally'}
```

## File: facebookresearch_sapiens/pretrain/mmpretrain/models/utils/batch_augments/mixup.py

Prompts

```
['build a python module that applies CutMix batch augmentation to a batch of images and labels', 'create a CutMix instance with alpha parameter and optional cutmix_minmax bounds for data augmentation', 'test the rand_bbox_minmax method to generate random rectangular bounding boxes within min/max area ratios', 'test the rand_bbox method to generate random square bounding boxes based on a lambda value', 'test the mix method that cuts and pastes patches among training images and mixes labels proportionally', 'build a python module to apply mixup batch augmentation on image tensors and one-hot labels', 'create a Mixup instance with a beta distribution alpha parameter for mixing ratios', 'test the Mixup mix method to blend batch inputs and one-hot scores with a random lambda', 'test the Mixup call method to mix batch inputs and validate one-hot tensor shape', 'review the Mixup class and its mix method for batch augmentation of image data', 'build a ResizeMix data augmentation module that resizes and pastes image patches onto other images in a batch', 'create a ResizeMix instance with alpha, lam_min, and lam_max parameters for image mixing ratio control', 'test the ResizeMix mix method to verify it returns mixed image tensors and interpolated label scores', 'review the ResizeMix class that extends CutMix for random paste data augmentation with preserved object information', 'refactor the ResizeMix mix method to support configurable interpolation modes like bilinear or bicubic']
```

Usage

```
{'build_mixup_augmentation': 'build a python module to apply mixup batch augmentation on image tensors and one-hot labels', 'create_mixup_instance': 'create a Mixup instance with a beta distribution alpha parameter for mixing ratios', 'test_mixup_mix': 'test the Mixup mix method to blend batch inputs and one-hot scores with a random lambda', 'test_mixup_call': 'test the Mixup call method to mix batch inputs and validate one-hot tensor shape', 'review_mixup_class': 'review the Mixup class and its mix method for batch augmentation of image data'}
```

## File: facebookresearch_sapiens/pretrain/mmpretrain/models/utils/batch_augments/resizemix.py

Prompts

```
['build a python module that applies CutMix batch augmentation to a batch of images and labels', 'create a CutMix instance with alpha parameter and optional cutmix_minmax bounds for data augmentation', 'test the rand_bbox_minmax method to generate random rectangular bounding boxes within min/max area ratios', 'test the rand_bbox method to generate random square bounding boxes based on a lambda value', 'test the mix method that cuts and pastes patches among training images and mixes labels proportionally', 'build a python module to apply mixup batch augmentation on image tensors and one-hot labels', 'create a Mixup instance with a beta distribution alpha parameter for mixing ratios', 'test the Mixup mix method to blend batch inputs and one-hot scores with a random lambda', 'test the Mixup call method to mix batch inputs and validate one-hot tensor shape', 'review the Mixup class and its mix method for batch augmentation of image data', 'build a ResizeMix data augmentation module that resizes and pastes image patches onto other images in a batch', 'create a ResizeMix instance with alpha, lam_min, and lam_max parameters for image mixing ratio control', 'test the ResizeMix mix method to verify it returns mixed image tensors and interpolated label scores', 'review the ResizeMix class that extends CutMix for random paste data augmentation with preserved object information', 'refactor the ResizeMix mix method to support configurable interpolation modes like bilinear or bicubic']
```

Usage

```
{'build_resizemix_augmentation': 'build a ResizeMix data augmentation module that resizes and pastes image patches onto other images in a batch', 'create_resizemix_instance': 'create a ResizeMix instance with alpha, lam_min, and lam_max parameters for image mixing ratio control', 'test_mix_method': 'test the ResizeMix mix method to verify it returns mixed image tensors and interpolated label scores', 'review_resizemix_class': 'review the ResizeMix class that extends CutMix for random paste data augmentation with preserved object information', 'refactor_interpolation_mode': 'refactor the ResizeMix mix method to support configurable interpolation modes like bilinear or bicubic'}
```

