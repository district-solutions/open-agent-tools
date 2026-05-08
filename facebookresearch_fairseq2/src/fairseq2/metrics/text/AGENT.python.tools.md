# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/src/fairseq2/metrics/text/bleu.py

Prompts

```
['create a BleuMetric instance with a sacrebleu tokenizer to compute BLEU scores', 'update the BleuMetric with reference and hypothesis sentence pairs for scoring', 'compute the final BLEU score tensor from accumulated n-gram counts and lengths', 'merge multiple BleuMetric instances by aggregating their n-gram counts and lengths', 'review the BleuMetric class that wraps sacrebleu BLEU as a torcheval Metric', 'create a ChrfMetric instance to compute chrF++ scores for text evaluation', 'update the ChrfMetric with reference and hypothesis text sequences', 'compute the final chrF++ score tensor from accumulated ChrfMetric statistics', 'merge multiple ChrfMetric instances to combine their accumulated statistics', 'review the ChrfMetric class and its chrF++ scoring implementation', 'create a WerMetric instance to compute Word Error Rate for speech recognition outputs', 'update the WerMetric with reference and hypothesis strings and their token sequences', 'compute the final word error rate and unit error rate from accumulated WerMetric state', 'merge multiple WerMetric instances to aggregate word error rate across distributed processes', 'review the WerMetric class that computes word and unit error rates using edit distance']
```

Usage

```
{'create_bleu_metric': 'create a BleuMetric instance with a sacrebleu tokenizer to compute BLEU scores', 'update_bleu_metric': 'update the BleuMetric with reference and hypothesis sentence pairs for scoring', 'compute_bleu_score': 'compute the final BLEU score tensor from accumulated n-gram counts and lengths', 'merge_bleu_metrics': 'merge multiple BleuMetric instances by aggregating their n-gram counts and lengths', 'review_bleu_metric_class': 'review the BleuMetric class that wraps sacrebleu BLEU as a torcheval Metric'}
```

## File: facebookresearch_fairseq2/src/fairseq2/metrics/text/chrf.py

Prompts

```
['create a BleuMetric instance with a sacrebleu tokenizer to compute BLEU scores', 'update the BleuMetric with reference and hypothesis sentence pairs for scoring', 'compute the final BLEU score tensor from accumulated n-gram counts and lengths', 'merge multiple BleuMetric instances by aggregating their n-gram counts and lengths', 'review the BleuMetric class that wraps sacrebleu BLEU as a torcheval Metric', 'create a ChrfMetric instance to compute chrF++ scores for text evaluation', 'update the ChrfMetric with reference and hypothesis text sequences', 'compute the final chrF++ score tensor from accumulated ChrfMetric statistics', 'merge multiple ChrfMetric instances to combine their accumulated statistics', 'review the ChrfMetric class and its chrF++ scoring implementation', 'create a WerMetric instance to compute Word Error Rate for speech recognition outputs', 'update the WerMetric with reference and hypothesis strings and their token sequences', 'compute the final word error rate and unit error rate from accumulated WerMetric state', 'merge multiple WerMetric instances to aggregate word error rate across distributed processes', 'review the WerMetric class that computes word and unit error rates using edit distance']
```

Usage

```
{'create_chrf_metric': 'create a ChrfMetric instance to compute chrF++ scores for text evaluation', 'update_chrf_with_refs_hyps': 'update the ChrfMetric with reference and hypothesis text sequences', 'compute_chrf_score': 'compute the final chrF++ score tensor from accumulated ChrfMetric statistics', 'merge_chrf_metrics': 'merge multiple ChrfMetric instances to combine their accumulated statistics', 'review_chrf_metric_class': 'review the ChrfMetric class and its chrF++ scoring implementation'}
```

## File: facebookresearch_fairseq2/src/fairseq2/metrics/text/wer.py

Prompts

```
['create a BleuMetric instance with a sacrebleu tokenizer to compute BLEU scores', 'update the BleuMetric with reference and hypothesis sentence pairs for scoring', 'compute the final BLEU score tensor from accumulated n-gram counts and lengths', 'merge multiple BleuMetric instances by aggregating their n-gram counts and lengths', 'review the BleuMetric class that wraps sacrebleu BLEU as a torcheval Metric', 'create a ChrfMetric instance to compute chrF++ scores for text evaluation', 'update the ChrfMetric with reference and hypothesis text sequences', 'compute the final chrF++ score tensor from accumulated ChrfMetric statistics', 'merge multiple ChrfMetric instances to combine their accumulated statistics', 'review the ChrfMetric class and its chrF++ scoring implementation', 'create a WerMetric instance to compute Word Error Rate for speech recognition outputs', 'update the WerMetric with reference and hypothesis strings and their token sequences', 'compute the final word error rate and unit error rate from accumulated WerMetric state', 'merge multiple WerMetric instances to aggregate word error rate across distributed processes', 'review the WerMetric class that computes word and unit error rates using edit distance']
```

Usage

```
{'create_WerMetric': 'create a WerMetric instance to compute Word Error Rate for speech recognition outputs', 'update_WerMetric': 'update the WerMetric with reference and hypothesis strings and their token sequences', 'compute_WerMetric': 'compute the final word error rate and unit error rate from accumulated WerMetric state', 'merge_WerMetric': 'merge multiple WerMetric instances to aggregate word error rate across distributed processes', 'review_WerMetric_class': 'review the WerMetric class that computes word and unit error rates using edit distance'}
```

