# Agent Python Tools

- repo: facebookresearch/mmf
- repo_uri: https://github.com/facebookresearch/mmf

## File: facebookresearch_mmf/tools/scripts/features/frcnn/extract_features_frcnn.py

Prompts

```
['run the FeatureExtractor to extract FRCNN features from images in a directory and save to output folder', 'build a GeneralizedRCNN detection model from a pretrained model file and config using _build_detection_model', 'extract FRCNN object detection features from a list of image paths using get_frcnn_features', 'process raw FRCNN features by filtering confidence thresholds and extracting ROI features via _process_features', 'save extracted features as numpy arrays to the output folder using _save_feature', 'load Visual Genome object and attribute labels from objects.txt and attributes.txt files into lists', 'load a Detectron2 pickle checkpoint file and convert numpy arrays to PyTorch tensors', 'create a Config object from a pretrained model name or path by loading its config.yaml', 'download and cache a remote URL or resolve a local file path with optional archive extraction', 'fetch data from a local file or remote URL and parse it into a Python object', 'build a GeneralizedRCNN model from a pretrained checkpoint using from_pretrained with a config path', 'run object detection inference on images using GeneralizedRCNN to get boxes, classes, and ROI features', 'build a ResNet backbone network from a config using build_backbone with specified depth and norm', 'create a Box2BoxTransform to compute deltas between source and target bounding boxes for regression', 'generate anchors for region proposal using AnchorGenerator with configurable sizes and aspect ratios', 'build a python module that uses Preprocess to resize, normalize, and pad images for Faster R-CNN feature extraction', 'create a function that calls Preprocess on a list of images and returns padded tensors with scale factors', 'test the Preprocess pad method to verify images are padded to uniform size and stacked into a tensor', 'refactor the _scale_box function to scale bounding box coordinates by a given yx scale factor', 'review the _clip_box function that clamps bounding box coordinates to valid image dimensions']
```

Usage

```
{'run_feature_extraction': 'run the FeatureExtractor to extract FRCNN features from images in a directory and save to output folder', 'build_detection_model': 'build a GeneralizedRCNN detection model from a pretrained model file and config using _build_detection_model', 'extract_frcnn_features': 'extract FRCNN object detection features from a list of image paths using get_frcnn_features', 'process_features': 'process raw FRCNN features by filtering confidence thresholds and extracting ROI features via _process_features', 'save_features': 'save extracted features as numpy arrays to the output folder using _save_feature'}
```

## File: facebookresearch_mmf/tools/scripts/features/frcnn/frcnn_utils.py

Prompts

```
['run the FeatureExtractor to extract FRCNN features from images in a directory and save to output folder', 'build a GeneralizedRCNN detection model from a pretrained model file and config using _build_detection_model', 'extract FRCNN object detection features from a list of image paths using get_frcnn_features', 'process raw FRCNN features by filtering confidence thresholds and extracting ROI features via _process_features', 'save extracted features as numpy arrays to the output folder using _save_feature', 'load Visual Genome object and attribute labels from objects.txt and attributes.txt files into lists', 'load a Detectron2 pickle checkpoint file and convert numpy arrays to PyTorch tensors', 'create a Config object from a pretrained model name or path by loading its config.yaml', 'download and cache a remote URL or resolve a local file path with optional archive extraction', 'fetch data from a local file or remote URL and parse it into a Python object', 'build a GeneralizedRCNN model from a pretrained checkpoint using from_pretrained with a config path', 'run object detection inference on images using GeneralizedRCNN to get boxes, classes, and ROI features', 'build a ResNet backbone network from a config using build_backbone with specified depth and norm', 'create a Box2BoxTransform to compute deltas between source and target bounding boxes for regression', 'generate anchors for region proposal using AnchorGenerator with configurable sizes and aspect ratios', 'build a python module that uses Preprocess to resize, normalize, and pad images for Faster R-CNN feature extraction', 'create a function that calls Preprocess on a list of images and returns padded tensors with scale factors', 'test the Preprocess pad method to verify images are padded to uniform size and stacked into a tensor', 'refactor the _scale_box function to scale bounding box coordinates by a given yx scale factor', 'review the _clip_box function that clamps bounding box coordinates to valid image dimensions']
```

Usage

```
{'load_labels': 'load Visual Genome object and attribute labels from objects.txt and attributes.txt files into lists', 'load_checkpoint': 'load a Detectron2 pickle checkpoint file and convert numpy arrays to PyTorch tensors', 'Config_from_pretrained': 'create a Config object from a pretrained model name or path by loading its config.yaml', 'cached_path': 'download and cache a remote URL or resolve a local file path with optional archive extraction', 'get_data': 'fetch data from a local file or remote URL and parse it into a Python object'}
```

## File: facebookresearch_mmf/tools/scripts/features/frcnn/modeling_frcnn.py

Prompts

```
['run the FeatureExtractor to extract FRCNN features from images in a directory and save to output folder', 'build a GeneralizedRCNN detection model from a pretrained model file and config using _build_detection_model', 'extract FRCNN object detection features from a list of image paths using get_frcnn_features', 'process raw FRCNN features by filtering confidence thresholds and extracting ROI features via _process_features', 'save extracted features as numpy arrays to the output folder using _save_feature', 'load Visual Genome object and attribute labels from objects.txt and attributes.txt files into lists', 'load a Detectron2 pickle checkpoint file and convert numpy arrays to PyTorch tensors', 'create a Config object from a pretrained model name or path by loading its config.yaml', 'download and cache a remote URL or resolve a local file path with optional archive extraction', 'fetch data from a local file or remote URL and parse it into a Python object', 'build a GeneralizedRCNN model from a pretrained checkpoint using from_pretrained with a config path', 'run object detection inference on images using GeneralizedRCNN to get boxes, classes, and ROI features', 'build a ResNet backbone network from a config using build_backbone with specified depth and norm', 'create a Box2BoxTransform to compute deltas between source and target bounding boxes for regression', 'generate anchors for region proposal using AnchorGenerator with configurable sizes and aspect ratios', 'build a python module that uses Preprocess to resize, normalize, and pad images for Faster R-CNN feature extraction', 'create a function that calls Preprocess on a list of images and returns padded tensors with scale factors', 'test the Preprocess pad method to verify images are padded to uniform size and stacked into a tensor', 'refactor the _scale_box function to scale bounding box coordinates by a given yx scale factor', 'review the _clip_box function that clamps bounding box coordinates to valid image dimensions']
```

Usage

```
{'build_frcnn_model_from_pretrained': 'build a GeneralizedRCNN model from a pretrained checkpoint using from_pretrained with a config path', 'run_frcnn_inference': 'run object detection inference on images using GeneralizedRCNN to get boxes, classes, and ROI features', 'build_resnet_backbone': 'build a ResNet backbone network from a config using build_backbone with specified depth and norm', 'create_box2box_transform': 'create a Box2BoxTransform to compute deltas between source and target bounding boxes for regression', 'generate_rpn_anchors': 'generate anchors for region proposal using AnchorGenerator with configurable sizes and aspect ratios'}
```

## File: facebookresearch_mmf/tools/scripts/features/frcnn/processing_image.py

Prompts

```
['run the FeatureExtractor to extract FRCNN features from images in a directory and save to output folder', 'build a GeneralizedRCNN detection model from a pretrained model file and config using _build_detection_model', 'extract FRCNN object detection features from a list of image paths using get_frcnn_features', 'process raw FRCNN features by filtering confidence thresholds and extracting ROI features via _process_features', 'save extracted features as numpy arrays to the output folder using _save_feature', 'load Visual Genome object and attribute labels from objects.txt and attributes.txt files into lists', 'load a Detectron2 pickle checkpoint file and convert numpy arrays to PyTorch tensors', 'create a Config object from a pretrained model name or path by loading its config.yaml', 'download and cache a remote URL or resolve a local file path with optional archive extraction', 'fetch data from a local file or remote URL and parse it into a Python object', 'build a GeneralizedRCNN model from a pretrained checkpoint using from_pretrained with a config path', 'run object detection inference on images using GeneralizedRCNN to get boxes, classes, and ROI features', 'build a ResNet backbone network from a config using build_backbone with specified depth and norm', 'create a Box2BoxTransform to compute deltas between source and target bounding boxes for regression', 'generate anchors for region proposal using AnchorGenerator with configurable sizes and aspect ratios', 'build a python module that uses Preprocess to resize, normalize, and pad images for Faster R-CNN feature extraction', 'create a function that calls Preprocess on a list of images and returns padded tensors with scale factors', 'test the Preprocess pad method to verify images are padded to uniform size and stacked into a tensor', 'refactor the _scale_box function to scale bounding box coordinates by a given yx scale factor', 'review the _clip_box function that clamps bounding box coordinates to valid image dimensions']
```

Usage

```
{'build_preprocess_images': 'build a python module that uses Preprocess to resize, normalize, and pad images for Faster R-CNN feature extraction', 'create_preprocess_call': 'create a function that calls Preprocess on a list of images and returns padded tensors with scale factors', 'test_preprocess_pad': 'test the Preprocess pad method to verify images are padded to uniform size and stacked into a tensor', 'refactor_scale_box': 'refactor the _scale_box function to scale bounding box coordinates by a given yx scale factor', 'review_clip_box': 'review the _clip_box function that clamps bounding box coordinates to valid image dimensions'}
```

