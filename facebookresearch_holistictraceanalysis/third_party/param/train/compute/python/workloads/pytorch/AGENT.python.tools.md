# Agent Python Tools

- repo: facebookresearch/holistictraceanalysis
- repo_uri: https://github.com/facebookresearch/holistictraceanalysis

## File: facebookresearch_holistictraceanalysis/third_party/param/train/compute/python/workloads/pytorch/alex_net.py

Prompts

```
['build a pytorch AlexNet model with 1000 classes and 0.5 dropout for image classification', 'run the AlexNet forward pass on a tensor through features, avgpool, flatten, and classifier layers', 'review the AlexNet features sequential block with five Conv2d layers and MaxPool2d layers', 'refactor the AlexNet classifier to change the number of output classes or dropout rate', 'summarize the AlexNet operator registered as pytorch.model.alex_net via BuildableOp', 'build a ResNet model with Bottleneck blocks and default layer configuration [3,4,6,3]', 'build a ResNet model using BasicBlock instead of Bottleneck for lighter computation', 'create a 3x3 convolutional layer with configurable stride, groups, and dilation parameters', 'create a 1x1 convolutional layer with configurable stride for channel transformation', 'register the ResNet model as a buildable operator under the name pytorch.model.resnet', 'generate synthetic embedding bag request tensors with configurable batch size, pooling factor, and Zipf or uniform index distribution', 'build a SplitTableBatchedEmbeddingBagsCodegen operator with specified table rows, embedding dims, optimizer, and learning rate for forward and backward passes', 'run forward and backward passes on the split table batched embedding bags operator with indices, offsets, and optional per-sample weights', 'create a SplitTableBatchedEmbeddingBagsCodegenInputDataGenerator to produce indices, offsets, and weights tensors from config or loaded files', 'iterate over input configurations for the split table batched embedding bags operator using the registered SplitTableBatchedEmbeddingBagsCodegenInputIterator']
```

Usage

```
{'build_alexnet_model': 'build a pytorch AlexNet model with 1000 classes and 0.5 dropout for image classification', 'run_alexnet_forward': 'run the AlexNet forward pass on a tensor through features, avgpool, flatten, and classifier layers', 'review_alexnet_features': 'review the AlexNet features sequential block with five Conv2d layers and MaxPool2d layers', 'refactor_alexnet_classifier': 'refactor the AlexNet classifier to change the number of output classes or dropout rate', 'summarize_alexnet_operator': 'summarize the AlexNet operator registered as pytorch.model.alex_net via BuildableOp'}
```

## File: facebookresearch_holistictraceanalysis/third_party/param/train/compute/python/workloads/pytorch/resnet.py

Prompts

```
['build a pytorch AlexNet model with 1000 classes and 0.5 dropout for image classification', 'run the AlexNet forward pass on a tensor through features, avgpool, flatten, and classifier layers', 'review the AlexNet features sequential block with five Conv2d layers and MaxPool2d layers', 'refactor the AlexNet classifier to change the number of output classes or dropout rate', 'summarize the AlexNet operator registered as pytorch.model.alex_net via BuildableOp', 'build a ResNet model with Bottleneck blocks and default layer configuration [3,4,6,3]', 'build a ResNet model using BasicBlock instead of Bottleneck for lighter computation', 'create a 3x3 convolutional layer with configurable stride, groups, and dilation parameters', 'create a 1x1 convolutional layer with configurable stride for channel transformation', 'register the ResNet model as a buildable operator under the name pytorch.model.resnet', 'generate synthetic embedding bag request tensors with configurable batch size, pooling factor, and Zipf or uniform index distribution', 'build a SplitTableBatchedEmbeddingBagsCodegen operator with specified table rows, embedding dims, optimizer, and learning rate for forward and backward passes', 'run forward and backward passes on the split table batched embedding bags operator with indices, offsets, and optional per-sample weights', 'create a SplitTableBatchedEmbeddingBagsCodegenInputDataGenerator to produce indices, offsets, and weights tensors from config or loaded files', 'iterate over input configurations for the split table batched embedding bags operator using the registered SplitTableBatchedEmbeddingBagsCodegenInputIterator']
```

Usage

```
{'build_resnet_model': 'build a ResNet model with Bottleneck blocks and default layer configuration [3,4,6,3]', 'build_resnet_basicblock': 'build a ResNet model using BasicBlock instead of Bottleneck for lighter computation', 'create_conv3x3_layer': 'create a 3x3 convolutional layer with configurable stride, groups, and dilation parameters', 'create_conv1x1_layer': 'create a 1x1 convolutional layer with configurable stride for channel transformation', 'register_resnet_operator': 'register the ResNet model as a buildable operator under the name pytorch.model.resnet'}
```

## File: facebookresearch_holistictraceanalysis/third_party/param/train/compute/python/workloads/pytorch/split_table_batched_embeddings_ops.py

Prompts

```
['build a pytorch AlexNet model with 1000 classes and 0.5 dropout for image classification', 'run the AlexNet forward pass on a tensor through features, avgpool, flatten, and classifier layers', 'review the AlexNet features sequential block with five Conv2d layers and MaxPool2d layers', 'refactor the AlexNet classifier to change the number of output classes or dropout rate', 'summarize the AlexNet operator registered as pytorch.model.alex_net via BuildableOp', 'build a ResNet model with Bottleneck blocks and default layer configuration [3,4,6,3]', 'build a ResNet model using BasicBlock instead of Bottleneck for lighter computation', 'create a 3x3 convolutional layer with configurable stride, groups, and dilation parameters', 'create a 1x1 convolutional layer with configurable stride for channel transformation', 'register the ResNet model as a buildable operator under the name pytorch.model.resnet', 'generate synthetic embedding bag request tensors with configurable batch size, pooling factor, and Zipf or uniform index distribution', 'build a SplitTableBatchedEmbeddingBagsCodegen operator with specified table rows, embedding dims, optimizer, and learning rate for forward and backward passes', 'run forward and backward passes on the split table batched embedding bags operator with indices, offsets, and optional per-sample weights', 'create a SplitTableBatchedEmbeddingBagsCodegenInputDataGenerator to produce indices, offsets, and weights tensors from config or loaded files', 'iterate over input configurations for the split table batched embedding bags operator using the registered SplitTableBatchedEmbeddingBagsCodegenInputIterator']
```

Usage

```
{'generate_requests': 'generate synthetic embedding bag request tensors with configurable batch size, pooling factor, and Zipf or uniform index distribution', 'build_split_table_op': 'build a SplitTableBatchedEmbeddingBagsCodegen operator with specified table rows, embedding dims, optimizer, and learning rate for forward and backward passes', 'run_forward_backward': 'run forward and backward passes on the split table batched embedding bags operator with indices, offsets, and optional per-sample weights', 'create_input_data_generator': 'create a SplitTableBatchedEmbeddingBagsCodegenInputDataGenerator to produce indices, offsets, and weights tensors from config or loaded files', 'iterate_input_configs': 'iterate over input configurations for the split table batched embedding bags operator using the registered SplitTableBatchedEmbeddingBagsCodegenInputIterator'}
```

