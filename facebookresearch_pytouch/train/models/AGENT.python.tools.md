# Agent Python Tools

- repo: facebookresearch/pytouch
- repo_uri: https://github.com/facebookresearch/pytouch

## File: facebookresearch_pytouch/train/models/slip_detect.py

Prompts

```
['build a SlipDetectionModel with a config that sets model.n_classes and optimizer.lr', 'run the SlipDetectionModel forward pass on a frame tensor to get slip predictions', 'test the SlipDetectionModel training_step method with a batch of images, targets, and sensor names', 'test the SlipDetectionModel validation_step method to compute val_loss and val_acc metrics', 'review the SlipDetectionModel configure_optimizers method that returns an Adam optimizer with the configured learning rate', 'build a ResNet-50 model using resnet50() to process 5D video tensors with temporal averaging', 'create a ResNet-18 model using resnet18() with BasicBlock for lightweight video feature extraction', 'review the ResNet class forward method that reshapes 5D video input and averages over the time dimension', 'test the Bottleneck class forward pass with 1x1-3x3-1x1 conv sequence and residual skip connection', 'summarize the resnext50_32x4d factory function that builds a grouped Bottleneck ResNet with 32 groups of width 4', 'build a ResNet18-based touch detection model with frozen base layers and a custom classification head', 'run inference on a frame tensor through the touch detection model to get class predictions']
```

Usage

```
{'build_slip_detection_model': 'build a SlipDetectionModel with a config that sets model.n_classes and optimizer.lr', 'run_slip_detection_forward': 'run the SlipDetectionModel forward pass on a frame tensor to get slip predictions', 'test_training_step': 'test the SlipDetectionModel training_step method with a batch of images, targets, and sensor names', 'test_validation_step': 'test the SlipDetectionModel validation_step method to compute val_loss and val_acc metrics', 'review_configure_optimizers': 'review the SlipDetectionModel configure_optimizers method that returns an Adam optimizer with the configured learning rate'}
```

## File: facebookresearch_pytouch/train/models/slip_resnet.py

Prompts

```
['build a SlipDetectionModel with a config that sets model.n_classes and optimizer.lr', 'run the SlipDetectionModel forward pass on a frame tensor to get slip predictions', 'test the SlipDetectionModel training_step method with a batch of images, targets, and sensor names', 'test the SlipDetectionModel validation_step method to compute val_loss and val_acc metrics', 'review the SlipDetectionModel configure_optimizers method that returns an Adam optimizer with the configured learning rate', 'build a ResNet-50 model using resnet50() to process 5D video tensors with temporal averaging', 'create a ResNet-18 model using resnet18() with BasicBlock for lightweight video feature extraction', 'review the ResNet class forward method that reshapes 5D video input and averages over the time dimension', 'test the Bottleneck class forward pass with 1x1-3x3-1x1 conv sequence and residual skip connection', 'summarize the resnext50_32x4d factory function that builds a grouped Bottleneck ResNet with 32 groups of width 4', 'build a ResNet18-based touch detection model with frozen base layers and a custom classification head', 'run inference on a frame tensor through the touch detection model to get class predictions']
```

Usage

```
{'build_resnet50_video_model': 'build a ResNet-50 model using resnet50() to process 5D video tensors with temporal averaging', 'create_resnet18_model': 'create a ResNet-18 model using resnet18() with BasicBlock for lightweight video feature extraction', 'review_ResNet_forward': 'review the ResNet class forward method that reshapes 5D video input and averages over the time dimension', 'test_Bottleneck_block': 'test the Bottleneck class forward pass with 1x1-3x3-1x1 conv sequence and residual skip connection', 'summarize_resnext50_32x4d': 'summarize the resnext50_32x4d factory function that builds a grouped Bottleneck ResNet with 32 groups of width 4'}
```

## File: facebookresearch_pytouch/train/models/touch_detect.py

Prompts

```
['build a SlipDetectionModel with a config that sets model.n_classes and optimizer.lr', 'run the SlipDetectionModel forward pass on a frame tensor to get slip predictions', 'test the SlipDetectionModel training_step method with a batch of images, targets, and sensor names', 'test the SlipDetectionModel validation_step method to compute val_loss and val_acc metrics', 'review the SlipDetectionModel configure_optimizers method that returns an Adam optimizer with the configured learning rate', 'build a ResNet-50 model using resnet50() to process 5D video tensors with temporal averaging', 'create a ResNet-18 model using resnet18() with BasicBlock for lightweight video feature extraction', 'review the ResNet class forward method that reshapes 5D video input and averages over the time dimension', 'test the Bottleneck class forward pass with 1x1-3x3-1x1 conv sequence and residual skip connection', 'summarize the resnext50_32x4d factory function that builds a grouped Bottleneck ResNet with 32 groups of width 4', 'build a ResNet18-based touch detection model with frozen base layers and a custom classification head', 'run inference on a frame tensor through the touch detection model to get class predictions']
```

Usage

```
{'build_touch_detection_model': 'build a ResNet18-based touch detection model with frozen base layers and a custom classification head', 'run_touch_detection_forward': 'run inference on a frame tensor through the touch detection model to get class predictions', 'test_training_step': 'test the training step that computes cross-entropy loss on image-target batches and logs train_loss', 'test_validation_step': 'test the validation step that computes loss and accuracy metrics on image-target batches', 'review_configure_optimizers': 'review the optimizer configuration that sets up MADGRAD with the specified learning rate'}
```

