# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/perception/semantic_parsing/tests/test_nsp_loading.py

Prompts

```
['test the NSPBertModel parse method by parsing chat strings like come here hello and dance', 'test loading an NSPBertModel with a valid model directory and data directory path', 'test that NSPBertModel raises an exception when given an invalid model directory path', 'run the unittest test suite for NSPBertModel loading and parsing chat input to logical forms', 'review the TestNSPModel unittest class that validates NSPBertModel parse returns a dict with dialogue_type', 'test the insert_spaces function that adds spaces around numbers and punctuation in chat input', 'test the preprocess_chat function that tokenizes user chat input for the dialogue manager', 'run the unittest test suite for the preprocess module including insert_spaces and preprocess_chat', 'review the MyTestCase class and its test methods for the preprocess utility functions', 'refactor the preprocess_chat function to handle additional edge cases for chat tokenization', 'run the DataValidationTest unittest suite to validate parse trees against JSON schemas', 'test high priority command parse trees using JSONValidator in array mode', 'test short command parse trees using JSONValidator in array mode', 'test annotated dataset parse trees using JSONValidator in array mode', 'test horizon world dataset parse trees using JSONValidator in array mode', 'run the unittest suite to validate parse tree JSON structures using NSPQuerier', 'test that validate_parse_tree returns False when given an empty dictionary as input', 'test that validate_parse_tree returns True for action dicts with array text spans', 'test that validate_parse_tree returns True for action dicts with string text spans', 'review the TestValidateParseTree class and its three test methods for NSPQuerier validation', 'run the TestDialogueManager test to verify semantic parsing pipeline achieves 100 percent accuracy', 'compare two nested dictionaries recursively checking keys, types, and values for structural equality', 'compare two dialogue parse dictionaries validating event sequences and dialogue types match', 'remove text_span keys from a parsed dialogue dictionary to normalize model output for comparison', 'recursively remove text_span keys from any nested dictionary structure']
```

Usage

```
{'test_NSPBertModel_parse': 'test the NSPBertModel parse method by parsing chat strings like come here hello and dance', 'test_NSPBertModel_instantiation': 'test loading an NSPBertModel with a valid model directory and data directory path', 'test_NSPBertModel_invalid_dir': 'test that NSPBertModel raises an exception when given an invalid model directory path', 'run_test_nsp_loading': 'run the unittest test suite for NSPBertModel loading and parsing chat input to logical forms', 'review_TestNSPModel': 'review the TestNSPModel unittest class that validates NSPBertModel parse returns a dict with dialogue_type'}
```

## File: facebookresearch_fairo/droidlet/perception/semantic_parsing/tests/test_preprocess.py

Prompts

```
['test the NSPBertModel parse method by parsing chat strings like come here hello and dance', 'test loading an NSPBertModel with a valid model directory and data directory path', 'test that NSPBertModel raises an exception when given an invalid model directory path', 'run the unittest test suite for NSPBertModel loading and parsing chat input to logical forms', 'review the TestNSPModel unittest class that validates NSPBertModel parse returns a dict with dialogue_type', 'test the insert_spaces function that adds spaces around numbers and punctuation in chat input', 'test the preprocess_chat function that tokenizes user chat input for the dialogue manager', 'run the unittest test suite for the preprocess module including insert_spaces and preprocess_chat', 'review the MyTestCase class and its test methods for the preprocess utility functions', 'refactor the preprocess_chat function to handle additional edge cases for chat tokenization', 'run the DataValidationTest unittest suite to validate parse trees against JSON schemas', 'test high priority command parse trees using JSONValidator in array mode', 'test short command parse trees using JSONValidator in array mode', 'test annotated dataset parse trees using JSONValidator in array mode', 'test horizon world dataset parse trees using JSONValidator in array mode', 'run the unittest suite to validate parse tree JSON structures using NSPQuerier', 'test that validate_parse_tree returns False when given an empty dictionary as input', 'test that validate_parse_tree returns True for action dicts with array text spans', 'test that validate_parse_tree returns True for action dicts with string text spans', 'review the TestValidateParseTree class and its three test methods for NSPQuerier validation', 'run the TestDialogueManager test to verify semantic parsing pipeline achieves 100 percent accuracy', 'compare two nested dictionaries recursively checking keys, types, and values for structural equality', 'compare two dialogue parse dictionaries validating event sequences and dialogue types match', 'remove text_span keys from a parsed dialogue dictionary to normalize model output for comparison', 'recursively remove text_span keys from any nested dictionary structure']
```

Usage

```
{'test_insert_spaces': 'test the insert_spaces function that adds spaces around numbers and punctuation in chat input', 'test_preprocess_chat': 'test the preprocess_chat function that tokenizes user chat input for the dialogue manager', 'run_preprocess_tests': 'run the unittest test suite for the preprocess module including insert_spaces and preprocess_chat', 'review_MyTestCase': 'review the MyTestCase class and its test methods for the preprocess utility functions', 'refactor_preprocess_chat': 'refactor the preprocess_chat function to handle additional edge cases for chat tokenization'}
```

## File: facebookresearch_fairo/droidlet/perception/semantic_parsing/tests/test_validate_dataset.py

Prompts

```
['test the NSPBertModel parse method by parsing chat strings like come here hello and dance', 'test loading an NSPBertModel with a valid model directory and data directory path', 'test that NSPBertModel raises an exception when given an invalid model directory path', 'run the unittest test suite for NSPBertModel loading and parsing chat input to logical forms', 'review the TestNSPModel unittest class that validates NSPBertModel parse returns a dict with dialogue_type', 'test the insert_spaces function that adds spaces around numbers and punctuation in chat input', 'test the preprocess_chat function that tokenizes user chat input for the dialogue manager', 'run the unittest test suite for the preprocess module including insert_spaces and preprocess_chat', 'review the MyTestCase class and its test methods for the preprocess utility functions', 'refactor the preprocess_chat function to handle additional edge cases for chat tokenization', 'run the DataValidationTest unittest suite to validate parse trees against JSON schemas', 'test high priority command parse trees using JSONValidator in array mode', 'test short command parse trees using JSONValidator in array mode', 'test annotated dataset parse trees using JSONValidator in array mode', 'test horizon world dataset parse trees using JSONValidator in array mode', 'run the unittest suite to validate parse tree JSON structures using NSPQuerier', 'test that validate_parse_tree returns False when given an empty dictionary as input', 'test that validate_parse_tree returns True for action dicts with array text spans', 'test that validate_parse_tree returns True for action dicts with string text spans', 'review the TestValidateParseTree class and its three test methods for NSPQuerier validation', 'run the TestDialogueManager test to verify semantic parsing pipeline achieves 100 percent accuracy', 'compare two nested dictionaries recursively checking keys, types, and values for structural equality', 'compare two dialogue parse dictionaries validating event sequences and dialogue types match', 'remove text_span keys from a parsed dialogue dictionary to normalize model output for comparison', 'recursively remove text_span keys from any nested dictionary structure']
```

Usage

```
{'run_data_validation_tests': 'run the DataValidationTest unittest suite to validate parse trees against JSON schemas', 'test_high_pri_commands': 'test high priority command parse trees using JSONValidator in array mode', 'test_short_commands': 'test short command parse trees using JSONValidator in array mode', 'test_annotated_data': 'test annotated dataset parse trees using JSONValidator in array mode', 'test_horizon_world_data': 'test horizon world dataset parse trees using JSONValidator in array mode'}
```

## File: facebookresearch_fairo/droidlet/perception/semantic_parsing/tests/test_validate_parse_tree.py

Prompts

```
['test the NSPBertModel parse method by parsing chat strings like come here hello and dance', 'test loading an NSPBertModel with a valid model directory and data directory path', 'test that NSPBertModel raises an exception when given an invalid model directory path', 'run the unittest test suite for NSPBertModel loading and parsing chat input to logical forms', 'review the TestNSPModel unittest class that validates NSPBertModel parse returns a dict with dialogue_type', 'test the insert_spaces function that adds spaces around numbers and punctuation in chat input', 'test the preprocess_chat function that tokenizes user chat input for the dialogue manager', 'run the unittest test suite for the preprocess module including insert_spaces and preprocess_chat', 'review the MyTestCase class and its test methods for the preprocess utility functions', 'refactor the preprocess_chat function to handle additional edge cases for chat tokenization', 'run the DataValidationTest unittest suite to validate parse trees against JSON schemas', 'test high priority command parse trees using JSONValidator in array mode', 'test short command parse trees using JSONValidator in array mode', 'test annotated dataset parse trees using JSONValidator in array mode', 'test horizon world dataset parse trees using JSONValidator in array mode', 'run the unittest suite to validate parse tree JSON structures using NSPQuerier', 'test that validate_parse_tree returns False when given an empty dictionary as input', 'test that validate_parse_tree returns True for action dicts with array text spans', 'test that validate_parse_tree returns True for action dicts with string text spans', 'review the TestValidateParseTree class and its three test methods for NSPQuerier validation', 'run the TestDialogueManager test to verify semantic parsing pipeline achieves 100 percent accuracy', 'compare two nested dictionaries recursively checking keys, types, and values for structural equality', 'compare two dialogue parse dictionaries validating event sequences and dialogue types match', 'remove text_span keys from a parsed dialogue dictionary to normalize model output for comparison', 'recursively remove text_span keys from any nested dictionary structure']
```

Usage

```
{'run_test_validate_parse_tree': 'run the unittest suite to validate parse tree JSON structures using NSPQuerier', 'test_validate_bad_json': 'test that validate_parse_tree returns False when given an empty dictionary as input', 'test_validate_array_span_json': 'test that validate_parse_tree returns True for action dicts with array text spans', 'test_validate_string_span_json': 'test that validate_parse_tree returns True for action dicts with string text spans', 'review_TestValidateParseTree': 'review the TestValidateParseTree class and its three test methods for NSPQuerier validation'}
```

## File: facebookresearch_fairo/droidlet/perception/semantic_parsing/tests/test_y_print_parsing_report.py

Prompts

```
['test the NSPBertModel parse method by parsing chat strings like come here hello and dance', 'test loading an NSPBertModel with a valid model directory and data directory path', 'test that NSPBertModel raises an exception when given an invalid model directory path', 'run the unittest test suite for NSPBertModel loading and parsing chat input to logical forms', 'review the TestNSPModel unittest class that validates NSPBertModel parse returns a dict with dialogue_type', 'test the insert_spaces function that adds spaces around numbers and punctuation in chat input', 'test the preprocess_chat function that tokenizes user chat input for the dialogue manager', 'run the unittest test suite for the preprocess module including insert_spaces and preprocess_chat', 'review the MyTestCase class and its test methods for the preprocess utility functions', 'refactor the preprocess_chat function to handle additional edge cases for chat tokenization', 'run the DataValidationTest unittest suite to validate parse trees against JSON schemas', 'test high priority command parse trees using JSONValidator in array mode', 'test short command parse trees using JSONValidator in array mode', 'test annotated dataset parse trees using JSONValidator in array mode', 'test horizon world dataset parse trees using JSONValidator in array mode', 'run the unittest suite to validate parse tree JSON structures using NSPQuerier', 'test that validate_parse_tree returns False when given an empty dictionary as input', 'test that validate_parse_tree returns True for action dicts with array text spans', 'test that validate_parse_tree returns True for action dicts with string text spans', 'review the TestValidateParseTree class and its three test methods for NSPQuerier validation', 'run the TestDialogueManager test to verify semantic parsing pipeline achieves 100 percent accuracy', 'compare two nested dictionaries recursively checking keys, types, and values for structural equality', 'compare two dialogue parse dictionaries validating event sequences and dialogue types match', 'remove text_span keys from a parsed dialogue dictionary to normalize model output for comparison', 'recursively remove text_span keys from any nested dictionary structure']
```

Usage

```
{'test_semantic_parsing_accuracy': 'run the TestDialogueManager test to verify semantic parsing pipeline achieves 100 percent accuracy', 'compare_dicts': 'compare two nested dictionaries recursively checking keys, types, and values for structural equality', 'compare_full_dictionaries': 'compare two dialogue parse dictionaries validating event sequences and dialogue types match', 'remove_text_span': 'remove text_span keys from a parsed dialogue dictionary to normalize model output for comparison', 'remove_key_text_span': 'recursively remove text_span keys from any nested dictionary structure'}
```

