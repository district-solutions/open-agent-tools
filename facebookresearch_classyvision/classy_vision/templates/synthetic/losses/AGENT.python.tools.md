# Agent Python Tools

- repo: facebookresearch/classyvision
- repo_uri: https://github.com/facebookresearch/classyvision

## File: facebookresearch_classyvision/classy_vision/templates/synthetic/losses/my_loss.py

Prompts

```
['create a custom ClassyLoss subclass named MyLoss that computes binary cross entropy loss', 'register the MyLoss class with the ClassyVision loss registry using the register_loss decorator', 'implement the forward method to convert targets to one-hot labels and compute binary cross entropy', 'implement the from_config class method to instantiate MyLoss without requiring config parameters', 'use PyTorch F.binary_cross_entropy to compute loss between model input and one-hot encoded target labels']
```

Usage

```
{'create_MyLoss_class': 'create a custom ClassyLoss subclass named MyLoss that computes binary cross entropy loss', 'register_MyLoss_with_decorator': 'register the MyLoss class with the ClassyVision loss registry using the register_loss decorator', 'implement_forward_method': 'implement the forward method to convert targets to one-hot labels and compute binary cross entropy', 'implement_from_config_method': 'implement the from_config class method to instantiate MyLoss without requiring config parameters', 'use_binary_cross_entropy_loss': 'use PyTorch F.binary_cross_entropy to compute loss between model input and one-hot encoded target labels'}
```

