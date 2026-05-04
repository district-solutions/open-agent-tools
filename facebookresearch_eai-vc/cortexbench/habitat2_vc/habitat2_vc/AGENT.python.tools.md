# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/cortexbench/habitat2_vc/habitat2_vc/policy.py

Prompts

```
['build an EAINet neural network with visual encoder, RNN state encoder, and previous action embedding layers', 'create an EAIPolicy instance from a DictConfig with observation space, action space, and backbone settings', 'run the EAINet forward pass with observations, RNN hidden states, previous actions, and masks', 'refactor a PyTorch module by converting all BatchNorm layers to FrozenBatchNorm for inference', 'review the EAIPolicy from_config class method that constructs a policy from an OmegaConf DictConfig', 'create a VisualEncoder instance using a ResNet backbone config with default 128x128 image size', 'create a VisualEncoder instance using a ViT or BEiT backbone config with global pooling enabled', 'run a forward pass through the VisualEncoder on a batch of image tensors to get visual embeddings', 'get the backbone model, embedding dimension, and visual transform from an existing VisualEncoder instance', 'review the VisualEncoder freeze_backbone logic that disables gradients for ResNet backbones during forward pass']
```

Usage

```
{'build_EAINet': 'build an EAINet neural network with visual encoder, RNN state encoder, and previous action embedding layers', 'create_EAIPolicy': 'create an EAIPolicy instance from a DictConfig with observation space, action space, and backbone settings', 'run_EAINet_forward': 'run the EAINet forward pass with observations, RNN hidden states, previous actions, and masks', 'refactor_convert_frozen_batchnorm': 'refactor a PyTorch module by converting all BatchNorm layers to FrozenBatchNorm for inference', 'review_EAIPolicy_from_config': 'review the EAIPolicy from_config class method that constructs a policy from an OmegaConf DictConfig'}
```

## File: facebookresearch_eai-vc/cortexbench/habitat2_vc/habitat2_vc/visual_encoder.py

Prompts

```
['build an EAINet neural network with visual encoder, RNN state encoder, and previous action embedding layers', 'create an EAIPolicy instance from a DictConfig with observation space, action space, and backbone settings', 'run the EAINet forward pass with observations, RNN hidden states, previous actions, and masks', 'refactor a PyTorch module by converting all BatchNorm layers to FrozenBatchNorm for inference', 'review the EAIPolicy from_config class method that constructs a policy from an OmegaConf DictConfig', 'create a VisualEncoder instance using a ResNet backbone config with default 128x128 image size', 'create a VisualEncoder instance using a ViT or BEiT backbone config with global pooling enabled', 'run a forward pass through the VisualEncoder on a batch of image tensors to get visual embeddings', 'get the backbone model, embedding dimension, and visual transform from an existing VisualEncoder instance', 'review the VisualEncoder freeze_backbone logic that disables gradients for ResNet backbones during forward pass']
```

Usage

```
{'create_VisualEncoder_with_resnet': 'create a VisualEncoder instance using a ResNet backbone config with default 128x128 image size', 'create_VisualEncoder_with_vit': 'create a VisualEncoder instance using a ViT or BEiT backbone config with global pooling enabled', 'forward_VisualEncoder': 'run a forward pass through the VisualEncoder on a batch of image tensors to get visual embeddings', 'get_loaded_backbone_data': 'get the backbone model, embedding dimension, and visual transform from an existing VisualEncoder instance', 'review_VisualEncoder_freeze_backbone': 'review the VisualEncoder freeze_backbone logic that disables gradients for ResNet backbones during forward pass'}
```

