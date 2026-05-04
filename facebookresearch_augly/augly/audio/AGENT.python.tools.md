# Agent Python Tools

- repo: facebookresearch/augly
- repo_uri: https://github.com/facebookresearch/augly

## File: facebookresearch_augly/augly/audio/functional.py

Prompts

```
['add background noise or white noise to an audio file with a configurable signal-to-noise ratio in dB', 'shift the pitch of an audio clip up or down by a given number of semitone steps', 'speed up or slow down an audio clip by a fixed rate without changing its pitch', 'add reverberation effects to audio with configurable room scale, damping, stereo depth, and wet gain', 'apply FFT-based convolution to audio using a custom impulse response or random impulse as the filter', 'compute the intensity score for adding background noise to audio given an SNR level in dB', 'compute the intensity score for changing audio volume given a decibel adjustment value', 'compute the intensity score for pitch shifting audio given the number of semitone steps', 'compute the intensity score for applying reverb to audio given reverberance and room scale parameters', 'compute the intensity score for changing audio playback speed given a speed factor multiplier', 'build a python module that applies PitchShift and Speed transforms to an audio numpy array', 'create a python script that adds background noise to audio using AddBackgroundNoise with a custom SNR level', 'apply HighPassFilter and LowPassFilter transforms to an audio array to isolate a frequency band', 'add reverberation to an audio numpy array using the Reverb transform with custom room scale and damping', 'build a python module that clips audio to a segment using the Clip transform with offset and duration factors', 'load an audio file from a path string and return the numpy array and sample rate', 'save a numpy audio array to an output file path with the given sample rate', 'convert a seed integer or RandomState into a numpy random state instance for reproducibility', 'append metadata about an audio transform including duration, channels, sample rate, and intensity to a list', 'compute source and destination time segments for audio transforms like speed, tempo, or time stretch']
```

Usage

```
{'add_background_noise': 'add background noise or white noise to an audio file with a configurable signal-to-noise ratio in dB', 'pitch_shift': 'shift the pitch of an audio clip up or down by a given number of semitone steps', 'time_stretch': 'speed up or slow down an audio clip by a fixed rate without changing its pitch', 'reverb': 'add reverberation effects to audio with configurable room scale, damping, stereo depth, and wet gain', 'fft_convolve': 'apply FFT-based convolution to audio using a custom impulse response or random impulse as the filter'}
```

## File: facebookresearch_augly/augly/audio/intensity.py

Prompts

```
['add background noise or white noise to an audio file with a configurable signal-to-noise ratio in dB', 'shift the pitch of an audio clip up or down by a given number of semitone steps', 'speed up or slow down an audio clip by a fixed rate without changing its pitch', 'add reverberation effects to audio with configurable room scale, damping, stereo depth, and wet gain', 'apply FFT-based convolution to audio using a custom impulse response or random impulse as the filter', 'compute the intensity score for adding background noise to audio given an SNR level in dB', 'compute the intensity score for changing audio volume given a decibel adjustment value', 'compute the intensity score for pitch shifting audio given the number of semitone steps', 'compute the intensity score for applying reverb to audio given reverberance and room scale parameters', 'compute the intensity score for changing audio playback speed given a speed factor multiplier', 'build a python module that applies PitchShift and Speed transforms to an audio numpy array', 'create a python script that adds background noise to audio using AddBackgroundNoise with a custom SNR level', 'apply HighPassFilter and LowPassFilter transforms to an audio array to isolate a frequency band', 'add reverberation to an audio numpy array using the Reverb transform with custom room scale and damping', 'build a python module that clips audio to a segment using the Clip transform with offset and duration factors', 'load an audio file from a path string and return the numpy array and sample rate', 'save a numpy audio array to an output file path with the given sample rate', 'convert a seed integer or RandomState into a numpy random state instance for reproducibility', 'append metadata about an audio transform including duration, channels, sample rate, and intensity to a list', 'compute source and destination time segments for audio transforms like speed, tempo, or time stretch']
```

Usage

```
{'compute_add_background_noise_intensity': 'compute the intensity score for adding background noise to audio given an SNR level in dB', 'compute_change_volume_intensity': 'compute the intensity score for changing audio volume given a decibel adjustment value', 'compute_pitch_shift_intensity': 'compute the intensity score for pitch shifting audio given the number of semitone steps', 'compute_reverb_intensity': 'compute the intensity score for applying reverb to audio given reverberance and room scale parameters', 'compute_speed_intensity': 'compute the intensity score for changing audio playback speed given a speed factor multiplier'}
```

## File: facebookresearch_augly/augly/audio/transforms.py

Prompts

```
['add background noise or white noise to an audio file with a configurable signal-to-noise ratio in dB', 'shift the pitch of an audio clip up or down by a given number of semitone steps', 'speed up or slow down an audio clip by a fixed rate without changing its pitch', 'add reverberation effects to audio with configurable room scale, damping, stereo depth, and wet gain', 'apply FFT-based convolution to audio using a custom impulse response or random impulse as the filter', 'compute the intensity score for adding background noise to audio given an SNR level in dB', 'compute the intensity score for changing audio volume given a decibel adjustment value', 'compute the intensity score for pitch shifting audio given the number of semitone steps', 'compute the intensity score for applying reverb to audio given reverberance and room scale parameters', 'compute the intensity score for changing audio playback speed given a speed factor multiplier', 'build a python module that applies PitchShift and Speed transforms to an audio numpy array', 'create a python script that adds background noise to audio using AddBackgroundNoise with a custom SNR level', 'apply HighPassFilter and LowPassFilter transforms to an audio array to isolate a frequency band', 'add reverberation to an audio numpy array using the Reverb transform with custom room scale and damping', 'build a python module that clips audio to a segment using the Clip transform with offset and duration factors', 'load an audio file from a path string and return the numpy array and sample rate', 'save a numpy audio array to an output file path with the given sample rate', 'convert a seed integer or RandomState into a numpy random state instance for reproducibility', 'append metadata about an audio transform including duration, channels, sample rate, and intensity to a list', 'compute source and destination time segments for audio transforms like speed, tempo, or time stretch']
```

Usage

```
{'build_audio_augmentation_pipeline': 'build a python module that applies PitchShift and Speed transforms to an audio numpy array', 'create_background_noise_augmentation': 'create a python script that adds background noise to audio using AddBackgroundNoise with a custom SNR level', 'apply_audio_filters': 'apply HighPassFilter and LowPassFilter transforms to an audio array to isolate a frequency band', 'add_reverb_to_audio': 'add reverberation to an audio numpy array using the Reverb transform with custom room scale and damping', 'build_audio_clipping_tool': 'build a python module that clips audio to a segment using the Clip transform with offset and duration factors'}
```

## File: facebookresearch_augly/augly/audio/utils.py

Prompts

```
['add background noise or white noise to an audio file with a configurable signal-to-noise ratio in dB', 'shift the pitch of an audio clip up or down by a given number of semitone steps', 'speed up or slow down an audio clip by a fixed rate without changing its pitch', 'add reverberation effects to audio with configurable room scale, damping, stereo depth, and wet gain', 'apply FFT-based convolution to audio using a custom impulse response or random impulse as the filter', 'compute the intensity score for adding background noise to audio given an SNR level in dB', 'compute the intensity score for changing audio volume given a decibel adjustment value', 'compute the intensity score for pitch shifting audio given the number of semitone steps', 'compute the intensity score for applying reverb to audio given reverberance and room scale parameters', 'compute the intensity score for changing audio playback speed given a speed factor multiplier', 'build a python module that applies PitchShift and Speed transforms to an audio numpy array', 'create a python script that adds background noise to audio using AddBackgroundNoise with a custom SNR level', 'apply HighPassFilter and LowPassFilter transforms to an audio array to isolate a frequency band', 'add reverberation to an audio numpy array using the Reverb transform with custom room scale and damping', 'build a python module that clips audio to a segment using the Clip transform with offset and duration factors', 'load an audio file from a path string and return the numpy array and sample rate', 'save a numpy audio array to an output file path with the given sample rate', 'convert a seed integer or RandomState into a numpy random state instance for reproducibility', 'append metadata about an audio transform including duration, channels, sample rate, and intensity to a list', 'compute source and destination time segments for audio transforms like speed, tempo, or time stretch']
```

Usage

```
{'load_audio_from_path': 'load an audio file from a path string and return the numpy array and sample rate', 'save_audio_to_file': 'save a numpy audio array to an output file path with the given sample rate', 'check_random_state': 'convert a seed integer or RandomState into a numpy random state instance for reproducibility', 'get_metadata_for_transform': 'append metadata about an audio transform including duration, channels, sample rate, and intensity to a list', 'compute_segments_for_transform': 'compute source and destination time segments for audio transforms like speed, tempo, or time stretch'}
```

