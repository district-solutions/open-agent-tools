# Agent Python Tools

- repo: facebookresearch/fast3r
- repo_uri: https://github.com/facebookresearch/fast3r

## File: facebookresearch_fast3r/fast3r/croco/datasets/pairs_dataset.py

Prompts

```
['run the cli to parse and cache image pairs for the habitat_release dataset', 'create a PairsDataset instance from dataset names with optional transforms and normalization', 'load image pairs from a cache file with two space-separated paths per line', 'load image pairs from a list file by appending _1.jpg and _2.jpg suffixes', 'write image pairs to a cache file with relative paths from a root directory', 'create a ComposePair transform to apply a sequence of paired transforms on two images', 'build a NormalizeBoth transform to normalize two images with the same mean and std values', 'create a ToTensorBoth transform to convert two PIL images into PyTorch tensors simultaneously', 'build a RandomCropPair transform to independently crop two images to a specified size', 'use get_pair_transforms to build a paired image transform pipeline from a string like crop224+acolor']
```

Usage

```
{'run_parse_and_cache_all_pairs': 'run the cli to parse and cache image pairs for the habitat_release dataset', 'create_PairsDataset': 'create a PairsDataset instance from dataset names with optional transforms and normalization', 'load_pairs_from_cache_file': 'load image pairs from a cache file with two space-separated paths per line', 'load_pairs_from_list_file': 'load image pairs from a list file by appending _1.jpg and _2.jpg suffixes', 'write_cache_file': 'write image pairs to a cache file with relative paths from a root directory'}
```

## File: facebookresearch_fast3r/fast3r/croco/datasets/transforms.py

Prompts

```
['run the cli to parse and cache image pairs for the habitat_release dataset', 'create a PairsDataset instance from dataset names with optional transforms and normalization', 'load image pairs from a cache file with two space-separated paths per line', 'load image pairs from a list file by appending _1.jpg and _2.jpg suffixes', 'write image pairs to a cache file with relative paths from a root directory', 'create a ComposePair transform to apply a sequence of paired transforms on two images', 'build a NormalizeBoth transform to normalize two images with the same mean and std values', 'create a ToTensorBoth transform to convert two PIL images into PyTorch tensors simultaneously', 'build a RandomCropPair transform to independently crop two images to a specified size', 'use get_pair_transforms to build a paired image transform pipeline from a string like crop224+acolor']
```

Usage

```
{'create_composepair': 'create a ComposePair transform to apply a sequence of paired transforms on two images', 'build_normalizeboth': 'build a NormalizeBoth transform to normalize two images with the same mean and std values', 'create_totensorboth': 'create a ToTensorBoth transform to convert two PIL images into PyTorch tensors simultaneously', 'build_randomcroppair': 'build a RandomCropPair transform to independently crop two images to a specified size', 'use_get_pair_transforms': 'use get_pair_transforms to build a paired image transform pipeline from a string like crop224+acolor'}
```

