# Agent Python Tools

- repo: facebookresearch/detectron2
- repo_uri: https://github.com/facebookresearch/detectron2.git

## File: facebookresearch_detectron2/detectron2/checkpoint/c2_model_loading.py

Prompts

```
['convert basic Caffe2 weight names to Detectron2 naming conventions for backbone models', 'convert Caffe2 Detectron weight dict to Detectron2 weight dict with name mapping', 'align and update model state dict with checkpoint state dict using heuristic name matching', 'summarize how convert_c2_detectron_names maps Caffe2 blob names to Detectron2 module names', 'review align_and_update_state_dicts and its suffix-based key matching strategy for loading pretrained weights', 'resolve a model catalog URL by name using ModelCatalog.get to retrieve the S3 download URL', 'lookup an ImageNet pretrained model URL from ModelCatalog.C2_IMAGENET_MODELS mappings', 'get a Caffe2 Detectron baseline model URL from ModelCatalog.C2_DETECTRON_MODELS mappings', 'register ModelCatalogHandler with PathManager to resolve catalog:// prefixed paths', 'open a model file from the catalog using catalog:// prefixed path via ModelCatalogHandler._open', 'create a DetectionCheckpointer instance to handle model checkpoint loading and saving with distributed data parallel support', 'load a model checkpoint from a file path supporting Detectron2, Caffe2, and pycls checkpoint formats', 'handle distributed checkpoint loading by verifying file availability across all workers before loading', 'convert legacy Caffe2 or Detectron1 checkpoint state dicts using name-matching heuristics for model weight alignment', 'ignore missing pixel_mean and pixel_std keys during checkpoint loading since they are initialized from config']
```

Usage

```
{'convert_basic_c2_names': 'convert basic Caffe2 weight names to Detectron2 naming conventions for backbone models', 'convert_c2_detectron_names': 'convert Caffe2 Detectron weight dict to Detectron2 weight dict with name mapping', 'align_and_update_state_dicts': 'align and update model state dict with checkpoint state dict using heuristic name matching', 'summarize_convert_c2_detectron_names': 'summarize how convert_c2_detectron_names maps Caffe2 blob names to Detectron2 module names', 'review_align_and_update_state_dicts': 'review align_and_update_state_dicts and its suffix-based key matching strategy for loading pretrained weights'}
```

## File: facebookresearch_detectron2/detectron2/checkpoint/catalog.py

Prompts

```
['convert basic Caffe2 weight names to Detectron2 naming conventions for backbone models', 'convert Caffe2 Detectron weight dict to Detectron2 weight dict with name mapping', 'align and update model state dict with checkpoint state dict using heuristic name matching', 'summarize how convert_c2_detectron_names maps Caffe2 blob names to Detectron2 module names', 'review align_and_update_state_dicts and its suffix-based key matching strategy for loading pretrained weights', 'resolve a model catalog URL by name using ModelCatalog.get to retrieve the S3 download URL', 'lookup an ImageNet pretrained model URL from ModelCatalog.C2_IMAGENET_MODELS mappings', 'get a Caffe2 Detectron baseline model URL from ModelCatalog.C2_DETECTRON_MODELS mappings', 'register ModelCatalogHandler with PathManager to resolve catalog:// prefixed paths', 'open a model file from the catalog using catalog:// prefixed path via ModelCatalogHandler._open', 'create a DetectionCheckpointer instance to handle model checkpoint loading and saving with distributed data parallel support', 'load a model checkpoint from a file path supporting Detectron2, Caffe2, and pycls checkpoint formats', 'handle distributed checkpoint loading by verifying file availability across all workers before loading', 'convert legacy Caffe2 or Detectron1 checkpoint state dicts using name-matching heuristics for model weight alignment', 'ignore missing pixel_mean and pixel_std keys during checkpoint loading since they are initialized from config']
```

Usage

```
{'resolve_model_catalog_url': 'resolve a model catalog URL by name using ModelCatalog.get to retrieve the S3 download URL', 'lookup_imagenet_pretrained_model': 'lookup an ImageNet pretrained model URL from ModelCatalog.C2_IMAGENET_MODELS mappings', 'get_detectron_baseline_url': 'get a Caffe2 Detectron baseline model URL from ModelCatalog.C2_DETECTRON_MODELS mappings', 'register_catalog_path_handler': 'register ModelCatalogHandler with PathManager to resolve catalog:// prefixed paths', 'open_catalog_model_file': 'open a model file from the catalog using catalog:// prefixed path via ModelCatalogHandler._open'}
```

## File: facebookresearch_detectron2/detectron2/checkpoint/detection_checkpoint.py

Prompts

```
['convert basic Caffe2 weight names to Detectron2 naming conventions for backbone models', 'convert Caffe2 Detectron weight dict to Detectron2 weight dict with name mapping', 'align and update model state dict with checkpoint state dict using heuristic name matching', 'summarize how convert_c2_detectron_names maps Caffe2 blob names to Detectron2 module names', 'review align_and_update_state_dicts and its suffix-based key matching strategy for loading pretrained weights', 'resolve a model catalog URL by name using ModelCatalog.get to retrieve the S3 download URL', 'lookup an ImageNet pretrained model URL from ModelCatalog.C2_IMAGENET_MODELS mappings', 'get a Caffe2 Detectron baseline model URL from ModelCatalog.C2_DETECTRON_MODELS mappings', 'register ModelCatalogHandler with PathManager to resolve catalog:// prefixed paths', 'open a model file from the catalog using catalog:// prefixed path via ModelCatalogHandler._open', 'create a DetectionCheckpointer instance to handle model checkpoint loading and saving with distributed data parallel support', 'load a model checkpoint from a file path supporting Detectron2, Caffe2, and pycls checkpoint formats', 'handle distributed checkpoint loading by verifying file availability across all workers before loading', 'convert legacy Caffe2 or Detectron1 checkpoint state dicts using name-matching heuristics for model weight alignment', 'ignore missing pixel_mean and pixel_std keys during checkpoint loading since they are initialized from config']
```

Usage

```
{'create_DetectionCheckpointer': 'create a DetectionCheckpointer instance to handle model checkpoint loading and saving with distributed data parallel support', 'load_DetectionCheckpointer_checkpoint': 'load a model checkpoint from a file path supporting Detectron2, Caffe2, and pycls checkpoint formats', 'handle_DistributedDataParallel_load': 'handle distributed checkpoint loading by verifying file availability across all workers before loading', 'convert_legacy_Caffe2_checkpoint': 'convert legacy Caffe2 or Detectron1 checkpoint state dicts using name-matching heuristics for model weight alignment', 'ignore_missing_pixel_mean_pixel_std': 'ignore missing pixel_mean and pixel_std keys during checkpoint loading since they are initialized from config'}
```

