# Agent Python Tools

- repo: facebookresearch/fastmri
- repo_uri: https://github.com/facebookresearch/fastmri

## File: facebookresearch_fastmri/banding_removal/fastmri/data/mri_data.py

Prompts

```
['create a PyTorch Dataset to load MR image slices from HDF5 files with configurable filtering', 'build a SliceData dataset with a custom transform callable for kspace and target preprocessing', 'test the SliceData __getitem__ method to retrieve kspace and target for a given slice index', 'review the SliceData __init__ method to understand filtering by coil count, kspace dimensions, and acquisition type', 'summarize the get_system_from_volume function that extracts the MRI system model from an ISMRMRD header', 'test the transforms.apply_mask function that applies a RandomMask to k-space MRI data tensors', 'test the transforms.fft2 function that computes a 2D FFT on complex-valued tensors', 'test the transforms.center_crop_or_pad function that crops or pads a tensor to a target shape', 'test the transforms.normalize_instance function that normalizes a tensor to zero mean and unit variance', 'test the transforms.root_sum_of_squares function that computes the RSS magnitude across a given dimension', 'build a python module that applies centered 2D FFT and IFFT transforms to complex MRI k-space data tensors', 'create a function that subsamples k-space data by multiplying with a generated mask tensor', 'test the complex multiplication, division, and conjugate functions on tensors with a trailing dimension of size 2', 'refactor the root sum of squares function to combine multi-coil MRI data along a specified dimension', 'review the complex packing, unpacking, and planar conversion functions for k-space data shape transformations', 'create a VolumeSampler that splits dataset volumes across distributed nodes keeping same volume together', 'iterate over a VolumeSampler to get shuffled indices for the current rank and epoch', 'set the epoch on a VolumeSampler to change the deterministic shuffle seed', 'review the VolumeSampler init to understand how volumes are split across distributed ranks', 'summarize the VolumeSampler class which extends PyTorch Sampler for volume-aware distributed training']
```

Usage

```
{'create_SliceData_dataset': 'create a PyTorch Dataset to load MR image slices from HDF5 files with configurable filtering', 'build_SliceData_with_transform': 'build a SliceData dataset with a custom transform callable for kspace and target preprocessing', 'test_SliceData_getitem': 'test the SliceData __getitem__ method to retrieve kspace and target for a given slice index', 'review_SliceData_init': 'review the SliceData __init__ method to understand filtering by coil count, kspace dimensions, and acquisition type', 'summarize_get_system_from_volume': 'summarize the get_system_from_volume function that extracts the MRI system model from an ISMRMRD header'}
```

## File: facebookresearch_fastmri/banding_removal/fastmri/data/test_transforms.py

Prompts

```
['create a PyTorch Dataset to load MR image slices from HDF5 files with configurable filtering', 'build a SliceData dataset with a custom transform callable for kspace and target preprocessing', 'test the SliceData __getitem__ method to retrieve kspace and target for a given slice index', 'review the SliceData __init__ method to understand filtering by coil count, kspace dimensions, and acquisition type', 'summarize the get_system_from_volume function that extracts the MRI system model from an ISMRMRD header', 'test the transforms.apply_mask function that applies a RandomMask to k-space MRI data tensors', 'test the transforms.fft2 function that computes a 2D FFT on complex-valued tensors', 'test the transforms.center_crop_or_pad function that crops or pads a tensor to a target shape', 'test the transforms.normalize_instance function that normalizes a tensor to zero mean and unit variance', 'test the transforms.root_sum_of_squares function that computes the RSS magnitude across a given dimension', 'build a python module that applies centered 2D FFT and IFFT transforms to complex MRI k-space data tensors', 'create a function that subsamples k-space data by multiplying with a generated mask tensor', 'test the complex multiplication, division, and conjugate functions on tensors with a trailing dimension of size 2', 'refactor the root sum of squares function to combine multi-coil MRI data along a specified dimension', 'review the complex packing, unpacking, and planar conversion functions for k-space data shape transformations', 'create a VolumeSampler that splits dataset volumes across distributed nodes keeping same volume together', 'iterate over a VolumeSampler to get shuffled indices for the current rank and epoch', 'set the epoch on a VolumeSampler to change the deterministic shuffle seed', 'review the VolumeSampler init to understand how volumes are split across distributed ranks', 'summarize the VolumeSampler class which extends PyTorch Sampler for volume-aware distributed training']
```

Usage

```
{'test_apply_mask': 'test the transforms.apply_mask function that applies a RandomMask to k-space MRI data tensors', 'test_fft2': 'test the transforms.fft2 function that computes a 2D FFT on complex-valued tensors', 'test_center_crop_or_pad': 'test the transforms.center_crop_or_pad function that crops or pads a tensor to a target shape', 'test_normalize_instance': 'test the transforms.normalize_instance function that normalizes a tensor to zero mean and unit variance', 'test_root_sum_of_squares': 'test the transforms.root_sum_of_squares function that computes the RSS magnitude across a given dimension'}
```

## File: facebookresearch_fastmri/banding_removal/fastmri/data/transforms.py

Prompts

```
['create a PyTorch Dataset to load MR image slices from HDF5 files with configurable filtering', 'build a SliceData dataset with a custom transform callable for kspace and target preprocessing', 'test the SliceData __getitem__ method to retrieve kspace and target for a given slice index', 'review the SliceData __init__ method to understand filtering by coil count, kspace dimensions, and acquisition type', 'summarize the get_system_from_volume function that extracts the MRI system model from an ISMRMRD header', 'test the transforms.apply_mask function that applies a RandomMask to k-space MRI data tensors', 'test the transforms.fft2 function that computes a 2D FFT on complex-valued tensors', 'test the transforms.center_crop_or_pad function that crops or pads a tensor to a target shape', 'test the transforms.normalize_instance function that normalizes a tensor to zero mean and unit variance', 'test the transforms.root_sum_of_squares function that computes the RSS magnitude across a given dimension', 'build a python module that applies centered 2D FFT and IFFT transforms to complex MRI k-space data tensors', 'create a function that subsamples k-space data by multiplying with a generated mask tensor', 'test the complex multiplication, division, and conjugate functions on tensors with a trailing dimension of size 2', 'refactor the root sum of squares function to combine multi-coil MRI data along a specified dimension', 'review the complex packing, unpacking, and planar conversion functions for k-space data shape transformations', 'create a VolumeSampler that splits dataset volumes across distributed nodes keeping same volume together', 'iterate over a VolumeSampler to get shuffled indices for the current rank and epoch', 'set the epoch on a VolumeSampler to change the deterministic shuffle seed', 'review the VolumeSampler init to understand how volumes are split across distributed ranks', 'summarize the VolumeSampler class which extends PyTorch Sampler for volume-aware distributed training']
```

Usage

```
{'build_complex_fft_pipeline': 'build a python module that applies centered 2D FFT and IFFT transforms to complex MRI k-space data tensors', 'create_masking_subsampling': 'create a function that subsamples k-space data by multiplying with a generated mask tensor', 'test_complex_arithmetic': 'test the complex multiplication, division, and conjugate functions on tensors with a trailing dimension of size 2', 'refactor_rss_coil_combination': 'refactor the root sum of squares function to combine multi-coil MRI data along a specified dimension', 'review_kspace_transforms': 'review the complex packing, unpacking, and planar conversion functions for k-space data shape transformations'}
```

## File: facebookresearch_fastmri/banding_removal/fastmri/data/volume_sampler.py

Prompts

```
['create a PyTorch Dataset to load MR image slices from HDF5 files with configurable filtering', 'build a SliceData dataset with a custom transform callable for kspace and target preprocessing', 'test the SliceData __getitem__ method to retrieve kspace and target for a given slice index', 'review the SliceData __init__ method to understand filtering by coil count, kspace dimensions, and acquisition type', 'summarize the get_system_from_volume function that extracts the MRI system model from an ISMRMRD header', 'test the transforms.apply_mask function that applies a RandomMask to k-space MRI data tensors', 'test the transforms.fft2 function that computes a 2D FFT on complex-valued tensors', 'test the transforms.center_crop_or_pad function that crops or pads a tensor to a target shape', 'test the transforms.normalize_instance function that normalizes a tensor to zero mean and unit variance', 'test the transforms.root_sum_of_squares function that computes the RSS magnitude across a given dimension', 'build a python module that applies centered 2D FFT and IFFT transforms to complex MRI k-space data tensors', 'create a function that subsamples k-space data by multiplying with a generated mask tensor', 'test the complex multiplication, division, and conjugate functions on tensors with a trailing dimension of size 2', 'refactor the root sum of squares function to combine multi-coil MRI data along a specified dimension', 'review the complex packing, unpacking, and planar conversion functions for k-space data shape transformations', 'create a VolumeSampler that splits dataset volumes across distributed nodes keeping same volume together', 'iterate over a VolumeSampler to get shuffled indices for the current rank and epoch', 'set the epoch on a VolumeSampler to change the deterministic shuffle seed', 'review the VolumeSampler init to understand how volumes are split across distributed ranks', 'summarize the VolumeSampler class which extends PyTorch Sampler for volume-aware distributed training']
```

Usage

```
{'create_VolumeSampler': 'create a VolumeSampler that splits dataset volumes across distributed nodes keeping same volume together', 'iterate_VolumeSampler': 'iterate over a VolumeSampler to get shuffled indices for the current rank and epoch', 'set_epoch_VolumeSampler': 'set the epoch on a VolumeSampler to change the deterministic shuffle seed', 'review_VolumeSampler_init': 'review the VolumeSampler init to understand how volumes are split across distributed ranks', 'summarize_VolumeSampler': 'summarize the VolumeSampler class which extends PyTorch Sampler for volume-aware distributed training'}
```

