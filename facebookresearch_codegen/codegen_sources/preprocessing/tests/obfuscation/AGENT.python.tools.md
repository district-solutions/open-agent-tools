# Agent Python Tools

- repo: facebookresearch/codegen
- repo_uri: https://github.com/facebookresearch/codegen

## File: facebookresearch_codegen/codegen_sources/preprocessing/tests/obfuscation/test_java_obfuscation.py

Prompts

```
['test obfuscating Java variable definitions by replacing names with VAR_N placeholders', 'test obfuscating recursive Java methods where method calls reference themselves', 'test obfuscating Java code with identical class and variable names across scopes', 'test obfuscating Java method overloading where multiple methods share the same name', 'test obfuscating Java inheritance hierarchies with super calls and this references', 'test obfuscating Python type annotations by replacing them with VAR_N placeholders using PythonTreeSitterProcessor', 'test obfuscating Python variable names, function names, and class names with VAR_N FUNC_N CLASS_N placeholders', 'test obfuscating recursive method calls where self references are preserved across obfuscated names', 'test obfuscating class instance attributes accessed via self across multiple methods', 'test obfuscating multiple top-level functions ensuring each scope gets independent variable mappings', 'test the diff_tester function by comparing two strings and printing a line-by-line diff on mismatch', 'test the diff_tester function by comparing two lists of items and printing differences', 'test the diff_tester function with a custom split character to compare space-separated tokens', 'test the diff_tester function with a normalization callable to compare case-insensitive strings', 'refactor the diff_tester function to return the diff output as a string instead of printing it']
```

Usage

```
{'test_java_obfuscation_var_definition': 'test obfuscating Java variable definitions by replacing names with VAR_N placeholders', 'test_java_obfuscation_recursive_method': 'test obfuscating recursive Java methods where method calls reference themselves', 'test_java_obfuscation_identical_names': 'test obfuscating Java code with identical class and variable names across scopes', 'test_java_methods_overloading': 'test obfuscating Java method overloading where multiple methods share the same name', 'test_java_inheritance_obfuscation': 'test obfuscating Java inheritance hierarchies with super calls and this references'}
```

## File: facebookresearch_codegen/codegen_sources/preprocessing/tests/obfuscation/test_python_obfuscator.py

Prompts

```
['test obfuscating Java variable definitions by replacing names with VAR_N placeholders', 'test obfuscating recursive Java methods where method calls reference themselves', 'test obfuscating Java code with identical class and variable names across scopes', 'test obfuscating Java method overloading where multiple methods share the same name', 'test obfuscating Java inheritance hierarchies with super calls and this references', 'test obfuscating Python type annotations by replacing them with VAR_N placeholders using PythonTreeSitterProcessor', 'test obfuscating Python variable names, function names, and class names with VAR_N FUNC_N CLASS_N placeholders', 'test obfuscating recursive method calls where self references are preserved across obfuscated names', 'test obfuscating class instance attributes accessed via self across multiple methods', 'test obfuscating multiple top-level functions ensuring each scope gets independent variable mappings', 'test the diff_tester function by comparing two strings and printing a line-by-line diff on mismatch', 'test the diff_tester function by comparing two lists of items and printing differences', 'test the diff_tester function with a custom split character to compare space-separated tokens', 'test the diff_tester function with a normalization callable to compare case-insensitive strings', 'refactor the diff_tester function to return the diff output as a string instead of printing it']
```

Usage

```
{'test_obfuscate_python_types': 'test obfuscating Python type annotations by replacing them with VAR_N placeholders using PythonTreeSitterProcessor', 'test_obfuscate_python_code': 'test obfuscating Python variable names, function names, and class names with VAR_N FUNC_N CLASS_N placeholders', 'test_obfuscate_recursive_methods': 'test obfuscating recursive method calls where self references are preserved across obfuscated names', 'test_obfuscate_class_attributes': 'test obfuscating class instance attributes accessed via self across multiple methods', 'test_obfuscate_function_scope': 'test obfuscating multiple top-level functions ensuring each scope gets independent variable mappings'}
```

## File: facebookresearch_codegen/codegen_sources/preprocessing/tests/obfuscation/utils.py

Prompts

```
['test obfuscating Java variable definitions by replacing names with VAR_N placeholders', 'test obfuscating recursive Java methods where method calls reference themselves', 'test obfuscating Java code with identical class and variable names across scopes', 'test obfuscating Java method overloading where multiple methods share the same name', 'test obfuscating Java inheritance hierarchies with super calls and this references', 'test obfuscating Python type annotations by replacing them with VAR_N placeholders using PythonTreeSitterProcessor', 'test obfuscating Python variable names, function names, and class names with VAR_N FUNC_N CLASS_N placeholders', 'test obfuscating recursive method calls where self references are preserved across obfuscated names', 'test obfuscating class instance attributes accessed via self across multiple methods', 'test obfuscating multiple top-level functions ensuring each scope gets independent variable mappings', 'test the diff_tester function by comparing two strings and printing a line-by-line diff on mismatch', 'test the diff_tester function by comparing two lists of items and printing differences', 'test the diff_tester function with a custom split character to compare space-separated tokens', 'test the diff_tester function with a normalization callable to compare case-insensitive strings', 'refactor the diff_tester function to return the diff output as a string instead of printing it']
```

Usage

```
{'test_diff_tester_strings': 'test the diff_tester function by comparing two strings and printing a line-by-line diff on mismatch', 'test_diff_tester_lists': 'test the diff_tester function by comparing two lists of items and printing differences', 'test_diff_tester_custom_split': 'test the diff_tester function with a custom split character to compare space-separated tokens', 'test_diff_tester_normalization': 'test the diff_tester function with a normalization callable to compare case-insensitive strings', 'refactor_diff_tester': 'refactor the diff_tester function to return the diff output as a string instead of printing it'}
```

