# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/mephisto/generators/form_composer/config_validation/task_data_config.py

Prompts

```
['verify Form Composer config files are valid by checking task data, unit config, and token sets paths', 'collect all form config items including sections, fieldsets, rows, and fields from a config data dictionary', 'find and return only dynamic fieldsets with lookup_name attributes for a given section name', 'create a normal fieldset from a dynamic fieldset config by resolving tokens and adding index suffixes', 'review the Form Composer task data config module for config validation and dynamic fieldset extrapolation utilities', 'validate a form composer unit config dict and return a tuple of is_valid bool and list of error strings', 'validate a single config dict item against available attributes and return whether it is valid', 'collect unique attribute values from a config item into a mapping dict for duplicate checking', 'check if duplicate values exist for unique attributes and append error messages to the errors list', 'replace a relative HTML file path token with the actual file content from the data directory']
```

Usage

```
{'verify_form_composer_configs': 'verify Form Composer config files are valid by checking task data, unit config, and token sets paths', 'collect_unit_config_items_to_extrapolate': 'collect all form config items including sections, fieldsets, rows, and fields from a config data dictionary', 'find_dynamic_fieldsets_for_section': 'find and return only dynamic fieldsets with lookup_name attributes for a given section name', 'extrapolate_dynamic_fieldset': 'create a normal fieldset from a dynamic fieldset config by resolving tokens and adding index suffixes', 'review_task_data_config': 'review the Form Composer task data config module for config validation and dynamic fieldset extrapolation utilities'}
```

## File: facebookresearch_mephisto/mephisto/generators/form_composer/config_validation/unit_config.py

Prompts

```
['verify Form Composer config files are valid by checking task data, unit config, and token sets paths', 'collect all form config items including sections, fieldsets, rows, and fields from a config data dictionary', 'find and return only dynamic fieldsets with lookup_name attributes for a given section name', 'create a normal fieldset from a dynamic fieldset config by resolving tokens and adding index suffixes', 'review the Form Composer task data config module for config validation and dynamic fieldset extrapolation utilities', 'validate a form composer unit config dict and return a tuple of is_valid bool and list of error strings', 'validate a single config dict item against available attributes and return whether it is valid', 'collect unique attribute values from a config item into a mapping dict for duplicate checking', 'check if duplicate values exist for unique attributes and append error messages to the errors list', 'replace a relative HTML file path token with the actual file content from the data directory']
```

Usage

```
{'validate_unit_config': 'validate a form composer unit config dict and return a tuple of is_valid bool and list of error strings', 'validate_config_dict_item': 'validate a single config dict item against available attributes and return whether it is valid', 'collect_values_for_unique_attrs': 'collect unique attribute values from a config item into a mapping dict for duplicate checking', 'duplicate_values_exist': 'check if duplicate values exist for unique attributes and append error messages to the errors list', 'replace_path_to_file_with_content': 'replace a relative HTML file path token with the actual file content from the data directory'}
```

