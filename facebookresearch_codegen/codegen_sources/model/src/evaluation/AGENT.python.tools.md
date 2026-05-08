# Agent Python Tools

- repo: facebookresearch/codegen
- repo_uri: https://github.com/facebookresearch/codegen

## File: facebookresearch_codegen/codegen_sources/model/src/evaluation/comp_acc_computation.py

Prompts

```
['run evaluation of generated code functions against reference solutions across multiple programming languages', 'submit generated code functions for execution and test against expected outputs in a given language', 'submit generated functions for CodeNet dataset evaluation using input/output test cases', 'submit generated functions for evaluation against EvoSuite-generated unit tests in C++ or Python', 'load and translate EvoSuite Java unit tests into Python and C++ test formats', 'run all evaluation metrics including CLM, MLM, MT, and classification on the model', 'compute BLEU score between hypothesis and reference text files using Moses scripts', 'evaluate BLEU score from hypothesis and reference files via the Moses multi-bleu.perl script', 'unsegment and detokenize a list of code sentences for a given programming language', 'evaluate machine translation perplexity and accuracy for a source to target language pair', 'run subtoken-level precision and recall evaluation on hypothesis and reference files for code deobfuscation', 'compute subtokens from a token string by converting to snake case and splitting on underscores', 'compute the number of precise, proposed, and ground truth subtokens from two token strings', 'calculate precision, recall, and F1 scores for subtoken-level comparison between proposed and ground truth tokens', 'evaluate subtoken precision, recall, F1, and exact match scores on lists of hypothesis and reference lines', 'test subtoken_counts to compare proposed and ground truth identifier subtoken counts', 'test subtoken_score_on_lines to evaluate precision recall and F1 on variable name deobfuscation', 'test subtoken_score_on_lines_subtoken_level to compute aggregated subtoken precision recall and F1 scores', 'test subtoken_score_on_lines with multiple beam hypotheses to select the best scoring beam', 'test subtoken_score_on_lines to verify case insensitive matching between snake_case and camelCase identifiers']
```

Usage

```
{'run_eval_function_output': 'run evaluation of generated code functions against reference solutions across multiple programming languages', 'run_submit_functions': 'submit generated code functions for execution and test against expected outputs in a given language', 'run_submit_codenet_functions': 'submit generated functions for CodeNet dataset evaluation using input/output test cases', 'run_submit_evosuite_functions': 'submit generated functions for evaluation against EvoSuite-generated unit tests in C++ or Python', 'run_load_evosuite_transcoder_tests': 'load and translate EvoSuite Java unit tests into Python and C++ test formats'}
```

## File: facebookresearch_codegen/codegen_sources/model/src/evaluation/evaluator.py

Prompts

```
['run evaluation of generated code functions against reference solutions across multiple programming languages', 'submit generated code functions for execution and test against expected outputs in a given language', 'submit generated functions for CodeNet dataset evaluation using input/output test cases', 'submit generated functions for evaluation against EvoSuite-generated unit tests in C++ or Python', 'load and translate EvoSuite Java unit tests into Python and C++ test formats', 'run all evaluation metrics including CLM, MLM, MT, and classification on the model', 'compute BLEU score between hypothesis and reference text files using Moses scripts', 'evaluate BLEU score from hypothesis and reference files via the Moses multi-bleu.perl script', 'unsegment and detokenize a list of code sentences for a given programming language', 'evaluate machine translation perplexity and accuracy for a source to target language pair', 'run subtoken-level precision and recall evaluation on hypothesis and reference files for code deobfuscation', 'compute subtokens from a token string by converting to snake case and splitting on underscores', 'compute the number of precise, proposed, and ground truth subtokens from two token strings', 'calculate precision, recall, and F1 scores for subtoken-level comparison between proposed and ground truth tokens', 'evaluate subtoken precision, recall, F1, and exact match scores on lists of hypothesis and reference lines', 'test subtoken_counts to compare proposed and ground truth identifier subtoken counts', 'test subtoken_score_on_lines to evaluate precision recall and F1 on variable name deobfuscation', 'test subtoken_score_on_lines_subtoken_level to compute aggregated subtoken precision recall and F1 scores', 'test subtoken_score_on_lines with multiple beam hypotheses to select the best scoring beam', 'test subtoken_score_on_lines to verify case insensitive matching between snake_case and camelCase identifiers']
```

Usage

```
{'run_evaluator_all_evals': 'run all evaluation metrics including CLM, MLM, MT, and classification on the model', 'run_compute_bleu': 'compute BLEU score between hypothesis and reference text files using Moses scripts', 'run_eval_moses_bleu': 'evaluate BLEU score from hypothesis and reference files via the Moses multi-bleu.perl script', 'run_unsegment_and_detokenize': 'unsegment and detokenize a list of code sentences for a given programming language', 'run_encdec_evaluator_mt': 'evaluate machine translation perplexity and accuracy for a source to target language pair'}
```

## File: facebookresearch_codegen/codegen_sources/model/src/evaluation/subtoken_score.py

Prompts

```
['run evaluation of generated code functions against reference solutions across multiple programming languages', 'submit generated code functions for execution and test against expected outputs in a given language', 'submit generated functions for CodeNet dataset evaluation using input/output test cases', 'submit generated functions for evaluation against EvoSuite-generated unit tests in C++ or Python', 'load and translate EvoSuite Java unit tests into Python and C++ test formats', 'run all evaluation metrics including CLM, MLM, MT, and classification on the model', 'compute BLEU score between hypothesis and reference text files using Moses scripts', 'evaluate BLEU score from hypothesis and reference files via the Moses multi-bleu.perl script', 'unsegment and detokenize a list of code sentences for a given programming language', 'evaluate machine translation perplexity and accuracy for a source to target language pair', 'run subtoken-level precision and recall evaluation on hypothesis and reference files for code deobfuscation', 'compute subtokens from a token string by converting to snake case and splitting on underscores', 'compute the number of precise, proposed, and ground truth subtokens from two token strings', 'calculate precision, recall, and F1 scores for subtoken-level comparison between proposed and ground truth tokens', 'evaluate subtoken precision, recall, F1, and exact match scores on lists of hypothesis and reference lines', 'test subtoken_counts to compare proposed and ground truth identifier subtoken counts', 'test subtoken_score_on_lines to evaluate precision recall and F1 on variable name deobfuscation', 'test subtoken_score_on_lines_subtoken_level to compute aggregated subtoken precision recall and F1 scores', 'test subtoken_score_on_lines with multiple beam hypotheses to select the best scoring beam', 'test subtoken_score_on_lines to verify case insensitive matching between snake_case and camelCase identifiers']
```

Usage

```
{'run_subtoken_score': 'run subtoken-level precision and recall evaluation on hypothesis and reference files for code deobfuscation', 'compute_subtokens': 'compute subtokens from a token string by converting to snake case and splitting on underscores', 'subtoken_counts': 'compute the number of precise, proposed, and ground truth subtokens from two token strings', 'subtoken_scores': 'calculate precision, recall, and F1 scores for subtoken-level comparison between proposed and ground truth tokens', 'subtoken_score_on_lines': 'evaluate subtoken precision, recall, F1, and exact match scores on lists of hypothesis and reference lines'}
```

## File: facebookresearch_codegen/codegen_sources/model/src/evaluation/test_subtoken_score.py

Prompts

```
['run evaluation of generated code functions against reference solutions across multiple programming languages', 'submit generated code functions for execution and test against expected outputs in a given language', 'submit generated functions for CodeNet dataset evaluation using input/output test cases', 'submit generated functions for evaluation against EvoSuite-generated unit tests in C++ or Python', 'load and translate EvoSuite Java unit tests into Python and C++ test formats', 'run all evaluation metrics including CLM, MLM, MT, and classification on the model', 'compute BLEU score between hypothesis and reference text files using Moses scripts', 'evaluate BLEU score from hypothesis and reference files via the Moses multi-bleu.perl script', 'unsegment and detokenize a list of code sentences for a given programming language', 'evaluate machine translation perplexity and accuracy for a source to target language pair', 'run subtoken-level precision and recall evaluation on hypothesis and reference files for code deobfuscation', 'compute subtokens from a token string by converting to snake case and splitting on underscores', 'compute the number of precise, proposed, and ground truth subtokens from two token strings', 'calculate precision, recall, and F1 scores for subtoken-level comparison between proposed and ground truth tokens', 'evaluate subtoken precision, recall, F1, and exact match scores on lists of hypothesis and reference lines', 'test subtoken_counts to compare proposed and ground truth identifier subtoken counts', 'test subtoken_score_on_lines to evaluate precision recall and F1 on variable name deobfuscation', 'test subtoken_score_on_lines_subtoken_level to compute aggregated subtoken precision recall and F1 scores', 'test subtoken_score_on_lines with multiple beam hypotheses to select the best scoring beam', 'test subtoken_score_on_lines to verify case insensitive matching between snake_case and camelCase identifiers']
```

Usage

```
{'test_subtoken_counts': 'test subtoken_counts to compare proposed and ground truth identifier subtoken counts', 'test_subtoken_score_on_lines': 'test subtoken_score_on_lines to evaluate precision recall and F1 on variable name deobfuscation', 'test_subtoken_score_on_lines_subtoken_level': 'test subtoken_score_on_lines_subtoken_level to compute aggregated subtoken precision recall and F1 scores', 'test_subtoken_score_beam_search': 'test subtoken_score_on_lines with multiple beam hypotheses to select the best scoring beam', 'test_subtoken_score_case_insensitive': 'test subtoken_score_on_lines to verify case insensitive matching between snake_case and camelCase identifiers'}
```

