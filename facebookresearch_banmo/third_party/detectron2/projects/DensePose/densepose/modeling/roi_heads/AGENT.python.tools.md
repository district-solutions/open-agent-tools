# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2/projects/DensePose/densepose/modeling/roi_heads/deeplab.py

Prompts

```
['build a DensePoseDeepLabHead module with ASPP and stacked convolutions for DensePose ROI feature extraction', 'create an ASPP module with atrous convolutions at rates 6, 12, 56 for multi-scale feature aggregation', 'create a NONLocalBlock2D module to capture long-range spatial dependencies in 2D feature maps', 'review the ASPPConv and ASPPPooling classes for atrous convolution and adaptive pooling with bilinear upsampling', 'test the _NonLocalBlockND class forward pass with theta, phi, and g projections for non-local attention', 'build a DensePose ROI heads module that extends StandardROIHeads with dense pose prediction capabilities', 'create a Decoder forward pass that merges FPN features from all pyramid levels into a single output', 'test the DensePoseROIHeads forward method to compute dense pose losses during training', 'review the DensePoseROIHeads _init_densepose_head method to configure pooler, head, predictor, and losses', 'refactor the DensePoseROIHeads forward_with_given_boxes method to produce dense pose outputs from given bounding boxes', 'build a DensePoseV1ConvXHead with config and input channels for fully convolutional DensePose head', 'run forward pass on DensePoseV1ConvXHead with input features tensor to get head outputs', 'test DensePoseV1ConvXHead initialization with stacked conv layers and configuration parameters', 'review the DensePoseV1ConvXHead forward method that applies stacked convolutions with ReLU activations', 'summarize the DensePoseV1ConvXHead class which implements a fully convolutional head with configurable stacked conv layers']
```

Usage

```
{'build_densepose_deeplab_head': 'build a DensePoseDeepLabHead module with ASPP and stacked convolutions for DensePose ROI feature extraction', 'create_aspp_module': 'create an ASPP module with atrous convolutions at rates 6, 12, 56 for multi-scale feature aggregation', 'create_nonlocal_block_2d': 'create a NONLocalBlock2D module to capture long-range spatial dependencies in 2D feature maps', 'review_asppconv_aspppooling': 'review the ASPPConv and ASPPPooling classes for atrous convolution and adaptive pooling with bilinear upsampling', 'test_nonlocal_block_nd': 'test the _NonLocalBlockND class forward pass with theta, phi, and g projections for non-local attention'}
```

## File: facebookresearch_banmo/third_party/detectron2/projects/DensePose/densepose/modeling/roi_heads/roi_head.py

Prompts

```
['build a DensePoseDeepLabHead module with ASPP and stacked convolutions for DensePose ROI feature extraction', 'create an ASPP module with atrous convolutions at rates 6, 12, 56 for multi-scale feature aggregation', 'create a NONLocalBlock2D module to capture long-range spatial dependencies in 2D feature maps', 'review the ASPPConv and ASPPPooling classes for atrous convolution and adaptive pooling with bilinear upsampling', 'test the _NonLocalBlockND class forward pass with theta, phi, and g projections for non-local attention', 'build a DensePose ROI heads module that extends StandardROIHeads with dense pose prediction capabilities', 'create a Decoder forward pass that merges FPN features from all pyramid levels into a single output', 'test the DensePoseROIHeads forward method to compute dense pose losses during training', 'review the DensePoseROIHeads _init_densepose_head method to configure pooler, head, predictor, and losses', 'refactor the DensePoseROIHeads forward_with_given_boxes method to produce dense pose outputs from given bounding boxes', 'build a DensePoseV1ConvXHead with config and input channels for fully convolutional DensePose head', 'run forward pass on DensePoseV1ConvXHead with input features tensor to get head outputs', 'test DensePoseV1ConvXHead initialization with stacked conv layers and configuration parameters', 'review the DensePoseV1ConvXHead forward method that applies stacked convolutions with ReLU activations', 'summarize the DensePoseV1ConvXHead class which implements a fully convolutional head with configurable stacked conv layers']
```

Usage

```
{'build_DensePoseROIHeads': 'build a DensePose ROI heads module that extends StandardROIHeads with dense pose prediction capabilities', 'create_Decoder_forward': 'create a Decoder forward pass that merges FPN features from all pyramid levels into a single output', 'test_DensePoseROIHeads_forward': 'test the DensePoseROIHeads forward method to compute dense pose losses during training', 'review_DensePoseROIHeads_init_densepose_head': 'review the DensePoseROIHeads _init_densepose_head method to configure pooler, head, predictor, and losses', 'refactor_DensePoseROIHeads_forward_with_given_boxes': 'refactor the DensePoseROIHeads forward_with_given_boxes method to produce dense pose outputs from given bounding boxes'}
```

## File: facebookresearch_banmo/third_party/detectron2/projects/DensePose/densepose/modeling/roi_heads/v1convx.py

Prompts

```
['build a DensePoseDeepLabHead module with ASPP and stacked convolutions for DensePose ROI feature extraction', 'create an ASPP module with atrous convolutions at rates 6, 12, 56 for multi-scale feature aggregation', 'create a NONLocalBlock2D module to capture long-range spatial dependencies in 2D feature maps', 'review the ASPPConv and ASPPPooling classes for atrous convolution and adaptive pooling with bilinear upsampling', 'test the _NonLocalBlockND class forward pass with theta, phi, and g projections for non-local attention', 'build a DensePose ROI heads module that extends StandardROIHeads with dense pose prediction capabilities', 'create a Decoder forward pass that merges FPN features from all pyramid levels into a single output', 'test the DensePoseROIHeads forward method to compute dense pose losses during training', 'review the DensePoseROIHeads _init_densepose_head method to configure pooler, head, predictor, and losses', 'refactor the DensePoseROIHeads forward_with_given_boxes method to produce dense pose outputs from given bounding boxes', 'build a DensePoseV1ConvXHead with config and input channels for fully convolutional DensePose head', 'run forward pass on DensePoseV1ConvXHead with input features tensor to get head outputs', 'test DensePoseV1ConvXHead initialization with stacked conv layers and configuration parameters', 'review the DensePoseV1ConvXHead forward method that applies stacked convolutions with ReLU activations', 'summarize the DensePoseV1ConvXHead class which implements a fully convolutional head with configurable stacked conv layers']
```

Usage

```
{'build_DensePoseV1ConvXHead': 'build a DensePoseV1ConvXHead with config and input channels for fully convolutional DensePose head', 'run_forward_DensePoseV1ConvXHead': 'run forward pass on DensePoseV1ConvXHead with input features tensor to get head outputs', 'test_DensePoseV1ConvXHead_init': 'test DensePoseV1ConvXHead initialization with stacked conv layers and configuration parameters', 'review_DensePoseV1ConvXHead_forward': 'review the DensePoseV1ConvXHead forward method that applies stacked convolutions with ReLU activations', 'summarize_DensePoseV1ConvXHead': 'summarize the DensePoseV1ConvXHead class which implements a fully convolutional head with configurable stacked conv layers'}
```

