# Agent Python Tools

- repo: facebookresearch/stopes
- repo_uri: https://github.com/facebookresearch/stopes

## File: facebookresearch_stopes/stopes/eval/alti/alti_metrics/alti_metrics_utils.py

Prompts

```
['compute ALTI sentence-level metrics and alignments for a batch of source-target text pairs using a FairseqTransformerHub model', 'compute the ALTI+ contribution matrix and tokenized sentences for a source-target text pair using an NLLB-like seq2seq model', 'compute sentence-level alignment quality metrics from an ALTI contribution matrix including hallucination and undertranslation detection scores', 'compute cross-entropy loss for a source-target text pair using a FairseqTransformerHub model and return average and total loss values', 'aggregate token-level ALTI contributions and tokens up to the word level using alignment-based token-to-word grouping', 'create a python module that reads a TSV file with named columns and returns a list of row dicts', 'create a function that reads a TSV file without headers and returns rows indexed by column number', 'build a python module that writes a list of dicts to a TSV file with headers', 'create a function that selects specific columns from a list of dicts by their column IDs', 'build a python module that joins multiple lists of dicts by merging corresponding elements', 'load an NLLB multilingual model from a Fairseq checkpoint for ALTI attribution analysis', 'load a bilingual Fairseq translation model from a checkpoint for ALTI hub inference', 'create an ALTIMetricsConfig dataclass to configure model paths, language codes, and output file locations', 'compute ALTI attribution scores for source-target sentence pairs using an NLLB model and save metrics', 'reference the NLLB200 language codes string containing all 200 supported language-script pairs']
```

Usage

```
{'compute_alti_scores_for_batch': 'compute ALTI sentence-level metrics and alignments for a batch of source-target text pairs using a FairseqTransformerHub model', 'compute_alti_nllb': 'compute the ALTI+ contribution matrix and tokenized sentences for a source-target text pair using an NLLB-like seq2seq model', 'compute_alti_metrics': 'compute sentence-level alignment quality metrics from an ALTI contribution matrix including hallucination and undertranslation detection scores', 'get_loss': 'compute cross-entropy loss for a source-target text pair using a FairseqTransformerHub model and return average and total loss values', 'alti_to_word': 'aggregate token-level ALTI contributions and tokens up to the word level using alignment-based token-to-word grouping'}
```

## File: facebookresearch_stopes/stopes/eval/alti/alti_metrics/file_utils.py

Prompts

```
['compute ALTI sentence-level metrics and alignments for a batch of source-target text pairs using a FairseqTransformerHub model', 'compute the ALTI+ contribution matrix and tokenized sentences for a source-target text pair using an NLLB-like seq2seq model', 'compute sentence-level alignment quality metrics from an ALTI contribution matrix including hallucination and undertranslation detection scores', 'compute cross-entropy loss for a source-target text pair using a FairseqTransformerHub model and return average and total loss values', 'aggregate token-level ALTI contributions and tokens up to the word level using alignment-based token-to-word grouping', 'create a python module that reads a TSV file with named columns and returns a list of row dicts', 'create a function that reads a TSV file without headers and returns rows indexed by column number', 'build a python module that writes a list of dicts to a TSV file with headers', 'create a function that selects specific columns from a list of dicts by their column IDs', 'build a python module that joins multiple lists of dicts by merging corresponding elements', 'load an NLLB multilingual model from a Fairseq checkpoint for ALTI attribution analysis', 'load a bilingual Fairseq translation model from a checkpoint for ALTI hub inference', 'create an ALTIMetricsConfig dataclass to configure model paths, language codes, and output file locations', 'compute ALTI attribution scores for source-target sentence pairs using an NLLB model and save metrics', 'reference the NLLB200 language codes string containing all 200 supported language-script pairs']
```

Usage

```
{'read_tsv_named': 'create a python module that reads a TSV file with named columns and returns a list of row dicts', 'read_tsv_unnamed': 'create a function that reads a TSV file without headers and returns rows indexed by column number', 'write_tsv': 'build a python module that writes a list of dicts to a TSV file with headers', 'select_columns': 'create a function that selects specific columns from a list of dicts by their column IDs', 'join_lists_of_dicts': 'build a python module that joins multiple lists of dicts by merging corresponding elements'}
```

## File: facebookresearch_stopes/stopes/eval/alti/alti_metrics/nllb_alti_detector.py

Prompts

```
['compute ALTI sentence-level metrics and alignments for a batch of source-target text pairs using a FairseqTransformerHub model', 'compute the ALTI+ contribution matrix and tokenized sentences for a source-target text pair using an NLLB-like seq2seq model', 'compute sentence-level alignment quality metrics from an ALTI contribution matrix including hallucination and undertranslation detection scores', 'compute cross-entropy loss for a source-target text pair using a FairseqTransformerHub model and return average and total loss values', 'aggregate token-level ALTI contributions and tokens up to the word level using alignment-based token-to-word grouping', 'create a python module that reads a TSV file with named columns and returns a list of row dicts', 'create a function that reads a TSV file without headers and returns rows indexed by column number', 'build a python module that writes a list of dicts to a TSV file with headers', 'create a function that selects specific columns from a list of dicts by their column IDs', 'build a python module that joins multiple lists of dicts by merging corresponding elements', 'load an NLLB multilingual model from a Fairseq checkpoint for ALTI attribution analysis', 'load a bilingual Fairseq translation model from a checkpoint for ALTI hub inference', 'create an ALTIMetricsConfig dataclass to configure model paths, language codes, and output file locations', 'compute ALTI attribution scores for source-target sentence pairs using an NLLB model and save metrics', 'reference the NLLB200 language codes string containing all 200 supported language-script pairs']
```

Usage

```
{'load_nllb_model': 'load an NLLB multilingual model from a Fairseq checkpoint for ALTI attribution analysis', 'load_bilingual_model': 'load a bilingual Fairseq translation model from a checkpoint for ALTI hub inference', 'ALTIMetricsConfig': 'create an ALTIMetricsConfig dataclass to configure model paths, language codes, and output file locations', 'compute_nllb_alti': 'compute ALTI attribution scores for source-target sentence pairs using an NLLB model and save metrics', 'NLLB200_LANGS': 'reference the NLLB200 language codes string containing all 200 supported language-script pairs'}
```

