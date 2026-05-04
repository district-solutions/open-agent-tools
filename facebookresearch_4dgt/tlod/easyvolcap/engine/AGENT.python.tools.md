# Agent Python Tools

- repo: facebookresearch/4dgt
- repo_uri: https://github.com/facebookresearch/4dgt

## File: facebookresearch_4dgt/tlod/easyvolcap/engine/config.py

Prompts

```
['load a config from a .py .json .yaml or .yml file using Config.fromfile and access values as attributes', 'merge a dictionary of dot-separated key-value options into an existing Config object using merge_from_dict', 'dump a Config object to a .py .json .yaml or .yml file using the dump method', 'auto-generate an argparse ArgumentParser from a config file using Config.auto_argparser', 'parse command-line KEY=VALUE arguments into a nested dict using DictAction with argparse', 'import Python modules from a list of dotted module name strings with optional failure tolerance', 'cast all elements of an iterable to a target type and return as a list or tuple', 'check whether a sequence contains only items of an expected type using is_seq_of', 'slice a list into sublists by given lengths or concatenate a list of lists into one flat list', 'decorate a function to require specific Python packages or executables before it runs', 'scan a directory recursively for files matching a suffix and return relative paths', 'open a file using either a string path or pathlib.Path object with standard open arguments', 'create a directory or verify it already exists with a specified permission mode', 'find the root directory of a git repository by walking up from a given path', 'check if a file exists at a given path and raise FileNotFoundError if missing', 'build a module instance from a config dict and Registry by specifying the type key', 'register a class or function into a Registry using the register_module decorator or direct call', 'create a new Registry instance with a name and optional parent registry for hierarchical module lookup', 'call a function with arguments extracted from a config dict matching the function signature', 'wrap a function so it can be called with a config dict as its first argument']
```

Usage

```
{'load_config_from_file': 'load a config from a .py .json .yaml or .yml file using Config.fromfile and access values as attributes', 'merge_config_from_dict': 'merge a dictionary of dot-separated key-value options into an existing Config object using merge_from_dict', 'dump_config_to_file': 'dump a Config object to a .py .json .yaml or .yml file using the dump method', 'create_argparser_from_config': 'auto-generate an argparse ArgumentParser from a config file using Config.auto_argparser', 'parse_cli_dict_args': 'parse command-line KEY=VALUE arguments into a nested dict using DictAction with argparse'}
```

## File: facebookresearch_4dgt/tlod/easyvolcap/engine/misc.py

Prompts

```
['load a config from a .py .json .yaml or .yml file using Config.fromfile and access values as attributes', 'merge a dictionary of dot-separated key-value options into an existing Config object using merge_from_dict', 'dump a Config object to a .py .json .yaml or .yml file using the dump method', 'auto-generate an argparse ArgumentParser from a config file using Config.auto_argparser', 'parse command-line KEY=VALUE arguments into a nested dict using DictAction with argparse', 'import Python modules from a list of dotted module name strings with optional failure tolerance', 'cast all elements of an iterable to a target type and return as a list or tuple', 'check whether a sequence contains only items of an expected type using is_seq_of', 'slice a list into sublists by given lengths or concatenate a list of lists into one flat list', 'decorate a function to require specific Python packages or executables before it runs', 'scan a directory recursively for files matching a suffix and return relative paths', 'open a file using either a string path or pathlib.Path object with standard open arguments', 'create a directory or verify it already exists with a specified permission mode', 'find the root directory of a git repository by walking up from a given path', 'check if a file exists at a given path and raise FileNotFoundError if missing', 'build a module instance from a config dict and Registry by specifying the type key', 'register a class or function into a Registry using the register_module decorator or direct call', 'create a new Registry instance with a name and optional parent registry for hierarchical module lookup', 'call a function with arguments extracted from a config dict matching the function signature', 'wrap a function so it can be called with a config dict as its first argument']
```

Usage

```
{'import_modules_from_strings': 'import Python modules from a list of dotted module name strings with optional failure tolerance', 'cast_iterable_elements': 'cast all elements of an iterable to a target type and return as a list or tuple', 'check_sequence_types': 'check whether a sequence contains only items of an expected type using is_seq_of', 'slice_and_concat_lists': 'slice a list into sublists by given lengths or concatenate a list of lists into one flat list', 'check_prerequisites_decorator': 'decorate a function to require specific Python packages or executables before it runs'}
```

## File: facebookresearch_4dgt/tlod/easyvolcap/engine/path.py

Prompts

```
['load a config from a .py .json .yaml or .yml file using Config.fromfile and access values as attributes', 'merge a dictionary of dot-separated key-value options into an existing Config object using merge_from_dict', 'dump a Config object to a .py .json .yaml or .yml file using the dump method', 'auto-generate an argparse ArgumentParser from a config file using Config.auto_argparser', 'parse command-line KEY=VALUE arguments into a nested dict using DictAction with argparse', 'import Python modules from a list of dotted module name strings with optional failure tolerance', 'cast all elements of an iterable to a target type and return as a list or tuple', 'check whether a sequence contains only items of an expected type using is_seq_of', 'slice a list into sublists by given lengths or concatenate a list of lists into one flat list', 'decorate a function to require specific Python packages or executables before it runs', 'scan a directory recursively for files matching a suffix and return relative paths', 'open a file using either a string path or pathlib.Path object with standard open arguments', 'create a directory or verify it already exists with a specified permission mode', 'find the root directory of a git repository by walking up from a given path', 'check if a file exists at a given path and raise FileNotFoundError if missing', 'build a module instance from a config dict and Registry by specifying the type key', 'register a class or function into a Registry using the register_module decorator or direct call', 'create a new Registry instance with a name and optional parent registry for hierarchical module lookup', 'call a function with arguments extracted from a config dict matching the function signature', 'wrap a function so it can be called with a config dict as its first argument']
```

Usage

```
{'scan_directory_for_files': 'scan a directory recursively for files matching a suffix and return relative paths', 'open_file_flexible': 'open a file using either a string path or pathlib.Path object with standard open arguments', 'create_directory_safe': 'create a directory or verify it already exists with a specified permission mode', 'find_vcs_root': 'find the root directory of a git repository by walking up from a given path', 'check_file_exists': 'check if a file exists at a given path and raise FileNotFoundError if missing'}
```

## File: facebookresearch_4dgt/tlod/easyvolcap/engine/registry.py

Prompts

```
['load a config from a .py .json .yaml or .yml file using Config.fromfile and access values as attributes', 'merge a dictionary of dot-separated key-value options into an existing Config object using merge_from_dict', 'dump a Config object to a .py .json .yaml or .yml file using the dump method', 'auto-generate an argparse ArgumentParser from a config file using Config.auto_argparser', 'parse command-line KEY=VALUE arguments into a nested dict using DictAction with argparse', 'import Python modules from a list of dotted module name strings with optional failure tolerance', 'cast all elements of an iterable to a target type and return as a list or tuple', 'check whether a sequence contains only items of an expected type using is_seq_of', 'slice a list into sublists by given lengths or concatenate a list of lists into one flat list', 'decorate a function to require specific Python packages or executables before it runs', 'scan a directory recursively for files matching a suffix and return relative paths', 'open a file using either a string path or pathlib.Path object with standard open arguments', 'create a directory or verify it already exists with a specified permission mode', 'find the root directory of a git repository by walking up from a given path', 'check if a file exists at a given path and raise FileNotFoundError if missing', 'build a module instance from a config dict and Registry by specifying the type key', 'register a class or function into a Registry using the register_module decorator or direct call', 'create a new Registry instance with a name and optional parent registry for hierarchical module lookup', 'call a function with arguments extracted from a config dict matching the function signature', 'wrap a function so it can be called with a config dict as its first argument']
```

Usage

```
{'build_from_cfg': 'build a module instance from a config dict and Registry by specifying the type key', 'register_module': 'register a class or function into a Registry using the register_module decorator or direct call', 'create_registry': 'create a new Registry instance with a name and optional parent registry for hierarchical module lookup', 'call_from_cfg': 'call a function with arguments extracted from a config dict matching the function signature', 'callable_from_cfg': 'wrap a function so it can be called with a config dict as its first argument'}
```

