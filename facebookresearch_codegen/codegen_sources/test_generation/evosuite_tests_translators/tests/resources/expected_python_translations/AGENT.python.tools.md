# Agent Python Tools

- repo: facebookresearch/codegen
- repo_uri: https://github.com/facebookresearch/codegen

## File: facebookresearch_codegen/codegen_sources/test_generation/evosuite_tests_translators/tests/resources/expected_python_translations/doubles.py

Prompts

```
['test the f_filled function returns the input double value 3051.0 within tolerance', 'run the unit test class PERMUTE_TWO_ARRAYS_SUM_EVERY_PAIR_GREATER_EQUAL_K using unittest.main', 'test the f_filled function that permutes two integer arrays so every pair sums to greater than or equal to k', 'review test0 which initializes integer arrays and asserts f_filled returns true with k equal to 1', 'review test3 which asserts f_filled returns false when both array elements are equal and k is 1', 'refactor the TOFILL placeholder f_filled to implement the permutation logic for two integer arrays', 'run the unittest test cases for the Java ArrayList translated Python test file', 'test that f_filled removes a given double value from the ArrayList', 'test that f_filled keeps the original double value in the ArrayList', 'test that f_filled sets the ArrayList size to 9001 after processing', 'test that f_filled on an empty list does not add the double value']
```

Usage

```
{'test_f_filled_double_identity': 'test the f_filled function returns the input double value 3051.0 within tolerance'}
```

## File: facebookresearch_codegen/codegen_sources/test_generation/evosuite_tests_translators/tests/resources/expected_python_translations/integer_array_check.py

Prompts

```
['test the f_filled function returns the input double value 3051.0 within tolerance', 'run the unit test class PERMUTE_TWO_ARRAYS_SUM_EVERY_PAIR_GREATER_EQUAL_K using unittest.main', 'test the f_filled function that permutes two integer arrays so every pair sums to greater than or equal to k', 'review test0 which initializes integer arrays and asserts f_filled returns true with k equal to 1', 'review test3 which asserts f_filled returns false when both array elements are equal and k is 1', 'refactor the TOFILL placeholder f_filled to implement the permutation logic for two integer arrays', 'run the unittest test cases for the Java ArrayList translated Python test file', 'test that f_filled removes a given double value from the ArrayList', 'test that f_filled keeps the original double value in the ArrayList', 'test that f_filled sets the ArrayList size to 9001 after processing', 'test that f_filled on an empty list does not add the double value']
```

Usage

```
{'run_test_PERMUTE_TWO_ARRAYS_SUM_EVERY_PAIR_GREATER_EQUAL_K': 'run the unit test class PERMUTE_TWO_ARRAYS_SUM_EVERY_PAIR_GREATER_EQUAL_K using unittest.main', 'test_f_filled_permutation_logic': 'test the f_filled function that permutes two integer arrays so every pair sums to greater than or equal to k', 'review_test0_array_initialization': 'review test0 which initializes integer arrays and asserts f_filled returns true with k equal to 1', 'review_test3_negative_case': 'review test3 which asserts f_filled returns false when both array elements are equal and k is 1', 'refactor_f_filled_implementation': 'refactor the TOFILL placeholder f_filled to implement the permutation logic for two integer arrays'}
```

## File: facebookresearch_codegen/codegen_sources/test_generation/evosuite_tests_translators/tests/resources/expected_python_translations/java_list.py

Prompts

```
['test the f_filled function returns the input double value 3051.0 within tolerance', 'run the unit test class PERMUTE_TWO_ARRAYS_SUM_EVERY_PAIR_GREATER_EQUAL_K using unittest.main', 'test the f_filled function that permutes two integer arrays so every pair sums to greater than or equal to k', 'review test0 which initializes integer arrays and asserts f_filled returns true with k equal to 1', 'review test3 which asserts f_filled returns false when both array elements are equal and k is 1', 'refactor the TOFILL placeholder f_filled to implement the permutation logic for two integer arrays', 'run the unittest test cases for the Java ArrayList translated Python test file', 'test that f_filled removes a given double value from the ArrayList', 'test that f_filled keeps the original double value in the ArrayList', 'test that f_filled sets the ArrayList size to 9001 after processing', 'test that f_filled on an empty list does not add the double value']
```

Usage

```
{'run_unittest_java_list': 'run the unittest test cases for the Java ArrayList translated Python test file', 'test_f_filled_removes_element': 'test that f_filled removes a given double value from the ArrayList', 'test_f_filled_keeps_element': 'test that f_filled keeps the original double value in the ArrayList', 'test_f_filled_size_after_fill': 'test that f_filled sets the ArrayList size to 9001 after processing', 'test_f_filled_on_empty_list': 'test that f_filled on an empty list does not add the double value'}
```

