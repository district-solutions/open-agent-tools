# Agent Python Tools

- repo: facebookresearch/meshrcnn
- repo_uri: https://github.com/facebookresearch/meshrcnn

## File: facebookresearch_meshrcnn/tools/preprocess_shapenet.py

Prompts

```
['run the ShapeNet dataset preprocessing pipeline to extract meshes, voxels, and sampled points from OBJ files', 'process a single ShapeNet model to save metadata, mesh data, voxel coordinates, and renderings to disk', 'align source voxel coordinates to the target mesh bounding box by applying per-axis scale and shift', 'project 3D voxel coordinates through a camera matrix and bin them into a VxVxV voxel grid', 'parse R2N2 rendering metadata to compute extrinsic camera matrices from azimuth, elevation, and distance', 'run the MeshRCNN Trainer to train a 3D object detection model on Pix3D dataset', 'test the MeshRCNN model on the Pix3D dataset and return evaluation metrics', 'build a training data loader with MeshRCNNMapper for the configured training datasets', 'build a test data loader with MeshRCNNMapper for the configured test dataset', 'setup the MeshRCNN configuration from a config file and command line arguments', 'run the training loop for ShapeNet mesh reconstruction model with configurable epochs and loss functions', 'evaluate a trained mesh reconstruction model on the ShapeNet test dataset using checkpoint weights', 'build train, validation, and test data loaders for the MeshVox ShapeNet dataset splits', 'setup configuration from YAML file and initialize distributed logging for multi-GPU training', 'copy and unpack a tar or zip ShapeNet dataset archive to a temporary directory']
```

Usage

```
{'preprocess_shapenet_dataset': 'run the ShapeNet dataset preprocessing pipeline to extract meshes, voxels, and sampled points from OBJ files', 'handle_model_extraction': 'process a single ShapeNet model to save metadata, mesh data, voxel coordinates, and renderings to disk', 'align_bbox_coords': 'align source voxel coordinates to the target mesh bounding box by applying per-axis scale and shift', 'voxelize_projected_coords': 'project 3D voxel coordinates through a camera matrix and bin them into a VxVxV voxel grid', 'load_extrinsics_from_rendering': 'parse R2N2 rendering metadata to compute extrinsic camera matrices from azimuth, elevation, and distance'}
```

## File: facebookresearch_meshrcnn/tools/train_net.py

Prompts

```
['run the ShapeNet dataset preprocessing pipeline to extract meshes, voxels, and sampled points from OBJ files', 'process a single ShapeNet model to save metadata, mesh data, voxel coordinates, and renderings to disk', 'align source voxel coordinates to the target mesh bounding box by applying per-axis scale and shift', 'project 3D voxel coordinates through a camera matrix and bin them into a VxVxV voxel grid', 'parse R2N2 rendering metadata to compute extrinsic camera matrices from azimuth, elevation, and distance', 'run the MeshRCNN Trainer to train a 3D object detection model on Pix3D dataset', 'test the MeshRCNN model on the Pix3D dataset and return evaluation metrics', 'build a training data loader with MeshRCNNMapper for the configured training datasets', 'build a test data loader with MeshRCNNMapper for the configured test dataset', 'setup the MeshRCNN configuration from a config file and command line arguments', 'run the training loop for ShapeNet mesh reconstruction model with configurable epochs and loss functions', 'evaluate a trained mesh reconstruction model on the ShapeNet test dataset using checkpoint weights', 'build train, validation, and test data loaders for the MeshVox ShapeNet dataset splits', 'setup configuration from YAML file and initialize distributed logging for multi-GPU training', 'copy and unpack a tar or zip ShapeNet dataset archive to a temporary directory']
```

Usage

```
{'run_trainer_training': 'run the MeshRCNN Trainer to train a 3D object detection model on Pix3D dataset', 'test_trainer_evaluation': 'test the MeshRCNN model on the Pix3D dataset and return evaluation metrics', 'build_train_loader': 'build a training data loader with MeshRCNNMapper for the configured training datasets', 'build_test_loader': 'build a test data loader with MeshRCNNMapper for the configured test dataset', 'setup_configuration': 'setup the MeshRCNN configuration from a config file and command line arguments'}
```

## File: facebookresearch_meshrcnn/tools/train_net_shapenet.py

Prompts

```
['run the ShapeNet dataset preprocessing pipeline to extract meshes, voxels, and sampled points from OBJ files', 'process a single ShapeNet model to save metadata, mesh data, voxel coordinates, and renderings to disk', 'align source voxel coordinates to the target mesh bounding box by applying per-axis scale and shift', 'project 3D voxel coordinates through a camera matrix and bin them into a VxVxV voxel grid', 'parse R2N2 rendering metadata to compute extrinsic camera matrices from azimuth, elevation, and distance', 'run the MeshRCNN Trainer to train a 3D object detection model on Pix3D dataset', 'test the MeshRCNN model on the Pix3D dataset and return evaluation metrics', 'build a training data loader with MeshRCNNMapper for the configured training datasets', 'build a test data loader with MeshRCNNMapper for the configured test dataset', 'setup the MeshRCNN configuration from a config file and command line arguments', 'run the training loop for ShapeNet mesh reconstruction model with configurable epochs and loss functions', 'evaluate a trained mesh reconstruction model on the ShapeNet test dataset using checkpoint weights', 'build train, validation, and test data loaders for the MeshVox ShapeNet dataset splits', 'setup configuration from YAML file and initialize distributed logging for multi-GPU training', 'copy and unpack a tar or zip ShapeNet dataset archive to a temporary directory']
```

Usage

```
{'run_training_loop': 'run the training loop for ShapeNet mesh reconstruction model with configurable epochs and loss functions', 'evaluate_test_set': 'evaluate a trained mesh reconstruction model on the ShapeNet test dataset using checkpoint weights', 'build_data_loaders': 'build train, validation, and test data loaders for the MeshVox ShapeNet dataset splits', 'setup_config_and_logger': 'setup configuration from YAML file and initialize distributed logging for multi-GPU training', 'copy_and_unpack_data': 'copy and unpack a tar or zip ShapeNet dataset archive to a temporary directory'}
```

