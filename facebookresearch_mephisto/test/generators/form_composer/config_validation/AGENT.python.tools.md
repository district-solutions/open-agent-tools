# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/test/generators/form_composer/config_validation/test_task_data_config.py

Prompts

```
['test collect_unit_config_items_to_extrapolate to extract 6 token items from a form config with template tokens', 'test verify_form_composer_configs to detect missing required config files and report validation errors', 'test verify_form_composer_configs with task_data_config_only flag to validate only the task data config file', 'test verify_form_composer_configs with all valid config files to confirm successful validation output', 'review the TestTaskDataConfig unittest class that validates Form Composer config files and token extrapolation', 'test validate_unit_config rejects non-dict input like a list and returns an error', 'test validate_unit_config detects wrong keys and reports missing required attributes', 'test validate_unit_config catches missing required fields like title and label in form config', 'test validate_unit_config detects duplicate names and ids in the form configuration', 'test validate_unit_config rejects unsupported field type values in the form config']
```

Usage

```
{'test_collect_unit_config_items_to_extrapolate': 'test collect_unit_config_items_to_extrapolate to extract 6 token items from a form config with template tokens', 'test_verify_form_composer_configs_errors': 'test verify_form_composer_configs to detect missing required config files and report validation errors', 'test_verify_form_composer_configs_task_data_only': 'test verify_form_composer_configs with task_data_config_only flag to validate only the task data config file', 'test_verify_form_composer_configs_success': 'test verify_form_composer_configs with all valid config files to confirm successful validation output', 'review_TestTaskDataConfig': 'review the TestTaskDataConfig unittest class that validates Form Composer config files and token extrapolation'}
```

## File: facebookresearch_mephisto/test/generators/form_composer/config_validation/test_unit_config.py

Prompts

```
['test collect_unit_config_items_to_extrapolate to extract 6 token items from a form config with template tokens', 'test verify_form_composer_configs to detect missing required config files and report validation errors', 'test verify_form_composer_configs with task_data_config_only flag to validate only the task data config file', 'test verify_form_composer_configs with all valid config files to confirm successful validation output', 'review the TestTaskDataConfig unittest class that validates Form Composer config files and token extrapolation', 'test validate_unit_config rejects non-dict input like a list and returns an error', 'test validate_unit_config detects wrong keys and reports missing required attributes', 'test validate_unit_config catches missing required fields like title and label in form config', 'test validate_unit_config detects duplicate names and ids in the form configuration', 'test validate_unit_config rejects unsupported field type values in the form config']
```

Usage

```
{'test_validate_unit_config_not_dict': 'test validate_unit_config rejects non-dict input like a list and returns an error', 'test_validate_unit_config_wrong_keys': 'test validate_unit_config detects wrong keys and reports missing required attributes', 'test_validate_unit_config_missing_required_fields': 'test validate_unit_config catches missing required fields like title and label in form config', 'test_validate_unit_config_duplicates': 'test validate_unit_config detects duplicate names and ids in the form configuration', 'test_validate_unit_config_invalid_field_type': 'test validate_unit_config rejects unsupported field type values in the form config'}
```

