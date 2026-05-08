# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/fairseq/data/audio/feature_transforms/delta_deltas.py

Prompts

```
['build a python module to compute delta and delta-delta features from a spectrogram using DeltaDeltas', 'create a DeltaDeltas instance from a config dictionary with a custom win_length parameter', 'test the DeltaDeltas class by calling it with a 2-D spectrogram numpy array', 'refactor the DeltaDeltas class to support a configurable window length for delta computation', 'review the DeltaDeltas class and its use of torchaudio compute_deltas for audio feature expansion', 'build a GlobalCMVN instance from a config dict with a stats_npz_path key', 'create a GlobalCMVN normalizer by passing a path to a precomputed .npz stats file', 'test the GlobalCMVN call method to normalize audio features by subtracting mean and dividing by std', 'refactor the GlobalCMVN init to load mean and std from a NumPy .npz stats file', 'review the GlobalCMVN class and its cepstral mean variance normalization logic', 'create a SpecAugmentTransform instance with time warp, freq mask, and time mask parameters', 'apply the SpecAugmentTransform call method to distort a 2-D spectrogram numpy array', 'build a SpecAugmentTransform from a config dictionary with time_warp_W, freq_mask_N, and time_mask_N keys', 'review the SpecAugmentTransform time warp logic that uses cv2 resize to distort spectrogram frames', 'test the SpecAugmentTransform freq and time masking on a spectrogram with random mask regions', 'build a python module to apply utterance-level cepstral mean and variance normalization to audio features', 'create a UtteranceCMVN instance from a config dictionary with norm_means and norm_vars options', 'test the UtteranceCMVN call method to normalize a numpy array of audio features', 'refactor the UtteranceCMVN class to support additional normalization parameters beyond means and vars', 'review the UtteranceCMVN class and its cepstral mean variance normalization logic for audio feature processing']
```

Usage

```
{'build_delta_deltas_transform': 'build a python module to compute delta and delta-delta features from a spectrogram using DeltaDeltas', 'create_delta_deltas_from_config': 'create a DeltaDeltas instance from a config dictionary with a custom win_length parameter', 'test_delta_deltas_call': 'test the DeltaDeltas class by calling it with a 2-D spectrogram numpy array', 'refactor_delta_deltas_win_length': 'refactor the DeltaDeltas class to support a configurable window length for delta computation', 'review_delta_deltas_transform': 'review the DeltaDeltas class and its use of torchaudio compute_deltas for audio feature expansion'}
```

## File: facebookresearch_fairseq/fairseq/data/audio/feature_transforms/global_cmvn.py

Prompts

```
['build a python module to compute delta and delta-delta features from a spectrogram using DeltaDeltas', 'create a DeltaDeltas instance from a config dictionary with a custom win_length parameter', 'test the DeltaDeltas class by calling it with a 2-D spectrogram numpy array', 'refactor the DeltaDeltas class to support a configurable window length for delta computation', 'review the DeltaDeltas class and its use of torchaudio compute_deltas for audio feature expansion', 'build a GlobalCMVN instance from a config dict with a stats_npz_path key', 'create a GlobalCMVN normalizer by passing a path to a precomputed .npz stats file', 'test the GlobalCMVN call method to normalize audio features by subtracting mean and dividing by std', 'refactor the GlobalCMVN init to load mean and std from a NumPy .npz stats file', 'review the GlobalCMVN class and its cepstral mean variance normalization logic', 'create a SpecAugmentTransform instance with time warp, freq mask, and time mask parameters', 'apply the SpecAugmentTransform call method to distort a 2-D spectrogram numpy array', 'build a SpecAugmentTransform from a config dictionary with time_warp_W, freq_mask_N, and time_mask_N keys', 'review the SpecAugmentTransform time warp logic that uses cv2 resize to distort spectrogram frames', 'test the SpecAugmentTransform freq and time masking on a spectrogram with random mask regions', 'build a python module to apply utterance-level cepstral mean and variance normalization to audio features', 'create a UtteranceCMVN instance from a config dictionary with norm_means and norm_vars options', 'test the UtteranceCMVN call method to normalize a numpy array of audio features', 'refactor the UtteranceCMVN class to support additional normalization parameters beyond means and vars', 'review the UtteranceCMVN class and its cepstral mean variance normalization logic for audio feature processing']
```

Usage

```
{'build_GlobalCMVN_from_config': 'build a GlobalCMVN instance from a config dict with a stats_npz_path key', 'create_GlobalCMVN_normalizer': 'create a GlobalCMVN normalizer by passing a path to a precomputed .npz stats file', 'test_GlobalCMVN_call': 'test the GlobalCMVN call method to normalize audio features by subtracting mean and dividing by std', 'refactor_GlobalCMVN_init': 'refactor the GlobalCMVN init to load mean and std from a NumPy .npz stats file', 'review_GlobalCMVN_transform': 'review the GlobalCMVN class and its cepstral mean variance normalization logic'}
```

## File: facebookresearch_fairseq/fairseq/data/audio/feature_transforms/specaugment.py

Prompts

```
['build a python module to compute delta and delta-delta features from a spectrogram using DeltaDeltas', 'create a DeltaDeltas instance from a config dictionary with a custom win_length parameter', 'test the DeltaDeltas class by calling it with a 2-D spectrogram numpy array', 'refactor the DeltaDeltas class to support a configurable window length for delta computation', 'review the DeltaDeltas class and its use of torchaudio compute_deltas for audio feature expansion', 'build a GlobalCMVN instance from a config dict with a stats_npz_path key', 'create a GlobalCMVN normalizer by passing a path to a precomputed .npz stats file', 'test the GlobalCMVN call method to normalize audio features by subtracting mean and dividing by std', 'refactor the GlobalCMVN init to load mean and std from a NumPy .npz stats file', 'review the GlobalCMVN class and its cepstral mean variance normalization logic', 'create a SpecAugmentTransform instance with time warp, freq mask, and time mask parameters', 'apply the SpecAugmentTransform call method to distort a 2-D spectrogram numpy array', 'build a SpecAugmentTransform from a config dictionary with time_warp_W, freq_mask_N, and time_mask_N keys', 'review the SpecAugmentTransform time warp logic that uses cv2 resize to distort spectrogram frames', 'test the SpecAugmentTransform freq and time masking on a spectrogram with random mask regions', 'build a python module to apply utterance-level cepstral mean and variance normalization to audio features', 'create a UtteranceCMVN instance from a config dictionary with norm_means and norm_vars options', 'test the UtteranceCMVN call method to normalize a numpy array of audio features', 'refactor the UtteranceCMVN class to support additional normalization parameters beyond means and vars', 'review the UtteranceCMVN class and its cepstral mean variance normalization logic for audio feature processing']
```

Usage

```
{'create_specaugment_transform': 'create a SpecAugmentTransform instance with time warp, freq mask, and time mask parameters', 'apply_specaugment_to_spectrogram': 'apply the SpecAugmentTransform call method to distort a 2-D spectrogram numpy array', 'build_specaugment_from_config': 'build a SpecAugmentTransform from a config dictionary with time_warp_W, freq_mask_N, and time_mask_N keys', 'review_specaugment_time_warp': 'review the SpecAugmentTransform time warp logic that uses cv2 resize to distort spectrogram frames', 'test_specaugment_masking': 'test the SpecAugmentTransform freq and time masking on a spectrogram with random mask regions'}
```

## File: facebookresearch_fairseq/fairseq/data/audio/feature_transforms/utterance_cmvn.py

Prompts

```
['build a python module to compute delta and delta-delta features from a spectrogram using DeltaDeltas', 'create a DeltaDeltas instance from a config dictionary with a custom win_length parameter', 'test the DeltaDeltas class by calling it with a 2-D spectrogram numpy array', 'refactor the DeltaDeltas class to support a configurable window length for delta computation', 'review the DeltaDeltas class and its use of torchaudio compute_deltas for audio feature expansion', 'build a GlobalCMVN instance from a config dict with a stats_npz_path key', 'create a GlobalCMVN normalizer by passing a path to a precomputed .npz stats file', 'test the GlobalCMVN call method to normalize audio features by subtracting mean and dividing by std', 'refactor the GlobalCMVN init to load mean and std from a NumPy .npz stats file', 'review the GlobalCMVN class and its cepstral mean variance normalization logic', 'create a SpecAugmentTransform instance with time warp, freq mask, and time mask parameters', 'apply the SpecAugmentTransform call method to distort a 2-D spectrogram numpy array', 'build a SpecAugmentTransform from a config dictionary with time_warp_W, freq_mask_N, and time_mask_N keys', 'review the SpecAugmentTransform time warp logic that uses cv2 resize to distort spectrogram frames', 'test the SpecAugmentTransform freq and time masking on a spectrogram with random mask regions', 'build a python module to apply utterance-level cepstral mean and variance normalization to audio features', 'create a UtteranceCMVN instance from a config dictionary with norm_means and norm_vars options', 'test the UtteranceCMVN call method to normalize a numpy array of audio features', 'refactor the UtteranceCMVN class to support additional normalization parameters beyond means and vars', 'review the UtteranceCMVN class and its cepstral mean variance normalization logic for audio feature processing']
```

Usage

```
{'build_utterance_cmvn_transform': 'build a python module to apply utterance-level cepstral mean and variance normalization to audio features', 'create_utterance_cmvn_from_config': 'create a UtteranceCMVN instance from a config dictionary with norm_means and norm_vars options', 'test_utterance_cmvn_call': 'test the UtteranceCMVN call method to normalize a numpy array of audio features', 'refactor_utterance_cmvn_init': 'refactor the UtteranceCMVN class to support additional normalization parameters beyond means and vars', 'review_utterance_cmvn_class': 'review the UtteranceCMVN class and its cepstral mean variance normalization logic for audio feature processing'}
```

