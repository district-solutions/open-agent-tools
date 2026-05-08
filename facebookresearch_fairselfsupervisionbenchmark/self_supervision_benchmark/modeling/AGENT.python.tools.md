# Agent Python Tools

- repo: facebookresearch/fairselfsupervisionbenchmark
- repo_uri: https://github.com/facebookresearch/fair_self_supervision_benchmark

## File: facebookresearch_fairselfsupervisionbenchmark/self_supervision_benchmark/modeling/model_builder.py

Prompts

```
['build a ModelBuilder instance to construct a multi-device Caffe2 training or testing model', 'build the full data-parallel model by calling ModelBuilder.build_model to set up the data loader and forward pass', 'create a model forward pass closure using create_model with a ModelBuilder and dataset split name', 'add MomentumSGD parameter update operations with weight decay and batch norm handling for training', 'get a top-k or AP metrics calculator from ModelBuilder.get_metrics_calculator for evaluation', 'build a ResNet bottleneck block with conv-bn-relu layers and a type B shortcut connection', 'build a residual layer by stacking multiple bottleneck blocks with configurable stride and dimensions', 'create a convolution followed by batch normalization and ReLU activation for a ResNet branch', 'add a type B shortcut connection with 1x1 conv and batch normalization when dimensions mismatch', 'review the ModelHelper class and its methods for building ResNet model components with configurable hyperparameters']
```

Usage

```
{'build_ModelBuilder': 'build a ModelBuilder instance to construct a multi-device Caffe2 training or testing model', 'build_model_method': 'build the full data-parallel model by calling ModelBuilder.build_model to set up the data loader and forward pass', 'create_model_function': 'create a model forward pass closure using create_model with a ModelBuilder and dataset split name', 'add_parameter_update_ops_function': 'add MomentumSGD parameter update operations with weight decay and batch norm handling for training', 'get_metrics_calculator_method': 'get a top-k or AP metrics calculator from ModelBuilder.get_metrics_calculator for evaluation'}
```

## File: facebookresearch_fairselfsupervisionbenchmark/self_supervision_benchmark/modeling/resnet_model_helper.py

Prompts

```
['build a ModelBuilder instance to construct a multi-device Caffe2 training or testing model', 'build the full data-parallel model by calling ModelBuilder.build_model to set up the data loader and forward pass', 'create a model forward pass closure using create_model with a ModelBuilder and dataset split name', 'add MomentumSGD parameter update operations with weight decay and batch norm handling for training', 'get a top-k or AP metrics calculator from ModelBuilder.get_metrics_calculator for evaluation', 'build a ResNet bottleneck block with conv-bn-relu layers and a type B shortcut connection', 'build a residual layer by stacking multiple bottleneck blocks with configurable stride and dimensions', 'create a convolution followed by batch normalization and ReLU activation for a ResNet branch', 'add a type B shortcut connection with 1x1 conv and batch normalization when dimensions mismatch', 'review the ModelHelper class and its methods for building ResNet model components with configurable hyperparameters']
```

Usage

```
{'build_bottleneck_block': 'build a ResNet bottleneck block with conv-bn-relu layers and a type B shortcut connection', 'build_residual_layer': 'build a residual layer by stacking multiple bottleneck blocks with configurable stride and dimensions', 'create_conv_bn_relu': 'create a convolution followed by batch normalization and ReLU activation for a ResNet branch', 'add_shortcut_connection': 'add a type B shortcut connection with 1x1 conv and batch normalization when dimensions mismatch', 'review_ModelHelper': 'review the ModelHelper class and its methods for building ResNet model components with configurable hyperparameters'}
```

