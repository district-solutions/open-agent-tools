# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/det/mmdet/models/reid/base_reid.py

Prompts

```
['build a BaseReID model for person re-identification using mmpretrain ImageClassifier', 'run the BaseReID forward pass in tensor mode to get raw feature embeddings', 'run the BaseReID forward pass in predict mode to get ReIDDataSample predictions', 'run the BaseReID forward pass in loss mode to compute re-identification losses', 'review the BaseReID forward method that handles 5D video and 4D image inputs', 'build a FcModule with input and output channels using default ReLU activation', 'build a FcModule with batch normalization and ReLU activation for feature transformation', 'run the FcModule forward pass on input tensor with optional activation and normalization', 'review the FcModule constructor to understand norm_cfg and act_cfg configuration options', 'refactor the FcModule to swap ReLU activation with a different activation type', 'build a GlobalAveragePooling neck module for ReID models using AdaptiveAvgPool2d', 'create a GlobalAveragePooling module with custom kernel_size and stride parameters', 'test the GlobalAveragePooling forward pass with a single torch.Tensor input', 'test the GlobalAveragePooling forward pass with a tuple of tensor inputs', 'review the GlobalAveragePooling forward method view reshaping logic for batch safety', 'build a LinearReIDHead with configurable fc layers, normalization, and activation for person re-identification', 'review the LinearReIDHead __init__ to understand loss configuration and top-k accuracy validation logic', 'test the LinearReIDHead forward method by passing multi-stage feature tuples and verifying output tensor shape', 'refactor the LinearReIDHead loss method to support additional loss types beyond cross entropy and triplet loss', 'summarize the LinearReIDHead predict method that extracts features and attaches them to ReIDDataSample objects']
```

Usage

```
{'build_BaseReID_model': 'build a BaseReID model for person re-identification using mmpretrain ImageClassifier', 'run_BaseReID_forward_tensor': 'run the BaseReID forward pass in tensor mode to get raw feature embeddings', 'run_BaseReID_forward_predict': 'run the BaseReID forward pass in predict mode to get ReIDDataSample predictions', 'run_BaseReID_forward_loss': 'run the BaseReID forward pass in loss mode to compute re-identification losses', 'review_BaseReID_forward': 'review the BaseReID forward method that handles 5D video and 4D image inputs'}
```

## File: facebookresearch_sapiens/det/mmdet/models/reid/fc_module.py

Prompts

```
['build a BaseReID model for person re-identification using mmpretrain ImageClassifier', 'run the BaseReID forward pass in tensor mode to get raw feature embeddings', 'run the BaseReID forward pass in predict mode to get ReIDDataSample predictions', 'run the BaseReID forward pass in loss mode to compute re-identification losses', 'review the BaseReID forward method that handles 5D video and 4D image inputs', 'build a FcModule with input and output channels using default ReLU activation', 'build a FcModule with batch normalization and ReLU activation for feature transformation', 'run the FcModule forward pass on input tensor with optional activation and normalization', 'review the FcModule constructor to understand norm_cfg and act_cfg configuration options', 'refactor the FcModule to swap ReLU activation with a different activation type', 'build a GlobalAveragePooling neck module for ReID models using AdaptiveAvgPool2d', 'create a GlobalAveragePooling module with custom kernel_size and stride parameters', 'test the GlobalAveragePooling forward pass with a single torch.Tensor input', 'test the GlobalAveragePooling forward pass with a tuple of tensor inputs', 'review the GlobalAveragePooling forward method view reshaping logic for batch safety', 'build a LinearReIDHead with configurable fc layers, normalization, and activation for person re-identification', 'review the LinearReIDHead __init__ to understand loss configuration and top-k accuracy validation logic', 'test the LinearReIDHead forward method by passing multi-stage feature tuples and verifying output tensor shape', 'refactor the LinearReIDHead loss method to support additional loss types beyond cross entropy and triplet loss', 'summarize the LinearReIDHead predict method that extracts features and attaches them to ReIDDataSample objects']
```

Usage

```
{'build_FcModule_basic': 'build a FcModule with input and output channels using default ReLU activation', 'build_FcModule_with_norm': 'build a FcModule with batch normalization and ReLU activation for feature transformation', 'run_FcModule_forward': 'run the FcModule forward pass on input tensor with optional activation and normalization', 'review_FcModule_init': 'review the FcModule constructor to understand norm_cfg and act_cfg configuration options', 'refactor_FcModule_activation': 'refactor the FcModule to swap ReLU activation with a different activation type'}
```

## File: facebookresearch_sapiens/det/mmdet/models/reid/gap.py

Prompts

```
['build a BaseReID model for person re-identification using mmpretrain ImageClassifier', 'run the BaseReID forward pass in tensor mode to get raw feature embeddings', 'run the BaseReID forward pass in predict mode to get ReIDDataSample predictions', 'run the BaseReID forward pass in loss mode to compute re-identification losses', 'review the BaseReID forward method that handles 5D video and 4D image inputs', 'build a FcModule with input and output channels using default ReLU activation', 'build a FcModule with batch normalization and ReLU activation for feature transformation', 'run the FcModule forward pass on input tensor with optional activation and normalization', 'review the FcModule constructor to understand norm_cfg and act_cfg configuration options', 'refactor the FcModule to swap ReLU activation with a different activation type', 'build a GlobalAveragePooling neck module for ReID models using AdaptiveAvgPool2d', 'create a GlobalAveragePooling module with custom kernel_size and stride parameters', 'test the GlobalAveragePooling forward pass with a single torch.Tensor input', 'test the GlobalAveragePooling forward pass with a tuple of tensor inputs', 'review the GlobalAveragePooling forward method view reshaping logic for batch safety', 'build a LinearReIDHead with configurable fc layers, normalization, and activation for person re-identification', 'review the LinearReIDHead __init__ to understand loss configuration and top-k accuracy validation logic', 'test the LinearReIDHead forward method by passing multi-stage feature tuples and verifying output tensor shape', 'refactor the LinearReIDHead loss method to support additional loss types beyond cross entropy and triplet loss', 'summarize the LinearReIDHead predict method that extracts features and attaches them to ReIDDataSample objects']
```

Usage

```
{'build_GAP_neck': 'build a GlobalAveragePooling neck module for ReID models using AdaptiveAvgPool2d', 'create_GAP_with_kernel': 'create a GlobalAveragePooling module with custom kernel_size and stride parameters', 'test_GAP_forward_tensor': 'test the GlobalAveragePooling forward pass with a single torch.Tensor input', 'test_GAP_forward_tuple': 'test the GlobalAveragePooling forward pass with a tuple of tensor inputs', 'review_GAP_view_logic': 'review the GlobalAveragePooling forward method view reshaping logic for batch safety'}
```

## File: facebookresearch_sapiens/det/mmdet/models/reid/linear_reid_head.py

Prompts

```
['build a BaseReID model for person re-identification using mmpretrain ImageClassifier', 'run the BaseReID forward pass in tensor mode to get raw feature embeddings', 'run the BaseReID forward pass in predict mode to get ReIDDataSample predictions', 'run the BaseReID forward pass in loss mode to compute re-identification losses', 'review the BaseReID forward method that handles 5D video and 4D image inputs', 'build a FcModule with input and output channels using default ReLU activation', 'build a FcModule with batch normalization and ReLU activation for feature transformation', 'run the FcModule forward pass on input tensor with optional activation and normalization', 'review the FcModule constructor to understand norm_cfg and act_cfg configuration options', 'refactor the FcModule to swap ReLU activation with a different activation type', 'build a GlobalAveragePooling neck module for ReID models using AdaptiveAvgPool2d', 'create a GlobalAveragePooling module with custom kernel_size and stride parameters', 'test the GlobalAveragePooling forward pass with a single torch.Tensor input', 'test the GlobalAveragePooling forward pass with a tuple of tensor inputs', 'review the GlobalAveragePooling forward method view reshaping logic for batch safety', 'build a LinearReIDHead with configurable fc layers, normalization, and activation for person re-identification', 'review the LinearReIDHead __init__ to understand loss configuration and top-k accuracy validation logic', 'test the LinearReIDHead forward method by passing multi-stage feature tuples and verifying output tensor shape', 'refactor the LinearReIDHead loss method to support additional loss types beyond cross entropy and triplet loss', 'summarize the LinearReIDHead predict method that extracts features and attaches them to ReIDDataSample objects']
```

Usage

```
{'build_LinearReIDHead': 'build a LinearReIDHead with configurable fc layers, normalization, and activation for person re-identification', 'review_LinearReIDHead_init': 'review the LinearReIDHead __init__ to understand loss configuration and top-k accuracy validation logic', 'test_LinearReIDHead_forward': 'test the LinearReIDHead forward method by passing multi-stage feature tuples and verifying output tensor shape', 'refactor_LinearReIDHead_loss': 'refactor the LinearReIDHead loss method to support additional loss types beyond cross entropy and triplet loss', 'summarize_LinearReIDHead_predict': 'summarize the LinearReIDHead predict method that extracts features and attaches them to ReIDDataSample objects'}
```

