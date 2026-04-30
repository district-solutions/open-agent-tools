# Agent Python Tools

- repo: huggingface/controlnetaux
- repo_uri: https://github.com/huggingface/controlnet_aux

## File: huggingface_controlnetaux/src/controlnet_aux/zoe/zoedepth/models/builder.py

Prompts

```
['build a zoedepth model from a config dict specifying model name and version', 'build a DepthModel instance from config for monocular depth estimation inference', 'build a zoedepth model from config for training on depth estimation datasets', 'review the build_model function that dynamically imports and constructs zoedepth models', 'test the build_model function with a sample config dict for model construction', 'run depth model inference on a tensor with padding and flip augmentation enabled', 'run depth model inference on a PIL image and return a numpy array output', 'run depth model inference with horizontal flip augmentation to improve accuracy', 'run depth model inference with padding augmentation to fix boundary artifacts', 'review the DepthModel class and its inference methods for zero-shot depth estimation', 'load a state_dict into a PyTorch model handling DataParallel and DistributedDataParallel prefix mismatches', 'load model weights from a local checkpoint file path into a PyTorch model', 'load a model state_dict from a remote URL into a PyTorch model using torch.hub', 'load model weights from a URL or local path resource string prefixed with url:: or local::', 'review the model_io module functions for loading PyTorch model state dicts from various sources']
```

Usage

```
{'build_model_from_config': 'build a zoedepth model from a config dict specifying model name and version', 'build_depth_model_for_inference': 'build a DepthModel instance from config for monocular depth estimation inference', 'build_model_for_training': 'build a zoedepth model from config for training on depth estimation datasets', 'review_build_model_function': 'review the build_model function that dynamically imports and constructs zoedepth models', 'test_build_model_with_config': 'test the build_model function with a sample config dict for model construction'}
```

## File: huggingface_controlnetaux/src/controlnet_aux/zoe/zoedepth/models/depth_model.py

Prompts

```
['build a zoedepth model from a config dict specifying model name and version', 'build a DepthModel instance from config for monocular depth estimation inference', 'build a zoedepth model from config for training on depth estimation datasets', 'review the build_model function that dynamically imports and constructs zoedepth models', 'test the build_model function with a sample config dict for model construction', 'run depth model inference on a tensor with padding and flip augmentation enabled', 'run depth model inference on a PIL image and return a numpy array output', 'run depth model inference with horizontal flip augmentation to improve accuracy', 'run depth model inference with padding augmentation to fix boundary artifacts', 'review the DepthModel class and its inference methods for zero-shot depth estimation', 'load a state_dict into a PyTorch model handling DataParallel and DistributedDataParallel prefix mismatches', 'load model weights from a local checkpoint file path into a PyTorch model', 'load a model state_dict from a remote URL into a PyTorch model using torch.hub', 'load model weights from a URL or local path resource string prefixed with url:: or local::', 'review the model_io module functions for loading PyTorch model state dicts from various sources']
```

Usage

```
{'run_depth_inference': 'run depth model inference on a tensor with padding and flip augmentation enabled', 'run_pil_inference': 'run depth model inference on a PIL image and return a numpy array output', 'run_flip_augmentation': 'run depth model inference with horizontal flip augmentation to improve accuracy', 'run_padding_augmentation': 'run depth model inference with padding augmentation to fix boundary artifacts', 'review_depth_model_class': 'review the DepthModel class and its inference methods for zero-shot depth estimation'}
```

## File: huggingface_controlnetaux/src/controlnet_aux/zoe/zoedepth/models/model_io.py

Prompts

```
['build a zoedepth model from a config dict specifying model name and version', 'build a DepthModel instance from config for monocular depth estimation inference', 'build a zoedepth model from config for training on depth estimation datasets', 'review the build_model function that dynamically imports and constructs zoedepth models', 'test the build_model function with a sample config dict for model construction', 'run depth model inference on a tensor with padding and flip augmentation enabled', 'run depth model inference on a PIL image and return a numpy array output', 'run depth model inference with horizontal flip augmentation to improve accuracy', 'run depth model inference with padding augmentation to fix boundary artifacts', 'review the DepthModel class and its inference methods for zero-shot depth estimation', 'load a state_dict into a PyTorch model handling DataParallel and DistributedDataParallel prefix mismatches', 'load model weights from a local checkpoint file path into a PyTorch model', 'load a model state_dict from a remote URL into a PyTorch model using torch.hub', 'load model weights from a URL or local path resource string prefixed with url:: or local::', 'review the model_io module functions for loading PyTorch model state dicts from various sources']
```

Usage

```
{'load_state_dict': 'load a state_dict into a PyTorch model handling DataParallel and DistributedDataParallel prefix mismatches', 'load_wts': 'load model weights from a local checkpoint file path into a PyTorch model', 'load_state_dict_from_url': 'load a model state_dict from a remote URL into a PyTorch model using torch.hub', 'load_state_from_resource': 'load model weights from a URL or local path resource string prefixed with url:: or local::', 'review_model_io': 'review the model_io module functions for loading PyTorch model state dicts from various sources'}
```

