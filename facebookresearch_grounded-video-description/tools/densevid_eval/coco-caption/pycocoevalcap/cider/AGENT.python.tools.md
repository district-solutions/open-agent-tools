# Agent Python Tools

- repo: facebookresearch/grounded-video-description
- repo_uri: https://github.com/facebookresearch/grounded-video-description

## File: facebookresearch_grounded-video-description/tools/densevid_eval/coco-caption/pycocoevalcap/cider/cider.py

Prompts

```
['compute the CIDEr score for a corpus of image captions by comparing hypotheses against references', 'create a Cider scorer instance with configurable n-gram range and gaussian penalty sigma parameter', 'get the string name of the CIDEr evaluation metric method', 'review the Cider class and its compute_score method for caption evaluation logic', 'summarize how the CiderScorer is used internally to accumulate and compute CIDEr scores', 'precook a sentence into an n-gram term frequency vector for CIDEr scoring', 'cook a list of reference sentences into precomputed n-gram representations', 'cook a single test sentence into a precomputed n-gram representation', 'compute document frequency of n-grams across all reference captions for IDF calculation']
```

Usage

```
{'compute_cider_score': 'compute the CIDEr score for a corpus of image captions by comparing hypotheses against references', 'init_cider_scorer': 'create a Cider scorer instance with configurable n-gram range and gaussian penalty sigma parameter', 'get_cider_method_name': 'get the string name of the CIDEr evaluation metric method', 'review_cider_class': 'review the Cider class and its compute_score method for caption evaluation logic', 'summarize_cider_scorer_usage': 'summarize how the CiderScorer is used internally to accumulate and compute CIDEr scores'}
```

## File: facebookresearch_grounded-video-description/tools/densevid_eval/coco-caption/pycocoevalcap/cider/cider_scorer.py

Prompts

```
['compute the CIDEr score for a corpus of image captions by comparing hypotheses against references', 'create a Cider scorer instance with configurable n-gram range and gaussian penalty sigma parameter', 'get the string name of the CIDEr evaluation metric method', 'review the Cider class and its compute_score method for caption evaluation logic', 'summarize how the CiderScorer is used internally to accumulate and compute CIDEr scores', 'precook a sentence into an n-gram term frequency vector for CIDEr scoring', 'cook a list of reference sentences into precomputed n-gram representations', 'cook a single test sentence into a precomputed n-gram representation', 'compute document frequency of n-grams across all reference captions for IDF calculation']
```

Usage

```
{'compute_cider_score': 'compute the CIDEr score for test captions against reference captions using corpus IDF', 'precook_ngrams': 'precook a sentence into an n-gram term frequency vector for CIDEr scoring', 'cook_references': 'cook a list of reference sentences into precomputed n-gram representations', 'cook_test_sentence': 'cook a single test sentence into a precomputed n-gram representation', 'compute_doc_freq': 'compute document frequency of n-grams across all reference captions for IDF calculation'}
```

