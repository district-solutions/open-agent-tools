# Agent Python Tools

- repo: facebookresearch/fairselfsupervisionbenchmark
- repo_uri: https://github.com/facebookresearch/fair_self_supervision_benchmark

## File: facebookresearch_fairselfsupervisionbenchmark/self_supervision_benchmark/modeling/supervised/caffenet_bvlc_supervised_finetune_full.py

Prompts

```
['create a Caffe BVLC Caffenet CNN model with conv, pool, fc layers for VOC07 finetuning', 'build the five convolutional layers with ReLU and LRN normalization following BVLC Alexnet architecture', 'build the fully connected fc6, fc7, fc8 layers with dropout for classification head', 'review the create_model function that constructs a Caffenet model with sigmoid cross entropy loss', 'refactor the Caffenet model to change num_classes or adjust weight initialization for a new dataset', 'create a CaffeNet BVLC model with linear classifier heads on each conv layer for supervised fine-tuning', 'build a CaffeNet network that freezes conv layers and adds batch norm plus FC heads for classification', 'create a model using create_model with a Caffe2 model helper, data blob, labels, and train or test split', 'review the CaffeNet BVLC architecture with conv1 through conv5 layers each having a linear classification head', 'summarize the create_model function that returns a CaffeNet model with per-layer softmax outputs and loss values', 'create a ResNet-50 supervised model for full finetuning on VOC07 using Caffe2 operators', 'build residual layers with bottleneck blocks across four stages using ModelHelper residual_layer', 'configure ResNet block counts per stage using BLOCK_CONFIG dictionary for depth 50', 'add the conv1, batch normalization, and ReLU head layer with MSRAFill weight initialization', 'compute sigmoid cross entropy loss for training splits and return model with sigmoid output', 'create a ResNet-50 model with linear classifiers at each stage for supervised fine-tuning', 'build a Caffe2 ResNet model with frozen backbone and linear heads on conv1 through pool5', 'test the create_model function by passing a Caffe2 model, data blob, labels, and split string', 'review the BLOCK_CONFIG dictionary that maps ResNet depth 50 to its block tuple (3, 4, 6, 3)']
```

Usage

```
{'create_model_caffenet_bvlc': 'create a Caffe BVLC Caffenet CNN model with conv, pool, fc layers for VOC07 finetuning', 'build_caffenet_conv_layers': 'build the five convolutional layers with ReLU and LRN normalization following BVLC Alexnet architecture', 'build_caffenet_fc_layers': 'build the fully connected fc6, fc7, fc8 layers with dropout for classification head', 'review_create_model_function': 'review the create_model function that constructs a Caffenet model with sigmoid cross entropy loss', 'refactor_caffenet_for_new_dataset': 'refactor the Caffenet model to change num_classes or adjust weight initialization for a new dataset'}
```

## File: facebookresearch_fairselfsupervisionbenchmark/self_supervision_benchmark/modeling/supervised/caffenet_bvlc_supervised_finetune_linear.py

Prompts

```
['create a Caffe BVLC Caffenet CNN model with conv, pool, fc layers for VOC07 finetuning', 'build the five convolutional layers with ReLU and LRN normalization following BVLC Alexnet architecture', 'build the fully connected fc6, fc7, fc8 layers with dropout for classification head', 'review the create_model function that constructs a Caffenet model with sigmoid cross entropy loss', 'refactor the Caffenet model to change num_classes or adjust weight initialization for a new dataset', 'create a CaffeNet BVLC model with linear classifier heads on each conv layer for supervised fine-tuning', 'build a CaffeNet network that freezes conv layers and adds batch norm plus FC heads for classification', 'create a model using create_model with a Caffe2 model helper, data blob, labels, and train or test split', 'review the CaffeNet BVLC architecture with conv1 through conv5 layers each having a linear classification head', 'summarize the create_model function that returns a CaffeNet model with per-layer softmax outputs and loss values', 'create a ResNet-50 supervised model for full finetuning on VOC07 using Caffe2 operators', 'build residual layers with bottleneck blocks across four stages using ModelHelper residual_layer', 'configure ResNet block counts per stage using BLOCK_CONFIG dictionary for depth 50', 'add the conv1, batch normalization, and ReLU head layer with MSRAFill weight initialization', 'compute sigmoid cross entropy loss for training splits and return model with sigmoid output', 'create a ResNet-50 model with linear classifiers at each stage for supervised fine-tuning', 'build a Caffe2 ResNet model with frozen backbone and linear heads on conv1 through pool5', 'test the create_model function by passing a Caffe2 model, data blob, labels, and split string', 'review the BLOCK_CONFIG dictionary that maps ResNet depth 50 to its block tuple (3, 4, 6, 3)']
```

Usage

```
{'create_caffenet_linear_classifier_model': 'create a CaffeNet BVLC model with linear classifier heads on each conv layer for supervised fine-tuning', 'build_caffenet_finetune_network': 'build a CaffeNet network that freezes conv layers and adds batch norm plus FC heads for classification', 'create_model_function': 'create a model using create_model with a Caffe2 model helper, data blob, labels, and train or test split', 'review_caffenet_architecture': 'review the CaffeNet BVLC architecture with conv1 through conv5 layers each having a linear classification head', 'summarize_create_model': 'summarize the create_model function that returns a CaffeNet model with per-layer softmax outputs and loss values'}
```

## File: facebookresearch_fairselfsupervisionbenchmark/self_supervision_benchmark/modeling/supervised/resnet_supervised_finetune_full.py

Prompts

```
['create a Caffe BVLC Caffenet CNN model with conv, pool, fc layers for VOC07 finetuning', 'build the five convolutional layers with ReLU and LRN normalization following BVLC Alexnet architecture', 'build the fully connected fc6, fc7, fc8 layers with dropout for classification head', 'review the create_model function that constructs a Caffenet model with sigmoid cross entropy loss', 'refactor the Caffenet model to change num_classes or adjust weight initialization for a new dataset', 'create a CaffeNet BVLC model with linear classifier heads on each conv layer for supervised fine-tuning', 'build a CaffeNet network that freezes conv layers and adds batch norm plus FC heads for classification', 'create a model using create_model with a Caffe2 model helper, data blob, labels, and train or test split', 'review the CaffeNet BVLC architecture with conv1 through conv5 layers each having a linear classification head', 'summarize the create_model function that returns a CaffeNet model with per-layer softmax outputs and loss values', 'create a ResNet-50 supervised model for full finetuning on VOC07 using Caffe2 operators', 'build residual layers with bottleneck blocks across four stages using ModelHelper residual_layer', 'configure ResNet block counts per stage using BLOCK_CONFIG dictionary for depth 50', 'add the conv1, batch normalization, and ReLU head layer with MSRAFill weight initialization', 'compute sigmoid cross entropy loss for training splits and return model with sigmoid output', 'create a ResNet-50 model with linear classifiers at each stage for supervised fine-tuning', 'build a Caffe2 ResNet model with frozen backbone and linear heads on conv1 through pool5', 'test the create_model function by passing a Caffe2 model, data blob, labels, and split string', 'review the BLOCK_CONFIG dictionary that maps ResNet depth 50 to its block tuple (3, 4, 6, 3)']
```

Usage

```
{'create_resnet50_supervised_model': 'create a ResNet-50 supervised model for full finetuning on VOC07 using Caffe2 operators', 'build_residual_layers': 'build residual layers with bottleneck blocks across four stages using ModelHelper residual_layer', 'configure_block_depth': 'configure ResNet block counts per stage using BLOCK_CONFIG dictionary for depth 50', 'add_conv_bn_relu_head': 'add the conv1, batch normalization, and ReLU head layer with MSRAFill weight initialization', 'compute_sigmoid_cross_entropy_loss': 'compute sigmoid cross entropy loss for training splits and return model with sigmoid output'}
```

## File: facebookresearch_fairselfsupervisionbenchmark/self_supervision_benchmark/modeling/supervised/resnet_supervised_finetune_linear.py

Prompts

```
['create a Caffe BVLC Caffenet CNN model with conv, pool, fc layers for VOC07 finetuning', 'build the five convolutional layers with ReLU and LRN normalization following BVLC Alexnet architecture', 'build the fully connected fc6, fc7, fc8 layers with dropout for classification head', 'review the create_model function that constructs a Caffenet model with sigmoid cross entropy loss', 'refactor the Caffenet model to change num_classes or adjust weight initialization for a new dataset', 'create a CaffeNet BVLC model with linear classifier heads on each conv layer for supervised fine-tuning', 'build a CaffeNet network that freezes conv layers and adds batch norm plus FC heads for classification', 'create a model using create_model with a Caffe2 model helper, data blob, labels, and train or test split', 'review the CaffeNet BVLC architecture with conv1 through conv5 layers each having a linear classification head', 'summarize the create_model function that returns a CaffeNet model with per-layer softmax outputs and loss values', 'create a ResNet-50 supervised model for full finetuning on VOC07 using Caffe2 operators', 'build residual layers with bottleneck blocks across four stages using ModelHelper residual_layer', 'configure ResNet block counts per stage using BLOCK_CONFIG dictionary for depth 50', 'add the conv1, batch normalization, and ReLU head layer with MSRAFill weight initialization', 'compute sigmoid cross entropy loss for training splits and return model with sigmoid output', 'create a ResNet-50 model with linear classifiers at each stage for supervised fine-tuning', 'build a Caffe2 ResNet model with frozen backbone and linear heads on conv1 through pool5', 'test the create_model function by passing a Caffe2 model, data blob, labels, and split string', 'review the BLOCK_CONFIG dictionary that maps ResNet depth 50 to its block tuple (3, 4, 6, 3)']
```

Usage

```
{'create_model_resnet_linear_classifier': 'create a ResNet-50 model with linear classifiers at each stage for supervised fine-tuning', 'build_resnet_finetune_model': 'build a Caffe2 ResNet model with frozen backbone and linear heads on conv1 through pool5', 'test_create_model_function': 'test the create_model function by passing a Caffe2 model, data blob, labels, and split string', 'review_BLOCK_CONFIG': 'review the BLOCK_CONFIG dictionary that maps ResNet depth 50 to its block tuple (3, 4, 6, 3)', 'summarize_create_model': 'summarize the create_model function that constructs multi-head linear classifiers on a frozen ResNet-50 backbone'}
```

