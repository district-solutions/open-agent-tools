# Agent Python Tools

- repo: facebookresearch/audiocraft
- repo_uri: https://github.com/facebookresearch/audiocraft.git

## File: facebookresearch_audiocraft/tests/data/test_audio.py

Prompts

```
['test the audio_info function to extract sample rate, channels, and duration from audio files', 'test the audio_read function to load full or partial WAV audio segments with seek support', 'test the audio_write function to save audio tensors as WAV or MP3 with peak, clip, or RMS strategies', 'test the _av_read function to seek and read partial audio segments from WAV files', 'test the audio_read function with padding to return fixed-length segments when seeking near file end', 'test _get_audio_meta to extract sample rate, duration, and path from a WAV file', 'test save_audio_meta to write a list of AudioMeta objects to a JSONL file', 'test load_audio_meta to read AudioMeta objects from a JSONL file and verify equality', 'test AudioDataset.from_path to create a dataset from a directory of WAV audio files', 'test AudioDataset.sample_file to sample audio files by weight or duration with a random generator', 'test convert_audio_channels to downmix 3-channel audio to 2-channel stereo output', 'test convert_audio to resample audio from one sample rate to another', 'test normalize_audio with peak strategy to clip audio values to valid range', 'test normalize_audio with rms strategy to normalize audio by root-mean-square energy', 'test f32_pcm and i16_pcm functions to convert between float32 and int16 audio formats']
```

Usage

```
{'test_audio_info': 'test the audio_info function to extract sample rate, channels, and duration from audio files', 'test_audio_read': 'test the audio_read function to load full or partial WAV audio segments with seek support', 'test_audio_write': 'test the audio_write function to save audio tensors as WAV or MP3 with peak, clip, or RMS strategies', 'test_av_read': 'test the _av_read function to seek and read partial audio segments from WAV files', 'test_audio_read_padded': 'test the audio_read function with padding to return fixed-length segments when seeking near file end'}
```

## File: facebookresearch_audiocraft/tests/data/test_audio_dataset.py

Prompts

```
['test the audio_info function to extract sample rate, channels, and duration from audio files', 'test the audio_read function to load full or partial WAV audio segments with seek support', 'test the audio_write function to save audio tensors as WAV or MP3 with peak, clip, or RMS strategies', 'test the _av_read function to seek and read partial audio segments from WAV files', 'test the audio_read function with padding to return fixed-length segments when seeking near file end', 'test _get_audio_meta to extract sample rate, duration, and path from a WAV file', 'test save_audio_meta to write a list of AudioMeta objects to a JSONL file', 'test load_audio_meta to read AudioMeta objects from a JSONL file and verify equality', 'test AudioDataset.from_path to create a dataset from a directory of WAV audio files', 'test AudioDataset.sample_file to sample audio files by weight or duration with a random generator', 'test convert_audio_channels to downmix 3-channel audio to 2-channel stereo output', 'test convert_audio to resample audio from one sample rate to another', 'test normalize_audio with peak strategy to clip audio values to valid range', 'test normalize_audio with rms strategy to normalize audio by root-mean-square energy', 'test f32_pcm and i16_pcm functions to convert between float32 and int16 audio formats']
```

Usage

```
{'test_get_audio_meta': 'test _get_audio_meta to extract sample rate, duration, and path from a WAV file', 'test_save_audio_meta': 'test save_audio_meta to write a list of AudioMeta objects to a JSONL file', 'test_load_audio_meta': 'test load_audio_meta to read AudioMeta objects from a JSONL file and verify equality', 'test_audio_dataset_from_path': 'test AudioDataset.from_path to create a dataset from a directory of WAV audio files', 'test_audio_dataset_sample_file': 'test AudioDataset.sample_file to sample audio files by weight or duration with a random generator'}
```

## File: facebookresearch_audiocraft/tests/data/test_audio_utils.py

Prompts

```
['test the audio_info function to extract sample rate, channels, and duration from audio files', 'test the audio_read function to load full or partial WAV audio segments with seek support', 'test the audio_write function to save audio tensors as WAV or MP3 with peak, clip, or RMS strategies', 'test the _av_read function to seek and read partial audio segments from WAV files', 'test the audio_read function with padding to return fixed-length segments when seeking near file end', 'test _get_audio_meta to extract sample rate, duration, and path from a WAV file', 'test save_audio_meta to write a list of AudioMeta objects to a JSONL file', 'test load_audio_meta to read AudioMeta objects from a JSONL file and verify equality', 'test AudioDataset.from_path to create a dataset from a directory of WAV audio files', 'test AudioDataset.sample_file to sample audio files by weight or duration with a random generator', 'test convert_audio_channels to downmix 3-channel audio to 2-channel stereo output', 'test convert_audio to resample audio from one sample rate to another', 'test normalize_audio with peak strategy to clip audio values to valid range', 'test normalize_audio with rms strategy to normalize audio by root-mean-square energy', 'test f32_pcm and i16_pcm functions to convert between float32 and int16 audio formats']
```

Usage

```
{'test_convert_audio_channels': 'test convert_audio_channels to downmix 3-channel audio to 2-channel stereo output', 'test_convert_audio_resample': 'test convert_audio to resample audio from one sample rate to another', 'test_normalize_audio_peak': 'test normalize_audio with peak strategy to clip audio values to valid range', 'test_normalize_audio_rms': 'test normalize_audio with rms strategy to normalize audio by root-mean-square energy', 'test_pcm_conversion': 'test f32_pcm and i16_pcm functions to convert between float32 and int16 audio formats'}
```

