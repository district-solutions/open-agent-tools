# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/mrp/tests/test_import.py

Prompts

```
['test importing all processes from an msetup directory using mrp.import_msetup', 'test importing processes from a specific msetup.py file path using mrp.import_msetup', 'test importing only proc1 from msetup using the processes filter parameter', 'test importing only proc2 from msetup using the processes filter parameter', 'test importing proc1 and proc2 together using the processes list filter', 'test that process_def.process raises ValueError when env contains non-string keys', 'review the process_def.process function env validation logic for dict[str, str] type checking', 'summarize the test_process_def module which validates error handling for invalid env arguments', 'test the shell_join function that joins a list of strings into a shell-safe command string', 'test the NoEscape class that wraps strings to skip shell quoting in shell_join', 'test the nested_dict_update function that recursively merges one dictionary into another', 'test the random_string function that generates a random string from a given alphabet and length', 'test the pid_children function that yields child process IDs for a given parent PID']
```

Usage

```
{'test_import_msetup_all_processes': 'test importing all processes from an msetup directory using mrp.import_msetup', 'test_import_msetup_single_file': 'test importing processes from a specific msetup.py file path using mrp.import_msetup', 'test_import_msetup_filter_proc1': 'test importing only proc1 from msetup using the processes filter parameter', 'test_import_msetup_filter_proc2': 'test importing only proc2 from msetup using the processes filter parameter', 'test_import_msetup_filter_multiple': 'test importing proc1 and proc2 together using the processes list filter'}
```

## File: facebookresearch_fairo/mrp/tests/test_process_def.py

Prompts

```
['test importing all processes from an msetup directory using mrp.import_msetup', 'test importing processes from a specific msetup.py file path using mrp.import_msetup', 'test importing only proc1 from msetup using the processes filter parameter', 'test importing only proc2 from msetup using the processes filter parameter', 'test importing proc1 and proc2 together using the processes list filter', 'test that process_def.process raises ValueError when env contains non-string keys', 'review the process_def.process function env validation logic for dict[str, str] type checking', 'summarize the test_process_def module which validates error handling for invalid env arguments', 'test the shell_join function that joins a list of strings into a shell-safe command string', 'test the NoEscape class that wraps strings to skip shell quoting in shell_join', 'test the nested_dict_update function that recursively merges one dictionary into another', 'test the random_string function that generates a random string from a given alphabet and length', 'test the pid_children function that yields child process IDs for a given parent PID']
```

Usage

```
{'test_process_def_invalid_env': 'test that process_def.process raises ValueError when env contains non-string keys', 'review_process_def_process_validation': 'review the process_def.process function env validation logic for dict[str, str] type checking', 'summarize_test_process_def': 'summarize the test_process_def module which validates error handling for invalid env arguments'}
```

## File: facebookresearch_fairo/mrp/tests/test_util.py

Prompts

```
['test importing all processes from an msetup directory using mrp.import_msetup', 'test importing processes from a specific msetup.py file path using mrp.import_msetup', 'test importing only proc1 from msetup using the processes filter parameter', 'test importing only proc2 from msetup using the processes filter parameter', 'test importing proc1 and proc2 together using the processes list filter', 'test that process_def.process raises ValueError when env contains non-string keys', 'review the process_def.process function env validation logic for dict[str, str] type checking', 'summarize the test_process_def module which validates error handling for invalid env arguments', 'test the shell_join function that joins a list of strings into a shell-safe command string', 'test the NoEscape class that wraps strings to skip shell quoting in shell_join', 'test the nested_dict_update function that recursively merges one dictionary into another', 'test the random_string function that generates a random string from a given alphabet and length', 'test the pid_children function that yields child process IDs for a given parent PID']
```

Usage

```
{'test_shell_join': 'test the shell_join function that joins a list of strings into a shell-safe command string', 'test_noescape': 'test the NoEscape class that wraps strings to skip shell quoting in shell_join', 'test_nested_dict_update': 'test the nested_dict_update function that recursively merges one dictionary into another', 'test_random_string': 'test the random_string function that generates a random string from a given alphabet and length', 'test_pid_children': 'test the pid_children function that yields child process IDs for a given parent PID'}
```

