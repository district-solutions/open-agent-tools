# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/fairseq/data/audio/feature_transforms/global_cmvn.py

Prompts

```
['create a GlobalCMVN instance by passing a path to a pre-computed .npz stats file', 'call a GlobalCMVN instance on a numpy array to apply cepstral mean and variance normalization', 'build a GlobalCMVN instance from a config dictionary with a stats_npz_path key', 'review the GlobalCMVN class __init__ to understand how it loads mean and std from an npz file', 'summarize the GlobalCMVN __call__ method that subtracts mean and divides by std for normalization', 'create a SpecAugmentTransform instance with time warp, frequency mask, and time mask parameters', 'apply SpecAugmentTransform to a 2-D spectrogram numpy array to distort it with masking', 'build a SpecAugmentTransform from a config dictionary with time_warp_W, freq_mask_N, and time_mask_N keys', 'review the SpecAugmentTransform time warp logic that uses cv2.resize to distort spectrogram frames', 'test the SpecAugmentTransform frequency and time masking on a 2-D spectrogram tensor', 'create a UtteranceCMVN instance to normalize audio features by mean and variance', 'build a UtteranceCMVN transform from a config dict with norm_means and norm_vars options', 'run utterance-level cepstral mean and variance normalization on a numpy array of audio features', 'review the UtteranceCMVN class and its from_config_dict factory method for audio feature normalization', 'test the UtteranceCMVN call method to verify mean subtraction and variance normalization on audio data']
```

Usage

```
{'create_GlobalCMVN_from_npz': 'create a GlobalCMVN instance by passing a path to a pre-computed .npz stats file', 'call_GlobalCMVN_normalize': 'call a GlobalCMVN instance on a numpy array to apply cepstral mean and variance normalization', 'build_GlobalCMVN_from_config': 'build a GlobalCMVN instance from a config dictionary with a stats_npz_path key', 'review_GlobalCMVN_init': 'review the GlobalCMVN class __init__ to understand how it loads mean and std from an npz file', 'summarize_GlobalCMVN_transform': 'summarize the GlobalCMVN __call__ method that subtracts mean and divides by std for normalization'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/data/audio/feature_transforms/specaugment.py

Prompts

```
['create a GlobalCMVN instance by passing a path to a pre-computed .npz stats file', 'call a GlobalCMVN instance on a numpy array to apply cepstral mean and variance normalization', 'build a GlobalCMVN instance from a config dictionary with a stats_npz_path key', 'review the GlobalCMVN class __init__ to understand how it loads mean and std from an npz file', 'summarize the GlobalCMVN __call__ method that subtracts mean and divides by std for normalization', 'create a SpecAugmentTransform instance with time warp, frequency mask, and time mask parameters', 'apply SpecAugmentTransform to a 2-D spectrogram numpy array to distort it with masking', 'build a SpecAugmentTransform from a config dictionary with time_warp_W, freq_mask_N, and time_mask_N keys', 'review the SpecAugmentTransform time warp logic that uses cv2.resize to distort spectrogram frames', 'test the SpecAugmentTransform frequency and time masking on a 2-D spectrogram tensor', 'create a UtteranceCMVN instance to normalize audio features by mean and variance', 'build a UtteranceCMVN transform from a config dict with norm_means and norm_vars options', 'run utterance-level cepstral mean and variance normalization on a numpy array of audio features', 'review the UtteranceCMVN class and its from_config_dict factory method for audio feature normalization', 'test the UtteranceCMVN call method to verify mean subtraction and variance normalization on audio data']
```

Usage

```
{'create_specaugment_transform': 'create a SpecAugmentTransform instance with time warp, frequency mask, and time mask parameters', 'apply_specaugment_to_spectrogram': 'apply SpecAugmentTransform to a 2-D spectrogram numpy array to distort it with masking', 'build_specaugment_from_config': 'build a SpecAugmentTransform from a config dictionary with time_warp_W, freq_mask_N, and time_mask_N keys', 'review_specaugment_time_warp': 'review the SpecAugmentTransform time warp logic that uses cv2.resize to distort spectrogram frames', 'test_specaugment_masking': 'test the SpecAugmentTransform frequency and time masking on a 2-D spectrogram tensor'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/data/audio/feature_transforms/utterance_cmvn.py

Prompts

```
['create a GlobalCMVN instance by passing a path to a pre-computed .npz stats file', 'call a GlobalCMVN instance on a numpy array to apply cepstral mean and variance normalization', 'build a GlobalCMVN instance from a config dictionary with a stats_npz_path key', 'review the GlobalCMVN class __init__ to understand how it loads mean and std from an npz file', 'summarize the GlobalCMVN __call__ method that subtracts mean and divides by std for normalization', 'create a SpecAugmentTransform instance with time warp, frequency mask, and time mask parameters', 'apply SpecAugmentTransform to a 2-D spectrogram numpy array to distort it with masking', 'build a SpecAugmentTransform from a config dictionary with time_warp_W, freq_mask_N, and time_mask_N keys', 'review the SpecAugmentTransform time warp logic that uses cv2.resize to distort spectrogram frames', 'test the SpecAugmentTransform frequency and time masking on a 2-D spectrogram tensor', 'create a UtteranceCMVN instance to normalize audio features by mean and variance', 'build a UtteranceCMVN transform from a config dict with norm_means and norm_vars options', 'run utterance-level cepstral mean and variance normalization on a numpy array of audio features', 'review the UtteranceCMVN class and its from_config_dict factory method for audio feature normalization', 'test the UtteranceCMVN call method to verify mean subtraction and variance normalization on audio data']
```

Usage

```
{'create_utterance_cmvn_transform': 'create a UtteranceCMVN instance to normalize audio features by mean and variance', 'build_cmvn_from_config': 'build a UtteranceCMVN transform from a config dict with norm_means and norm_vars options', 'run_cmvn_normalization': 'run utterance-level cepstral mean and variance normalization on a numpy array of audio features', 'review_utterance_cmvn_class': 'review the UtteranceCMVN class and its from_config_dict factory method for audio feature normalization', 'test_cmvn_call': 'test the UtteranceCMVN call method to verify mean subtraction and variance normalization on audio data'}
```

