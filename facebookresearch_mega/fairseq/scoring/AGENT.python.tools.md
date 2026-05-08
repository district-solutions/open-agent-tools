# Agent Python Tools

- repo: facebookresearch/mega
- repo_uri: https://github.com/facebookresearch/mega

## File: facebookresearch_mega/fairseq/scoring/bleu.py

Prompts

```
['create a SacrebleuScorer instance to score translation hypotheses against references using sacrebleu', 'add a reference and prediction string pair to the SacrebleuScorer for corpus-level BLEU scoring', 'create a Scorer instance with pad, eos, and unk token IDs for BLEU scoring', 'add a reference and prediction torch.IntTensor pair to the BLEU Scorer for n-gram matching', 'score the BLEU metric with a given n-gram order and return the brevity-penalized score', 'build a python module using WerScorer to compute word error rate between reference and predicted text', 'create a function that adds reference and prediction string pairs to a WerScorer instance for WER calculation', 'test the WerScorer score method to return word error rate as a percentage value', 'refactor the WerScorer reset method to clear accumulated distance and reference length counters', 'summarize the WerScorer result_string method that returns a formatted WER percentage string']
```

Usage

```
{'create_sacrebleu_scorer': 'create a SacrebleuScorer instance to score translation hypotheses against references using sacrebleu', 'add_string_to_sacrebleu': 'add a reference and prediction string pair to the SacrebleuScorer for corpus-level BLEU scoring', 'create_bleu_scorer': 'create a Scorer instance with pad, eos, and unk token IDs for BLEU scoring', 'add_tensor_pair_to_scorer': 'add a reference and prediction torch.IntTensor pair to the BLEU Scorer for n-gram matching', 'score_bleu': 'score the BLEU metric with a given n-gram order and return the brevity-penalized score'}
```

## File: facebookresearch_mega/fairseq/scoring/wer.py

Prompts

```
['create a SacrebleuScorer instance to score translation hypotheses against references using sacrebleu', 'add a reference and prediction string pair to the SacrebleuScorer for corpus-level BLEU scoring', 'create a Scorer instance with pad, eos, and unk token IDs for BLEU scoring', 'add a reference and prediction torch.IntTensor pair to the BLEU Scorer for n-gram matching', 'score the BLEU metric with a given n-gram order and return the brevity-penalized score', 'build a python module using WerScorer to compute word error rate between reference and predicted text', 'create a function that adds reference and prediction string pairs to a WerScorer instance for WER calculation', 'test the WerScorer score method to return word error rate as a percentage value', 'refactor the WerScorer reset method to clear accumulated distance and reference length counters', 'summarize the WerScorer result_string method that returns a formatted WER percentage string']
```

Usage

```
{'build_wer_scorer': 'build a python module using WerScorer to compute word error rate between reference and predicted text', 'create_add_string': 'create a function that adds reference and prediction string pairs to a WerScorer instance for WER calculation', 'test_score': 'test the WerScorer score method to return word error rate as a percentage value', 'refactor_reset': 'refactor the WerScorer reset method to clear accumulated distance and reference length counters', 'summarize_result_string': 'summarize the WerScorer result_string method that returns a formatted WER percentage string'}
```

