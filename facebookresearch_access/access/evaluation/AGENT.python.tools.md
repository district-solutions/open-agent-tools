# Agent Python Tools

- repo: facebookresearch/access
- repo_uri: https://github.com/facebookresearch/access

## File: facebookresearch_access/access/evaluation/general.py

Prompts

```
['run a sentence simplifier on the turkcorpus dataset and return the prediction filepath', 'evaluate a sentence simplifier on turkcorpus using bleu, sari, and fkgl metrics', 'get predictions from a simplifier function on the turkcorpus complex sentences', 'test the evaluate_simplifier_on_turkcorpus function with a custom simplifier and phase', 'refactor get_prediction_on_turkcorpus to support additional corpus datasets beyond turkcorpus', 'normalize a BLEU score between 0 and 100 to a value between 0 and 1', 'normalize a SARI score between 0 and 60 to a value between 0 and 1', 'normalize a FKGL score between 0 and 20 to an inverted value between 0 and 1', 'combine BLEU, SARI, and FKGL scores into a single harmonic mean metric using coefficients', 'review the BLEU, SARI, and FKGL transform functions to understand normalization ranges and inversion logic']
```

Usage

```
{'run_simplifier_on_turkcorpus': 'run a sentence simplifier on the turkcorpus dataset and return the prediction filepath', 'evaluate_simplifier_on_turkcorpus': 'evaluate a sentence simplifier on turkcorpus using bleu, sari, and fkgl metrics', 'get_prediction_on_turkcorpus': 'get predictions from a simplifier function on the turkcorpus complex sentences', 'test_evaluate_simplifier_on_turkcorpus': 'test the evaluate_simplifier_on_turkcorpus function with a custom simplifier and phase', 'refactor_get_prediction_on_turkcorpus': 'refactor get_prediction_on_turkcorpus to support additional corpus datasets beyond turkcorpus'}
```

## File: facebookresearch_access/access/evaluation/utils.py

Prompts

```
['run a sentence simplifier on the turkcorpus dataset and return the prediction filepath', 'evaluate a sentence simplifier on turkcorpus using bleu, sari, and fkgl metrics', 'get predictions from a simplifier function on the turkcorpus complex sentences', 'test the evaluate_simplifier_on_turkcorpus function with a custom simplifier and phase', 'refactor get_prediction_on_turkcorpus to support additional corpus datasets beyond turkcorpus', 'normalize a BLEU score between 0 and 100 to a value between 0 and 1', 'normalize a SARI score between 0 and 60 to a value between 0 and 1', 'normalize a FKGL score between 0 and 20 to an inverted value between 0 and 1', 'combine BLEU, SARI, and FKGL scores into a single harmonic mean metric using coefficients', 'review the BLEU, SARI, and FKGL transform functions to understand normalization ranges and inversion logic']
```

Usage

```
{'transform_bleu_score': 'normalize a BLEU score between 0 and 100 to a value between 0 and 1', 'transform_sari_score': 'normalize a SARI score between 0 and 60 to a value between 0 and 1', 'transform_fkgl_score': 'normalize a FKGL score between 0 and 20 to an inverted value between 0 and 1', 'combine_evaluation_metrics': 'combine BLEU, SARI, and FKGL scores into a single harmonic mean metric using coefficients', 'review_transform_functions': 'review the BLEU, SARI, and FKGL transform functions to understand normalization ranges and inversion logic'}
```

