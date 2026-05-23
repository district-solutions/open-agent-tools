# Agent Python Tools

- repo: facebookresearch/omnivore
- repo_uri: https://github.com/facebookresearch/omnivore

## File: facebookresearch_omnivore/omnivore/predict.py

Prompts

```
['run the Predictor.predict method to classify an image using the Omnivore model and return top k predicted labels', 'build an Omnivore Swin-B model with a SwinTransformer3D trunk and all classification heads loaded from checkpoint', 'build an Omnivore Swin-L model with a larger SwinTransformer3D trunk and 1536-dimensional head input', 'refactor the omnivore_base function to load a SwinTransformer3D trunk and all heads from a specified checkpoint path', 'review the Predictor.setup method that initializes all five Omnivore models, class name mappings, and image transforms', 'create a DepthNorm module to normalize and clamp the depth channel in a 4-channel RGBD tensor', 'build a TemporalCrop module to split a video tensor into smaller temporal clips with configurable stride', 'create a SpatialCrop module to crop temporally sliced videos into left, center, and right spatial regions', 'build a function to adjust bounding box coordinates by subtracting x and y crop offsets', 'create a function to perform uniform spatial crop on images with optional scaling and bounding box adjustment']
```

Usage

```
{'run_Predictor_predict': 'run the Predictor.predict method to classify an image using the Omnivore model and return top k predicted labels', 'build_omnivore_swinB': 'build an Omnivore Swin-B model with a SwinTransformer3D trunk and all classification heads loaded from checkpoint', 'build_omnivore_swinL': 'build an Omnivore Swin-L model with a larger SwinTransformer3D trunk and 1536-dimensional head input', 'refactor_omnivore_base': 'refactor the omnivore_base function to load a SwinTransformer3D trunk and all heads from a specified checkpoint path', 'review_Predictor_setup': 'review the Predictor.setup method that initializes all five Omnivore models, class name mappings, and image transforms'}
```

## File: facebookresearch_omnivore/omnivore/transforms.py

Prompts

```
['run the Predictor.predict method to classify an image using the Omnivore model and return top k predicted labels', 'build an Omnivore Swin-B model with a SwinTransformer3D trunk and all classification heads loaded from checkpoint', 'build an Omnivore Swin-L model with a larger SwinTransformer3D trunk and 1536-dimensional head input', 'refactor the omnivore_base function to load a SwinTransformer3D trunk and all heads from a specified checkpoint path', 'review the Predictor.setup method that initializes all five Omnivore models, class name mappings, and image transforms', 'create a DepthNorm module to normalize and clamp the depth channel in a 4-channel RGBD tensor', 'build a TemporalCrop module to split a video tensor into smaller temporal clips with configurable stride', 'create a SpatialCrop module to crop temporally sliced videos into left, center, and right spatial regions', 'build a function to adjust bounding box coordinates by subtracting x and y crop offsets', 'create a function to perform uniform spatial crop on images with optional scaling and bounding box adjustment']
```

Usage

```
{'normalize_depth_channel': 'create a DepthNorm module to normalize and clamp the depth channel in a 4-channel RGBD tensor', 'temporal_crop_video': 'build a TemporalCrop module to split a video tensor into smaller temporal clips with configurable stride', 'spatial_crop_video': 'create a SpatialCrop module to crop temporally sliced videos into left, center, and right spatial regions', 'crop_bounding_boxes': 'build a function to adjust bounding box coordinates by subtracting x and y crop offsets', 'uniform_crop_images': 'create a function to perform uniform spatial crop on images with optional scaling and bounding box adjustment'}
```

