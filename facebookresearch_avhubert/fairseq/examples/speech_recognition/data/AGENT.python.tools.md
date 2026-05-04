# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/examples/speech_recognition/data/asr_dataset.py

Prompts

```
['create an AsrDataset instance with audio paths, durations, target transcriptions, and vocabulary dictionary', 'extract Kaldi-style fbank features from WAV audio files using torchaudio and apply MVN normalization', 'collate a list of ASR dataset samples into a mini-batch using Seq2SeqCollater', 'get the frame size and target length tuple for a given sample index in the dataset', 'review the AsrDataset class that represents speech audio and corresponding transcription data', 'create a Seq2SeqCollater instance and call collate to batch speech recognition samples into padded tensors', 'use _collate_frames to convert a list of 2d feature frames into a padded 3d tensor', 'initialize Seq2SeqCollater with custom feature_index and label_index to select data fields from samples', 'use collate to batch samples with move_eos_to_beginning for teacher forcing in seq2seq training', 'review the Seq2SeqCollater collate method to understand batch structure with src_tokens, target, and prev_output_tokens', 'calculate the mean and inverse standard deviation of a 2-D PyTorch feature tensor', 'apply mean-variance normalization to a batch of spectrogram feature tensors', 'convert a 1-D sequence lengths tensor into a 2-D binary encoder padding mask', 'convert a 2-D encoder padding mask tensor back into a 1-D sequence lengths tensor', 'review the speech recognition data utilities module for tensor normalization and padding mask functions', 'pack a token sequence so that repeated symbols are replaced by replabels for ASG criterion training', 'unpack a token sequence so that replabels are replaced by their original repeated symbols', 'generate a replabel symbol string for a given repetition count index', 'review the pack_replabels function to understand how repeated tokens are compressed into replabel indices', 'review the unpack_replabels function to understand how replabel indices are expanded back into repeated tokens']
```

Usage

```
{'create_asr_dataset': 'create an AsrDataset instance with audio paths, durations, target transcriptions, and vocabulary dictionary', 'extract_fbank_features': 'extract Kaldi-style fbank features from WAV audio files using torchaudio and apply MVN normalization', 'collate_asr_samples': 'collate a list of ASR dataset samples into a mini-batch using Seq2SeqCollater', 'get_asr_sample_size': 'get the frame size and target length tuple for a given sample index in the dataset', 'review_asr_dataset_class': 'review the AsrDataset class that represents speech audio and corresponding transcription data'}
```

## File: facebookresearch_avhubert/fairseq/examples/speech_recognition/data/collaters.py

Prompts

```
['create an AsrDataset instance with audio paths, durations, target transcriptions, and vocabulary dictionary', 'extract Kaldi-style fbank features from WAV audio files using torchaudio and apply MVN normalization', 'collate a list of ASR dataset samples into a mini-batch using Seq2SeqCollater', 'get the frame size and target length tuple for a given sample index in the dataset', 'review the AsrDataset class that represents speech audio and corresponding transcription data', 'create a Seq2SeqCollater instance and call collate to batch speech recognition samples into padded tensors', 'use _collate_frames to convert a list of 2d feature frames into a padded 3d tensor', 'initialize Seq2SeqCollater with custom feature_index and label_index to select data fields from samples', 'use collate to batch samples with move_eos_to_beginning for teacher forcing in seq2seq training', 'review the Seq2SeqCollater collate method to understand batch structure with src_tokens, target, and prev_output_tokens', 'calculate the mean and inverse standard deviation of a 2-D PyTorch feature tensor', 'apply mean-variance normalization to a batch of spectrogram feature tensors', 'convert a 1-D sequence lengths tensor into a 2-D binary encoder padding mask', 'convert a 2-D encoder padding mask tensor back into a 1-D sequence lengths tensor', 'review the speech recognition data utilities module for tensor normalization and padding mask functions', 'pack a token sequence so that repeated symbols are replaced by replabels for ASG criterion training', 'unpack a token sequence so that replabels are replaced by their original repeated symbols', 'generate a replabel symbol string for a given repetition count index', 'review the pack_replabels function to understand how repeated tokens are compressed into replabel indices', 'review the unpack_replabels function to understand how replabel indices are expanded back into repeated tokens']
```

Usage

```
{'collate_samples_for_speech_recognition': 'create a Seq2SeqCollater instance and call collate to batch speech recognition samples into padded tensors', 'collate_frames_into_padded_tensor': 'use _collate_frames to convert a list of 2d feature frames into a padded 3d tensor', 'configure_seq2seq_collater_indices': 'initialize Seq2SeqCollater with custom feature_index and label_index to select data fields from samples', 'collate_tokens_with_eos_handling': 'use collate to batch samples with move_eos_to_beginning for teacher forcing in seq2seq training', 'review_seq2seq_collater_batch_output': 'review the Seq2SeqCollater collate method to understand batch structure with src_tokens, target, and prev_output_tokens'}
```

## File: facebookresearch_avhubert/fairseq/examples/speech_recognition/data/data_utils.py

Prompts

```
['create an AsrDataset instance with audio paths, durations, target transcriptions, and vocabulary dictionary', 'extract Kaldi-style fbank features from WAV audio files using torchaudio and apply MVN normalization', 'collate a list of ASR dataset samples into a mini-batch using Seq2SeqCollater', 'get the frame size and target length tuple for a given sample index in the dataset', 'review the AsrDataset class that represents speech audio and corresponding transcription data', 'create a Seq2SeqCollater instance and call collate to batch speech recognition samples into padded tensors', 'use _collate_frames to convert a list of 2d feature frames into a padded 3d tensor', 'initialize Seq2SeqCollater with custom feature_index and label_index to select data fields from samples', 'use collate to batch samples with move_eos_to_beginning for teacher forcing in seq2seq training', 'review the Seq2SeqCollater collate method to understand batch structure with src_tokens, target, and prev_output_tokens', 'calculate the mean and inverse standard deviation of a 2-D PyTorch feature tensor', 'apply mean-variance normalization to a batch of spectrogram feature tensors', 'convert a 1-D sequence lengths tensor into a 2-D binary encoder padding mask', 'convert a 2-D encoder padding mask tensor back into a 1-D sequence lengths tensor', 'review the speech recognition data utilities module for tensor normalization and padding mask functions', 'pack a token sequence so that repeated symbols are replaced by replabels for ASG criterion training', 'unpack a token sequence so that replabels are replaced by their original repeated symbols', 'generate a replabel symbol string for a given repetition count index', 'review the pack_replabels function to understand how repeated tokens are compressed into replabel indices', 'review the unpack_replabels function to understand how replabel indices are expanded back into repeated tokens']
```

Usage

```
{'calc_mean_invstddev': 'calculate the mean and inverse standard deviation of a 2-D PyTorch feature tensor', 'apply_mv_norm': 'apply mean-variance normalization to a batch of spectrogram feature tensors', 'lengths_to_encoder_padding_mask': 'convert a 1-D sequence lengths tensor into a 2-D binary encoder padding mask', 'encoder_padding_mask_to_lengths': 'convert a 2-D encoder padding mask tensor back into a 1-D sequence lengths tensor', 'review_data_utils': 'review the speech recognition data utilities module for tensor normalization and padding mask functions'}
```

## File: facebookresearch_avhubert/fairseq/examples/speech_recognition/data/replabels.py

Prompts

```
['create an AsrDataset instance with audio paths, durations, target transcriptions, and vocabulary dictionary', 'extract Kaldi-style fbank features from WAV audio files using torchaudio and apply MVN normalization', 'collate a list of ASR dataset samples into a mini-batch using Seq2SeqCollater', 'get the frame size and target length tuple for a given sample index in the dataset', 'review the AsrDataset class that represents speech audio and corresponding transcription data', 'create a Seq2SeqCollater instance and call collate to batch speech recognition samples into padded tensors', 'use _collate_frames to convert a list of 2d feature frames into a padded 3d tensor', 'initialize Seq2SeqCollater with custom feature_index and label_index to select data fields from samples', 'use collate to batch samples with move_eos_to_beginning for teacher forcing in seq2seq training', 'review the Seq2SeqCollater collate method to understand batch structure with src_tokens, target, and prev_output_tokens', 'calculate the mean and inverse standard deviation of a 2-D PyTorch feature tensor', 'apply mean-variance normalization to a batch of spectrogram feature tensors', 'convert a 1-D sequence lengths tensor into a 2-D binary encoder padding mask', 'convert a 2-D encoder padding mask tensor back into a 1-D sequence lengths tensor', 'review the speech recognition data utilities module for tensor normalization and padding mask functions', 'pack a token sequence so that repeated symbols are replaced by replabels for ASG criterion training', 'unpack a token sequence so that replabels are replaced by their original repeated symbols', 'generate a replabel symbol string for a given repetition count index', 'review the pack_replabels function to understand how repeated tokens are compressed into replabel indices', 'review the unpack_replabels function to understand how replabel indices are expanded back into repeated tokens']
```

Usage

```
{'pack_replabels': 'pack a token sequence so that repeated symbols are replaced by replabels for ASG criterion training', 'unpack_replabels': 'unpack a token sequence so that replabels are replaced by their original repeated symbols', 'replabel_symbol': 'generate a replabel symbol string for a given repetition count index', 'review_pack_replabels': 'review the pack_replabels function to understand how repeated tokens are compressed into replabel indices', 'review_unpack_replabels': 'review the unpack_replabels function to understand how replabel indices are expanded back into repeated tokens'}
```

