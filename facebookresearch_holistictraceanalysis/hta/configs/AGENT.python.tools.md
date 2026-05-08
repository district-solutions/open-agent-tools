# Agent Python Tools

- repo: facebookresearch/holistictraceanalysis
- repo_uri: https://github.com/facebookresearch/holistictraceanalysis

## File: facebookresearch_holistictraceanalysis/hta/configs/config.py

Prompts

```
['create an HtaConfig instance that loads default and user-provided JSON config files', 'get a configuration value by dot-path from an HtaConfig instance with optional default', 'print the full merged configuration dictionary as formatted JSON to stdout', 'get the list of default config file paths for trace analyzer customization', 'get the file system path to a named test dataset under tests/data', 'parse a version string like 1.2.3 into a YamlVersion named tuple using from_string', 'get a dot-separated version string from a YamlVersion named tuple using get_version_str', 'create an AttributeSpec named tuple with name, raw_name, value_type, default_value, and min_supported_version', 'compare two AttributeSpec instances for equality using the custom __eq__ method', 'use the ValueType enum to classify attribute values as Int, Float, String, or Object', 'get a string representation of all HTA environment options and their current values', 'check if nanosecond rounding is disabled for trace event precision handling', 'check if call graph depth tracking is disabled in the analysis pipeline', 'check if zero weight launch edges should be added for critical path causality analysis', 'check if strict negative weight checking is enabled to fail on invalid edge weights', 'parse a YAML event args config file for a given version and return an EventArgs object', 'run the main entry point to parse and print event args for version 1.0.0', 'review the ARGS_DEFAULT_FUNC lambda that combines minimum, bandwidth, sync, input shape, index, and communication args', 'summarize the ARGS_COMMUNICATION_FUNC lambda that extracts NCCL collective communication attribute specs', 'refactor parse_event_args_yaml to support additional YAML version formats or custom fallback logic', 'create a ParserConfig instance to configure how a JSON trace file is parsed', 'clone an existing ParserConfig to create a deep copy for safe modification', 'enable communication-related attribute specs on a ParserConfig for parsing network events', 'infer AttributeSpec definitions from a pandas Series of trace event argument dictionaries', 'set a custom ParserConfig as the global default for all subsequent trace parsing operations']
```

Usage

```
{'create_hta_config': 'create an HtaConfig instance that loads default and user-provided JSON config files', 'get_config_value': 'get a configuration value by dot-path from an HtaConfig instance with optional default', 'show_config': 'print the full merged configuration dictionary as formatted JSON to stdout', 'get_default_paths': 'get the list of default config file paths for trace analyzer customization', 'get_test_data_path': 'get the file system path to a named test dataset under tests/data'}
```

## File: facebookresearch_holistictraceanalysis/hta/configs/default_values.py

Prompts

```
['create an HtaConfig instance that loads default and user-provided JSON config files', 'get a configuration value by dot-path from an HtaConfig instance with optional default', 'print the full merged configuration dictionary as formatted JSON to stdout', 'get the list of default config file paths for trace analyzer customization', 'get the file system path to a named test dataset under tests/data', 'parse a version string like 1.2.3 into a YamlVersion named tuple using from_string', 'get a dot-separated version string from a YamlVersion named tuple using get_version_str', 'create an AttributeSpec named tuple with name, raw_name, value_type, default_value, and min_supported_version', 'compare two AttributeSpec instances for equality using the custom __eq__ method', 'use the ValueType enum to classify attribute values as Int, Float, String, or Object', 'get a string representation of all HTA environment options and their current values', 'check if nanosecond rounding is disabled for trace event precision handling', 'check if call graph depth tracking is disabled in the analysis pipeline', 'check if zero weight launch edges should be added for critical path causality analysis', 'check if strict negative weight checking is enabled to fail on invalid edge weights', 'parse a YAML event args config file for a given version and return an EventArgs object', 'run the main entry point to parse and print event args for version 1.0.0', 'review the ARGS_DEFAULT_FUNC lambda that combines minimum, bandwidth, sync, input shape, index, and communication args', 'summarize the ARGS_COMMUNICATION_FUNC lambda that extracts NCCL collective communication attribute specs', 'refactor parse_event_args_yaml to support additional YAML version formats or custom fallback logic', 'create a ParserConfig instance to configure how a JSON trace file is parsed', 'clone an existing ParserConfig to create a deep copy for safe modification', 'enable communication-related attribute specs on a ParserConfig for parsing network events', 'infer AttributeSpec definitions from a pandas Series of trace event argument dictionaries', 'set a custom ParserConfig as the global default for all subsequent trace parsing operations']
```

Usage

```
{'parse_yaml_version_from_string': 'parse a version string like 1.2.3 into a YamlVersion named tuple using from_string', 'get_yaml_version_string': 'get a dot-separated version string from a YamlVersion named tuple using get_version_str', 'create_attribute_spec': 'create an AttributeSpec named tuple with name, raw_name, value_type, default_value, and min_supported_version', 'compare_attribute_specs': 'compare two AttributeSpec instances for equality using the custom __eq__ method', 'use_valuetype_enum': 'use the ValueType enum to classify attribute values as Int, Float, String, or Object'}
```

## File: facebookresearch_holistictraceanalysis/hta/configs/env_options.py

Prompts

```
['create an HtaConfig instance that loads default and user-provided JSON config files', 'get a configuration value by dot-path from an HtaConfig instance with optional default', 'print the full merged configuration dictionary as formatted JSON to stdout', 'get the list of default config file paths for trace analyzer customization', 'get the file system path to a named test dataset under tests/data', 'parse a version string like 1.2.3 into a YamlVersion named tuple using from_string', 'get a dot-separated version string from a YamlVersion named tuple using get_version_str', 'create an AttributeSpec named tuple with name, raw_name, value_type, default_value, and min_supported_version', 'compare two AttributeSpec instances for equality using the custom __eq__ method', 'use the ValueType enum to classify attribute values as Int, Float, String, or Object', 'get a string representation of all HTA environment options and their current values', 'check if nanosecond rounding is disabled for trace event precision handling', 'check if call graph depth tracking is disabled in the analysis pipeline', 'check if zero weight launch edges should be added for critical path causality analysis', 'check if strict negative weight checking is enabled to fail on invalid edge weights', 'parse a YAML event args config file for a given version and return an EventArgs object', 'run the main entry point to parse and print event args for version 1.0.0', 'review the ARGS_DEFAULT_FUNC lambda that combines minimum, bandwidth, sync, input shape, index, and communication args', 'summarize the ARGS_COMMUNICATION_FUNC lambda that extracts NCCL collective communication attribute specs', 'refactor parse_event_args_yaml to support additional YAML version formats or custom fallback logic', 'create a ParserConfig instance to configure how a JSON trace file is parsed', 'clone an existing ParserConfig to create a deep copy for safe modification', 'enable communication-related attribute specs on a ParserConfig for parsing network events', 'infer AttributeSpec definitions from a pandas Series of trace event argument dictionaries', 'set a custom ParserConfig as the global default for all subsequent trace parsing operations']
```

Usage

```
{'get_hta_env_options_string': 'get a string representation of all HTA environment options and their current values', 'check_disable_ns_rounding': 'check if nanosecond rounding is disabled for trace event precision handling', 'check_disable_call_graph_depth': 'check if call graph depth tracking is disabled in the analysis pipeline', 'check_critical_path_zero_weight_launch_edges': 'check if zero weight launch edges should be added for critical path causality analysis', 'check_critical_path_strict_negative_weight': 'check if strict negative weight checking is enabled to fail on invalid edge weights'}
```

## File: facebookresearch_holistictraceanalysis/hta/configs/event_args_yaml_parser.py

Prompts

```
['create an HtaConfig instance that loads default and user-provided JSON config files', 'get a configuration value by dot-path from an HtaConfig instance with optional default', 'print the full merged configuration dictionary as formatted JSON to stdout', 'get the list of default config file paths for trace analyzer customization', 'get the file system path to a named test dataset under tests/data', 'parse a version string like 1.2.3 into a YamlVersion named tuple using from_string', 'get a dot-separated version string from a YamlVersion named tuple using get_version_str', 'create an AttributeSpec named tuple with name, raw_name, value_type, default_value, and min_supported_version', 'compare two AttributeSpec instances for equality using the custom __eq__ method', 'use the ValueType enum to classify attribute values as Int, Float, String, or Object', 'get a string representation of all HTA environment options and their current values', 'check if nanosecond rounding is disabled for trace event precision handling', 'check if call graph depth tracking is disabled in the analysis pipeline', 'check if zero weight launch edges should be added for critical path causality analysis', 'check if strict negative weight checking is enabled to fail on invalid edge weights', 'parse a YAML event args config file for a given version and return an EventArgs object', 'run the main entry point to parse and print event args for version 1.0.0', 'review the ARGS_DEFAULT_FUNC lambda that combines minimum, bandwidth, sync, input shape, index, and communication args', 'summarize the ARGS_COMMUNICATION_FUNC lambda that extracts NCCL collective communication attribute specs', 'refactor parse_event_args_yaml to support additional YAML version formats or custom fallback logic', 'create a ParserConfig instance to configure how a JSON trace file is parsed', 'clone an existing ParserConfig to create a deep copy for safe modification', 'enable communication-related attribute specs on a ParserConfig for parsing network events', 'infer AttributeSpec definitions from a pandas Series of trace event argument dictionaries', 'set a custom ParserConfig as the global default for all subsequent trace parsing operations']
```

Usage

```
{'parse_event_args_yaml': 'parse a YAML event args config file for a given version and return an EventArgs object', 'run_main': 'run the main entry point to parse and print event args for version 1.0.0', 'review_ARGS_DEFAULT_FUNC': 'review the ARGS_DEFAULT_FUNC lambda that combines minimum, bandwidth, sync, input shape, index, and communication args', 'summarize_ARGS_COMMUNICATION_FUNC': 'summarize the ARGS_COMMUNICATION_FUNC lambda that extracts NCCL collective communication attribute specs', 'refactor_parse_event_args_yaml': 'refactor parse_event_args_yaml to support additional YAML version formats or custom fallback logic'}
```

## File: facebookresearch_holistictraceanalysis/hta/configs/parser_config.py

Prompts

```
['create an HtaConfig instance that loads default and user-provided JSON config files', 'get a configuration value by dot-path from an HtaConfig instance with optional default', 'print the full merged configuration dictionary as formatted JSON to stdout', 'get the list of default config file paths for trace analyzer customization', 'get the file system path to a named test dataset under tests/data', 'parse a version string like 1.2.3 into a YamlVersion named tuple using from_string', 'get a dot-separated version string from a YamlVersion named tuple using get_version_str', 'create an AttributeSpec named tuple with name, raw_name, value_type, default_value, and min_supported_version', 'compare two AttributeSpec instances for equality using the custom __eq__ method', 'use the ValueType enum to classify attribute values as Int, Float, String, or Object', 'get a string representation of all HTA environment options and their current values', 'check if nanosecond rounding is disabled for trace event precision handling', 'check if call graph depth tracking is disabled in the analysis pipeline', 'check if zero weight launch edges should be added for critical path causality analysis', 'check if strict negative weight checking is enabled to fail on invalid edge weights', 'parse a YAML event args config file for a given version and return an EventArgs object', 'run the main entry point to parse and print event args for version 1.0.0', 'review the ARGS_DEFAULT_FUNC lambda that combines minimum, bandwidth, sync, input shape, index, and communication args', 'summarize the ARGS_COMMUNICATION_FUNC lambda that extracts NCCL collective communication attribute specs', 'refactor parse_event_args_yaml to support additional YAML version formats or custom fallback logic', 'create a ParserConfig instance to configure how a JSON trace file is parsed', 'clone an existing ParserConfig to create a deep copy for safe modification', 'enable communication-related attribute specs on a ParserConfig for parsing network events', 'infer AttributeSpec definitions from a pandas Series of trace event argument dictionaries', 'set a custom ParserConfig as the global default for all subsequent trace parsing operations']
```

Usage

```
{'create_parser_config': 'create a ParserConfig instance to configure how a JSON trace file is parsed', 'clone_parser_config': 'clone an existing ParserConfig to create a deep copy for safe modification', 'enable_communication_args': 'enable communication-related attribute specs on a ParserConfig for parsing network events', 'infer_attribute_specs': 'infer AttributeSpec definitions from a pandas Series of trace event argument dictionaries', 'set_default_cfg': 'set a custom ParserConfig as the global default for all subsequent trace parsing operations'}
```

