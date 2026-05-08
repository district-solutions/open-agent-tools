# Agent Python Tools

- repo: facebookresearch/param
- repo_uri: https://github.com/facebookresearch/param

## File: facebookresearch_param/train/compute/python/workloads/pytorch/alex_net.py

Prompts

```
['build a PyTorch AlexNet model with a custom number of classes and dropout rate', 'run a forward pass through the AlexNet model on an input tensor', 'register the AlexNet model as a buildable operator under pytorch.model.alex_net', 'review the AlexNet convolutional feature extractor and classifier layer architecture', 'refactor the AlexNet model to use a different number of output classes', 'build a ResNet model using the Bottleneck block with default layer configuration for image classification', 'build a ResNet model using the BasicBlock instead of Bottleneck for a lighter network', 'create a Bottleneck residual block with 1x1, 3x3, and 1x1 convolutions for deep ResNet variants', 'create a BasicBlock residual block with two 3x3 convolutions for shallow ResNet variants', 'register the ResNet model as a buildable operator under the pytorch.model.resnet key', 'generate synthetic embedding bag request tensors with uniform or Zipf distribution for a given batch size and pooling factor', 'build a SplitTableBatchedEmbeddingBagsCodegen operator with specified table rows, embedding dims, optimizer, and learning rate', 'run forward and backward passes on the split table embedding bags operator with indices, offsets, and optional weights', 'create a config iterator that yields batched embedding bag input configurations from a build config dictionary', 'generate indices, offsets, and per-sample weights tensors for split table embedding bag operations from a data config']
```

Usage

```
{'build_alexnet_model': 'build a PyTorch AlexNet model with a custom number of classes and dropout rate', 'run_alexnet_forward': 'run a forward pass through the AlexNet model on an input tensor', 'register_alexnet_operator': 'register the AlexNet model as a buildable operator under pytorch.model.alex_net', 'review_alexnet_architecture': 'review the AlexNet convolutional feature extractor and classifier layer architecture', 'refactor_alexnet_classes': 'refactor the AlexNet model to use a different number of output classes'}
```

## File: facebookresearch_param/train/compute/python/workloads/pytorch/resnet.py

Prompts

```
['build a PyTorch AlexNet model with a custom number of classes and dropout rate', 'run a forward pass through the AlexNet model on an input tensor', 'register the AlexNet model as a buildable operator under pytorch.model.alex_net', 'review the AlexNet convolutional feature extractor and classifier layer architecture', 'refactor the AlexNet model to use a different number of output classes', 'build a ResNet model using the Bottleneck block with default layer configuration for image classification', 'build a ResNet model using the BasicBlock instead of Bottleneck for a lighter network', 'create a Bottleneck residual block with 1x1, 3x3, and 1x1 convolutions for deep ResNet variants', 'create a BasicBlock residual block with two 3x3 convolutions for shallow ResNet variants', 'register the ResNet model as a buildable operator under the pytorch.model.resnet key', 'generate synthetic embedding bag request tensors with uniform or Zipf distribution for a given batch size and pooling factor', 'build a SplitTableBatchedEmbeddingBagsCodegen operator with specified table rows, embedding dims, optimizer, and learning rate', 'run forward and backward passes on the split table embedding bags operator with indices, offsets, and optional weights', 'create a config iterator that yields batched embedding bag input configurations from a build config dictionary', 'generate indices, offsets, and per-sample weights tensors for split table embedding bag operations from a data config']
```

Usage

```
{'build_resnet_model': 'build a ResNet model using the Bottleneck block with default layer configuration for image classification', 'build_resnet_basicblock': 'build a ResNet model using the BasicBlock instead of Bottleneck for a lighter network', 'create_bottleneck_block': 'create a Bottleneck residual block with 1x1, 3x3, and 1x1 convolutions for deep ResNet variants', 'create_basicblock': 'create a BasicBlock residual block with two 3x3 convolutions for shallow ResNet variants', 'register_resnet_operator': 'register the ResNet model as a buildable operator under the pytorch.model.resnet key'}
```

## File: facebookresearch_param/train/compute/python/workloads/pytorch/split_table_batched_embeddings_ops.py

Prompts

```
['build a PyTorch AlexNet model with a custom number of classes and dropout rate', 'run a forward pass through the AlexNet model on an input tensor', 'register the AlexNet model as a buildable operator under pytorch.model.alex_net', 'review the AlexNet convolutional feature extractor and classifier layer architecture', 'refactor the AlexNet model to use a different number of output classes', 'build a ResNet model using the Bottleneck block with default layer configuration for image classification', 'build a ResNet model using the BasicBlock instead of Bottleneck for a lighter network', 'create a Bottleneck residual block with 1x1, 3x3, and 1x1 convolutions for deep ResNet variants', 'create a BasicBlock residual block with two 3x3 convolutions for shallow ResNet variants', 'register the ResNet model as a buildable operator under the pytorch.model.resnet key', 'generate synthetic embedding bag request tensors with uniform or Zipf distribution for a given batch size and pooling factor', 'build a SplitTableBatchedEmbeddingBagsCodegen operator with specified table rows, embedding dims, optimizer, and learning rate', 'run forward and backward passes on the split table embedding bags operator with indices, offsets, and optional weights', 'create a config iterator that yields batched embedding bag input configurations from a build config dictionary', 'generate indices, offsets, and per-sample weights tensors for split table embedding bag operations from a data config']
```

Usage

```
{'generate_requests': 'generate synthetic embedding bag request tensors with uniform or Zipf distribution for a given batch size and pooling factor', 'build_split_table_op': 'build a SplitTableBatchedEmbeddingBagsCodegen operator with specified table rows, embedding dims, optimizer, and learning rate', 'run_forward_backward': 'run forward and backward passes on the split table embedding bags operator with indices, offsets, and optional weights', 'create_input_iterator': 'create a config iterator that yields batched embedding bag input configurations from a build config dictionary', 'generate_input_data': 'generate indices, offsets, and per-sample weights tensors for split table embedding bag operations from a data config'}
```

