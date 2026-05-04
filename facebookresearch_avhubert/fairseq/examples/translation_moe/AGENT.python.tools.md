# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/examples/translation_moe/score.py

Prompts

```
['run the scoring script with --sys flag to compute pairwise BLEU over candidate hypotheses', 'run the scoring script with --sys and --ref flags to compute multi-reference BLEU scores', 'run the scoring script with --ref flag alone to compute intra-reference pairwise and leave-one-out BLEU', 'run the scoring script with --sys and --output flags to merge source, target, and hypothesis outputs', 'run the scoring script to compute corpus-level BLEU scores using sacrebleu with no tokenization']
```

Usage

```
{'run_pairwise_bleu': 'run the scoring script with --sys flag to compute pairwise BLEU over candidate hypotheses', 'run_multi_ref_bleu': 'run the scoring script with --sys and --ref flags to compute multi-reference BLEU scores', 'run_intra_ref_bleu': 'run the scoring script with --ref flag alone to compute intra-reference pairwise and leave-one-out BLEU', 'run_merge_output': 'run the scoring script with --sys and --output flags to merge source, target, and hypothesis outputs', 'run_corpus_bleu': 'run the scoring script to compute corpus-level BLEU scores using sacrebleu with no tokenization'}
```

