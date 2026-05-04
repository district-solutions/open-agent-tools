# Agent Python Tools

- repo: facebookresearch/emg2qwerty
- repo_uri: https://github.com/facebookresearch/emg2qwerty

## File: facebookresearch_emg2qwerty/emg2qwerty/tests/charset_test.py

Prompts

```
['test the charset clean_str function to normalize unicode and special characters', 'test the charset str_to_keys function to convert strings to pynput key representations', 'test the charset keys_to_str function to convert pynput keys back to strings', 'test the charset str_to_labels roundtrip conversion for model training class labels', 'run all charset test cases to verify string key and label conversion correctness', 'test LabelData.from_str to create label data from a text string', 'test LabelData.from_labels to create label data from a list of integer labels', 'test concatenating two LabelData instances using the plus operator', 'test equality comparison between two LabelData instances', 'test accessing the text and labels properties of a LabelData instance', 'test the CTCGreedyDecoder to decode emissions into text using the decode API', 'test the CTCGreedyDecoder decode_batch API for batched decoding of multiple emission sequences', 'test the BeamState class initialization and label node operations without a language model', 'test the CTCBeamDecoder to verify correct onset timestamp tracking across beam search paths', 'test the CTCBeamDecoder LM scoring with delete key handling and insertion bonus']
```

Usage

```
{'test_clean_str': 'test the charset clean_str function to normalize unicode and special characters', 'test_str_to_keys': 'test the charset str_to_keys function to convert strings to pynput key representations', 'test_keys_to_str': 'test the charset keys_to_str function to convert pynput keys back to strings', 'test_str_to_labels': 'test the charset str_to_labels roundtrip conversion for model training class labels', 'run_charset_tests': 'run all charset test cases to verify string key and label conversion correctness'}
```

## File: facebookresearch_emg2qwerty/emg2qwerty/tests/data_test.py

Prompts

```
['test the charset clean_str function to normalize unicode and special characters', 'test the charset str_to_keys function to convert strings to pynput key representations', 'test the charset keys_to_str function to convert pynput keys back to strings', 'test the charset str_to_labels roundtrip conversion for model training class labels', 'run all charset test cases to verify string key and label conversion correctness', 'test LabelData.from_str to create label data from a text string', 'test LabelData.from_labels to create label data from a list of integer labels', 'test concatenating two LabelData instances using the plus operator', 'test equality comparison between two LabelData instances', 'test accessing the text and labels properties of a LabelData instance', 'test the CTCGreedyDecoder to decode emissions into text using the decode API', 'test the CTCGreedyDecoder decode_batch API for batched decoding of multiple emission sequences', 'test the BeamState class initialization and label node operations without a language model', 'test the CTCBeamDecoder to verify correct onset timestamp tracking across beam search paths', 'test the CTCBeamDecoder LM scoring with delete key handling and insertion bonus']
```

Usage

```
{'test_LabelData_from_str': 'test LabelData.from_str to create label data from a text string', 'test_LabelData_from_labels': 'test LabelData.from_labels to create label data from a list of integer labels', 'test_LabelData_concatenation': 'test concatenating two LabelData instances using the plus operator', 'test_LabelData_equality': 'test equality comparison between two LabelData instances', 'test_LabelData_text_and_labels': 'test accessing the text and labels properties of a LabelData instance'}
```

## File: facebookresearch_emg2qwerty/emg2qwerty/tests/decoder_test.py

Prompts

```
['test the charset clean_str function to normalize unicode and special characters', 'test the charset str_to_keys function to convert strings to pynput key representations', 'test the charset keys_to_str function to convert pynput keys back to strings', 'test the charset str_to_labels roundtrip conversion for model training class labels', 'run all charset test cases to verify string key and label conversion correctness', 'test LabelData.from_str to create label data from a text string', 'test LabelData.from_labels to create label data from a list of integer labels', 'test concatenating two LabelData instances using the plus operator', 'test equality comparison between two LabelData instances', 'test accessing the text and labels properties of a LabelData instance', 'test the CTCGreedyDecoder to decode emissions into text using the decode API', 'test the CTCGreedyDecoder decode_batch API for batched decoding of multiple emission sequences', 'test the BeamState class initialization and label node operations without a language model', 'test the CTCBeamDecoder to verify correct onset timestamp tracking across beam search paths', 'test the CTCBeamDecoder LM scoring with delete key handling and insertion bonus']
```

Usage

```
{'test_CTCGreedyDecoder_decode': 'test the CTCGreedyDecoder to decode emissions into text using the decode API', 'test_CTCGreedyDecoder_decode_batch': 'test the CTCGreedyDecoder decode_batch API for batched decoding of multiple emission sequences', 'test_BeamState_no_lm': 'test the BeamState class initialization and label node operations without a language model', 'test_CTCBeamDecoder_timestamps': 'test the CTCBeamDecoder to verify correct onset timestamp tracking across beam search paths', 'test_CTCBeamDecoder_lm_score': 'test the CTCBeamDecoder LM scoring with delete key handling and insertion bonus'}
```

