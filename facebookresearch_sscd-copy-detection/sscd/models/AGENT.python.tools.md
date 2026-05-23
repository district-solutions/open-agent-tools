# Agent Python Tools

- repo: facebookresearch/sscd-copy-detection
- repo_uri: https://github.com/facebookresearch/sscd-copy-detection

## File: facebookresearch_sscd-copy-detection/sscd/models/gem_pooling.py

Prompts

```
['build a PyTorch module that applies generalized mean pooling with a configurable pooling parameter', 'create a forward pass that computes generalized mean pooling over spatial dimensions of a 4D tensor', 'test the GlobalGeMPool2d class by passing a non-negative 4D tensor and verifying the pooled output shape', 'refactor the GlobalGeMPool2d forward method to use a configurable minimum clamp value instead of a hardcoded 1e-6', 'review the GlobalGeMPool2d constructor to understand how the pooling parameter is initialized and stored', 'build a Model instance with a specified backbone, embedding dims, and GeM pooling parameter', 'build a backbone network from the Backbone enum using its build method with dims', 'run the Model forward pass to compute L2-normalized embeddings from input images', 'review the L2Norm module that applies F.normalize to L2-normalize feature vectors', 'test the Model add_arguments classmethod to register backbone, dims, and pool_param CLI args']
```

Usage

```
{'build_gem_pooling_layer': 'build a PyTorch module that applies generalized mean pooling with a configurable pooling parameter', 'create_gem_pooling_forward': 'create a forward pass that computes generalized mean pooling over spatial dimensions of a 4D tensor', 'test_GlobalGeMPool2d': 'test the GlobalGeMPool2d class by passing a non-negative 4D tensor and verifying the pooled output shape', 'refactor_gem_pooling_clamp': 'refactor the GlobalGeMPool2d forward method to use a configurable minimum clamp value instead of a hardcoded 1e-6', 'review_GlobalGeMPool2d_init': 'review the GlobalGeMPool2d constructor to understand how the pooling parameter is initialized and stored'}
```

## File: facebookresearch_sscd-copy-detection/sscd/models/model.py

Prompts

```
['build a PyTorch module that applies generalized mean pooling with a configurable pooling parameter', 'create a forward pass that computes generalized mean pooling over spatial dimensions of a 4D tensor', 'test the GlobalGeMPool2d class by passing a non-negative 4D tensor and verifying the pooled output shape', 'refactor the GlobalGeMPool2d forward method to use a configurable minimum clamp value instead of a hardcoded 1e-6', 'review the GlobalGeMPool2d constructor to understand how the pooling parameter is initialized and stored', 'build a Model instance with a specified backbone, embedding dims, and GeM pooling parameter', 'build a backbone network from the Backbone enum using its build method with dims', 'run the Model forward pass to compute L2-normalized embeddings from input images', 'review the L2Norm module that applies F.normalize to L2-normalize feature vectors', 'test the Model add_arguments classmethod to register backbone, dims, and pool_param CLI args']
```

Usage

```
{'build_Model_with_backbone': 'build a Model instance with a specified backbone, embedding dims, and GeM pooling parameter', 'build_Backbone_enum': 'build a backbone network from the Backbone enum using its build method with dims', 'run_Model_forward': 'run the Model forward pass to compute L2-normalized embeddings from input images', 'review_L2Norm_module': 'review the L2Norm module that applies F.normalize to L2-normalize feature vectors', 'test_Model_add_arguments': 'test the Model add_arguments classmethod to register backbone, dims, and pool_param CLI args'}
```

