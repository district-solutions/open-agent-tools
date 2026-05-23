# Agent Python Tools

- repo: facebookresearch/stopes
- repo_uri: https://github.com/facebookresearch/stopes

## File: facebookresearch_stopes/stopes/eval/local_prosody/tests/test_emphasis_alignment.py

Prompts

```
['test the evaluate_emphasis_alignment function with source and target utterances using strong and weak word alignments', 'test creating Utterance objects with word lists and emphasis scores for prosody evaluation', 'test perfect emphasis alignment between German and French utterances with matching emphasized words', 'test incomplete recall when source has more emphasized words than target across aligned pairs', 'test incomplete precision when target has more emphasized words than source using weak alignment weight', 'test the Wav2Vec2ForcedAligner to verify it correctly predicts word-level timestamps from CTC emissions', 'run force_align_emission on a Wav2Vec2ForcedAligner with a pipe-separated transcript and emission tensor', 'create a Wav2Vec2ForcedAligner instance with a HuggingFace model name and target device', 'verify that forced alignment returns correct start and end timestamps for each word', 'decode emission tensor tokens using the aligner processor tokenizer to get ASR text', 'test the get_noncross_ratio function to compute the proportion of word alignment edges that do not cross a pause alignment edge', 'test the align_pauses function to find the most aligned pairs of pauses between source and target utterances', 'test compute_pause_alignment_metrics to evaluate pause alignment quality across pairs of source and target utterances', 'test the Utterance class get_pauses_after_words method to compute pause durations between consecutive words', 'test the CompareUtterancesConfig dataclass to configure pause alignment evaluation parameters for comparing utterance pairs', 'test that Utterance correctly computes net_duration as the sum of word speech durations', 'test that Utterance correctly computes trimmed_duration including pauses between words', 'test Utterance get_text_with_markup to insert pause annotations between words based on threshold', 'test creating an Utterance with word lists and corresponding start and end timestamps', 'test get_text_with_markup with different min_pause_duration thresholds to filter small pauses']
```

Usage

```
{'test_evaluate_emphasis_alignment': 'test the evaluate_emphasis_alignment function with source and target utterances using strong and weak word alignments', 'test_Utterance_creation': 'test creating Utterance objects with word lists and emphasis scores for prosody evaluation', 'test_emphasis_alignment_perfect': 'test perfect emphasis alignment between German and French utterances with matching emphasized words', 'test_emphasis_alignment_recall': 'test incomplete recall when source has more emphasized words than target across aligned pairs', 'test_emphasis_alignment_precision': 'test incomplete precision when target has more emphasized words than source using weak alignment weight'}
```

## File: facebookresearch_stopes/stopes/eval/local_prosody/tests/test_force_align.py

Prompts

```
['test the evaluate_emphasis_alignment function with source and target utterances using strong and weak word alignments', 'test creating Utterance objects with word lists and emphasis scores for prosody evaluation', 'test perfect emphasis alignment between German and French utterances with matching emphasized words', 'test incomplete recall when source has more emphasized words than target across aligned pairs', 'test incomplete precision when target has more emphasized words than source using weak alignment weight', 'test the Wav2Vec2ForcedAligner to verify it correctly predicts word-level timestamps from CTC emissions', 'run force_align_emission on a Wav2Vec2ForcedAligner with a pipe-separated transcript and emission tensor', 'create a Wav2Vec2ForcedAligner instance with a HuggingFace model name and target device', 'verify that forced alignment returns correct start and end timestamps for each word', 'decode emission tensor tokens using the aligner processor tokenizer to get ASR text', 'test the get_noncross_ratio function to compute the proportion of word alignment edges that do not cross a pause alignment edge', 'test the align_pauses function to find the most aligned pairs of pauses between source and target utterances', 'test compute_pause_alignment_metrics to evaluate pause alignment quality across pairs of source and target utterances', 'test the Utterance class get_pauses_after_words method to compute pause durations between consecutive words', 'test the CompareUtterancesConfig dataclass to configure pause alignment evaluation parameters for comparing utterance pairs', 'test that Utterance correctly computes net_duration as the sum of word speech durations', 'test that Utterance correctly computes trimmed_duration including pauses between words', 'test Utterance get_text_with_markup to insert pause annotations between words based on threshold', 'test creating an Utterance with word lists and corresponding start and end timestamps', 'test get_text_with_markup with different min_pause_duration thresholds to filter small pauses']
```

Usage

```
{'test_force_aligner': 'test the Wav2Vec2ForcedAligner to verify it correctly predicts word-level timestamps from CTC emissions', 'run_force_align_emission': 'run force_align_emission on a Wav2Vec2ForcedAligner with a pipe-separated transcript and emission tensor', 'create_wav2vec2_aligner': 'create a Wav2Vec2ForcedAligner instance with a HuggingFace model name and target device', 'verify_alignment_timestamps': 'verify that forced alignment returns correct start and end timestamps for each word', 'decode_emission_tokens': 'decode emission tensor tokens using the aligner processor tokenizer to get ASR text'}
```

## File: facebookresearch_stopes/stopes/eval/local_prosody/tests/test_pause_alignment.py

Prompts

```
['test the evaluate_emphasis_alignment function with source and target utterances using strong and weak word alignments', 'test creating Utterance objects with word lists and emphasis scores for prosody evaluation', 'test perfect emphasis alignment between German and French utterances with matching emphasized words', 'test incomplete recall when source has more emphasized words than target across aligned pairs', 'test incomplete precision when target has more emphasized words than source using weak alignment weight', 'test the Wav2Vec2ForcedAligner to verify it correctly predicts word-level timestamps from CTC emissions', 'run force_align_emission on a Wav2Vec2ForcedAligner with a pipe-separated transcript and emission tensor', 'create a Wav2Vec2ForcedAligner instance with a HuggingFace model name and target device', 'verify that forced alignment returns correct start and end timestamps for each word', 'decode emission tensor tokens using the aligner processor tokenizer to get ASR text', 'test the get_noncross_ratio function to compute the proportion of word alignment edges that do not cross a pause alignment edge', 'test the align_pauses function to find the most aligned pairs of pauses between source and target utterances', 'test compute_pause_alignment_metrics to evaluate pause alignment quality across pairs of source and target utterances', 'test the Utterance class get_pauses_after_words method to compute pause durations between consecutive words', 'test the CompareUtterancesConfig dataclass to configure pause alignment evaluation parameters for comparing utterance pairs', 'test that Utterance correctly computes net_duration as the sum of word speech durations', 'test that Utterance correctly computes trimmed_duration including pauses between words', 'test Utterance get_text_with_markup to insert pause annotations between words based on threshold', 'test creating an Utterance with word lists and corresponding start and end timestamps', 'test get_text_with_markup with different min_pause_duration thresholds to filter small pauses']
```

Usage

```
{'test_get_noncross_ratio': 'test the get_noncross_ratio function to compute the proportion of word alignment edges that do not cross a pause alignment edge', 'test_align_pauses': 'test the align_pauses function to find the most aligned pairs of pauses between source and target utterances', 'test_compute_pause_alignment_metrics': 'test compute_pause_alignment_metrics to evaluate pause alignment quality across pairs of source and target utterances', 'test_Utterance_get_pauses_after_words': 'test the Utterance class get_pauses_after_words method to compute pause durations between consecutive words', 'test_CompareUtterancesConfig': 'test the CompareUtterancesConfig dataclass to configure pause alignment evaluation parameters for comparing utterance pairs'}
```

## File: facebookresearch_stopes/stopes/eval/local_prosody/tests/test_utterance.py

Prompts

```
['test the evaluate_emphasis_alignment function with source and target utterances using strong and weak word alignments', 'test creating Utterance objects with word lists and emphasis scores for prosody evaluation', 'test perfect emphasis alignment between German and French utterances with matching emphasized words', 'test incomplete recall when source has more emphasized words than target across aligned pairs', 'test incomplete precision when target has more emphasized words than source using weak alignment weight', 'test the Wav2Vec2ForcedAligner to verify it correctly predicts word-level timestamps from CTC emissions', 'run force_align_emission on a Wav2Vec2ForcedAligner with a pipe-separated transcript and emission tensor', 'create a Wav2Vec2ForcedAligner instance with a HuggingFace model name and target device', 'verify that forced alignment returns correct start and end timestamps for each word', 'decode emission tensor tokens using the aligner processor tokenizer to get ASR text', 'test the get_noncross_ratio function to compute the proportion of word alignment edges that do not cross a pause alignment edge', 'test the align_pauses function to find the most aligned pairs of pauses between source and target utterances', 'test compute_pause_alignment_metrics to evaluate pause alignment quality across pairs of source and target utterances', 'test the Utterance class get_pauses_after_words method to compute pause durations between consecutive words', 'test the CompareUtterancesConfig dataclass to configure pause alignment evaluation parameters for comparing utterance pairs', 'test that Utterance correctly computes net_duration as the sum of word speech durations', 'test that Utterance correctly computes trimmed_duration including pauses between words', 'test Utterance get_text_with_markup to insert pause annotations between words based on threshold', 'test creating an Utterance with word lists and corresponding start and end timestamps', 'test get_text_with_markup with different min_pause_duration thresholds to filter small pauses']
```

Usage

```
{'test_utterance_net_duration': 'test that Utterance correctly computes net_duration as the sum of word speech durations', 'test_utterance_trimmed_duration': 'test that Utterance correctly computes trimmed_duration including pauses between words', 'test_get_text_with_markup': 'test Utterance get_text_with_markup to insert pause annotations between words based on threshold', 'test_utterance_construction': 'test creating an Utterance with word lists and corresponding start and end timestamps', 'test_get_text_with_markup_thresholds': 'test get_text_with_markup with different min_pause_duration thresholds to filter small pauses'}
```

