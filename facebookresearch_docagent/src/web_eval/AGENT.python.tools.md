# Agent Python Tools

- repo: facebookresearch/docagent
- repo_uri: https://github.com/facebookresearch/docagent

## File: facebookresearch_docagent/src/web_eval/app.py

Prompts

```
['run a flask web server to evaluate docstring completeness and helpfulness for a Python repository', 'run docstring completeness tests on a single Python source file and return evaluation results', 'process all Python files in a directory and aggregate docstring evaluation results with statistics', 'test an OpenAI or Claude LLM API connection by sending a simple query and returning the response', 'evaluate the helpfulness of a specific docstring component like summary, description, or parameters using an LLM', 'parse a score and explanation from raw LLM response text using regex patterns', 'parse a Google-style docstring into a dictionary with canonical section names and their content', 'extract the summary component from a Google-style docstring using the robust parser', 'extract the parameters component from a Google-style docstring using the robust parser', 'extract the returns component from a Google-style docstring using the robust parser', 'run all test cases for the Google-style docstring parser to verify parsing behavior', 'test parsing a Google-style docstring with args, returns, raises, and examples sections', 'test extracting individual components like summary, description, parameters, returns from a docstring', 'test parsing a docstring that uses explicit Summary and Description section markers', 'test parsing docstrings with unusual indentation, missing sections, or extra spacing between sections']
```

Usage

```
{'run_docstring_evaluation_server': 'run a flask web server to evaluate docstring completeness and helpfulness for a Python repository', 'run_docstring_tests_on_file': 'run docstring completeness tests on a single Python source file and return evaluation results', 'process_directory_for_docstrings': 'process all Python files in a directory and aggregate docstring evaluation results with statistics', 'test_llm_api_connection': 'test an OpenAI or Claude LLM API connection by sending a simple query and returning the response', 'evaluate_docstring_helpfulness': 'evaluate the helpfulness of a specific docstring component like summary, description, or parameters using an LLM'}
```

## File: facebookresearch_docagent/src/web_eval/helpers.py

Prompts

```
['run a flask web server to evaluate docstring completeness and helpfulness for a Python repository', 'run docstring completeness tests on a single Python source file and return evaluation results', 'process all Python files in a directory and aggregate docstring evaluation results with statistics', 'test an OpenAI or Claude LLM API connection by sending a simple query and returning the response', 'evaluate the helpfulness of a specific docstring component like summary, description, or parameters using an LLM', 'parse a score and explanation from raw LLM response text using regex patterns', 'parse a Google-style docstring into a dictionary with canonical section names and their content', 'extract the summary component from a Google-style docstring using the robust parser', 'extract the parameters component from a Google-style docstring using the robust parser', 'extract the returns component from a Google-style docstring using the robust parser', 'run all test cases for the Google-style docstring parser to verify parsing behavior', 'test parsing a Google-style docstring with args, returns, raises, and examples sections', 'test extracting individual components like summary, description, parameters, returns from a docstring', 'test parsing a docstring that uses explicit Summary and Description section markers', 'test parsing docstrings with unusual indentation, missing sections, or extra spacing between sections']
```

Usage

```
{'parse_llm_score_from_text': 'parse a score and explanation from raw LLM response text using regex patterns', 'parse_google_style_docstring': 'parse a Google-style docstring into a dictionary with canonical section names and their content', 'extract_docstring_component_summary': 'extract the summary component from a Google-style docstring using the robust parser', 'extract_docstring_component_parameters': 'extract the parameters component from a Google-style docstring using the robust parser', 'extract_docstring_component_returns': 'extract the returns component from a Google-style docstring using the robust parser'}
```

## File: facebookresearch_docagent/src/web_eval/test_docstring_parser.py

Prompts

```
['run a flask web server to evaluate docstring completeness and helpfulness for a Python repository', 'run docstring completeness tests on a single Python source file and return evaluation results', 'process all Python files in a directory and aggregate docstring evaluation results with statistics', 'test an OpenAI or Claude LLM API connection by sending a simple query and returning the response', 'evaluate the helpfulness of a specific docstring component like summary, description, or parameters using an LLM', 'parse a score and explanation from raw LLM response text using regex patterns', 'parse a Google-style docstring into a dictionary with canonical section names and their content', 'extract the summary component from a Google-style docstring using the robust parser', 'extract the parameters component from a Google-style docstring using the robust parser', 'extract the returns component from a Google-style docstring using the robust parser', 'run all test cases for the Google-style docstring parser to verify parsing behavior', 'test parsing a Google-style docstring with args, returns, raises, and examples sections', 'test extracting individual components like summary, description, parameters, returns from a docstring', 'test parsing a docstring that uses explicit Summary and Description section markers', 'test parsing docstrings with unusual indentation, missing sections, or extra spacing between sections']
```

Usage

```
{'run_docstring_parser_tests': 'run all test cases for the Google-style docstring parser to verify parsing behavior', 'test_parse_google_style_docstring': 'test parsing a Google-style docstring with args, returns, raises, and examples sections', 'test_extract_docstring_component': 'test extracting individual components like summary, description, parameters, returns from a docstring', 'test_docstring_with_explicit_markers': 'test parsing a docstring that uses explicit Summary and Description section markers', 'test_docstring_edge_cases': 'test parsing docstrings with unusual indentation, missing sections, or extra spacing between sections'}
```

