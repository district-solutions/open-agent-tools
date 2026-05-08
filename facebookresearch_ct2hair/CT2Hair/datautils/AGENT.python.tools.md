# Agent Python Tools

- repo: facebookresearch/ct2hair
- repo_uri: https://github.com/facebookresearch/ct2hair

## File: facebookresearch_ct2hair/CT2Hair/datautils/dataloaders.py

Prompts

```
['create a TbnStrandsBinDataset from TBN strand arrays with configurable resampling and point count', 'get a PyTorch DataLoader from a TbnStrandsBinDataset instance with batch size 300', 'get a strand item by index returning points tensor and optional times tensor', 'review the TbnStrandsBinDataset constructor to understand resampling and point count parameters', 'summarize the TbnStrandsBinDataset class for hair strand data loading with mm to m scaling', 'load a raw 3D volume from a .npy or binary file with optional cropping and downsampling', 'crop hair regions from volumetric data using a specified hair density range threshold', 'load hair strand data from a binary file containing vertex positions and normal vectors', 'save hair strand data with optional tangent vectors to a binary file format', 'expand voxel indices by a scale rate to generate finer-grained 3D coordinate grids']
```

Usage

```
{'create_TbnStrandsBinDataset': 'create a TbnStrandsBinDataset from TBN strand arrays with configurable resampling and point count', 'get_dataloader_TbnStrandsBinDataset': 'get a PyTorch DataLoader from a TbnStrandsBinDataset instance with batch size 300', 'getitem_TbnStrandsBinDataset': 'get a strand item by index returning points tensor and optional times tensor', 'review_TbnStrandsBinDataset_init': 'review the TbnStrandsBinDataset constructor to understand resampling and point count parameters', 'summarize_TbnStrandsBinDataset': 'summarize the TbnStrandsBinDataset class for hair strand data loading with mm to m scaling'}
```

## File: facebookresearch_ct2hair/CT2Hair/datautils/datautils.py

Prompts

```
['create a TbnStrandsBinDataset from TBN strand arrays with configurable resampling and point count', 'get a PyTorch DataLoader from a TbnStrandsBinDataset instance with batch size 300', 'get a strand item by index returning points tensor and optional times tensor', 'review the TbnStrandsBinDataset constructor to understand resampling and point count parameters', 'summarize the TbnStrandsBinDataset class for hair strand data loading with mm to m scaling', 'load a raw 3D volume from a .npy or binary file with optional cropping and downsampling', 'crop hair regions from volumetric data using a specified hair density range threshold', 'load hair strand data from a binary file containing vertex positions and normal vectors', 'save hair strand data with optional tangent vectors to a binary file format', 'expand voxel indices by a scale rate to generate finer-grained 3D coordinate grids']
```

Usage

```
{'load_raw_volume': 'load a raw 3D volume from a .npy or binary file with optional cropping and downsampling', 'crop_hair_by_density': 'crop hair regions from volumetric data using a specified hair density range threshold', 'load_bin_strands': 'load hair strand data from a binary file containing vertex positions and normal vectors', 'save_bin_strands': 'save hair strand data with optional tangent vectors to a binary file format', 'expand_vidx': 'expand voxel indices by a scale rate to generate finer-grained 3D coordinate grids'}
```

