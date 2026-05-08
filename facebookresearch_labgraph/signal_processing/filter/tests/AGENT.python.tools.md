# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/signal_processing/filter/tests/test_detrend.py

Prompts

```
['run the DetrendTest test_detrend_and_offset_positive_trend unit test for positive linear trend signals', 'run the DetrendTest test_detrend_and_offset_negative_trend unit test for negative linear trend signals', 'test the detrend_and_offset function with composite signals containing DC offset and linear trends', 'review the DetrendTest class and its test methods for signal detrending assertions', 'refactor the DetrendTest test_detrend_and_offset_negative_trend to verify fix_negative parameter behavior', 'test the fir_filter function with one-dimensional signal data and verify lowpass filtering', 'test the fir_filter function with multi-dimensional signal data stacked along axis 1', 'test the fir_filter function with column vector and row vector input shapes', 'test the fir_filter function produces linear phase delay proportional to filter order', 'check that filtered signal peak frequencies match expected values using PSD multitaper analysis', 'test the butterworth_filter function to verify highpass, lowpass, and bandpass frequency attenuation on multi-channel signals', 'test the CausalButterworth class for numerical stability when filtering long-duration low-frequency signals sample by sample', 'test that second-order section filters remain stable for narrow passbands while transfer-function filters may not', 'test the noDelay option to verify filtfilt produces zero-phase output while lfilter introduces phase delay', 'test the moving_average_convergence_divergence and exponential_moving_average functions to isolate a frequency of interest from noisy physiological signals', 'test the do_fft function on 1D signals to verify FFT magnitude at known frequencies', 'test the do_fft function on 2D and 3D arrays along a specified axis', 'test the filter_impulse_response function for both IIR SOS and FIR coefficient filters', 'test the filter_freq_response function to verify magnitude and phase of a Butterworth bandpass filter', 'test the filter_group_delay function and compare results against symmetric_fir_group_delay for FIR filters']
```

Usage

```
{'run_detrend_positive_trend_test': 'run the DetrendTest test_detrend_and_offset_positive_trend unit test for positive linear trend signals', 'run_detrend_negative_trend_test': 'run the DetrendTest test_detrend_and_offset_negative_trend unit test for negative linear trend signals', 'test_detrend_and_offset_function': 'test the detrend_and_offset function with composite signals containing DC offset and linear trends', 'review_detrend_test_class': 'review the DetrendTest class and its test methods for signal detrending assertions', 'refactor_detrend_test_fix_negative': 'refactor the DetrendTest test_detrend_and_offset_negative_trend to verify fix_negative parameter behavior'}
```

## File: facebookresearch_labgraph/signal_processing/filter/tests/test_fir_filters.py

Prompts

```
['run the DetrendTest test_detrend_and_offset_positive_trend unit test for positive linear trend signals', 'run the DetrendTest test_detrend_and_offset_negative_trend unit test for negative linear trend signals', 'test the detrend_and_offset function with composite signals containing DC offset and linear trends', 'review the DetrendTest class and its test methods for signal detrending assertions', 'refactor the DetrendTest test_detrend_and_offset_negative_trend to verify fix_negative parameter behavior', 'test the fir_filter function with one-dimensional signal data and verify lowpass filtering', 'test the fir_filter function with multi-dimensional signal data stacked along axis 1', 'test the fir_filter function with column vector and row vector input shapes', 'test the fir_filter function produces linear phase delay proportional to filter order', 'check that filtered signal peak frequencies match expected values using PSD multitaper analysis', 'test the butterworth_filter function to verify highpass, lowpass, and bandpass frequency attenuation on multi-channel signals', 'test the CausalButterworth class for numerical stability when filtering long-duration low-frequency signals sample by sample', 'test that second-order section filters remain stable for narrow passbands while transfer-function filters may not', 'test the noDelay option to verify filtfilt produces zero-phase output while lfilter introduces phase delay', 'test the moving_average_convergence_divergence and exponential_moving_average functions to isolate a frequency of interest from noisy physiological signals', 'test the do_fft function on 1D signals to verify FFT magnitude at known frequencies', 'test the do_fft function on 2D and 3D arrays along a specified axis', 'test the filter_impulse_response function for both IIR SOS and FIR coefficient filters', 'test the filter_freq_response function to verify magnitude and phase of a Butterworth bandpass filter', 'test the filter_group_delay function and compare results against symmetric_fir_group_delay for FIR filters']
```

Usage

```
{'test_fir_filter_1D': 'test the fir_filter function with one-dimensional signal data and verify lowpass filtering', 'test_fir_filter_nD': 'test the fir_filter function with multi-dimensional signal data stacked along axis 1', 'test_fir_filter_axis': 'test the fir_filter function with column vector and row vector input shapes', 'test_fir_filter_linearPhase': 'test the fir_filter function produces linear phase delay proportional to filter order', 'check_peak_freq': 'check that filtered signal peak frequencies match expected values using PSD multitaper analysis'}
```

## File: facebookresearch_labgraph/signal_processing/filter/tests/test_iir_filters.py

Prompts

```
['run the DetrendTest test_detrend_and_offset_positive_trend unit test for positive linear trend signals', 'run the DetrendTest test_detrend_and_offset_negative_trend unit test for negative linear trend signals', 'test the detrend_and_offset function with composite signals containing DC offset and linear trends', 'review the DetrendTest class and its test methods for signal detrending assertions', 'refactor the DetrendTest test_detrend_and_offset_negative_trend to verify fix_negative parameter behavior', 'test the fir_filter function with one-dimensional signal data and verify lowpass filtering', 'test the fir_filter function with multi-dimensional signal data stacked along axis 1', 'test the fir_filter function with column vector and row vector input shapes', 'test the fir_filter function produces linear phase delay proportional to filter order', 'check that filtered signal peak frequencies match expected values using PSD multitaper analysis', 'test the butterworth_filter function to verify highpass, lowpass, and bandpass frequency attenuation on multi-channel signals', 'test the CausalButterworth class for numerical stability when filtering long-duration low-frequency signals sample by sample', 'test that second-order section filters remain stable for narrow passbands while transfer-function filters may not', 'test the noDelay option to verify filtfilt produces zero-phase output while lfilter introduces phase delay', 'test the moving_average_convergence_divergence and exponential_moving_average functions to isolate a frequency of interest from noisy physiological signals', 'test the do_fft function on 1D signals to verify FFT magnitude at known frequencies', 'test the do_fft function on 2D and 3D arrays along a specified axis', 'test the filter_impulse_response function for both IIR SOS and FIR coefficient filters', 'test the filter_freq_response function to verify magnitude and phase of a Butterworth bandpass filter', 'test the filter_group_delay function and compare results against symmetric_fir_group_delay for FIR filters']
```

Usage

```
{'test_butterworth_filter_attenuation': 'test the butterworth_filter function to verify highpass, lowpass, and bandpass frequency attenuation on multi-channel signals', 'test_causal_butterworth_stability': 'test the CausalButterworth class for numerical stability when filtering long-duration low-frequency signals sample by sample', 'test_butterworth_sos_vs_tf_stability': 'test that second-order section filters remain stable for narrow passbands while transfer-function filters may not', 'test_butterworth_filter_phase_delay': 'test the noDelay option to verify filtfilt produces zero-phase output while lfilter introduces phase delay', 'test_macd_ema_signal_processing': 'test the moving_average_convergence_divergence and exponential_moving_average functions to isolate a frequency of interest from noisy physiological signals'}
```

## File: facebookresearch_labgraph/signal_processing/filter/tests/test_signal_transforms.py

Prompts

```
['run the DetrendTest test_detrend_and_offset_positive_trend unit test for positive linear trend signals', 'run the DetrendTest test_detrend_and_offset_negative_trend unit test for negative linear trend signals', 'test the detrend_and_offset function with composite signals containing DC offset and linear trends', 'review the DetrendTest class and its test methods for signal detrending assertions', 'refactor the DetrendTest test_detrend_and_offset_negative_trend to verify fix_negative parameter behavior', 'test the fir_filter function with one-dimensional signal data and verify lowpass filtering', 'test the fir_filter function with multi-dimensional signal data stacked along axis 1', 'test the fir_filter function with column vector and row vector input shapes', 'test the fir_filter function produces linear phase delay proportional to filter order', 'check that filtered signal peak frequencies match expected values using PSD multitaper analysis', 'test the butterworth_filter function to verify highpass, lowpass, and bandpass frequency attenuation on multi-channel signals', 'test the CausalButterworth class for numerical stability when filtering long-duration low-frequency signals sample by sample', 'test that second-order section filters remain stable for narrow passbands while transfer-function filters may not', 'test the noDelay option to verify filtfilt produces zero-phase output while lfilter introduces phase delay', 'test the moving_average_convergence_divergence and exponential_moving_average functions to isolate a frequency of interest from noisy physiological signals', 'test the do_fft function on 1D signals to verify FFT magnitude at known frequencies', 'test the do_fft function on 2D and 3D arrays along a specified axis', 'test the filter_impulse_response function for both IIR SOS and FIR coefficient filters', 'test the filter_freq_response function to verify magnitude and phase of a Butterworth bandpass filter', 'test the filter_group_delay function and compare results against symmetric_fir_group_delay for FIR filters']
```

Usage

```
{'test_do_fft_1D': 'test the do_fft function on 1D signals to verify FFT magnitude at known frequencies', 'test_do_fft_multidimensional': 'test the do_fft function on 2D and 3D arrays along a specified axis', 'test_filter_impulse_response': 'test the filter_impulse_response function for both IIR SOS and FIR coefficient filters', 'test_filter_freq_response': 'test the filter_freq_response function to verify magnitude and phase of a Butterworth bandpass filter', 'test_filter_group_delay': 'test the filter_group_delay function and compare results against symmetric_fir_group_delay for FIR filters'}
```

