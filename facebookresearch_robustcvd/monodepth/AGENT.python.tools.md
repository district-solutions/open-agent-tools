# Agent Python Tools

- repo: facebookresearch/robustcvd
- repo_uri: https://github.com/facebookresearch/robust_cvd

## File: facebookresearch_robustcvd/monodepth/depth_model.py

Prompts

```
['review the DepthModel forward method to understand image input format and metadata scaling logic', 'implement the abstract estimate_depth method in a subclass to compute depth from BGR images', 'implement the abstract save method in a DepthModel subclass to persist model weights with a label', 'create a DepthModel subclass that overrides estimate_depth and save for monocular depth estimation', 'test the DepthModel forward method with metadata scales to verify spatially varying depth adjustment', 'create a MidasV2 depth model instance by calling create_depth_model with type midas2', 'get the MidasV2Model class by calling get_depth_model with type midas2', 'list all available depth model types by calling get_depth_model_list', 'review the get_depth_model function to understand how it validates and returns model classes', 'test the create_depth_model function by instantiating a midas2 model and verifying it returns a DepthModel', 'create a MidasV2Model instance with optional CPU support for monocular depth estimation', 'estimate depth from input images using the MidasV2Model and return depth tensors', 'save the MidasV2Model state dict to a file using the save method', 'review the MidasV2Model constructor to understand GPU fallback and normalization setup', 'refactor the estimate_depth method to support custom normalization or batch reshaping']
```

Usage

```
{'review_DepthModel_forward': 'review the DepthModel forward method to understand image input format and metadata scaling logic', 'implement_estimate_depth': 'implement the abstract estimate_depth method in a subclass to compute depth from BGR images', 'implement_save': 'implement the abstract save method in a DepthModel subclass to persist model weights with a label', 'create_DepthModel_subclass': 'create a DepthModel subclass that overrides estimate_depth and save for monocular depth estimation', 'test_DepthModel_forward_scaling': 'test the DepthModel forward method with metadata scales to verify spatially varying depth adjustment'}
```

## File: facebookresearch_robustcvd/monodepth/depth_model_registry.py

Prompts

```
['review the DepthModel forward method to understand image input format and metadata scaling logic', 'implement the abstract estimate_depth method in a subclass to compute depth from BGR images', 'implement the abstract save method in a DepthModel subclass to persist model weights with a label', 'create a DepthModel subclass that overrides estimate_depth and save for monocular depth estimation', 'test the DepthModel forward method with metadata scales to verify spatially varying depth adjustment', 'create a MidasV2 depth model instance by calling create_depth_model with type midas2', 'get the MidasV2Model class by calling get_depth_model with type midas2', 'list all available depth model types by calling get_depth_model_list', 'review the get_depth_model function to understand how it validates and returns model classes', 'test the create_depth_model function by instantiating a midas2 model and verifying it returns a DepthModel', 'create a MidasV2Model instance with optional CPU support for monocular depth estimation', 'estimate depth from input images using the MidasV2Model and return depth tensors', 'save the MidasV2Model state dict to a file using the save method', 'review the MidasV2Model constructor to understand GPU fallback and normalization setup', 'refactor the estimate_depth method to support custom normalization or batch reshaping']
```

Usage

```
{'create_depth_model_midas2': 'create a MidasV2 depth model instance by calling create_depth_model with type midas2', 'get_depth_model_class': 'get the MidasV2Model class by calling get_depth_model with type midas2', 'list_available_depth_models': 'list all available depth model types by calling get_depth_model_list', 'review_get_depth_model': 'review the get_depth_model function to understand how it validates and returns model classes', 'test_create_depth_model': 'test the create_depth_model function by instantiating a midas2 model and verifying it returns a DepthModel'}
```

## File: facebookresearch_robustcvd/monodepth/midas_v2_model.py

Prompts

```
['review the DepthModel forward method to understand image input format and metadata scaling logic', 'implement the abstract estimate_depth method in a subclass to compute depth from BGR images', 'implement the abstract save method in a DepthModel subclass to persist model weights with a label', 'create a DepthModel subclass that overrides estimate_depth and save for monocular depth estimation', 'test the DepthModel forward method with metadata scales to verify spatially varying depth adjustment', 'create a MidasV2 depth model instance by calling create_depth_model with type midas2', 'get the MidasV2Model class by calling get_depth_model with type midas2', 'list all available depth model types by calling get_depth_model_list', 'review the get_depth_model function to understand how it validates and returns model classes', 'test the create_depth_model function by instantiating a midas2 model and verifying it returns a DepthModel', 'create a MidasV2Model instance with optional CPU support for monocular depth estimation', 'estimate depth from input images using the MidasV2Model and return depth tensors', 'save the MidasV2Model state dict to a file using the save method', 'review the MidasV2Model constructor to understand GPU fallback and normalization setup', 'refactor the estimate_depth method to support custom normalization or batch reshaping']
```

Usage

```
{'create_MidasV2Model': 'create a MidasV2Model instance with optional CPU support for monocular depth estimation', 'estimate_depth_images': 'estimate depth from input images using the MidasV2Model and return depth tensors', 'save_model_state': 'save the MidasV2Model state dict to a file using the save method', 'review_MidasV2Model_init': 'review the MidasV2Model constructor to understand GPU fallback and normalization setup', 'refactor_estimate_depth': 'refactor the estimate_depth method to support custom normalization or batch reshaping'}
```

