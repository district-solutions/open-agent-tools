# Agent Python Tools

- repo: facebookresearch/egoblur
- repo_uri: https://github.com/facebookresearch/egoblur

## File: facebookresearch_egoblur/gen2/script/detectron2/utils/env.py

Prompts

```
['set the random seed for torch, numpy, python, and cuda RNGs with a given integer seed', 'perform environment setup work including library configuration and optional custom module loading via DETECTRON2_ENV_MODULE', 'load a custom Python source file or module and run its setup_environment function for custom environment configuration', 'fix the __qualname__ and __module__ of module members so sphinx can find them during documentation builds', 'dynamically import a Python module from a given file path using importlib and optionally register it in sys.modules', 'convert a TorchScript scripted Instances object back to a regular detectron2 Instances object', 'postprocess detector results by scaling and clipping bounding boxes to the original output image dimensions', 'resize a numpy array image to new dimensions using PIL or torch interpolate depending on dtype', 'scale coordinate arrays proportionally to match a ResizeTransform dimension change', 'create a ResizeTransform that resizes an image by its shortest edge length with optional max size constraint']
```

Usage

```
{'seed_all_rng': 'set the random seed for torch, numpy, python, and cuda RNGs with a given integer seed', 'setup_environment': 'perform environment setup work including library configuration and optional custom module loading via DETECTRON2_ENV_MODULE', 'setup_custom_environment': 'load a custom Python source file or module and run its setup_environment function for custom environment configuration', 'fixup_module_metadata': 'fix the __qualname__ and __module__ of module members so sphinx can find them during documentation builds', 'import_file': 'dynamically import a Python module from a given file path using importlib and optionally register it in sys.modules'}
```

## File: facebookresearch_egoblur/gen2/script/detectron2/utils/utils.py

Prompts

```
['set the random seed for torch, numpy, python, and cuda RNGs with a given integer seed', 'perform environment setup work including library configuration and optional custom module loading via DETECTRON2_ENV_MODULE', 'load a custom Python source file or module and run its setup_environment function for custom environment configuration', 'fix the __qualname__ and __module__ of module members so sphinx can find them during documentation builds', 'dynamically import a Python module from a given file path using importlib and optionally register it in sys.modules', 'convert a TorchScript scripted Instances object back to a regular detectron2 Instances object', 'postprocess detector results by scaling and clipping bounding boxes to the original output image dimensions', 'resize a numpy array image to new dimensions using PIL or torch interpolate depending on dtype', 'scale coordinate arrays proportionally to match a ResizeTransform dimension change', 'create a ResizeTransform that resizes an image by its shortest edge length with optional max size constraint']
```

Usage

```
{'convert_scripted_instances': 'convert a TorchScript scripted Instances object back to a regular detectron2 Instances object', 'detector_postprocess': 'postprocess detector results by scaling and clipping bounding boxes to the original output image dimensions', 'ResizeTransform_apply_image': 'resize a numpy array image to new dimensions using PIL or torch interpolate depending on dtype', 'ResizeTransform_apply_coords': 'scale coordinate arrays proportionally to match a ResizeTransform dimension change', 'ResizeShortestEdge_get_transform': 'create a ResizeTransform that resizes an image by its shortest edge length with optional max size constraint'}
```

