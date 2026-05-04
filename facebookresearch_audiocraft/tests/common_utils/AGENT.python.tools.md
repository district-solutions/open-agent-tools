# Agent Python Tools

- repo: facebookresearch/audiocraft
- repo_uri: https://github.com/facebookresearch/audiocraft.git

## File: facebookresearch_audiocraft/tests/common_utils/temp_utils.py

Prompts

```
['create a test class that inherits TempDirMixin to get easy access to temporary directories', 'get the base temporary directory path using the get_base_temp_dir class method', 'get a temporary file path by calling get_temp_path with relative path components', 'get a temporary directory path by calling get_temp_dir with relative path components', 'clean up temporary directories by calling tearDownClass after test completion', 'generate a random white noise tensor with specified channels and frame count using PyTorch', 'generate a batch of random white noise tensors with specified batch size, channels, and frames', 'save a 2D audio tensor to disk as a WAV, MP3, OGG, or FLAC file with clipping strategy', 'test the get_white_noise function by generating random audio tensors with varying channel and frame counts', 'refactor the save_wav function to support additional audio formats or normalization strategies']
```

Usage

```
{'create_temp_dir_mixin': 'create a test class that inherits TempDirMixin to get easy access to temporary directories', 'get_base_temp_dir': 'get the base temporary directory path using the get_base_temp_dir class method', 'get_temp_path': 'get a temporary file path by calling get_temp_path with relative path components', 'get_temp_dir': 'get a temporary directory path by calling get_temp_dir with relative path components', 'tear_down_temp_dir': 'clean up temporary directories by calling tearDownClass after test completion'}
```

## File: facebookresearch_audiocraft/tests/common_utils/wav_utils.py

Prompts

```
['create a test class that inherits TempDirMixin to get easy access to temporary directories', 'get the base temporary directory path using the get_base_temp_dir class method', 'get a temporary file path by calling get_temp_path with relative path components', 'get a temporary directory path by calling get_temp_dir with relative path components', 'clean up temporary directories by calling tearDownClass after test completion', 'generate a random white noise tensor with specified channels and frame count using PyTorch', 'generate a batch of random white noise tensors with specified batch size, channels, and frames', 'save a 2D audio tensor to disk as a WAV, MP3, OGG, or FLAC file with clipping strategy', 'test the get_white_noise function by generating random audio tensors with varying channel and frame counts', 'refactor the save_wav function to support additional audio formats or normalization strategies']
```

Usage

```
{'get_white_noise': 'generate a random white noise tensor with specified channels and frame count using PyTorch', 'get_batch_white_noise': 'generate a batch of random white noise tensors with specified batch size, channels, and frames', 'save_wav': 'save a 2D audio tensor to disk as a WAV, MP3, OGG, or FLAC file with clipping strategy', 'test_get_white_noise': 'test the get_white_noise function by generating random audio tensors with varying channel and frame counts', 'refactor_save_wav': 'refactor the save_wav function to support additional audio formats or normalization strategies'}
```

