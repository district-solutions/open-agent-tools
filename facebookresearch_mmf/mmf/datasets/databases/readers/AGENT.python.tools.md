# Agent Python Tools

- repo: facebookresearch/mmf
- repo_uri: https://github.com/facebookresearch/mmf

## File: facebookresearch_mmf/mmf/datasets/databases/readers/feature_readers.py

Prompts

```
['load a .npy or .pth feature file from disk and optionally convert to a PyTorch tensor', 'read image features from a base path using auto-detected dimensionality and return the feature tensor', 'read Faster R-CNN image features and pad them to a fixed maximum number of bounding boxes', 'read image features from an LMDB database by image ID and return padded feature tensors with metadata', 'read 4D CHW-format image features, pad to a square spatial size, and return the squeezed tensor']
```

Usage

```
{'load_feat': 'load a .npy or .pth feature file from disk and optionally convert to a PyTorch tensor', 'FeatureReader_read': 'read image features from a base path using auto-detected dimensionality and return the feature tensor', 'PaddedFasterRCNNFeatureReader_read': 'read Faster R-CNN image features and pad them to a fixed maximum number of bounding boxes', 'LMDBFeatureReader_read': 'read image features from an LMDB database by image ID and return padded feature tensors with metadata', 'CHWFeatureReader_read': 'read 4D CHW-format image features, pad to a square spatial size, and return the squeezed tensor'}
```

