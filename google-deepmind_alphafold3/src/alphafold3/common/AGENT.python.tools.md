# Agent Python Tools

- repo: google-deepmind/alphafold3
- repo_uri: https://github.com/google-deepmind/alphafold3

## File: google-deepmind_alphafold3/src/alphafold3/common/base_config.py

Prompts

```
['create a subclass of BaseConfig to define a typed configuration dataclass with keyword-only fields', 'coerce a dictionary into a BaseConfig subclass instance by passing the dict as keyword arguments', 'use autocreate to set a field default that auto-constructs a nested config from its type', 'call as_dict on a BaseConfig instance to recursively serialize nested configs to a plain dictionary', 'use _strip_optional to transform a type annotation of the form T | None into just T', 'create a python module that loads an AlphaFold 3 Input from a JSON string using Input.from_json', 'create a python module that loads an AlphaFold 3 Input from an mmCIF string using Input.from_mmcif', 'create a python module that serializes an AlphaFold 3 Input object to a JSON string using Input.to_json', 'create a python module that converts an AlphaFold 3 Input to a Structure object using Input.to_structure', 'create a python module that loads all fold inputs from JSON files in a directory using load_fold_inputs_from_dir', 'get the absolute file path string for a named AlphaFold 3 resource relative to the data root', 'open a named AlphaFold 3 resource file in text or binary mode and return a file object', 'get the path to a named AlphaFold 3 resource directory relative to the data root', 'walk the AlphaFold 3 resource directory tree and yield directory entries like os.walk', 'access the AlphaFold 3 common data root path for locating bundled resources and data files', 'load pickle data from a binary file using the safe restricted unpickler that only allows built-in types', 'review the RestrictedUnpickler class that overrides find_class to block arbitrary object instantiation during unpickling', 'test the find_class method to ensure only allowed builtins like int, str, dict pass validation', 'summarize the ALLOWED_BUILTINS frozenset that lists safe types like NoneType, bool, bytes, dict, float, int, str, tuple', 'refactor the load function to accept a file path string instead of a binary file object']
```

Usage

```
{'create_config_subclass': 'create a subclass of BaseConfig to define a typed configuration dataclass with keyword-only fields', 'coerce_dict_to_config': 'coerce a dictionary into a BaseConfig subclass instance by passing the dict as keyword arguments', 'use_autocreate_default': 'use autocreate to set a field default that auto-constructs a nested config from its type', 'serialize_config_to_dict': 'call as_dict on a BaseConfig instance to recursively serialize nested configs to a plain dictionary', 'strip_optional_type': 'use _strip_optional to transform a type annotation of the form T | None into just T'}
```

## File: google-deepmind_alphafold3/src/alphafold3/common/folding_input.py

Prompts

```
['create a subclass of BaseConfig to define a typed configuration dataclass with keyword-only fields', 'coerce a dictionary into a BaseConfig subclass instance by passing the dict as keyword arguments', 'use autocreate to set a field default that auto-constructs a nested config from its type', 'call as_dict on a BaseConfig instance to recursively serialize nested configs to a plain dictionary', 'use _strip_optional to transform a type annotation of the form T | None into just T', 'create a python module that loads an AlphaFold 3 Input from a JSON string using Input.from_json', 'create a python module that loads an AlphaFold 3 Input from an mmCIF string using Input.from_mmcif', 'create a python module that serializes an AlphaFold 3 Input object to a JSON string using Input.to_json', 'create a python module that converts an AlphaFold 3 Input to a Structure object using Input.to_structure', 'create a python module that loads all fold inputs from JSON files in a directory using load_fold_inputs_from_dir', 'get the absolute file path string for a named AlphaFold 3 resource relative to the data root', 'open a named AlphaFold 3 resource file in text or binary mode and return a file object', 'get the path to a named AlphaFold 3 resource directory relative to the data root', 'walk the AlphaFold 3 resource directory tree and yield directory entries like os.walk', 'access the AlphaFold 3 common data root path for locating bundled resources and data files', 'load pickle data from a binary file using the safe restricted unpickler that only allows built-in types', 'review the RestrictedUnpickler class that overrides find_class to block arbitrary object instantiation during unpickling', 'test the find_class method to ensure only allowed builtins like int, str, dict pass validation', 'summarize the ALLOWED_BUILTINS frozenset that lists safe types like NoneType, bool, bytes, dict, float, int, str, tuple', 'refactor the load function to accept a file path string instead of a binary file object']
```

Usage

```
{'load_input_from_json': 'create a python module that loads an AlphaFold 3 Input from a JSON string using Input.from_json', 'load_input_from_mmcif': 'create a python module that loads an AlphaFold 3 Input from an mmCIF string using Input.from_mmcif', 'serialize_input_to_json': 'create a python module that serializes an AlphaFold 3 Input object to a JSON string using Input.to_json', 'convert_input_to_structure': 'create a python module that converts an AlphaFold 3 Input to a Structure object using Input.to_structure', 'load_fold_inputs_from_dir': 'create a python module that loads all fold inputs from JSON files in a directory using load_fold_inputs_from_dir'}
```

## File: google-deepmind_alphafold3/src/alphafold3/common/resources.py

Prompts

```
['create a subclass of BaseConfig to define a typed configuration dataclass with keyword-only fields', 'coerce a dictionary into a BaseConfig subclass instance by passing the dict as keyword arguments', 'use autocreate to set a field default that auto-constructs a nested config from its type', 'call as_dict on a BaseConfig instance to recursively serialize nested configs to a plain dictionary', 'use _strip_optional to transform a type annotation of the form T | None into just T', 'create a python module that loads an AlphaFold 3 Input from a JSON string using Input.from_json', 'create a python module that loads an AlphaFold 3 Input from an mmCIF string using Input.from_mmcif', 'create a python module that serializes an AlphaFold 3 Input object to a JSON string using Input.to_json', 'create a python module that converts an AlphaFold 3 Input to a Structure object using Input.to_structure', 'create a python module that loads all fold inputs from JSON files in a directory using load_fold_inputs_from_dir', 'get the absolute file path string for a named AlphaFold 3 resource relative to the data root', 'open a named AlphaFold 3 resource file in text or binary mode and return a file object', 'get the path to a named AlphaFold 3 resource directory relative to the data root', 'walk the AlphaFold 3 resource directory tree and yield directory entries like os.walk', 'access the AlphaFold 3 common data root path for locating bundled resources and data files', 'load pickle data from a binary file using the safe restricted unpickler that only allows built-in types', 'review the RestrictedUnpickler class that overrides find_class to block arbitrary object instantiation during unpickling', 'test the find_class method to ensure only allowed builtins like int, str, dict pass validation', 'summarize the ALLOWED_BUILTINS frozenset that lists safe types like NoneType, bool, bytes, dict, float, int, str, tuple', 'refactor the load function to accept a file path string instead of a binary file object']
```

Usage

```
{'get_resource_filename': 'get the absolute file path string for a named AlphaFold 3 resource relative to the data root', 'open_resource_file': 'open a named AlphaFold 3 resource file in text or binary mode and return a file object', 'get_resource_directory': 'get the path to a named AlphaFold 3 resource directory relative to the data root', 'walk_resource_tree': 'walk the AlphaFold 3 resource directory tree and yield directory entries like os.walk', 'access_data_root': 'access the AlphaFold 3 common data root path for locating bundled resources and data files'}
```

## File: google-deepmind_alphafold3/src/alphafold3/common/safe_pickle.py

Prompts

```
['create a subclass of BaseConfig to define a typed configuration dataclass with keyword-only fields', 'coerce a dictionary into a BaseConfig subclass instance by passing the dict as keyword arguments', 'use autocreate to set a field default that auto-constructs a nested config from its type', 'call as_dict on a BaseConfig instance to recursively serialize nested configs to a plain dictionary', 'use _strip_optional to transform a type annotation of the form T | None into just T', 'create a python module that loads an AlphaFold 3 Input from a JSON string using Input.from_json', 'create a python module that loads an AlphaFold 3 Input from an mmCIF string using Input.from_mmcif', 'create a python module that serializes an AlphaFold 3 Input object to a JSON string using Input.to_json', 'create a python module that converts an AlphaFold 3 Input to a Structure object using Input.to_structure', 'create a python module that loads all fold inputs from JSON files in a directory using load_fold_inputs_from_dir', 'get the absolute file path string for a named AlphaFold 3 resource relative to the data root', 'open a named AlphaFold 3 resource file in text or binary mode and return a file object', 'get the path to a named AlphaFold 3 resource directory relative to the data root', 'walk the AlphaFold 3 resource directory tree and yield directory entries like os.walk', 'access the AlphaFold 3 common data root path for locating bundled resources and data files', 'load pickle data from a binary file using the safe restricted unpickler that only allows built-in types', 'review the RestrictedUnpickler class that overrides find_class to block arbitrary object instantiation during unpickling', 'test the find_class method to ensure only allowed builtins like int, str, dict pass validation', 'summarize the ALLOWED_BUILTINS frozenset that lists safe types like NoneType, bool, bytes, dict, float, int, str, tuple', 'refactor the load function to accept a file path string instead of a binary file object']
```

Usage

```
{'load_safe_pickle': 'load pickle data from a binary file using the safe restricted unpickler that only allows built-in types', 'review_restricted_unpickler': 'review the RestrictedUnpickler class that overrides find_class to block arbitrary object instantiation during unpickling', 'test_find_class_allowlist': 'test the find_class method to ensure only allowed builtins like int, str, dict pass validation', 'summarize_allowed_builtins': 'summarize the ALLOWED_BUILTINS frozenset that lists safe types like NoneType, bool, bytes, dict, float, int, str, tuple', 'refactor_load_function': 'refactor the load function to accept a file path string instead of a binary file object'}
```

