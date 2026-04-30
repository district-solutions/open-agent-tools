# Agent Python Tools

- repo: huggingface/controlnetaux
- repo_uri: https://github.com/huggingface/controlnet_aux

## File: huggingface_controlnetaux/src/controlnet_aux/mlsd/models/mbv2_mlsd_large.py

Prompts

```
['build a MobileV2_MLSD_Large model instance for straight line detection using MobileNetV2 backbone', 'run the MobileNetV2 backbone forward pass to extract FPN features c1 through c5', 'create a BlockTypeA module that concatenates two feature maps with optional bilinear upsampling', 'create a BlockTypeB module with residual connection and two 3x3 convolutions', 'create a BlockTypeC module with dilated convolution, regular convolution, and 1x1 output convolution', 'build a MobileV2_MLSD_Tiny model instance for line segment detection on images', 'run the MobileNetV2 backbone to extract FPN features c2, c3, c4 from input', 'create a BlockTypeA module that fuses two feature maps with 1x1 convolutions and bilinear upsampling', 'create a BlockTypeB module with residual connection and two 3x3 convolution blocks', 'create a BlockTypeC module with dilated convolution, regular convolution, and 1x1 output projection']
```

Usage

```
{'build_MobileV2_MLSD_Large': 'build a MobileV2_MLSD_Large model instance for straight line detection using MobileNetV2 backbone', 'run_MobileNetV2_forward': 'run the MobileNetV2 backbone forward pass to extract FPN features c1 through c5', 'create_BlockTypeA': 'create a BlockTypeA module that concatenates two feature maps with optional bilinear upsampling', 'create_BlockTypeB': 'create a BlockTypeB module with residual connection and two 3x3 convolutions', 'create_BlockTypeC': 'create a BlockTypeC module with dilated convolution, regular convolution, and 1x1 output convolution'}
```

## File: huggingface_controlnetaux/src/controlnet_aux/mlsd/models/mbv2_mlsd_tiny.py

Prompts

```
['build a MobileV2_MLSD_Large model instance for straight line detection using MobileNetV2 backbone', 'run the MobileNetV2 backbone forward pass to extract FPN features c1 through c5', 'create a BlockTypeA module that concatenates two feature maps with optional bilinear upsampling', 'create a BlockTypeB module with residual connection and two 3x3 convolutions', 'create a BlockTypeC module with dilated convolution, regular convolution, and 1x1 output convolution', 'build a MobileV2_MLSD_Tiny model instance for line segment detection on images', 'run the MobileNetV2 backbone to extract FPN features c2, c3, c4 from input', 'create a BlockTypeA module that fuses two feature maps with 1x1 convolutions and bilinear upsampling', 'create a BlockTypeB module with residual connection and two 3x3 convolution blocks', 'create a BlockTypeC module with dilated convolution, regular convolution, and 1x1 output projection']
```

Usage

```
{'build_MobileV2_MLSD_Tiny': 'build a MobileV2_MLSD_Tiny model instance for line segment detection on images', 'run_MobileNetV2_backbone': 'run the MobileNetV2 backbone to extract FPN features c2, c3, c4 from input', 'create_BlockTypeA_fusion': 'create a BlockTypeA module that fuses two feature maps with 1x1 convolutions and bilinear upsampling', 'create_BlockTypeB_residual': 'create a BlockTypeB module with residual connection and two 3x3 convolution blocks', 'create_BlockTypeC_dilated': 'create a BlockTypeC module with dilated convolution, regular convolution, and 1x1 output projection'}
```

