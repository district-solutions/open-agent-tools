# Agent Python Tools

- repo: facebookresearch/meshrcnn
- repo_uri: https://github.com/facebookresearch/meshrcnn

## File: facebookresearch_meshrcnn/shapenet/data/build_data_loader.py

Prompts

```
['build a PyTorch DataLoader for MeshVox dataset with configurable batch size and sampling strategy', 'build a distributed DataLoader using DistributedSampler for multi-GPU training with MeshVox dataset', 'build a DataLoader with a random or sequential subset of num_samples from the MeshVox dataset', 'review the build_data_loader function to understand how it configures batch size, samplers, and postprocessing', 'refactor the build_data_loader function to support a new dataset type beyond MeshVox', 'register a shapenet dataset by name and return its data directory and splits file path', 'register a shapenet dataset with a custom root directory instead of the default datasets folder', 'review the predefined ShapeNet splits dictionary to see registered dataset names and their paths', 'summarize the register_shapenet function which validates dataset names and returns joined data and splits paths', 'test the register_shapenet function with an unregistered dataset name to verify it raises a ValueError', 'create a MeshVoxDataset instance from a data directory with configurable voxel size and sample count', 'use the dataset getitem method to retrieve an image, mesh, points, normals, and voxels by index', 'use the collate_fn static method to batch images, meshes, points, normals, and voxels together', 'use the postprocess method to move batched data to GPU and compute voxels on the fly', 'use the _voxelize method to convert voxel coordinates into a 3D voxel grid tensor', 'build a python module that returns a torchvision Normalize transform using ImageNet mean and std values', 'create a function that rescales a tensor to 0-1 range by subtracting min and dividing by range', 'build a python module that returns a Compose transform to reverse ImageNet normalization on a tensor', 'create a function that converts a PyTorch image tensor to a NumPy array with HWC layout', 'summarize the ImageNet mean, std, inverse mean, and inverse std constants defined in the module']
```

Usage

```
{'build_data_loader_for_meshvox': 'build a PyTorch DataLoader for MeshVox dataset with configurable batch size and sampling strategy', 'build_distributed_data_loader': 'build a distributed DataLoader using DistributedSampler for multi-GPU training with MeshVox dataset', 'build_subset_data_loader': 'build a DataLoader with a random or sequential subset of num_samples from the MeshVox dataset', 'review_build_data_loader_function': 'review the build_data_loader function to understand how it configures batch size, samplers, and postprocessing', 'refactor_build_data_loader_for_new_dataset': 'refactor the build_data_loader function to support a new dataset type beyond MeshVox'}
```

## File: facebookresearch_meshrcnn/shapenet/data/builtin.py

Prompts

```
['build a PyTorch DataLoader for MeshVox dataset with configurable batch size and sampling strategy', 'build a distributed DataLoader using DistributedSampler for multi-GPU training with MeshVox dataset', 'build a DataLoader with a random or sequential subset of num_samples from the MeshVox dataset', 'review the build_data_loader function to understand how it configures batch size, samplers, and postprocessing', 'refactor the build_data_loader function to support a new dataset type beyond MeshVox', 'register a shapenet dataset by name and return its data directory and splits file path', 'register a shapenet dataset with a custom root directory instead of the default datasets folder', 'review the predefined ShapeNet splits dictionary to see registered dataset names and their paths', 'summarize the register_shapenet function which validates dataset names and returns joined data and splits paths', 'test the register_shapenet function with an unregistered dataset name to verify it raises a ValueError', 'create a MeshVoxDataset instance from a data directory with configurable voxel size and sample count', 'use the dataset getitem method to retrieve an image, mesh, points, normals, and voxels by index', 'use the collate_fn static method to batch images, meshes, points, normals, and voxels together', 'use the postprocess method to move batched data to GPU and compute voxels on the fly', 'use the _voxelize method to convert voxel coordinates into a 3D voxel grid tensor', 'build a python module that returns a torchvision Normalize transform using ImageNet mean and std values', 'create a function that rescales a tensor to 0-1 range by subtracting min and dividing by range', 'build a python module that returns a Compose transform to reverse ImageNet normalization on a tensor', 'create a function that converts a PyTorch image tensor to a NumPy array with HWC layout', 'summarize the ImageNet mean, std, inverse mean, and inverse std constants defined in the module']
```

Usage

```
{'register_shapenet_dataset': 'register a shapenet dataset by name and return its data directory and splits file path', 'register_shapenet_custom_root': 'register a shapenet dataset with a custom root directory instead of the default datasets folder', 'review_PREDEFINED_SPLITS_SHAPENET': 'review the predefined ShapeNet splits dictionary to see registered dataset names and their paths', 'summarize_register_shapenet': 'summarize the register_shapenet function which validates dataset names and returns joined data and splits paths', 'test_register_shapenet_error': 'test the register_shapenet function with an unregistered dataset name to verify it raises a ValueError'}
```

## File: facebookresearch_meshrcnn/shapenet/data/mesh_vox.py

Prompts

```
['build a PyTorch DataLoader for MeshVox dataset with configurable batch size and sampling strategy', 'build a distributed DataLoader using DistributedSampler for multi-GPU training with MeshVox dataset', 'build a DataLoader with a random or sequential subset of num_samples from the MeshVox dataset', 'review the build_data_loader function to understand how it configures batch size, samplers, and postprocessing', 'refactor the build_data_loader function to support a new dataset type beyond MeshVox', 'register a shapenet dataset by name and return its data directory and splits file path', 'register a shapenet dataset with a custom root directory instead of the default datasets folder', 'review the predefined ShapeNet splits dictionary to see registered dataset names and their paths', 'summarize the register_shapenet function which validates dataset names and returns joined data and splits paths', 'test the register_shapenet function with an unregistered dataset name to verify it raises a ValueError', 'create a MeshVoxDataset instance from a data directory with configurable voxel size and sample count', 'use the dataset getitem method to retrieve an image, mesh, points, normals, and voxels by index', 'use the collate_fn static method to batch images, meshes, points, normals, and voxels together', 'use the postprocess method to move batched data to GPU and compute voxels on the fly', 'use the _voxelize method to convert voxel coordinates into a 3D voxel grid tensor', 'build a python module that returns a torchvision Normalize transform using ImageNet mean and std values', 'create a function that rescales a tensor to 0-1 range by subtracting min and dividing by range', 'build a python module that returns a Compose transform to reverse ImageNet normalization on a tensor', 'create a function that converts a PyTorch image tensor to a NumPy array with HWC layout', 'summarize the ImageNet mean, std, inverse mean, and inverse std constants defined in the module']
```

Usage

```
{'create_MeshVoxDataset': 'create a MeshVoxDataset instance from a data directory with configurable voxel size and sample count', 'use_getitem_MeshVoxDataset': 'use the dataset getitem method to retrieve an image, mesh, points, normals, and voxels by index', 'use_collate_fn_MeshVoxDataset': 'use the collate_fn static method to batch images, meshes, points, normals, and voxels together', 'use_postprocess_MeshVoxDataset': 'use the postprocess method to move batched data to GPU and compute voxels on the fly', 'use_voxelize_MeshVoxDataset': 'use the _voxelize method to convert voxel coordinates into a 3D voxel grid tensor'}
```

## File: facebookresearch_meshrcnn/shapenet/data/utils.py

Prompts

```
['build a PyTorch DataLoader for MeshVox dataset with configurable batch size and sampling strategy', 'build a distributed DataLoader using DistributedSampler for multi-GPU training with MeshVox dataset', 'build a DataLoader with a random or sequential subset of num_samples from the MeshVox dataset', 'review the build_data_loader function to understand how it configures batch size, samplers, and postprocessing', 'refactor the build_data_loader function to support a new dataset type beyond MeshVox', 'register a shapenet dataset by name and return its data directory and splits file path', 'register a shapenet dataset with a custom root directory instead of the default datasets folder', 'review the predefined ShapeNet splits dictionary to see registered dataset names and their paths', 'summarize the register_shapenet function which validates dataset names and returns joined data and splits paths', 'test the register_shapenet function with an unregistered dataset name to verify it raises a ValueError', 'create a MeshVoxDataset instance from a data directory with configurable voxel size and sample count', 'use the dataset getitem method to retrieve an image, mesh, points, normals, and voxels by index', 'use the collate_fn static method to batch images, meshes, points, normals, and voxels together', 'use the postprocess method to move batched data to GPU and compute voxels on the fly', 'use the _voxelize method to convert voxel coordinates into a 3D voxel grid tensor', 'build a python module that returns a torchvision Normalize transform using ImageNet mean and std values', 'create a function that rescales a tensor to 0-1 range by subtracting min and dividing by range', 'build a python module that returns a Compose transform to reverse ImageNet normalization on a tensor', 'create a function that converts a PyTorch image tensor to a NumPy array with HWC layout', 'summarize the ImageNet mean, std, inverse mean, and inverse std constants defined in the module']
```

Usage

```
{'build_imagenet_preprocess': 'build a python module that returns a torchvision Normalize transform using ImageNet mean and std values', 'create_rescale_tensor': 'create a function that rescales a tensor to 0-1 range by subtracting min and dividing by range', 'build_imagenet_deprocess': 'build a python module that returns a Compose transform to reverse ImageNet normalization on a tensor', 'create_image_to_numpy': 'create a function that converts a PyTorch image tensor to a NumPy array with HWC layout', 'summarize_constants': 'summarize the ImageNet mean, std, inverse mean, and inverse std constants defined in the module'}
```

