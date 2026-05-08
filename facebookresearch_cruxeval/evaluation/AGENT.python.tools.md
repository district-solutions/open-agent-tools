# Agent Python Tools

- repo: facebookresearch/cruxeval
- repo_uri: https://github.com/facebookresearch/cruxeval

## File: facebookresearch_cruxeval/evaluation/evaluate_generations.py

Prompts

```
['run the evaluate_generations CLI to score code generations against the CRUXEval benchmark dataset', 'run evaluate_generations to compute pass@1 and pass@5 scores for model-generated code samples', 'run evaluate_generations in input mode to evaluate generated code against input-based test cases', 'run evaluate_generations in output mode to evaluate generated code against output-based test cases', 'run evaluate_generations and dump scored results including raw generations to a JSON file', 'create a function that lists all subdirectories in a given path and returns them as a sorted list', 'run the script to print all input evaluation directories from the model_generations folder', 'run the script to print all output evaluation directories from the model_generations folder', 'review the get_all_directories function that uses os.listdir and os.path.isdir to filter directories', 'refactor get_all_directories to accept a custom path argument instead of defaulting to the current directory', 'run a Python program in a sandboxed subprocess and check if it passes within a timeout', 'create a context manager that enforces a time limit on code execution using signals', 'create a context manager that redirects stdout, stderr, and stdin to a write-only buffer', 'run a safety guard that disables destructive OS functions and subprocess calls for sandboxed execution', 'create a temporary directory context manager that changes into it for isolated file operations', 'calculate the pass@k score given total samples n, correct count c, and k', 'evaluate generated code samples against expected output using input or output mode', 'run pass@k evaluation to measure code generation success rate at k samples', 'test the evaluate_score function with generated code samples and expected outputs', 'summarize the pass@k formula used for evaluating code generation correctness']
```

Usage

```
{'run_evaluate_generations_cli': 'run the evaluate_generations CLI to score code generations against the CRUXEval benchmark dataset', 'run_evaluate_generations_pass_at_k': 'run evaluate_generations to compute pass@1 and pass@5 scores for model-generated code samples', 'run_evaluate_generations_input_mode': 'run evaluate_generations in input mode to evaluate generated code against input-based test cases', 'run_evaluate_generations_output_mode': 'run evaluate_generations in output mode to evaluate generated code against output-based test cases', 'run_evaluate_generations_dump_results': 'run evaluate_generations and dump scored results including raw generations to a JSON file'}
```

## File: facebookresearch_cruxeval/evaluation/print_evaluation_directories.py

Prompts

```
['run the evaluate_generations CLI to score code generations against the CRUXEval benchmark dataset', 'run evaluate_generations to compute pass@1 and pass@5 scores for model-generated code samples', 'run evaluate_generations in input mode to evaluate generated code against input-based test cases', 'run evaluate_generations in output mode to evaluate generated code against output-based test cases', 'run evaluate_generations and dump scored results including raw generations to a JSON file', 'create a function that lists all subdirectories in a given path and returns them as a sorted list', 'run the script to print all input evaluation directories from the model_generations folder', 'run the script to print all output evaluation directories from the model_generations folder', 'review the get_all_directories function that uses os.listdir and os.path.isdir to filter directories', 'refactor get_all_directories to accept a custom path argument instead of defaulting to the current directory', 'run a Python program in a sandboxed subprocess and check if it passes within a timeout', 'create a context manager that enforces a time limit on code execution using signals', 'create a context manager that redirects stdout, stderr, and stdin to a write-only buffer', 'run a safety guard that disables destructive OS functions and subprocess calls for sandboxed execution', 'create a temporary directory context manager that changes into it for isolated file operations', 'calculate the pass@k score given total samples n, correct count c, and k', 'evaluate generated code samples against expected output using input or output mode', 'run pass@k evaluation to measure code generation success rate at k samples', 'test the evaluate_score function with generated code samples and expected outputs', 'summarize the pass@k formula used for evaluating code generation correctness']
```

Usage

```
{'get_all_directories': 'create a function that lists all subdirectories in a given path and returns them as a sorted list', 'print_input_directories': 'run the script to print all input evaluation directories from the model_generations folder', 'print_output_directories': 'run the script to print all output evaluation directories from the model_generations folder', 'review_get_all_directories': 'review the get_all_directories function that uses os.listdir and os.path.isdir to filter directories', 'refactor_get_all_directories': 'refactor get_all_directories to accept a custom path argument instead of defaulting to the current directory'}
```

## File: facebookresearch_cruxeval/evaluation/utils_execute.py

Prompts

```
['run the evaluate_generations CLI to score code generations against the CRUXEval benchmark dataset', 'run evaluate_generations to compute pass@1 and pass@5 scores for model-generated code samples', 'run evaluate_generations in input mode to evaluate generated code against input-based test cases', 'run evaluate_generations in output mode to evaluate generated code against output-based test cases', 'run evaluate_generations and dump scored results including raw generations to a JSON file', 'create a function that lists all subdirectories in a given path and returns them as a sorted list', 'run the script to print all input evaluation directories from the model_generations folder', 'run the script to print all output evaluation directories from the model_generations folder', 'review the get_all_directories function that uses os.listdir and os.path.isdir to filter directories', 'refactor get_all_directories to accept a custom path argument instead of defaulting to the current directory', 'run a Python program in a sandboxed subprocess and check if it passes within a timeout', 'create a context manager that enforces a time limit on code execution using signals', 'create a context manager that redirects stdout, stderr, and stdin to a write-only buffer', 'run a safety guard that disables destructive OS functions and subprocess calls for sandboxed execution', 'create a temporary directory context manager that changes into it for isolated file operations', 'calculate the pass@k score given total samples n, correct count c, and k', 'evaluate generated code samples against expected output using input or output mode', 'run pass@k evaluation to measure code generation success rate at k samples', 'test the evaluate_score function with generated code samples and expected outputs', 'summarize the pass@k formula used for evaluating code generation correctness']
```

Usage

```
{'check_correctness': 'run a Python program in a sandboxed subprocess and check if it passes within a timeout', 'time_limit': 'create a context manager that enforces a time limit on code execution using signals', 'swallow_io': 'create a context manager that redirects stdout, stderr, and stdin to a write-only buffer', 'reliability_guard': 'run a safety guard that disables destructive OS functions and subprocess calls for sandboxed execution', 'create_tempdir': 'create a temporary directory context manager that changes into it for isolated file operations'}
```

## File: facebookresearch_cruxeval/evaluation/utils_general.py

Prompts

```
['run the evaluate_generations CLI to score code generations against the CRUXEval benchmark dataset', 'run evaluate_generations to compute pass@1 and pass@5 scores for model-generated code samples', 'run evaluate_generations in input mode to evaluate generated code against input-based test cases', 'run evaluate_generations in output mode to evaluate generated code against output-based test cases', 'run evaluate_generations and dump scored results including raw generations to a JSON file', 'create a function that lists all subdirectories in a given path and returns them as a sorted list', 'run the script to print all input evaluation directories from the model_generations folder', 'run the script to print all output evaluation directories from the model_generations folder', 'review the get_all_directories function that uses os.listdir and os.path.isdir to filter directories', 'refactor get_all_directories to accept a custom path argument instead of defaulting to the current directory', 'run a Python program in a sandboxed subprocess and check if it passes within a timeout', 'create a context manager that enforces a time limit on code execution using signals', 'create a context manager that redirects stdout, stderr, and stdin to a write-only buffer', 'run a safety guard that disables destructive OS functions and subprocess calls for sandboxed execution', 'create a temporary directory context manager that changes into it for isolated file operations', 'calculate the pass@k score given total samples n, correct count c, and k', 'evaluate generated code samples against expected output using input or output mode', 'run pass@k evaluation to measure code generation success rate at k samples', 'test the evaluate_score function with generated code samples and expected outputs', 'summarize the pass@k formula used for evaluating code generation correctness']
```

Usage

```
{'calculate_pass_at_k': 'calculate the pass@k score given total samples n, correct count c, and k', 'evaluate_generations_score': 'evaluate generated code samples against expected output using input or output mode', 'run_pass_at_k_evaluation': 'run pass@k evaluation to measure code generation success rate at k samples', 'test_evaluate_score': 'test the evaluate_score function with generated code samples and expected outputs', 'summarize_pass_at_k_formula': 'summarize the pass@k formula used for evaluating code generation correctness'}
```

