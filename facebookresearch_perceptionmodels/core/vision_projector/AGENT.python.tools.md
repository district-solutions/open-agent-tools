# Agent Python Tools

- repo: facebookresearch/perceptionmodels
- repo_uri: https://github.com/facebookresearch/perception_models

## File: facebookresearch_perceptionmodels/core/vision_projector/base.py

Prompts

```
['create a subclass of BaseProjector that implements setup_projector to define a custom vision projector', 'implement the setup_projector abstract method in a BaseProjector subclass to configure self.projector', 'pass an NLD tensor through the BaseProjector forward method to get projected output with optional pooling', 'set the adaptive_avg_pool attribute on a BaseProjector instance to apply pooling after projection', 'review the BaseProjector forward method that permutes NLD to LND, projects, and permutes back', 'build an MLPProjector that projects vision model features to a target dimension using a two-layer MLP', 'create an AdaptiveAvgPooling module that reduces token sequences by a configurable pooling ratio', 'test the MLPProjector setup_projector method to verify it creates Linear-GELU-Linear layers from args', 'review the MLPProjector init_tensors method and how it initializes linear layer weights and biases', 'summarize the AdaptiveAvgPooling forward method that reshapes tokens to 2D, pools, and flattens back']
```

Usage

```
{'create_subclass_BaseProjector': 'create a subclass of BaseProjector that implements setup_projector to define a custom vision projector', 'implement_setup_projector': 'implement the setup_projector abstract method in a BaseProjector subclass to configure self.projector', 'forward_tensor_through_projector': 'pass an NLD tensor through the BaseProjector forward method to get projected output with optional pooling', 'configure_adaptive_avg_pool': 'set the adaptive_avg_pool attribute on a BaseProjector instance to apply pooling after projection', 'review_BaseProjector_forward': 'review the BaseProjector forward method that permutes NLD to LND, projects, and permutes back'}
```

## File: facebookresearch_perceptionmodels/core/vision_projector/mlp.py

Prompts

```
['create a subclass of BaseProjector that implements setup_projector to define a custom vision projector', 'implement the setup_projector abstract method in a BaseProjector subclass to configure self.projector', 'pass an NLD tensor through the BaseProjector forward method to get projected output with optional pooling', 'set the adaptive_avg_pool attribute on a BaseProjector instance to apply pooling after projection', 'review the BaseProjector forward method that permutes NLD to LND, projects, and permutes back', 'build an MLPProjector that projects vision model features to a target dimension using a two-layer MLP', 'create an AdaptiveAvgPooling module that reduces token sequences by a configurable pooling ratio', 'test the MLPProjector setup_projector method to verify it creates Linear-GELU-Linear layers from args', 'review the MLPProjector init_tensors method and how it initializes linear layer weights and biases', 'summarize the AdaptiveAvgPooling forward method that reshapes tokens to 2D, pools, and flattens back']
```

Usage

```
{'build_mlp_projector': 'build an MLPProjector that projects vision model features to a target dimension using a two-layer MLP', 'create_adaptive_avg_pooling': 'create an AdaptiveAvgPooling module that reduces token sequences by a configurable pooling ratio', 'test_MLPProjector_setup_projector': 'test the MLPProjector setup_projector method to verify it creates Linear-GELU-Linear layers from args', 'review_MLPProjector_init_tensors': 'review the MLPProjector init_tensors method and how it initializes linear layer weights and biases', 'summarize_AdaptiveAvgPooling_forward': 'summarize the AdaptiveAvgPooling forward method that reshapes tokens to 2D, pools, and flattens back'}
```

