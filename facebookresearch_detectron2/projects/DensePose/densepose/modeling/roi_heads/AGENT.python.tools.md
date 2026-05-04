# Agent Python Tools

- repo: facebookresearch/detectron2
- repo_uri: https://github.com/facebookresearch/detectron2.git

## File: facebookresearch_detectron2/projects/DensePose/densepose/modeling/roi_heads/deeplab.py

Prompts

```
['build a DensePoseDeepLabHead module using ASPP and stacked convolutions for dense pose estimation', 'create an ASPP module with atrous convolutions at rates 6, 12, and 56 for multi-scale feature extraction', 'create a NONLocalBlock2D module to capture long-range spatial dependencies in 2D feature maps', 'review the ASPPConv class that applies dilated convolution with GroupNorm and ReLU activation', 'test the ASPPPooling forward pass that performs adaptive average pooling then bilinear interpolation', 'build a DensePose ROI heads module that extends StandardROIHeads with DensePose prediction capabilities', 'create a Decoder forward pass that merges FPN features from all pyramid levels into a single output', 'test the DensePoseROIHeads forward method to compute DensePose losses during training', 'review the DensePoseROIHeads _init_densepose_head method that configures the pooler, head, predictor, and losses', 'refactor the DensePoseROIHeads forward_with_given_boxes method to produce per-ROI DensePose outputs from given boxes', 'build a DensePoseV1ConvXHead with config and input channels for fully convolutional DensePose head', 'run the forward pass of DensePoseV1ConvXHead on input feature tensors to get head outputs', 'review the DensePoseV1ConvXHead __init__ to understand stacked conv layer configuration and initialization', 'test the DensePoseV1ConvXHead forward method with sample feature tensors and verify output shape', 'summarize the DensePoseV1ConvXHead class which implements a fully convolutional head with stacked ReLU conv layers']
```

Usage

```
{'build_densepose_deeplab_head': 'build a DensePoseDeepLabHead module using ASPP and stacked convolutions for dense pose estimation', 'create_aspp_module': 'create an ASPP module with atrous convolutions at rates 6, 12, and 56 for multi-scale feature extraction', 'create_nonlocal_block_2d': 'create a NONLocalBlock2D module to capture long-range spatial dependencies in 2D feature maps', 'review_asppconv_class': 'review the ASPPConv class that applies dilated convolution with GroupNorm and ReLU activation', 'test_aspppooling_forward': 'test the ASPPPooling forward pass that performs adaptive average pooling then bilinear interpolation'}
```

## File: facebookresearch_detectron2/projects/DensePose/densepose/modeling/roi_heads/roi_head.py

Prompts

```
['build a DensePoseDeepLabHead module using ASPP and stacked convolutions for dense pose estimation', 'create an ASPP module with atrous convolutions at rates 6, 12, and 56 for multi-scale feature extraction', 'create a NONLocalBlock2D module to capture long-range spatial dependencies in 2D feature maps', 'review the ASPPConv class that applies dilated convolution with GroupNorm and ReLU activation', 'test the ASPPPooling forward pass that performs adaptive average pooling then bilinear interpolation', 'build a DensePose ROI heads module that extends StandardROIHeads with DensePose prediction capabilities', 'create a Decoder forward pass that merges FPN features from all pyramid levels into a single output', 'test the DensePoseROIHeads forward method to compute DensePose losses during training', 'review the DensePoseROIHeads _init_densepose_head method that configures the pooler, head, predictor, and losses', 'refactor the DensePoseROIHeads forward_with_given_boxes method to produce per-ROI DensePose outputs from given boxes', 'build a DensePoseV1ConvXHead with config and input channels for fully convolutional DensePose head', 'run the forward pass of DensePoseV1ConvXHead on input feature tensors to get head outputs', 'review the DensePoseV1ConvXHead __init__ to understand stacked conv layer configuration and initialization', 'test the DensePoseV1ConvXHead forward method with sample feature tensors and verify output shape', 'summarize the DensePoseV1ConvXHead class which implements a fully convolutional head with stacked ReLU conv layers']
```

Usage

```
{'build_DensePoseROIHeads': 'build a DensePose ROI heads module that extends StandardROIHeads with DensePose prediction capabilities', 'create_Decoder_forward': 'create a Decoder forward pass that merges FPN features from all pyramid levels into a single output', 'test_DensePoseROIHeads_forward': 'test the DensePoseROIHeads forward method to compute DensePose losses during training', 'review_DensePoseROIHeads_init_densepose_head': 'review the DensePoseROIHeads _init_densepose_head method that configures the pooler, head, predictor, and losses', 'refactor_DensePoseROIHeads_forward_with_given_boxes': 'refactor the DensePoseROIHeads forward_with_given_boxes method to produce per-ROI DensePose outputs from given boxes'}
```

## File: facebookresearch_detectron2/projects/DensePose/densepose/modeling/roi_heads/v1convx.py

Prompts

```
['build a DensePoseDeepLabHead module using ASPP and stacked convolutions for dense pose estimation', 'create an ASPP module with atrous convolutions at rates 6, 12, and 56 for multi-scale feature extraction', 'create a NONLocalBlock2D module to capture long-range spatial dependencies in 2D feature maps', 'review the ASPPConv class that applies dilated convolution with GroupNorm and ReLU activation', 'test the ASPPPooling forward pass that performs adaptive average pooling then bilinear interpolation', 'build a DensePose ROI heads module that extends StandardROIHeads with DensePose prediction capabilities', 'create a Decoder forward pass that merges FPN features from all pyramid levels into a single output', 'test the DensePoseROIHeads forward method to compute DensePose losses during training', 'review the DensePoseROIHeads _init_densepose_head method that configures the pooler, head, predictor, and losses', 'refactor the DensePoseROIHeads forward_with_given_boxes method to produce per-ROI DensePose outputs from given boxes', 'build a DensePoseV1ConvXHead with config and input channels for fully convolutional DensePose head', 'run the forward pass of DensePoseV1ConvXHead on input feature tensors to get head outputs', 'review the DensePoseV1ConvXHead __init__ to understand stacked conv layer configuration and initialization', 'test the DensePoseV1ConvXHead forward method with sample feature tensors and verify output shape', 'summarize the DensePoseV1ConvXHead class which implements a fully convolutional head with stacked ReLU conv layers']
```

Usage

```
{'build_DensePoseV1ConvXHead': 'build a DensePoseV1ConvXHead with config and input channels for fully convolutional DensePose head', 'run_forward_DensePoseV1ConvXHead': 'run the forward pass of DensePoseV1ConvXHead on input feature tensors to get head outputs', 'review_DensePoseV1ConvXHead_init': 'review the DensePoseV1ConvXHead __init__ to understand stacked conv layer configuration and initialization', 'test_DensePoseV1ConvXHead_forward': 'test the DensePoseV1ConvXHead forward method with sample feature tensors and verify output shape', 'summarize_DensePoseV1ConvXHead': 'summarize the DensePoseV1ConvXHead class which implements a fully convolutional head with stacked ReLU conv layers'}
```

