# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/audio_diffusion/mel.py

Prompts

```
['create a Mel spectrogram image from an audio file using the Mel class', 'convert a spectrogram PIL image back to audio using the Mel class image_to_audio method', 'load an audio file or raw NumPy array into the Mel class for processing', 'get a specific slice of loaded audio by index using the Mel class', 'set the x and y resolution of the Mel spectrogram using set_resolution', 'run the AudioDiffusionPipeline to generate audio samples from noise using DDIM or DDPM scheduler', 'run the AudioDiffusionPipeline with raw audio input and mask start and end seconds for inpainting', 'encode a list of PIL images into a noise tensor using the reverse denoising process', 'interpolate between two tensors using spherical linear interpolation with a given alpha value', 'get the default number of denoising steps based on whether the scheduler is DDIM or DDPM']
```

Usage

```
{'create_mel_spectrogram_from_audio': 'create a Mel spectrogram image from an audio file using the Mel class', 'convert_spectrogram_image_to_audio': 'convert a spectrogram PIL image back to audio using the Mel class image_to_audio method', 'load_audio_file_or_array': 'load an audio file or raw NumPy array into the Mel class for processing', 'get_audio_slice_by_index': 'get a specific slice of loaded audio by index using the Mel class', 'set_mel_spectrogram_resolution': 'set the x and y resolution of the Mel spectrogram using set_resolution'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/audio_diffusion/pipeline_audio_diffusion.py

Prompts

```
['create a Mel spectrogram image from an audio file using the Mel class', 'convert a spectrogram PIL image back to audio using the Mel class image_to_audio method', 'load an audio file or raw NumPy array into the Mel class for processing', 'get a specific slice of loaded audio by index using the Mel class', 'set the x and y resolution of the Mel spectrogram using set_resolution', 'run the AudioDiffusionPipeline to generate audio samples from noise using DDIM or DDPM scheduler', 'run the AudioDiffusionPipeline with raw audio input and mask start and end seconds for inpainting', 'encode a list of PIL images into a noise tensor using the reverse denoising process', 'interpolate between two tensors using spherical linear interpolation with a given alpha value', 'get the default number of denoising steps based on whether the scheduler is DDIM or DDPM']
```

Usage

```
{'run_audio_diffusion_pipeline': 'run the AudioDiffusionPipeline to generate audio samples from noise using DDIM or DDPM scheduler', 'run_audio_diffusion_with_masking': 'run the AudioDiffusionPipeline with raw audio input and mask start and end seconds for inpainting', 'encode_images_to_noise': 'encode a list of PIL images into a noise tensor using the reverse denoising process', 'interpolate_tensors_with_slerp': 'interpolate between two tensors using spherical linear interpolation with a given alpha value', 'get_default_steps': 'get the default number of denoising steps based on whether the scheduler is DDIM or DDPM'}
```

