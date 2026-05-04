# Agent Python Tools

- repo: facebookresearch/ImageBind
- repo_uri: https://github.com/facebookresearch/ImageBind.git

## File: facebookresearch_ImageBind/imagebind/data.py

Prompts

```
['load image files from paths and transform them into normalized tensors for ImageBind model input', 'tokenize text strings using BPE tokenizer and return tensors for ImageBind multimodal model input', 'load audio files and convert waveforms to mel spectrogram tensors for ImageBind model input', 'load video files and extract transformed spatial crop clips as tensors for ImageBind model input', 'convert an audio waveform tensor into a mel spectrogram tensor with padding and truncation']
```

Usage

```
{'load_and_transform_vision_data': 'load image files from paths and transform them into normalized tensors for ImageBind model input', 'load_and_transform_text': 'tokenize text strings using BPE tokenizer and return tensors for ImageBind multimodal model input', 'load_and_transform_audio_data': 'load audio files and convert waveforms to mel spectrogram tensors for ImageBind model input', 'load_and_transform_video_data': 'load video files and extract transformed spatial crop clips as tensors for ImageBind model input', 'waveform2melspec': 'convert an audio waveform tensor into a mel spectrogram tensor with padding and truncation'}
```

