# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/seg/mmseg/apis/inference.py

Prompts

```
['initialize a segmentation model from a config file and optional checkpoint weights', 'run inference on an image with a loaded segmentation model to get predictions', 'run stereo pointmap inference on a pair of images with a segmentation model', 'visualize segmentation results by overlaying predictions on the original image with labels', 'review the init_model function to understand how checkpoints and dataset metadata are loaded', 'run semantic segmentation inference on images using MMSegInferencer with a pretrained model and config file', 'visualize segmentation predictions with configurable opacity and save rendered masks to an output directory', 'load model weights and dataset metadata from a checkpoint file into a segmentation model', 'initialize a test data processing pipeline by replacing LoadImageFromFile with InferencerLoader transform', 'postprocess segmentation predictions and save predicted masks as PNG or NPY files to disk', 'run remote sensing inference on a GeoTIFF image using RSInferencer.from_config_path with a model config and checkpoint', 'run remote sensing inference on a GeoTIFF image using RSInferencer.from_model with an existing BaseModel', 'create sliding window grids for a remote sensing image using RSImage.create_grids with a specified window size and stride', 'read remote sensing image data from a GeoTIFF file using RSImage.read with an optional grid region', 'create a segmentation map GeoTIFF output file using RSImage.create_seg_map with a specified output path']
```

Usage

```
{'init_model': 'initialize a segmentation model from a config file and optional checkpoint weights', 'inference_model': 'run inference on an image with a loaded segmentation model to get predictions', 'stereo_pointmap_inference_model': 'run stereo pointmap inference on a pair of images with a segmentation model', 'show_result_pyplot': 'visualize segmentation results by overlaying predictions on the original image with labels', 'review_init_model': 'review the init_model function to understand how checkpoints and dataset metadata are loaded'}
```

## File: facebookresearch_sapiens/seg/mmseg/apis/mmseg_inferencer.py

Prompts

```
['initialize a segmentation model from a config file and optional checkpoint weights', 'run inference on an image with a loaded segmentation model to get predictions', 'run stereo pointmap inference on a pair of images with a segmentation model', 'visualize segmentation results by overlaying predictions on the original image with labels', 'review the init_model function to understand how checkpoints and dataset metadata are loaded', 'run semantic segmentation inference on images using MMSegInferencer with a pretrained model and config file', 'visualize segmentation predictions with configurable opacity and save rendered masks to an output directory', 'load model weights and dataset metadata from a checkpoint file into a segmentation model', 'initialize a test data processing pipeline by replacing LoadImageFromFile with InferencerLoader transform', 'postprocess segmentation predictions and save predicted masks as PNG or NPY files to disk', 'run remote sensing inference on a GeoTIFF image using RSInferencer.from_config_path with a model config and checkpoint', 'run remote sensing inference on a GeoTIFF image using RSInferencer.from_model with an existing BaseModel', 'create sliding window grids for a remote sensing image using RSImage.create_grids with a specified window size and stride', 'read remote sensing image data from a GeoTIFF file using RSImage.read with an optional grid region', 'create a segmentation map GeoTIFF output file using RSImage.create_seg_map with a specified output path']
```

Usage

```
{'run_semantic_segmentation_inference': 'run semantic segmentation inference on images using MMSegInferencer with a pretrained model and config file', 'visualize_segmentation_predictions': 'visualize segmentation predictions with configurable opacity and save rendered masks to an output directory', 'load_checkpoint_weights_to_model': 'load model weights and dataset metadata from a checkpoint file into a segmentation model', 'initialize_test_pipeline': 'initialize a test data processing pipeline by replacing LoadImageFromFile with InferencerLoader transform', 'postprocess_segmentation_results': 'postprocess segmentation predictions and save predicted masks as PNG or NPY files to disk'}
```

## File: facebookresearch_sapiens/seg/mmseg/apis/remote_sense_inferencer.py

Prompts

```
['initialize a segmentation model from a config file and optional checkpoint weights', 'run inference on an image with a loaded segmentation model to get predictions', 'run stereo pointmap inference on a pair of images with a segmentation model', 'visualize segmentation results by overlaying predictions on the original image with labels', 'review the init_model function to understand how checkpoints and dataset metadata are loaded', 'run semantic segmentation inference on images using MMSegInferencer with a pretrained model and config file', 'visualize segmentation predictions with configurable opacity and save rendered masks to an output directory', 'load model weights and dataset metadata from a checkpoint file into a segmentation model', 'initialize a test data processing pipeline by replacing LoadImageFromFile with InferencerLoader transform', 'postprocess segmentation predictions and save predicted masks as PNG or NPY files to disk', 'run remote sensing inference on a GeoTIFF image using RSInferencer.from_config_path with a model config and checkpoint', 'run remote sensing inference on a GeoTIFF image using RSInferencer.from_model with an existing BaseModel', 'create sliding window grids for a remote sensing image using RSImage.create_grids with a specified window size and stride', 'read remote sensing image data from a GeoTIFF file using RSImage.read with an optional grid region', 'create a segmentation map GeoTIFF output file using RSImage.create_seg_map with a specified output path']
```

Usage

```
{'run_RSInferencer_from_config': 'run remote sensing inference on a GeoTIFF image using RSInferencer.from_config_path with a model config and checkpoint', 'run_RSInferencer_from_model': 'run remote sensing inference on a GeoTIFF image using RSInferencer.from_model with an existing BaseModel', 'create_RSImage_grids': 'create sliding window grids for a remote sensing image using RSImage.create_grids with a specified window size and stride', 'read_RSImage_data': 'read remote sensing image data from a GeoTIFF file using RSImage.read with an optional grid region', 'create_RSImage_seg_map': 'create a segmentation map GeoTIFF output file using RSImage.create_seg_map with a specified output path'}
```

