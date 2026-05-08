# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/fairseq/data/audio/dataset_transforms/concataugment.py

Prompts

```
['create a ConcatAugment instance from a config dictionary with rate, max_tokens, and attempts', 'build a ConcatAugment audio dataset transform using default rate of 0.25 and max_tokens of 3000', 'run find_indices to select audio samples for concatenation augmentation within token limits', 'test the ConcatAugment class to verify the augmentation rate controls sample concatenation probability', 'review the ConcatAugment find_indices method to understand max_tokens skip logic and concatenation attempts', 'create a NoisyOverlapAugment instance from a config dictionary with custom rate and SNR settings', 'build a NoisyOverlapAugment transform using default parameters for noisy overlap data augmentation', 'run the NoisyOverlapAugment transform on a list of audio source tensors to apply overlap augmentation', 'review the NoisyOverlapAugment constructor to understand rate, mixing noise rate, and SNR range parameters', 'summarize the NoisyOverlapAugment class that mixes utterances or noise into audio sources at random offsets']
```

Usage

```
{'create_ConcatAugment_from_config': 'create a ConcatAugment instance from a config dictionary with rate, max_tokens, and attempts', 'build_ConcatAugment_with_defaults': 'build a ConcatAugment audio dataset transform using default rate of 0.25 and max_tokens of 3000', 'run_find_indices': 'run find_indices to select audio samples for concatenation augmentation within token limits', 'test_ConcatAugment_augmentation_rate': 'test the ConcatAugment class to verify the augmentation rate controls sample concatenation probability', 'review_ConcatAugment_max_tokens': 'review the ConcatAugment find_indices method to understand max_tokens skip logic and concatenation attempts'}
```

## File: facebookresearch_fairseq/fairseq/data/audio/dataset_transforms/noisyoverlapaugment.py

Prompts

```
['create a ConcatAugment instance from a config dictionary with rate, max_tokens, and attempts', 'build a ConcatAugment audio dataset transform using default rate of 0.25 and max_tokens of 3000', 'run find_indices to select audio samples for concatenation augmentation within token limits', 'test the ConcatAugment class to verify the augmentation rate controls sample concatenation probability', 'review the ConcatAugment find_indices method to understand max_tokens skip logic and concatenation attempts', 'create a NoisyOverlapAugment instance from a config dictionary with custom rate and SNR settings', 'build a NoisyOverlapAugment transform using default parameters for noisy overlap data augmentation', 'run the NoisyOverlapAugment transform on a list of audio source tensors to apply overlap augmentation', 'review the NoisyOverlapAugment constructor to understand rate, mixing noise rate, and SNR range parameters', 'summarize the NoisyOverlapAugment class that mixes utterances or noise into audio sources at random offsets']
```

Usage

```
{'create_NoisyOverlapAugment_from_config': 'create a NoisyOverlapAugment instance from a config dictionary with custom rate and SNR settings', 'build_NoisyOverlapAugment_with_defaults': 'build a NoisyOverlapAugment transform using default parameters for noisy overlap data augmentation', 'run_NoisyOverlapAugment_call': 'run the NoisyOverlapAugment transform on a list of audio source tensors to apply overlap augmentation', 'review_NoisyOverlapAugment_init': 'review the NoisyOverlapAugment constructor to understand rate, mixing noise rate, and SNR range parameters', 'summarize_NoisyOverlapAugment_class': 'summarize the NoisyOverlapAugment class that mixes utterances or noise into audio sources at random offsets'}
```

