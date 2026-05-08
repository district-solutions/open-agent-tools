# Agent Python Tools

- repo: facebookresearch/cwm
- repo_uri: https://github.com/facebookresearch/cwm

## File: facebookresearch_cwm/cwm/exec/code/eval/runners/python_lcbcodegen.py

Prompts

```
['run the grade_call function to evaluate a Python function against inputs and expected outputs', "run the grade_stdio function to evaluate a Python script's stdout against expected output", 'run the compile_code function to compile Python code into a RuntimeModule with timeout', "run the clean_if_name function to remove if __name__ == '__main__' guards from Python code", 'run the make_function function to wrap Python code into a callable wrapped_function', 'execute compiled Python source code in a sandboxed environment with __name__ set to __main__', 'strip internal python_tool.py frames from a traceback string to show only user code', 'replace built-in exit and quit functions to raise EarlyReturnException instead of terminating', 'handle early returns in user code by catching this custom exception during execution', 'run the sandboxed Python code executor via multiprocessing connections to receive source and return stdout stderr or errors']
```

Usage

```
{'run_grade_call': 'run the grade_call function to evaluate a Python function against inputs and expected outputs', 'run_grade_stdio': "run the grade_stdio function to evaluate a Python script's stdout against expected output", 'run_compile_code': 'run the compile_code function to compile Python code into a RuntimeModule with timeout', 'run_clean_if_name': "run the clean_if_name function to remove if __name__ == '__main__' guards from Python code", 'run_make_function': 'run the make_function function to wrap Python code into a callable wrapped_function'}
```

## File: facebookresearch_cwm/cwm/exec/code/eval/runners/python_tool.py

Prompts

```
['run the grade_call function to evaluate a Python function against inputs and expected outputs', "run the grade_stdio function to evaluate a Python script's stdout against expected output", 'run the compile_code function to compile Python code into a RuntimeModule with timeout', "run the clean_if_name function to remove if __name__ == '__main__' guards from Python code", 'run the make_function function to wrap Python code into a callable wrapped_function', 'execute compiled Python source code in a sandboxed environment with __name__ set to __main__', 'strip internal python_tool.py frames from a traceback string to show only user code', 'replace built-in exit and quit functions to raise EarlyReturnException instead of terminating', 'handle early returns in user code by catching this custom exception during execution', 'run the sandboxed Python code executor via multiprocessing connections to receive source and return stdout stderr or errors']
```

Usage

```
{'execute_code': 'execute compiled Python source code in a sandboxed environment with __name__ set to __main__', 'format_tb': 'strip internal python_tool.py frames from a traceback string to show only user code', 'custom_exit': 'replace built-in exit and quit functions to raise EarlyReturnException instead of terminating', 'EarlyReturnException': 'handle early returns in user code by catching this custom exception during execution', 'main': 'run the sandboxed Python code executor via multiprocessing connections to receive source and return stdout stderr or errors'}
```

