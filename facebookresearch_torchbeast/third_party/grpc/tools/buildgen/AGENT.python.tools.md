# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/tools/buildgen/build_cleaner.py

Prompts

```
['run build_cleaner.py on a build.yaml file to produce a cleaned and sorted version', 'run build_cleaner.py with TEST=true to verify a build.yaml file is already cleaned', 'call cleaned_build_yaml_dict_as_string to convert a parsed yaml dict into a cleaned yaml string', 'call _rebuild_as_ordered_dict to reorder dictionary keys with special keys prioritized', 'call _clean_elem to sort proto files before others in headers, src, and public_headers lists', 'create a dot-accessible dictionary object from a standard Python dict using the Bunch class', 'convert nested dicts and lists into dot-accessible Bunch objects using the to_bunch function', 'merge two JSON-compatible dicts recursively with the merge_json function, extending lists and combining keys', 'review the Bunch class that extends dict to allow attribute-style access via dot notation', 'test the merge_json function to verify it correctly merges nested dicts and extends lists', 'render Mako templates from YAML input files and write output to a specified file or directory', 'import a Python plugin module from a file path and execute it in the current process', 'load a pickled dictionary from a preprocessed input file for use in template rendering', 'render templates conditionally using foreach loops and eval-based conditions from YAML control data', 'merge multiple YAML dictionary files into a single dictionary for template rendering context']
```

Usage

```
{'clean_build_yaml_file': 'run build_cleaner.py on a build.yaml file to produce a cleaned and sorted version', 'test_build_yaml_clean': 'run build_cleaner.py with TEST=true to verify a build.yaml file is already cleaned', 'cleaned_build_yaml_dict_as_string': 'call cleaned_build_yaml_dict_as_string to convert a parsed yaml dict into a cleaned yaml string', 'rebuild_as_ordered_dict': 'call _rebuild_as_ordered_dict to reorder dictionary keys with special keys prioritized', 'clean_elem': 'call _clean_elem to sort proto files before others in headers, src, and public_headers lists'}
```

## File: facebookresearch_torchbeast/third_party/grpc/tools/buildgen/bunch.py

Prompts

```
['run build_cleaner.py on a build.yaml file to produce a cleaned and sorted version', 'run build_cleaner.py with TEST=true to verify a build.yaml file is already cleaned', 'call cleaned_build_yaml_dict_as_string to convert a parsed yaml dict into a cleaned yaml string', 'call _rebuild_as_ordered_dict to reorder dictionary keys with special keys prioritized', 'call _clean_elem to sort proto files before others in headers, src, and public_headers lists', 'create a dot-accessible dictionary object from a standard Python dict using the Bunch class', 'convert nested dicts and lists into dot-accessible Bunch objects using the to_bunch function', 'merge two JSON-compatible dicts recursively with the merge_json function, extending lists and combining keys', 'review the Bunch class that extends dict to allow attribute-style access via dot notation', 'test the merge_json function to verify it correctly merges nested dicts and extends lists', 'render Mako templates from YAML input files and write output to a specified file or directory', 'import a Python plugin module from a file path and execute it in the current process', 'load a pickled dictionary from a preprocessed input file for use in template rendering', 'render templates conditionally using foreach loops and eval-based conditions from YAML control data', 'merge multiple YAML dictionary files into a single dictionary for template rendering context']
```

Usage

```
{'create_BUNCH': 'create a dot-accessible dictionary object from a standard Python dict using the Bunch class', 'convert_to_bunch': 'convert nested dicts and lists into dot-accessible Bunch objects using the to_bunch function', 'merge_json_dicts': 'merge two JSON-compatible dicts recursively with the merge_json function, extending lists and combining keys', 'review_Bunch_class': 'review the Bunch class that extends dict to allow attribute-style access via dot notation', 'test_merge_json': 'test the merge_json function to verify it correctly merges nested dicts and extends lists'}
```

## File: facebookresearch_torchbeast/third_party/grpc/tools/buildgen/mako_renderer.py

Prompts

```
['run build_cleaner.py on a build.yaml file to produce a cleaned and sorted version', 'run build_cleaner.py with TEST=true to verify a build.yaml file is already cleaned', 'call cleaned_build_yaml_dict_as_string to convert a parsed yaml dict into a cleaned yaml string', 'call _rebuild_as_ordered_dict to reorder dictionary keys with special keys prioritized', 'call _clean_elem to sort proto files before others in headers, src, and public_headers lists', 'create a dot-accessible dictionary object from a standard Python dict using the Bunch class', 'convert nested dicts and lists into dot-accessible Bunch objects using the to_bunch function', 'merge two JSON-compatible dicts recursively with the merge_json function, extending lists and combining keys', 'review the Bunch class that extends dict to allow attribute-style access via dot notation', 'test the merge_json function to verify it correctly merges nested dicts and extends lists', 'render Mako templates from YAML input files and write output to a specified file or directory', 'import a Python plugin module from a file path and execute it in the current process', 'load a pickled dictionary from a preprocessed input file for use in template rendering', 'render templates conditionally using foreach loops and eval-based conditions from YAML control data', 'merge multiple YAML dictionary files into a single dictionary for template rendering context']
```

Usage

```
{'render_mako_templates_from_yaml': 'render Mako templates from YAML input files and write output to a specified file or directory', 'import_plugin': 'import a Python plugin module from a file path and execute it in the current process', 'process_preprocessed_input': 'load a pickled dictionary from a preprocessed input file for use in template rendering', 'render_conditional_templates_with_foreach': 'render templates conditionally using foreach loops and eval-based conditions from YAML control data', 'merge_yaml_dictionaries': 'merge multiple YAML dictionary files into a single dictionary for template rendering context'}
```

