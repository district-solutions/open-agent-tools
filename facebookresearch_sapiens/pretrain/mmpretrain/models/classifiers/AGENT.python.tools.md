# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pretrain/mmpretrain/models/classifiers/base.py

Prompts

```
['build a python module that subclasses BaseClassifier to implement a custom image classifier with forward method', 'implement the abstract forward method in a BaseClassifier subclass supporting tensor predict and loss modes', 'create a function that calls extract_feat on a classifier instance to get features from a single input tensor', 'build a python module that uses extract_feats to extract features from a sequence of input tensors for augmented inference', 'review the BaseClassifier with_neck and with_head properties to check if a classifier has neck or head modules', 'build a HuggingFaceClassifier with a pretrained model name and cross entropy loss config', 'run the classifier in tensor mode to get raw logits from input images', 'predict class labels and scores for a batch of input image tensors', 'compute classification loss from input tensors and ground truth data samples', 'review the state dict hooks that add and remove the model prefix for checkpoint compatibility', 'build an ImageClassifier with a backbone, neck, and head for supervised image classification', 'extract features from input images at backbone, neck, or pre_logits stage', 'run forward pass in tensor, predict, or loss mode on a batch of input images', 'predict class labels from a batch of input images using the classifier head', 'calculate classification losses from input images and annotated data samples', 'build a TimmClassifier with a pretrained resnet50 model for image classification', 'run a forward pass on input tensors through the TimmClassifier model', 'extract feature representations from input images using the TimmClassifier model', 'predict class labels and scores for input images using the TimmClassifier', 'compute classification loss for a batch of inputs and ground truth labels']
```

Usage

```
{'build_classifier_subclass': 'build a python module that subclasses BaseClassifier to implement a custom image classifier with forward method', 'implement_forward_method': 'implement the abstract forward method in a BaseClassifier subclass supporting tensor predict and loss modes', 'extract_features_single': 'create a function that calls extract_feat on a classifier instance to get features from a single input tensor', 'extract_features_batch': 'build a python module that uses extract_feats to extract features from a sequence of input tensors for augmented inference', 'check_classifier_components': 'review the BaseClassifier with_neck and with_head properties to check if a classifier has neck or head modules'}
```

## File: facebookresearch_sapiens/pretrain/mmpretrain/models/classifiers/hugging_face.py

Prompts

```
['build a python module that subclasses BaseClassifier to implement a custom image classifier with forward method', 'implement the abstract forward method in a BaseClassifier subclass supporting tensor predict and loss modes', 'create a function that calls extract_feat on a classifier instance to get features from a single input tensor', 'build a python module that uses extract_feats to extract features from a sequence of input tensors for augmented inference', 'review the BaseClassifier with_neck and with_head properties to check if a classifier has neck or head modules', 'build a HuggingFaceClassifier with a pretrained model name and cross entropy loss config', 'run the classifier in tensor mode to get raw logits from input images', 'predict class labels and scores for a batch of input image tensors', 'compute classification loss from input tensors and ground truth data samples', 'review the state dict hooks that add and remove the model prefix for checkpoint compatibility', 'build an ImageClassifier with a backbone, neck, and head for supervised image classification', 'extract features from input images at backbone, neck, or pre_logits stage', 'run forward pass in tensor, predict, or loss mode on a batch of input images', 'predict class labels from a batch of input images using the classifier head', 'calculate classification losses from input images and annotated data samples', 'build a TimmClassifier with a pretrained resnet50 model for image classification', 'run a forward pass on input tensors through the TimmClassifier model', 'extract feature representations from input images using the TimmClassifier model', 'predict class labels and scores for input images using the TimmClassifier', 'compute classification loss for a batch of inputs and ground truth labels']
```

Usage

```
{'build_classifier_from_huggingface': 'build a HuggingFaceClassifier with a pretrained model name and cross entropy loss config', 'forward_tensor_mode': 'run the classifier in tensor mode to get raw logits from input images', 'predict_class_labels': 'predict class labels and scores for a batch of input image tensors', 'compute_classification_loss': 'compute classification loss from input tensors and ground truth data samples', 'manage_state_dict_prefix': 'review the state dict hooks that add and remove the model prefix for checkpoint compatibility'}
```

## File: facebookresearch_sapiens/pretrain/mmpretrain/models/classifiers/image.py

Prompts

```
['build a python module that subclasses BaseClassifier to implement a custom image classifier with forward method', 'implement the abstract forward method in a BaseClassifier subclass supporting tensor predict and loss modes', 'create a function that calls extract_feat on a classifier instance to get features from a single input tensor', 'build a python module that uses extract_feats to extract features from a sequence of input tensors for augmented inference', 'review the BaseClassifier with_neck and with_head properties to check if a classifier has neck or head modules', 'build a HuggingFaceClassifier with a pretrained model name and cross entropy loss config', 'run the classifier in tensor mode to get raw logits from input images', 'predict class labels and scores for a batch of input image tensors', 'compute classification loss from input tensors and ground truth data samples', 'review the state dict hooks that add and remove the model prefix for checkpoint compatibility', 'build an ImageClassifier with a backbone, neck, and head for supervised image classification', 'extract features from input images at backbone, neck, or pre_logits stage', 'run forward pass in tensor, predict, or loss mode on a batch of input images', 'predict class labels from a batch of input images using the classifier head', 'calculate classification losses from input images and annotated data samples', 'build a TimmClassifier with a pretrained resnet50 model for image classification', 'run a forward pass on input tensors through the TimmClassifier model', 'extract feature representations from input images using the TimmClassifier model', 'predict class labels and scores for input images using the TimmClassifier', 'compute classification loss for a batch of inputs and ground truth labels']
```

Usage

```
{'build_ImageClassifier': 'build an ImageClassifier with a backbone, neck, and head for supervised image classification', 'extract_feat_ImageClassifier': 'extract features from input images at backbone, neck, or pre_logits stage', 'forward_ImageClassifier': 'run forward pass in tensor, predict, or loss mode on a batch of input images', 'predict_ImageClassifier': 'predict class labels from a batch of input images using the classifier head', 'loss_ImageClassifier': 'calculate classification losses from input images and annotated data samples'}
```

## File: facebookresearch_sapiens/pretrain/mmpretrain/models/classifiers/timm.py

Prompts

```
['build a python module that subclasses BaseClassifier to implement a custom image classifier with forward method', 'implement the abstract forward method in a BaseClassifier subclass supporting tensor predict and loss modes', 'create a function that calls extract_feat on a classifier instance to get features from a single input tensor', 'build a python module that uses extract_feats to extract features from a sequence of input tensors for augmented inference', 'review the BaseClassifier with_neck and with_head properties to check if a classifier has neck or head modules', 'build a HuggingFaceClassifier with a pretrained model name and cross entropy loss config', 'run the classifier in tensor mode to get raw logits from input images', 'predict class labels and scores for a batch of input image tensors', 'compute classification loss from input tensors and ground truth data samples', 'review the state dict hooks that add and remove the model prefix for checkpoint compatibility', 'build an ImageClassifier with a backbone, neck, and head for supervised image classification', 'extract features from input images at backbone, neck, or pre_logits stage', 'run forward pass in tensor, predict, or loss mode on a batch of input images', 'predict class labels from a batch of input images using the classifier head', 'calculate classification losses from input images and annotated data samples', 'build a TimmClassifier with a pretrained resnet50 model for image classification', 'run a forward pass on input tensors through the TimmClassifier model', 'extract feature representations from input images using the TimmClassifier model', 'predict class labels and scores for input images using the TimmClassifier', 'compute classification loss for a batch of inputs and ground truth labels']
```

Usage

```
{'build_timm_classifier': 'build a TimmClassifier with a pretrained resnet50 model for image classification', 'forward_timm_classifier': 'run a forward pass on input tensors through the TimmClassifier model', 'extract_feat_timm_classifier': 'extract feature representations from input images using the TimmClassifier model', 'predict_timm_classifier': 'predict class labels and scores for input images using the TimmClassifier', 'loss_timm_classifier': 'compute classification loss for a batch of inputs and ground truth labels'}
```

