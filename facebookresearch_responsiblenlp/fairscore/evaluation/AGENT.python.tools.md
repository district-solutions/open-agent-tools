# Agent Python Tools

- repo: facebookresearch/responsiblenlp
- repo_uri: https://github.com/facebookresearch/responsiblenlp

## File: facebookresearch_responsiblenlp/fairscore/evaluation/process_baseline_comparison.py

Prompts

```
['run the script with --csv_file to compute bleu, rouge, and levenshtein metrics for text rewriting models', 'compute a BLEU score between a prediction string and a reference string using sacrebleu', 'compute ROUGE-1, ROUGE-2, and ROUGE-L F1 scores between predictions and references', 'compute the word-level Levenshtein distance between two text strings with optional normalization', 'apply a metric function across a DataFrame to compare model rewrites against annotator rewrites', 'run the python module to generate an HTML comparison of perturbation methods from a pipe-delimited CSV file', 'render an HTML visualization highlighting changed words between original and rewritten text using difflib sequence matching', 'compare AugLy, TextFlint, Perturber, and Annotator text perturbation methods side by side in an HTML report', 'tokenize original and rewritten text with NLTK and diff the sequences to find changed words', 'generate an HTML page with color-coded highlights showing differences between original text and four perturbation method outputs']
```

Usage

```
{'run_baseline_comparison': 'run the script with --csv_file to compute bleu, rouge, and levenshtein metrics for text rewriting models', 'compute_bleu_score': 'compute a BLEU score between a prediction string and a reference string using sacrebleu', 'compute_rouge_score': 'compute ROUGE-1, ROUGE-2, and ROUGE-L F1 scores between predictions and references', 'compute_levenshtein_distance': 'compute the word-level Levenshtein distance between two text strings with optional normalization', 'compute_metrics_on_dataframe': 'apply a metric function across a DataFrame to compare model rewrites against annotator rewrites'}
```

## File: facebookresearch_responsiblenlp/fairscore/evaluation/visualize_differences.py

Prompts

```
['run the script with --csv_file to compute bleu, rouge, and levenshtein metrics for text rewriting models', 'compute a BLEU score between a prediction string and a reference string using sacrebleu', 'compute ROUGE-1, ROUGE-2, and ROUGE-L F1 scores between predictions and references', 'compute the word-level Levenshtein distance between two text strings with optional normalization', 'apply a metric function across a DataFrame to compare model rewrites against annotator rewrites', 'run the python module to generate an HTML comparison of perturbation methods from a pipe-delimited CSV file', 'render an HTML visualization highlighting changed words between original and rewritten text using difflib sequence matching', 'compare AugLy, TextFlint, Perturber, and Annotator text perturbation methods side by side in an HTML report', 'tokenize original and rewritten text with NLTK and diff the sequences to find changed words', 'generate an HTML page with color-coded highlights showing differences between original text and four perturbation method outputs']
```

Usage

```
{'run_visualize_differences': 'run the python module to generate an HTML comparison of perturbation methods from a pipe-delimited CSV file', 'render_rewrite_highlight_changes': 'render an HTML visualization highlighting changed words between original and rewritten text using difflib sequence matching', 'compare_perturbation_methods': 'compare AugLy, TextFlint, Perturber, and Annotator text perturbation methods side by side in an HTML report', 'tokenize_and_diff_text': 'tokenize original and rewritten text with NLTK and diff the sequences to find changed words', 'generate_perturbation_comparison_html': 'generate an HTML page with color-coded highlights showing differences between original text and four perturbation method outputs'}
```

