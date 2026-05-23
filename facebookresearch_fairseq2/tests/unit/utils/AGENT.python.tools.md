# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/tests/unit/utils/test_config.py

Prompts

```
['use StandardConfigMerger to merge a target config dict with source overrides using _del_ and _set_ directives', 'test that StandardConfigMerger raises TypeError when _del_ is not a list or _set_ is not a Mapping', 'use ReplaceEnvDirective to replace ${env:VAR} and ${env:VAR:default} placeholders in config strings with environment variable values', 'build a config merger that recursively merges nested dicts while supporting _del_ and _set_ override keys', 'test that config merge raises TypeError with descriptive path messages when override keys or values have invalid types', 'test that StandardValueConverter.structure converts a dict with mixed types into a typed dataclass instance', 'test that StandardValueConverter.structure raises StructureError when data cannot be converted to the target type', 'test that StandardValueConverter.unstructure converts a typed dataclass instance back into a plain dict', 'review the StandardValueConverter class and its structure and unstructure methods for type conversion', 'review the StructureError exception class used when value structuring fails', 'parse a URI string like https://foo.com/foo2/foo3 and extract scheme, netloc, and path', 'parse a URI with params and query strings and extract each component separately', 'convert a file scheme URI like file:///root/sub1/sub2 to a pathlib Path object', 'test that Uri.parse raises UriFormatError when the input string has no URI scheme', 'test that to_path raises NotSupportedError when called on a non file scheme URI', 'create a config object and use StandardObjectValidator to validate it recursively across nested fields', 'create a class that inherits from Validatable and implements the validate method returning a ValidationResult', 'raise a ValidationError with a specific field name to attach the error to a sub-result', 'create a ValidationResult instance and add error messages using the add_error method', 'test config validation that traverses dicts, tuples, lists, and nested Validatable objects']
```

Usage

```
{'merge_config_with_overrides': 'use StandardConfigMerger to merge a target config dict with source overrides using _del_ and _set_ directives', 'test_config_merge_type_validation': 'test that StandardConfigMerger raises TypeError when _del_ is not a list or _set_ is not a Mapping', 'replace_env_directive_substitution': 'use ReplaceEnvDirective to replace ${env:VAR} and ${env:VAR:default} placeholders in config strings with environment variable values', 'build_config_merger_with_deep_merge': 'build a config merger that recursively merges nested dicts while supporting _del_ and _set_ override keys', 'test_config_directive_error_handling': 'test that config merge raises TypeError with descriptive path messages when override keys or values have invalid types'}
```

## File: facebookresearch_fairseq2/tests/unit/utils/test_structured.py

Prompts

```
['use StandardConfigMerger to merge a target config dict with source overrides using _del_ and _set_ directives', 'test that StandardConfigMerger raises TypeError when _del_ is not a list or _set_ is not a Mapping', 'use ReplaceEnvDirective to replace ${env:VAR} and ${env:VAR:default} placeholders in config strings with environment variable values', 'build a config merger that recursively merges nested dicts while supporting _del_ and _set_ override keys', 'test that config merge raises TypeError with descriptive path messages when override keys or values have invalid types', 'test that StandardValueConverter.structure converts a dict with mixed types into a typed dataclass instance', 'test that StandardValueConverter.structure raises StructureError when data cannot be converted to the target type', 'test that StandardValueConverter.unstructure converts a typed dataclass instance back into a plain dict', 'review the StandardValueConverter class and its structure and unstructure methods for type conversion', 'review the StructureError exception class used when value structuring fails', 'parse a URI string like https://foo.com/foo2/foo3 and extract scheme, netloc, and path', 'parse a URI with params and query strings and extract each component separately', 'convert a file scheme URI like file:///root/sub1/sub2 to a pathlib Path object', 'test that Uri.parse raises UriFormatError when the input string has no URI scheme', 'test that to_path raises NotSupportedError when called on a non file scheme URI', 'create a config object and use StandardObjectValidator to validate it recursively across nested fields', 'create a class that inherits from Validatable and implements the validate method returning a ValidationResult', 'raise a ValidationError with a specific field name to attach the error to a sub-result', 'create a ValidationResult instance and add error messages using the add_error method', 'test config validation that traverses dicts, tuples, lists, and nested Validatable objects']
```

Usage

```
{'test_structure_works': 'test that StandardValueConverter.structure converts a dict with mixed types into a typed dataclass instance', 'test_structure_raises_error_when_conversion_fails': 'test that StandardValueConverter.structure raises StructureError when data cannot be converted to the target type', 'test_unstructure_works': 'test that StandardValueConverter.unstructure converts a typed dataclass instance back into a plain dict', 'review_StandardValueConverter': 'review the StandardValueConverter class and its structure and unstructure methods for type conversion', 'review_StructureError': 'review the StructureError exception class used when value structuring fails'}
```

## File: facebookresearch_fairseq2/tests/unit/utils/test_uri.py

Prompts

```
['use StandardConfigMerger to merge a target config dict with source overrides using _del_ and _set_ directives', 'test that StandardConfigMerger raises TypeError when _del_ is not a list or _set_ is not a Mapping', 'use ReplaceEnvDirective to replace ${env:VAR} and ${env:VAR:default} placeholders in config strings with environment variable values', 'build a config merger that recursively merges nested dicts while supporting _del_ and _set_ override keys', 'test that config merge raises TypeError with descriptive path messages when override keys or values have invalid types', 'test that StandardValueConverter.structure converts a dict with mixed types into a typed dataclass instance', 'test that StandardValueConverter.structure raises StructureError when data cannot be converted to the target type', 'test that StandardValueConverter.unstructure converts a typed dataclass instance back into a plain dict', 'review the StandardValueConverter class and its structure and unstructure methods for type conversion', 'review the StructureError exception class used when value structuring fails', 'parse a URI string like https://foo.com/foo2/foo3 and extract scheme, netloc, and path', 'parse a URI with params and query strings and extract each component separately', 'convert a file scheme URI like file:///root/sub1/sub2 to a pathlib Path object', 'test that Uri.parse raises UriFormatError when the input string has no URI scheme', 'test that to_path raises NotSupportedError when called on a non file scheme URI', 'create a config object and use StandardObjectValidator to validate it recursively across nested fields', 'create a class that inherits from Validatable and implements the validate method returning a ValidationResult', 'raise a ValidationError with a specific field name to attach the error to a sub-result', 'create a ValidationResult instance and add error messages using the add_error method', 'test config validation that traverses dicts, tuples, lists, and nested Validatable objects']
```

Usage

```
{'parse_uri_string': 'parse a URI string like https://foo.com/foo2/foo3 and extract scheme, netloc, and path', 'parse_uri_with_params_and_query': 'parse a URI with params and query strings and extract each component separately', 'convert_file_uri_to_path': 'convert a file scheme URI like file:///root/sub1/sub2 to a pathlib Path object', 'test_uri_parse_error_handling': 'test that Uri.parse raises UriFormatError when the input string has no URI scheme', 'test_uri_to_path_error_handling': 'test that to_path raises NotSupportedError when called on a non file scheme URI'}
```

## File: facebookresearch_fairseq2/tests/unit/utils/test_validation.py

Prompts

```
['use StandardConfigMerger to merge a target config dict with source overrides using _del_ and _set_ directives', 'test that StandardConfigMerger raises TypeError when _del_ is not a list or _set_ is not a Mapping', 'use ReplaceEnvDirective to replace ${env:VAR} and ${env:VAR:default} placeholders in config strings with environment variable values', 'build a config merger that recursively merges nested dicts while supporting _del_ and _set_ override keys', 'test that config merge raises TypeError with descriptive path messages when override keys or values have invalid types', 'test that StandardValueConverter.structure converts a dict with mixed types into a typed dataclass instance', 'test that StandardValueConverter.structure raises StructureError when data cannot be converted to the target type', 'test that StandardValueConverter.unstructure converts a typed dataclass instance back into a plain dict', 'review the StandardValueConverter class and its structure and unstructure methods for type conversion', 'review the StructureError exception class used when value structuring fails', 'parse a URI string like https://foo.com/foo2/foo3 and extract scheme, netloc, and path', 'parse a URI with params and query strings and extract each component separately', 'convert a file scheme URI like file:///root/sub1/sub2 to a pathlib Path object', 'test that Uri.parse raises UriFormatError when the input string has no URI scheme', 'test that to_path raises NotSupportedError when called on a non file scheme URI', 'create a config object and use StandardObjectValidator to validate it recursively across nested fields', 'create a class that inherits from Validatable and implements the validate method returning a ValidationResult', 'raise a ValidationError with a specific field name to attach the error to a sub-result', 'create a ValidationResult instance and add error messages using the add_error method', 'test config validation that traverses dicts, tuples, lists, and nested Validatable objects']
```

Usage

```
{'validate_config_with_standard_object_validator': 'create a config object and use StandardObjectValidator to validate it recursively across nested fields', 'implement_validatable_interface': 'create a class that inherits from Validatable and implements the validate method returning a ValidationResult', 'raise_validation_error_with_field': 'raise a ValidationError with a specific field name to attach the error to a sub-result', 'build_validation_result_with_errors': 'create a ValidationResult instance and add error messages using the add_error method', 'test_validation_with_nested_configs': 'test config validation that traverses dicts, tuples, lists, and nested Validatable objects'}
```

