# Agent Python Tools

- repo: facebookresearch/grounded-video-description
- repo_uri: https://github.com/facebookresearch/grounded-video-description

## File: facebookresearch_grounded-video-description/tools/densevid_eval/coco-caption/pycocoevalcap/bleu/bleu.py

Prompts

```
['compute BLEU scores for image caption hypotheses against ground truth references using the Bleu class', 'initialize a Bleu scorer with a custom n-gram range up to n for evaluating captions', "get the method name string 'Bleu' from the Bleu class for metric identification", 'review the Bleu class compute_score method to understand how hypotheses and references are scored', 'refactor the Bleu class to switch between shortest, closest, or average scoring options', 'build a python module that uses BleuScorer to compute BLEU scores for candidate sentences against references', 'create a function that calls cook_refs to preprocess a list of reference sentences for BLEU evaluation', 'create a function that calls cook_test to preprocess a candidate sentence against cooked references for BLEU scoring', 'create a function that uses precook to extract n-gram counts and word length from a sentence string']
```

Usage

```
{'compute_bleu_score': 'compute BLEU scores for image caption hypotheses against ground truth references using the Bleu class', 'init_bleu_with_n_grams': 'initialize a Bleu scorer with a custom n-gram range up to n for evaluating captions', 'get_bleu_method_name': "get the method name string 'Bleu' from the Bleu class for metric identification", 'review_Bleu_compute_score': 'review the Bleu class compute_score method to understand how hypotheses and references are scored', 'refactor_Bleu_scoring_option': 'refactor the Bleu class to switch between shortest, closest, or average scoring options'}
```

## File: facebookresearch_grounded-video-description/tools/densevid_eval/coco-caption/pycocoevalcap/bleu/bleu_scorer.py

Prompts

```
['compute BLEU scores for image caption hypotheses against ground truth references using the Bleu class', 'initialize a Bleu scorer with a custom n-gram range up to n for evaluating captions', "get the method name string 'Bleu' from the Bleu class for metric identification", 'review the Bleu class compute_score method to understand how hypotheses and references are scored', 'refactor the Bleu class to switch between shortest, closest, or average scoring options', 'build a python module that uses BleuScorer to compute BLEU scores for candidate sentences against references', 'create a function that calls cook_refs to preprocess a list of reference sentences for BLEU evaluation', 'create a function that calls cook_test to preprocess a candidate sentence against cooked references for BLEU scoring', 'create a function that uses precook to extract n-gram counts and word length from a sentence string']
```

Usage

```
{'build_bleu_scorer': 'build a python module that uses BleuScorer to compute BLEU scores for candidate sentences against references', 'cook_refs_function': 'create a function that calls cook_refs to preprocess a list of reference sentences for BLEU evaluation', 'cook_test_function': 'create a function that calls cook_test to preprocess a candidate sentence against cooked references for BLEU scoring', 'compute_bleu_score': 'run the BleuScorer compute_score method to calculate BLEU scores with closest or average reference length strategy', 'precook_ngrams': 'create a function that uses precook to extract n-gram counts and word length from a sentence string'}
```

