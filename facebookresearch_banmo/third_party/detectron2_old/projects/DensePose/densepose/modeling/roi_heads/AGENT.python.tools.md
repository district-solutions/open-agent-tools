# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2_old/projects/DensePose/densepose/modeling/roi_heads/deeplab.py

Prompts

```
['build a DensePoseDeepLabHead module using a Detectron2 CfgNode config and input channel count', 'run the ASPP module forward pass on a feature tensor with configurable atrous rates', 'create a NONLocalBlock2D non-local attention block for 2D feature maps with batch norm', 'review the ASPPConv class that builds atrous convolution layers with group normalization and ReLU', 'test the ASPPPooling class that performs adaptive average pooling followed by bilinear interpolation', 'build a DensePoseROIHeads instance from a Detectron2 config and input shape to add DensePose prediction', 'review the Decoder forward method that merges FPN features from multiple scales into a single output', 'test the DensePoseROIHeads forward method to verify it returns instances and loss dict during training', 'refactor the _init_densepose_head method to support additional pooler configuration options', 'summarize the forward_with_given_boxes method that produces DensePose outputs using pre-existing predicted boxes', 'build a DensePoseV1ConvXHead module with stacked conv layers from a Detectron2 config node', 'run the forward pass of DensePoseV1ConvXHead on input feature tensors through stacked convolutions', 'review the DensePoseV1ConvXHead constructor to understand how stacked conv layers are configured and added', 'test the DensePoseV1ConvXHead forward method with sample feature tensors and verify output shape', 'summarize the DensePoseV1ConvXHead class which implements a fully convolutional DensePose head with configurable stacked conv layers']
```

Usage

```
{'build_DensePoseDeepLabHead': 'build a DensePoseDeepLabHead module using a Detectron2 CfgNode config and input channel count', 'run_ASPP_forward': 'run the ASPP module forward pass on a feature tensor with configurable atrous rates', 'create_NONLocalBlock2D': 'create a NONLocalBlock2D non-local attention block for 2D feature maps with batch norm', 'review_ASPPConv': 'review the ASPPConv class that builds atrous convolution layers with group normalization and ReLU', 'test_ASPPPooling': 'test the ASPPPooling class that performs adaptive average pooling followed by bilinear interpolation'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/projects/DensePose/densepose/modeling/roi_heads/roi_head.py

Prompts

```
['build a DensePoseDeepLabHead module using a Detectron2 CfgNode config and input channel count', 'run the ASPP module forward pass on a feature tensor with configurable atrous rates', 'create a NONLocalBlock2D non-local attention block for 2D feature maps with batch norm', 'review the ASPPConv class that builds atrous convolution layers with group normalization and ReLU', 'test the ASPPPooling class that performs adaptive average pooling followed by bilinear interpolation', 'build a DensePoseROIHeads instance from a Detectron2 config and input shape to add DensePose prediction', 'review the Decoder forward method that merges FPN features from multiple scales into a single output', 'test the DensePoseROIHeads forward method to verify it returns instances and loss dict during training', 'refactor the _init_densepose_head method to support additional pooler configuration options', 'summarize the forward_with_given_boxes method that produces DensePose outputs using pre-existing predicted boxes', 'build a DensePoseV1ConvXHead module with stacked conv layers from a Detectron2 config node', 'run the forward pass of DensePoseV1ConvXHead on input feature tensors through stacked convolutions', 'review the DensePoseV1ConvXHead constructor to understand how stacked conv layers are configured and added', 'test the DensePoseV1ConvXHead forward method with sample feature tensors and verify output shape', 'summarize the DensePoseV1ConvXHead class which implements a fully convolutional DensePose head with configurable stacked conv layers']
```

Usage

```
{'build_DensePoseROIHeads': 'build a DensePoseROIHeads instance from a Detectron2 config and input shape to add DensePose prediction', 'review_Decoder_forward': 'review the Decoder forward method that merges FPN features from multiple scales into a single output', 'test_DensePoseROIHeads_forward': 'test the DensePoseROIHeads forward method to verify it returns instances and loss dict during training', 'refactor_DensePoseROIHeads_init_densepose_head': 'refactor the _init_densepose_head method to support additional pooler configuration options', 'summarize_DensePoseROIHeads_forward_with_given_boxes': 'summarize the forward_with_given_boxes method that produces DensePose outputs using pre-existing predicted boxes'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/projects/DensePose/densepose/modeling/roi_heads/v1convx.py

Prompts

```
['build a DensePoseDeepLabHead module using a Detectron2 CfgNode config and input channel count', 'run the ASPP module forward pass on a feature tensor with configurable atrous rates', 'create a NONLocalBlock2D non-local attention block for 2D feature maps with batch norm', 'review the ASPPConv class that builds atrous convolution layers with group normalization and ReLU', 'test the ASPPPooling class that performs adaptive average pooling followed by bilinear interpolation', 'build a DensePoseROIHeads instance from a Detectron2 config and input shape to add DensePose prediction', 'review the Decoder forward method that merges FPN features from multiple scales into a single output', 'test the DensePoseROIHeads forward method to verify it returns instances and loss dict during training', 'refactor the _init_densepose_head method to support additional pooler configuration options', 'summarize the forward_with_given_boxes method that produces DensePose outputs using pre-existing predicted boxes', 'build a DensePoseV1ConvXHead module with stacked conv layers from a Detectron2 config node', 'run the forward pass of DensePoseV1ConvXHead on input feature tensors through stacked convolutions', 'review the DensePoseV1ConvXHead constructor to understand how stacked conv layers are configured and added', 'test the DensePoseV1ConvXHead forward method with sample feature tensors and verify output shape', 'summarize the DensePoseV1ConvXHead class which implements a fully convolutional DensePose head with configurable stacked conv layers']
```

Usage

```
{'build_DensePoseV1ConvXHead': 'build a DensePoseV1ConvXHead module with stacked conv layers from a Detectron2 config node', 'run_forward_DensePoseV1ConvXHead': 'run the forward pass of DensePoseV1ConvXHead on input feature tensors through stacked convolutions', 'review_DensePoseV1ConvXHead_init': 'review the DensePoseV1ConvXHead constructor to understand how stacked conv layers are configured and added', 'test_DensePoseV1ConvXHead_forward': 'test the DensePoseV1ConvXHead forward method with sample feature tensors and verify output shape', 'summarize_DensePoseV1ConvXHead': 'summarize the DensePoseV1ConvXHead class which implements a fully convolutional DensePose head with configurable stacked conv layers'}
```

