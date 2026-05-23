# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/tests/unit/generation/test_step_processor.py

Prompts

```
['test NGramRepeatBlockProcessor to block repeated n-grams in generated sequences by zeroing their probabilities', 'test NGramRepeatBlockProcessor with ngram_size 1 to block any previously generated token from repeating', 'test NGramRepeatBlockProcessor handles sequences shorter than ngram_size without modifying probabilities', 'create an NGramRepeatBlockProcessor with a given ngram_size to prevent n-gram repetition during generation', 'review the StepProcessor protocol that defines the call interface for processing next-step probabilities during generation']
```

Usage

```
{'test_NGramRepeatBlockProcessor_ngram_blocking': 'test NGramRepeatBlockProcessor to block repeated n-grams in generated sequences by zeroing their probabilities', 'test_NGramRepeatBlockProcessor_unigram_blocking': 'test NGramRepeatBlockProcessor with ngram_size 1 to block any previously generated token from repeating', 'test_NGramRepeatBlockProcessor_short_sequences': 'test NGramRepeatBlockProcessor handles sequences shorter than ngram_size without modifying probabilities', 'create_NGramRepeatBlockProcessor_instance': 'create an NGramRepeatBlockProcessor with a given ngram_size to prevent n-gram repetition during generation', 'review_StepProcessor_protocol': 'review the StepProcessor protocol that defines the call interface for processing next-step probabilities during generation'}
```

