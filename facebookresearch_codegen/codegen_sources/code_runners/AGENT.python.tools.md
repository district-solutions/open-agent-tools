# Agent Python Tools

- repo: facebookresearch/codegen
- repo_uri: https://github.com/facebookresearch/codegen

## File: facebookresearch_codegen/codegen_sources/code_runners/code_runner.py

Prompts

```
['run python code in a sandboxed environment with firejail and memory limits', 'run a shell command with optional script input and environment preparation using timeout', 'create a unique temporary folder for writing and executing code files', 'write source code to a file with a random filename and language-specific extension', 'clean firejail shutdown messages from subprocess output strings', 'run a Python code string using PythonCodeRunner and capture stdout, stderr, and exit code', 'run a Python script with stdin input via PythonCodeRunner and return the output tuple', 'initialize the PythonCodeRunner environment to add the current Python executable to PATH', 'create a PythonCodeRunner instance with a custom timeout, tmp folder, and firejail sandboxing', 'review the PythonCodeRunner class and its run method for executing Python code in a sandboxed temp folder', 'compile a C++ source file to an executable using g++ with gtest and pthread libraries', 'compile a Java source file using javac with a configurable compilation timeout', 'compile a Rust source file to an executable using rustc with timeout handling', 'compile a Go source file to an executable with optional goimports formatting', 'clean useless bash version warnings from compilation error output strings']
```

Usage

```
{'run_code_with_sandbox': 'run python code in a sandboxed environment with firejail and memory limits', 'run_command_with_timeout': 'run a shell command with optional script input and environment preparation using timeout', 'create_temp_folder': 'create a unique temporary folder for writing and executing code files', 'write_code_file': 'write source code to a file with a random filename and language-specific extension', 'clean_firejail_output': 'clean firejail shutdown messages from subprocess output strings'}
```

## File: facebookresearch_codegen/codegen_sources/code_runners/python_code_runner.py

Prompts

```
['run python code in a sandboxed environment with firejail and memory limits', 'run a shell command with optional script input and environment preparation using timeout', 'create a unique temporary folder for writing and executing code files', 'write source code to a file with a random filename and language-specific extension', 'clean firejail shutdown messages from subprocess output strings', 'run a Python code string using PythonCodeRunner and capture stdout, stderr, and exit code', 'run a Python script with stdin input via PythonCodeRunner and return the output tuple', 'initialize the PythonCodeRunner environment to add the current Python executable to PATH', 'create a PythonCodeRunner instance with a custom timeout, tmp folder, and firejail sandboxing', 'review the PythonCodeRunner class and its run method for executing Python code in a sandboxed temp folder', 'compile a C++ source file to an executable using g++ with gtest and pthread libraries', 'compile a Java source file using javac with a configurable compilation timeout', 'compile a Rust source file to an executable using rustc with timeout handling', 'compile a Go source file to an executable with optional goimports formatting', 'clean useless bash version warnings from compilation error output strings']
```

Usage

```
{'run_python_code': 'run a Python code string using PythonCodeRunner and capture stdout, stderr, and exit code', 'run_python_code_with_input': 'run a Python script with stdin input via PythonCodeRunner and return the output tuple', 'init_python_env': 'initialize the PythonCodeRunner environment to add the current Python executable to PATH', 'create_python_code_runner': 'create a PythonCodeRunner instance with a custom timeout, tmp folder, and firejail sandboxing', 'review_python_code_runner': 'review the PythonCodeRunner class and its run method for executing Python code in a sandboxed temp folder'}
```

## File: facebookresearch_codegen/codegen_sources/code_runners/utils.py

Prompts

```
['run python code in a sandboxed environment with firejail and memory limits', 'run a shell command with optional script input and environment preparation using timeout', 'create a unique temporary folder for writing and executing code files', 'write source code to a file with a random filename and language-specific extension', 'clean firejail shutdown messages from subprocess output strings', 'run a Python code string using PythonCodeRunner and capture stdout, stderr, and exit code', 'run a Python script with stdin input via PythonCodeRunner and return the output tuple', 'initialize the PythonCodeRunner environment to add the current Python executable to PATH', 'create a PythonCodeRunner instance with a custom timeout, tmp folder, and firejail sandboxing', 'review the PythonCodeRunner class and its run method for executing Python code in a sandboxed temp folder', 'compile a C++ source file to an executable using g++ with gtest and pthread libraries', 'compile a Java source file using javac with a configurable compilation timeout', 'compile a Rust source file to an executable using rustc with timeout handling', 'compile a Go source file to an executable with optional goimports formatting', 'clean useless bash version warnings from compilation error output strings']
```

Usage

```
{'compile_cpp_code': 'compile a C++ source file to an executable using g++ with gtest and pthread libraries', 'compile_java_code': 'compile a Java source file using javac with a configurable compilation timeout', 'compile_rust_code': 'compile a Rust source file to an executable using rustc with timeout handling', 'compile_go_code': 'compile a Go source file to an executable with optional goimports formatting', 'clean_error_output': 'clean useless bash version warnings from compilation error output strings'}
```

