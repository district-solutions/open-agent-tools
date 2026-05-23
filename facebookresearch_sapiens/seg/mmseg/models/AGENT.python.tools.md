# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/seg/mmseg/models/builder.py

Prompts

```
['build a backbone model from a config dict using the MODELS registry', 'build a neck model from a config dict using the MODELS registry', 'build a head model from a config dict using the MODELS registry', 'build a loss function from a config dict using the MODELS registry', 'build a segmentor model from a config dict with optional train and test config', 'build a SegDataPreProcessor to normalize, pad, and convert BGR to RGB for segmentation model inputs', 'create a StereoPointmapDataPreProcessor to preprocess stereo image pairs with normalization and padding for pointmap tasks', 'create a StereoCorrespondencesDataPreProcessor to preprocess stereo image pairs with normalization and padding for correspondence tasks', 'review the SegDataPreProcessor forward method to understand normalization, padding, and batch augmentation logic', 'test the SegDataPreProcessor channel conversion to verify BGR to RGB input transformation works correctly']
```

Usage

```
{'build_backbone': 'build a backbone model from a config dict using the MODELS registry', 'build_neck': 'build a neck model from a config dict using the MODELS registry', 'build_head': 'build a head model from a config dict using the MODELS registry', 'build_loss': 'build a loss function from a config dict using the MODELS registry', 'build_segmentor': 'build a segmentor model from a config dict with optional train and test config'}
```

## File: facebookresearch_sapiens/seg/mmseg/models/data_preprocessor.py

Prompts

```
['build a backbone model from a config dict using the MODELS registry', 'build a neck model from a config dict using the MODELS registry', 'build a head model from a config dict using the MODELS registry', 'build a loss function from a config dict using the MODELS registry', 'build a segmentor model from a config dict with optional train and test config', 'build a SegDataPreProcessor to normalize, pad, and convert BGR to RGB for segmentation model inputs', 'create a StereoPointmapDataPreProcessor to preprocess stereo image pairs with normalization and padding for pointmap tasks', 'create a StereoCorrespondencesDataPreProcessor to preprocess stereo image pairs with normalization and padding for correspondence tasks', 'review the SegDataPreProcessor forward method to understand normalization, padding, and batch augmentation logic', 'test the SegDataPreProcessor channel conversion to verify BGR to RGB input transformation works correctly']
```

Usage

```
{'build_SegDataPreProcessor': 'build a SegDataPreProcessor to normalize, pad, and convert BGR to RGB for segmentation model inputs', 'create_StereoPointmapDataPreProcessor': 'create a StereoPointmapDataPreProcessor to preprocess stereo image pairs with normalization and padding for pointmap tasks', 'create_StereoCorrespondencesDataPreProcessor': 'create a StereoCorrespondencesDataPreProcessor to preprocess stereo image pairs with normalization and padding for correspondence tasks', 'review_SegDataPreProcessor_forward': 'review the SegDataPreProcessor forward method to understand normalization, padding, and batch augmentation logic', 'test_SegDataPreProcessor_channel_conversion': 'test the SegDataPreProcessor channel conversion to verify BGR to RGB input transformation works correctly'}
```

