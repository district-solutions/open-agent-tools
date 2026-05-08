# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/perception/craftassist/voxel_models/semantic_segmentation/data_loaders.py

Prompts

```
['create a SemSegData dataset from a pickle file with configurable sidelength and augmentation options', 'preprocess raw voxel schematic data into normalized examples using make_example_from_raw with augmentation', 'randomly flip or rotate a 3D voxel cube tensor for data augmentation across x-z plane', 'fit and center a voxel schematic into a fixed sidelength cube with random shift augmentation', 'organize and merge semantic segmentation classes by swallowing rare classes below a minimum occurrence threshold', 'generate Minecraft shape scenes and save segmentation data as a pickle file using argparse CLI', 'convert a JSON scene description with blocks and instance segmentation tags into numpy segmentation arrays', 'build a Minecraft shape scene with configurable scene size, height, ground depth, and max number of shapes', 'run the CLI tool to generate multiple shape scenes with configurable offsets and save paths', 'review the json_to_segdata function that maps block locations and instance tags to 3D numpy arrays', 'build a 3D convolutional semantic segmentation neural network with configurable embedding and hidden dimensions', 'run the SemSegNet module via argparse CLI to instantiate a model with custom hyperparameters', 'create a SemSegWrapper to load a pretrained model and segment voxel blocks into semantic classes', 'test the SemSegWrapper segment_object method to classify non-air blocks in a voxel grid', 'review the SemSegNet forward pass that embeds block IDs and applies stacked 3D conv layers', 'train a voxel semantic segmentation model on Minecraft block data using PyTorch with configurable epochs and batch size', 'validate a trained semantic segmentation model on validation data and report accuracy metrics', 'run a single training epoch on the semantic segmentation model with masked loss computation', 'extract nonzero voxel blocks from a data sample and return their coordinates and block IDs', 'print input, ground truth, and predicted slices from a semantic segmentation model for debugging']
```

Usage

```
{'create_semseg_dataset': 'create a SemSegData dataset from a pickle file with configurable sidelength and augmentation options', 'preprocess_raw_schematic': 'preprocess raw voxel schematic data into normalized examples using make_example_from_raw with augmentation', 'flip_rotate_cube': 'randomly flip or rotate a 3D voxel cube tensor for data augmentation across x-z plane', 'fit_schematic_to_sidelength': 'fit and center a voxel schematic into a fixed sidelength cube with random shift augmentation', 'organize_segmentation_classes': 'organize and merge semantic segmentation classes by swallowing rare classes below a minimum occurrence threshold'}
```

## File: facebookresearch_fairo/droidlet/perception/craftassist/voxel_models/semantic_segmentation/generate_data_from_iglu.py

Prompts

```
['create a SemSegData dataset from a pickle file with configurable sidelength and augmentation options', 'preprocess raw voxel schematic data into normalized examples using make_example_from_raw with augmentation', 'randomly flip or rotate a 3D voxel cube tensor for data augmentation across x-z plane', 'fit and center a voxel schematic into a fixed sidelength cube with random shift augmentation', 'organize and merge semantic segmentation classes by swallowing rare classes below a minimum occurrence threshold', 'generate Minecraft shape scenes and save segmentation data as a pickle file using argparse CLI', 'convert a JSON scene description with blocks and instance segmentation tags into numpy segmentation arrays', 'build a Minecraft shape scene with configurable scene size, height, ground depth, and max number of shapes', 'run the CLI tool to generate multiple shape scenes with configurable offsets and save paths', 'review the json_to_segdata function that maps block locations and instance tags to 3D numpy arrays', 'build a 3D convolutional semantic segmentation neural network with configurable embedding and hidden dimensions', 'run the SemSegNet module via argparse CLI to instantiate a model with custom hyperparameters', 'create a SemSegWrapper to load a pretrained model and segment voxel blocks into semantic classes', 'test the SemSegWrapper segment_object method to classify non-air blocks in a voxel grid', 'review the SemSegNet forward pass that embeds block IDs and applies stacked 3D conv layers', 'train a voxel semantic segmentation model on Minecraft block data using PyTorch with configurable epochs and batch size', 'validate a trained semantic segmentation model on validation data and report accuracy metrics', 'run a single training epoch on the semantic segmentation model with masked loss computation', 'extract nonzero voxel blocks from a data sample and return their coordinates and block IDs', 'print input, ground truth, and predicted slices from a semantic segmentation model for debugging']
```

Usage

```
{'generate_shape_scenes': 'generate Minecraft shape scenes and save segmentation data as a pickle file using argparse CLI', 'convert_json_to_segdata': 'convert a JSON scene description with blocks and instance segmentation tags into numpy segmentation arrays', 'build_shape_scene': 'build a Minecraft shape scene with configurable scene size, height, ground depth, and max number of shapes', 'run_scene_generation_cli': 'run the CLI tool to generate multiple shape scenes with configurable offsets and save paths', 'review_json_to_segdata': 'review the json_to_segdata function that maps block locations and instance tags to 3D numpy arrays'}
```

## File: facebookresearch_fairo/droidlet/perception/craftassist/voxel_models/semantic_segmentation/semseg_models.py

Prompts

```
['create a SemSegData dataset from a pickle file with configurable sidelength and augmentation options', 'preprocess raw voxel schematic data into normalized examples using make_example_from_raw with augmentation', 'randomly flip or rotate a 3D voxel cube tensor for data augmentation across x-z plane', 'fit and center a voxel schematic into a fixed sidelength cube with random shift augmentation', 'organize and merge semantic segmentation classes by swallowing rare classes below a minimum occurrence threshold', 'generate Minecraft shape scenes and save segmentation data as a pickle file using argparse CLI', 'convert a JSON scene description with blocks and instance segmentation tags into numpy segmentation arrays', 'build a Minecraft shape scene with configurable scene size, height, ground depth, and max number of shapes', 'run the CLI tool to generate multiple shape scenes with configurable offsets and save paths', 'review the json_to_segdata function that maps block locations and instance tags to 3D numpy arrays', 'build a 3D convolutional semantic segmentation neural network with configurable embedding and hidden dimensions', 'run the SemSegNet module via argparse CLI to instantiate a model with custom hyperparameters', 'create a SemSegWrapper to load a pretrained model and segment voxel blocks into semantic classes', 'test the SemSegWrapper segment_object method to classify non-air blocks in a voxel grid', 'review the SemSegNet forward pass that embeds block IDs and applies stacked 3D conv layers', 'train a voxel semantic segmentation model on Minecraft block data using PyTorch with configurable epochs and batch size', 'validate a trained semantic segmentation model on validation data and report accuracy metrics', 'run a single training epoch on the semantic segmentation model with masked loss computation', 'extract nonzero voxel blocks from a data sample and return their coordinates and block IDs', 'print input, ground truth, and predicted slices from a semantic segmentation model for debugging']
```

Usage

```
{'build_semsegnet': 'build a 3D convolutional semantic segmentation neural network with configurable embedding and hidden dimensions', 'run_semsegnet_cli': 'run the SemSegNet module via argparse CLI to instantiate a model with custom hyperparameters', 'create_semsegwrapper': 'create a SemSegWrapper to load a pretrained model and segment voxel blocks into semantic classes', 'test_segment_object': 'test the SemSegWrapper segment_object method to classify non-air blocks in a voxel grid', 'review_semsegnet_forward': 'review the SemSegNet forward pass that embeds block IDs and applies stacked 3D conv layers'}
```

## File: facebookresearch_fairo/droidlet/perception/craftassist/voxel_models/semantic_segmentation/train_semantic_segmentation.py

Prompts

```
['create a SemSegData dataset from a pickle file with configurable sidelength and augmentation options', 'preprocess raw voxel schematic data into normalized examples using make_example_from_raw with augmentation', 'randomly flip or rotate a 3D voxel cube tensor for data augmentation across x-z plane', 'fit and center a voxel schematic into a fixed sidelength cube with random shift augmentation', 'organize and merge semantic segmentation classes by swallowing rare classes below a minimum occurrence threshold', 'generate Minecraft shape scenes and save segmentation data as a pickle file using argparse CLI', 'convert a JSON scene description with blocks and instance segmentation tags into numpy segmentation arrays', 'build a Minecraft shape scene with configurable scene size, height, ground depth, and max number of shapes', 'run the CLI tool to generate multiple shape scenes with configurable offsets and save paths', 'review the json_to_segdata function that maps block locations and instance tags to 3D numpy arrays', 'build a 3D convolutional semantic segmentation neural network with configurable embedding and hidden dimensions', 'run the SemSegNet module via argparse CLI to instantiate a model with custom hyperparameters', 'create a SemSegWrapper to load a pretrained model and segment voxel blocks into semantic classes', 'test the SemSegWrapper segment_object method to classify non-air blocks in a voxel grid', 'review the SemSegNet forward pass that embeds block IDs and applies stacked 3D conv layers', 'train a voxel semantic segmentation model on Minecraft block data using PyTorch with configurable epochs and batch size', 'validate a trained semantic segmentation model on validation data and report accuracy metrics', 'run a single training epoch on the semantic segmentation model with masked loss computation', 'extract nonzero voxel blocks from a data sample and return their coordinates and block IDs', 'print input, ground truth, and predicted slices from a semantic segmentation model for debugging']
```

Usage

```
{'train_semantic_segmentation_model': 'train a voxel semantic segmentation model on Minecraft block data using PyTorch with configurable epochs and batch size', 'validate_semantic_segmentation_model': 'validate a trained semantic segmentation model on validation data and report accuracy metrics', 'run_train_epoch': 'run a single training epoch on the semantic segmentation model with masked loss computation', 'extract_blocks_from_data': 'extract nonzero voxel blocks from a data sample and return their coordinates and block IDs', 'print_model_slices': 'print input, ground truth, and predicted slices from a semantic segmentation model for debugging'}
```

