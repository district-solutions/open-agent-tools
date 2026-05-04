# Agent Python Tools

- repo: facebookresearch/detectron2
- repo_uri: https://github.com/facebookresearch/detectron2.git

## File: facebookresearch_detectron2/projects/DensePose/densepose/utils/dbhelper.py

Prompts

```
['create an EntrySelector from a string spec using EntrySelector.from_string to filter database entries', 'create an AllEntrySelector that accepts all entries regardless of their field values', "create a FieldEntrySelector with a spec string like 'field=value' to filter entries by field", 'test the FieldEntryRangePredicate to check if an entry field falls within a specified range', 'review the FieldEntryValuePredicate class to understand strict equality checking for entry fields', 'run verbosity_to_level with an integer to get the corresponding Python logging level', 'test verbosity_to_level with 0 and verify it returns logging.WARNING', 'test verbosity_to_level with 1 and verify it returns logging.INFO', 'test verbosity_to_level with 2 or higher and verify it returns logging.DEBUG', 'test verbosity_to_level with None and verify it returns logging.WARNING', 'load DensePose transform data from a named dataset using MetadataCatalog and PathManager', 'load DensePose transform data from a Detectron2 config object using the first test dataset', 'review the load_for_dataset function that resolves a dataset name to a local transform data file path', 'review the load_from_cfg function that delegates to load_for_dataset using cfg.DATASETS.TEST', 'summarize the transform utility module that provides DensePoseTransformData loading helpers for datasets and configs']
```

Usage

```
{'create_entry_selector_from_string': 'create an EntrySelector from a string spec using EntrySelector.from_string to filter database entries', 'create_all_entry_selector': 'create an AllEntrySelector that accepts all entries regardless of their field values', 'create_field_entry_selector': "create a FieldEntrySelector with a spec string like 'field=value' to filter entries by field", 'test_field_entry_range_predicate': 'test the FieldEntryRangePredicate to check if an entry field falls within a specified range', 'review_field_entry_value_predicate': 'review the FieldEntryValuePredicate class to understand strict equality checking for entry fields'}
```

## File: facebookresearch_detectron2/projects/DensePose/densepose/utils/logger.py

Prompts

```
['create an EntrySelector from a string spec using EntrySelector.from_string to filter database entries', 'create an AllEntrySelector that accepts all entries regardless of their field values', "create a FieldEntrySelector with a spec string like 'field=value' to filter entries by field", 'test the FieldEntryRangePredicate to check if an entry field falls within a specified range', 'review the FieldEntryValuePredicate class to understand strict equality checking for entry fields', 'run verbosity_to_level with an integer to get the corresponding Python logging level', 'test verbosity_to_level with 0 and verify it returns logging.WARNING', 'test verbosity_to_level with 1 and verify it returns logging.INFO', 'test verbosity_to_level with 2 or higher and verify it returns logging.DEBUG', 'test verbosity_to_level with None and verify it returns logging.WARNING', 'load DensePose transform data from a named dataset using MetadataCatalog and PathManager', 'load DensePose transform data from a Detectron2 config object using the first test dataset', 'review the load_for_dataset function that resolves a dataset name to a local transform data file path', 'review the load_from_cfg function that delegates to load_for_dataset using cfg.DATASETS.TEST', 'summarize the transform utility module that provides DensePoseTransformData loading helpers for datasets and configs']
```

Usage

```
{'run_verbosity_to_level': 'run verbosity_to_level with an integer to get the corresponding Python logging level', 'test_verbosity_to_level_zero': 'test verbosity_to_level with 0 and verify it returns logging.WARNING', 'test_verbosity_to_level_one': 'test verbosity_to_level with 1 and verify it returns logging.INFO', 'test_verbosity_to_level_two': 'test verbosity_to_level with 2 or higher and verify it returns logging.DEBUG', 'test_verbosity_to_level_none': 'test verbosity_to_level with None and verify it returns logging.WARNING'}
```

## File: facebookresearch_detectron2/projects/DensePose/densepose/utils/transform.py

Prompts

```
['create an EntrySelector from a string spec using EntrySelector.from_string to filter database entries', 'create an AllEntrySelector that accepts all entries regardless of their field values', "create a FieldEntrySelector with a spec string like 'field=value' to filter entries by field", 'test the FieldEntryRangePredicate to check if an entry field falls within a specified range', 'review the FieldEntryValuePredicate class to understand strict equality checking for entry fields', 'run verbosity_to_level with an integer to get the corresponding Python logging level', 'test verbosity_to_level with 0 and verify it returns logging.WARNING', 'test verbosity_to_level with 1 and verify it returns logging.INFO', 'test verbosity_to_level with 2 or higher and verify it returns logging.DEBUG', 'test verbosity_to_level with None and verify it returns logging.WARNING', 'load DensePose transform data from a named dataset using MetadataCatalog and PathManager', 'load DensePose transform data from a Detectron2 config object using the first test dataset', 'review the load_for_dataset function that resolves a dataset name to a local transform data file path', 'review the load_from_cfg function that delegates to load_for_dataset using cfg.DATASETS.TEST', 'summarize the transform utility module that provides DensePoseTransformData loading helpers for datasets and configs']
```

Usage

```
{'load_transform_data_for_dataset': 'load DensePose transform data from a named dataset using MetadataCatalog and PathManager', 'load_transform_data_from_cfg': 'load DensePose transform data from a Detectron2 config object using the first test dataset', 'review_load_for_dataset': 'review the load_for_dataset function that resolves a dataset name to a local transform data file path', 'review_load_from_cfg': 'review the load_from_cfg function that delegates to load_for_dataset using cfg.DATASETS.TEST', 'summarize_transform_module': 'summarize the transform utility module that provides DensePoseTransformData loading helpers for datasets and configs'}
```

