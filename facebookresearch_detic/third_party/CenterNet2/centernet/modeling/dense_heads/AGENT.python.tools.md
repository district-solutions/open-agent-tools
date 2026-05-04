# Agent Python Tools

- repo: facebookresearch/detic
- repo_uri: https://github.com/facebookresearch/detic

## File: facebookresearch_detic/third_party/CenterNet2/centernet/modeling/dense_heads/centernet.py

Prompts

```
['build a CenterNet proposal generator module with configurable FPN levels and class count for object detection', 'create a CenterNet model instance from a Detectron2 config with specified input shapes and hyperparameters', 'run the CenterNet forward pass on images and feature dictionaries to compute losses or predictions', 'review the CenterNet losses method to understand heatmap focal loss and regression loss computation', 'test the CenterNet inference pipeline including NMS and top-K filtering for object detection predictions', 'build a CenterNetHead module with configurable cls, bbox, and share towers for object detection', 'create a CenterNetHead instance from a detectron2 config object and input shape specs', 'run the CenterNetHead forward pass on multi-scale feature maps to get cls logits and bbox regression', 'review the Scale nn.Module that multiplies input tensors by a learnable scalar parameter', 'refactor the CenterNetHead to enable or disable deformable convolutions in the tower heads', 'summarize the _transpose function that converts image-first training targets to level-first format for FPN', 'summarize the reduce_sum function that performs distributed tensor summation across multiple GPUs', 'review the _transpose function to understand how it splits and concatenates training targets across FPN levels', 'review the reduce_sum function to understand its behavior in single GPU versus multi-GPU distributed training', 'test the reduce_sum function to verify it returns the tensor unchanged when world size is less than 2']
```

Usage

```
{'build_centernet_proposal_generator': 'build a CenterNet proposal generator module with configurable FPN levels and class count for object detection', 'create_centernet_from_config': 'create a CenterNet model instance from a Detectron2 config with specified input shapes and hyperparameters', 'run_centernet_forward_pass': 'run the CenterNet forward pass on images and feature dictionaries to compute losses or predictions', 'review_centernet_losses': 'review the CenterNet losses method to understand heatmap focal loss and regression loss computation', 'test_centernet_inference': 'test the CenterNet inference pipeline including NMS and top-K filtering for object detection predictions'}
```

## File: facebookresearch_detic/third_party/CenterNet2/centernet/modeling/dense_heads/centernet_head.py

Prompts

```
['build a CenterNet proposal generator module with configurable FPN levels and class count for object detection', 'create a CenterNet model instance from a Detectron2 config with specified input shapes and hyperparameters', 'run the CenterNet forward pass on images and feature dictionaries to compute losses or predictions', 'review the CenterNet losses method to understand heatmap focal loss and regression loss computation', 'test the CenterNet inference pipeline including NMS and top-K filtering for object detection predictions', 'build a CenterNetHead module with configurable cls, bbox, and share towers for object detection', 'create a CenterNetHead instance from a detectron2 config object and input shape specs', 'run the CenterNetHead forward pass on multi-scale feature maps to get cls logits and bbox regression', 'review the Scale nn.Module that multiplies input tensors by a learnable scalar parameter', 'refactor the CenterNetHead to enable or disable deformable convolutions in the tower heads', 'summarize the _transpose function that converts image-first training targets to level-first format for FPN', 'summarize the reduce_sum function that performs distributed tensor summation across multiple GPUs', 'review the _transpose function to understand how it splits and concatenates training targets across FPN levels', 'review the reduce_sum function to understand its behavior in single GPU versus multi-GPU distributed training', 'test the reduce_sum function to verify it returns the tensor unchanged when world size is less than 2']
```

Usage

```
{'build_CenterNetHead': 'build a CenterNetHead module with configurable cls, bbox, and share towers for object detection', 'create_CenterNetHead_from_config': 'create a CenterNetHead instance from a detectron2 config object and input shape specs', 'run_CenterNetHead_forward': 'run the CenterNetHead forward pass on multi-scale feature maps to get cls logits and bbox regression', 'review_Scale_module': 'review the Scale nn.Module that multiplies input tensors by a learnable scalar parameter', 'refactor_CenterNetHead_deformable': 'refactor the CenterNetHead to enable or disable deformable convolutions in the tower heads'}
```

## File: facebookresearch_detic/third_party/CenterNet2/centernet/modeling/dense_heads/utils.py

Prompts

```
['build a CenterNet proposal generator module with configurable FPN levels and class count for object detection', 'create a CenterNet model instance from a Detectron2 config with specified input shapes and hyperparameters', 'run the CenterNet forward pass on images and feature dictionaries to compute losses or predictions', 'review the CenterNet losses method to understand heatmap focal loss and regression loss computation', 'test the CenterNet inference pipeline including NMS and top-K filtering for object detection predictions', 'build a CenterNetHead module with configurable cls, bbox, and share towers for object detection', 'create a CenterNetHead instance from a detectron2 config object and input shape specs', 'run the CenterNetHead forward pass on multi-scale feature maps to get cls logits and bbox regression', 'review the Scale nn.Module that multiplies input tensors by a learnable scalar parameter', 'refactor the CenterNetHead to enable or disable deformable convolutions in the tower heads', 'summarize the _transpose function that converts image-first training targets to level-first format for FPN', 'summarize the reduce_sum function that performs distributed tensor summation across multiple GPUs', 'review the _transpose function to understand how it splits and concatenates training targets across FPN levels', 'review the reduce_sum function to understand its behavior in single GPU versus multi-GPU distributed training', 'test the reduce_sum function to verify it returns the tensor unchanged when world size is less than 2']
```

Usage

```
{'summarize_transpose': 'summarize the _transpose function that converts image-first training targets to level-first format for FPN', 'summarize_reduce_sum': 'summarize the reduce_sum function that performs distributed tensor summation across multiple GPUs', 'review_transpose': 'review the _transpose function to understand how it splits and concatenates training targets across FPN levels', 'review_reduce_sum': 'review the reduce_sum function to understand its behavior in single GPU versus multi-GPU distributed training', 'test_reduce_sum': 'test the reduce_sum function to verify it returns the tensor unchanged when world size is less than 2'}
```

