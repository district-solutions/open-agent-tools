# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/fairseq/scoring/bleu.py

Prompts

```
['build a Scorer instance with BleuConfig to compute BLEU scores from torch.IntTensor references and predictions', 'add reference and prediction token tensors to the Scorer using the add method for BLEU accumulation', 'compute the final BLEU score by calling score on the Scorer with a specified n-gram order', 'create a SacrebleuScorer with SacrebleuConfig to evaluate translations using sacrebleu corpus_bleu with custom tokenization', 'get a formatted BLEU result string with precision, brevity penalty, ratio, and lengths via result_string', 'create a ChrFScorer instance to compute character n-gram F-score for translation evaluation', 'add a reference and prediction string pair to the ChrFScorer for scoring', 'score accumulated reference and prediction pairs using character n-gram F-score with order 4', 'get the formatted chrF result object from sacrebleu corpus_chrf for the scorer', 'review the ChrFScorer class that extends BaseScorer and uses sacrebleu for chrF scoring', 'create an EvaluationTokenizer with sacreBLEU tokenizer type 13a for evaluation-time text tokenization', 'tokenize a sentence using the EvaluationTokenizer with optional lowercasing and punctuation removal', 'remove punctuation from a sentence using the EvaluationTokenizer remove_punctuation class method based on Unicode category', 'create an EvaluationTokenizer with character tokenization enabled to split text into individual characters', 'review the EvaluationTokenizer ALL_TOKENIZER_TYPES enum to see available sacreBLEU tokenizer options like none, 13a, intl, zh, ja-mecab', 'create a WerScorerConfig dataclass to configure WER evaluation with tokenizer, punctuation removal, and character level options', 'build a WerScorer instance that computes word error rate using editdistance and an EvaluationTokenizer', 'run add_string on a WerScorer to accumulate edit distance between reference and hypothesis strings', 'test the WerScorer score method to return the WER percentage from accumulated edit distance and reference length', 'review the WerScorer reset method to zero out accumulated distance and reference length counters']
```

Usage

```
{'build_bleu_scorer': 'build a Scorer instance with BleuConfig to compute BLEU scores from torch.IntTensor references and predictions', 'add_reference_prediction_pairs': 'add reference and prediction token tensors to the Scorer using the add method for BLEU accumulation', 'compute_bleu_score': 'compute the final BLEU score by calling score on the Scorer with a specified n-gram order', 'create_sacrebleu_scorer': 'create a SacrebleuScorer with SacrebleuConfig to evaluate translations using sacrebleu corpus_bleu with custom tokenization', 'get_bleu_result_string': 'get a formatted BLEU result string with precision, brevity penalty, ratio, and lengths via result_string'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/scoring/chrf.py

Prompts

```
['build a Scorer instance with BleuConfig to compute BLEU scores from torch.IntTensor references and predictions', 'add reference and prediction token tensors to the Scorer using the add method for BLEU accumulation', 'compute the final BLEU score by calling score on the Scorer with a specified n-gram order', 'create a SacrebleuScorer with SacrebleuConfig to evaluate translations using sacrebleu corpus_bleu with custom tokenization', 'get a formatted BLEU result string with precision, brevity penalty, ratio, and lengths via result_string', 'create a ChrFScorer instance to compute character n-gram F-score for translation evaluation', 'add a reference and prediction string pair to the ChrFScorer for scoring', 'score accumulated reference and prediction pairs using character n-gram F-score with order 4', 'get the formatted chrF result object from sacrebleu corpus_chrf for the scorer', 'review the ChrFScorer class that extends BaseScorer and uses sacrebleu for chrF scoring', 'create an EvaluationTokenizer with sacreBLEU tokenizer type 13a for evaluation-time text tokenization', 'tokenize a sentence using the EvaluationTokenizer with optional lowercasing and punctuation removal', 'remove punctuation from a sentence using the EvaluationTokenizer remove_punctuation class method based on Unicode category', 'create an EvaluationTokenizer with character tokenization enabled to split text into individual characters', 'review the EvaluationTokenizer ALL_TOKENIZER_TYPES enum to see available sacreBLEU tokenizer options like none, 13a, intl, zh, ja-mecab', 'create a WerScorerConfig dataclass to configure WER evaluation with tokenizer, punctuation removal, and character level options', 'build a WerScorer instance that computes word error rate using editdistance and an EvaluationTokenizer', 'run add_string on a WerScorer to accumulate edit distance between reference and hypothesis strings', 'test the WerScorer score method to return the WER percentage from accumulated edit distance and reference length', 'review the WerScorer reset method to zero out accumulated distance and reference length counters']
```

Usage

```
{'create_chrf_scorer': 'create a ChrFScorer instance to compute character n-gram F-score for translation evaluation', 'add_string_ref_pred': 'add a reference and prediction string pair to the ChrFScorer for scoring', 'score_chrf': 'score accumulated reference and prediction pairs using character n-gram F-score with order 4', 'result_string_chrf': 'get the formatted chrF result object from sacrebleu corpus_chrf for the scorer', 'review_chrf_scorer_class': 'review the ChrFScorer class that extends BaseScorer and uses sacrebleu for chrF scoring'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/scoring/tokenizer.py

Prompts

```
['build a Scorer instance with BleuConfig to compute BLEU scores from torch.IntTensor references and predictions', 'add reference and prediction token tensors to the Scorer using the add method for BLEU accumulation', 'compute the final BLEU score by calling score on the Scorer with a specified n-gram order', 'create a SacrebleuScorer with SacrebleuConfig to evaluate translations using sacrebleu corpus_bleu with custom tokenization', 'get a formatted BLEU result string with precision, brevity penalty, ratio, and lengths via result_string', 'create a ChrFScorer instance to compute character n-gram F-score for translation evaluation', 'add a reference and prediction string pair to the ChrFScorer for scoring', 'score accumulated reference and prediction pairs using character n-gram F-score with order 4', 'get the formatted chrF result object from sacrebleu corpus_chrf for the scorer', 'review the ChrFScorer class that extends BaseScorer and uses sacrebleu for chrF scoring', 'create an EvaluationTokenizer with sacreBLEU tokenizer type 13a for evaluation-time text tokenization', 'tokenize a sentence using the EvaluationTokenizer with optional lowercasing and punctuation removal', 'remove punctuation from a sentence using the EvaluationTokenizer remove_punctuation class method based on Unicode category', 'create an EvaluationTokenizer with character tokenization enabled to split text into individual characters', 'review the EvaluationTokenizer ALL_TOKENIZER_TYPES enum to see available sacreBLEU tokenizer options like none, 13a, intl, zh, ja-mecab', 'create a WerScorerConfig dataclass to configure WER evaluation with tokenizer, punctuation removal, and character level options', 'build a WerScorer instance that computes word error rate using editdistance and an EvaluationTokenizer', 'run add_string on a WerScorer to accumulate edit distance between reference and hypothesis strings', 'test the WerScorer score method to return the WER percentage from accumulated edit distance and reference length', 'review the WerScorer reset method to zero out accumulated distance and reference length counters']
```

Usage

```
{'create_evaluation_tokenizer': 'create an EvaluationTokenizer with sacreBLEU tokenizer type 13a for evaluation-time text tokenization', 'tokenize_sentence': 'tokenize a sentence using the EvaluationTokenizer with optional lowercasing and punctuation removal', 'remove_punctuation_classmethod': 'remove punctuation from a sentence using the EvaluationTokenizer remove_punctuation class method based on Unicode category', 'create_character_tokenizer': 'create an EvaluationTokenizer with character tokenization enabled to split text into individual characters', 'review_tokenizer_types': 'review the EvaluationTokenizer ALL_TOKENIZER_TYPES enum to see available sacreBLEU tokenizer options like none, 13a, intl, zh, ja-mecab'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/scoring/wer.py

Prompts

```
['build a Scorer instance with BleuConfig to compute BLEU scores from torch.IntTensor references and predictions', 'add reference and prediction token tensors to the Scorer using the add method for BLEU accumulation', 'compute the final BLEU score by calling score on the Scorer with a specified n-gram order', 'create a SacrebleuScorer with SacrebleuConfig to evaluate translations using sacrebleu corpus_bleu with custom tokenization', 'get a formatted BLEU result string with precision, brevity penalty, ratio, and lengths via result_string', 'create a ChrFScorer instance to compute character n-gram F-score for translation evaluation', 'add a reference and prediction string pair to the ChrFScorer for scoring', 'score accumulated reference and prediction pairs using character n-gram F-score with order 4', 'get the formatted chrF result object from sacrebleu corpus_chrf for the scorer', 'review the ChrFScorer class that extends BaseScorer and uses sacrebleu for chrF scoring', 'create an EvaluationTokenizer with sacreBLEU tokenizer type 13a for evaluation-time text tokenization', 'tokenize a sentence using the EvaluationTokenizer with optional lowercasing and punctuation removal', 'remove punctuation from a sentence using the EvaluationTokenizer remove_punctuation class method based on Unicode category', 'create an EvaluationTokenizer with character tokenization enabled to split text into individual characters', 'review the EvaluationTokenizer ALL_TOKENIZER_TYPES enum to see available sacreBLEU tokenizer options like none, 13a, intl, zh, ja-mecab', 'create a WerScorerConfig dataclass to configure WER evaluation with tokenizer, punctuation removal, and character level options', 'build a WerScorer instance that computes word error rate using editdistance and an EvaluationTokenizer', 'run add_string on a WerScorer to accumulate edit distance between reference and hypothesis strings', 'test the WerScorer score method to return the WER percentage from accumulated edit distance and reference length', 'review the WerScorer reset method to zero out accumulated distance and reference length counters']
```

Usage

```
{'create_WerScorerConfig': 'create a WerScorerConfig dataclass to configure WER evaluation with tokenizer, punctuation removal, and character level options', 'build_WerScorer': 'build a WerScorer instance that computes word error rate using editdistance and an EvaluationTokenizer', 'run_add_string': 'run add_string on a WerScorer to accumulate edit distance between reference and hypothesis strings', 'test_score': 'test the WerScorer score method to return the WER percentage from accumulated edit distance and reference length', 'review_reset': 'review the WerScorer reset method to zero out accumulated distance and reference length counters'}
```

