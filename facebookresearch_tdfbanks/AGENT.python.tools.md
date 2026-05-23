# Agent Python Tools

- repo: facebookresearch/tdfbanks
- repo_uri: https://github.com/facebookresearch/tdfbanks

## File: facebookresearch_tdfbanks/melfilters.py

Prompts

```
['create a Gabor object with 40 mel filters for audio feature extraction at 16kHz sample rate', 'build a mel filter bank matrix by calling Gabor._build_mels() to generate triangular filters in the mel scale', 'build Gabor wavelet filters from mel filter parameters using Gabor._build_gabors() for time-frequency analysis', 'convert a frequency in hertz to the mel scale using Gabor._hz2mel() for perceptual audio analysis', 'compute the energy of a mel filter by calling Gabor._melfilter_energy() to get area under the magnitude spectrum', 'create a TDFbanks module in Fixed mode with 64 filters for audio feature extraction', 'create a TDFbanks module in learnfbanks mode with preemphasis and instance normalization enabled', 'initialize the TDFbanks complex convolution weights using Gabor filters with a specified frequency range', 'run the TDFbanks forward pass on an audio waveform tensor to extract time-domain filterbank features', 'review the TDFbanks class architecture including complex convolution, squared modulus, and log compression layers', 'create a linear chirp signal from frequency f0 to f1 over duration T at sampling rate fs', 'create a Hanning window array of length N for signal processing', 'create a Hamming window array of length N for signal processing', 'test the chirp function by generating a signal between 100Hz and 1000Hz over 1 second', 'test the window function by generating a Hanning window of length 1024']
```

Usage

```
{'create_Gabor_instance': 'create a Gabor object with 40 mel filters for audio feature extraction at 16kHz sample rate', 'build_mel_filters': 'build a mel filter bank matrix by calling Gabor._build_mels() to generate triangular filters in the mel scale', 'build_gabor_wavelets': 'build Gabor wavelet filters from mel filter parameters using Gabor._build_gabors() for time-frequency analysis', 'convert_hz_to_mel': 'convert a frequency in hertz to the mel scale using Gabor._hz2mel() for perceptual audio analysis', 'compute_mel_filter_energy': 'compute the energy of a mel filter by calling Gabor._melfilter_energy() to get area under the magnitude spectrum'}
```

## File: facebookresearch_tdfbanks/model.py

Prompts

```
['create a Gabor object with 40 mel filters for audio feature extraction at 16kHz sample rate', 'build a mel filter bank matrix by calling Gabor._build_mels() to generate triangular filters in the mel scale', 'build Gabor wavelet filters from mel filter parameters using Gabor._build_gabors() for time-frequency analysis', 'convert a frequency in hertz to the mel scale using Gabor._hz2mel() for perceptual audio analysis', 'compute the energy of a mel filter by calling Gabor._melfilter_energy() to get area under the magnitude spectrum', 'create a TDFbanks module in Fixed mode with 64 filters for audio feature extraction', 'create a TDFbanks module in learnfbanks mode with preemphasis and instance normalization enabled', 'initialize the TDFbanks complex convolution weights using Gabor filters with a specified frequency range', 'run the TDFbanks forward pass on an audio waveform tensor to extract time-domain filterbank features', 'review the TDFbanks class architecture including complex convolution, squared modulus, and log compression layers', 'create a linear chirp signal from frequency f0 to f1 over duration T at sampling rate fs', 'create a Hanning window array of length N for signal processing', 'create a Hamming window array of length N for signal processing', 'test the chirp function by generating a signal between 100Hz and 1000Hz over 1 second', 'test the window function by generating a Hanning window of length 1024']
```

Usage

```
{'create_TDFbanks_Fixed': 'create a TDFbanks module in Fixed mode with 64 filters for audio feature extraction', 'create_TDFbanks_learnfbanks': 'create a TDFbanks module in learnfbanks mode with preemphasis and instance normalization enabled', 'initialize_TDFbanks_Gabor': 'initialize the TDFbanks complex convolution weights using Gabor filters with a specified frequency range', 'run_TDFbanks_forward': 'run the TDFbanks forward pass on an audio waveform tensor to extract time-domain filterbank features', 'review_TDFbanks_architecture': 'review the TDFbanks class architecture including complex convolution, squared modulus, and log compression layers'}
```

## File: facebookresearch_tdfbanks/utils.py

Prompts

```
['create a Gabor object with 40 mel filters for audio feature extraction at 16kHz sample rate', 'build a mel filter bank matrix by calling Gabor._build_mels() to generate triangular filters in the mel scale', 'build Gabor wavelet filters from mel filter parameters using Gabor._build_gabors() for time-frequency analysis', 'convert a frequency in hertz to the mel scale using Gabor._hz2mel() for perceptual audio analysis', 'compute the energy of a mel filter by calling Gabor._melfilter_energy() to get area under the magnitude spectrum', 'create a TDFbanks module in Fixed mode with 64 filters for audio feature extraction', 'create a TDFbanks module in learnfbanks mode with preemphasis and instance normalization enabled', 'initialize the TDFbanks complex convolution weights using Gabor filters with a specified frequency range', 'run the TDFbanks forward pass on an audio waveform tensor to extract time-domain filterbank features', 'review the TDFbanks class architecture including complex convolution, squared modulus, and log compression layers', 'create a linear chirp signal from frequency f0 to f1 over duration T at sampling rate fs', 'create a Hanning window array of length N for signal processing', 'create a Hamming window array of length N for signal processing', 'test the chirp function by generating a signal between 100Hz and 1000Hz over 1 second', 'test the window function by generating a Hanning window of length 1024']
```

Usage

```
{'create_chirp_signal': 'create a linear chirp signal from frequency f0 to f1 over duration T at sampling rate fs', 'create_hanning_window': 'create a Hanning window array of length N for signal processing', 'create_hamming_window': 'create a Hamming window array of length N for signal processing', 'test_chirp_function': 'test the chirp function by generating a signal between 100Hz and 1000Hz over 1 second', 'test_window_function': 'test the window function by generating a Hanning window of length 1024'}
```

