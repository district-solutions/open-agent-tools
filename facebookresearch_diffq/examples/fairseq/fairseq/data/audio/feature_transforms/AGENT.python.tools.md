# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/fairseq/data/audio/feature_transforms/global_cmvn.py

Prompts

```
['build a python module that applies global cepstral mean and variance normalization to audio features using pre-computed stats', 'create a GlobalCMVN instance from a config dictionary with a stats_npz_path key pointing to pre-computed statistics', 'test the GlobalCMVN class by calling it with a numpy array to normalize audio features', 'review the GlobalCMVN constructor to understand how it loads mean and std from an npz file', 'summarize the GlobalCMVN class which performs cepstral mean and variance normalization on audio feature arrays', 'create a SpecAugmentTransform instance with time warp, frequency mask, and time mask parameters', 'apply SpecAugmentTransform to a 2D spectrogram numpy array to distort it with masking', 'build a SpecAugmentTransform from a config dictionary with time_warp_W, freq_mask_N, and time_mask_N keys', 'review the SpecAugmentTransform class and its frequency masking and time masking augmentation logic', 'test the SpecAugmentTransform time warp feature using cv2 resize on spectrogram frames', 'build a python module that applies utterance-level cepstral mean and variance normalization to audio features', 'test the UtteranceCMVN class by calling it on a numpy array of audio features', 'refactor the UtteranceCMVN variance calculation to use a different minimum clamp value than 1e-10', 'review the UtteranceCMVN class and its from_config_dict factory method for audio feature normalization']
```

Usage

```
{'build_global_cmvn_transform': 'build a python module that applies global cepstral mean and variance normalization to audio features using pre-computed stats', 'create_cmvn_from_config': 'create a GlobalCMVN instance from a config dictionary with a stats_npz_path key pointing to pre-computed statistics', 'test_global_cmvn_call': 'test the GlobalCMVN class by calling it with a numpy array to normalize audio features', 'review_global_cmvn_init': 'review the GlobalCMVN constructor to understand how it loads mean and std from an npz file', 'summarize_global_cmvn_class': 'summarize the GlobalCMVN class which performs cepstral mean and variance normalization on audio feature arrays'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/data/audio/feature_transforms/specaugment.py

Prompts

```
['build a python module that applies global cepstral mean and variance normalization to audio features using pre-computed stats', 'create a GlobalCMVN instance from a config dictionary with a stats_npz_path key pointing to pre-computed statistics', 'test the GlobalCMVN class by calling it with a numpy array to normalize audio features', 'review the GlobalCMVN constructor to understand how it loads mean and std from an npz file', 'summarize the GlobalCMVN class which performs cepstral mean and variance normalization on audio feature arrays', 'create a SpecAugmentTransform instance with time warp, frequency mask, and time mask parameters', 'apply SpecAugmentTransform to a 2D spectrogram numpy array to distort it with masking', 'build a SpecAugmentTransform from a config dictionary with time_warp_W, freq_mask_N, and time_mask_N keys', 'review the SpecAugmentTransform class and its frequency masking and time masking augmentation logic', 'test the SpecAugmentTransform time warp feature using cv2 resize on spectrogram frames', 'build a python module that applies utterance-level cepstral mean and variance normalization to audio features', 'test the UtteranceCMVN class by calling it on a numpy array of audio features', 'refactor the UtteranceCMVN variance calculation to use a different minimum clamp value than 1e-10', 'review the UtteranceCMVN class and its from_config_dict factory method for audio feature normalization']
```

Usage

```
{'create_spec_augment_transform': 'create a SpecAugmentTransform instance with time warp, frequency mask, and time mask parameters', 'apply_specaugment_to_spectrogram': 'apply SpecAugmentTransform to a 2D spectrogram numpy array to distort it with masking', 'build_specaugment_from_config': 'build a SpecAugmentTransform from a config dictionary with time_warp_W, freq_mask_N, and time_mask_N keys', 'review_specaugment_masking': 'review the SpecAugmentTransform class and its frequency masking and time masking augmentation logic', 'test_specaugment_time_warp': 'test the SpecAugmentTransform time warp feature using cv2 resize on spectrogram frames'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/data/audio/feature_transforms/utterance_cmvn.py

Prompts

```
['build a python module that applies global cepstral mean and variance normalization to audio features using pre-computed stats', 'create a GlobalCMVN instance from a config dictionary with a stats_npz_path key pointing to pre-computed statistics', 'test the GlobalCMVN class by calling it with a numpy array to normalize audio features', 'review the GlobalCMVN constructor to understand how it loads mean and std from an npz file', 'summarize the GlobalCMVN class which performs cepstral mean and variance normalization on audio feature arrays', 'create a SpecAugmentTransform instance with time warp, frequency mask, and time mask parameters', 'apply SpecAugmentTransform to a 2D spectrogram numpy array to distort it with masking', 'build a SpecAugmentTransform from a config dictionary with time_warp_W, freq_mask_N, and time_mask_N keys', 'review the SpecAugmentTransform class and its frequency masking and time masking augmentation logic', 'test the SpecAugmentTransform time warp feature using cv2 resize on spectrogram frames', 'build a python module that applies utterance-level cepstral mean and variance normalization to audio features', 'test the UtteranceCMVN class by calling it on a numpy array of audio features', 'refactor the UtteranceCMVN variance calculation to use a different minimum clamp value than 1e-10', 'review the UtteranceCMVN class and its from_config_dict factory method for audio feature normalization']
```

Usage

```
{'build_utterance_cmvn_normalizer': 'build a python module that applies utterance-level cepstral mean and variance normalization to audio features', 'create_cmvn_from_config': 'create a UtteranceCMVN instance from a config dictionary with norm_means and norm_vars options', 'test_utterance_cmvn_call': 'test the UtteranceCMVN class by calling it on a numpy array of audio features', 'refactor_cmvn_variance_clamp': 'refactor the UtteranceCMVN variance calculation to use a different minimum clamp value than 1e-10', 'review_utterance_cmvn_class': 'review the UtteranceCMVN class and its from_config_dict factory method for audio feature normalization'}
```

