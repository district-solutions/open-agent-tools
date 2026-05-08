# Agent Python Tools

- repo: facebookresearch/fairselfsupervisionbenchmark
- repo_uri: https://github.com/facebookresearch/fair_self_supervision_benchmark

## File: facebookresearch_fairselfsupervisionbenchmark/self_supervision_benchmark/modeling/colorization/alexnet_colorize_finetune_full.py

Prompts

```
['create an AlexNet model for colorization pre-training full finetuning on VOC07 dataset', 'build the five convolutional layers with batch normalization and ReLU activations for feature extraction', 'configure spatial batch normalization layers with configurable epsilon momentum and scale shift options', 'setup fully connected layers fc6 fc7 fc8 with gaussian or xavier weight initialization', 'add sigmoid activation and sigmoid cross entropy loss for multi-label classification on VOC07', 'create an AlexNet model with linear classifiers on top of colorization pre-trained features for ImageNet-1K or Places205', 'build linear classifiers at each conv layer of a colorization pre-trained AlexNet using Caffe2 operations', 'test the create_model function that builds AlexNet with linear heads on frozen colorization features', 'review the AlexNet colorization fine-tuning architecture with linear classifiers at conv1 through conv5 and pool5', 'summarize the create_model function that splits LAB channels and attaches linear heads to each AlexNet layer', 'create a ResNet-50 model for full finetuning on VOC07 using colorization self-supervised pre-training', 'build a Caffe2 ResNet model that splits LAB channels and uses only the L channel as input', 'review the create_model function that constructs a ResNet-50 with bottleneck blocks and sigmoid cross-entropy loss', 'summarize the BLOCK_CONFIG dictionary that maps ResNet depth to the number of blocks per stage', 'test the ResNet-50 colorization finetune model by calling create_model with a Caffe2 model helper and data blobs', 'create a ResNet-50 model with linear classifiers on each stage for colorization pre-trained feature evaluation', 'build a multi-stage linear evaluation head on top of frozen ResNet-50 feature extractors', 'review the BLOCK_CONFIG dictionary that maps ResNet depth to per-stage block counts for ResNet-50', 'refactor create_model to add or remove StopGradient calls on intermediate feature stages']
```

Usage

```
{'create_alexnet_colorize_model': 'create an AlexNet model for colorization pre-training full finetuning on VOC07 dataset', 'build_conv_layers': 'build the five convolutional layers with batch normalization and ReLU activations for feature extraction', 'configure_batch_norm': 'configure spatial batch normalization layers with configurable epsilon momentum and scale shift options', 'setup_fc_layers': 'setup fully connected layers fc6 fc7 fc8 with gaussian or xavier weight initialization', 'add_loss_and_sigmoid': 'add sigmoid activation and sigmoid cross entropy loss for multi-label classification on VOC07'}
```

## File: facebookresearch_fairselfsupervisionbenchmark/self_supervision_benchmark/modeling/colorization/alexnet_colorize_finetune_linear.py

Prompts

```
['create an AlexNet model for colorization pre-training full finetuning on VOC07 dataset', 'build the five convolutional layers with batch normalization and ReLU activations for feature extraction', 'configure spatial batch normalization layers with configurable epsilon momentum and scale shift options', 'setup fully connected layers fc6 fc7 fc8 with gaussian or xavier weight initialization', 'add sigmoid activation and sigmoid cross entropy loss for multi-label classification on VOC07', 'create an AlexNet model with linear classifiers on top of colorization pre-trained features for ImageNet-1K or Places205', 'build linear classifiers at each conv layer of a colorization pre-trained AlexNet using Caffe2 operations', 'test the create_model function that builds AlexNet with linear heads on frozen colorization features', 'review the AlexNet colorization fine-tuning architecture with linear classifiers at conv1 through conv5 and pool5', 'summarize the create_model function that splits LAB channels and attaches linear heads to each AlexNet layer', 'create a ResNet-50 model for full finetuning on VOC07 using colorization self-supervised pre-training', 'build a Caffe2 ResNet model that splits LAB channels and uses only the L channel as input', 'review the create_model function that constructs a ResNet-50 with bottleneck blocks and sigmoid cross-entropy loss', 'summarize the BLOCK_CONFIG dictionary that maps ResNet depth to the number of blocks per stage', 'test the ResNet-50 colorization finetune model by calling create_model with a Caffe2 model helper and data blobs', 'create a ResNet-50 model with linear classifiers on each stage for colorization pre-trained feature evaluation', 'build a multi-stage linear evaluation head on top of frozen ResNet-50 feature extractors', 'review the BLOCK_CONFIG dictionary that maps ResNet depth to per-stage block counts for ResNet-50', 'refactor create_model to add or remove StopGradient calls on intermediate feature stages']
```

Usage

```
{'create_model_alexnet_colorize_linear': 'create an AlexNet model with linear classifiers on top of colorization pre-trained features for ImageNet-1K or Places205', 'build_alexnet_finetune_linear_classifiers': 'build linear classifiers at each conv layer of a colorization pre-trained AlexNet using Caffe2 operations', 'test_create_model_function': 'test the create_model function that builds AlexNet with linear heads on frozen colorization features', 'review_alexnet_colorize_architecture': 'review the AlexNet colorization fine-tuning architecture with linear classifiers at conv1 through conv5 and pool5', 'summarize_create_model': 'summarize the create_model function that splits LAB channels and attaches linear heads to each AlexNet layer'}
```

## File: facebookresearch_fairselfsupervisionbenchmark/self_supervision_benchmark/modeling/colorization/resnet_colorize_finetune_full.py

Prompts

```
['create an AlexNet model for colorization pre-training full finetuning on VOC07 dataset', 'build the five convolutional layers with batch normalization and ReLU activations for feature extraction', 'configure spatial batch normalization layers with configurable epsilon momentum and scale shift options', 'setup fully connected layers fc6 fc7 fc8 with gaussian or xavier weight initialization', 'add sigmoid activation and sigmoid cross entropy loss for multi-label classification on VOC07', 'create an AlexNet model with linear classifiers on top of colorization pre-trained features for ImageNet-1K or Places205', 'build linear classifiers at each conv layer of a colorization pre-trained AlexNet using Caffe2 operations', 'test the create_model function that builds AlexNet with linear heads on frozen colorization features', 'review the AlexNet colorization fine-tuning architecture with linear classifiers at conv1 through conv5 and pool5', 'summarize the create_model function that splits LAB channels and attaches linear heads to each AlexNet layer', 'create a ResNet-50 model for full finetuning on VOC07 using colorization self-supervised pre-training', 'build a Caffe2 ResNet model that splits LAB channels and uses only the L channel as input', 'review the create_model function that constructs a ResNet-50 with bottleneck blocks and sigmoid cross-entropy loss', 'summarize the BLOCK_CONFIG dictionary that maps ResNet depth to the number of blocks per stage', 'test the ResNet-50 colorization finetune model by calling create_model with a Caffe2 model helper and data blobs', 'create a ResNet-50 model with linear classifiers on each stage for colorization pre-trained feature evaluation', 'build a multi-stage linear evaluation head on top of frozen ResNet-50 feature extractors', 'review the BLOCK_CONFIG dictionary that maps ResNet depth to per-stage block counts for ResNet-50', 'refactor create_model to add or remove StopGradient calls on intermediate feature stages']
```

Usage

```
{'create_model_resnet50_colorize_finetune': 'create a ResNet-50 model for full finetuning on VOC07 using colorization self-supervised pre-training', 'build_resnet_colorize_transfer_model': 'build a Caffe2 ResNet model that splits LAB channels and uses only the L channel as input', 'review_create_model_function': 'review the create_model function that constructs a ResNet-50 with bottleneck blocks and sigmoid cross-entropy loss', 'summarize_block_config': 'summarize the BLOCK_CONFIG dictionary that maps ResNet depth to the number of blocks per stage', 'test_resnet_colorize_model': 'test the ResNet-50 colorization finetune model by calling create_model with a Caffe2 model helper and data blobs'}
```

## File: facebookresearch_fairselfsupervisionbenchmark/self_supervision_benchmark/modeling/colorization/resnet_colorize_finetune_linear.py

Prompts

```
['create an AlexNet model for colorization pre-training full finetuning on VOC07 dataset', 'build the five convolutional layers with batch normalization and ReLU activations for feature extraction', 'configure spatial batch normalization layers with configurable epsilon momentum and scale shift options', 'setup fully connected layers fc6 fc7 fc8 with gaussian or xavier weight initialization', 'add sigmoid activation and sigmoid cross entropy loss for multi-label classification on VOC07', 'create an AlexNet model with linear classifiers on top of colorization pre-trained features for ImageNet-1K or Places205', 'build linear classifiers at each conv layer of a colorization pre-trained AlexNet using Caffe2 operations', 'test the create_model function that builds AlexNet with linear heads on frozen colorization features', 'review the AlexNet colorization fine-tuning architecture with linear classifiers at conv1 through conv5 and pool5', 'summarize the create_model function that splits LAB channels and attaches linear heads to each AlexNet layer', 'create a ResNet-50 model for full finetuning on VOC07 using colorization self-supervised pre-training', 'build a Caffe2 ResNet model that splits LAB channels and uses only the L channel as input', 'review the create_model function that constructs a ResNet-50 with bottleneck blocks and sigmoid cross-entropy loss', 'summarize the BLOCK_CONFIG dictionary that maps ResNet depth to the number of blocks per stage', 'test the ResNet-50 colorization finetune model by calling create_model with a Caffe2 model helper and data blobs', 'create a ResNet-50 model with linear classifiers on each stage for colorization pre-trained feature evaluation', 'build a multi-stage linear evaluation head on top of frozen ResNet-50 feature extractors', 'review the BLOCK_CONFIG dictionary that maps ResNet depth to per-stage block counts for ResNet-50', 'refactor create_model to add or remove StopGradient calls on intermediate feature stages']
```

Usage

```
{'create_model_resnet50_linear_classifier': 'create a ResNet-50 model with linear classifiers on each stage for colorization pre-trained feature evaluation', 'build_multi_stage_linear_eval': 'build a multi-stage linear evaluation head on top of frozen ResNet-50 feature extractors', 'test_create_model_function': 'test the create_model function with a Caffe2 model helper, data blob, labels, and split string', 'review_BLOCK_CONFIG': 'review the BLOCK_CONFIG dictionary that maps ResNet depth to per-stage block counts for ResNet-50', 'refactor_create_model_frozen_features': 'refactor create_model to add or remove StopGradient calls on intermediate feature stages'}
```

