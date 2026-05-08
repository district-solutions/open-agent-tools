# Agent Python Tools

- repo: facebookresearch/codegen
- repo_uri: https://github.com/facebookresearch/codegen

## File: facebookresearch_codegen/codegen_sources/test_generation/evosuite_tests_translators/tests/test_evosuite_to_cpp_translator.py

Prompts

```
['test the EvosuiteToCpp translator to convert Java integer array casting tests to C++', 'test the EvosuiteToCpp translator to convert Java list tests to C++', 'test the EvosuiteToCpp translator to convert Java float and double tests to C++', 'test the EvosuiteToCpp translator to convert Java string and null casting tests to C++', 'test the EvosuiteToCpp translator to convert Java tests with different object names to C++', 'review the EvosuiteToPython translator class used to translate EvoSuite Java tests to Python', 'test a translator by running it against a list of input and expected translation pairs', 'test two strings for equality and print a line-by-line diff on mismatch', 'read a Java test file and its expected Python or C++ translation from resource directories', 'refactor the translation_testing function to support additional target languages beyond Python and C++', 'review the diff_tester function and its use of difflib.Differ for comparing expected and actual output']
```

Usage

```
{'test_array_translation': 'test the EvosuiteToCpp translator to convert Java integer array casting tests to C++', 'test_lists_translation': 'test the EvosuiteToCpp translator to convert Java list tests to C++', 'test_floats': 'test the EvosuiteToCpp translator to convert Java float and double tests to C++', 'test_string_translation': 'test the EvosuiteToCpp translator to convert Java string and null casting tests to C++', 'test_different_object_name': 'test the EvosuiteToCpp translator to convert Java tests with different object names to C++'}
```

## File: facebookresearch_codegen/codegen_sources/test_generation/evosuite_tests_translators/tests/test_evosuite_to_python_translator.py

Prompts

```
['test the EvosuiteToCpp translator to convert Java integer array casting tests to C++', 'test the EvosuiteToCpp translator to convert Java list tests to C++', 'test the EvosuiteToCpp translator to convert Java float and double tests to C++', 'test the EvosuiteToCpp translator to convert Java string and null casting tests to C++', 'test the EvosuiteToCpp translator to convert Java tests with different object names to C++', 'review the EvosuiteToPython translator class used to translate EvoSuite Java tests to Python', 'test a translator by running it against a list of input and expected translation pairs', 'test two strings for equality and print a line-by-line diff on mismatch', 'read a Java test file and its expected Python or C++ translation from resource directories', 'refactor the translation_testing function to support additional target languages beyond Python and C++', 'review the diff_tester function and its use of difflib.Differ for comparing expected and actual output']
```

Usage

```
{'test_array_translation': 'test the EvosuiteToPython translator for integer array check and casting translation cases', 'test_lists_translation': 'test the EvosuiteToPython translator for Java list to Python list translation cases', 'test_floats': 'test the EvosuiteToPython translator for float and double type translation cases', 'test_string_translation': 'test the EvosuiteToPython translator for string and null casting translation cases', 'review_EvosuiteToPython': 'review the EvosuiteToPython translator class used to translate EvoSuite Java tests to Python'}
```

## File: facebookresearch_codegen/codegen_sources/test_generation/evosuite_tests_translators/tests/test_utils.py

Prompts

```
['test the EvosuiteToCpp translator to convert Java integer array casting tests to C++', 'test the EvosuiteToCpp translator to convert Java list tests to C++', 'test the EvosuiteToCpp translator to convert Java float and double tests to C++', 'test the EvosuiteToCpp translator to convert Java string and null casting tests to C++', 'test the EvosuiteToCpp translator to convert Java tests with different object names to C++', 'review the EvosuiteToPython translator class used to translate EvoSuite Java tests to Python', 'test a translator by running it against a list of input and expected translation pairs', 'test two strings for equality and print a line-by-line diff on mismatch', 'read a Java test file and its expected Python or C++ translation from resource directories', 'refactor the translation_testing function to support additional target languages beyond Python and C++', 'review the diff_tester function and its use of difflib.Differ for comparing expected and actual output']
```

Usage

```
{'test_translation_testing': 'test a translator by running it against a list of input and expected translation pairs', 'test_diff_tester': 'test two strings for equality and print a line-by-line diff on mismatch', 'read_read_inputs': 'read a Java test file and its expected Python or C++ translation from resource directories', 'refactor_translation_testing': 'refactor the translation_testing function to support additional target languages beyond Python and C++', 'review_diff_tester': 'review the diff_tester function and its use of difflib.Differ for comparing expected and actual output'}
```

