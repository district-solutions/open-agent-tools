# Agent Python Tools

- repo: facebookresearch/editeval
- repo_uri: https://github.com/facebookresearch/editeval

## File: facebookresearch_editeval/src/metrics/custom_metrics.py

Prompts

```
['run ExactMatchDiffMetric.evaluate to score predictions against targets using diff overlap', 'run ExactMatchMetric.evaluate to compute the fraction of predictions matching any target', 'run InsertDeleteMetric.evaluate to score insertions and deletions using n-gram overlap', 'run EasseSariMetric.evaluate to compute SARI scores for sentence editing predictions', 'run iBLEUMetric.evaluate to compute iBLEU scores balancing reference BLEU and input BLEU', 'normalize a sentence using the 13a tokenizer with lowercase enabled', 'normalize a sentence using the Moses tokenizer for NLP preprocessing', 'normalize a sentence using the Penn tokenizer for tokenization', 'normalize a sentence using the international tokenizer V14', 'normalize a sentence and return tokens as a list instead of a string', 'compute the SARI score for a corpus of original, system, and reference sentences', 'extract n-grams from a sentence and return a list of counters per n-gram order', 'compute n-gram addition, keeping, and deletion statistics for sentence pairs with references', 'compute micro-averaged SARI scores for addition, keeping, and deletion operations across n-gram orders', 'compute macro-averaged SARI scores for addition, keeping, and deletion operations across n-gram orders', 'run GLEU scoring iterations on tokenized hypotheses against multiple reference sentences', 'load tokenized reference sentences into the GLEU calculator for n-gram comparison', 'load tokenized source input sentences into the GLEU calculator for n-gram extraction', 'compute n-gram counts of a given order for a tokenized sentence using GLEU', 'calculate the GLEU score from collected BLEU-relevant statistics with optional smoothing', 'run update_rouge to measure ROUGE-1, ROUGE-2, and ROUGE-Lsum scores on text edit predictions', 'run extract_additions to find text added between a source and target string', 'test update_rouge with source, target, and prediction lists to evaluate edit quality', 'test extract_additions with source and target strings to verify added text extraction', 'refactor update_rouge to customize ROUGE metrics or add new scoring variants']
```

Usage

```
{'run_exact_match_diff_metric': 'run ExactMatchDiffMetric.evaluate to score predictions against targets using diff overlap', 'run_exact_match_metric': 'run ExactMatchMetric.evaluate to compute the fraction of predictions matching any target', 'run_insert_delete_metric': 'run InsertDeleteMetric.evaluate to score insertions and deletions using n-gram overlap', 'run_easse_sari_metric': 'run EasseSariMetric.evaluate to compute SARI scores for sentence editing predictions', 'run_ibleu_metric': 'run iBLEUMetric.evaluate to compute iBLEU scores balancing reference BLEU and input BLEU'}
```

## File: facebookresearch_editeval/src/metrics/easse_preprocessing.py

Prompts

```
['run ExactMatchDiffMetric.evaluate to score predictions against targets using diff overlap', 'run ExactMatchMetric.evaluate to compute the fraction of predictions matching any target', 'run InsertDeleteMetric.evaluate to score insertions and deletions using n-gram overlap', 'run EasseSariMetric.evaluate to compute SARI scores for sentence editing predictions', 'run iBLEUMetric.evaluate to compute iBLEU scores balancing reference BLEU and input BLEU', 'normalize a sentence using the 13a tokenizer with lowercase enabled', 'normalize a sentence using the Moses tokenizer for NLP preprocessing', 'normalize a sentence using the Penn tokenizer for tokenization', 'normalize a sentence using the international tokenizer V14', 'normalize a sentence and return tokens as a list instead of a string', 'compute the SARI score for a corpus of original, system, and reference sentences', 'extract n-grams from a sentence and return a list of counters per n-gram order', 'compute n-gram addition, keeping, and deletion statistics for sentence pairs with references', 'compute micro-averaged SARI scores for addition, keeping, and deletion operations across n-gram orders', 'compute macro-averaged SARI scores for addition, keeping, and deletion operations across n-gram orders', 'run GLEU scoring iterations on tokenized hypotheses against multiple reference sentences', 'load tokenized reference sentences into the GLEU calculator for n-gram comparison', 'load tokenized source input sentences into the GLEU calculator for n-gram extraction', 'compute n-gram counts of a given order for a tokenized sentence using GLEU', 'calculate the GLEU score from collected BLEU-relevant statistics with optional smoothing', 'run update_rouge to measure ROUGE-1, ROUGE-2, and ROUGE-Lsum scores on text edit predictions', 'run extract_additions to find text added between a source and target string', 'test update_rouge with source, target, and prediction lists to evaluate edit quality', 'test extract_additions with source and target strings to verify added text extraction', 'refactor update_rouge to customize ROUGE metrics or add new scoring variants']
```

Usage

```
{'normalize_sentence_13a': 'normalize a sentence using the 13a tokenizer with lowercase enabled', 'normalize_sentence_moses': 'normalize a sentence using the Moses tokenizer for NLP preprocessing', 'normalize_sentence_penn': 'normalize a sentence using the Penn tokenizer for tokenization', 'normalize_sentence_intl': 'normalize a sentence using the international tokenizer V14', 'normalize_sentence_token_list': 'normalize a sentence and return tokens as a list instead of a string'}
```

## File: facebookresearch_editeval/src/metrics/easse_sari.py

Prompts

```
['run ExactMatchDiffMetric.evaluate to score predictions against targets using diff overlap', 'run ExactMatchMetric.evaluate to compute the fraction of predictions matching any target', 'run InsertDeleteMetric.evaluate to score insertions and deletions using n-gram overlap', 'run EasseSariMetric.evaluate to compute SARI scores for sentence editing predictions', 'run iBLEUMetric.evaluate to compute iBLEU scores balancing reference BLEU and input BLEU', 'normalize a sentence using the 13a tokenizer with lowercase enabled', 'normalize a sentence using the Moses tokenizer for NLP preprocessing', 'normalize a sentence using the Penn tokenizer for tokenization', 'normalize a sentence using the international tokenizer V14', 'normalize a sentence and return tokens as a list instead of a string', 'compute the SARI score for a corpus of original, system, and reference sentences', 'extract n-grams from a sentence and return a list of counters per n-gram order', 'compute n-gram addition, keeping, and deletion statistics for sentence pairs with references', 'compute micro-averaged SARI scores for addition, keeping, and deletion operations across n-gram orders', 'compute macro-averaged SARI scores for addition, keeping, and deletion operations across n-gram orders', 'run GLEU scoring iterations on tokenized hypotheses against multiple reference sentences', 'load tokenized reference sentences into the GLEU calculator for n-gram comparison', 'load tokenized source input sentences into the GLEU calculator for n-gram extraction', 'compute n-gram counts of a given order for a tokenized sentence using GLEU', 'calculate the GLEU score from collected BLEU-relevant statistics with optional smoothing', 'run update_rouge to measure ROUGE-1, ROUGE-2, and ROUGE-Lsum scores on text edit predictions', 'run extract_additions to find text added between a source and target string', 'test update_rouge with source, target, and prediction lists to evaluate edit quality', 'test extract_additions with source and target strings to verify added text extraction', 'refactor update_rouge to customize ROUGE metrics or add new scoring variants']
```

Usage

```
{'compute_corpus_sari': 'compute the SARI score for a corpus of original, system, and reference sentences', 'extract_ngrams': 'extract n-grams from a sentence and return a list of counters per n-gram order', 'compute_ngram_stats': 'compute n-gram addition, keeping, and deletion statistics for sentence pairs with references', 'compute_micro_sari': 'compute micro-averaged SARI scores for addition, keeping, and deletion operations across n-gram orders', 'compute_macro_sari': 'compute macro-averaged SARI scores for addition, keeping, and deletion operations across n-gram orders'}
```

## File: facebookresearch_editeval/src/metrics/gleu.py

Prompts

```
['run ExactMatchDiffMetric.evaluate to score predictions against targets using diff overlap', 'run ExactMatchMetric.evaluate to compute the fraction of predictions matching any target', 'run InsertDeleteMetric.evaluate to score insertions and deletions using n-gram overlap', 'run EasseSariMetric.evaluate to compute SARI scores for sentence editing predictions', 'run iBLEUMetric.evaluate to compute iBLEU scores balancing reference BLEU and input BLEU', 'normalize a sentence using the 13a tokenizer with lowercase enabled', 'normalize a sentence using the Moses tokenizer for NLP preprocessing', 'normalize a sentence using the Penn tokenizer for tokenization', 'normalize a sentence using the international tokenizer V14', 'normalize a sentence and return tokens as a list instead of a string', 'compute the SARI score for a corpus of original, system, and reference sentences', 'extract n-grams from a sentence and return a list of counters per n-gram order', 'compute n-gram addition, keeping, and deletion statistics for sentence pairs with references', 'compute micro-averaged SARI scores for addition, keeping, and deletion operations across n-gram orders', 'compute macro-averaged SARI scores for addition, keeping, and deletion operations across n-gram orders', 'run GLEU scoring iterations on tokenized hypotheses against multiple reference sentences', 'load tokenized reference sentences into the GLEU calculator for n-gram comparison', 'load tokenized source input sentences into the GLEU calculator for n-gram extraction', 'compute n-gram counts of a given order for a tokenized sentence using GLEU', 'calculate the GLEU score from collected BLEU-relevant statistics with optional smoothing', 'run update_rouge to measure ROUGE-1, ROUGE-2, and ROUGE-Lsum scores on text edit predictions', 'run extract_additions to find text added between a source and target string', 'test update_rouge with source, target, and prediction lists to evaluate edit quality', 'test extract_additions with source and target strings to verify added text extraction', 'refactor update_rouge to customize ROUGE metrics or add new scoring variants']
```

Usage

```
{'run_GLEU_iterations': 'run GLEU scoring iterations on tokenized hypotheses against multiple reference sentences', 'load_references_GLEU': 'load tokenized reference sentences into the GLEU calculator for n-gram comparison', 'load_inputs_GLEU': 'load tokenized source input sentences into the GLEU calculator for n-gram extraction', 'compute_ngram_counts': 'compute n-gram counts of a given order for a tokenized sentence using GLEU', 'calculate_gleu_score': 'calculate the GLEU score from collected BLEU-relevant statistics with optional smoothing'}
```

## File: facebookresearch_editeval/src/metrics/update_rouge.py

Prompts

```
['run ExactMatchDiffMetric.evaluate to score predictions against targets using diff overlap', 'run ExactMatchMetric.evaluate to compute the fraction of predictions matching any target', 'run InsertDeleteMetric.evaluate to score insertions and deletions using n-gram overlap', 'run EasseSariMetric.evaluate to compute SARI scores for sentence editing predictions', 'run iBLEUMetric.evaluate to compute iBLEU scores balancing reference BLEU and input BLEU', 'normalize a sentence using the 13a tokenizer with lowercase enabled', 'normalize a sentence using the Moses tokenizer for NLP preprocessing', 'normalize a sentence using the Penn tokenizer for tokenization', 'normalize a sentence using the international tokenizer V14', 'normalize a sentence and return tokens as a list instead of a string', 'compute the SARI score for a corpus of original, system, and reference sentences', 'extract n-grams from a sentence and return a list of counters per n-gram order', 'compute n-gram addition, keeping, and deletion statistics for sentence pairs with references', 'compute micro-averaged SARI scores for addition, keeping, and deletion operations across n-gram orders', 'compute macro-averaged SARI scores for addition, keeping, and deletion operations across n-gram orders', 'run GLEU scoring iterations on tokenized hypotheses against multiple reference sentences', 'load tokenized reference sentences into the GLEU calculator for n-gram comparison', 'load tokenized source input sentences into the GLEU calculator for n-gram extraction', 'compute n-gram counts of a given order for a tokenized sentence using GLEU', 'calculate the GLEU score from collected BLEU-relevant statistics with optional smoothing', 'run update_rouge to measure ROUGE-1, ROUGE-2, and ROUGE-Lsum scores on text edit predictions', 'run extract_additions to find text added between a source and target string', 'test update_rouge with source, target, and prediction lists to evaluate edit quality', 'test extract_additions with source and target strings to verify added text extraction', 'refactor update_rouge to customize ROUGE metrics or add new scoring variants']
```

Usage

```
{'run_update_rouge': 'run update_rouge to measure ROUGE-1, ROUGE-2, and ROUGE-Lsum scores on text edit predictions', 'run_extract_additions': 'run extract_additions to find text added between a source and target string', 'test_update_rouge': 'test update_rouge with source, target, and prediction lists to evaluate edit quality', 'test_extract_additions': 'test extract_additions with source and target strings to verify added text extraction', 'refactor_update_rouge': 'refactor update_rouge to customize ROUGE metrics or add new scoring variants'}
```

