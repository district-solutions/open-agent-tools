# Agent Python Tools

- repo: facebookresearch/docagent
- repo_uri: https://github.com/facebookresearch/docagent

## File: facebookresearch_docagent/eval_completeness.py

Prompts

```
['run docstring completeness tests on a Python source file and return evaluation results', 'process all Python files in a directory and aggregate docstring completeness evaluation results', 'print formatted evaluation results with color-coded completeness scores for classes and functions', 'evaluate the docstring completeness of classes and methods in a single Python file', 'recursively evaluate docstring completeness across all Python files in a directory tree', 'generate docstrings for all Python functions, classes, and methods in a repository using dependency-based ordering', 'generate placeholder test docstrings for a code component without making LLM calls', 'generate an AI docstring for a single function, class, or method using the orchestrator', 'insert or update a docstring into a Python file by modifying the AST and writing back', 'safely set or replace the docstring on an AST node with proper indentation handling', 'run the DocAgent web UI server on a specified host and port with optional debug mode', 'run the DocAgent web UI on a custom port using the --port argument', 'run the DocAgent web UI in debug mode using the --debug flag', 'check if all required dependencies like flask, flask_socketio, eventlet, yaml, tabulate, and colorama are installed', 'run the DocAgent web UI on the default host 127.0.0.1 and port 5000']
```

Usage

```
{'run_docstring_completeness_tests': 'run docstring completeness tests on a Python source file and return evaluation results', 'process_directory_for_docstring_eval': 'process all Python files in a directory and aggregate docstring completeness evaluation results', 'print_evaluation_results': 'print formatted evaluation results with color-coded completeness scores for classes and functions', 'evaluate_single_file_completeness': 'evaluate the docstring completeness of classes and methods in a single Python file', 'evaluate_directory_completeness': 'recursively evaluate docstring completeness across all Python files in a directory tree'}
```

## File: facebookresearch_docagent/generate_docstrings.py

Prompts

```
['run docstring completeness tests on a Python source file and return evaluation results', 'process all Python files in a directory and aggregate docstring completeness evaluation results', 'print formatted evaluation results with color-coded completeness scores for classes and functions', 'evaluate the docstring completeness of classes and methods in a single Python file', 'recursively evaluate docstring completeness across all Python files in a directory tree', 'generate docstrings for all Python functions, classes, and methods in a repository using dependency-based ordering', 'generate placeholder test docstrings for a code component without making LLM calls', 'generate an AI docstring for a single function, class, or method using the orchestrator', 'insert or update a docstring into a Python file by modifying the AST and writing back', 'safely set or replace the docstring on an AST node with proper indentation handling', 'run the DocAgent web UI server on a specified host and port with optional debug mode', 'run the DocAgent web UI on a custom port using the --port argument', 'run the DocAgent web UI in debug mode using the --debug flag', 'check if all required dependencies like flask, flask_socketio, eventlet, yaml, tabulate, and colorama are installed', 'run the DocAgent web UI on the default host 127.0.0.1 and port 5000']
```

Usage

```
{'generate_docstrings_for_repo': 'generate docstrings for all Python functions, classes, and methods in a repository using dependency-based ordering', 'generate_test_docstring': 'generate placeholder test docstrings for a code component without making LLM calls', 'generate_docstring_for_component': 'generate an AI docstring for a single function, class, or method using the orchestrator', 'set_docstring_in_file': 'insert or update a docstring into a Python file by modifying the AST and writing back', 'set_node_docstring': 'safely set or replace the docstring on an AST node with proper indentation handling'}
```

## File: facebookresearch_docagent/run_web_ui.py

Prompts

```
['run docstring completeness tests on a Python source file and return evaluation results', 'process all Python files in a directory and aggregate docstring completeness evaluation results', 'print formatted evaluation results with color-coded completeness scores for classes and functions', 'evaluate the docstring completeness of classes and methods in a single Python file', 'recursively evaluate docstring completeness across all Python files in a directory tree', 'generate docstrings for all Python functions, classes, and methods in a repository using dependency-based ordering', 'generate placeholder test docstrings for a code component without making LLM calls', 'generate an AI docstring for a single function, class, or method using the orchestrator', 'insert or update a docstring into a Python file by modifying the AST and writing back', 'safely set or replace the docstring on an AST node with proper indentation handling', 'run the DocAgent web UI server on a specified host and port with optional debug mode', 'run the DocAgent web UI on a custom port using the --port argument', 'run the DocAgent web UI in debug mode using the --debug flag', 'check if all required dependencies like flask, flask_socketio, eventlet, yaml, tabulate, and colorama are installed', 'run the DocAgent web UI on the default host 127.0.0.1 and port 5000']
```

Usage

```
{'run_docagent_web_ui': 'run the DocAgent web UI server on a specified host and port with optional debug mode', 'run_web_ui_custom_port': 'run the DocAgent web UI on a custom port using the --port argument', 'run_web_ui_debug': 'run the DocAgent web UI in debug mode using the --debug flag', 'check_dependencies': 'check if all required dependencies like flask, flask_socketio, eventlet, yaml, tabulate, and colorama are installed', 'run_web_ui_default': 'run the DocAgent web UI on the default host 127.0.0.1 and port 5000'}
```

