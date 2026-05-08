# Agent Python Tools

- repo: facebookresearch/codegen
- repo_uri: https://github.com/facebookresearch/codegen

## File: facebookresearch_codegen/codegen_sources/test_generation/evosuite_tests_translators/evosuite_to_cpp.py

Prompts

```
['translate Java EvoSuite test code into C++ GoogleTest equivalent using EvosuiteToCpp', 'replace Java JUnit assert statements with C++ GoogleTest ASSERT macros in test code', 'translate Java variable definitions and type names to C++ equivalents in test code', 'translate Java type casting expressions to C++ style casts and remove null casts', 'wrap translated test code with C++ imports and a GoogleTest main function', 'translate Java EvoSuite test code into equivalent Python unittest code', 'replace Java assertTrue, assertFalse, assertEquals, assertSame, assertNull asserts with Python assert statements', 'translate Java array definitions and length getters into Python list syntax and len() calls', 'translate Java type casts like (int), (String), (double) into Python int(), str(), float() calls', 'translate Java typed variable definitions into Python assignment statements', 'extract all assert arguments from Java test code using EvosuiteTranslator get_asserts_arguments', 'replace Java class method calls with f_filled placeholder using replace_func_calls', 'extract arguments for a specific assert type like assertTrue from Java test code', 'join a list of argument strings into a comma-separated string using args_to_string', 'get the Python default value for a given Java primitive or standard type']
```

Usage

```
{'translate_java_to_cpp': 'translate Java EvoSuite test code into C++ GoogleTest equivalent using EvosuiteToCpp', 'replace_asserts': 'replace Java JUnit assert statements with C++ GoogleTest ASSERT macros in test code', 'translate_variable_definitions': 'translate Java variable definitions and type names to C++ equivalents in test code', 'translate_type_casting': 'translate Java type casting expressions to C++ style casts and remove null casts', 'translation_wrapup': 'wrap translated test code with C++ imports and a GoogleTest main function'}
```

## File: facebookresearch_codegen/codegen_sources/test_generation/evosuite_tests_translators/evosuite_to_python.py

Prompts

```
['translate Java EvoSuite test code into C++ GoogleTest equivalent using EvosuiteToCpp', 'replace Java JUnit assert statements with C++ GoogleTest ASSERT macros in test code', 'translate Java variable definitions and type names to C++ equivalents in test code', 'translate Java type casting expressions to C++ style casts and remove null casts', 'wrap translated test code with C++ imports and a GoogleTest main function', 'translate Java EvoSuite test code into equivalent Python unittest code', 'replace Java assertTrue, assertFalse, assertEquals, assertSame, assertNull asserts with Python assert statements', 'translate Java array definitions and length getters into Python list syntax and len() calls', 'translate Java type casts like (int), (String), (double) into Python int(), str(), float() calls', 'translate Java typed variable definitions into Python assignment statements', 'extract all assert arguments from Java test code using EvosuiteTranslator get_asserts_arguments', 'replace Java class method calls with f_filled placeholder using replace_func_calls', 'extract arguments for a specific assert type like assertTrue from Java test code', 'join a list of argument strings into a comma-separated string using args_to_string', 'get the Python default value for a given Java primitive or standard type']
```

Usage

```
{'translate_java_test_to_python': 'translate Java EvoSuite test code into equivalent Python unittest code', 'replace_java_asserts_with_python_asserts': 'replace Java assertTrue, assertFalse, assertEquals, assertSame, assertNull asserts with Python assert statements', 'translate_java_arrays_to_python_lists': 'translate Java array definitions and length getters into Python list syntax and len() calls', 'translate_java_type_casting_to_python': 'translate Java type casts like (int), (String), (double) into Python int(), str(), float() calls', 'translate_java_variable_definitions_to_python': 'translate Java typed variable definitions into Python assignment statements'}
```

## File: facebookresearch_codegen/codegen_sources/test_generation/evosuite_tests_translators/evosuite_translator.py

Prompts

```
['translate Java EvoSuite test code into C++ GoogleTest equivalent using EvosuiteToCpp', 'replace Java JUnit assert statements with C++ GoogleTest ASSERT macros in test code', 'translate Java variable definitions and type names to C++ equivalents in test code', 'translate Java type casting expressions to C++ style casts and remove null casts', 'wrap translated test code with C++ imports and a GoogleTest main function', 'translate Java EvoSuite test code into equivalent Python unittest code', 'replace Java assertTrue, assertFalse, assertEquals, assertSame, assertNull asserts with Python assert statements', 'translate Java array definitions and length getters into Python list syntax and len() calls', 'translate Java type casts like (int), (String), (double) into Python int(), str(), float() calls', 'translate Java typed variable definitions into Python assignment statements', 'extract all assert arguments from Java test code using EvosuiteTranslator get_asserts_arguments', 'replace Java class method calls with f_filled placeholder using replace_func_calls', 'extract arguments for a specific assert type like assertTrue from Java test code', 'join a list of argument strings into a comma-separated string using args_to_string', 'get the Python default value for a given Java primitive or standard type']
```

Usage

```
{'extract_asserts_from_java_test_code': 'extract all assert arguments from Java test code using EvosuiteTranslator get_asserts_arguments', 'replace_java_func_calls_with_placeholder': 'replace Java class method calls with f_filled placeholder using replace_func_calls', 'extract_specific_assert_args': 'extract arguments for a specific assert type like assertTrue from Java test code', 'join_args_list_to_string': 'join a list of argument strings into a comma-separated string using args_to_string', 'get_java_type_default_value': 'get the Python default value for a given Java primitive or standard type'}
```

