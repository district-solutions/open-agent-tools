# Agent Python Tools

- repo: facebookresearch/adaptiveteacher
- repo_uri: https://github.com/facebookresearch/adaptive_teacher

## File: facebookresearch_adaptiveteacher/adapteacher/modeling/meta_arch/rcnn.py

Prompts

```
['build a domain adaptation two-stage pseudo-label GeneralizedRCNN model from a Detectron2 config', 'build a two-stage pseudo-label GeneralizedRCNN model for supervised and unsupervised training branches', 'build a fully connected image discriminator with configurable convolutional layers for domain classification', 'use the gradient reverse function to negate gradients during backpropagation for domain adaptation', 'run the domain adaptation RCNN forward pass with supervised, unsupervised, or domain branches', 'build a VGG16 backbone network using make_layers with batch normalization for feature extraction', 'build a VGG16 backbone wrapped in an FPN with LastLevelMaxPool for multi-scale feature pyramids', 'create a Sequential convolutional layer stack from a VGG config list with optional batch normalization', 'review the vgg_backbone forward pass that returns a dict of features from each stage', 'refactor the vgg_backbone stage slicing logic that splits the VGG16 modules into 5 stages']
```

Usage

```
{'build_DAobjTwoStagePseudoLabGeneralizedRCNN': 'build a domain adaptation two-stage pseudo-label GeneralizedRCNN model from a Detectron2 config', 'build_TwoStagePseudoLabGeneralizedRCNN': 'build a two-stage pseudo-label GeneralizedRCNN model for supervised and unsupervised training branches', 'build_FCDiscriminator_img': 'build a fully connected image discriminator with configurable convolutional layers for domain classification', 'use_grad_reverse': 'use the gradient reverse function to negate gradients during backpropagation for domain adaptation', 'run_DAobjTwoStagePseudoLabGeneralizedRCNN_forward': 'run the domain adaptation RCNN forward pass with supervised, unsupervised, or domain branches'}
```

## File: facebookresearch_adaptiveteacher/adapteacher/modeling/meta_arch/vgg.py

Prompts

```
['build a domain adaptation two-stage pseudo-label GeneralizedRCNN model from a Detectron2 config', 'build a two-stage pseudo-label GeneralizedRCNN model for supervised and unsupervised training branches', 'build a fully connected image discriminator with configurable convolutional layers for domain classification', 'use the gradient reverse function to negate gradients during backpropagation for domain adaptation', 'run the domain adaptation RCNN forward pass with supervised, unsupervised, or domain branches', 'build a VGG16 backbone network using make_layers with batch normalization for feature extraction', 'build a VGG16 backbone wrapped in an FPN with LastLevelMaxPool for multi-scale feature pyramids', 'create a Sequential convolutional layer stack from a VGG config list with optional batch normalization', 'review the vgg_backbone forward pass that returns a dict of features from each stage', 'refactor the vgg_backbone stage slicing logic that splits the VGG16 modules into 5 stages']
```

Usage

```
{'build_vgg_backbone': 'build a VGG16 backbone network using make_layers with batch normalization for feature extraction', 'build_vgg_fpn_backbone': 'build a VGG16 backbone wrapped in an FPN with LastLevelMaxPool for multi-scale feature pyramids', 'create_make_layers': 'create a Sequential convolutional layer stack from a VGG config list with optional batch normalization', 'review_vgg_backbone_forward': 'review the vgg_backbone forward pass that returns a dict of features from each stage', 'refactor_vgg_backbone_stages': 'refactor the vgg_backbone stage slicing logic that splits the VGG16 modules into 5 stages'}
```

