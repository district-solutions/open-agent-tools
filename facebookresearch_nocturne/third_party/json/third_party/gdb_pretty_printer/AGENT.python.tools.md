# Agent Python Tools

- repo: facebookresearch/nocturne
- repo_uri: https://github.com/facebookresearch/nocturne

## File: facebookresearch_nocturne/third_party/json/third_party/gdb_pretty_printer/nlohmann-json.py

Prompts

```
['load the GDB pretty printer by appending json_lookup_function to gdb.pretty_printers', 'use JsonValuePrinter to format a nlohmann json value as a readable string', 'use json_lookup_function to detect and return a visualizer for nlohmann::basic_json values', 'use JsonValuePrinter.to_string to format floating point json values with 6 decimal places', 'use json_lookup_function to automatically dereference pointer-type json values via gdb.default_visualizer']
```

Usage

```
{'register_gdb_pretty_printer': 'load the GDB pretty printer by appending json_lookup_function to gdb.pretty_printers', 'print_json_value': 'use JsonValuePrinter to format a nlohmann json value as a readable string', 'lookup_json_type': 'use json_lookup_function to detect and return a visualizer for nlohmann::basic_json values', 'format_float_values': 'use JsonValuePrinter.to_string to format floating point json values with 6 decimal places', 'dereference_json_pointers': 'use json_lookup_function to automatically dereference pointer-type json values via gdb.default_visualizer'}
```

