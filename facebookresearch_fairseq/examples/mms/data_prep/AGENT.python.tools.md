# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/mms/data_prep/align_and_segment.py

Prompts

```
['run the CLI tool to force-align and segment a long audio file using a transcript text file', 'generate log-softmax emissions from an audio file by running it through a wav2vec model in 30-second chunks', 'get forced alignment segments between audio emissions and tokenized transcript tokens using CTC forced alignment', 'review the generate_emissions function that processes audio in 30-second windows with 10% context overlap for model inference', 'refactor the get_alignments function to handle empty transcripts or missing dictionary tokens more gracefully', 'normalize text to lowercase ASCII with only letters, apostrophes, and spaces for uroman processing', 'run uroman perl script on normalized transcripts to convert text to romanized tokens for a given ISO language', 'merge consecutive repeated tokens in a CTC prediction path into labeled Segment objects with start and end indices', 'download and load a pretrained wav2vec2 CTC alignment model and its token dictionary for multilingual speech alignment', 'compute time-aligned token spans from CTC segments by matching token letters and padding with silence boundaries', 'normalize a text string by lowercasing, removing punctuation, digits, and extra spaces for a given ISO language code', 'normalize text and remove all bracketed content including those without numbers using the remove_brackets flag', 'normalize text for a given ISO code while preserving standalone digit words using remove_numbers false', 'normalize text for a given ISO code while preserving original case using lower_case false', 'review the text_normalize function to understand its normalization pipeline including unicode normalization, mapping, punctuation removal, and diacritic stripping']
```

Usage

```
{'run_align_and_segment': 'run the CLI tool to force-align and segment a long audio file using a transcript text file', 'generate_emissions': 'generate log-softmax emissions from an audio file by running it through a wav2vec model in 30-second chunks', 'get_alignments': 'get forced alignment segments between audio emissions and tokenized transcript tokens using CTC forced alignment', 'review_generate_emissions': 'review the generate_emissions function that processes audio in 30-second windows with 10% context overlap for model inference', 'refactor_get_alignments': 'refactor the get_alignments function to handle empty transcripts or missing dictionary tokens more gracefully'}
```

## File: facebookresearch_fairseq/examples/mms/data_prep/align_utils.py

Prompts

```
['run the CLI tool to force-align and segment a long audio file using a transcript text file', 'generate log-softmax emissions from an audio file by running it through a wav2vec model in 30-second chunks', 'get forced alignment segments between audio emissions and tokenized transcript tokens using CTC forced alignment', 'review the generate_emissions function that processes audio in 30-second windows with 10% context overlap for model inference', 'refactor the get_alignments function to handle empty transcripts or missing dictionary tokens more gracefully', 'normalize text to lowercase ASCII with only letters, apostrophes, and spaces for uroman processing', 'run uroman perl script on normalized transcripts to convert text to romanized tokens for a given ISO language', 'merge consecutive repeated tokens in a CTC prediction path into labeled Segment objects with start and end indices', 'download and load a pretrained wav2vec2 CTC alignment model and its token dictionary for multilingual speech alignment', 'compute time-aligned token spans from CTC segments by matching token letters and padding with silence boundaries', 'normalize a text string by lowercasing, removing punctuation, digits, and extra spaces for a given ISO language code', 'normalize text and remove all bracketed content including those without numbers using the remove_brackets flag', 'normalize text for a given ISO code while preserving standalone digit words using remove_numbers false', 'normalize text for a given ISO code while preserving original case using lower_case false', 'review the text_normalize function to understand its normalization pipeline including unicode normalization, mapping, punctuation removal, and diacritic stripping']
```

Usage

```
{'normalize_uroman_text': 'normalize text to lowercase ASCII with only letters, apostrophes, and spaces for uroman processing', 'get_uroman_tokens': 'run uroman perl script on normalized transcripts to convert text to romanized tokens for a given ISO language', 'merge_repeats_into_segments': 'merge consecutive repeated tokens in a CTC prediction path into labeled Segment objects with start and end indices', 'load_wav2vec2_model_and_dict': 'download and load a pretrained wav2vec2 CTC alignment model and its token dictionary for multilingual speech alignment', 'get_token_spans_from_segments': 'compute time-aligned token spans from CTC segments by matching token letters and padding with silence boundaries'}
```

## File: facebookresearch_fairseq/examples/mms/data_prep/text_normalization.py

Prompts

```
['run the CLI tool to force-align and segment a long audio file using a transcript text file', 'generate log-softmax emissions from an audio file by running it through a wav2vec model in 30-second chunks', 'get forced alignment segments between audio emissions and tokenized transcript tokens using CTC forced alignment', 'review the generate_emissions function that processes audio in 30-second windows with 10% context overlap for model inference', 'refactor the get_alignments function to handle empty transcripts or missing dictionary tokens more gracefully', 'normalize text to lowercase ASCII with only letters, apostrophes, and spaces for uroman processing', 'run uroman perl script on normalized transcripts to convert text to romanized tokens for a given ISO language', 'merge consecutive repeated tokens in a CTC prediction path into labeled Segment objects with start and end indices', 'download and load a pretrained wav2vec2 CTC alignment model and its token dictionary for multilingual speech alignment', 'compute time-aligned token spans from CTC segments by matching token letters and padding with silence boundaries', 'normalize a text string by lowercasing, removing punctuation, digits, and extra spaces for a given ISO language code', 'normalize text and remove all bracketed content including those without numbers using the remove_brackets flag', 'normalize text for a given ISO code while preserving standalone digit words using remove_numbers false', 'normalize text for a given ISO code while preserving original case using lower_case false', 'review the text_normalize function to understand its normalization pipeline including unicode normalization, mapping, punctuation removal, and diacritic stripping']
```

Usage

```
{'normalize_text': 'normalize a text string by lowercasing, removing punctuation, digits, and extra spaces for a given ISO language code', 'normalize_text_with_bracket_removal': 'normalize text and remove all bracketed content including those without numbers using the remove_brackets flag', 'normalize_text_keep_numbers': 'normalize text for a given ISO code while preserving standalone digit words using remove_numbers false', 'normalize_text_no_lowercase': 'normalize text for a given ISO code while preserving original case using lower_case false', 'review_text_normalize': 'review the text_normalize function to understand its normalization pipeline including unicode normalization, mapping, punctuation removal, and diacritic stripping'}
```

