# Agent Python Tools

- repo: facebookresearch/multigrain
- repo_uri: https://github.com/facebookresearch/multigrain

## File: facebookresearch_multigrain/multigrain/datasets/imagenet.py

Prompts

```
['create an IN1K dataset instance with a root path and train split for ImageNet 1K', 'build an IN1K dataset with a custom transform applied to each loaded image', 'test the IN1K dataset __getitem__ method to load and transform an image by index', 'review the IN1K get_dataset method that indexes and caches ImageNet files from ImageFolder or DevKit format', 'summarize the IN1K class attributes including NUM_CLASSES, MEAN, STD, EIG_VALS, and EIG_VECS constants', 'build a python module that loads an image from a file path and converts it to RGB format', 'build a python module that preloads images from a dataset root directory to a preload directory for faster access', 'test the loader function by loading an image file and verifying it returns an RGB PIL Image', 'test the preloader function by creating a preload directory and verifying images are copied and loaded correctly', 'review the loader and preloader functions to understand how images are loaded and cached for dataset processing', 'create a DownloadableDataset subclass that downloads and extracts zip or tar archives to a root directory', 'use the UKBench dataset class to load 10200 images grouped into sets of four for image retrieval', 'use the Holidays dataset class to load 1491 images with optional rotation correction from a YAML config', 'use the CopyDays dataset class to load images with variants and distractors for copy detection retrieval', 'extract zip or tar.gz archive files to a destination directory using the static extract methods']
```

Usage

```
{'create_IN1K_dataset': 'create an IN1K dataset instance with a root path and train split for ImageNet 1K', 'build_IN1K_with_transform': 'build an IN1K dataset with a custom transform applied to each loaded image', 'test_IN1K_getitem': 'test the IN1K dataset __getitem__ method to load and transform an image by index', 'review_IN1K_get_dataset': 'review the IN1K get_dataset method that indexes and caches ImageNet files from ImageFolder or DevKit format', 'summarize_IN1K_class_attributes': 'summarize the IN1K class attributes including NUM_CLASSES, MEAN, STD, EIG_VALS, and EIG_VECS constants'}
```

## File: facebookresearch_multigrain/multigrain/datasets/loader.py

Prompts

```
['create an IN1K dataset instance with a root path and train split for ImageNet 1K', 'build an IN1K dataset with a custom transform applied to each loaded image', 'test the IN1K dataset __getitem__ method to load and transform an image by index', 'review the IN1K get_dataset method that indexes and caches ImageNet files from ImageFolder or DevKit format', 'summarize the IN1K class attributes including NUM_CLASSES, MEAN, STD, EIG_VALS, and EIG_VECS constants', 'build a python module that loads an image from a file path and converts it to RGB format', 'build a python module that preloads images from a dataset root directory to a preload directory for faster access', 'test the loader function by loading an image file and verifying it returns an RGB PIL Image', 'test the preloader function by creating a preload directory and verifying images are copied and loaded correctly', 'review the loader and preloader functions to understand how images are loaded and cached for dataset processing', 'create a DownloadableDataset subclass that downloads and extracts zip or tar archives to a root directory', 'use the UKBench dataset class to load 10200 images grouped into sets of four for image retrieval', 'use the Holidays dataset class to load 1491 images with optional rotation correction from a YAML config', 'use the CopyDays dataset class to load images with variants and distractors for copy detection retrieval', 'extract zip or tar.gz archive files to a destination directory using the static extract methods']
```

Usage

```
{'build_loader_function': 'build a python module that loads an image from a file path and converts it to RGB format', 'build_preloader_function': 'build a python module that preloads images from a dataset root directory to a preload directory for faster access', 'test_loader': 'test the loader function by loading an image file and verifying it returns an RGB PIL Image', 'test_preloader': 'test the preloader function by creating a preload directory and verifying images are copied and loaded correctly', 'review_loader_and_preloader': 'review the loader and preloader functions to understand how images are loaded and cached for dataset processing'}
```

## File: facebookresearch_multigrain/multigrain/datasets/retrieval.py

Prompts

```
['create an IN1K dataset instance with a root path and train split for ImageNet 1K', 'build an IN1K dataset with a custom transform applied to each loaded image', 'test the IN1K dataset __getitem__ method to load and transform an image by index', 'review the IN1K get_dataset method that indexes and caches ImageNet files from ImageFolder or DevKit format', 'summarize the IN1K class attributes including NUM_CLASSES, MEAN, STD, EIG_VALS, and EIG_VECS constants', 'build a python module that loads an image from a file path and converts it to RGB format', 'build a python module that preloads images from a dataset root directory to a preload directory for faster access', 'test the loader function by loading an image file and verifying it returns an RGB PIL Image', 'test the preloader function by creating a preload directory and verifying images are copied and loaded correctly', 'review the loader and preloader functions to understand how images are loaded and cached for dataset processing', 'create a DownloadableDataset subclass that downloads and extracts zip or tar archives to a root directory', 'use the UKBench dataset class to load 10200 images grouped into sets of four for image retrieval', 'use the Holidays dataset class to load 1491 images with optional rotation correction from a YAML config', 'use the CopyDays dataset class to load images with variants and distractors for copy detection retrieval', 'extract zip or tar.gz archive files to a destination directory using the static extract methods']
```

Usage

```
{'create_downloadable_dataset': 'create a DownloadableDataset subclass that downloads and extracts zip or tar archives to a root directory', 'use_ukbench_dataset': 'use the UKBench dataset class to load 10200 images grouped into sets of four for image retrieval', 'use_holidays_dataset': 'use the Holidays dataset class to load 1491 images with optional rotation correction from a YAML config', 'use_copydays_dataset': 'use the CopyDays dataset class to load images with variants and distractors for copy detection retrieval', 'extract_archive_files': 'extract zip or tar.gz archive files to a destination directory using the static extract methods'}
```

