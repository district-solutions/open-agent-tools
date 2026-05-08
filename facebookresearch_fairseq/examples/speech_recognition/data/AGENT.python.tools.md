# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/speech_recognition/data/asr_dataset.py

Prompts

```
['create an AsrDataset instance with audio paths, durations, target transcriptions, and a target dictionary', 'review the AsrDataset __getitem__ method that loads WAV files and extracts Kaldi fbank features with CMVN normalization', 'refactor the AsrDataset collater method to merge samples into a mini-batch using Seq2SeqCollater', 'summarize the AsrDataset size method that returns frame count and target length for max-positions filtering', 'test the AsrDataset ordered_indices method that returns an ordered list of indices for batch construction', 'collate speech recognition samples into a padded batch with source frames and target tokens', 'collate a list of 2d feature frames into a single padded 3d tensor', 'create a Seq2SeqCollater instance with custom feature index, label index, pad index, and eos index', 'review the Seq2SeqCollater class and understand how it packs samples into batches for seq2seq tasks', 'summarize the collate method that parses samples, sorts by frame length, and builds a batch dictionary', 'calculate the mean and inverse standard deviation of a 2-D feature tensor', 'apply mean-variance normalization to a batch of spectrogram feature tensors', 'convert a 1-D sequence lengths tensor into a 2-D binary encoder padding mask', 'convert a 2-D encoder padding mask back into a 1-D sequence lengths tensor', 'review the speech recognition data utility functions for tensor normalization and padding mask conversion', 'pack a token sequence so that repeated symbols are replaced by replabels for ASG criterion', 'unpack a token sequence so that replabels are replaced by their original repeated symbols', 'generate a replabel symbol string from an integer index for use in flashlight ASG', 'review the pack_replabels function to understand how repeated tokens are compressed into replabels', 'test the unpack_replabels function to verify it correctly expands replabels back to repeated tokens']
```

Usage

```
{'create_asr_dataset': 'create an AsrDataset instance with audio paths, durations, target transcriptions, and a target dictionary', 'review_asr_dataset_getitem': 'review the AsrDataset __getitem__ method that loads WAV files and extracts Kaldi fbank features with CMVN normalization', 'refactor_asr_dataset_collater': 'refactor the AsrDataset collater method to merge samples into a mini-batch using Seq2SeqCollater', 'summarize_asr_dataset_size': 'summarize the AsrDataset size method that returns frame count and target length for max-positions filtering', 'test_asr_dataset_ordered_indices': 'test the AsrDataset ordered_indices method that returns an ordered list of indices for batch construction'}
```

## File: facebookresearch_fairseq/examples/speech_recognition/data/collaters.py

Prompts

```
['create an AsrDataset instance with audio paths, durations, target transcriptions, and a target dictionary', 'review the AsrDataset __getitem__ method that loads WAV files and extracts Kaldi fbank features with CMVN normalization', 'refactor the AsrDataset collater method to merge samples into a mini-batch using Seq2SeqCollater', 'summarize the AsrDataset size method that returns frame count and target length for max-positions filtering', 'test the AsrDataset ordered_indices method that returns an ordered list of indices for batch construction', 'collate speech recognition samples into a padded batch with source frames and target tokens', 'collate a list of 2d feature frames into a single padded 3d tensor', 'create a Seq2SeqCollater instance with custom feature index, label index, pad index, and eos index', 'review the Seq2SeqCollater class and understand how it packs samples into batches for seq2seq tasks', 'summarize the collate method that parses samples, sorts by frame length, and builds a batch dictionary', 'calculate the mean and inverse standard deviation of a 2-D feature tensor', 'apply mean-variance normalization to a batch of spectrogram feature tensors', 'convert a 1-D sequence lengths tensor into a 2-D binary encoder padding mask', 'convert a 2-D encoder padding mask back into a 1-D sequence lengths tensor', 'review the speech recognition data utility functions for tensor normalization and padding mask conversion', 'pack a token sequence so that repeated symbols are replaced by replabels for ASG criterion', 'unpack a token sequence so that replabels are replaced by their original repeated symbols', 'generate a replabel symbol string from an integer index for use in flashlight ASG', 'review the pack_replabels function to understand how repeated tokens are compressed into replabels', 'test the unpack_replabels function to verify it correctly expands replabels back to repeated tokens']
```

Usage

```
{'collate_samples_into_batch': 'collate speech recognition samples into a padded batch with source frames and target tokens', 'collate_frames_into_tensor': 'collate a list of 2d feature frames into a single padded 3d tensor', 'create_seq2seq_collater': 'create a Seq2SeqCollater instance with custom feature index, label index, pad index, and eos index', 'review_seq2seq_collater_class': 'review the Seq2SeqCollater class and understand how it packs samples into batches for seq2seq tasks', 'summarize_collate_method': 'summarize the collate method that parses samples, sorts by frame length, and builds a batch dictionary'}
```

## File: facebookresearch_fairseq/examples/speech_recognition/data/data_utils.py

Prompts

```
['create an AsrDataset instance with audio paths, durations, target transcriptions, and a target dictionary', 'review the AsrDataset __getitem__ method that loads WAV files and extracts Kaldi fbank features with CMVN normalization', 'refactor the AsrDataset collater method to merge samples into a mini-batch using Seq2SeqCollater', 'summarize the AsrDataset size method that returns frame count and target length for max-positions filtering', 'test the AsrDataset ordered_indices method that returns an ordered list of indices for batch construction', 'collate speech recognition samples into a padded batch with source frames and target tokens', 'collate a list of 2d feature frames into a single padded 3d tensor', 'create a Seq2SeqCollater instance with custom feature index, label index, pad index, and eos index', 'review the Seq2SeqCollater class and understand how it packs samples into batches for seq2seq tasks', 'summarize the collate method that parses samples, sorts by frame length, and builds a batch dictionary', 'calculate the mean and inverse standard deviation of a 2-D feature tensor', 'apply mean-variance normalization to a batch of spectrogram feature tensors', 'convert a 1-D sequence lengths tensor into a 2-D binary encoder padding mask', 'convert a 2-D encoder padding mask back into a 1-D sequence lengths tensor', 'review the speech recognition data utility functions for tensor normalization and padding mask conversion', 'pack a token sequence so that repeated symbols are replaced by replabels for ASG criterion', 'unpack a token sequence so that replabels are replaced by their original repeated symbols', 'generate a replabel symbol string from an integer index for use in flashlight ASG', 'review the pack_replabels function to understand how repeated tokens are compressed into replabels', 'test the unpack_replabels function to verify it correctly expands replabels back to repeated tokens']
```

Usage

```
{'calc_mean_invstddev': 'calculate the mean and inverse standard deviation of a 2-D feature tensor', 'apply_mv_norm': 'apply mean-variance normalization to a batch of spectrogram feature tensors', 'lengths_to_encoder_padding_mask': 'convert a 1-D sequence lengths tensor into a 2-D binary encoder padding mask', 'encoder_padding_mask_to_lengths': 'convert a 2-D encoder padding mask back into a 1-D sequence lengths tensor', 'review_data_utils': 'review the speech recognition data utility functions for tensor normalization and padding mask conversion'}
```

## File: facebookresearch_fairseq/examples/speech_recognition/data/replabels.py

Prompts

```
['create an AsrDataset instance with audio paths, durations, target transcriptions, and a target dictionary', 'review the AsrDataset __getitem__ method that loads WAV files and extracts Kaldi fbank features with CMVN normalization', 'refactor the AsrDataset collater method to merge samples into a mini-batch using Seq2SeqCollater', 'summarize the AsrDataset size method that returns frame count and target length for max-positions filtering', 'test the AsrDataset ordered_indices method that returns an ordered list of indices for batch construction', 'collate speech recognition samples into a padded batch with source frames and target tokens', 'collate a list of 2d feature frames into a single padded 3d tensor', 'create a Seq2SeqCollater instance with custom feature index, label index, pad index, and eos index', 'review the Seq2SeqCollater class and understand how it packs samples into batches for seq2seq tasks', 'summarize the collate method that parses samples, sorts by frame length, and builds a batch dictionary', 'calculate the mean and inverse standard deviation of a 2-D feature tensor', 'apply mean-variance normalization to a batch of spectrogram feature tensors', 'convert a 1-D sequence lengths tensor into a 2-D binary encoder padding mask', 'convert a 2-D encoder padding mask back into a 1-D sequence lengths tensor', 'review the speech recognition data utility functions for tensor normalization and padding mask conversion', 'pack a token sequence so that repeated symbols are replaced by replabels for ASG criterion', 'unpack a token sequence so that replabels are replaced by their original repeated symbols', 'generate a replabel symbol string from an integer index for use in flashlight ASG', 'review the pack_replabels function to understand how repeated tokens are compressed into replabels', 'test the unpack_replabels function to verify it correctly expands replabels back to repeated tokens']
```

Usage

```
{'pack_replabels': 'pack a token sequence so that repeated symbols are replaced by replabels for ASG criterion', 'unpack_replabels': 'unpack a token sequence so that replabels are replaced by their original repeated symbols', 'replabel_symbol': 'generate a replabel symbol string from an integer index for use in flashlight ASG', 'review_pack_replabels': 'review the pack_replabels function to understand how repeated tokens are compressed into replabels', 'test_unpack_replabels': 'test the unpack_replabels function to verify it correctly expands replabels back to repeated tokens'}
```

