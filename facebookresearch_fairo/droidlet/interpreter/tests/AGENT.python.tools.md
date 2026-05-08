# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/interpreter/tests/all_test_commands.py

Prompts

```
['summarize the all_test_commands.py file which defines DROIDLET interpreter test command dictionaries for natural language parsing', 'review the FILTERS dictionary that defines object selection filters using where_clause predicates and selectors for the DROIDLET interpreter', 'review the INTERPRETER_POSSIBLE_ACTIONS dictionary that maps action types like BUILD, DESTROY, MOVE, SPAWN, and FILL to structured command definitions', 'review the STOP_CONDITION_COMMANDS dictionary that defines terminate_condition logic for timed or attribute-based command loops in DROIDLET', 'review the GET_MEMORY_COMMANDS dictionary that defines query structures for retrieving object attributes, counts, and spatial relationships in DROIDLET', 'test the interpret_span_value function to parse numeric span values from action dictionaries', 'test the maybe_specific_mem function to generate SQL queries for reference object lookups', 'test the interpret_linear_extent function to handle distance-based queries and error cases', 'test the interpret_task_info function to build AttributeSequence objects from task info dictionaries', 'test linear extent search with MemorySearcher to find reference objects by distance comparator', 'test the process_spans_and_remove_fixed_value function using logical form before and after processing dictionaries', 'test that location is not nested inside filters across all interpreter possible actions and reference objects', 'run the unittest test suite for interpreter utils including process spans and location reference object tests', 'review the TestInterpreterUtils class and its test_process_spans and test_location_reference_object test methods', 'summarize how logical form dictionaries are transformed by process_spans_and_remove_fixed_value for turn right, go forward, and where are my keys commands']
```

Usage

```
{'summarize_all_test_commands': 'summarize the all_test_commands.py file which defines DROIDLET interpreter test command dictionaries for natural language parsing', 'review_FILTERS': 'review the FILTERS dictionary that defines object selection filters using where_clause predicates and selectors for the DROIDLET interpreter', 'review_INTERPRETER_POSSIBLE_ACTIONS': 'review the INTERPRETER_POSSIBLE_ACTIONS dictionary that maps action types like BUILD, DESTROY, MOVE, SPAWN, and FILL to structured command definitions', 'review_STOP_CONDITION_COMMANDS': 'review the STOP_CONDITION_COMMANDS dictionary that defines terminate_condition logic for timed or attribute-based command loops in DROIDLET', 'review_GET_MEMORY_COMMANDS': 'review the GET_MEMORY_COMMANDS dictionary that defines query structures for retrieving object attributes, counts, and spatial relationships in DROIDLET'}
```

## File: facebookresearch_fairo/droidlet/interpreter/tests/test_interpret_attribute.py

Prompts

```
['summarize the all_test_commands.py file which defines DROIDLET interpreter test command dictionaries for natural language parsing', 'review the FILTERS dictionary that defines object selection filters using where_clause predicates and selectors for the DROIDLET interpreter', 'review the INTERPRETER_POSSIBLE_ACTIONS dictionary that maps action types like BUILD, DESTROY, MOVE, SPAWN, and FILL to structured command definitions', 'review the STOP_CONDITION_COMMANDS dictionary that defines terminate_condition logic for timed or attribute-based command loops in DROIDLET', 'review the GET_MEMORY_COMMANDS dictionary that defines query structures for retrieving object attributes, counts, and spatial relationships in DROIDLET', 'test the interpret_span_value function to parse numeric span values from action dictionaries', 'test the maybe_specific_mem function to generate SQL queries for reference object lookups', 'test the interpret_linear_extent function to handle distance-based queries and error cases', 'test the interpret_task_info function to build AttributeSequence objects from task info dictionaries', 'test linear extent search with MemorySearcher to find reference objects by distance comparator', 'test the process_spans_and_remove_fixed_value function using logical form before and after processing dictionaries', 'test that location is not nested inside filters across all interpreter possible actions and reference objects', 'run the unittest test suite for interpreter utils including process spans and location reference object tests', 'review the TestInterpreterUtils class and its test_process_spans and test_location_reference_object test methods', 'summarize how logical form dictionaries are transformed by process_spans_and_remove_fixed_value for turn right, go forward, and where are my keys commands']
```

Usage

```
{'test_interpret_span_value': 'test the interpret_span_value function to parse numeric span values from action dictionaries', 'test_maybe_specific_mem': 'test the maybe_specific_mem function to generate SQL queries for reference object lookups', 'test_interpret_linear_extent': 'test the interpret_linear_extent function to handle distance-based queries and error cases', 'test_interpret_task_info': 'test the interpret_task_info function to build AttributeSequence objects from task info dictionaries', 'test_linear_extent_search': 'test linear extent search with MemorySearcher to find reference objects by distance comparator'}
```

## File: facebookresearch_fairo/droidlet/interpreter/tests/test_interpreter_utils.py

Prompts

```
['summarize the all_test_commands.py file which defines DROIDLET interpreter test command dictionaries for natural language parsing', 'review the FILTERS dictionary that defines object selection filters using where_clause predicates and selectors for the DROIDLET interpreter', 'review the INTERPRETER_POSSIBLE_ACTIONS dictionary that maps action types like BUILD, DESTROY, MOVE, SPAWN, and FILL to structured command definitions', 'review the STOP_CONDITION_COMMANDS dictionary that defines terminate_condition logic for timed or attribute-based command loops in DROIDLET', 'review the GET_MEMORY_COMMANDS dictionary that defines query structures for retrieving object attributes, counts, and spatial relationships in DROIDLET', 'test the interpret_span_value function to parse numeric span values from action dictionaries', 'test the maybe_specific_mem function to generate SQL queries for reference object lookups', 'test the interpret_linear_extent function to handle distance-based queries and error cases', 'test the interpret_task_info function to build AttributeSequence objects from task info dictionaries', 'test linear extent search with MemorySearcher to find reference objects by distance comparator', 'test the process_spans_and_remove_fixed_value function using logical form before and after processing dictionaries', 'test that location is not nested inside filters across all interpreter possible actions and reference objects', 'run the unittest test suite for interpreter utils including process spans and location reference object tests', 'review the TestInterpreterUtils class and its test_process_spans and test_location_reference_object test methods', 'summarize how logical form dictionaries are transformed by process_spans_and_remove_fixed_value for turn right, go forward, and where are my keys commands']
```

Usage

```
{'test_process_spans': 'test the process_spans_and_remove_fixed_value function using logical form before and after processing dictionaries', 'test_location_reference_object': 'test that location is not nested inside filters across all interpreter possible actions and reference objects', 'run_interpreter_utils_tests': 'run the unittest test suite for interpreter utils including process spans and location reference object tests', 'review_test_interpreter_utils': 'review the TestInterpreterUtils class and its test_process_spans and test_location_reference_object test methods', 'summarize_logical_form_processing': 'summarize how logical form dictionaries are transformed by process_spans_and_remove_fixed_value for turn right, go forward, and where are my keys commands'}
```

