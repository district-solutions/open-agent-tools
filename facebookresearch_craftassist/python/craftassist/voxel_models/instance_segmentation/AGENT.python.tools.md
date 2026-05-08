# Agent Python Tools

- repo: facebookresearch/craftassist
- repo_uri: https://github.com/facebookresearch/craftassist

## File: facebookresearch_craftassist/python/craftassist/voxel_models/instance_segmentation/data_loaders.py

Prompts

```
['create an InstSegData PyTorch dataset from a pickle file for voxel instance segmentation training', 'build a flip or rotate augmentation on a 3D voxel cube and optional labels', 'fit a 3D voxel schematic into a fixed sidelength cube with optional centering on labels', 'generate a rectangular bounding mask around nonzero voxels in a 3D label tensor', 'create an underdirt augmentation that shifts a schematic downward and fills with dirt blocks', 'build a multi-scale 3D instance segmentation network with downsamplers, upsamplers, and cleanup layers', 'build a flat 3D instance segmentation network with configurable embedding and convolutional layers', 'run the MsInstSegNet model from command line with argparse for hidden_dim and embedding_dim', 'review the InstSegWrapper segment_object method that segments objects from numpy block arrays', 'test the InstSegNet save and load methods for persisting model state and options to disk', 'run the instance segmentation training script with configurable epochs, batch size, and CUDA support', 'run a single training epoch on the instance segmentation model with BCE loss and masked gradient sampling', 'run validation on the instance segmentation model using validation data', 'run debug slice printing to compare model input, ground truth, and predicted outputs for a data sample', 'run extraction of non-zero block coordinates and values from a voxel data sample']
```

Usage

```
{'create_instsegdata_dataset': 'create an InstSegData PyTorch dataset from a pickle file for voxel instance segmentation training', 'build_flip_rotate_augmentation': 'build a flip or rotate augmentation on a 3D voxel cube and optional labels', 'fit_schematic_in_sidelength': 'fit a 3D voxel schematic into a fixed sidelength cube with optional centering on labels', 'generate_rectanguloid_mask': 'generate a rectangular bounding mask around nonzero voxels in a 3D label tensor', 'create_underdirt_augmentation': 'create an underdirt augmentation that shifts a schematic downward and fills with dirt blocks'}
```

## File: facebookresearch_craftassist/python/craftassist/voxel_models/instance_segmentation/instseg_models.py

Prompts

```
['create an InstSegData PyTorch dataset from a pickle file for voxel instance segmentation training', 'build a flip or rotate augmentation on a 3D voxel cube and optional labels', 'fit a 3D voxel schematic into a fixed sidelength cube with optional centering on labels', 'generate a rectangular bounding mask around nonzero voxels in a 3D label tensor', 'create an underdirt augmentation that shifts a schematic downward and fills with dirt blocks', 'build a multi-scale 3D instance segmentation network with downsamplers, upsamplers, and cleanup layers', 'build a flat 3D instance segmentation network with configurable embedding and convolutional layers', 'run the MsInstSegNet model from command line with argparse for hidden_dim and embedding_dim', 'review the InstSegWrapper segment_object method that segments objects from numpy block arrays', 'test the InstSegNet save and load methods for persisting model state and options to disk', 'run the instance segmentation training script with configurable epochs, batch size, and CUDA support', 'run a single training epoch on the instance segmentation model with BCE loss and masked gradient sampling', 'run validation on the instance segmentation model using validation data', 'run debug slice printing to compare model input, ground truth, and predicted outputs for a data sample', 'run extraction of non-zero block coordinates and values from a voxel data sample']
```

Usage

```
{'build_MsInstSegNet': 'build a multi-scale 3D instance segmentation network with downsamplers, upsamplers, and cleanup layers', 'build_FlatInstSegNet': 'build a flat 3D instance segmentation network with configurable embedding and convolutional layers', 'run_MsInstSegNet_cli': 'run the MsInstSegNet model from command line with argparse for hidden_dim and embedding_dim', 'review_InstSegWrapper_segment_object': 'review the InstSegWrapper segment_object method that segments objects from numpy block arrays', 'test_InstSegNet_save_load': 'test the InstSegNet save and load methods for persisting model state and options to disk'}
```

## File: facebookresearch_craftassist/python/craftassist/voxel_models/instance_segmentation/train_instance_segmentation.py

Prompts

```
['create an InstSegData PyTorch dataset from a pickle file for voxel instance segmentation training', 'build a flip or rotate augmentation on a 3D voxel cube and optional labels', 'fit a 3D voxel schematic into a fixed sidelength cube with optional centering on labels', 'generate a rectangular bounding mask around nonzero voxels in a 3D label tensor', 'create an underdirt augmentation that shifts a schematic downward and fills with dirt blocks', 'build a multi-scale 3D instance segmentation network with downsamplers, upsamplers, and cleanup layers', 'build a flat 3D instance segmentation network with configurable embedding and convolutional layers', 'run the MsInstSegNet model from command line with argparse for hidden_dim and embedding_dim', 'review the InstSegWrapper segment_object method that segments objects from numpy block arrays', 'test the InstSegNet save and load methods for persisting model state and options to disk', 'run the instance segmentation training script with configurable epochs, batch size, and CUDA support', 'run a single training epoch on the instance segmentation model with BCE loss and masked gradient sampling', 'run validation on the instance segmentation model using validation data', 'run debug slice printing to compare model input, ground truth, and predicted outputs for a data sample', 'run extraction of non-zero block coordinates and values from a voxel data sample']
```

Usage

```
{'run_train_instance_segmentation': 'run the instance segmentation training script with configurable epochs, batch size, and CUDA support', 'run_train_epoch': 'run a single training epoch on the instance segmentation model with BCE loss and masked gradient sampling', 'run_validate': 'run validation on the instance segmentation model using validation data', 'run_print_slices': 'run debug slice printing to compare model input, ground truth, and predicted outputs for a data sample', 'run_blocks_from_data': 'run extraction of non-zero block coordinates and values from a voxel data sample'}
```

