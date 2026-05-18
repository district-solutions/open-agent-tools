# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/test/generators/video_annotator/config_validation/test_task_data_config.py

Prompts

```
['test the verify_video_annotator_configs function to validate video annotator JSON config files', 'test the collect_unit_config_items_to_extrapolate function to extract unit config items from config data', 'verify video annotator configs are valid by providing all required JSON config files', 'verify video annotator configs and check error output when required config files are missing', 'review the TestTaskDataConfig unittest class and its test methods for video annotator config validation', 'test validate_unit_config rejects non-dict input like a list and returns an error', 'test validate_unit_config detects wrong keys in the annotator config and reports missing required attributes', 'test validate_unit_config catches missing required fields like title and label in segment_fields', 'test validate_unit_config enforces that the first segment field must be named title', 'test validate_unit_config detects duplicate id and name values across segment fields']
```

Usage

```
{'test_verify_video_annotator_configs': 'test the verify_video_annotator_configs function to validate video annotator JSON config files', 'test_collect_unit_config_items_to_extrapolate': 'test the collect_unit_config_items_to_extrapolate function to extract unit config items from config data', 'verify_video_annotator_configs_success': 'verify video annotator configs are valid by providing all required JSON config files', 'verify_video_annotator_configs_errors': 'verify video annotator configs and check error output when required config files are missing', 'review_TestTaskDataConfig': 'review the TestTaskDataConfig unittest class and its test methods for video annotator config validation'}
```

## File: facebookresearch_mephisto/test/generators/video_annotator/config_validation/test_unit_config.py

Prompts

```
['test the verify_video_annotator_configs function to validate video annotator JSON config files', 'test the collect_unit_config_items_to_extrapolate function to extract unit config items from config data', 'verify video annotator configs are valid by providing all required JSON config files', 'verify video annotator configs and check error output when required config files are missing', 'review the TestTaskDataConfig unittest class and its test methods for video annotator config validation', 'test validate_unit_config rejects non-dict input like a list and returns an error', 'test validate_unit_config detects wrong keys in the annotator config and reports missing required attributes', 'test validate_unit_config catches missing required fields like title and label in segment_fields', 'test validate_unit_config enforces that the first segment field must be named title', 'test validate_unit_config detects duplicate id and name values across segment fields']
```

Usage

```
{'test_validate_unit_config_not_dict': 'test validate_unit_config rejects non-dict input like a list and returns an error', 'test_validate_unit_config_wrong_keys': 'test validate_unit_config detects wrong keys in the annotator config and reports missing required attributes', 'test_validate_unit_config_not_all_required_fields': 'test validate_unit_config catches missing required fields like title and label in segment_fields', 'test_validate_unit_config_no_title_field': 'test validate_unit_config enforces that the first segment field must be named title', 'test_validate_unit_config_with_duplicates': 'test validate_unit_config detects duplicate id and name values across segment fields'}
```

