# Agent Python Tools

- repo: facebookresearch/codegen
- repo_uri: https://github.com/facebookresearch/codegen

## File: facebookresearch_codegen/codegen_sources/code_runners/test_runners/input_output_runners/input_output_evaluator.py

Prompts

```
['run a program against input/output pairs and check if outputs match expected results', 'run a compiled executable with a given input value and capture stdout, stderr, and return code', 'evaluate program output by comparing actual stdout against expected output string', 'review the InputOutputEvaluator base class that compiles, runs, and evaluates generated code programs', 'refactor the abstract _process method in a subclass to preprocess source code before writing to file', 'run Java programs against input/output test cases and compare actual output to expected output', 'compile a Java source file to a .class bytecode file with a configurable compilation timeout', 'evaluate Java program output by running it with test inputs and checking results for success or failure', 'process and detokenize Java source code using the JavaProcessor for evaluation', 'initialize the environment by prepending the Java binary path to the system PATH variable']
```

Usage

```
{'run_check_outputs': 'run a program against input/output pairs and check if outputs match expected results', 'run_program_with_input': 'run a compiled executable with a given input value and capture stdout, stderr, and return code', 'eval_output_comparison': 'evaluate program output by comparing actual stdout against expected output string', 'review_InputOutputEvaluator_class': 'review the InputOutputEvaluator base class that compiles, runs, and evaluates generated code programs', 'refactor_process_method': 'refactor the abstract _process method in a subclass to preprocess source code before writing to file'}
```

## File: facebookresearch_codegen/codegen_sources/code_runners/test_runners/input_output_runners/java_input_output_evaluator.py

Prompts

```
['run a program against input/output pairs and check if outputs match expected results', 'run a compiled executable with a given input value and capture stdout, stderr, and return code', 'evaluate program output by comparing actual stdout against expected output string', 'review the InputOutputEvaluator base class that compiles, runs, and evaluates generated code programs', 'refactor the abstract _process method in a subclass to preprocess source code before writing to file', 'run Java programs against input/output test cases and compare actual output to expected output', 'compile a Java source file to a .class bytecode file with a configurable compilation timeout', 'evaluate Java program output by running it with test inputs and checking results for success or failure', 'process and detokenize Java source code using the JavaProcessor for evaluation', 'initialize the environment by prepending the Java binary path to the system PATH variable']
```

Usage

```
{'run_java_io_tests': 'run Java programs against input/output test cases and compare actual output to expected output', 'compile_java_program': 'compile a Java source file to a .class bytecode file with a configurable compilation timeout', 'evaluate_java_output': 'evaluate Java program output by running it with test inputs and checking results for success or failure', 'process_java_code': 'process and detokenize Java source code using the JavaProcessor for evaluation', 'init_java_env': 'initialize the environment by prepending the Java binary path to the system PATH variable'}
```

