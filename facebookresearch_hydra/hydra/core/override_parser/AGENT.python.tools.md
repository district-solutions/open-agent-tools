# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/hydra/core/override_parser/overrides_parser.py

Prompts

```
['parse a single Hydra override string into an Override object using OverridesParser', 'parse a list of Hydra override strings into Override objects with error handling', 'create an OverridesParser instance with registered grammar functions using the create class method', 'parse an arbitrary grammar rule string by name using the parse_rule method', 'create and register cast, sweep, and misc grammar functions for override parsing', 'parse a Hydra override string into an Override object with key, value, and type using HydraOverrideVisitor', 'visit an OverrideParser OverrideContext to produce an Override with ADD, DEL, CHANGE, or EXTEND_LIST type', 'visit a SimpleChoiceSweepContext to produce a ChoiceSweep object from comma-separated elements', 'visit a FunctionContext to evaluate a function call with positional args and keyword args via Functions', 'unescape a quoted string by processing backslash sequences before quotes and stripping enclosing quotes', 'create an Override with OverrideType.CHANGE to modify a Hydra config value at a dot-path key', 'create a ChoiceSweep with a list of values to sweep over hyperparameters in Hydra', 'create a RangeSweep with start, stop, and step to iterate over numeric values in Hydra', 'create a QuotedString with single or double quotes and use with_quotes to escape special characters', 'create a Glob with include and exclude patterns to filter Hydra config group options']
```

Usage

```
{'parse_single_override': 'parse a single Hydra override string into an Override object using OverridesParser', 'parse_multiple_overrides': 'parse a list of Hydra override strings into Override objects with error handling', 'create_overrides_parser': 'create an OverridesParser instance with registered grammar functions using the create class method', 'parse_generic_rule': 'parse an arbitrary grammar rule string by name using the parse_rule method', 'register_grammar_functions': 'create and register cast, sweep, and misc grammar functions for override parsing'}
```

## File: facebookresearch_hydra/hydra/core/override_parser/overrides_visitor.py

Prompts

```
['parse a single Hydra override string into an Override object using OverridesParser', 'parse a list of Hydra override strings into Override objects with error handling', 'create an OverridesParser instance with registered grammar functions using the create class method', 'parse an arbitrary grammar rule string by name using the parse_rule method', 'create and register cast, sweep, and misc grammar functions for override parsing', 'parse a Hydra override string into an Override object with key, value, and type using HydraOverrideVisitor', 'visit an OverrideParser OverrideContext to produce an Override with ADD, DEL, CHANGE, or EXTEND_LIST type', 'visit a SimpleChoiceSweepContext to produce a ChoiceSweep object from comma-separated elements', 'visit a FunctionContext to evaluate a function call with positional args and keyword args via Functions', 'unescape a quoted string by processing backslash sequences before quotes and stripping enclosing quotes', 'create an Override with OverrideType.CHANGE to modify a Hydra config value at a dot-path key', 'create a ChoiceSweep with a list of values to sweep over hyperparameters in Hydra', 'create a RangeSweep with start, stop, and step to iterate over numeric values in Hydra', 'create a QuotedString with single or double quotes and use with_quotes to escape special characters', 'create a Glob with include and exclude patterns to filter Hydra config group options']
```

Usage

```
{'parse_hydra_override': 'parse a Hydra override string into an Override object with key, value, and type using HydraOverrideVisitor', 'visit_override_context': 'visit an OverrideParser OverrideContext to produce an Override with ADD, DEL, CHANGE, or EXTEND_LIST type', 'visit_simple_choice_sweep': 'visit a SimpleChoiceSweepContext to produce a ChoiceSweep object from comma-separated elements', 'visit_function_call': 'visit a FunctionContext to evaluate a function call with positional args and keyword args via Functions', 'unescape_quoted_string': 'unescape a quoted string by processing backslash sequences before quotes and stripping enclosing quotes'}
```

## File: facebookresearch_hydra/hydra/core/override_parser/types.py

Prompts

```
['parse a single Hydra override string into an Override object using OverridesParser', 'parse a list of Hydra override strings into Override objects with error handling', 'create an OverridesParser instance with registered grammar functions using the create class method', 'parse an arbitrary grammar rule string by name using the parse_rule method', 'create and register cast, sweep, and misc grammar functions for override parsing', 'parse a Hydra override string into an Override object with key, value, and type using HydraOverrideVisitor', 'visit an OverrideParser OverrideContext to produce an Override with ADD, DEL, CHANGE, or EXTEND_LIST type', 'visit a SimpleChoiceSweepContext to produce a ChoiceSweep object from comma-separated elements', 'visit a FunctionContext to evaluate a function call with positional args and keyword args via Functions', 'unescape a quoted string by processing backslash sequences before quotes and stripping enclosing quotes', 'create an Override with OverrideType.CHANGE to modify a Hydra config value at a dot-path key', 'create a ChoiceSweep with a list of values to sweep over hyperparameters in Hydra', 'create a RangeSweep with start, stop, and step to iterate over numeric values in Hydra', 'create a QuotedString with single or double quotes and use with_quotes to escape special characters', 'create a Glob with include and exclude patterns to filter Hydra config group options']
```

Usage

```
{'create_override_for_config_change': 'create an Override with OverrideType.CHANGE to modify a Hydra config value at a dot-path key', 'create_choice_sweep_for_hyperparams': 'create a ChoiceSweep with a list of values to sweep over hyperparameters in Hydra', 'create_range_sweep_for_numeric_values': 'create a RangeSweep with start, stop, and step to iterate over numeric values in Hydra', 'create_quoted_string_with_escaping': 'create a QuotedString with single or double quotes and use with_quotes to escape special characters', 'create_glob_filter_for_config_groups': 'create a Glob with include and exclude patterns to filter Hydra config group options'}
```

