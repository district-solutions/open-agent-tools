# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2/detectron2/checkpoint/c2_model_loading.py

Prompts

```
['convert Caffe2 backbone weight layer keys to Detectron2 naming conventions using regex substitutions', 'convert a Caffe2 Detectron weights dictionary to Detectron2 names and return the mapping', 'align checkpoint state dict keys to model state dict keys using suffix matching heuristics', 'group parameter names by their shared submodule prefix for organized checkpoint logging', 'compute the longest common dot-separated prefix across a list of parameter name strings', 'get the download URL for a named model from the ModelCatalog using ModelCatalog.get(name)', 'list all ImageNet pretrained model names available in ModelCatalog.C2_IMAGENET_MODELS dictionary', 'list all Detectron COCO baseline model names available in ModelCatalog.C2_DETECTRON_MODELS dictionary', 'resolve a catalog:// prefixed path to its local file path using ModelCatalogHandler', 'open a model file from the catalog using PathManager.open with a catalog:// URL', 'create a DetectionCheckpointer instance for a model with a specified save directory', 'load a model checkpoint from a file path using DetectionCheckpointer with distributed sync support', 'load a Detectron2 or Caffe2 pickle checkpoint file using DetectionCheckpointer _load_file method', 'load a pycls .pyth checkpoint file and extract model state using DetectionCheckpointer', 'load a model checkpoint with name-matching heuristics and Caffe2 weight conversion using _load_model']
```

Usage

```
{'convert_basic_c2_names': 'convert Caffe2 backbone weight layer keys to Detectron2 naming conventions using regex substitutions', 'convert_c2_detectron_names': 'convert a Caffe2 Detectron weights dictionary to Detectron2 names and return the mapping', 'align_and_update_state_dicts': 'align checkpoint state dict keys to model state dict keys using suffix matching heuristics', 'group_keys_by_module': 'group parameter names by their shared submodule prefix for organized checkpoint logging', 'longest_common_prefix': 'compute the longest common dot-separated prefix across a list of parameter name strings'}
```

## File: facebookresearch_banmo/third_party/detectron2/detectron2/checkpoint/catalog.py

Prompts

```
['convert Caffe2 backbone weight layer keys to Detectron2 naming conventions using regex substitutions', 'convert a Caffe2 Detectron weights dictionary to Detectron2 names and return the mapping', 'align checkpoint state dict keys to model state dict keys using suffix matching heuristics', 'group parameter names by their shared submodule prefix for organized checkpoint logging', 'compute the longest common dot-separated prefix across a list of parameter name strings', 'get the download URL for a named model from the ModelCatalog using ModelCatalog.get(name)', 'list all ImageNet pretrained model names available in ModelCatalog.C2_IMAGENET_MODELS dictionary', 'list all Detectron COCO baseline model names available in ModelCatalog.C2_DETECTRON_MODELS dictionary', 'resolve a catalog:// prefixed path to its local file path using ModelCatalogHandler', 'open a model file from the catalog using PathManager.open with a catalog:// URL', 'create a DetectionCheckpointer instance for a model with a specified save directory', 'load a model checkpoint from a file path using DetectionCheckpointer with distributed sync support', 'load a Detectron2 or Caffe2 pickle checkpoint file using DetectionCheckpointer _load_file method', 'load a pycls .pyth checkpoint file and extract model state using DetectionCheckpointer', 'load a model checkpoint with name-matching heuristics and Caffe2 weight conversion using _load_model']
```

Usage

```
{'get_model_url_by_name': 'get the download URL for a named model from the ModelCatalog using ModelCatalog.get(name)', 'list_imagenet_pretrained_models': 'list all ImageNet pretrained model names available in ModelCatalog.C2_IMAGENET_MODELS dictionary', 'list_detectron_baseline_models': 'list all Detectron COCO baseline model names available in ModelCatalog.C2_DETECTRON_MODELS dictionary', 'resolve_catalog_path': 'resolve a catalog:// prefixed path to its local file path using ModelCatalogHandler', 'open_catalog_model_file': 'open a model file from the catalog using PathManager.open with a catalog:// URL'}
```

## File: facebookresearch_banmo/third_party/detectron2/detectron2/checkpoint/detection_checkpoint.py

Prompts

```
['convert Caffe2 backbone weight layer keys to Detectron2 naming conventions using regex substitutions', 'convert a Caffe2 Detectron weights dictionary to Detectron2 names and return the mapping', 'align checkpoint state dict keys to model state dict keys using suffix matching heuristics', 'group parameter names by their shared submodule prefix for organized checkpoint logging', 'compute the longest common dot-separated prefix across a list of parameter name strings', 'get the download URL for a named model from the ModelCatalog using ModelCatalog.get(name)', 'list all ImageNet pretrained model names available in ModelCatalog.C2_IMAGENET_MODELS dictionary', 'list all Detectron COCO baseline model names available in ModelCatalog.C2_DETECTRON_MODELS dictionary', 'resolve a catalog:// prefixed path to its local file path using ModelCatalogHandler', 'open a model file from the catalog using PathManager.open with a catalog:// URL', 'create a DetectionCheckpointer instance for a model with a specified save directory', 'load a model checkpoint from a file path using DetectionCheckpointer with distributed sync support', 'load a Detectron2 or Caffe2 pickle checkpoint file using DetectionCheckpointer _load_file method', 'load a pycls .pyth checkpoint file and extract model state using DetectionCheckpointer', 'load a model checkpoint with name-matching heuristics and Caffe2 weight conversion using _load_model']
```

Usage

```
{'create_DetectionCheckpointer': 'create a DetectionCheckpointer instance for a model with a specified save directory', 'load_checkpoint_DetectionCheckpointer': 'load a model checkpoint from a file path using DetectionCheckpointer with distributed sync support', 'load_pkl_checkpoint_DetectionCheckpointer': 'load a Detectron2 or Caffe2 pickle checkpoint file using DetectionCheckpointer _load_file method', 'load_pyth_checkpoint_DetectionCheckpointer': 'load a pycls .pyth checkpoint file and extract model state using DetectionCheckpointer', 'load_model_with_heuristics_DetectionCheckpointer': 'load a model checkpoint with name-matching heuristics and Caffe2 weight conversion using _load_model'}
```

