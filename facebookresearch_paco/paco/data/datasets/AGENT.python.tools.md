# Agent Python Tools

- repo: facebookresearch/paco
- repo_uri: https://github.com/facebookresearch/paco

## File: facebookresearch_paco/paco/data/datasets/builtin.py

Prompts

```
['register all predefined PACO dataset splits including LVIS and Ego4D train val and test splits', 'review the predefined PACO dataset dictionary mapping dataset names to annotation and image root paths', 'summarize the register_all_paco function that iterates predefined datasets and calls register_instances for each', 'review the PACO annotation root environment variable defaulting to datasets/paco/annotations', 'review the PACO image root environment variable defaulting to datasets/paco/images', 'load a JSON file in LVIS annotation format and return a list of dicts in Detectron2 standard format', 'register a PACO dataset with Detectron2 DatasetCatalog and MetadataCatalog using a JSON file and image root path', 'get instance metadata including thing classes, part classes, and attribute classes for a given dataset name', 'get PACO object categories, attribute categories, and part categories sorted by id with contiguous ID mapping', 'review the load_json function to understand how LVIS-format annotations are parsed into Detectron2 standard format dicts']
```

Usage

```
{'register_all_paco': 'register all predefined PACO dataset splits including LVIS and Ego4D train val and test splits', 'review_PREDEFINED_PACO': 'review the predefined PACO dataset dictionary mapping dataset names to annotation and image root paths', 'summarize_register_all_paco': 'summarize the register_all_paco function that iterates predefined datasets and calls register_instances for each', 'review_PACO_ANNOTATION_ROOT': 'review the PACO annotation root environment variable defaulting to datasets/paco/annotations', 'review_PACO_IMAGE_ROOT': 'review the PACO image root environment variable defaulting to datasets/paco/images'}
```

## File: facebookresearch_paco/paco/data/datasets/paco.py

Prompts

```
['register all predefined PACO dataset splits including LVIS and Ego4D train val and test splits', 'review the predefined PACO dataset dictionary mapping dataset names to annotation and image root paths', 'summarize the register_all_paco function that iterates predefined datasets and calls register_instances for each', 'review the PACO annotation root environment variable defaulting to datasets/paco/annotations', 'review the PACO image root environment variable defaulting to datasets/paco/images', 'load a JSON file in LVIS annotation format and return a list of dicts in Detectron2 standard format', 'register a PACO dataset with Detectron2 DatasetCatalog and MetadataCatalog using a JSON file and image root path', 'get instance metadata including thing classes, part classes, and attribute classes for a given dataset name', 'get PACO object categories, attribute categories, and part categories sorted by id with contiguous ID mapping', 'review the load_json function to understand how LVIS-format annotations are parsed into Detectron2 standard format dicts']
```

Usage

```
{'load_json_lvis_annotations': 'load a JSON file in LVIS annotation format and return a list of dicts in Detectron2 standard format', 'register_instances_dataset': 'register a PACO dataset with Detectron2 DatasetCatalog and MetadataCatalog using a JSON file and image root path', 'get_instances_meta': 'get instance metadata including thing classes, part classes, and attribute classes for a given dataset name', 'get_object_and_attribute_classes': 'get PACO object categories, attribute categories, and part categories sorted by id with contiguous ID mapping', 'review_load_json': 'review the load_json function to understand how LVIS-format annotations are parsed into Detectron2 standard format dicts'}
```

