# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/speech_synthesis/preprocessing/denoiser/demucs.py

Prompts

```
['build a Demucs speech enhancement model with configurable depth, hidden channels, and kernel size', 'run the Demucs model on a waveform tensor to enhance speech and remove noise', 'create a DemucsStreamer for real-time streaming speech enhancement with configurable dry signal mixing', 'test the Demucs streaming implementation against the offline batch model and benchmark RTF', 'review the BLSTM bidirectional LSTM wrapper class with optional linear projection layer', 'use get_model with default args to load the pre-trained DNS H=48 denoiser model', 'use get_model with dns64 flag to load the pre-trained DNS H=64 denoiser model', 'use get_model with master64 flag to load the pre-trained DNS and Valentini H=64 model', 'use get_model with model_path arg to load a local trained denoiser model package', 'use add_model_flags to add mutually exclusive model selection arguments to an argparse parser', 'upsample a PyTorch audio tensor by 2x using sinc interpolation with a Hann-windowed kernel', 'downsample a PyTorch audio tensor by 2x using sinc interpolation with a Hann-windowed kernel', 'create a Hann-windowed sinc interpolation kernel for upsampling audio signals by a factor of 2', 'create a Hann-windowed sinc interpolation kernel for downsampling audio signals by a factor of 2', 'compute the sinc function on a PyTorch tensor, handling the t equals 0 edge case', 'deserialize a PyTorch model from a serialized package dict with optional strict mode', 'serialize a PyTorch model with captured init args and state dict into a package dict', "temporarily swap a model's state dict within a context manager and restore on exit", 'calculate the signal-to-noise ratio between label and estimated PyTorch tensors', 'wrap an iterable with LogProgress to log periodic progress updates with speed metrics']
```

Usage

```
{'build_demucs_model': 'build a Demucs speech enhancement model with configurable depth, hidden channels, and kernel size', 'run_demucs_inference': 'run the Demucs model on a waveform tensor to enhance speech and remove noise', 'create_demucs_streamer': 'create a DemucsStreamer for real-time streaming speech enhancement with configurable dry signal mixing', 'test_demucs_streaming': 'test the Demucs streaming implementation against the offline batch model and benchmark RTF', 'review_blstm': 'review the BLSTM bidirectional LSTM wrapper class with optional linear projection layer'}
```

## File: facebookresearch_fairseq/examples/speech_synthesis/preprocessing/denoiser/pretrained.py

Prompts

```
['build a Demucs speech enhancement model with configurable depth, hidden channels, and kernel size', 'run the Demucs model on a waveform tensor to enhance speech and remove noise', 'create a DemucsStreamer for real-time streaming speech enhancement with configurable dry signal mixing', 'test the Demucs streaming implementation against the offline batch model and benchmark RTF', 'review the BLSTM bidirectional LSTM wrapper class with optional linear projection layer', 'use get_model with default args to load the pre-trained DNS H=48 denoiser model', 'use get_model with dns64 flag to load the pre-trained DNS H=64 denoiser model', 'use get_model with master64 flag to load the pre-trained DNS and Valentini H=64 model', 'use get_model with model_path arg to load a local trained denoiser model package', 'use add_model_flags to add mutually exclusive model selection arguments to an argparse parser', 'upsample a PyTorch audio tensor by 2x using sinc interpolation with a Hann-windowed kernel', 'downsample a PyTorch audio tensor by 2x using sinc interpolation with a Hann-windowed kernel', 'create a Hann-windowed sinc interpolation kernel for upsampling audio signals by a factor of 2', 'create a Hann-windowed sinc interpolation kernel for downsampling audio signals by a factor of 2', 'compute the sinc function on a PyTorch tensor, handling the t equals 0 edge case', 'deserialize a PyTorch model from a serialized package dict with optional strict mode', 'serialize a PyTorch model with captured init args and state dict into a package dict', "temporarily swap a model's state dict within a context manager and restore on exit", 'calculate the signal-to-noise ratio between label and estimated PyTorch tensors', 'wrap an iterable with LogProgress to log periodic progress updates with speed metrics']
```

Usage

```
{'get_model_dns48': 'use get_model with default args to load the pre-trained DNS H=48 denoiser model', 'get_model_dns64': 'use get_model with dns64 flag to load the pre-trained DNS H=64 denoiser model', 'get_model_master64': 'use get_model with master64 flag to load the pre-trained DNS and Valentini H=64 model', 'get_model_local': 'use get_model with model_path arg to load a local trained denoiser model package', 'add_model_flags': 'use add_model_flags to add mutually exclusive model selection arguments to an argparse parser'}
```

## File: facebookresearch_fairseq/examples/speech_synthesis/preprocessing/denoiser/resample.py

Prompts

```
['build a Demucs speech enhancement model with configurable depth, hidden channels, and kernel size', 'run the Demucs model on a waveform tensor to enhance speech and remove noise', 'create a DemucsStreamer for real-time streaming speech enhancement with configurable dry signal mixing', 'test the Demucs streaming implementation against the offline batch model and benchmark RTF', 'review the BLSTM bidirectional LSTM wrapper class with optional linear projection layer', 'use get_model with default args to load the pre-trained DNS H=48 denoiser model', 'use get_model with dns64 flag to load the pre-trained DNS H=64 denoiser model', 'use get_model with master64 flag to load the pre-trained DNS and Valentini H=64 model', 'use get_model with model_path arg to load a local trained denoiser model package', 'use add_model_flags to add mutually exclusive model selection arguments to an argparse parser', 'upsample a PyTorch audio tensor by 2x using sinc interpolation with a Hann-windowed kernel', 'downsample a PyTorch audio tensor by 2x using sinc interpolation with a Hann-windowed kernel', 'create a Hann-windowed sinc interpolation kernel for upsampling audio signals by a factor of 2', 'create a Hann-windowed sinc interpolation kernel for downsampling audio signals by a factor of 2', 'compute the sinc function on a PyTorch tensor, handling the t equals 0 edge case', 'deserialize a PyTorch model from a serialized package dict with optional strict mode', 'serialize a PyTorch model with captured init args and state dict into a package dict', "temporarily swap a model's state dict within a context manager and restore on exit", 'calculate the signal-to-noise ratio between label and estimated PyTorch tensors', 'wrap an iterable with LogProgress to log periodic progress updates with speed metrics']
```

Usage

```
{'upsample2_audio_tensor': 'upsample a PyTorch audio tensor by 2x using sinc interpolation with a Hann-windowed kernel', 'downsample2_audio_tensor': 'downsample a PyTorch audio tensor by 2x using sinc interpolation with a Hann-windowed kernel', 'kernel_upsample2_create': 'create a Hann-windowed sinc interpolation kernel for upsampling audio signals by a factor of 2', 'kernel_downsample2_create': 'create a Hann-windowed sinc interpolation kernel for downsampling audio signals by a factor of 2', 'sinc_compute': 'compute the sinc function on a PyTorch tensor, handling the t equals 0 edge case'}
```

## File: facebookresearch_fairseq/examples/speech_synthesis/preprocessing/denoiser/utils.py

Prompts

```
['build a Demucs speech enhancement model with configurable depth, hidden channels, and kernel size', 'run the Demucs model on a waveform tensor to enhance speech and remove noise', 'create a DemucsStreamer for real-time streaming speech enhancement with configurable dry signal mixing', 'test the Demucs streaming implementation against the offline batch model and benchmark RTF', 'review the BLSTM bidirectional LSTM wrapper class with optional linear projection layer', 'use get_model with default args to load the pre-trained DNS H=48 denoiser model', 'use get_model with dns64 flag to load the pre-trained DNS H=64 denoiser model', 'use get_model with master64 flag to load the pre-trained DNS and Valentini H=64 model', 'use get_model with model_path arg to load a local trained denoiser model package', 'use add_model_flags to add mutually exclusive model selection arguments to an argparse parser', 'upsample a PyTorch audio tensor by 2x using sinc interpolation with a Hann-windowed kernel', 'downsample a PyTorch audio tensor by 2x using sinc interpolation with a Hann-windowed kernel', 'create a Hann-windowed sinc interpolation kernel for upsampling audio signals by a factor of 2', 'create a Hann-windowed sinc interpolation kernel for downsampling audio signals by a factor of 2', 'compute the sinc function on a PyTorch tensor, handling the t equals 0 edge case', 'deserialize a PyTorch model from a serialized package dict with optional strict mode', 'serialize a PyTorch model with captured init args and state dict into a package dict', "temporarily swap a model's state dict within a context manager and restore on exit", 'calculate the signal-to-noise ratio between label and estimated PyTorch tensors', 'wrap an iterable with LogProgress to log periodic progress updates with speed metrics']
```

Usage

```
{'deserialize_model_from_package': 'deserialize a PyTorch model from a serialized package dict with optional strict mode', 'serialize_model_to_package': 'serialize a PyTorch model with captured init args and state dict into a package dict', 'swap_model_state_temporarily': "temporarily swap a model's state dict within a context manager and restore on exit", 'calculate_snr_between_tensors': 'calculate the signal-to-noise ratio between label and estimated PyTorch tensors', 'wrap_iterable_with_logprogress': 'wrap an iterable with LogProgress to log periodic progress updates with speed metrics'}
```

