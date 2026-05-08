# Agent Python Tools

- repo: facebookresearch/co3d
- repo_uri: https://github.com/facebookresearch/co3d

## File: facebookresearch_co3d/tests/test_challenge_evaluate.py

Prompts

```
['test the CO3D challenge evaluation pipeline by running unittest on test_challenge_evaluate.py', 'evaluate prediction and ground truth folders and return average and per-example metrics', 'evaluate a single RGBDA prediction against a ground truth target and return iou, psnr, and depth metrics', 'store an RGBDAFrame with image, mask, and depth data to a directory as PNG files', 'load an RGBDAFrame from a directory by reading image, mask, and depth PNG files', 'run the unittest to visualize CO3D dataset point clouds and export rendered images', 'test the TestDatasetVisualize class to render point clouds from CO3D skateboard sequences', 'create a JsonIndexDataset instance with frame and sequence annotation files for CO3D data', 'render a point cloud from camera viewpoints using PyTorch3D with configurable point radius and topk', 'extract and visualize a sequence point cloud from the Implicitron dataset with mask points', 'test the FrameAnnotation dataclass by constructing it with image, mask, and viewpoint fields', 'test the _asdict_rec function to recursively convert a list of dataclasses to dictionaries', 'test the _dataclass_from_dict function to parse dictionaries back into FrameAnnotation dataclasses', 'test _dataclass_from_dict with NamedTuple, tuple, list, and dict collections enclosing dataclasses', 'test the ViewpointAnnotation dataclass with rotation matrix, translation, principal point, and focal length']
```

Usage

```
{'test_challenge_evaluation_pipeline': 'test the CO3D challenge evaluation pipeline by running unittest on test_challenge_evaluate.py', 'evaluate_file_folders': 'evaluate prediction and ground truth folders and return average and per-example metrics', 'eval_one': 'evaluate a single RGBDA prediction against a ground truth target and return iou, psnr, and depth metrics', 'store_rgbda_frame': 'store an RGBDAFrame with image, mask, and depth data to a directory as PNG files', 'load_rgbda_frame': 'load an RGBDAFrame from a directory by reading image, mask, and depth PNG files'}
```

## File: facebookresearch_co3d/tests/test_dataset_visualize.py

Prompts

```
['test the CO3D challenge evaluation pipeline by running unittest on test_challenge_evaluate.py', 'evaluate prediction and ground truth folders and return average and per-example metrics', 'evaluate a single RGBDA prediction against a ground truth target and return iou, psnr, and depth metrics', 'store an RGBDAFrame with image, mask, and depth data to a directory as PNG files', 'load an RGBDAFrame from a directory by reading image, mask, and depth PNG files', 'run the unittest to visualize CO3D dataset point clouds and export rendered images', 'test the TestDatasetVisualize class to render point clouds from CO3D skateboard sequences', 'create a JsonIndexDataset instance with frame and sequence annotation files for CO3D data', 'render a point cloud from camera viewpoints using PyTorch3D with configurable point radius and topk', 'extract and visualize a sequence point cloud from the Implicitron dataset with mask points', 'test the FrameAnnotation dataclass by constructing it with image, mask, and viewpoint fields', 'test the _asdict_rec function to recursively convert a list of dataclasses to dictionaries', 'test the _dataclass_from_dict function to parse dictionaries back into FrameAnnotation dataclasses', 'test _dataclass_from_dict with NamedTuple, tuple, list, and dict collections enclosing dataclasses', 'test the ViewpointAnnotation dataclass with rotation matrix, translation, principal point, and focal length']
```

Usage

```
{'run_test_dataset_visualize': 'run the unittest to visualize CO3D dataset point clouds and export rendered images', 'test_TestDatasetVisualize': 'test the TestDatasetVisualize class to render point clouds from CO3D skateboard sequences', 'create_JsonIndexDataset': 'create a JsonIndexDataset instance with frame and sequence annotation files for CO3D data', 'render_render_point_cloud_pytorch3d': 'render a point cloud from camera viewpoints using PyTorch3D with configurable point radius and topk', 'visualize_get_implicitron_sequence_pointcloud': 'extract and visualize a sequence point cloud from the Implicitron dataset with mask points'}
```

## File: facebookresearch_co3d/tests/test_types.py

Prompts

```
['test the CO3D challenge evaluation pipeline by running unittest on test_challenge_evaluate.py', 'evaluate prediction and ground truth folders and return average and per-example metrics', 'evaluate a single RGBDA prediction against a ground truth target and return iou, psnr, and depth metrics', 'store an RGBDAFrame with image, mask, and depth data to a directory as PNG files', 'load an RGBDAFrame from a directory by reading image, mask, and depth PNG files', 'run the unittest to visualize CO3D dataset point clouds and export rendered images', 'test the TestDatasetVisualize class to render point clouds from CO3D skateboard sequences', 'create a JsonIndexDataset instance with frame and sequence annotation files for CO3D data', 'render a point cloud from camera viewpoints using PyTorch3D with configurable point radius and topk', 'extract and visualize a sequence point cloud from the Implicitron dataset with mask points', 'test the FrameAnnotation dataclass by constructing it with image, mask, and viewpoint fields', 'test the _asdict_rec function to recursively convert a list of dataclasses to dictionaries', 'test the _dataclass_from_dict function to parse dictionaries back into FrameAnnotation dataclasses', 'test _dataclass_from_dict with NamedTuple, tuple, list, and dict collections enclosing dataclasses', 'test the ViewpointAnnotation dataclass with rotation matrix, translation, principal point, and focal length']
```

Usage

```
{'test_FrameAnnotation_dataclass': 'test the FrameAnnotation dataclass by constructing it with image, mask, and viewpoint fields', 'test_asdict_rec_function': 'test the _asdict_rec function to recursively convert a list of dataclasses to dictionaries', 'test_dataclass_from_dict_parsing': 'test the _dataclass_from_dict function to parse dictionaries back into FrameAnnotation dataclasses', 'test_dataclass_from_dict_collections': 'test _dataclass_from_dict with NamedTuple, tuple, list, and dict collections enclosing dataclasses', 'test_ViewpointAnnotation_fields': 'test the ViewpointAnnotation dataclass with rotation matrix, translation, principal point, and focal length'}
```

