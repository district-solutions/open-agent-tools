# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2_old/detectron2/checkpoint/c2_model_loading.py

Prompts

```
['convert Caffe2 backbone weight layer keys to Detectron2 naming conventions using regex substitutions', 'convert a Caffe2 Detectron weights dictionary to Detectron2 names and return the mapping', 'align checkpoint state dict keys to model state dict keys using suffix matching heuristics', 'group parameter names by their submodule prefix for organized checkpoint weight logging', 'find the longest common dot-separated prefix across a list of parameter name strings', 'get the download URL for a named model from the ModelCatalog using ModelCatalog.get()', 'get the S3 URL for an ImageNet pretrained model using ModelCatalog._get_c2_imagenet_pretrained()', 'get the S3 URL for a Detectron COCO baseline model using ModelCatalog._get_c2_detectron_baseline()', 'resolve a catalog:// prefixed path to its local file path using ModelCatalogHandler._get_local_path()', 'open a catalog:// prefixed model file for reading using ModelCatalogHandler._open()', 'create a DetectionCheckpointer instance for a model with a specified save directory', 'load a model checkpoint from a file path using DetectionCheckpointer load method', 'load a Caffe2 or Detectron1 model zoo checkpoint in pkl format with automatic conversion', 'load a pycls checkpoint in pyth format and extract model state for loading', 'review the DetectionCheckpointer _load_model method for Caffe2 weight alignment and pixel buffer handling']
```

Usage

```
{'convert_basic_c2_names': 'convert Caffe2 backbone weight layer keys to Detectron2 naming conventions using regex substitutions', 'convert_c2_detectron_names': 'convert a Caffe2 Detectron weights dictionary to Detectron2 names and return the mapping', 'align_and_update_state_dicts': 'align checkpoint state dict keys to model state dict keys using suffix matching heuristics', 'group_keys_by_module': 'group parameter names by their submodule prefix for organized checkpoint weight logging', 'longest_common_prefix': 'find the longest common dot-separated prefix across a list of parameter name strings'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/detectron2/checkpoint/catalog.py

Prompts

```
['convert Caffe2 backbone weight layer keys to Detectron2 naming conventions using regex substitutions', 'convert a Caffe2 Detectron weights dictionary to Detectron2 names and return the mapping', 'align checkpoint state dict keys to model state dict keys using suffix matching heuristics', 'group parameter names by their submodule prefix for organized checkpoint weight logging', 'find the longest common dot-separated prefix across a list of parameter name strings', 'get the download URL for a named model from the ModelCatalog using ModelCatalog.get()', 'get the S3 URL for an ImageNet pretrained model using ModelCatalog._get_c2_imagenet_pretrained()', 'get the S3 URL for a Detectron COCO baseline model using ModelCatalog._get_c2_detectron_baseline()', 'resolve a catalog:// prefixed path to its local file path using ModelCatalogHandler._get_local_path()', 'open a catalog:// prefixed model file for reading using ModelCatalogHandler._open()', 'create a DetectionCheckpointer instance for a model with a specified save directory', 'load a model checkpoint from a file path using DetectionCheckpointer load method', 'load a Caffe2 or Detectron1 model zoo checkpoint in pkl format with automatic conversion', 'load a pycls checkpoint in pyth format and extract model state for loading', 'review the DetectionCheckpointer _load_model method for Caffe2 weight alignment and pixel buffer handling']
```

Usage

```
{'get_model_url': 'get the download URL for a named model from the ModelCatalog using ModelCatalog.get()', 'get_imagenet_pretrained_url': 'get the S3 URL for an ImageNet pretrained model using ModelCatalog._get_c2_imagenet_pretrained()', 'get_detectron_baseline_url': 'get the S3 URL for a Detectron COCO baseline model using ModelCatalog._get_c2_detectron_baseline()', 'resolve_catalog_path': 'resolve a catalog:// prefixed path to its local file path using ModelCatalogHandler._get_local_path()', 'open_catalog_file': 'open a catalog:// prefixed model file for reading using ModelCatalogHandler._open()'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/detectron2/checkpoint/detection_checkpoint.py

Prompts

```
['convert Caffe2 backbone weight layer keys to Detectron2 naming conventions using regex substitutions', 'convert a Caffe2 Detectron weights dictionary to Detectron2 names and return the mapping', 'align checkpoint state dict keys to model state dict keys using suffix matching heuristics', 'group parameter names by their submodule prefix for organized checkpoint weight logging', 'find the longest common dot-separated prefix across a list of parameter name strings', 'get the download URL for a named model from the ModelCatalog using ModelCatalog.get()', 'get the S3 URL for an ImageNet pretrained model using ModelCatalog._get_c2_imagenet_pretrained()', 'get the S3 URL for a Detectron COCO baseline model using ModelCatalog._get_c2_detectron_baseline()', 'resolve a catalog:// prefixed path to its local file path using ModelCatalogHandler._get_local_path()', 'open a catalog:// prefixed model file for reading using ModelCatalogHandler._open()', 'create a DetectionCheckpointer instance for a model with a specified save directory', 'load a model checkpoint from a file path using DetectionCheckpointer load method', 'load a Caffe2 or Detectron1 model zoo checkpoint in pkl format with automatic conversion', 'load a pycls checkpoint in pyth format and extract model state for loading', 'review the DetectionCheckpointer _load_model method for Caffe2 weight alignment and pixel buffer handling']
```

Usage

```
{'create_DetectionCheckpointer': 'create a DetectionCheckpointer instance for a model with a specified save directory', 'load_checkpoint_DetectionCheckpointer': 'load a model checkpoint from a file path using DetectionCheckpointer load method', 'load_Caffe2_checkpoint': 'load a Caffe2 or Detectron1 model zoo checkpoint in pkl format with automatic conversion', 'load_pycls_checkpoint': 'load a pycls checkpoint in pyth format and extract model state for loading', 'review_DetectionCheckpointer_load_model': 'review the DetectionCheckpointer _load_model method for Caffe2 weight alignment and pixel buffer handling'}
```

