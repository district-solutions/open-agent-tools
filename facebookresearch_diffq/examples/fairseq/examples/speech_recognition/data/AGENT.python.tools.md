# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/examples/speech_recognition/data/asr_dataset.py

Prompts

```
['create an AsrDataset instance with audio paths, durations, target transcriptions, and vocabulary dictionary', 'extract Kaldi-style fbank features from WAV audio files using torchaudio and apply mean-variance normalization', 'collate a list of ASR samples into a mini-batch using the Seq2SeqCollater for model forwarding', 'get the frame size and target length tuple for a given sample index to filter by max positions', 'review the AsrDataset class that represents speech audio and corresponding transcription data for fairseq', 'collate speech recognition samples into a padded batch with source frames and target tokens', 'collate a list of 2d feature frames into a padded 3d tensor for batch processing', 'create a Seq2SeqCollater instance with custom feature index, label index, pad index, and eos index', 'parse raw samples with numpy arrays and lists into torch tensors for batch collation', 'sort collated samples by descending frame length and reorder ids, frames, and targets accordingly', 'calculate the mean and inverse standard deviation of a 2-D feature tensor', 'apply mean-variance normalization to a batch of spectrogram feature tensors', 'convert a 1-D sequence lengths tensor into a 2-D binary encoder padding mask', 'convert a 2-D encoder padding mask back into a 1-D sequence lengths tensor', 'review the data_utils module for speech recognition feature normalization and padding mask utilities', 'pack a token sequence so that repeated symbols are replaced by replabels for ASG criterion', 'unpack a token sequence so that replabels are replaced by their original repeated symbols', 'generate a replabel symbol string from an integer index for use in flashlight ASG training', 'review the pack_replabels function to understand how repeated tokens are compressed into replabel indices', 'review the unpack_replabels function to understand how replabel indices are expanded back into repeated tokens']
```

Usage

```
{'create_asr_dataset': 'create an AsrDataset instance with audio paths, durations, target transcriptions, and vocabulary dictionary', 'extract_fbank_features': 'extract Kaldi-style fbank features from WAV audio files using torchaudio and apply mean-variance normalization', 'collate_asr_samples': 'collate a list of ASR samples into a mini-batch using the Seq2SeqCollater for model forwarding', 'get_asr_sample_size': 'get the frame size and target length tuple for a given sample index to filter by max positions', 'review_asr_dataset_class': 'review the AsrDataset class that represents speech audio and corresponding transcription data for fairseq'}
```

## File: facebookresearch_diffq/examples/fairseq/examples/speech_recognition/data/collaters.py

Prompts

```
['create an AsrDataset instance with audio paths, durations, target transcriptions, and vocabulary dictionary', 'extract Kaldi-style fbank features from WAV audio files using torchaudio and apply mean-variance normalization', 'collate a list of ASR samples into a mini-batch using the Seq2SeqCollater for model forwarding', 'get the frame size and target length tuple for a given sample index to filter by max positions', 'review the AsrDataset class that represents speech audio and corresponding transcription data for fairseq', 'collate speech recognition samples into a padded batch with source frames and target tokens', 'collate a list of 2d feature frames into a padded 3d tensor for batch processing', 'create a Seq2SeqCollater instance with custom feature index, label index, pad index, and eos index', 'parse raw samples with numpy arrays and lists into torch tensors for batch collation', 'sort collated samples by descending frame length and reorder ids, frames, and targets accordingly', 'calculate the mean and inverse standard deviation of a 2-D feature tensor', 'apply mean-variance normalization to a batch of spectrogram feature tensors', 'convert a 1-D sequence lengths tensor into a 2-D binary encoder padding mask', 'convert a 2-D encoder padding mask back into a 1-D sequence lengths tensor', 'review the data_utils module for speech recognition feature normalization and padding mask utilities', 'pack a token sequence so that repeated symbols are replaced by replabels for ASG criterion', 'unpack a token sequence so that replabels are replaced by their original repeated symbols', 'generate a replabel symbol string from an integer index for use in flashlight ASG training', 'review the pack_replabels function to understand how repeated tokens are compressed into replabel indices', 'review the unpack_replabels function to understand how replabel indices are expanded back into repeated tokens']
```

Usage

```
{'collate_samples_for_speech_recognition': 'collate speech recognition samples into a padded batch with source frames and target tokens', 'collate_frames_into_padded_tensor': 'collate a list of 2d feature frames into a padded 3d tensor for batch processing', 'create_seq2seq_collater': 'create a Seq2SeqCollater instance with custom feature index, label index, pad index, and eos index', 'parse_samples_into_tensors': 'parse raw samples with numpy arrays and lists into torch tensors for batch collation', 'sort_samples_by_frame_length': 'sort collated samples by descending frame length and reorder ids, frames, and targets accordingly'}
```

## File: facebookresearch_diffq/examples/fairseq/examples/speech_recognition/data/data_utils.py

Prompts

```
['create an AsrDataset instance with audio paths, durations, target transcriptions, and vocabulary dictionary', 'extract Kaldi-style fbank features from WAV audio files using torchaudio and apply mean-variance normalization', 'collate a list of ASR samples into a mini-batch using the Seq2SeqCollater for model forwarding', 'get the frame size and target length tuple for a given sample index to filter by max positions', 'review the AsrDataset class that represents speech audio and corresponding transcription data for fairseq', 'collate speech recognition samples into a padded batch with source frames and target tokens', 'collate a list of 2d feature frames into a padded 3d tensor for batch processing', 'create a Seq2SeqCollater instance with custom feature index, label index, pad index, and eos index', 'parse raw samples with numpy arrays and lists into torch tensors for batch collation', 'sort collated samples by descending frame length and reorder ids, frames, and targets accordingly', 'calculate the mean and inverse standard deviation of a 2-D feature tensor', 'apply mean-variance normalization to a batch of spectrogram feature tensors', 'convert a 1-D sequence lengths tensor into a 2-D binary encoder padding mask', 'convert a 2-D encoder padding mask back into a 1-D sequence lengths tensor', 'review the data_utils module for speech recognition feature normalization and padding mask utilities', 'pack a token sequence so that repeated symbols are replaced by replabels for ASG criterion', 'unpack a token sequence so that replabels are replaced by their original repeated symbols', 'generate a replabel symbol string from an integer index for use in flashlight ASG training', 'review the pack_replabels function to understand how repeated tokens are compressed into replabel indices', 'review the unpack_replabels function to understand how replabel indices are expanded back into repeated tokens']
```

Usage

```
{'calc_mean_invstddev': 'calculate the mean and inverse standard deviation of a 2-D feature tensor', 'apply_mv_norm': 'apply mean-variance normalization to a batch of spectrogram feature tensors', 'lengths_to_encoder_padding_mask': 'convert a 1-D sequence lengths tensor into a 2-D binary encoder padding mask', 'encoder_padding_mask_to_lengths': 'convert a 2-D encoder padding mask back into a 1-D sequence lengths tensor', 'review_data_utils': 'review the data_utils module for speech recognition feature normalization and padding mask utilities'}
```

## File: facebookresearch_diffq/examples/fairseq/examples/speech_recognition/data/replabels.py

Prompts

```
['create an AsrDataset instance with audio paths, durations, target transcriptions, and vocabulary dictionary', 'extract Kaldi-style fbank features from WAV audio files using torchaudio and apply mean-variance normalization', 'collate a list of ASR samples into a mini-batch using the Seq2SeqCollater for model forwarding', 'get the frame size and target length tuple for a given sample index to filter by max positions', 'review the AsrDataset class that represents speech audio and corresponding transcription data for fairseq', 'collate speech recognition samples into a padded batch with source frames and target tokens', 'collate a list of 2d feature frames into a padded 3d tensor for batch processing', 'create a Seq2SeqCollater instance with custom feature index, label index, pad index, and eos index', 'parse raw samples with numpy arrays and lists into torch tensors for batch collation', 'sort collated samples by descending frame length and reorder ids, frames, and targets accordingly', 'calculate the mean and inverse standard deviation of a 2-D feature tensor', 'apply mean-variance normalization to a batch of spectrogram feature tensors', 'convert a 1-D sequence lengths tensor into a 2-D binary encoder padding mask', 'convert a 2-D encoder padding mask back into a 1-D sequence lengths tensor', 'review the data_utils module for speech recognition feature normalization and padding mask utilities', 'pack a token sequence so that repeated symbols are replaced by replabels for ASG criterion', 'unpack a token sequence so that replabels are replaced by their original repeated symbols', 'generate a replabel symbol string from an integer index for use in flashlight ASG training', 'review the pack_replabels function to understand how repeated tokens are compressed into replabel indices', 'review the unpack_replabels function to understand how replabel indices are expanded back into repeated tokens']
```

Usage

```
{'pack_replabels': 'pack a token sequence so that repeated symbols are replaced by replabels for ASG criterion', 'unpack_replabels': 'unpack a token sequence so that replabels are replaced by their original repeated symbols', 'replabel_symbol': 'generate a replabel symbol string from an integer index for use in flashlight ASG training', 'review_pack_replabels': 'review the pack_replabels function to understand how repeated tokens are compressed into replabel indices', 'review_unpack_replabels': 'review the unpack_replabels function to understand how replabel indices are expanded back into repeated tokens'}
```

