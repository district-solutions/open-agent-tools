# Agent Python Tools

- repo: facebookresearch/aira-dojo
- repo_uri: https://github.com/facebookresearch/aira-dojo

## File: facebookresearch_aira-dojo/src/dojo/core/interpreters/jupyter/apptainer_jupyter_server.py

Prompts

```
['start a Jupyter kernel gateway server inside an Apptainer container with read-only binds and overlays', 'stop the running Apptainer Jupyter server by sending SIGTERM then SIGKILL if needed', 'get the JupyterConnectionInfo with host, port, and auth token for the running server', 'get a JupyterClient instance connected to the Apptainer Jupyter kernel gateway server', 'use ApptainerJupyterServer as a context manager to auto-start and auto-stop the server', 'create a CodeBlock with code and language fields for execution', 'create a CodeResult with exit_code and output from code execution', 'create an IPythonCodeResult with exit_code, output, and output_files list', 'create a JupyterConnectionInfo dataclass with host, use_https, port, and token', 'implement the CodeExecutor protocol with execute_code_blocks and restart methods', 'start a new Jupyter kernel by name and return its kernel ID', 'execute Python code in a Jupyter kernel and collect text output and data items', 'list all running Jupyter kernels on the gateway server', 'interrupt a running Jupyter kernel by its kernel ID', 'use JupyterKernelClient as a context manager to auto-connect and auto-close the WebSocket', 'create a JupyterCodeExecutor instance with a Jupyter server connection, kernel name, and timeout settings', 'execute Python code statefully in a Jupyter kernel and return the execution result with output', 'fetch a file from the Jupyter kernel filesystem by executing base64 encoding code and returning bytes', 'restart the Jupyter kernel to reset the execution state and get a fresh kernel client', 'stop the Jupyter kernel client and delete the kernel to clean up resources', 'run Python code in a Jupyter kernel inside an Apptainer container and return execution results', "fetch a file from the Jupyter container's working directory and write it to the local filesystem", 'create a JupyterInterpreter instance with a config to execute code in a containerized Jupyter kernel', 'cleanup and stop the active Jupyter code executor session to free resources', 'run Python code via JupyterInterpreterFactory that lazily creates and manages interpreter instances']
```

Usage

```
{'start_apptainer_jupyter_server': 'start a Jupyter kernel gateway server inside an Apptainer container with read-only binds and overlays', 'stop_apptainer_jupyter_server': 'stop the running Apptainer Jupyter server by sending SIGTERM then SIGKILL if needed', 'get_connection_info': 'get the JupyterConnectionInfo with host, port, and auth token for the running server', 'get_jupyter_client': 'get a JupyterClient instance connected to the Apptainer Jupyter kernel gateway server', 'use_context_manager': 'use ApptainerJupyterServer as a context manager to auto-start and auto-stop the server'}
```

## File: facebookresearch_aira-dojo/src/dojo/core/interpreters/jupyter/base.py

Prompts

```
['start a Jupyter kernel gateway server inside an Apptainer container with read-only binds and overlays', 'stop the running Apptainer Jupyter server by sending SIGTERM then SIGKILL if needed', 'get the JupyterConnectionInfo with host, port, and auth token for the running server', 'get a JupyterClient instance connected to the Apptainer Jupyter kernel gateway server', 'use ApptainerJupyterServer as a context manager to auto-start and auto-stop the server', 'create a CodeBlock with code and language fields for execution', 'create a CodeResult with exit_code and output from code execution', 'create an IPythonCodeResult with exit_code, output, and output_files list', 'create a JupyterConnectionInfo dataclass with host, use_https, port, and token', 'implement the CodeExecutor protocol with execute_code_blocks and restart methods', 'start a new Jupyter kernel by name and return its kernel ID', 'execute Python code in a Jupyter kernel and collect text output and data items', 'list all running Jupyter kernels on the gateway server', 'interrupt a running Jupyter kernel by its kernel ID', 'use JupyterKernelClient as a context manager to auto-connect and auto-close the WebSocket', 'create a JupyterCodeExecutor instance with a Jupyter server connection, kernel name, and timeout settings', 'execute Python code statefully in a Jupyter kernel and return the execution result with output', 'fetch a file from the Jupyter kernel filesystem by executing base64 encoding code and returning bytes', 'restart the Jupyter kernel to reset the execution state and get a fresh kernel client', 'stop the Jupyter kernel client and delete the kernel to clean up resources', 'run Python code in a Jupyter kernel inside an Apptainer container and return execution results', "fetch a file from the Jupyter container's working directory and write it to the local filesystem", 'create a JupyterInterpreter instance with a config to execute code in a containerized Jupyter kernel', 'cleanup and stop the active Jupyter code executor session to free resources', 'run Python code via JupyterInterpreterFactory that lazily creates and manages interpreter instances']
```

Usage

```
{'create_CodeBlock': 'create a CodeBlock with code and language fields for execution', 'create_CodeResult': 'create a CodeResult with exit_code and output from code execution', 'create_IPythonCodeResult': 'create an IPythonCodeResult with exit_code, output, and output_files list', 'create_JupyterConnectionInfo': 'create a JupyterConnectionInfo dataclass with host, use_https, port, and token', 'implement_CodeExecutor_protocol': 'implement the CodeExecutor protocol with execute_code_blocks and restart methods'}
```

## File: facebookresearch_aira-dojo/src/dojo/core/interpreters/jupyter/jupyter_client.py

Prompts

```
['start a Jupyter kernel gateway server inside an Apptainer container with read-only binds and overlays', 'stop the running Apptainer Jupyter server by sending SIGTERM then SIGKILL if needed', 'get the JupyterConnectionInfo with host, port, and auth token for the running server', 'get a JupyterClient instance connected to the Apptainer Jupyter kernel gateway server', 'use ApptainerJupyterServer as a context manager to auto-start and auto-stop the server', 'create a CodeBlock with code and language fields for execution', 'create a CodeResult with exit_code and output from code execution', 'create an IPythonCodeResult with exit_code, output, and output_files list', 'create a JupyterConnectionInfo dataclass with host, use_https, port, and token', 'implement the CodeExecutor protocol with execute_code_blocks and restart methods', 'start a new Jupyter kernel by name and return its kernel ID', 'execute Python code in a Jupyter kernel and collect text output and data items', 'list all running Jupyter kernels on the gateway server', 'interrupt a running Jupyter kernel by its kernel ID', 'use JupyterKernelClient as a context manager to auto-connect and auto-close the WebSocket', 'create a JupyterCodeExecutor instance with a Jupyter server connection, kernel name, and timeout settings', 'execute Python code statefully in a Jupyter kernel and return the execution result with output', 'fetch a file from the Jupyter kernel filesystem by executing base64 encoding code and returning bytes', 'restart the Jupyter kernel to reset the execution state and get a fresh kernel client', 'stop the Jupyter kernel client and delete the kernel to clean up resources', 'run Python code in a Jupyter kernel inside an Apptainer container and return execution results', "fetch a file from the Jupyter container's working directory and write it to the local filesystem", 'create a JupyterInterpreter instance with a config to execute code in a containerized Jupyter kernel', 'cleanup and stop the active Jupyter code executor session to free resources', 'run Python code via JupyterInterpreterFactory that lazily creates and manages interpreter instances']
```

Usage

```
{'start_kernel': 'start a new Jupyter kernel by name and return its kernel ID', 'execute_code': 'execute Python code in a Jupyter kernel and collect text output and data items', 'list_kernels': 'list all running Jupyter kernels on the gateway server', 'interrupt_kernel': 'interrupt a running Jupyter kernel by its kernel ID', 'use_kernel_context_manager': 'use JupyterKernelClient as a context manager to auto-connect and auto-close the WebSocket'}
```

## File: facebookresearch_aira-dojo/src/dojo/core/interpreters/jupyter/jupyter_code_executor.py

Prompts

```
['start a Jupyter kernel gateway server inside an Apptainer container with read-only binds and overlays', 'stop the running Apptainer Jupyter server by sending SIGTERM then SIGKILL if needed', 'get the JupyterConnectionInfo with host, port, and auth token for the running server', 'get a JupyterClient instance connected to the Apptainer Jupyter kernel gateway server', 'use ApptainerJupyterServer as a context manager to auto-start and auto-stop the server', 'create a CodeBlock with code and language fields for execution', 'create a CodeResult with exit_code and output from code execution', 'create an IPythonCodeResult with exit_code, output, and output_files list', 'create a JupyterConnectionInfo dataclass with host, use_https, port, and token', 'implement the CodeExecutor protocol with execute_code_blocks and restart methods', 'start a new Jupyter kernel by name and return its kernel ID', 'execute Python code in a Jupyter kernel and collect text output and data items', 'list all running Jupyter kernels on the gateway server', 'interrupt a running Jupyter kernel by its kernel ID', 'use JupyterKernelClient as a context manager to auto-connect and auto-close the WebSocket', 'create a JupyterCodeExecutor instance with a Jupyter server connection, kernel name, and timeout settings', 'execute Python code statefully in a Jupyter kernel and return the execution result with output', 'fetch a file from the Jupyter kernel filesystem by executing base64 encoding code and returning bytes', 'restart the Jupyter kernel to reset the execution state and get a fresh kernel client', 'stop the Jupyter kernel client and delete the kernel to clean up resources', 'run Python code in a Jupyter kernel inside an Apptainer container and return execution results', "fetch a file from the Jupyter container's working directory and write it to the local filesystem", 'create a JupyterInterpreter instance with a config to execute code in a containerized Jupyter kernel', 'cleanup and stop the active Jupyter code executor session to free resources', 'run Python code via JupyterInterpreterFactory that lazily creates and manages interpreter instances']
```

Usage

```
{'create_jupyter_code_executor': 'create a JupyterCodeExecutor instance with a Jupyter server connection, kernel name, and timeout settings', 'execute_code_in_jupyter_kernel': 'execute Python code statefully in a Jupyter kernel and return the execution result with output', 'fetch_file_from_jupyter_kernel': 'fetch a file from the Jupyter kernel filesystem by executing base64 encoding code and returning bytes', 'restart_jupyter_kernel': 'restart the Jupyter kernel to reset the execution state and get a fresh kernel client', 'stop_jupyter_kernel': 'stop the Jupyter kernel client and delete the kernel to clean up resources'}
```

## File: facebookresearch_aira-dojo/src/dojo/core/interpreters/jupyter/jupyter_interpreter.py

Prompts

```
['start a Jupyter kernel gateway server inside an Apptainer container with read-only binds and overlays', 'stop the running Apptainer Jupyter server by sending SIGTERM then SIGKILL if needed', 'get the JupyterConnectionInfo with host, port, and auth token for the running server', 'get a JupyterClient instance connected to the Apptainer Jupyter kernel gateway server', 'use ApptainerJupyterServer as a context manager to auto-start and auto-stop the server', 'create a CodeBlock with code and language fields for execution', 'create a CodeResult with exit_code and output from code execution', 'create an IPythonCodeResult with exit_code, output, and output_files list', 'create a JupyterConnectionInfo dataclass with host, use_https, port, and token', 'implement the CodeExecutor protocol with execute_code_blocks and restart methods', 'start a new Jupyter kernel by name and return its kernel ID', 'execute Python code in a Jupyter kernel and collect text output and data items', 'list all running Jupyter kernels on the gateway server', 'interrupt a running Jupyter kernel by its kernel ID', 'use JupyterKernelClient as a context manager to auto-connect and auto-close the WebSocket', 'create a JupyterCodeExecutor instance with a Jupyter server connection, kernel name, and timeout settings', 'execute Python code statefully in a Jupyter kernel and return the execution result with output', 'fetch a file from the Jupyter kernel filesystem by executing base64 encoding code and returning bytes', 'restart the Jupyter kernel to reset the execution state and get a fresh kernel client', 'stop the Jupyter kernel client and delete the kernel to clean up resources', 'run Python code in a Jupyter kernel inside an Apptainer container and return execution results', "fetch a file from the Jupyter container's working directory and write it to the local filesystem", 'create a JupyterInterpreter instance with a config to execute code in a containerized Jupyter kernel', 'cleanup and stop the active Jupyter code executor session to free resources', 'run Python code via JupyterInterpreterFactory that lazily creates and manages interpreter instances']
```

Usage

```
{'run_code_in_jupyter': 'run Python code in a Jupyter kernel inside an Apptainer container and return execution results', 'fetch_file_from_container': "fetch a file from the Jupyter container's working directory and write it to the local filesystem", 'create_jupyter_interpreter': 'create a JupyterInterpreter instance with a config to execute code in a containerized Jupyter kernel', 'cleanup_jupyter_session': 'cleanup and stop the active Jupyter code executor session to free resources', 'run_code_with_factory': 'run Python code via JupyterInterpreterFactory that lazily creates and manages interpreter instances'}
```

