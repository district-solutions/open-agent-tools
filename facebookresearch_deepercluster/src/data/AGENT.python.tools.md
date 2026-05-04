# Agent Python Tools

- repo: facebookresearch/deepercluster
- repo_uri: https://github.com/facebookresearch/deepercluster

## File: facebookresearch_deepercluster/src/data/YFCC100M.py

Prompts

```
['create a YFCC100M dataset instance with a root directory, size, and optional transform', 'load an image file from a zip archive and convert it to RGB format', 'get an image and its cluster sub-class label by index from the YFCC100M dataset', 'get the total number of samples in the YFCC100M dataset including subset indexes', 'filter YFCC100M dataset to use only flickr unique IDs that exclude uniform color images', 'load an ImageFolder or YFCC100M dataset from a given data path argument', 'get clustering and training image transformations with optional rotation augmentation', 'rotate a numpy image array by 0, 90, 180, or 270 degrees', 'create a PyTorch sampler that iterates over image indices grouped by target class', 'group a list of image-target tuples into a dictionary keyed by target label']
```

Usage

```
{'create_YFCC100M_dataset': 'create a YFCC100M dataset instance with a root directory, size, and optional transform', 'load_image_from_zip': 'load an image file from a zip archive and convert it to RGB format', 'get_dataset_item': 'get an image and its cluster sub-class label by index from the YFCC100M dataset', 'get_dataset_length': 'get the total number of samples in the YFCC100M dataset including subset indexes', 'filter_flickr_unique_ids': 'filter YFCC100M dataset to use only flickr unique IDs that exclude uniform color images'}
```

## File: facebookresearch_deepercluster/src/data/loader.py

Prompts

```
['create a YFCC100M dataset instance with a root directory, size, and optional transform', 'load an image file from a zip archive and convert it to RGB format', 'get an image and its cluster sub-class label by index from the YFCC100M dataset', 'get the total number of samples in the YFCC100M dataset including subset indexes', 'filter YFCC100M dataset to use only flickr unique IDs that exclude uniform color images', 'load an ImageFolder or YFCC100M dataset from a given data path argument', 'get clustering and training image transformations with optional rotation augmentation', 'rotate a numpy image array by 0, 90, 180, or 270 degrees', 'create a PyTorch sampler that iterates over image indices grouped by target class', 'group a list of image-target tuples into a dictionary keyed by target label']
```

Usage

```
{'load_data': 'load an ImageFolder or YFCC100M dataset from a given data path argument', 'get_data_transformations': 'get clustering and training image transformations with optional rotation augmentation', 'rotate_img': 'rotate a numpy image array by 0, 90, 180, or 270 degrees', 'KFoldSampler': 'create a PyTorch sampler that iterates over image indices grouped by target class', 'per_target': 'group a list of image-target tuples into a dictionary keyed by target label'}
```

