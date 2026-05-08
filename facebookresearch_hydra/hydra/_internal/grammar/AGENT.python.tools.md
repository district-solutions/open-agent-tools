# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/hydra/_internal/grammar/functions.py

Prompts

```
['register a callable function with a name in the Hydra Functions registry for grammar evaluation', 'evaluate a FunctionCall object through the Functions registry with signature binding and type validation', 'create a FunctionCall dataclass instance with a name, positional args list, and kwargs dict', 'review the Functions class to understand how it validates argument types against function signatures', 'refactor the Functions eval method to handle QuotedString unquoting in args and kwargs values', 'create a choice sweep over multiple config values using the choice function', 'create a range sweep over integer or float values with start, stop, and step', 'cast config values, lists, or sweeps to integers using the cast_int function', 'cast config values, lists, or sweeps to floats using the cast_float function', 'create a glob to select config group options with include and exclude patterns', 'escape special characters like parentheses, brackets, colons, and commas in a string for Hydra grammar', 'test the escape_special_characters function to verify backslashes and special chars are properly escaped', 'check if a value matches a given type including Union types and primitives like int or str', 'test the is_type_matching function to verify it correctly matches values against Union and primitive types', 'review the _ESC, _ESC_REGEX, and _ESC_QUOTED_STR constants used for Hydra grammar escaping']
```

Usage

```
{'register_function_in_hydra_grammar': 'register a callable function with a name in the Hydra Functions registry for grammar evaluation', 'eval_function_call_with_type_checking': 'evaluate a FunctionCall object through the Functions registry with signature binding and type validation', 'create_functioncall_dataclass': 'create a FunctionCall dataclass instance with a name, positional args list, and kwargs dict', 'review_functions_registry_type_validation': 'review the Functions class to understand how it validates argument types against function signatures', 'refactor_functions_eval_quotedstring_handling': 'refactor the Functions eval method to handle QuotedString unquoting in args and kwargs values'}
```

## File: facebookresearch_hydra/hydra/_internal/grammar/grammar_functions.py

Prompts

```
['register a callable function with a name in the Hydra Functions registry for grammar evaluation', 'evaluate a FunctionCall object through the Functions registry with signature binding and type validation', 'create a FunctionCall dataclass instance with a name, positional args list, and kwargs dict', 'review the Functions class to understand how it validates argument types against function signatures', 'refactor the Functions eval method to handle QuotedString unquoting in args and kwargs values', 'create a choice sweep over multiple config values using the choice function', 'create a range sweep over integer or float values with start, stop, and step', 'cast config values, lists, or sweeps to integers using the cast_int function', 'cast config values, lists, or sweeps to floats using the cast_float function', 'create a glob to select config group options with include and exclude patterns', 'escape special characters like parentheses, brackets, colons, and commas in a string for Hydra grammar', 'test the escape_special_characters function to verify backslashes and special chars are properly escaped', 'check if a value matches a given type including Union types and primitives like int or str', 'test the is_type_matching function to verify it correctly matches values against Union and primitive types', 'review the _ESC, _ESC_REGEX, and _ESC_QUOTED_STR constants used for Hydra grammar escaping']
```

Usage

```
{'create_choice_sweep': 'create a choice sweep over multiple config values using the choice function', 'create_range_sweep': 'create a range sweep over integer or float values with start, stop, and step', 'cast_values_to_int': 'cast config values, lists, or sweeps to integers using the cast_int function', 'cast_values_to_float': 'cast config values, lists, or sweeps to floats using the cast_float function', 'create_glob_selection': 'create a glob to select config group options with include and exclude patterns'}
```

## File: facebookresearch_hydra/hydra/_internal/grammar/utils.py

Prompts

```
['register a callable function with a name in the Hydra Functions registry for grammar evaluation', 'evaluate a FunctionCall object through the Functions registry with signature binding and type validation', 'create a FunctionCall dataclass instance with a name, positional args list, and kwargs dict', 'review the Functions class to understand how it validates argument types against function signatures', 'refactor the Functions eval method to handle QuotedString unquoting in args and kwargs values', 'create a choice sweep over multiple config values using the choice function', 'create a range sweep over integer or float values with start, stop, and step', 'cast config values, lists, or sweeps to integers using the cast_int function', 'cast config values, lists, or sweeps to floats using the cast_float function', 'create a glob to select config group options with include and exclude patterns', 'escape special characters like parentheses, brackets, colons, and commas in a string for Hydra grammar', 'test the escape_special_characters function to verify backslashes and special chars are properly escaped', 'check if a value matches a given type including Union types and primitives like int or str', 'test the is_type_matching function to verify it correctly matches values against Union and primitive types', 'review the _ESC, _ESC_REGEX, and _ESC_QUOTED_STR constants used for Hydra grammar escaping']
```

Usage

```
{'escape_special_characters': 'escape special characters like parentheses, brackets, colons, and commas in a string for Hydra grammar', 'test_escape_special_characters': 'test the escape_special_characters function to verify backslashes and special chars are properly escaped', 'is_type_matching': 'check if a value matches a given type including Union types and primitives like int or str', 'test_is_type_matching': 'test the is_type_matching function to verify it correctly matches values against Union and primitive types', 'review_escape_regex_constants': 'review the _ESC, _ESC_REGEX, and _ESC_QUOTED_STR constants used for Hydra grammar escaping'}
```

