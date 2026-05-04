# Agent Python Tools

- repo: facebookresearch/augly
- repo_uri: https://github.com/facebookresearch/augly

## File: facebookresearch_augly/augly/tests/audio_tests/base_unit_test.py

Prompts

```
['test an audio augmentation function against expected mono and stereo reference WAV outputs', 'test an audio transform class by comparing its output and metadata to expected reference audio', 'compare two numpy audio arrays for equality using a tolerance-based allclose check', 'load a reference WAV audio file from the expected output directory using librosa', 'load input audio files and sample rates into class-level fixtures for audio unit tests', 'test the add_background_noise function that mixes background audio into audio with a given SNR level', 'test the pitch_shift function that shifts audio pitch by a specified number of semitone steps', 'test the speed function that changes audio playback speed by a given factor', 'test the reverb function that applies reverberation effects to audio with a specified reverberance level', 'test the high_pass_filter function that filters audio frequencies below a specified cutoff in Hz', 'run the IntensityAudioUnitTest suite to verify all audio augmentation intensity calculations', 'test the add_background_noise_intensity function with a given snr_level_db value', 'test the change_volume_intensity function with a specified volume_db parameter', 'test the reverb_intensity function with reverberance, wet_only, and room_scale parameters', 'test the pitch_shift_intensity function with a specified n_steps value', 'run the unittest suite for all AugLy audio augmentation transforms', 'test composing multiple audio transforms like Clip and ChangeVolume in sequence', 'test randomly selecting one audio transform from a list of candidates', 'test the PitchShift audio augmentation transform with a specified number of semitone steps', 'test the TimeStretch audio augmentation transform with a specified stretch rate']
```

Usage

```
{'test_audio_augmentation_function': 'test an audio augmentation function against expected mono and stereo reference WAV outputs', 'test_audio_transform_class': 'test an audio transform class by comparing its output and metadata to expected reference audio', 'compare_audio_arrays': 'compare two numpy audio arrays for equality using a tolerance-based allclose check', 'load_reference_audio': 'load a reference WAV audio file from the expected output directory using librosa', 'setup_audio_test_fixtures': 'load input audio files and sample rates into class-level fixtures for audio unit tests'}
```

## File: facebookresearch_augly/augly/tests/audio_tests/functional_unit_test.py

Prompts

```
['test an audio augmentation function against expected mono and stereo reference WAV outputs', 'test an audio transform class by comparing its output and metadata to expected reference audio', 'compare two numpy audio arrays for equality using a tolerance-based allclose check', 'load a reference WAV audio file from the expected output directory using librosa', 'load input audio files and sample rates into class-level fixtures for audio unit tests', 'test the add_background_noise function that mixes background audio into audio with a given SNR level', 'test the pitch_shift function that shifts audio pitch by a specified number of semitone steps', 'test the speed function that changes audio playback speed by a given factor', 'test the reverb function that applies reverberation effects to audio with a specified reverberance level', 'test the high_pass_filter function that filters audio frequencies below a specified cutoff in Hz', 'run the IntensityAudioUnitTest suite to verify all audio augmentation intensity calculations', 'test the add_background_noise_intensity function with a given snr_level_db value', 'test the change_volume_intensity function with a specified volume_db parameter', 'test the reverb_intensity function with reverberance, wet_only, and room_scale parameters', 'test the pitch_shift_intensity function with a specified n_steps value', 'run the unittest suite for all AugLy audio augmentation transforms', 'test composing multiple audio transforms like Clip and ChangeVolume in sequence', 'test randomly selecting one audio transform from a list of candidates', 'test the PitchShift audio augmentation transform with a specified number of semitone steps', 'test the TimeStretch audio augmentation transform with a specified stretch rate']
```

Usage

```
{'test_add_background_noise': 'test the add_background_noise function that mixes background audio into audio with a given SNR level', 'test_pitch_shift': 'test the pitch_shift function that shifts audio pitch by a specified number of semitone steps', 'test_speed': 'test the speed function that changes audio playback speed by a given factor', 'test_reverb': 'test the reverb function that applies reverberation effects to audio with a specified reverberance level', 'test_high_pass_filter': 'test the high_pass_filter function that filters audio frequencies below a specified cutoff in Hz'}
```

## File: facebookresearch_augly/augly/tests/audio_tests/intensity_unit_test.py

Prompts

```
['test an audio augmentation function against expected mono and stereo reference WAV outputs', 'test an audio transform class by comparing its output and metadata to expected reference audio', 'compare two numpy audio arrays for equality using a tolerance-based allclose check', 'load a reference WAV audio file from the expected output directory using librosa', 'load input audio files and sample rates into class-level fixtures for audio unit tests', 'test the add_background_noise function that mixes background audio into audio with a given SNR level', 'test the pitch_shift function that shifts audio pitch by a specified number of semitone steps', 'test the speed function that changes audio playback speed by a given factor', 'test the reverb function that applies reverberation effects to audio with a specified reverberance level', 'test the high_pass_filter function that filters audio frequencies below a specified cutoff in Hz', 'run the IntensityAudioUnitTest suite to verify all audio augmentation intensity calculations', 'test the add_background_noise_intensity function with a given snr_level_db value', 'test the change_volume_intensity function with a specified volume_db parameter', 'test the reverb_intensity function with reverberance, wet_only, and room_scale parameters', 'test the pitch_shift_intensity function with a specified n_steps value', 'run the unittest suite for all AugLy audio augmentation transforms', 'test composing multiple audio transforms like Clip and ChangeVolume in sequence', 'test randomly selecting one audio transform from a list of candidates', 'test the PitchShift audio augmentation transform with a specified number of semitone steps', 'test the TimeStretch audio augmentation transform with a specified stretch rate']
```

Usage

```
{'test_intensity_unit_tests': 'run the IntensityAudioUnitTest suite to verify all audio augmentation intensity calculations', 'test_add_background_noise_intensity': 'test the add_background_noise_intensity function with a given snr_level_db value', 'test_change_volume_intensity': 'test the change_volume_intensity function with a specified volume_db parameter', 'test_reverb_intensity': 'test the reverb_intensity function with reverberance, wet_only, and room_scale parameters', 'test_pitch_shift_intensity': 'test the pitch_shift_intensity function with a specified n_steps value'}
```

## File: facebookresearch_augly/augly/tests/audio_tests/transforms_unit_test.py

Prompts

```
['test an audio augmentation function against expected mono and stereo reference WAV outputs', 'test an audio transform class by comparing its output and metadata to expected reference audio', 'compare two numpy audio arrays for equality using a tolerance-based allclose check', 'load a reference WAV audio file from the expected output directory using librosa', 'load input audio files and sample rates into class-level fixtures for audio unit tests', 'test the add_background_noise function that mixes background audio into audio with a given SNR level', 'test the pitch_shift function that shifts audio pitch by a specified number of semitone steps', 'test the speed function that changes audio playback speed by a given factor', 'test the reverb function that applies reverberation effects to audio with a specified reverberance level', 'test the high_pass_filter function that filters audio frequencies below a specified cutoff in Hz', 'run the IntensityAudioUnitTest suite to verify all audio augmentation intensity calculations', 'test the add_background_noise_intensity function with a given snr_level_db value', 'test the change_volume_intensity function with a specified volume_db parameter', 'test the reverb_intensity function with reverberance, wet_only, and room_scale parameters', 'test the pitch_shift_intensity function with a specified n_steps value', 'run the unittest suite for all AugLy audio augmentation transforms', 'test composing multiple audio transforms like Clip and ChangeVolume in sequence', 'test randomly selecting one audio transform from a list of candidates', 'test the PitchShift audio augmentation transform with a specified number of semitone steps', 'test the TimeStretch audio augmentation transform with a specified stretch rate']
```

Usage

```
{'run_audio_transforms_unit_tests': 'run the unittest suite for all AugLy audio augmentation transforms', 'test_Compose_audio_transforms': 'test composing multiple audio transforms like Clip and ChangeVolume in sequence', 'test_OneOf_audio_transforms': 'test randomly selecting one audio transform from a list of candidates', 'test_PitchShift_transform': 'test the PitchShift audio augmentation transform with a specified number of semitone steps', 'test_TimeStretch_transform': 'test the TimeStretch audio augmentation transform with a specified stretch rate'}
```

