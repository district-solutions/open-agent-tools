# Agent Python Tools

- repo: facebookresearch/codegen
- repo_uri: https://github.com/facebookresearch/codegen

## File: facebookresearch_codegen/codegen_sources/model/model_tests/test_comp_acc_computation.py

Prompts

```
['test the submit_functions API by submitting a correct C++ hypothesis against a reference and asserting success', 'test the submit_functions API by submitting a C++ function with a minor naming bug and asserting success', 'initialize evaluation scripts folders for a given dataset and language pair using the Params configuration object', 'submit a list of hypothesis functions against a reference function for compilation accuracy evaluation in C++', 'create a Params instance to hold the eval_scripts_root path and eval_scripts_folders dictionary for evaluation configuration', 'run the pytest test_reload_and_run to verify TransCoder encoder/decoder forward pass with parametrized efficient attention modes', 'run the pytest test_reload_and_run_with_padding to verify TransCoder forward pass with batched padded sequences', 'test the reload_model function to load a TransCoder checkpoint and build encoder/decoder with BPE tokenization', 'test the get_loss function to compute prediction loss from decoder outputs and target sequences', 'test the decode function to run source code through the TransCoder decoder with encoder context', 'test subtoken_counts to compare proposed and ground truth variable names and return token counts', 'test subtoken_score_on_lines to compute precision recall and F1 scores for variable name predictions', 'test subtoken_score_on_lines_subtoken_level to compute aggregated subtoken-level precision recall and F1 scores', 'test subtoken_score_on_lines with multiple beam hypotheses to select the best scoring beam', 'test subtoken_score_on_lines to verify case-insensitive matching between snake_case and camelCase variable names', 'test translating a C++ factorial function to Python using the TransCoder model', 'test translating a Python factorial function to C++ using the TransCoder model', 'test translating a Java factorial function to Python using the TransCoder model', 'test translating Python code to C++ with beam search decoding for multiple candidates', 'run the Translator class to translate code between programming languages like C++ to Java']
```

Usage

```
{'test_submit_correct_function': 'test the submit_functions API by submitting a correct C++ hypothesis against a reference and asserting success', 'test_submit_correct_function_bug': 'test the submit_functions API by submitting a C++ function with a minor naming bug and asserting success', 'init_eval_scripts_folder': 'initialize evaluation scripts folders for a given dataset and language pair using the Params configuration object', 'submit_functions': 'submit a list of hypothesis functions against a reference function for compilation accuracy evaluation in C++', 'Params_class': 'create a Params instance to hold the eval_scripts_root path and eval_scripts_folders dictionary for evaluation configuration'}
```

## File: facebookresearch_codegen/codegen_sources/model/model_tests/test_forward_pass.py

Prompts

```
['test the submit_functions API by submitting a correct C++ hypothesis against a reference and asserting success', 'test the submit_functions API by submitting a C++ function with a minor naming bug and asserting success', 'initialize evaluation scripts folders for a given dataset and language pair using the Params configuration object', 'submit a list of hypothesis functions against a reference function for compilation accuracy evaluation in C++', 'create a Params instance to hold the eval_scripts_root path and eval_scripts_folders dictionary for evaluation configuration', 'run the pytest test_reload_and_run to verify TransCoder encoder/decoder forward pass with parametrized efficient attention modes', 'run the pytest test_reload_and_run_with_padding to verify TransCoder forward pass with batched padded sequences', 'test the reload_model function to load a TransCoder checkpoint and build encoder/decoder with BPE tokenization', 'test the get_loss function to compute prediction loss from decoder outputs and target sequences', 'test the decode function to run source code through the TransCoder decoder with encoder context', 'test subtoken_counts to compare proposed and ground truth variable names and return token counts', 'test subtoken_score_on_lines to compute precision recall and F1 scores for variable name predictions', 'test subtoken_score_on_lines_subtoken_level to compute aggregated subtoken-level precision recall and F1 scores', 'test subtoken_score_on_lines with multiple beam hypotheses to select the best scoring beam', 'test subtoken_score_on_lines to verify case-insensitive matching between snake_case and camelCase variable names', 'test translating a C++ factorial function to Python using the TransCoder model', 'test translating a Python factorial function to C++ using the TransCoder model', 'test translating a Java factorial function to Python using the TransCoder model', 'test translating Python code to C++ with beam search decoding for multiple candidates', 'run the Translator class to translate code between programming languages like C++ to Java']
```

Usage

```
{'run_test_reload_and_run': 'run the pytest test_reload_and_run to verify TransCoder encoder/decoder forward pass with parametrized efficient attention modes', 'run_test_reload_and_run_with_padding': 'run the pytest test_reload_and_run_with_padding to verify TransCoder forward pass with batched padded sequences', 'test_reload_model': 'test the reload_model function to load a TransCoder checkpoint and build encoder/decoder with BPE tokenization', 'test_get_loss': 'test the get_loss function to compute prediction loss from decoder outputs and target sequences', 'test_decode': 'test the decode function to run source code through the TransCoder decoder with encoder context'}
```

## File: facebookresearch_codegen/codegen_sources/model/model_tests/test_subtoken_score.py

Prompts

```
['test the submit_functions API by submitting a correct C++ hypothesis against a reference and asserting success', 'test the submit_functions API by submitting a C++ function with a minor naming bug and asserting success', 'initialize evaluation scripts folders for a given dataset and language pair using the Params configuration object', 'submit a list of hypothesis functions against a reference function for compilation accuracy evaluation in C++', 'create a Params instance to hold the eval_scripts_root path and eval_scripts_folders dictionary for evaluation configuration', 'run the pytest test_reload_and_run to verify TransCoder encoder/decoder forward pass with parametrized efficient attention modes', 'run the pytest test_reload_and_run_with_padding to verify TransCoder forward pass with batched padded sequences', 'test the reload_model function to load a TransCoder checkpoint and build encoder/decoder with BPE tokenization', 'test the get_loss function to compute prediction loss from decoder outputs and target sequences', 'test the decode function to run source code through the TransCoder decoder with encoder context', 'test subtoken_counts to compare proposed and ground truth variable names and return token counts', 'test subtoken_score_on_lines to compute precision recall and F1 scores for variable name predictions', 'test subtoken_score_on_lines_subtoken_level to compute aggregated subtoken-level precision recall and F1 scores', 'test subtoken_score_on_lines with multiple beam hypotheses to select the best scoring beam', 'test subtoken_score_on_lines to verify case-insensitive matching between snake_case and camelCase variable names', 'test translating a C++ factorial function to Python using the TransCoder model', 'test translating a Python factorial function to C++ using the TransCoder model', 'test translating a Java factorial function to Python using the TransCoder model', 'test translating Python code to C++ with beam search decoding for multiple candidates', 'run the Translator class to translate code between programming languages like C++ to Java']
```

Usage

```
{'test_subtoken_counts': 'test subtoken_counts to compare proposed and ground truth variable names and return token counts', 'test_subtoken_score_on_lines': 'test subtoken_score_on_lines to compute precision recall and F1 scores for variable name predictions', 'test_subtoken_score_on_lines_subtoken_level': 'test subtoken_score_on_lines_subtoken_level to compute aggregated subtoken-level precision recall and F1 scores', 'test_subtoken_score_best_beam': 'test subtoken_score_on_lines with multiple beam hypotheses to select the best scoring beam', 'test_subtoken_score_case_insensitive': 'test subtoken_score_on_lines to verify case-insensitive matching between snake_case and camelCase variable names'}
```

## File: facebookresearch_codegen/codegen_sources/model/model_tests/test_translation.py

Prompts

```
['test the submit_functions API by submitting a correct C++ hypothesis against a reference and asserting success', 'test the submit_functions API by submitting a C++ function with a minor naming bug and asserting success', 'initialize evaluation scripts folders for a given dataset and language pair using the Params configuration object', 'submit a list of hypothesis functions against a reference function for compilation accuracy evaluation in C++', 'create a Params instance to hold the eval_scripts_root path and eval_scripts_folders dictionary for evaluation configuration', 'run the pytest test_reload_and_run to verify TransCoder encoder/decoder forward pass with parametrized efficient attention modes', 'run the pytest test_reload_and_run_with_padding to verify TransCoder forward pass with batched padded sequences', 'test the reload_model function to load a TransCoder checkpoint and build encoder/decoder with BPE tokenization', 'test the get_loss function to compute prediction loss from decoder outputs and target sequences', 'test the decode function to run source code through the TransCoder decoder with encoder context', 'test subtoken_counts to compare proposed and ground truth variable names and return token counts', 'test subtoken_score_on_lines to compute precision recall and F1 scores for variable name predictions', 'test subtoken_score_on_lines_subtoken_level to compute aggregated subtoken-level precision recall and F1 scores', 'test subtoken_score_on_lines with multiple beam hypotheses to select the best scoring beam', 'test subtoken_score_on_lines to verify case-insensitive matching between snake_case and camelCase variable names', 'test translating a C++ factorial function to Python using the TransCoder model', 'test translating a Python factorial function to C++ using the TransCoder model', 'test translating a Java factorial function to Python using the TransCoder model', 'test translating Python code to C++ with beam search decoding for multiple candidates', 'run the Translator class to translate code between programming languages like C++ to Java']
```

Usage

```
{'test_cpp_to_python_translation': 'test translating a C++ factorial function to Python using the TransCoder model', 'test_python_to_cpp_translation': 'test translating a Python factorial function to C++ using the TransCoder model', 'test_java_to_python_translation': 'test translating a Java factorial function to Python using the TransCoder model', 'test_translation_with_beam_decoding': 'test translating Python code to C++ with beam search decoding for multiple candidates', 'run_translation_class_tester': 'run the Translator class to translate code between programming languages like C++ to Java'}
```

