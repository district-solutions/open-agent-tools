# Agent Python Tools

- repo: facebookresearch/agem
- repo_uri: https://github.com/facebookresearch/agem

## File: facebookresearch_agem/utils/resnet_utils.py

Prompts

```
['build a TensorFlow 2D convolutional layer with uniform weight initialization and configurable kernel size', 'create a fully connected layer with configurable output dimensions and optional CIFAR bias initialization', 'build a batch normalization layer with exponential moving average for training and inference phases', 'create a ResNet residual block with two conv layers and batch normalization for same-channel skip connections', 'build a generic ResNet residual block that handles channel dimension changes with shortcut convolutions', 'create a tensorflow convolutional layer with configurable stride and optional relu activation', 'load task-specific images and labels from a dataset filtered by class labels', 'sample representative images using iCaRL herding based on feature mean distance', 'compute average forgetting metrics from a task-by-task accuracy matrix', 'build a VGG convolutional layer with kernel weights, biases, and ReLU activation using TensorFlow', 'build a VGG fully connected layer with weights, biases, and optional ReLU activation using TensorFlow', 'create a convolutional layer with a custom kernel size, output channels, and stride value', 'create a fully connected layer that skips ReLU activation by setting apply_relu to False', 'review the VGG layer weight initialization strategy using random uniform distribution based on input dimensions', 'create a pickle snapshot of experiment evaluation data to a specified log directory', 'create a pickle snapshot of task labels data to a specified log directory', 'write experiment metadata key-value pairs to a text file in the log directory', 'build a multi-subplot accuracy plot with error bars across tasks and multiple runs', 'create a histogram plot of data and save it to a specified file path']
```

Usage

```
{'build_conv_layer': 'build a TensorFlow 2D convolutional layer with uniform weight initialization and configurable kernel size', 'create_fc_layer': 'create a fully connected layer with configurable output dimensions and optional CIFAR bias initialization', 'build_batch_norm': 'build a batch normalization layer with exponential moving average for training and inference phases', 'create_residual_block': 'create a ResNet residual block with two conv layers and batch normalization for same-channel skip connections', 'build_residual_block_first': 'build a generic ResNet residual block that handles channel dimension changes with shortcut convolutions'}
```

## File: facebookresearch_agem/utils/utils.py

Prompts

```
['build a TensorFlow 2D convolutional layer with uniform weight initialization and configurable kernel size', 'create a fully connected layer with configurable output dimensions and optional CIFAR bias initialization', 'build a batch normalization layer with exponential moving average for training and inference phases', 'create a ResNet residual block with two conv layers and batch normalization for same-channel skip connections', 'build a generic ResNet residual block that handles channel dimension changes with shortcut convolutions', 'create a tensorflow convolutional layer with configurable stride and optional relu activation', 'load task-specific images and labels from a dataset filtered by class labels', 'sample representative images using iCaRL herding based on feature mean distance', 'compute average forgetting metrics from a task-by-task accuracy matrix', 'build a VGG convolutional layer with kernel weights, biases, and ReLU activation using TensorFlow', 'build a VGG fully connected layer with weights, biases, and optional ReLU activation using TensorFlow', 'create a convolutional layer with a custom kernel size, output channels, and stride value', 'create a fully connected layer that skips ReLU activation by setting apply_relu to False', 'review the VGG layer weight initialization strategy using random uniform distribution based on input dimensions', 'create a pickle snapshot of experiment evaluation data to a specified log directory', 'create a pickle snapshot of task labels data to a specified log directory', 'write experiment metadata key-value pairs to a text file in the log directory', 'build a multi-subplot accuracy plot with error bars across tasks and multiple runs', 'create a histogram plot of data and save it to a specified file path']
```

Usage

```
{'create_fc_layer': 'create a tensorflow fully connected layer with weights, biases, and optional relu activation', 'create_conv_layer': 'create a tensorflow convolutional layer with configurable stride and optional relu activation', 'load_task_specific_data': 'load task-specific images and labels from a dataset filtered by class labels', 'sample_from_dataset_icarl': 'sample representative images using iCaRL herding based on feature mean distance', 'compute_fgt': 'compute average forgetting metrics from a task-by-task accuracy matrix'}
```

## File: facebookresearch_agem/utils/vgg_utils.py

Prompts

```
['build a TensorFlow 2D convolutional layer with uniform weight initialization and configurable kernel size', 'create a fully connected layer with configurable output dimensions and optional CIFAR bias initialization', 'build a batch normalization layer with exponential moving average for training and inference phases', 'create a ResNet residual block with two conv layers and batch normalization for same-channel skip connections', 'build a generic ResNet residual block that handles channel dimension changes with shortcut convolutions', 'create a tensorflow convolutional layer with configurable stride and optional relu activation', 'load task-specific images and labels from a dataset filtered by class labels', 'sample representative images using iCaRL herding based on feature mean distance', 'compute average forgetting metrics from a task-by-task accuracy matrix', 'build a VGG convolutional layer with kernel weights, biases, and ReLU activation using TensorFlow', 'build a VGG fully connected layer with weights, biases, and optional ReLU activation using TensorFlow', 'create a convolutional layer with a custom kernel size, output channels, and stride value', 'create a fully connected layer that skips ReLU activation by setting apply_relu to False', 'review the VGG layer weight initialization strategy using random uniform distribution based on input dimensions', 'create a pickle snapshot of experiment evaluation data to a specified log directory', 'create a pickle snapshot of task labels data to a specified log directory', 'write experiment metadata key-value pairs to a text file in the log directory', 'build a multi-subplot accuracy plot with error bars across tasks and multiple runs', 'create a histogram plot of data and save it to a specified file path']
```

Usage

```
{'build_vgg_conv_layer': 'build a VGG convolutional layer with kernel weights, biases, and ReLU activation using TensorFlow', 'build_vgg_fc_layer': 'build a VGG fully connected layer with weights, biases, and optional ReLU activation using TensorFlow', 'create_conv_layer_with_custom_stride': 'create a convolutional layer with a custom kernel size, output channels, and stride value', 'create_fc_layer_without_relu': 'create a fully connected layer that skips ReLU activation by setting apply_relu to False', 'review_vgg_layer_weight_init': 'review the VGG layer weight initialization strategy using random uniform distribution based on input dimensions'}
```

## File: facebookresearch_agem/utils/vis_utils.py

Prompts

```
['build a TensorFlow 2D convolutional layer with uniform weight initialization and configurable kernel size', 'create a fully connected layer with configurable output dimensions and optional CIFAR bias initialization', 'build a batch normalization layer with exponential moving average for training and inference phases', 'create a ResNet residual block with two conv layers and batch normalization for same-channel skip connections', 'build a generic ResNet residual block that handles channel dimension changes with shortcut convolutions', 'create a tensorflow convolutional layer with configurable stride and optional relu activation', 'load task-specific images and labels from a dataset filtered by class labels', 'sample representative images using iCaRL herding based on feature mean distance', 'compute average forgetting metrics from a task-by-task accuracy matrix', 'build a VGG convolutional layer with kernel weights, biases, and ReLU activation using TensorFlow', 'build a VGG fully connected layer with weights, biases, and optional ReLU activation using TensorFlow', 'create a convolutional layer with a custom kernel size, output channels, and stride value', 'create a fully connected layer that skips ReLU activation by setting apply_relu to False', 'review the VGG layer weight initialization strategy using random uniform distribution based on input dimensions', 'create a pickle snapshot of experiment evaluation data to a specified log directory', 'create a pickle snapshot of task labels data to a specified log directory', 'write experiment metadata key-value pairs to a text file in the log directory', 'build a multi-subplot accuracy plot with error bars across tasks and multiple runs', 'create a histogram plot of data and save it to a specified file path']
```

Usage

```
{'snapshot_experiment_eval': 'create a pickle snapshot of experiment evaluation data to a specified log directory', 'snapshot_task_labels': 'create a pickle snapshot of task labels data to a specified log directory', 'snapshot_experiment_meta_data': 'write experiment metadata key-value pairs to a text file in the log directory', 'plot_acc_multiple_runs': 'build a multi-subplot accuracy plot with error bars across tasks and multiple runs', 'plot_histogram': 'create a histogram plot of data and save it to a specified file path'}
```

