# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/distributed/elastic/multiprocessing/errors/error_handler.py

Prompts

```
['initialize an ErrorHandler instance to enable fault handlers before running error-capturing code', 'record an exception using ErrorHandler.record_exception to write structured JSON error info to the TORCHELASTIC_ERROR_FILE', 'dump a child process error file to the parent error file using ErrorHandler.dump_error_file with a rootcause path and exit code', 'override the exit code in a rootcause error file using ErrorHandler.override_error_code_in_rootcause_data', 'get the error file path from the TORCHELASTIC_ERROR_FILE environment variable using ErrorHandler._get_error_file_path', 'create an ErrorHandler instance via get_error_handler() for multiprocessing error reporting', 'dump a child process error file into the parent error file with an overridden error code', 'override the exit code in a child process rootcause error JSON data']
```

Usage

```
{'initialize_error_handler': 'initialize an ErrorHandler instance to enable fault handlers before running error-capturing code', 'record_exception_error_handler': 'record an exception using ErrorHandler.record_exception to write structured JSON error info to the TORCHELASTIC_ERROR_FILE', 'dump_error_file_error_handler': 'dump a child process error file to the parent error file using ErrorHandler.dump_error_file with a rootcause path and exit code', 'override_error_code_rootcause': 'override the exit code in a rootcause error file using ErrorHandler.override_error_code_in_rootcause_data', 'get_error_file_path': 'get the error file path from the TORCHELASTIC_ERROR_FILE environment variable using ErrorHandler._get_error_file_path'}
```

## File: pytorch_pytorch/torch/distributed/elastic/multiprocessing/errors/handlers.py

Prompts

```
['initialize an ErrorHandler instance to enable fault handlers before running error-capturing code', 'record an exception using ErrorHandler.record_exception to write structured JSON error info to the TORCHELASTIC_ERROR_FILE', 'dump a child process error file to the parent error file using ErrorHandler.dump_error_file with a rootcause path and exit code', 'override the exit code in a rootcause error file using ErrorHandler.override_error_code_in_rootcause_data', 'get the error file path from the TORCHELASTIC_ERROR_FILE environment variable using ErrorHandler._get_error_file_path', 'create an ErrorHandler instance via get_error_handler() for multiprocessing error reporting', 'dump a child process error file into the parent error file with an overridden error code', 'override the exit code in a child process rootcause error JSON data']
```

Usage

```
{'create_error_handler': 'create an ErrorHandler instance via get_error_handler() for multiprocessing error reporting', 'initialize_error_handler': 'initialize the error handler to enable fault handling and signal registration before running code', 'record_exception_error_handler': 'record an exception with traceback and timestamp into the TORCHELASTIC_ERROR_FILE as JSON', 'dump_error_file': 'dump a child process error file into the parent error file with an overridden error code', 'override_error_code_in_rootcause_data': 'override the exit code in a child process rootcause error JSON data'}
```

