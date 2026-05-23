# Agent Python Tools

- repo: facebookresearch/fastmri
- repo_uri: https://github.com/facebookresearch/fastmri

## File: facebookresearch_fastmri/fastmri/data/mri_data.py

Prompts

```
['use et_query to retrieve nested values from an ISMRMRD XML header element tree', 'use fetch_dir to retrieve a knee or brain data path from a yaml config file', 'create a SliceDataset to load MR kspace slices from hdf5 files with optional transforms', 'create a CombinedSliceDataset to merge multiple SliceDatasets with per-dataset transforms and sampling', 'create an AnnotatedSliceDataset to load MR slices with fastMRI+ annotations downloaded from github', 'create a RandomMaskFunc with center fractions and accelerations to generate random k-space subsampling masks', 'create an EquiSpacedMaskFunc with center fractions and accelerations to generate equispaced k-space subsampling masks', 'create a MaskFunc by calling create_mask_for_mask_type with a mask type string, center fractions, and accelerations', 'call a MaskFunc instance with a k-space shape to get a sampling mask tensor and center frequency count', 'create a MagicMaskFunc that exploits conjugate symmetry via offset sampling for accelerated MRI reconstruction', 'apply a sampling mask to k-space data using a MaskFunc to subsample MRI k-space', 'convert a numpy array to a PyTorch tensor with complex values stacked along the last dimension', 'normalize a tensor using instance normalization by computing mean and stddev from the data itself', 'apply a center crop to a complex MRI image tensor along the last three spatial dimensions', 'transform raw k-space data into a VarNetSample with masked k-space, mask, and target for VarNet training', 'create a VolumeSampler for distributed MRI training that keeps all slices from the same volume on the same node', 'build a PyTorch DataLoader using VolumeSampler to distribute MRI volumes across multiple training processes', 'test the VolumeSampler shuffle functionality by verifying indices are reordered with different epoch seeds', 'review the VolumeSampler constructor to understand how it splits volume names across distributed replicas', 'summarize the VolumeSampler __iter__ method that handles shuffling and padding indices to equal length per replica']
```

Usage

```
{'query_ismrmrd_xml_with_et_query': 'use et_query to retrieve nested values from an ISMRMRD XML header element tree', 'fetch_data_directory_with_fetch_dir': 'use fetch_dir to retrieve a knee or brain data path from a yaml config file', 'create_slice_dataset_for_mr_slices': 'create a SliceDataset to load MR kspace slices from hdf5 files with optional transforms', 'combine_datasets_with_combined_slice_dataset': 'create a CombinedSliceDataset to merge multiple SliceDatasets with per-dataset transforms and sampling', 'create_annotated_slice_dataset_with_annotations': 'create an AnnotatedSliceDataset to load MR slices with fastMRI+ annotations downloaded from github'}
```

## File: facebookresearch_fastmri/fastmri/data/subsample.py

Prompts

```
['use et_query to retrieve nested values from an ISMRMRD XML header element tree', 'use fetch_dir to retrieve a knee or brain data path from a yaml config file', 'create a SliceDataset to load MR kspace slices from hdf5 files with optional transforms', 'create a CombinedSliceDataset to merge multiple SliceDatasets with per-dataset transforms and sampling', 'create an AnnotatedSliceDataset to load MR slices with fastMRI+ annotations downloaded from github', 'create a RandomMaskFunc with center fractions and accelerations to generate random k-space subsampling masks', 'create an EquiSpacedMaskFunc with center fractions and accelerations to generate equispaced k-space subsampling masks', 'create a MaskFunc by calling create_mask_for_mask_type with a mask type string, center fractions, and accelerations', 'call a MaskFunc instance with a k-space shape to get a sampling mask tensor and center frequency count', 'create a MagicMaskFunc that exploits conjugate symmetry via offset sampling for accelerated MRI reconstruction', 'apply a sampling mask to k-space data using a MaskFunc to subsample MRI k-space', 'convert a numpy array to a PyTorch tensor with complex values stacked along the last dimension', 'normalize a tensor using instance normalization by computing mean and stddev from the data itself', 'apply a center crop to a complex MRI image tensor along the last three spatial dimensions', 'transform raw k-space data into a VarNetSample with masked k-space, mask, and target for VarNet training', 'create a VolumeSampler for distributed MRI training that keeps all slices from the same volume on the same node', 'build a PyTorch DataLoader using VolumeSampler to distribute MRI volumes across multiple training processes', 'test the VolumeSampler shuffle functionality by verifying indices are reordered with different epoch seeds', 'review the VolumeSampler constructor to understand how it splits volume names across distributed replicas', 'summarize the VolumeSampler __iter__ method that handles shuffling and padding indices to equal length per replica']
```

Usage

```
{'create_random_mask': 'create a RandomMaskFunc with center fractions and accelerations to generate random k-space subsampling masks', 'create_equispaced_mask': 'create an EquiSpacedMaskFunc with center fractions and accelerations to generate equispaced k-space subsampling masks', 'create_mask_for_type': 'create a MaskFunc by calling create_mask_for_mask_type with a mask type string, center fractions, and accelerations', 'call_mask_func': 'call a MaskFunc instance with a k-space shape to get a sampling mask tensor and center frequency count', 'create_magic_mask': 'create a MagicMaskFunc that exploits conjugate symmetry via offset sampling for accelerated MRI reconstruction'}
```

## File: facebookresearch_fastmri/fastmri/data/transforms.py

Prompts

```
['use et_query to retrieve nested values from an ISMRMRD XML header element tree', 'use fetch_dir to retrieve a knee or brain data path from a yaml config file', 'create a SliceDataset to load MR kspace slices from hdf5 files with optional transforms', 'create a CombinedSliceDataset to merge multiple SliceDatasets with per-dataset transforms and sampling', 'create an AnnotatedSliceDataset to load MR slices with fastMRI+ annotations downloaded from github', 'create a RandomMaskFunc with center fractions and accelerations to generate random k-space subsampling masks', 'create an EquiSpacedMaskFunc with center fractions and accelerations to generate equispaced k-space subsampling masks', 'create a MaskFunc by calling create_mask_for_mask_type with a mask type string, center fractions, and accelerations', 'call a MaskFunc instance with a k-space shape to get a sampling mask tensor and center frequency count', 'create a MagicMaskFunc that exploits conjugate symmetry via offset sampling for accelerated MRI reconstruction', 'apply a sampling mask to k-space data using a MaskFunc to subsample MRI k-space', 'convert a numpy array to a PyTorch tensor with complex values stacked along the last dimension', 'normalize a tensor using instance normalization by computing mean and stddev from the data itself', 'apply a center crop to a complex MRI image tensor along the last three spatial dimensions', 'transform raw k-space data into a VarNetSample with masked k-space, mask, and target for VarNet training', 'create a VolumeSampler for distributed MRI training that keeps all slices from the same volume on the same node', 'build a PyTorch DataLoader using VolumeSampler to distribute MRI volumes across multiple training processes', 'test the VolumeSampler shuffle functionality by verifying indices are reordered with different epoch seeds', 'review the VolumeSampler constructor to understand how it splits volume names across distributed replicas', 'summarize the VolumeSampler __iter__ method that handles shuffling and padding indices to equal length per replica']
```

Usage

```
{'apply_mask_to_kspace': 'apply a sampling mask to k-space data using a MaskFunc to subsample MRI k-space', 'convert_numpy_to_tensor': 'convert a numpy array to a PyTorch tensor with complex values stacked along the last dimension', 'normalize_instance_data': 'normalize a tensor using instance normalization by computing mean and stddev from the data itself', 'center_crop_complex_image': 'apply a center crop to a complex MRI image tensor along the last three spatial dimensions', 'transform_varnet_data': 'transform raw k-space data into a VarNetSample with masked k-space, mask, and target for VarNet training'}
```

## File: facebookresearch_fastmri/fastmri/data/volume_sampler.py

Prompts

```
['use et_query to retrieve nested values from an ISMRMRD XML header element tree', 'use fetch_dir to retrieve a knee or brain data path from a yaml config file', 'create a SliceDataset to load MR kspace slices from hdf5 files with optional transforms', 'create a CombinedSliceDataset to merge multiple SliceDatasets with per-dataset transforms and sampling', 'create an AnnotatedSliceDataset to load MR slices with fastMRI+ annotations downloaded from github', 'create a RandomMaskFunc with center fractions and accelerations to generate random k-space subsampling masks', 'create an EquiSpacedMaskFunc with center fractions and accelerations to generate equispaced k-space subsampling masks', 'create a MaskFunc by calling create_mask_for_mask_type with a mask type string, center fractions, and accelerations', 'call a MaskFunc instance with a k-space shape to get a sampling mask tensor and center frequency count', 'create a MagicMaskFunc that exploits conjugate symmetry via offset sampling for accelerated MRI reconstruction', 'apply a sampling mask to k-space data using a MaskFunc to subsample MRI k-space', 'convert a numpy array to a PyTorch tensor with complex values stacked along the last dimension', 'normalize a tensor using instance normalization by computing mean and stddev from the data itself', 'apply a center crop to a complex MRI image tensor along the last three spatial dimensions', 'transform raw k-space data into a VarNetSample with masked k-space, mask, and target for VarNet training', 'create a VolumeSampler for distributed MRI training that keeps all slices from the same volume on the same node', 'build a PyTorch DataLoader using VolumeSampler to distribute MRI volumes across multiple training processes', 'test the VolumeSampler shuffle functionality by verifying indices are reordered with different epoch seeds', 'review the VolumeSampler constructor to understand how it splits volume names across distributed replicas', 'summarize the VolumeSampler __iter__ method that handles shuffling and padding indices to equal length per replica']
```

Usage

```
{'create_volume_sampler': 'create a VolumeSampler for distributed MRI training that keeps all slices from the same volume on the same node', 'build_distributed_mri_dataloader': 'build a PyTorch DataLoader using VolumeSampler to distribute MRI volumes across multiple training processes', 'test_volume_sampler_shuffling': 'test the VolumeSampler shuffle functionality by verifying indices are reordered with different epoch seeds', 'review_volume_sampler_init': 'review the VolumeSampler constructor to understand how it splits volume names across distributed replicas', 'summarize_volume_sampler_iter': 'summarize the VolumeSampler __iter__ method that handles shuffling and padding indices to equal length per replica'}
```

