# Agent Python Tools

- repo: facebookresearch/maskrcnn-benchmark
- repo_uri: https://github.com/facebookresearch/maskrcnn-benchmark

## File: facebookresearch_maskrcnn-benchmark/maskrcnn_benchmark/modeling/detector/detectors.py

Prompts

```
['build a detection model by calling build_detection_model with a config object that has MODEL.META_ARCHITECTURE set', 'review the _DETECTION_META_ARCHITECTURES registry mapping GeneralizedRCNN to its class for object detection', 'refactor build_detection_model to support additional meta-architecture types beyond GeneralizedRCNN', 'test build_detection_model by passing a mock config with MODEL.META_ARCHITECTURE set to GeneralizedRCNN', 'summarize the detectors module which provides a factory function to instantiate detection meta-architectures from config', 'build a GeneralizedRCNN model from a config that includes backbone, RPN, and ROI heads', 'run the GeneralizedRCNN forward pass in training mode with images and targets to get losses', 'run the GeneralizedRCNN forward pass in inference mode with images to get detections and masks', 'review the GeneralizedRCNN class architecture consisting of backbone, RPN, and ROI heads components', 'refactor the GeneralizedRCNN forward method to handle RPN-only models without ROI heads']
```

Usage

```
{'build_detection_model': 'build a detection model by calling build_detection_model with a config object that has MODEL.META_ARCHITECTURE set', 'review_DETECTION_META_ARCHITECTURES': 'review the _DETECTION_META_ARCHITECTURES registry mapping GeneralizedRCNN to its class for object detection', 'refactor_build_detection_model': 'refactor build_detection_model to support additional meta-architecture types beyond GeneralizedRCNN', 'test_build_detection_model': 'test build_detection_model by passing a mock config with MODEL.META_ARCHITECTURE set to GeneralizedRCNN', 'summarize_detectors_module': 'summarize the detectors module which provides a factory function to instantiate detection meta-architectures from config'}
```

## File: facebookresearch_maskrcnn-benchmark/maskrcnn_benchmark/modeling/detector/generalized_rcnn.py

Prompts

```
['build a detection model by calling build_detection_model with a config object that has MODEL.META_ARCHITECTURE set', 'review the _DETECTION_META_ARCHITECTURES registry mapping GeneralizedRCNN to its class for object detection', 'refactor build_detection_model to support additional meta-architecture types beyond GeneralizedRCNN', 'test build_detection_model by passing a mock config with MODEL.META_ARCHITECTURE set to GeneralizedRCNN', 'summarize the detectors module which provides a factory function to instantiate detection meta-architectures from config', 'build a GeneralizedRCNN model from a config that includes backbone, RPN, and ROI heads', 'run the GeneralizedRCNN forward pass in training mode with images and targets to get losses', 'run the GeneralizedRCNN forward pass in inference mode with images to get detections and masks', 'review the GeneralizedRCNN class architecture consisting of backbone, RPN, and ROI heads components', 'refactor the GeneralizedRCNN forward method to handle RPN-only models without ROI heads']
```

Usage

```
{'build_GeneralizedRCNN': 'build a GeneralizedRCNN model from a config that includes backbone, RPN, and ROI heads', 'run_GeneralizedRCNN_forward_training': 'run the GeneralizedRCNN forward pass in training mode with images and targets to get losses', 'run_GeneralizedRCNN_forward_inference': 'run the GeneralizedRCNN forward pass in inference mode with images to get detections and masks', 'review_GeneralizedRCNN_architecture': 'review the GeneralizedRCNN class architecture consisting of backbone, RPN, and ROI heads components', 'refactor_GeneralizedRCNN_forward': 'refactor the GeneralizedRCNN forward method to handle RPN-only models without ROI heads'}
```

