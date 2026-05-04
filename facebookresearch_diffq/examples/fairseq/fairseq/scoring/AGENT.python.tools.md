# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/fairseq/scoring/bleu.py

Prompts

```
['build a Scorer instance with BleuConfig to compute BLEU scores from token tensors', 'add reference and prediction torch.IntTensor pairs to the Scorer for BLEU evaluation', 'score the accumulated reference-prediction pairs and return the BLEU score for a given n-gram order', 'compute a SacrebleuScorer score using corpus_bleu with configurable tokenizer and lowercasing options', 'get a formatted result string with BLEU score, precision, brevity penalty, and length ratio', 'create a ChrFScorer instance to compute character n-gram F-score for translation evaluation', 'add a reference and prediction string pair to the ChrFScorer for scoring', 'score accumulated reference and prediction pairs using character n-gram F-score with order 4', 'get the formatted chrF result object from sacrebleu corpus_chrf for the scorer', 'review the ChrFScorer class that extends BaseScorer and uses sacrebleu for chrF scoring', 'create an EvaluationTokenizer with sacreBLEU tokenizer type 13a for text tokenization', 'tokenize a sentence using the EvaluationTokenizer with optional lowercasing and punctuation removal', 'remove punctuation from a sentence based on Unicode category using the remove_punctuation class method', 'tokenize text into individual characters using the EvaluationTokenizer with character tokenization enabled', 'review the available sacreBLEU tokenizer types including none, 13a, intl, zh, and ja-mecab', 'create a WerScorer instance with a WerScorerConfig to compute word error rate', 'add a reference and prediction string pair to the WerScorer for WER calculation', 'compute the word error rate score as a percentage from accumulated string pairs', 'reset the WerScorer distance and reference length counters to zero', 'get a formatted WER result string with the score rounded to two decimal places']
```

Usage

```
{'build_bleu_scorer': 'build a Scorer instance with BleuConfig to compute BLEU scores from token tensors', 'add_reference_prediction_pairs': 'add reference and prediction torch.IntTensor pairs to the Scorer for BLEU evaluation', 'score_bleu_order': 'score the accumulated reference-prediction pairs and return the BLEU score for a given n-gram order', 'compute_sacrebleu_score': 'compute a SacrebleuScorer score using corpus_bleu with configurable tokenizer and lowercasing options', 'get_bleu_result_string': 'get a formatted result string with BLEU score, precision, brevity penalty, and length ratio'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/scoring/chrf.py

Prompts

```
['build a Scorer instance with BleuConfig to compute BLEU scores from token tensors', 'add reference and prediction torch.IntTensor pairs to the Scorer for BLEU evaluation', 'score the accumulated reference-prediction pairs and return the BLEU score for a given n-gram order', 'compute a SacrebleuScorer score using corpus_bleu with configurable tokenizer and lowercasing options', 'get a formatted result string with BLEU score, precision, brevity penalty, and length ratio', 'create a ChrFScorer instance to compute character n-gram F-score for translation evaluation', 'add a reference and prediction string pair to the ChrFScorer for scoring', 'score accumulated reference and prediction pairs using character n-gram F-score with order 4', 'get the formatted chrF result object from sacrebleu corpus_chrf for the scorer', 'review the ChrFScorer class that extends BaseScorer and uses sacrebleu for chrF scoring', 'create an EvaluationTokenizer with sacreBLEU tokenizer type 13a for text tokenization', 'tokenize a sentence using the EvaluationTokenizer with optional lowercasing and punctuation removal', 'remove punctuation from a sentence based on Unicode category using the remove_punctuation class method', 'tokenize text into individual characters using the EvaluationTokenizer with character tokenization enabled', 'review the available sacreBLEU tokenizer types including none, 13a, intl, zh, and ja-mecab', 'create a WerScorer instance with a WerScorerConfig to compute word error rate', 'add a reference and prediction string pair to the WerScorer for WER calculation', 'compute the word error rate score as a percentage from accumulated string pairs', 'reset the WerScorer distance and reference length counters to zero', 'get a formatted WER result string with the score rounded to two decimal places']
```

Usage

```
{'create_chrf_scorer': 'create a ChrFScorer instance to compute character n-gram F-score for translation evaluation', 'add_string_ref_pred': 'add a reference and prediction string pair to the ChrFScorer for scoring', 'score_chrf_order4': 'score accumulated reference and prediction pairs using character n-gram F-score with order 4', 'result_string_chrf': 'get the formatted chrF result object from sacrebleu corpus_chrf for the scorer', 'review_chrf_scorer_class': 'review the ChrFScorer class that extends BaseScorer and uses sacrebleu for chrF scoring'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/scoring/tokenizer.py

Prompts

```
['build a Scorer instance with BleuConfig to compute BLEU scores from token tensors', 'add reference and prediction torch.IntTensor pairs to the Scorer for BLEU evaluation', 'score the accumulated reference-prediction pairs and return the BLEU score for a given n-gram order', 'compute a SacrebleuScorer score using corpus_bleu with configurable tokenizer and lowercasing options', 'get a formatted result string with BLEU score, precision, brevity penalty, and length ratio', 'create a ChrFScorer instance to compute character n-gram F-score for translation evaluation', 'add a reference and prediction string pair to the ChrFScorer for scoring', 'score accumulated reference and prediction pairs using character n-gram F-score with order 4', 'get the formatted chrF result object from sacrebleu corpus_chrf for the scorer', 'review the ChrFScorer class that extends BaseScorer and uses sacrebleu for chrF scoring', 'create an EvaluationTokenizer with sacreBLEU tokenizer type 13a for text tokenization', 'tokenize a sentence using the EvaluationTokenizer with optional lowercasing and punctuation removal', 'remove punctuation from a sentence based on Unicode category using the remove_punctuation class method', 'tokenize text into individual characters using the EvaluationTokenizer with character tokenization enabled', 'review the available sacreBLEU tokenizer types including none, 13a, intl, zh, and ja-mecab', 'create a WerScorer instance with a WerScorerConfig to compute word error rate', 'add a reference and prediction string pair to the WerScorer for WER calculation', 'compute the word error rate score as a percentage from accumulated string pairs', 'reset the WerScorer distance and reference length counters to zero', 'get a formatted WER result string with the score rounded to two decimal places']
```

Usage

```
{'create_evaluation_tokenizer': 'create an EvaluationTokenizer with sacreBLEU tokenizer type 13a for text tokenization', 'tokenize_sentence': 'tokenize a sentence using the EvaluationTokenizer with optional lowercasing and punctuation removal', 'remove_punctuation': 'remove punctuation from a sentence based on Unicode category using the remove_punctuation class method', 'tokenize_with_character_mode': 'tokenize text into individual characters using the EvaluationTokenizer with character tokenization enabled', 'review_tokenizer_types': 'review the available sacreBLEU tokenizer types including none, 13a, intl, zh, and ja-mecab'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/scoring/wer.py

Prompts

```
['build a Scorer instance with BleuConfig to compute BLEU scores from token tensors', 'add reference and prediction torch.IntTensor pairs to the Scorer for BLEU evaluation', 'score the accumulated reference-prediction pairs and return the BLEU score for a given n-gram order', 'compute a SacrebleuScorer score using corpus_bleu with configurable tokenizer and lowercasing options', 'get a formatted result string with BLEU score, precision, brevity penalty, and length ratio', 'create a ChrFScorer instance to compute character n-gram F-score for translation evaluation', 'add a reference and prediction string pair to the ChrFScorer for scoring', 'score accumulated reference and prediction pairs using character n-gram F-score with order 4', 'get the formatted chrF result object from sacrebleu corpus_chrf for the scorer', 'review the ChrFScorer class that extends BaseScorer and uses sacrebleu for chrF scoring', 'create an EvaluationTokenizer with sacreBLEU tokenizer type 13a for text tokenization', 'tokenize a sentence using the EvaluationTokenizer with optional lowercasing and punctuation removal', 'remove punctuation from a sentence based on Unicode category using the remove_punctuation class method', 'tokenize text into individual characters using the EvaluationTokenizer with character tokenization enabled', 'review the available sacreBLEU tokenizer types including none, 13a, intl, zh, and ja-mecab', 'create a WerScorer instance with a WerScorerConfig to compute word error rate', 'add a reference and prediction string pair to the WerScorer for WER calculation', 'compute the word error rate score as a percentage from accumulated string pairs', 'reset the WerScorer distance and reference length counters to zero', 'get a formatted WER result string with the score rounded to two decimal places']
```

Usage

```
{'create_WerScorer': 'create a WerScorer instance with a WerScorerConfig to compute word error rate', 'add_string_WerScorer': 'add a reference and prediction string pair to the WerScorer for WER calculation', 'score_WerScorer': 'compute the word error rate score as a percentage from accumulated string pairs', 'reset_WerScorer': 'reset the WerScorer distance and reference length counters to zero', 'result_string_WerScorer': 'get a formatted WER result string with the score rounded to two decimal places'}
```

