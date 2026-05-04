# Agent Python Tools

- repo: facebookresearch/adaptiveteacher
- repo_uri: https://github.com/facebookresearch/adaptive_teacher

## File: facebookresearch_adaptiveteacher/prod_lib/modeling/daobj_rcnn.py

Prompts

```
['build a domain adversarial two-stage pseudo-label GeneralizedRCNN model from a Detectron2 config', 'create a fully connected image discriminator module with configurable convolutional layers for domain classification', 'run the gradient reverse function to negate gradients during backpropagation for domain adaptation', 'review the DAobjTwoStagePseudoLabGeneralizedRCNN forward method to understand supervised and unsupervised branch logic', 'summarize the FCDiscriminator_img class which implements a 3-layer Conv2d discriminator with LeakyReLU activations', 'build a VGG16 backbone for Detectron2 that outputs multi-scale feature maps from five stages', 'build a VGG16 backbone with FPN for Detectron2 using LastLevelMaxPool as the top block', 'create a Sequential module from a VGG config list with optional batch normalization layers', 'review the vgg_backbone forward method that returns a dict of features from each stage', 'refactor the VGG config dictionary to add support for custom VGG variant layer configurations']
```

Usage

```
{'build_DAobjTwoStagePseudoLabGeneralizedRCNN': 'build a domain adversarial two-stage pseudo-label GeneralizedRCNN model from a Detectron2 config', 'create_FCDiscriminator_img': 'create a fully connected image discriminator module with configurable convolutional layers for domain classification', 'run_grad_reverse': 'run the gradient reverse function to negate gradients during backpropagation for domain adaptation', 'review_DAobjTwoStagePseudoLabGeneralizedRCNN_forward': 'review the DAobjTwoStagePseudoLabGeneralizedRCNN forward method to understand supervised and unsupervised branch logic', 'summarize_FCDiscriminator_img': 'summarize the FCDiscriminator_img class which implements a 3-layer Conv2d discriminator with LeakyReLU activations'}
```

## File: facebookresearch_adaptiveteacher/prod_lib/modeling/vgg.py

Prompts

```
['build a domain adversarial two-stage pseudo-label GeneralizedRCNN model from a Detectron2 config', 'create a fully connected image discriminator module with configurable convolutional layers for domain classification', 'run the gradient reverse function to negate gradients during backpropagation for domain adaptation', 'review the DAobjTwoStagePseudoLabGeneralizedRCNN forward method to understand supervised and unsupervised branch logic', 'summarize the FCDiscriminator_img class which implements a 3-layer Conv2d discriminator with LeakyReLU activations', 'build a VGG16 backbone for Detectron2 that outputs multi-scale feature maps from five stages', 'build a VGG16 backbone with FPN for Detectron2 using LastLevelMaxPool as the top block', 'create a Sequential module from a VGG config list with optional batch normalization layers', 'review the vgg_backbone forward method that returns a dict of features from each stage', 'refactor the VGG config dictionary to add support for custom VGG variant layer configurations']
```

Usage

```
{'build_vgg_backbone': 'build a VGG16 backbone for Detectron2 that outputs multi-scale feature maps from five stages', 'build_vgg_fpn_backbone': 'build a VGG16 backbone with FPN for Detectron2 using LastLevelMaxPool as the top block', 'create_make_layers': 'create a Sequential module from a VGG config list with optional batch normalization layers', 'review_vgg_backbone_forward': 'review the vgg_backbone forward method that returns a dict of features from each stage', 'refactor_vgg_cfgs': 'refactor the VGG config dictionary to add support for custom VGG variant layer configurations'}
```

