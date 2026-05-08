# Agent Python Tools

- repo: facebookresearch/cutler
- repo_uri: https://github.com/facebookresearch/cutler

## File: facebookresearch_cutler/cutler/modeling/meta_arch/build.py

Prompts

```
['build a model architecture from a detectron2 config object using the registered meta-architecture', 'register a new meta-architecture class in the META_ARCH_REGISTRY for model building', 'get a registered meta-architecture constructor from META_ARCH_REGISTRY by name', 'build a model and move it to the specified torch device from config', 'log API usage when a specific meta-architecture is instantiated via build_model', 'build a GeneralizedRCNN model from a detectron2 config with backbone, proposal generator, and ROI heads', 'run the GeneralizedRCNN forward pass in training mode to compute detection losses from batched inputs', 'run inference with GeneralizedRCNN to detect instances with predicted boxes, classes, and scores on input images', 'build a ProposalNetwork model from a detectron2 config with backbone and proposal generator for object proposals', 'run the ProposalNetwork forward pass to generate object proposals with boxes and objectness logits']
```

Usage

```
{'build_model_from_cfg': 'build a model architecture from a detectron2 config object using the registered meta-architecture', 'register_meta_architecture': 'register a new meta-architecture class in the META_ARCH_REGISTRY for model building', 'get_registered_meta_arch': 'get a registered meta-architecture constructor from META_ARCH_REGISTRY by name', 'build_model_with_device': 'build a model and move it to the specified torch device from config', 'log_meta_arch_usage': 'log API usage when a specific meta-architecture is instantiated via build_model'}
```

## File: facebookresearch_cutler/cutler/modeling/meta_arch/rcnn.py

Prompts

```
['build a model architecture from a detectron2 config object using the registered meta-architecture', 'register a new meta-architecture class in the META_ARCH_REGISTRY for model building', 'get a registered meta-architecture constructor from META_ARCH_REGISTRY by name', 'build a model and move it to the specified torch device from config', 'log API usage when a specific meta-architecture is instantiated via build_model', 'build a GeneralizedRCNN model from a detectron2 config with backbone, proposal generator, and ROI heads', 'run the GeneralizedRCNN forward pass in training mode to compute detection losses from batched inputs', 'run inference with GeneralizedRCNN to detect instances with predicted boxes, classes, and scores on input images', 'build a ProposalNetwork model from a detectron2 config with backbone and proposal generator for object proposals', 'run the ProposalNetwork forward pass to generate object proposals with boxes and objectness logits']
```

Usage

```
{'build_GeneralizedRCNN_from_config': 'build a GeneralizedRCNN model from a detectron2 config with backbone, proposal generator, and ROI heads', 'run_GeneralizedRCNN_forward_training': 'run the GeneralizedRCNN forward pass in training mode to compute detection losses from batched inputs', 'run_GeneralizedRCNN_inference': 'run inference with GeneralizedRCNN to detect instances with predicted boxes, classes, and scores on input images', 'build_ProposalNetwork_from_config': 'build a ProposalNetwork model from a detectron2 config with backbone and proposal generator for object proposals', 'run_ProposalNetwork_forward': 'run the ProposalNetwork forward pass to generate object proposals with boxes and objectness logits'}
```

