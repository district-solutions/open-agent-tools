# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/signal_processing/synthetic_data/additive_synth_dataset.py

Prompts

```
['create a synthetic fNIRS finger-tapping dataset with configurable trials, channels, and class proportions', 'generate synthetic fNIRS trial data combining HRF signal, physiological noise, measurement noise, and motion artifacts', 'simulate physiological noise with configurable frequency and amplitude parameters for five components', 'generate a hemodynamic response function signal with configurable amplitude and scaling factor', 'compute HRF scaling weights from source-detector channel distances using cutoff thresholds', 'create an AdditiveSynthDatasetVariant synthetic fNIRS dataset with trials, channels, and class labels', 'generate simulated motion artifact noise with pulse, shift, low-frequency oscillation, and spike components', 'generate simulated hemodynamics using a double-gamma HRF over a given duration and sample rate', 'generate dummy physiological noise as a sine wave at a specified frequency, amplitude, and phase', 'compute a hemodynamic response function as a linear combination of two gamma distributions', 'compute the gamma probability density function using shape and rate parameterization instead of scale']
```

Usage

```
{'create_AdditiveSynthDataset': 'create a synthetic fNIRS finger-tapping dataset with configurable trials, channels, and class proportions', 'generate_synth_data': 'generate synthetic fNIRS trial data combining HRF signal, physiological noise, measurement noise, and motion artifacts', 'sim_physio_noise': 'simulate physiological noise with configurable frequency and amplitude parameters for five components', 'generate_hrf': 'generate a hemodynamic response function signal with configurable amplitude and scaling factor', 'hrf_scale_from_channel_dists': 'compute HRF scaling weights from source-detector channel distances using cutoff thresholds'}
```

## File: facebookresearch_labgraph/signal_processing/synthetic_data/additive_synth_dataset_variant.py

Prompts

```
['create a synthetic fNIRS finger-tapping dataset with configurable trials, channels, and class proportions', 'generate synthetic fNIRS trial data combining HRF signal, physiological noise, measurement noise, and motion artifacts', 'simulate physiological noise with configurable frequency and amplitude parameters for five components', 'generate a hemodynamic response function signal with configurable amplitude and scaling factor', 'compute HRF scaling weights from source-detector channel distances using cutoff thresholds', 'create an AdditiveSynthDatasetVariant synthetic fNIRS dataset with trials, channels, and class labels', 'generate simulated motion artifact noise with pulse, shift, low-frequency oscillation, and spike components', 'generate simulated hemodynamics using a double-gamma HRF over a given duration and sample rate', 'generate dummy physiological noise as a sine wave at a specified frequency, amplitude, and phase', 'compute a hemodynamic response function as a linear combination of two gamma distributions', 'compute the gamma probability density function using shape and rate parameterization instead of scale']
```

Usage

```
{'create_AdditiveSynthDatasetVariant': 'create an AdditiveSynthDatasetVariant synthetic fNIRS dataset with trials, channels, and class labels', 'generate_synth_data': 'generate synthetic fNIRS data combining HRF signal, physiological noise, measurement noise, and motion artifacts', 'generate_motion_noise': 'generate simulated motion artifact noise with pulse, shift, low-frequency oscillation, and spike components', 'sim_physio_noise': 'simulate physiological noise with configurable frequency and amplitude bands for heart rate and respiration', 'hrf_scale_from_channel_dists': 'compute HRF scale attenuation factors from source-detector channel distance array values'}
```

## File: facebookresearch_labgraph/signal_processing/synthetic_data/dummy_generator.py

Prompts

```
['create a synthetic fNIRS finger-tapping dataset with configurable trials, channels, and class proportions', 'generate synthetic fNIRS trial data combining HRF signal, physiological noise, measurement noise, and motion artifacts', 'simulate physiological noise with configurable frequency and amplitude parameters for five components', 'generate a hemodynamic response function signal with configurable amplitude and scaling factor', 'compute HRF scaling weights from source-detector channel distances using cutoff thresholds', 'create an AdditiveSynthDatasetVariant synthetic fNIRS dataset with trials, channels, and class labels', 'generate simulated motion artifact noise with pulse, shift, low-frequency oscillation, and spike components', 'generate simulated hemodynamics using a double-gamma HRF over a given duration and sample rate', 'generate dummy physiological noise as a sine wave at a specified frequency, amplitude, and phase', 'compute a hemodynamic response function as a linear combination of two gamma distributions', 'compute the gamma probability density function using shape and rate parameterization instead of scale']
```

Usage

```
{'generate_simulated_hemodynamics': 'generate simulated hemodynamics using a double-gamma HRF over a given duration and sample rate', 'generate_dummy_physiological_noise': 'generate dummy physiological noise as a sine wave at a specified frequency, amplitude, and phase', 'generate_motion_noise': 'generate motion noise artifacts as a linear drift at a random temporal position in the signal', 'compute_double_gamma_hrf': 'compute a hemodynamic response function as a linear combination of two gamma distributions', 'compute_gamma_pdf': 'compute the gamma probability density function using shape and rate parameterization instead of scale'}
```

