# Agent Python Tools

- repo: facebookresearch/aira-dojo
- repo_uri: https://github.com/facebookresearch/aira-dojo

## File: facebookresearch_aira-dojo/src/dojo/config_dataclasses/interpreter/base.py

Prompts

```
['create an InterpreterConfig dataclass instance with a custom working_dir and timeout value', 'configure the InterpreterConfig working_dir field to point to a custom workspace agent directory', 'configure the InterpreterConfig timeout field to set a custom execution timeout for the interpreter', 'validate an InterpreterConfig instance by calling its validate method to check configuration correctness', 'inspect the InterpreterConfig dataclass fields working_dir and timeout using dataclass metadata', 'create a JupyterInterpreterConfig dataclass instance with superimage directory, version, and environment settings', 'configure JupyterInterpreterConfig to strip ANSI escape codes from container output', 'configure JupyterInterpreterConfig with read-only host-to-container bind mounts', 'configure JupyterInterpreterConfig with custom environment variables for the container', 'validate a JupyterInterpreterConfig instance by calling its validate method', 'review the PythonInterpreterConfig dataclass that configures symlink usage and IPython traceback formatting for the interpreter', 'create a PythonInterpreterConfig instance with use_symlinks and format_tb_ipython settings for interpreter configuration', 'validate a PythonInterpreterConfig instance by calling its validate method to check configuration correctness']
```

Usage

```
{'create_InterpreterConfig': 'create an InterpreterConfig dataclass instance with a custom working_dir and timeout value', 'configure_InterpreterConfig_working_dir': 'configure the InterpreterConfig working_dir field to point to a custom workspace agent directory', 'configure_InterpreterConfig_timeout': 'configure the InterpreterConfig timeout field to set a custom execution timeout for the interpreter', 'validate_InterpreterConfig': 'validate an InterpreterConfig instance by calling its validate method to check configuration correctness', 'inspect_InterpreterConfig_fields': 'inspect the InterpreterConfig dataclass fields working_dir and timeout using dataclass metadata'}
```

## File: facebookresearch_aira-dojo/src/dojo/config_dataclasses/interpreter/jupyter.py

Prompts

```
['create an InterpreterConfig dataclass instance with a custom working_dir and timeout value', 'configure the InterpreterConfig working_dir field to point to a custom workspace agent directory', 'configure the InterpreterConfig timeout field to set a custom execution timeout for the interpreter', 'validate an InterpreterConfig instance by calling its validate method to check configuration correctness', 'inspect the InterpreterConfig dataclass fields working_dir and timeout using dataclass metadata', 'create a JupyterInterpreterConfig dataclass instance with superimage directory, version, and environment settings', 'configure JupyterInterpreterConfig to strip ANSI escape codes from container output', 'configure JupyterInterpreterConfig with read-only host-to-container bind mounts', 'configure JupyterInterpreterConfig with custom environment variables for the container', 'validate a JupyterInterpreterConfig instance by calling its validate method', 'review the PythonInterpreterConfig dataclass that configures symlink usage and IPython traceback formatting for the interpreter', 'create a PythonInterpreterConfig instance with use_symlinks and format_tb_ipython settings for interpreter configuration', 'validate a PythonInterpreterConfig instance by calling its validate method to check configuration correctness']
```

Usage

```
{'create_JupyterInterpreterConfig': 'create a JupyterInterpreterConfig dataclass instance with superimage directory, version, and environment settings', 'configure_JupyterInterpreterConfig_strip_ansi': 'configure JupyterInterpreterConfig to strip ANSI escape codes from container output', 'configure_JupyterInterpreterConfig_read_only_binds': 'configure JupyterInterpreterConfig with read-only host-to-container bind mounts', 'configure_JupyterInterpreterConfig_env': 'configure JupyterInterpreterConfig with custom environment variables for the container', 'validate_JupyterInterpreterConfig': 'validate a JupyterInterpreterConfig instance by calling its validate method'}
```

## File: facebookresearch_aira-dojo/src/dojo/config_dataclasses/interpreter/python.py

Prompts

```
['create an InterpreterConfig dataclass instance with a custom working_dir and timeout value', 'configure the InterpreterConfig working_dir field to point to a custom workspace agent directory', 'configure the InterpreterConfig timeout field to set a custom execution timeout for the interpreter', 'validate an InterpreterConfig instance by calling its validate method to check configuration correctness', 'inspect the InterpreterConfig dataclass fields working_dir and timeout using dataclass metadata', 'create a JupyterInterpreterConfig dataclass instance with superimage directory, version, and environment settings', 'configure JupyterInterpreterConfig to strip ANSI escape codes from container output', 'configure JupyterInterpreterConfig with read-only host-to-container bind mounts', 'configure JupyterInterpreterConfig with custom environment variables for the container', 'validate a JupyterInterpreterConfig instance by calling its validate method', 'review the PythonInterpreterConfig dataclass that configures symlink usage and IPython traceback formatting for the interpreter', 'create a PythonInterpreterConfig instance with use_symlinks and format_tb_ipython settings for interpreter configuration', 'validate a PythonInterpreterConfig instance by calling its validate method to check configuration correctness']
```

Usage

```
{'review_PythonInterpreterConfig': 'review the PythonInterpreterConfig dataclass that configures symlink usage and IPython traceback formatting for the interpreter', 'create_PythonInterpreterConfig': 'create a PythonInterpreterConfig instance with use_symlinks and format_tb_ipython settings for interpreter configuration', 'validate_PythonInterpreterConfig': 'validate a PythonInterpreterConfig instance by calling its validate method to check configuration correctness'}
```

