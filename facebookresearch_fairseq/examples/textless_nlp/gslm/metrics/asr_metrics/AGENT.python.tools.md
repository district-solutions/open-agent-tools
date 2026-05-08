# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/textless_nlp/gslm/metrics/asr_metrics/ppx.py

Prompts

```
['run the PPX metric evaluation on an ASR transcript file using a fairseq transformer language model', 'run get_target_sequences to extract target sequence IDs from a manifest and ground truth JSON file', 'run get_args to parse command line arguments for the PPX transcript evaluation script', 'review the main function that loads a language model, scores transcripts, and prints perplexity statistics', 'refactor the get_logprob inner function to compute mean negative positional scores from the language model', 'run the self/auto BLEU metrics CLI with --manifest and --prompts-description flags on ASR transcripts', 'compute the auto BLEU score for a single sentence using n-gram self-match with arithmetic or geometric weighting', 'compute self BLEU scores for a list of utterances by comparing each against all others', 'extract target sequence IDs from a manifest file filtered by ground truth durations', 'run all 8 self and auto BLEU metric variants in parallel across ASR transcript utterances']
```

Usage

```
{'run_ppx_evaluation': 'run the PPX metric evaluation on an ASR transcript file using a fairseq transformer language model', 'run_get_target_sequences': 'run get_target_sequences to extract target sequence IDs from a manifest and ground truth JSON file', 'run_get_args': 'run get_args to parse command line arguments for the PPX transcript evaluation script', 'review_main': 'review the main function that loads a language model, scores transcripts, and prints perplexity statistics', 'refactor_get_logprob': 'refactor the get_logprob inner function to compute mean negative positional scores from the language model'}
```

## File: facebookresearch_fairseq/examples/textless_nlp/gslm/metrics/asr_metrics/self_auto_bleu.py

Prompts

```
['run the PPX metric evaluation on an ASR transcript file using a fairseq transformer language model', 'run get_target_sequences to extract target sequence IDs from a manifest and ground truth JSON file', 'run get_args to parse command line arguments for the PPX transcript evaluation script', 'review the main function that loads a language model, scores transcripts, and prints perplexity statistics', 'refactor the get_logprob inner function to compute mean negative positional scores from the language model', 'run the self/auto BLEU metrics CLI with --manifest and --prompts-description flags on ASR transcripts', 'compute the auto BLEU score for a single sentence using n-gram self-match with arithmetic or geometric weighting', 'compute self BLEU scores for a list of utterances by comparing each against all others', 'extract target sequence IDs from a manifest file filtered by ground truth durations', 'run all 8 self and auto BLEU metric variants in parallel across ASR transcript utterances']
```

Usage

```
{'run_self_auto_bleu_cli': 'run the self/auto BLEU metrics CLI with --manifest and --prompts-description flags on ASR transcripts', 'compute_auto_bleu': 'compute the auto BLEU score for a single sentence using n-gram self-match with arithmetic or geometric weighting', 'compute_self_bleu': 'compute self BLEU scores for a list of utterances by comparing each against all others', 'get_target_sequences': 'extract target sequence IDs from a manifest file filtered by ground truth durations', 'run_all_bleu_metrics': 'run all 8 self and auto BLEU metric variants in parallel across ASR transcript utterances'}
```

