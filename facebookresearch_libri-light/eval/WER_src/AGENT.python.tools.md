# Agent Python Tools

- repo: facebookresearch/libri-light
- repo_uri: https://github.com/facebookresearch/libri-light

## File: facebookresearch_libri-light/eval/WER_src/letter_ctc.py

Prompts

```
['build a LetterClassifier with a feature maker, encoder dimension, and letter count for CTC speech recognition', 'run the LetterClassifier forward pass on raw audio input to get letter predictions', 'build a CTCLetterCriterion with a letter classifier and letter count for computing CTC loss', 'run the CTCLetterCriterion forward pass with features, feature sizes, labels, and label sizes to compute loss', 'run cut_data to trim a sequence tensor to its maximum length based on sequence lengths', 'parse CTC labels from text files in a directory using a letters mapping file', 'find audio sequence files and their speakers in a directory by file extension', 'create a PyTorch Dataset that loads audio sequences and labels from a root directory', 'load and concatenate audio waveforms and labels into a single tensor for batching', 'retrieve a padded waveform and label pair by index from the dataset', 'create a Wav2Letter CTC decoder with KenLM, lexicon, and token dictionary for speech recognition', 'run the WlDecoder predictions method on emissions tensor to decode speech into text tokens', 'run the WlDecoder collapse method to deduplicate and remove blank tokens from a prediction list', 'review the WlDecoder constructor to understand how the trie, KenLM, and decoder options are configured', 'summarize the WlDecoder class and its CTC-based word-level decoding pipeline using wav2letter bindings']
```

Usage

```
{'build_LetterClassifier': 'build a LetterClassifier with a feature maker, encoder dimension, and letter count for CTC speech recognition', 'run_LetterClassifier_forward': 'run the LetterClassifier forward pass on raw audio input to get letter predictions', 'build_CTCLetterCriterion': 'build a CTCLetterCriterion with a letter classifier and letter count for computing CTC loss', 'run_CTCLetterCriterion_forward': 'run the CTCLetterCriterion forward pass with features, feature sizes, labels, and label sizes to compute loss', 'run_cut_data': 'run cut_data to trim a sequence tensor to its maximum length based on sequence lengths'}
```

## File: facebookresearch_libri-light/eval/WER_src/simple_dataset.py

Prompts

```
['build a LetterClassifier with a feature maker, encoder dimension, and letter count for CTC speech recognition', 'run the LetterClassifier forward pass on raw audio input to get letter predictions', 'build a CTCLetterCriterion with a letter classifier and letter count for computing CTC loss', 'run the CTCLetterCriterion forward pass with features, feature sizes, labels, and label sizes to compute loss', 'run cut_data to trim a sequence tensor to its maximum length based on sequence lengths', 'parse CTC labels from text files in a directory using a letters mapping file', 'find audio sequence files and their speakers in a directory by file extension', 'create a PyTorch Dataset that loads audio sequences and labels from a root directory', 'load and concatenate audio waveforms and labels into a single tensor for batching', 'retrieve a padded waveform and label pair by index from the dataset', 'create a Wav2Letter CTC decoder with KenLM, lexicon, and token dictionary for speech recognition', 'run the WlDecoder predictions method on emissions tensor to decode speech into text tokens', 'run the WlDecoder collapse method to deduplicate and remove blank tokens from a prediction list', 'review the WlDecoder constructor to understand how the trie, KenLM, and decoder options are configured', 'summarize the WlDecoder class and its CTC-based word-level decoding pipeline using wav2letter bindings']
```

Usage

```
{'parse_ctc_labels_from_root': 'parse CTC labels from text files in a directory using a letters mapping file', 'find_seqs': 'find audio sequence files and their speakers in a directory by file extension', 'create_SingleSequenceDataset': 'create a PyTorch Dataset that loads audio sequences and labels from a root directory', 'load_seqs_SingleSequenceDataset': 'load and concatenate audio waveforms and labels into a single tensor for batching', 'getitem_SingleSequenceDataset': 'retrieve a padded waveform and label pair by index from the dataset'}
```

## File: facebookresearch_libri-light/eval/WER_src/wl_decoder.py

Prompts

```
['build a LetterClassifier with a feature maker, encoder dimension, and letter count for CTC speech recognition', 'run the LetterClassifier forward pass on raw audio input to get letter predictions', 'build a CTCLetterCriterion with a letter classifier and letter count for computing CTC loss', 'run the CTCLetterCriterion forward pass with features, feature sizes, labels, and label sizes to compute loss', 'run cut_data to trim a sequence tensor to its maximum length based on sequence lengths', 'parse CTC labels from text files in a directory using a letters mapping file', 'find audio sequence files and their speakers in a directory by file extension', 'create a PyTorch Dataset that loads audio sequences and labels from a root directory', 'load and concatenate audio waveforms and labels into a single tensor for batching', 'retrieve a padded waveform and label pair by index from the dataset', 'create a Wav2Letter CTC decoder with KenLM, lexicon, and token dictionary for speech recognition', 'run the WlDecoder predictions method on emissions tensor to decode speech into text tokens', 'run the WlDecoder collapse method to deduplicate and remove blank tokens from a prediction list', 'review the WlDecoder constructor to understand how the trie, KenLM, and decoder options are configured', 'summarize the WlDecoder class and its CTC-based word-level decoding pipeline using wav2letter bindings']
```

Usage

```
{'create_WlDecoder': 'create a Wav2Letter CTC decoder with KenLM, lexicon, and token dictionary for speech recognition', 'run_WlDecoder_predictions': 'run the WlDecoder predictions method on emissions tensor to decode speech into text tokens', 'run_WlDecoder_collapse': 'run the WlDecoder collapse method to deduplicate and remove blank tokens from a prediction list', 'review_WlDecoder_init': 'review the WlDecoder constructor to understand how the trie, KenLM, and decoder options are configured', 'summarize_WlDecoder': 'summarize the WlDecoder class and its CTC-based word-level decoding pipeline using wav2letter bindings'}
```

