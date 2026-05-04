# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/examples/speech_to_text/data_utils.py

Prompts

```
['train a SentencePiece BPE vocabulary model from text input and export a fairseq dictionary file', 'extract Kaldi-compliant fbank audio features from a waveform tensor and save to numpy file', 'create an uncompressed zip archive of all numpy feature files in a given data root directory', 'generate a manifest mapping utterance IDs to byte offsets and sizes inside a zip archive', 'generate a speech-to-text data config YAML file with specaugment policy and BPE tokenizer settings', 'run the script to prepare CoVoST speech-to-text data with source and target language arguments', 'create a CoVoST PyTorch Dataset instance for a given language pair and train dev or test split', 'generate a TSV manifest file with audio IDs, frame counts, target text, and speaker info', 'build a sentencepiece vocab model from training text using bpe, unigram, or char tokenization', 'run the script to download LibriSpeech data and extract fbank features for all splits', 'create log mel filter bank features from LibriSpeech audio waveforms and save as numpy files', 'generate TSV manifest files with audio paths, frame counts, text, and speaker IDs for each split', 'generate a config YAML file with the vocab model path and specaugment policy for speech-to-text training', 'create a MUSTC dataset for a language split to load audio segments and utterances', 'generate a SentencePiece vocabulary model from training text with a specified vocab size', 'process all 8 MuST-C languages jointly to create a shared vocabulary and config']
```

Usage

```
{'gen_vocab': 'train a SentencePiece BPE vocabulary model from text input and export a fairseq dictionary file', 'extract_fbank_features': 'extract Kaldi-compliant fbank audio features from a waveform tensor and save to numpy file', 'create_zip': 'create an uncompressed zip archive of all numpy feature files in a given data root directory', 'get_zip_manifest': 'generate a manifest mapping utterance IDs to byte offsets and sizes inside a zip archive', 'gen_config_yaml': 'generate a speech-to-text data config YAML file with specaugment policy and BPE tokenizer settings'}
```

## File: facebookresearch_diffq/examples/fairseq/examples/speech_to_text/prep_covost_data.py

Prompts

```
['train a SentencePiece BPE vocabulary model from text input and export a fairseq dictionary file', 'extract Kaldi-compliant fbank audio features from a waveform tensor and save to numpy file', 'create an uncompressed zip archive of all numpy feature files in a given data root directory', 'generate a manifest mapping utterance IDs to byte offsets and sizes inside a zip archive', 'generate a speech-to-text data config YAML file with specaugment policy and BPE tokenizer settings', 'run the script to prepare CoVoST speech-to-text data with source and target language arguments', 'create a CoVoST PyTorch Dataset instance for a given language pair and train dev or test split', 'generate a TSV manifest file with audio IDs, frame counts, target text, and speaker info', 'build a sentencepiece vocab model from training text using bpe, unigram, or char tokenization', 'run the script to download LibriSpeech data and extract fbank features for all splits', 'create log mel filter bank features from LibriSpeech audio waveforms and save as numpy files', 'generate TSV manifest files with audio paths, frame counts, text, and speaker IDs for each split', 'generate a config YAML file with the vocab model path and specaugment policy for speech-to-text training', 'create a MUSTC dataset for a language split to load audio segments and utterances', 'generate a SentencePiece vocabulary model from training text with a specified vocab size', 'process all 8 MuST-C languages jointly to create a shared vocabulary and config']
```

Usage

```
{'run_covost_data_prep': 'run the script to prepare CoVoST speech-to-text data with source and target language arguments', 'create_covost_dataset': 'create a CoVoST PyTorch Dataset instance for a given language pair and train dev or test split', 'extract_fbank_features': 'extract log mel filter bank features from audio waveforms and save them as numpy arrays', 'generate_manifest_tsv': 'generate a TSV manifest file with audio IDs, frame counts, target text, and speaker info', 'build_vocab_model': 'build a sentencepiece vocab model from training text using bpe, unigram, or char tokenization'}
```

## File: facebookresearch_diffq/examples/fairseq/examples/speech_to_text/prep_librispeech_data.py

Prompts

```
['train a SentencePiece BPE vocabulary model from text input and export a fairseq dictionary file', 'extract Kaldi-compliant fbank audio features from a waveform tensor and save to numpy file', 'create an uncompressed zip archive of all numpy feature files in a given data root directory', 'generate a manifest mapping utterance IDs to byte offsets and sizes inside a zip archive', 'generate a speech-to-text data config YAML file with specaugment policy and BPE tokenizer settings', 'run the script to prepare CoVoST speech-to-text data with source and target language arguments', 'create a CoVoST PyTorch Dataset instance for a given language pair and train dev or test split', 'generate a TSV manifest file with audio IDs, frame counts, target text, and speaker info', 'build a sentencepiece vocab model from training text using bpe, unigram, or char tokenization', 'run the script to download LibriSpeech data and extract fbank features for all splits', 'create log mel filter bank features from LibriSpeech audio waveforms and save as numpy files', 'generate TSV manifest files with audio paths, frame counts, text, and speaker IDs for each split', 'generate a config YAML file with the vocab model path and specaugment policy for speech-to-text training', 'create a MUSTC dataset for a language split to load audio segments and utterances', 'generate a SentencePiece vocabulary model from training text with a specified vocab size', 'process all 8 MuST-C languages jointly to create a shared vocabulary and config']
```

Usage

```
{'run_librispeech_data_prep': 'run the script to download LibriSpeech data and extract fbank features for all splits', 'create_fbank_features': 'create log mel filter bank features from LibriSpeech audio waveforms and save as numpy files', 'generate_tsv_manifest': 'generate TSV manifest files with audio paths, frame counts, text, and speaker IDs for each split', 'build_vocab_model': 'build a SentencePiece vocabulary model from LibriSpeech training text using bpe, unigram, or char encoding', 'generate_config_yaml': 'generate a config YAML file with the vocab model path and specaugment policy for speech-to-text training'}
```

## File: facebookresearch_diffq/examples/fairseq/examples/speech_to_text/prep_mustc_data.py

Prompts

```
['train a SentencePiece BPE vocabulary model from text input and export a fairseq dictionary file', 'extract Kaldi-compliant fbank audio features from a waveform tensor and save to numpy file', 'create an uncompressed zip archive of all numpy feature files in a given data root directory', 'generate a manifest mapping utterance IDs to byte offsets and sizes inside a zip archive', 'generate a speech-to-text data config YAML file with specaugment policy and BPE tokenizer settings', 'run the script to prepare CoVoST speech-to-text data with source and target language arguments', 'create a CoVoST PyTorch Dataset instance for a given language pair and train dev or test split', 'generate a TSV manifest file with audio IDs, frame counts, target text, and speaker info', 'build a sentencepiece vocab model from training text using bpe, unigram, or char tokenization', 'run the script to download LibriSpeech data and extract fbank features for all splits', 'create log mel filter bank features from LibriSpeech audio waveforms and save as numpy files', 'generate TSV manifest files with audio paths, frame counts, text, and speaker IDs for each split', 'generate a config YAML file with the vocab model path and specaugment policy for speech-to-text training', 'create a MUSTC dataset for a language split to load audio segments and utterances', 'generate a SentencePiece vocabulary model from training text with a specified vocab size', 'process all 8 MuST-C languages jointly to create a shared vocabulary and config']
```

Usage

```
{'create_mustc_dataset': 'create a MUSTC dataset for a language split to load audio segments and utterances', 'extract_fbank_features': 'extract log mel filter bank features from waveform audio data for all splits', 'generate_manifest_tsv': 'generate a TSV manifest file with audio metadata and target text for a task', 'generate_vocab': 'generate a SentencePiece vocabulary model from training text with a specified vocab size', 'process_joint_multilingual': 'process all 8 MuST-C languages jointly to create a shared vocabulary and config'}
```

