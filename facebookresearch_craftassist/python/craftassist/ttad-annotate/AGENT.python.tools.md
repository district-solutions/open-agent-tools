# Agent Python Tools

- repo: facebookresearch/craftassist
- repo_uri: https://github.com/facebookresearch/craftassist

## File: facebookresearch_craftassist/python/craftassist/ttad-annotate/analyze_outputs.py

Prompts

```
['summarize the python any_two function that checks if any two of three arguments are equal', 'review the python any_two function to check if any two of three values match', 'test the python any_two function with various combinations of three arguments', 'refactor the python any_two function to accept a variable number of arguments instead of three', 'review the python analyze_outputs script that reads CSV and tmp files to find faulty processed entries', 'run the process_results CLI to aggregate and display annotation results from a CSV file', 'process a single annotation result dictionary and return the worker id, action dict, and words', 'process a flat key-value dictionary into a nested structure with spans and location handling', 'process a loop annotation dictionary into a structured repeat dict with FOR, ALL, or NEVER keys', 'fix word span indices in an action dict after removing empty words from the word list', 'render a fieldset HTML element for a survey question with radio options and span annotations', 'render a group of 25 checkbox buttons for word-level span annotation in a survey form', 'render radio button options with nested child questions and onchange toggle logic for survey flows', 'generate an HTML label tag with optional Bootstrap tooltip attributes for form elements', 'generate a sanitized child element ID from a parent ID and arbitrary text using regex']
```

Usage

```
{'summarize_any_two': 'summarize the python any_two function that checks if any two of three arguments are equal', 'review_any_two': 'review the python any_two function to check if any two of three values match', 'test_any_two': 'test the python any_two function with various combinations of three arguments', 'refactor_any_two': 'refactor the python any_two function to accept a variable number of arguments instead of three', 'review_analyze_outputs_script': 'review the python analyze_outputs script that reads CSV and tmp files to find faulty processed entries'}
```

## File: facebookresearch_craftassist/python/craftassist/ttad-annotate/process_results.py

Prompts

```
['summarize the python any_two function that checks if any two of three arguments are equal', 'review the python any_two function to check if any two of three values match', 'test the python any_two function with various combinations of three arguments', 'refactor the python any_two function to accept a variable number of arguments instead of three', 'review the python analyze_outputs script that reads CSV and tmp files to find faulty processed entries', 'run the process_results CLI to aggregate and display annotation results from a CSV file', 'process a single annotation result dictionary and return the worker id, action dict, and words', 'process a flat key-value dictionary into a nested structure with spans and location handling', 'process a loop annotation dictionary into a structured repeat dict with FOR, ALL, or NEVER keys', 'fix word span indices in an action dict after removing empty words from the word list', 'render a fieldset HTML element for a survey question with radio options and span annotations', 'render a group of 25 checkbox buttons for word-level span annotation in a survey form', 'render radio button options with nested child questions and onchange toggle logic for survey flows', 'generate an HTML label tag with optional Bootstrap tooltip attributes for form elements', 'generate a sanitized child element ID from a parent ID and arbitrary text using regex']
```

Usage

```
{'run_process_results_cli': 'run the process_results CLI to aggregate and display annotation results from a CSV file', 'process_result': 'process a single annotation result dictionary and return the worker id, action dict, and words', 'process_dict': 'process a flat key-value dictionary into a nested structure with spans and location handling', 'process_repeat_dict': 'process a loop annotation dictionary into a structured repeat dict with FOR, ALL, or NEVER keys', 'fix_spans_due_to_empty_words': 'fix word span indices in an action dict after removing empty words from the word list'}
```

## File: facebookresearch_craftassist/python/craftassist/ttad-annotate/render_flows.py

Prompts

```
['summarize the python any_two function that checks if any two of three arguments are equal', 'review the python any_two function to check if any two of three values match', 'test the python any_two function with various combinations of three arguments', 'refactor the python any_two function to accept a variable number of arguments instead of three', 'review the python analyze_outputs script that reads CSV and tmp files to find faulty processed entries', 'run the process_results CLI to aggregate and display annotation results from a CSV file', 'process a single annotation result dictionary and return the worker id, action dict, and words', 'process a flat key-value dictionary into a nested structure with spans and location handling', 'process a loop annotation dictionary into a structured repeat dict with FOR, ALL, or NEVER keys', 'fix word span indices in an action dict after removing empty words from the word list', 'render a fieldset HTML element for a survey question with radio options and span annotations', 'render a group of 25 checkbox buttons for word-level span annotation in a survey form', 'render radio button options with nested child questions and onchange toggle logic for survey flows', 'generate an HTML label tag with optional Bootstrap tooltip attributes for form elements', 'generate a sanitized child element ID from a parent ID and arbitrary text using regex']
```

Usage

```
{'render_question_fieldset': 'render a fieldset HTML element for a survey question with radio options and span annotations', 'render_span_checkboxes': 'render a group of 25 checkbox buttons for word-level span annotation in a survey form', 'render_radio_options': 'render radio button options with nested child questions and onchange toggle logic for survey flows', 'generate_label_tag': 'generate an HTML label tag with optional Bootstrap tooltip attributes for form elements', 'generate_child_id': 'generate a sanitized child element ID from a parent ID and arbitrary text using regex'}
```

