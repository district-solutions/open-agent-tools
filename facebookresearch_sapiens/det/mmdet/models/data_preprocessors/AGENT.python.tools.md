# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/det/mmdet/models/data_preprocessors/data_preprocessor.py

Prompts

```
['build a DetDataPreprocessor to normalize, pad, and convert BGR to RGB for detection tasks', 'create a BatchSyncRandomResize module to synchronize random resize across distributed training ranks', 'create a BatchFixedSizePad module to pad batch images to a fixed target size', 'create a MultiBranchDataPreprocessor to preprocess multi-branch data for semi-supervised object detection', 'create a BoxInstDataPreprocessor to generate pseudo masks using box annotations and color similarity', 'create a ReIDDataPreprocessor instance with mean, std, and num_classes for image normalization', 'run the ReIDDataPreprocessor forward pass to normalize, pad, and augment a batch of images', 'review the ReIDDataPreprocessor constructor to configure BGR to RGB conversion and one-hot label generation', 'test the stack_batch_scores function to stack LabelData score fields into a single tensor', 'refactor the ReIDDataPreprocessor to customize mixup and cutmix batch augmentation settings', 'create a TrackDataPreprocessor instance with mean, std, and pad_size_divisor for video tracking data preprocessing', 'run the TrackDataPreprocessor forward pass to normalize, pad, and stack batch sequence images for tracking models', 'build a batch of padded sequence images by stacking TCHW tensors into an NTCHW 5D tensor with right bottom padding', 'review the TrackDataPreprocessor constructor to configure mean/std buffers and use_det_processor flag for training mode', 'test the pad_track_gt_masks method to pad ground truth instance masks to match batch input shape']
```

Usage

```
{'build_DetDataPreprocessor': 'build a DetDataPreprocessor to normalize, pad, and convert BGR to RGB for detection tasks', 'create_BatchSyncRandomResize': 'create a BatchSyncRandomResize module to synchronize random resize across distributed training ranks', 'create_BatchFixedSizePad': 'create a BatchFixedSizePad module to pad batch images to a fixed target size', 'create_MultiBranchDataPreprocessor': 'create a MultiBranchDataPreprocessor to preprocess multi-branch data for semi-supervised object detection', 'create_BoxInstDataPreprocessor': 'create a BoxInstDataPreprocessor to generate pseudo masks using box annotations and color similarity'}
```

## File: facebookresearch_sapiens/det/mmdet/models/data_preprocessors/reid_data_preprocessor.py

Prompts

```
['build a DetDataPreprocessor to normalize, pad, and convert BGR to RGB for detection tasks', 'create a BatchSyncRandomResize module to synchronize random resize across distributed training ranks', 'create a BatchFixedSizePad module to pad batch images to a fixed target size', 'create a MultiBranchDataPreprocessor to preprocess multi-branch data for semi-supervised object detection', 'create a BoxInstDataPreprocessor to generate pseudo masks using box annotations and color similarity', 'create a ReIDDataPreprocessor instance with mean, std, and num_classes for image normalization', 'run the ReIDDataPreprocessor forward pass to normalize, pad, and augment a batch of images', 'review the ReIDDataPreprocessor constructor to configure BGR to RGB conversion and one-hot label generation', 'test the stack_batch_scores function to stack LabelData score fields into a single tensor', 'refactor the ReIDDataPreprocessor to customize mixup and cutmix batch augmentation settings', 'create a TrackDataPreprocessor instance with mean, std, and pad_size_divisor for video tracking data preprocessing', 'run the TrackDataPreprocessor forward pass to normalize, pad, and stack batch sequence images for tracking models', 'build a batch of padded sequence images by stacking TCHW tensors into an NTCHW 5D tensor with right bottom padding', 'review the TrackDataPreprocessor constructor to configure mean/std buffers and use_det_processor flag for training mode', 'test the pad_track_gt_masks method to pad ground truth instance masks to match batch input shape']
```

Usage

```
{'create_ReIDDataPreprocessor': 'create a ReIDDataPreprocessor instance with mean, std, and num_classes for image normalization', 'run_ReIDDataPreprocessor_forward': 'run the ReIDDataPreprocessor forward pass to normalize, pad, and augment a batch of images', 'review_ReIDDataPreprocessor_init': 'review the ReIDDataPreprocessor constructor to configure BGR to RGB conversion and one-hot label generation', 'test_stack_batch_scores': 'test the stack_batch_scores function to stack LabelData score fields into a single tensor', 'refactor_ReIDDataPreprocessor_batch_augments': 'refactor the ReIDDataPreprocessor to customize mixup and cutmix batch augmentation settings'}
```

## File: facebookresearch_sapiens/det/mmdet/models/data_preprocessors/track_data_preprocessor.py

Prompts

```
['build a DetDataPreprocessor to normalize, pad, and convert BGR to RGB for detection tasks', 'create a BatchSyncRandomResize module to synchronize random resize across distributed training ranks', 'create a BatchFixedSizePad module to pad batch images to a fixed target size', 'create a MultiBranchDataPreprocessor to preprocess multi-branch data for semi-supervised object detection', 'create a BoxInstDataPreprocessor to generate pseudo masks using box annotations and color similarity', 'create a ReIDDataPreprocessor instance with mean, std, and num_classes for image normalization', 'run the ReIDDataPreprocessor forward pass to normalize, pad, and augment a batch of images', 'review the ReIDDataPreprocessor constructor to configure BGR to RGB conversion and one-hot label generation', 'test the stack_batch_scores function to stack LabelData score fields into a single tensor', 'refactor the ReIDDataPreprocessor to customize mixup and cutmix batch augmentation settings', 'create a TrackDataPreprocessor instance with mean, std, and pad_size_divisor for video tracking data preprocessing', 'run the TrackDataPreprocessor forward pass to normalize, pad, and stack batch sequence images for tracking models', 'build a batch of padded sequence images by stacking TCHW tensors into an NTCHW 5D tensor with right bottom padding', 'review the TrackDataPreprocessor constructor to configure mean/std buffers and use_det_processor flag for training mode', 'test the pad_track_gt_masks method to pad ground truth instance masks to match batch input shape']
```

Usage

```
{'create_TrackDataPreprocessor': 'create a TrackDataPreprocessor instance with mean, std, and pad_size_divisor for video tracking data preprocessing', 'run_TrackDataPreprocessor_forward': 'run the TrackDataPreprocessor forward pass to normalize, pad, and stack batch sequence images for tracking models', 'build_stack_track_batch': 'build a batch of padded sequence images by stacking TCHW tensors into an NTCHW 5D tensor with right bottom padding', 'review_TrackDataPreprocessor_init': 'review the TrackDataPreprocessor constructor to configure mean/std buffers and use_det_processor flag for training mode', 'test_pad_track_gt_masks': 'test the pad_track_gt_masks method to pad ground truth instance masks to match batch input shape'}
```

