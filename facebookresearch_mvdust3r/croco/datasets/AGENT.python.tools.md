# Agent Python Tools

- repo: facebookresearch/mvdust3r
- repo_uri: https://github.com/facebookresearch/mvdust3r

## File: facebookresearch_mvdust3r/croco/datasets/pairs_dataset.py

Prompts

```
['run the CLI to parse and cache image pairs for the habitat_release dataset', 'create a PairsDataset instance from dataset names with optional transforms and normalization', 'load image pairs from a cache file containing two paths per line', 'load image pairs from a listing file by appending _1.jpg and _2.jpg suffixes', 'write a list of image pairs to a cache file with optional root path stripping', 'build a pair image transform pipeline from a string like crop224+acolor with optional tensor conversion and normalization', 'create a ComposePair transform that applies a sequence of paired transforms to two images in order', 'build a ColorJitterPair transform that applies symmetric or asymmetric color jitter to a pair of images', 'create a RandomCropPair transform that applies independent random crops to two images with the same target size', 'build a NormalizeBoth transform that applies the same ImageNet normalization to a pair of images']
```

Usage

```
{'run_parse_and_cache_pairs': 'run the CLI to parse and cache image pairs for the habitat_release dataset', 'create_PairsDataset': 'create a PairsDataset instance from dataset names with optional transforms and normalization', 'load_pairs_from_cache_file': 'load image pairs from a cache file containing two paths per line', 'load_pairs_from_list_file': 'load image pairs from a listing file by appending _1.jpg and _2.jpg suffixes', 'write_cache_file': 'write a list of image pairs to a cache file with optional root path stripping'}
```

## File: facebookresearch_mvdust3r/croco/datasets/transforms.py

Prompts

```
['run the CLI to parse and cache image pairs for the habitat_release dataset', 'create a PairsDataset instance from dataset names with optional transforms and normalization', 'load image pairs from a cache file containing two paths per line', 'load image pairs from a listing file by appending _1.jpg and _2.jpg suffixes', 'write a list of image pairs to a cache file with optional root path stripping', 'build a pair image transform pipeline from a string like crop224+acolor with optional tensor conversion and normalization', 'create a ComposePair transform that applies a sequence of paired transforms to two images in order', 'build a ColorJitterPair transform that applies symmetric or asymmetric color jitter to a pair of images', 'create a RandomCropPair transform that applies independent random crops to two images with the same target size', 'build a NormalizeBoth transform that applies the same ImageNet normalization to a pair of images']
```

Usage

```
{'get_pair_transforms': 'build a pair image transform pipeline from a string like crop224+acolor with optional tensor conversion and normalization', 'ComposePair': 'create a ComposePair transform that applies a sequence of paired transforms to two images in order', 'ColorJitterPair': 'build a ColorJitterPair transform that applies symmetric or asymmetric color jitter to a pair of images', 'RandomCropPair': 'create a RandomCropPair transform that applies independent random crops to two images with the same target size', 'NormalizeBoth': 'build a NormalizeBoth transform that applies the same ImageNet normalization to a pair of images'}
```

