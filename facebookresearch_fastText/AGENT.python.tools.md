# Agent Python Tools

- repo: facebookresearch/fastText
- repo_uri: https://github.com/facebookresearch/fastText.git

## File: facebookresearch_fastText/download_model.py

Prompts

```
['run the download_model script to download pre-trained English word vectors from fastText', 'run the download_model script with language fr to download French pre-trained vectors', 'run the download_model script with --overwrite to replace existing model files', 'review the command_download function that wraps fasttext.util.download_model for downloading vectors', 'test the main function that parses language and overwrite arguments via argparse', 'run eval.py with --model and --data flags to evaluate word vector similarity on a benchmark dataset', 'run eval.py to compute Spearman correlation between predicted and gold word pair similarity scores', 'run the similarity function to compute cosine similarity between two numpy vector arrays', 'review the compat_splitting function that decodes UTF-8 bytes and splits a line into tokens', 'review the similarity function that calculates cosine similarity between two vectors using numpy', 'run the CLI tool to reduce a fastText model dimension from 300 to 100 using PCA', 'run the CLI tool to reduce a fastText model dimension and overwrite the existing output file', 'call command_reduce to load a fastText model, reduce its dimension via PCA, and save it', 'call guess_target_name to generate a new model filename with the target dimension substituted', 'review the command_reduce function to understand how it handles overwrite, strict, and ignore modes', 'run the fastText unit tests by calling runtests.py with the --unit-tests flag', 'run the fastText integration tests by calling runtests.py with --integration-tests and --data-dir', 'run fastText tests with a custom verbosity level using the --verbose flag', 'call the run_tests function with a unittest TestLoader suite to execute tests', 'generate fastText unit test cases using gen_unit_tests with an optional verbose parameter', 'build the fasttext C++ extension module using setuptools and pybind11 bindings', 'review the BuildExt class that adds platform-specific compiler options for unix and msvc', 'test the has_flag function to check if a compiler supports specific flags', 'summarize the get_pybind_include class that resolves pybind11 include paths and auto-installs if missing', 'refactor the cpp_flag function to support additional C++ standards beyond c++17']
```

Usage

```
{'run_download_model_en': 'run the download_model script to download pre-trained English word vectors from fastText', 'run_download_model_fr': 'run the download_model script with language fr to download French pre-trained vectors', 'run_download_model_overwrite': 'run the download_model script with --overwrite to replace existing model files', 'review_command_download': 'review the command_download function that wraps fasttext.util.download_model for downloading vectors', 'test_main': 'test the main function that parses language and overwrite arguments via argparse'}
```

## File: facebookresearch_fastText/eval.py

Prompts

```
['run the download_model script to download pre-trained English word vectors from fastText', 'run the download_model script with language fr to download French pre-trained vectors', 'run the download_model script with --overwrite to replace existing model files', 'review the command_download function that wraps fasttext.util.download_model for downloading vectors', 'test the main function that parses language and overwrite arguments via argparse', 'run eval.py with --model and --data flags to evaluate word vector similarity on a benchmark dataset', 'run eval.py to compute Spearman correlation between predicted and gold word pair similarity scores', 'run the similarity function to compute cosine similarity between two numpy vector arrays', 'review the compat_splitting function that decodes UTF-8 bytes and splits a line into tokens', 'review the similarity function that calculates cosine similarity between two vectors using numpy', 'run the CLI tool to reduce a fastText model dimension from 300 to 100 using PCA', 'run the CLI tool to reduce a fastText model dimension and overwrite the existing output file', 'call command_reduce to load a fastText model, reduce its dimension via PCA, and save it', 'call guess_target_name to generate a new model filename with the target dimension substituted', 'review the command_reduce function to understand how it handles overwrite, strict, and ignore modes', 'run the fastText unit tests by calling runtests.py with the --unit-tests flag', 'run the fastText integration tests by calling runtests.py with --integration-tests and --data-dir', 'run fastText tests with a custom verbosity level using the --verbose flag', 'call the run_tests function with a unittest TestLoader suite to execute tests', 'generate fastText unit test cases using gen_unit_tests with an optional verbose parameter', 'build the fasttext C++ extension module using setuptools and pybind11 bindings', 'review the BuildExt class that adds platform-specific compiler options for unix and msvc', 'test the has_flag function to check if a compiler supports specific flags', 'summarize the get_pybind_include class that resolves pybind11 include paths and auto-installs if missing', 'refactor the cpp_flag function to support additional C++ standards beyond c++17']
```

Usage

```
{'run_eval_word_vectors': 'run eval.py with --model and --data flags to evaluate word vector similarity on a benchmark dataset', 'run_spearman_correlation': 'run eval.py to compute Spearman correlation between predicted and gold word pair similarity scores', 'run_cosine_similarity': 'run the similarity function to compute cosine similarity between two numpy vector arrays', 'review_compat_splitting': 'review the compat_splitting function that decodes UTF-8 bytes and splits a line into tokens', 'review_similarity': 'review the similarity function that calculates cosine similarity between two vectors using numpy'}
```

## File: facebookresearch_fastText/reduce_model.py

Prompts

```
['run the download_model script to download pre-trained English word vectors from fastText', 'run the download_model script with language fr to download French pre-trained vectors', 'run the download_model script with --overwrite to replace existing model files', 'review the command_download function that wraps fasttext.util.download_model for downloading vectors', 'test the main function that parses language and overwrite arguments via argparse', 'run eval.py with --model and --data flags to evaluate word vector similarity on a benchmark dataset', 'run eval.py to compute Spearman correlation between predicted and gold word pair similarity scores', 'run the similarity function to compute cosine similarity between two numpy vector arrays', 'review the compat_splitting function that decodes UTF-8 bytes and splits a line into tokens', 'review the similarity function that calculates cosine similarity between two vectors using numpy', 'run the CLI tool to reduce a fastText model dimension from 300 to 100 using PCA', 'run the CLI tool to reduce a fastText model dimension and overwrite the existing output file', 'call command_reduce to load a fastText model, reduce its dimension via PCA, and save it', 'call guess_target_name to generate a new model filename with the target dimension substituted', 'review the command_reduce function to understand how it handles overwrite, strict, and ignore modes', 'run the fastText unit tests by calling runtests.py with the --unit-tests flag', 'run the fastText integration tests by calling runtests.py with --integration-tests and --data-dir', 'run fastText tests with a custom verbosity level using the --verbose flag', 'call the run_tests function with a unittest TestLoader suite to execute tests', 'generate fastText unit test cases using gen_unit_tests with an optional verbose parameter', 'build the fasttext C++ extension module using setuptools and pybind11 bindings', 'review the BuildExt class that adds platform-specific compiler options for unix and msvc', 'test the has_flag function to check if a compiler supports specific flags', 'summarize the get_pybind_include class that resolves pybind11 include paths and auto-installs if missing', 'refactor the cpp_flag function to support additional C++ standards beyond c++17']
```

Usage

```
{'run_reduce_model': 'run the CLI tool to reduce a fastText model dimension from 300 to 100 using PCA', 'run_reduce_model_overwrite': 'run the CLI tool to reduce a fastText model dimension and overwrite the existing output file', 'command_reduce_function': 'call command_reduce to load a fastText model, reduce its dimension via PCA, and save it', 'guess_target_name_function': 'call guess_target_name to generate a new model filename with the target dimension substituted', 'review_command_reduce': 'review the command_reduce function to understand how it handles overwrite, strict, and ignore modes'}
```

## File: facebookresearch_fastText/runtests.py

Prompts

```
['run the download_model script to download pre-trained English word vectors from fastText', 'run the download_model script with language fr to download French pre-trained vectors', 'run the download_model script with --overwrite to replace existing model files', 'review the command_download function that wraps fasttext.util.download_model for downloading vectors', 'test the main function that parses language and overwrite arguments via argparse', 'run eval.py with --model and --data flags to evaluate word vector similarity on a benchmark dataset', 'run eval.py to compute Spearman correlation between predicted and gold word pair similarity scores', 'run the similarity function to compute cosine similarity between two numpy vector arrays', 'review the compat_splitting function that decodes UTF-8 bytes and splits a line into tokens', 'review the similarity function that calculates cosine similarity between two vectors using numpy', 'run the CLI tool to reduce a fastText model dimension from 300 to 100 using PCA', 'run the CLI tool to reduce a fastText model dimension and overwrite the existing output file', 'call command_reduce to load a fastText model, reduce its dimension via PCA, and save it', 'call guess_target_name to generate a new model filename with the target dimension substituted', 'review the command_reduce function to understand how it handles overwrite, strict, and ignore modes', 'run the fastText unit tests by calling runtests.py with the --unit-tests flag', 'run the fastText integration tests by calling runtests.py with --integration-tests and --data-dir', 'run fastText tests with a custom verbosity level using the --verbose flag', 'call the run_tests function with a unittest TestLoader suite to execute tests', 'generate fastText unit test cases using gen_unit_tests with an optional verbose parameter', 'build the fasttext C++ extension module using setuptools and pybind11 bindings', 'review the BuildExt class that adds platform-specific compiler options for unix and msvc', 'test the has_flag function to check if a compiler supports specific flags', 'summarize the get_pybind_include class that resolves pybind11 include paths and auto-installs if missing', 'refactor the cpp_flag function to support additional C++ standards beyond c++17']
```

Usage

```
{'run_unit_tests': 'run the fastText unit tests by calling runtests.py with the --unit-tests flag', 'run_integration_tests': 'run the fastText integration tests by calling runtests.py with --integration-tests and --data-dir', 'run_tests_with_verbosity': 'run fastText tests with a custom verbosity level using the --verbose flag', 'call_run_tests_programmatically': 'call the run_tests function with a unittest TestLoader suite to execute tests', 'generate_unit_tests': 'generate fastText unit test cases using gen_unit_tests with an optional verbose parameter'}
```

## File: facebookresearch_fastText/setup.py

Prompts

```
['run the download_model script to download pre-trained English word vectors from fastText', 'run the download_model script with language fr to download French pre-trained vectors', 'run the download_model script with --overwrite to replace existing model files', 'review the command_download function that wraps fasttext.util.download_model for downloading vectors', 'test the main function that parses language and overwrite arguments via argparse', 'run eval.py with --model and --data flags to evaluate word vector similarity on a benchmark dataset', 'run eval.py to compute Spearman correlation between predicted and gold word pair similarity scores', 'run the similarity function to compute cosine similarity between two numpy vector arrays', 'review the compat_splitting function that decodes UTF-8 bytes and splits a line into tokens', 'review the similarity function that calculates cosine similarity between two vectors using numpy', 'run the CLI tool to reduce a fastText model dimension from 300 to 100 using PCA', 'run the CLI tool to reduce a fastText model dimension and overwrite the existing output file', 'call command_reduce to load a fastText model, reduce its dimension via PCA, and save it', 'call guess_target_name to generate a new model filename with the target dimension substituted', 'review the command_reduce function to understand how it handles overwrite, strict, and ignore modes', 'run the fastText unit tests by calling runtests.py with the --unit-tests flag', 'run the fastText integration tests by calling runtests.py with --integration-tests and --data-dir', 'run fastText tests with a custom verbosity level using the --verbose flag', 'call the run_tests function with a unittest TestLoader suite to execute tests', 'generate fastText unit test cases using gen_unit_tests with an optional verbose parameter', 'build the fasttext C++ extension module using setuptools and pybind11 bindings', 'review the BuildExt class that adds platform-specific compiler options for unix and msvc', 'test the has_flag function to check if a compiler supports specific flags', 'summarize the get_pybind_include class that resolves pybind11 include paths and auto-installs if missing', 'refactor the cpp_flag function to support additional C++ standards beyond c++17']
```

Usage

```
{'build_fasttext_extension': 'build the fasttext C++ extension module using setuptools and pybind11 bindings', 'review_BuildExt_class': 'review the BuildExt class that adds platform-specific compiler options for unix and msvc', 'test_has_flag_function': 'test the has_flag function to check if a compiler supports specific flags', 'summarize_get_pybind_include': 'summarize the get_pybind_include class that resolves pybind11 include paths and auto-installs if missing', 'refactor_cpp_flag_function': 'refactor the cpp_flag function to support additional C++ standards beyond c++17'}
```

