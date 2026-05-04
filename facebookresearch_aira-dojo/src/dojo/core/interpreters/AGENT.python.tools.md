# Agent Python Tools

- repo: facebookresearch/aira-dojo
- repo_uri: https://github.com/facebookresearch/aira-dojo

## File: facebookresearch_aira-dojo/src/dojo/core/interpreters/base.py

Prompts

```
['create an ExecutionResult dataclass instance with term_out, exec_time, exit_code, eval_return, and timed_out fields', 'get an empty ExecutionResult using the static get_empty method with default values', 'serialize an ExecutionResult instance to JSON using the DataClassJsonMixin to_json method', 'implement a concrete subclass of the abstract Interpreter base class with run and cleanup_session methods', 'run code in an Interpreter subclass using the run method with optional reset_session and persist_file flags', 'run a Python code snippet in an isolated subprocess with timeout and capture stdout stderr output', 'execute Python code by resetting the interpreter session and returning an ExecutionResult with terminal output', 'terminate the child Python process with escalation from terminate to kill to SIGKILL', 'generate a formatted exception summary with stack trace using IPython or standard traceback formatting', 'redirect stdout and stderr to a multiprocessing Queue using the RedirectQueue file-like object', 'copy files or directories from source to destination using symlinks or hard copies', 'extract all zip archives in a directory tree and remove the original zip files', 'prepare and validate an OmegaConf configuration by resolving paths and generating experiment names', 'remove unwanted files and directories like __MACOSX and .DS_Store from a directory tree', 'display an OmegaConf configuration in formatted YAML style with syntax highlighting']
```

Usage

```
{'create_execution_result': 'create an ExecutionResult dataclass instance with term_out, exec_time, exit_code, eval_return, and timed_out fields', 'get_empty_execution_result': 'get an empty ExecutionResult using the static get_empty method with default values', 'serialize_execution_result_to_json': 'serialize an ExecutionResult instance to JSON using the DataClassJsonMixin to_json method', 'implement_interpreter_subclass': 'implement a concrete subclass of the abstract Interpreter base class with run and cleanup_session methods', 'run_code_in_interpreter': 'run code in an Interpreter subclass using the run method with optional reset_session and persist_file flags'}
```

## File: facebookresearch_aira-dojo/src/dojo/core/interpreters/python.py

Prompts

```
['create an ExecutionResult dataclass instance with term_out, exec_time, exit_code, eval_return, and timed_out fields', 'get an empty ExecutionResult using the static get_empty method with default values', 'serialize an ExecutionResult instance to JSON using the DataClassJsonMixin to_json method', 'implement a concrete subclass of the abstract Interpreter base class with run and cleanup_session methods', 'run code in an Interpreter subclass using the run method with optional reset_session and persist_file flags', 'run a Python code snippet in an isolated subprocess with timeout and capture stdout stderr output', 'execute Python code by resetting the interpreter session and returning an ExecutionResult with terminal output', 'terminate the child Python process with escalation from terminate to kill to SIGKILL', 'generate a formatted exception summary with stack trace using IPython or standard traceback formatting', 'redirect stdout and stderr to a multiprocessing Queue using the RedirectQueue file-like object', 'copy files or directories from source to destination using symlinks or hard copies', 'extract all zip archives in a directory tree and remove the original zip files', 'prepare and validate an OmegaConf configuration by resolving paths and generating experiment names', 'remove unwanted files and directories like __MACOSX and .DS_Store from a directory tree', 'display an OmegaConf configuration in formatted YAML style with syntax highlighting']
```

Usage

```
{'run_python_code_in_isolated_process': 'run a Python code snippet in an isolated subprocess with timeout and capture stdout stderr output', 'execute_code_with_session_reset': 'execute Python code by resetting the interpreter session and returning an ExecutionResult with terminal output', 'cleanup_python_interpreter_process': 'terminate the child Python process with escalation from terminate to kill to SIGKILL', 'generate_exception_summary_with_traceback': 'generate a formatted exception summary with stack trace using IPython or standard traceback formatting', 'redirect_stdout_to_multiprocessing_queue': 'redirect stdout and stderr to a multiprocessing Queue using the RedirectQueue file-like object'}
```

## File: facebookresearch_aira-dojo/src/dojo/core/interpreters/utils.py

Prompts

```
['create an ExecutionResult dataclass instance with term_out, exec_time, exit_code, eval_return, and timed_out fields', 'get an empty ExecutionResult using the static get_empty method with default values', 'serialize an ExecutionResult instance to JSON using the DataClassJsonMixin to_json method', 'implement a concrete subclass of the abstract Interpreter base class with run and cleanup_session methods', 'run code in an Interpreter subclass using the run method with optional reset_session and persist_file flags', 'run a Python code snippet in an isolated subprocess with timeout and capture stdout stderr output', 'execute Python code by resetting the interpreter session and returning an ExecutionResult with terminal output', 'terminate the child Python process with escalation from terminate to kill to SIGKILL', 'generate a formatted exception summary with stack trace using IPython or standard traceback formatting', 'redirect stdout and stderr to a multiprocessing Queue using the RedirectQueue file-like object', 'copy files or directories from source to destination using symlinks or hard copies', 'extract all zip archives in a directory tree and remove the original zip files', 'prepare and validate an OmegaConf configuration by resolving paths and generating experiment names', 'remove unwanted files and directories like __MACOSX and .DS_Store from a directory tree', 'display an OmegaConf configuration in formatted YAML style with syntax highlighting']
```

Usage

```
{'copy_contents': 'copy files or directories from source to destination using symlinks or hard copies', 'extract_all_archives': 'extract all zip archives in a directory tree and remove the original zip files', 'prepare_configuration': 'prepare and validate an OmegaConf configuration by resolving paths and generating experiment names', 'remove_unwanted_items': 'remove unwanted files and directories like __MACOSX and .DS_Store from a directory tree', 'display_configuration': 'display an OmegaConf configuration in formatted YAML style with syntax highlighting'}
```

