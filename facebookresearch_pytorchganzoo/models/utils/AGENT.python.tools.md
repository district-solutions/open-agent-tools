# Agent Python Tools

- repo: facebookresearch/pytorchganzoo
- repo_uri: https://github.com/facebookresearch/pytorch_gan_zoo

## File: facebookresearch_pytorchganzoo/models/utils/config.py

Prompts

```
['create a config object by merging an input dictionary with a default config object', 'update a config object with fields from another config object or dictionary', 'parse a string value into a boolean using common yes no true false variants', 'add argparse arguments to a parser based on the attributes of a default config object', 'extract config object members into a dictionary using a reference config as a template', 'create a NumpyResize transform to resize a numpy array image to a given size using bilinear interpolation', 'create a NumpyFlip transform to randomly flip a numpy array image horizontally with configurable probability', 'create a NumpyToTensor transform to convert a numpy array image into a PyTorch tensor', 'load an image from a file path as a PIL RGB image or numpy array using pil_loader', 'build a standard image transform pipeline with resize, tensor conversion, and normalization using standardTransform', 'build a binary mask to split a latent vector into shape and texture network inputs', 'build a mask split with mixed noise enabled so both shape and texture use all noise dimensions', 'build a mask split that assigns conditional attributes to shape or texture networks using keySplits', 'build a basic mask split with no conditional attributes for a simple shape and texture GAN', 'review the buildMaskSplit function to understand how latent vectors are split into shape and texture masks', 'check PyTorch tensor gradients for inf or NaN values and zero them out', 'replace the final linear layer of a PyTorch model with a new classifier head', 'parse a model checkpoint filename to extract the model name, scale, and iteration number', 'find the latest model checkpoint files in a directory by name, scale, or iteration', 'load a state dict into a PyTorch module with fallback key matching for DataParallel']
```

Usage

```
{'create_config_from_dict': 'create a config object by merging an input dictionary with a default config object', 'update_config_object': 'update a config object with fields from another config object or dictionary', 'parse_bool_from_string': 'parse a string value into a boolean using common yes no true false variants', 'add_config_args_to_parser': 'add argparse arguments to a parser based on the attributes of a default config object', 'extract_config_to_dict': 'extract config object members into a dictionary using a reference config as a template'}
```

## File: facebookresearch_pytorchganzoo/models/utils/image_transform.py

Prompts

```
['create a config object by merging an input dictionary with a default config object', 'update a config object with fields from another config object or dictionary', 'parse a string value into a boolean using common yes no true false variants', 'add argparse arguments to a parser based on the attributes of a default config object', 'extract config object members into a dictionary using a reference config as a template', 'create a NumpyResize transform to resize a numpy array image to a given size using bilinear interpolation', 'create a NumpyFlip transform to randomly flip a numpy array image horizontally with configurable probability', 'create a NumpyToTensor transform to convert a numpy array image into a PyTorch tensor', 'load an image from a file path as a PIL RGB image or numpy array using pil_loader', 'build a standard image transform pipeline with resize, tensor conversion, and normalization using standardTransform', 'build a binary mask to split a latent vector into shape and texture network inputs', 'build a mask split with mixed noise enabled so both shape and texture use all noise dimensions', 'build a mask split that assigns conditional attributes to shape or texture networks using keySplits', 'build a basic mask split with no conditional attributes for a simple shape and texture GAN', 'review the buildMaskSplit function to understand how latent vectors are split into shape and texture masks', 'check PyTorch tensor gradients for inf or NaN values and zero them out', 'replace the final linear layer of a PyTorch model with a new classifier head', 'parse a model checkpoint filename to extract the model name, scale, and iteration number', 'find the latest model checkpoint files in a directory by name, scale, or iteration', 'load a state dict into a PyTorch module with fallback key matching for DataParallel']
```

Usage

```
{'create_numpy_resize': 'create a NumpyResize transform to resize a numpy array image to a given size using bilinear interpolation', 'create_numpy_flip': 'create a NumpyFlip transform to randomly flip a numpy array image horizontally with configurable probability', 'create_numpy_to_tensor': 'create a NumpyToTensor transform to convert a numpy array image into a PyTorch tensor', 'load_image_with_pil_loader': 'load an image from a file path as a PIL RGB image or numpy array using pil_loader', 'build_standard_transform': 'build a standard image transform pipeline with resize, tensor conversion, and normalization using standardTransform'}
```

## File: facebookresearch_pytorchganzoo/models/utils/product_module.py

Prompts

```
['create a config object by merging an input dictionary with a default config object', 'update a config object with fields from another config object or dictionary', 'parse a string value into a boolean using common yes no true false variants', 'add argparse arguments to a parser based on the attributes of a default config object', 'extract config object members into a dictionary using a reference config as a template', 'create a NumpyResize transform to resize a numpy array image to a given size using bilinear interpolation', 'create a NumpyFlip transform to randomly flip a numpy array image horizontally with configurable probability', 'create a NumpyToTensor transform to convert a numpy array image into a PyTorch tensor', 'load an image from a file path as a PIL RGB image or numpy array using pil_loader', 'build a standard image transform pipeline with resize, tensor conversion, and normalization using standardTransform', 'build a binary mask to split a latent vector into shape and texture network inputs', 'build a mask split with mixed noise enabled so both shape and texture use all noise dimensions', 'build a mask split that assigns conditional attributes to shape or texture networks using keySplits', 'build a basic mask split with no conditional attributes for a simple shape and texture GAN', 'review the buildMaskSplit function to understand how latent vectors are split into shape and texture masks', 'check PyTorch tensor gradients for inf or NaN values and zero them out', 'replace the final linear layer of a PyTorch model with a new classifier head', 'parse a model checkpoint filename to extract the model name, scale, and iteration number', 'find the latest model checkpoint files in a directory by name, scale, or iteration', 'load a state dict into a PyTorch module with fallback key matching for DataParallel']
```

Usage

```
{'build_mask_split_shape_texture': 'build a binary mask to split a latent vector into shape and texture network inputs', 'build_mask_split_mixed_noise': 'build a mask split with mixed noise enabled so both shape and texture use all noise dimensions', 'build_mask_split_conditional': 'build a mask split that assigns conditional attributes to shape or texture networks using keySplits', 'build_mask_split_simple': 'build a basic mask split with no conditional attributes for a simple shape and texture GAN', 'review_buildMaskSplit': 'review the buildMaskSplit function to understand how latent vectors are split into shape and texture masks'}
```

## File: facebookresearch_pytorchganzoo/models/utils/utils.py

Prompts

```
['create a config object by merging an input dictionary with a default config object', 'update a config object with fields from another config object or dictionary', 'parse a string value into a boolean using common yes no true false variants', 'add argparse arguments to a parser based on the attributes of a default config object', 'extract config object members into a dictionary using a reference config as a template', 'create a NumpyResize transform to resize a numpy array image to a given size using bilinear interpolation', 'create a NumpyFlip transform to randomly flip a numpy array image horizontally with configurable probability', 'create a NumpyToTensor transform to convert a numpy array image into a PyTorch tensor', 'load an image from a file path as a PIL RGB image or numpy array using pil_loader', 'build a standard image transform pipeline with resize, tensor conversion, and normalization using standardTransform', 'build a binary mask to split a latent vector into shape and texture network inputs', 'build a mask split with mixed noise enabled so both shape and texture use all noise dimensions', 'build a mask split that assigns conditional attributes to shape or texture networks using keySplits', 'build a basic mask split with no conditional attributes for a simple shape and texture GAN', 'review the buildMaskSplit function to understand how latent vectors are split into shape and texture masks', 'check PyTorch tensor gradients for inf or NaN values and zero them out', 'replace the final linear layer of a PyTorch model with a new classifier head', 'parse a model checkpoint filename to extract the model name, scale, and iteration number', 'find the latest model checkpoint files in a directory by name, scale, or iteration', 'load a state dict into a PyTorch module with fallback key matching for DataParallel']
```

Usage

```
{'finiteCheck': 'check PyTorch tensor gradients for inf or NaN values and zero them out', 'prepareClassifier': 'replace the final linear layer of a PyTorch model with a new classifier head', 'parse_state_name': 'parse a model checkpoint filename to extract the model name, scale, and iteration number', 'getLastCheckPoint': 'find the latest model checkpoint files in a directory by name, scale, or iteration', 'loadStateDictCompatible': 'load a state dict into a PyTorch module with fallback key matching for DataParallel'}
```

