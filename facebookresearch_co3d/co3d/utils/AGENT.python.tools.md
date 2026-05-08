# Agent Python Tools

- repo: facebookresearch/co3d
- repo_uri: https://github.com/facebookresearch/co3d

## File: facebookresearch_co3d/co3d/utils/dbir_utils.py

Prompts

```
['render a PyTorch3D point cloud to a camera view and return an ImplicitronRender object', 'paste a cropped render back into the original image coordinate frame using FrameData', 'generate a 3D point cloud for a CO3D dataset sequence by unprojecting depth maps', 'generate a point cloud by unprojecting depth maps from a FrameData object', 'subsample a PyTorch3D Pointclouds object to a maximum number of points randomly', 'evaluate multiple Implicitron models across CO3Dv2 categories and subsets then submit results to EvalAI', 'evaluate a single Implicitron experiment directory on a CO3Dv2 category and subset and dump results to JSON', 'render new view predictions for a CO3D category subset using an Implicitron model and add results to a submission', 'load a trained Implicitron GenericModel from an experiment directory checkpoint and set it to eval mode', 'obtain a DatasetMap containing train val and test dataset objects for a CO3Dv2 category and subset']
```

Usage

```
{'render_point_cloud': 'render a PyTorch3D point cloud to a camera view and return an ImplicitronRender object', 'paste_render_to_original_image': 'paste a cropped render back into the original image coordinate frame using FrameData', 'get_sequence_pointcloud': 'generate a 3D point cloud for a CO3D dataset sequence by unprojecting depth maps', 'get_eval_frame_data_pointcloud': 'generate a point cloud by unprojecting depth maps from a FrameData object', 'subsample_pointcloud': 'subsample a PyTorch3D Pointclouds object to a maximum number of points randomly'}
```

## File: facebookresearch_co3d/co3d/utils/evaluate_implicitron_model.py

Prompts

```
['render a PyTorch3D point cloud to a camera view and return an ImplicitronRender object', 'paste a cropped render back into the original image coordinate frame using FrameData', 'generate a 3D point cloud for a CO3D dataset sequence by unprojecting depth maps', 'generate a point cloud by unprojecting depth maps from a FrameData object', 'subsample a PyTorch3D Pointclouds object to a maximum number of points randomly', 'evaluate multiple Implicitron models across CO3Dv2 categories and subsets then submit results to EvalAI', 'evaluate a single Implicitron experiment directory on a CO3Dv2 category and subset and dump results to JSON', 'render new view predictions for a CO3D category subset using an Implicitron model and add results to a submission', 'load a trained Implicitron GenericModel from an experiment directory checkpoint and set it to eval mode', 'obtain a DatasetMap containing train val and test dataset objects for a CO3Dv2 category and subset']
```

Usage

```
{'evaluate_implicitron_exp_dir_map': 'evaluate multiple Implicitron models across CO3Dv2 categories and subsets then submit results to EvalAI', 'evaluate_implicitron_exp_dir': 'evaluate a single Implicitron experiment directory on a CO3Dv2 category and subset and dump results to JSON', 'update_implicitron_submission_with_category_and_subset_predictions': 'render new view predictions for a CO3D category subset using an Implicitron model and add results to a submission', 'load_model_from_implicitron_exp_dir': 'load a trained Implicitron GenericModel from an experiment directory checkpoint and set it to eval mode', 'get_dataset_map': 'obtain a DatasetMap containing train val and test dataset objects for a CO3Dv2 category and subset'}
```

