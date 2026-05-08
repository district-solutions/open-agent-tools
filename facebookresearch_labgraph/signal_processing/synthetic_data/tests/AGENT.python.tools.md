# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/signal_processing/synthetic_data/tests/test_additive_synth_dataset_variant.py

Prompts

```
['test the generate_synth_data function to verify trial length equals sample_rate times trial_length', 'test AdditiveSynthDatasetVariant with multiple channels, class labels, and HRF scale conditions', 'test hrf_scale_from_channel_dists to compute HRF scales from a list of channel distance values', 'review the AdditiveSynthDatasetVariant class constructor parameters including n_trials, trial_length, channel_dists, class_labels, hrf_scale_for_cond, and sample_rate', 'summarize the generate_synth_data function which takes hrf_scale, sample_rate, and trial_length to produce synthetic signal data', 'test the simulated_hemodynamics function that generates double-gamma HRF signals with configurable amplitude, duration, and sample rate', 'test the dummy_physiological_noise function that generates cardiac-like noise at a specified frequency and phase', 'test the motion_noise function that generates random motion artifacts with configurable amplitude and duration', 'test the _make_time_index helper that creates time series indices from duration and sample rate parameters', 'test the powerlaw_psd_gaussian function that generates 1/f pink noise and verify spectral power decreases with frequency']
```

Usage

```
{'test_generate_synth_data': 'test the generate_synth_data function to verify trial length equals sample_rate times trial_length', 'test_AdditiveSynthDatasetVariant_multiple_channels': 'test AdditiveSynthDatasetVariant with multiple channels, class labels, and HRF scale conditions', 'test_hrf_scale_from_channel_dists': 'test hrf_scale_from_channel_dists to compute HRF scales from a list of channel distance values', 'review_AdditiveSynthDatasetVariant': 'review the AdditiveSynthDatasetVariant class constructor parameters including n_trials, trial_length, channel_dists, class_labels, hrf_scale_for_cond, and sample_rate', 'summarize_generate_synth_data': 'summarize the generate_synth_data function which takes hrf_scale, sample_rate, and trial_length to produce synthetic signal data'}
```

## File: facebookresearch_labgraph/signal_processing/synthetic_data/tests/test_dummy_generator.py

Prompts

```
['test the generate_synth_data function to verify trial length equals sample_rate times trial_length', 'test AdditiveSynthDatasetVariant with multiple channels, class labels, and HRF scale conditions', 'test hrf_scale_from_channel_dists to compute HRF scales from a list of channel distance values', 'review the AdditiveSynthDatasetVariant class constructor parameters including n_trials, trial_length, channel_dists, class_labels, hrf_scale_for_cond, and sample_rate', 'summarize the generate_synth_data function which takes hrf_scale, sample_rate, and trial_length to produce synthetic signal data', 'test the simulated_hemodynamics function that generates double-gamma HRF signals with configurable amplitude, duration, and sample rate', 'test the dummy_physiological_noise function that generates cardiac-like noise at a specified frequency and phase', 'test the motion_noise function that generates random motion artifacts with configurable amplitude and duration', 'test the _make_time_index helper that creates time series indices from duration and sample rate parameters', 'test the powerlaw_psd_gaussian function that generates 1/f pink noise and verify spectral power decreases with frequency']
```

Usage

```
{'test_simulated_hemodynamics': 'test the simulated_hemodynamics function that generates double-gamma HRF signals with configurable amplitude, duration, and sample rate', 'test_dummy_physiological_noise': 'test the dummy_physiological_noise function that generates cardiac-like noise at a specified frequency and phase', 'test_motion_noise': 'test the motion_noise function that generates random motion artifacts with configurable amplitude and duration', 'test_time_index': 'test the _make_time_index helper that creates time series indices from duration and sample rate parameters', 'test_pink_noise': 'test the powerlaw_psd_gaussian function that generates 1/f pink noise and verify spectral power decreases with frequency'}
```

