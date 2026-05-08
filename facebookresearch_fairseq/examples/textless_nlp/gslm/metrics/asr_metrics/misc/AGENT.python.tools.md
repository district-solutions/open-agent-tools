# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/textless_nlp/gslm/metrics/asr_metrics/misc/bleu_utils.py

Prompts

```
['calculate the corpus-level BLEU score for a list of hypotheses against their reference sentences', 'calculate the sentence-level BLEU score for a single hypothesis against its reference sentences', 'calculate BLEU score with no length penalty enabled for self-BLEU use cases', 'calculate BLEU score using arithmetic mean instead of geometric mean for averaging precision', 'calculate BLEU score with a custom smoothing function to handle zero-frequency n-gram issues', 'run the cut_as CLI tool to trim WAV audio files to match ground-truth lengths using a prompts description JSON', 'run the cut function to load a WAV file, trim it to a target length in seconds, and save the result', 'run the main function to process all WAV files in a samples directory against a prompts description JSON', 'review the cut function that loads audio with torchaudio, trims to target frames, and returns a length flag', 'review the get_args function that parses CLI arguments for samples directory, output directory, and prompts description']
```

Usage

```
{'calculate_corpus_bleu': 'calculate the corpus-level BLEU score for a list of hypotheses against their reference sentences', 'calculate_sentence_bleu': 'calculate the sentence-level BLEU score for a single hypothesis against its reference sentences', 'calculate_bleu_without_length_penalty': 'calculate BLEU score with no length penalty enabled for self-BLEU use cases', 'calculate_bleu_arithmetic_mean': 'calculate BLEU score using arithmetic mean instead of geometric mean for averaging precision', 'calculate_bleu_with_smoothing': 'calculate BLEU score with a custom smoothing function to handle zero-frequency n-gram issues'}
```

## File: facebookresearch_fairseq/examples/textless_nlp/gslm/metrics/asr_metrics/misc/cut_as.py

Prompts

```
['calculate the corpus-level BLEU score for a list of hypotheses against their reference sentences', 'calculate the sentence-level BLEU score for a single hypothesis against its reference sentences', 'calculate BLEU score with no length penalty enabled for self-BLEU use cases', 'calculate BLEU score using arithmetic mean instead of geometric mean for averaging precision', 'calculate BLEU score with a custom smoothing function to handle zero-frequency n-gram issues', 'run the cut_as CLI tool to trim WAV audio files to match ground-truth lengths using a prompts description JSON', 'run the cut function to load a WAV file, trim it to a target length in seconds, and save the result', 'run the main function to process all WAV files in a samples directory against a prompts description JSON', 'review the cut function that loads audio with torchaudio, trims to target frames, and returns a length flag', 'review the get_args function that parses CLI arguments for samples directory, output directory, and prompts description']
```

Usage

```
{'run_cut_as_cli': 'run the cut_as CLI tool to trim WAV audio files to match ground-truth lengths using a prompts description JSON', 'run_cut_function': 'run the cut function to load a WAV file, trim it to a target length in seconds, and save the result', 'run_main_function': 'run the main function to process all WAV files in a samples directory against a prompts description JSON', 'review_cut_function': 'review the cut function that loads audio with torchaudio, trims to target frames, and returns a length flag', 'review_get_args': 'review the get_args function that parses CLI arguments for samples directory, output directory, and prompts description'}
```

