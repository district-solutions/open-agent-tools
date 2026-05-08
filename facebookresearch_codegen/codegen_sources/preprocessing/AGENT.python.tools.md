# Agent Python Tools

- repo: facebookresearch/codegen
- repo_uri: https://github.com/facebookresearch/codegen

## File: facebookresearch_codegen/codegen_sources/preprocessing/preprocess.py

Prompts

```
['run the code preprocessing pipeline on a source code folder with BPE tokenization and binarization', 'preprocess a monolingual functions dataset by extracting, tokenizing, splitting, and binarizing source code', 'apply fastBPE tokenization to source code files in multiple programming languages like Python, Java, and C++', 'train BPE codes on source code data with a configurable number of merge operations', 'binarize tokenized source code data and create vocabulary files for XLM model training', "use the timeout decorator to limit a function's execution to a specified number of seconds", 'raise a TimeoutError exception when a decorated function exceeds its allotted execution time', 'nest multiple timeout decorators on the same function to support layered timeout constraints', 'customize the timeout error message by passing a custom error_message string to the decorator', "review the timeout decorator's SIGALRM signal handler logic for nested timer preservation and restoration", 'parse a command line boolean flag string like true false on off or 1 0', 'check if a given file path exists and has a non-zero file size', 'count the number of lines in a file using the wc command', 'shuffle multiple parallel files in the same random order and write shuffled outputs', 'split a comma-separated argument string respecting parentheses nesting and quoted strings']
```

Usage

```
{'run_preprocessing_pipeline': 'run the code preprocessing pipeline on a source code folder with BPE tokenization and binarization', 'preprocess_dataset_for_training': 'preprocess a monolingual functions dataset by extracting, tokenizing, splitting, and binarizing source code', 'apply_fastbpe_tokenization': 'apply fastBPE tokenization to source code files in multiple programming languages like Python, Java, and C++', 'train_bpe_codes': 'train BPE codes on source code data with a configurable number of merge operations', 'binarize_dataset': 'binarize tokenized source code data and create vocabulary files for XLM model training'}
```

## File: facebookresearch_codegen/codegen_sources/preprocessing/timeout.py

Prompts

```
['run the code preprocessing pipeline on a source code folder with BPE tokenization and binarization', 'preprocess a monolingual functions dataset by extracting, tokenizing, splitting, and binarizing source code', 'apply fastBPE tokenization to source code files in multiple programming languages like Python, Java, and C++', 'train BPE codes on source code data with a configurable number of merge operations', 'binarize tokenized source code data and create vocabulary files for XLM model training', "use the timeout decorator to limit a function's execution to a specified number of seconds", 'raise a TimeoutError exception when a decorated function exceeds its allotted execution time', 'nest multiple timeout decorators on the same function to support layered timeout constraints', 'customize the timeout error message by passing a custom error_message string to the decorator', "review the timeout decorator's SIGALRM signal handler logic for nested timer preservation and restoration", 'parse a command line boolean flag string like true false on off or 1 0', 'check if a given file path exists and has a non-zero file size', 'count the number of lines in a file using the wc command', 'shuffle multiple parallel files in the same random order and write shuffled outputs', 'split a comma-separated argument string respecting parentheses nesting and quoted strings']
```

Usage

```
{'use_timeout_decorator': "use the timeout decorator to limit a function's execution to a specified number of seconds", 'raise_timeout_error': 'raise a TimeoutError exception when a decorated function exceeds its allotted execution time', 'nest_timeout_decorators': 'nest multiple timeout decorators on the same function to support layered timeout constraints', 'customize_timeout_message': 'customize the timeout error message by passing a custom error_message string to the decorator', 'review_timeout_handler': "review the timeout decorator's SIGALRM signal handler logic for nested timer preservation and restoration"}
```

## File: facebookresearch_codegen/codegen_sources/preprocessing/utils.py

Prompts

```
['run the code preprocessing pipeline on a source code folder with BPE tokenization and binarization', 'preprocess a monolingual functions dataset by extracting, tokenizing, splitting, and binarizing source code', 'apply fastBPE tokenization to source code files in multiple programming languages like Python, Java, and C++', 'train BPE codes on source code data with a configurable number of merge operations', 'binarize tokenized source code data and create vocabulary files for XLM model training', "use the timeout decorator to limit a function's execution to a specified number of seconds", 'raise a TimeoutError exception when a decorated function exceeds its allotted execution time', 'nest multiple timeout decorators on the same function to support layered timeout constraints', 'customize the timeout error message by passing a custom error_message string to the decorator', "review the timeout decorator's SIGALRM signal handler logic for nested timer preservation and restoration", 'parse a command line boolean flag string like true false on off or 1 0', 'check if a given file path exists and has a non-zero file size', 'count the number of lines in a file using the wc command', 'shuffle multiple parallel files in the same random order and write shuffled outputs', 'split a comma-separated argument string respecting parentheses nesting and quoted strings']
```

Usage

```
{'parse_bool_flag': 'parse a command line boolean flag string like true false on off or 1 0', 'validate_file': 'check if a given file path exists and has a non-zero file size', 'count_lines': 'count the number of lines in a file using the wc command', 'shuffle_parallel_files': 'shuffle multiple parallel files in the same random order and write shuffled outputs', 'split_arguments': 'split a comma-separated argument string respecting parentheses nesting and quoted strings'}
```

